![image](https://github.com/user-attachments/assets/f4a86f09-09b8-4ab5-870b-a2de3c588e6f)
# Virtual Networks and Virtual Machines


# Prerequisites:
-Microsoft Account

-Azure account made through the Azure Portal, using your Microsoft credentials

-Connection to Internet


# Creating Your Resource Group

This is the Azure Portal Home Screen. In the search bar, search for the Resource Groups, the icon looks like this:

![image](https://github.com/user-attachments/assets/4f7a541e-bfe2-40d0-b081-ca71c51b5045)


A resource group in Azure is a container that organizes and manages related resources like virtual machines, storage, and applications.

When you go to Resource Groups, in the top left it will say "Create Resource Group" and this page will come up. Use your subscription you used to set up your Azure account, name your gruop, and then selectyour region.

![image](https://github.com/user-attachments/assets/5ee0f022-4278-4e23-9411-6a813d43f9e5)

After you set up your subscription, name, and region, click through review and create.
![image](https://github.com/user-attachments/assets/54074f5f-2776-48e7-a838-fc03382e5c80)



# Creating Your Virtual Network

Go back to the Azure hompage and search for Virtual Networks, or click the icon at the top toolbar. It will look like this, click create.

![image](https://github.com/user-attachments/assets/a2ac2053-9e1c-4ed6-8129-04a984c755be)


Next it will bring you here, make sure the Resource Group that the Virtual Network is connected to is the same one you just created. Name your network whatever you would like. Then clickthrough to review and create.
![image](https://github.com/user-attachments/assets/86695987-790e-4489-bef7-aed3e56c4eca)


To make sure this is done correctly, go to the Azure homepage, go to Resource Groups, click the one that was just made, and you should see the Virtual Network is within the Resource Group. 
![image](https://github.com/user-attachments/assets/7e9a3965-f3b6-47f0-b75f-16c88abafa47)

# Virtual Machine Creation

Same as before, search for Virtual Machines in the Azure search bar, or click it on the toolbar.

![image](https://github.com/user-attachments/assets/5b34703c-b046-4e35-baff-7f5ddc77342b)

Click Create Azure Virtual Machine, and ensure you have the correct Resource Group selected. Name your VM whatever you want.
![image](https://github.com/user-attachments/assets/d0332a51-d6db-45cf-acb5-b10d7857c850)

![image](https://github.com/user-attachments/assets/846e72e2-7f21-4e58-bf7d-307a219b9d81)

Next select your image, this is the Operating System that will be running. All other settings shown in the picture do not get changed. For this tutorial, I will be using this Operating System and size:
![image](https://github.com/user-attachments/assets/badf6bef-e65f-40b7-9290-9a8b1edfc28d)

For this demo, I will be using account name labuser and the password is Password1234!. In real time, this username and password combination would not be an option, but is appropriate for the demo.
![image](https://github.com/user-attachments/assets/3f08cfc0-159a-41f6-9a74-9b8597567870)


Be sure to check the box at the bottom of the page or it will cause an error at the end!

![image](https://github.com/user-attachments/assets/655de003-d27b-4c1c-9a58-399990fd6cd1)

Click next which will bring you to Disks. Click Next again and it will bring you to Networking. Set the Virtual Network to the same one we created earlier.
![image](https://github.com/user-attachments/assets/41dfd4ed-32e3-4fb2-96f4-595fc5224b95)

Click through to Review and Create and wait for the deployment to finish. Once deployment is finished, go to Resource Groups and click on the one that we created for our network and machines. If done correctly, it will look like this, with everything needed for our virtual network and virtual machine contained in the same Resource Group:

![image](https://github.com/user-attachments/assets/9606fbcf-7253-4be3-a7de-6783e6c6a3d7)

This demonstration is now complete. This tutorial explained how to configure a Virtual Network and Virtual Machines in Microsoft Azure. We are able to add more machines to the network by following the same steps used above, and both VM's would be on the same Virtual Network!







