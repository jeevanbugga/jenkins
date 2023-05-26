__Requirement__
--------------------------------------
Client:  #default value invest <br>
region:   #default value us-east-1 <br>
version_number: <br>
aws_account:  #list- prod,dev<br>
cluster name: __show list based on aws_account__<br>
    - if dev is selected<br>
    --invest-cluster<br>
    --investbvt-cluster<br>
    --investnonprod-cluster<br>
    - if prod is selected<br>
    --investprod-cluster<br>
