
# DevOps Useful Scripts

This repository contains some Scripts in bash or puthon that can be Useful for a DevOps activities on the field.



## ip_address_update.sh

When you stop and start an ec2 instance, you will have a new public IP assigned to the instance if any Elastic IP Address is not configured. In addition, sometimes the instance becomes too slow. You are called to change manually the Public Address in the corresponding file to fix this issue, and, restart the service.

This bash script allows you to automatically change the Jenkins Server IP Address and restart the service.
To deploy this project run

```bash
  sh ip_address_update.sh <Your_Jenkins_Instance_Name>
```
Example

```bash
  sh ip_address_update.sh Jenkins-Server
```
## Feedback

If you have any feedback, please reach out to us at jddbetambo@gmail.com

