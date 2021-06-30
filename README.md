# K8_cluster_Ansible_AWS
K8 cluster on AWS using Ansible.

<h3>Here I configure the kubernetes cluster on the AWS using Ansible</h3>




<h4>File Require</h4>
1.In This we Require the .pem file to login to IAM.

2.Require the file containing the Access key and Seceret key which can be secure by using Ansible Vault.
 
 ``` ansible-vault create --init-password-file = <file name> <vault name>  ```
 
 <h3>Software require</h3>
 1. Ansible.

 2. boto.

 3. boto3 ,ec2
 
 In this we use dynamic inventory update approach so we dont require to add ip of Master and slave inventory it will directly add in the Inventory.
 
 
