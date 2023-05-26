__Requirement__
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
