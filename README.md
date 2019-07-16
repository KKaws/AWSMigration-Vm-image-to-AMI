# AWSMigration-Vm-image-to-AMI
How to Install Ubuntu Server 18.04 LTS in VirtualBox
Installing Ubuntu Server 18.04 LTS in VirtualBox.
This tutorial assumes that you have already downloaded the Ubuntu Server 18.04 LTS iso image from the Ubuntu website. This tutorial also assumes that VirtualBox is already installed and configured on your current system.
1.	Open VirtualBox Manager and click the ‘New’ button at the top-left of the window.

![](https://github.com/KKaws/AWSMigration-Vm-image-to-AMI/blob/master/1.png)

2.	In the pop-up dialog that appears, give your virtual machine a descriptive name. Then select ‘Linux’ in the Type field and ‘Ubuntu (64-bit)’ in the Version field.


![](https://github.com/KKaws/AWSMigration-Vm-image-to-AMI/blob/master/2.png)

3.	Click the ‘Next >’ button to proceed. Select the amount of RAM that you want to allocate to your new virtual machine. Since Ubuntu Server is so light on resources, 1 GB (1024 MB) will be just fine for this tutorial.

![](https://github.com/KKaws/AWSMigration-Vm-image-to-AMI/blob/master/3.png)

4.	Click the ‘Next >’ button. Select the option to create a virtual hard disk and click the ‘Create’ button to create the virtual hard disk for the new virtual machine.
![](https://github.com/KKaws/AWSMigration-Vm-image-to-AMI/blob/master/4.png)
5.	Select ‘VDI (VirtualBox Disk Image) as the hard disk file type and click the ‘Next >’ button to proceed.
![](https://github.com/KKaws/AWSMigration-Vm-image-to-AMI/blob/master/5.png)
6.	Select the option to dynamically allocate the storage on the physical hard disk and click the ‘Next >’ button to continue.
![](https://github.com/KKaws/AWSMigration-Vm-image-to-AMI/blob/master/6.png)

7.	Finally, select the location to save your new virtual machine to and select the amount of hard disk space to allocate to your new virtual machine. For this tutorial, 20 GB of disk space will suffice.
![](https://github.com/KKaws/AWSMigration-Vm-image-to-AMI/blob/master/7.png)

8.	Click the ‘Create’ button to finish the initial configuration of the new virtual machine. The pop-up dialog will close and we can begin to install Ubuntu Server 18.04 LTS. Click on your new virtual machine in the left pane of VirtualBox Manager and highlight it, then click the ‘Start’ button on the top-left of the window.
![]()
9. In the new pop-up dialog, we must select the Ubuntu Server 18.04 LTS iso that we downloaded from the Ubuntu website. Click the folder icon, navigate to the iso, then click the ‘Start’ button to begin the installation.
![]()
10. The Ubuntu Server 18.04 LTS Installation launches and we must select our language to continue.
