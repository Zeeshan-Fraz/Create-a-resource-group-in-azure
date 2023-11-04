<h1> How to create a resource group in azure</h1>

<br />


<p align="center">
Created Resouce Group in Azure: <br/>
<img src="https://i.imgur.com/yrwFL7g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

You may be asking why should I create a resource group first and why not the virtual machine right away.
This is because in Azure we will be creating a lot of resources and from my experience it is easier to setup a new resource group as this will make it a lot easier later in this lab.

To create a new resource group, click on the resource groups button

<br />

<p align="center">
<img src="https://i.imgur.com/hFqBqXC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click on the resource group button to create your resource group

By default, there will be no resource groups and we will have to create one for this lab.

<br />

Click on the create resource group button and you will be presented with the project details and resource details field that need to be filled in.
NOTE: the default subscription will always be Azure subscription 1 with the free Azure sign up

<p align="center">
<img src="https://i.imgur.com/X6ThREN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br /> 

As I will be using my virtual machine for a honeypot scenario, I have called mine Honeypot-Lab, but you can name your resource group to any name as you wish. anything of your choice.

<p align="center">
<img src="https://i.imgur.com/ebTE1a1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br /> 

NOTE: in the region settings, by default it will be set to (US) EAST US, this is the region where we want to deploy our resource group to a region where the data centre is situated. I set mine to (Europe) UK South as this was the recommended option for myself for the region, I am in.
Then click the review + create button and your new resource group should be created:

<p align="center">
<img src="https://i.imgur.com/lv1mAgM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br /> 

You should see a pop up box in the top right hand corner of the Azure portal to show if the resource group has been successfully created.
NOTE: you will see a lot of these dialogue boxes appear to show the deployment status of resources and alerts in the Azure portal.

<p align="center">
<img src="https://i.imgur.com/Ijsi3vM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
