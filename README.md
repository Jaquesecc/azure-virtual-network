![image](https://github.com/user-attachments/assets/f4a86f09-09b8-4ab5-870b-a2de3c588e6f)
# Virtual Networks and Virtual Machines


# Prerequisites:
-Microsoft Account

-Azure account made through the Azure Portal, using your Microsoft credentials

-Connection to Internet


# Creating Your Resource Group

This is the Azure Portal Home Screen. In the search bar, search for the Resource Groups, the icon looks like this:

! [image]
! [image]

A resource group in Azure is a container that organizes and manages related resources like virtual machines, storage, and applications

When you go to Resource Groups, in the top left it will say "Create Resource Group" and this page will come up. Use your subscription you used to set up your Azure account, name your gruop, and then selectyour region.
! [image]

After you set up your subscription, name, and region, click through review and create.
! [image]

# Creating Your Virtual Network

Go back to the Azure hompage and search for Virtual Networks, or click the icon at the top toolbar. It will look like this, click create.

! [image]

Next it will bring you here, make sure the Resource Group that the Virtual Network is connected to is the same one you just created. Name your network whatever you would like. Then clickthrough to review and create.
! [image]

To make sure this is done correctly, go to the Azure homepage, go to Resource Groups, click the one that was just made, and you should see the Virtual Network is within the Resource Group. 
![image]

# Virtual Machine Creation

Same as before, search for Virtual Machines in the Azure search bar, or click it on the toolbar.

![image]

Click Create Azure Virtual Machine and ensure you have the correct Resource Groupselected. Name your VM whatever you want.
! [image]
! [image]

Next select your image, this is the OS the machine that will be running. All other settings shown in picture do not getchange. For this demonstration, I will be using this OS and size:
! [image]

For the demo, I will be using account name user123 and the password is Password1234.In real time, this username and password combination would not be an option, but is appropriate for the demo.
![iamge]

Be sure to check the box at the bottom of the page asit will not work if you do not check it!

![image]

Click next which will bring you to Disks. Click Next again and it will bring you to Networking. Set the Virtual Network to the same one we created earlier.
![image]

Click through to REview and Create and wait for the deployment to finish. once deployment is finished, go to Resource Groups and click on the one that we created for our network and machines. If done successfully, it will look like this, with everything needed for our virtual network and virtual machine contained in the same Resource Group:

![image]

This demonstration is now complete. This displayed how to configure a Virtual Network and Virtual Machines in Azure. We are able to add more machines to the network by following the same steps used above, and both VM's would be on the same Virtual Network!







