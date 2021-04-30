# ansible_aws-instance-launch_n-update-inventory <br/>
- For this, you need to add the details such as key-pair name, imageid, security group, vpc, instance type etc n other details in vars/main.yml. <br/>
- install **boto** library in your controller node to contact with AWS.<br/>
##### pip3 install boto

For dynamic updation of inventory you need to export the access key and secret key <br/>
##### export AWS_ACCESS_KEY_ID='AK123' <br/>
##### export AWS_SECRET_ACCESS_KEY='abc123' <br/>
<center>or</center>
add access key n secret key in **ec2.ini** file


            
