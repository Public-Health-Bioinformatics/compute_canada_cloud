# How to use Compute Canada cloud

## Cloud Resources
If you do not have a Compute Canada account, create one with these [instructions](https://www.computecanada.ca/research-portal/account-management/apply-for-an-account/). Right now we have projects on these cloud systems:

1. [Cedar cloud](http://cedar.cloud.computecanada.ca)
2. [Arbutus cloud](http://arbutus.cloud.computecanada.ca)

You can use Compute Canada (CCDB) username (not your email address) to log in.

## How to create a VM instance
1. Generate SSH keys

When you create a virtual machine, password authentication is disabled for security reasons. Instead, OpenStack creates your VM with one SSH (Secure Shell) public key installed, and you can only log in using this SSH key pair. If you have used SSH keys before, the SSH public key can come from a key pair which you have already created on some other machine. You can import an existing key pair. If you have not used SSH key pairs before or don't currently have a pair you want to use, you will need to create a key pair. 

* [Generate SSH keys in Windows](https://docs.computecanada.ca/wiki/Generating_SSH_keys_in_Windows/en)
* [Generate SSH keys in Linux/MAC](https://docs.computecanada.ca/wiki/Using_SSH_keys_in_Linux) 

2. Launching a VM

Reference: [https://docs.computecanada.ca/wiki/Cloud_Quick_Start](https://docs.computecanada.ca/wiki/Cloud_Quick_Start)
