## Documentation for Project 1

Before launching the Ubuntu virtual machine we need to install some dependencies on our local machine 

- [Install OpenSSH](https://learn.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse?tabs=powershell#tabpanel_1_powershell)

- [OpenSSH Key Management](https://learn.microsoft.com/en-us/windows-server/administration/openssh/openssh_keymanagement#user-key-generation)


After launching the Ubuntu Virtual machine on AWS Account, Update it using;

**`sudo apt update`**

After the update is completed, following the instruction fromt the task assigned

Install Apache using Ubuntu’s package manager ‘apt’:

**`sudo apt install apache2`**

To verify that apache2 is running as a Service in our OS, use following command:

**`sudo systemctl status apache2`**

Below is the outcome of the apache status, which shows it is running and active

![Apache status](./Images/Apache2%20status.PNG)