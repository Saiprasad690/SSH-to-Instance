# SSH-to-Instance
Create an ec2 with pem keys and open the terminal
ssh -i path to the keys and IP of instances
```
ssh -i user\downloads\aws-key.pem ubuntu@instance_ip_adress
```
if permission is denied change the permission
```
chmod 600 path of the key
```
And then try to ssh again

# OR
Go to the path of the key and open the cmd in the path and 
```
ssh -i key-name.pem ubuntu@123.456.789
```
