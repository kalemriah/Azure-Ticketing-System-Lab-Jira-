# Azure-Ticketing-System-Lab-Jira-
Microsoft Azure VM running Jira ticketing system lab to further skill sets

<h2>Prerequisites </h2> -Windows Remote Access Connection, or another application to use remote access protocol & a Microsfot Azure account. <br/>
<h2>Steps</h2>
<p align="center">
  <b>1.)Creating Microsoft Azure Account</b><br/>
<p align="left">
-Create a free trial account for azure. You will get $200 free credit.<br/>
<p align="center">
  <b>2.)Creating New Resource Group</b><br/>
<p align="left">
-Once logged in, redirect to the Home portal for Microsoft Azure. Under 'Azure services' select 'Resources Groups'. Select 'Create a resource'. Name your resource group whatever you'd like, I named mine "VMs”. Select 'Review + Create'. Once created, redirect back to the Home portal.<br/>
<p align="center">
  <b>3.)Creating Azure VM (Windows Server Database 2022)</b><br/>
<p align="left">
-Start in the Azure Home portal. Under 'Azure services' Select 'Virtual Machines', select 'create'. Under the 'Basics' tab select the resources group you've just created in the previous step. Under 'Instance details', name your virtual machine, I'll be naming mine "WorkLab ''. Select the region corresponding to the resource group region you previously created. Under 'Image' select 'Windows Server 2022 Datacenter'. Scroll down and select the size you would like, I selected the 'Standard_D2s_v3' option. Under 'Administrator account' create your user name and password. *IMPORTANT* Leave RDP 3389 (Remote Desktop Protocol) open to access your VM later. (optional) Go through other tabs and review, this is completely optional. Select 'Review + create' and wait for the VM to be created.<br/>
<p align="center">
  <b>4.)Start up Azure VM</b><br/>
<p align="left">
-Redirect back to Azure Home portal. Under 'Azure services' select 'Virtual machines'. Now the VM you just created should be there. Hover your mouse over the name of your VM under the 'Names' tab. A pop-up will appear and you will have the options of 'View', 'Start', 'Restart', and details of the machine below. Select 'Start' and your machine will be up. Remain on the 'Virtual machines' page for the next step<br/>
<p align="center">
  <b>5.)Connect to Azure VM using Remote Desktop Connection</b><br/>
<p align="left">
-On the taskbar of your pc type 'Remote Desktop Connection' and open the application. Under the 'Computer' option, type the IP of the Azure VM you created. This can be found on the 'Virtual machines' service under the 'Public IP address' tab. Once typed in, select connect and login to your account. Congratulations you're now accessing your own Azure VM desktop!<br/>
<p align="center">
  <b>6.)Open up Microsoft Edge and install Jira application</b><br/>
<p align="left">
-Select the Windows icon on the bottom left of your screen and select 'Microsoft edge'. Search up 'Jira' and select the web link "https://www.atlassian.com/software/jira". <br/>
<p align="center">
  <b>7.)Create Jira account and login</b><br/>
<p align="center">
  <b>8.)Learn Jira</b><br/> 
<p align="left">
-Enjoying furthering your work skill sets!<br/>
