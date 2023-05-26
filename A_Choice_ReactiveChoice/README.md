__Requirement__<br>
- The main objective of the requirement is to dynamically display variable list based on another variable.In this case cluster names based on the selected AWS account. This can be accomplished using the __Active Choice and Active Choice Reactive parameters__ in Jenkins. Instead of manually configuring these parameters through the Jenkins console, we are leveraging the power of pipeline scripting. By __utilizing the built-in CascadeChoiceParameter class__ within the pipeline script, we are able to achieve the desired functionality.<br>
--------------------------------------
Client:  #default value invest <br>
region:   #default value us-east-1 <br>
version_number: <br>
aws_account:  #list- prod,dev<br>
cluster name: __show list based on aws_account__<br>
    - __if dev is selected from AWS account list__<br>
        --invest-cluster<br>
        --investbvt-cluster<br>
        --investnonprod-cluster<br>
    - __if prod is selected from AWS account list__<br>
         --investprod-cluster<br>
