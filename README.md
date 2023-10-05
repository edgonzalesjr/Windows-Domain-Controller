<h1>Windows Domain Controller</h1>

<h2>Description</h2>
This tutorial is a walk through of setting up of Windows Domain Controller. Visit https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2019 website to download the latest iso.
<br />

<h2>Environment Used</h2>

<b>Windows Server 2019 Standard Evaluation (Note: This evaluation edition expires in 180 days.)</b>
<p align="center">
<img src="https://i.imgur.com/fKXJsL7.png" height="40%" width="40%" alt="Device Specification"/>
<br/>
 
<h2>Program setup:</h2>

<p align="center">
While Server Manager is running, click Add Roles and Features:<br/>
<img src="https://i.imgur.com/9zT9FF6.png" height="70%" width="70%" alt="Run installer"/>
<br />
Click Next button in Before you begin:<br />
<img src="https://i.imgur.com/0GHizEH.png" height="70%" width="70%" alt="Run installer"/>
<br />
Select Role-based or feature-based installation in Installation Type, click Next button:<br />
<img src="https://i.imgur.com/xZqRZuW.png" height="70%" width="70%" alt="Run installer"/>
<br />
Select your Server name in Server Selection, click Next button:<br />
<img src="https://i.imgur.com/QW2dWD2.png" height="70%" width="70%" alt="Run installer"/>
<br />
Tick Active Directory Domain Services and DNS Server in Server Roles, click Next button:<br />
<img src="https://i.imgur.com/TCMhE6T.png" height="70%" width="70%" alt="Run installer"/>
<br />
Leave the default settings in Features, click Next button:<br />
<img src="https://i.imgur.com/VdW3j9p.png" height="70%" width="70%" alt="Run installer"/>
<br />
Leave the default settings in AD DS, click Next button:<br />
<img src="https://i.imgur.com/OYI1e0a.png" height="70%" width="70%" alt="Run installer"/>
<br />
Leave the default settings in DNS Server, click Next button:<br />
<img src="https://i.imgur.com/blHz2JP.png" height="70%" width="70%" alt="Run installer"/>
<br />
Click Install button to confirm installation selections:<br />
<img src="https://i.imgur.com/SG7j2af.png" height="70%" width="70%" alt="Run installer"/>
<br />
Let the Installation progress run:<br />
<img src="https://i.imgur.com/BqshACE.png" height="70%" width="70%" alt="Run installer"/>
<br />
When the installation succeeded, click Promote this server to a domain controller:<br />
<img src="https://i.imgur.com/jaNOtSK.png" height="70%" width="70%" alt="Run installer"/>
<br />
In Deployment Configuration, Click the radio button Add a new forest, Specify and type a desired Root domain name:<br />
<img src="https://i.imgur.com/2E5g4K3.png" height="70%" width="70%" alt="Run installer"/>
<br />
In Domain Controller Options, Specify and type a desired Directory Services Restore Mode Password:<br />
<img src="https://i.imgur.com/WqvnHRw.png" height="70%" width="70%" alt="Run installer"/>
<br />
Leave the default options in DNS Options and click Next button:<br />
<img src="https://i.imgur.com/53P06A4.png" height="70%" width="70%" alt="Run installer"/>
<br />
Leave the default options in Additional Options and click Next button:<br />
<img src="https://i.imgur.com/xvXcYii.png" height="70%" width="70%" alt="Run installer"/>
<br />
Leave the default options in Paths and click Next button:<br />
<img src="https://i.imgur.com/7J7jcHl.png" height="70%" width="70%" alt="Run installer"/>
<br />
Read the Review Options and click Next button:<br />
<img src="https://i.imgur.com/jOMhKMX.png" height="70%" width="70%" alt="Run installer"/>
<br />
Read the Prerequisites Check and click Install button:<br />
<img src="https://i.imgur.com/DGpc9yY.png" height="70%" width="70%" alt="Run installer"/>
<br />
Let the installation run and wait for it to finish:<br />
<img src="https://i.imgur.com/b9VSSVK.png" height="70%" width="70%" alt="Run installer"/>
<br />
When the installation finished, Open Server Manager:
<img src="https://i.imgur.com/LXmnMtb.png" height="70%" width="70%" alt="Run installer"/>
<br />
In Server Manager, Click Tools>Active Directory Users and Computers:
<img src="https://i.imgur.com/lIZAqTy.png" height="70%" width="70%" alt="Run installer"/>
<br />
In Active Directory Users and Computers, you may Create User Credentials to login to Domain:
<img src="https://i.imgur.com/xvybhKY.png" height="70%" width="70%" alt="Run installer"/>
<br />

<h2>Program walk-through:</h2>

<p align="center">
 Now let's create user to login in our Domain, In Active Directory Users and Computers:<br/>
<img src="https://i.imgur.com/wlOPsJz.png" height="60%" width="60%" alt="Run installer"/>
<br />
<br />
For a Name, will give it Ubuntu Desktop 22, Locate the ISO file on the ISO image option, Type is Linux, Version is Ubuntu (64-bit), Tick the Skip unattended installation, then Click the Next button: <br/>
<img src="https://i.imgur.com/Z9qm9ri.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
For the Hardware, well give 4GB of Memory and 2 of Processors, then Click the Next button: <br/>
<img src="https://i.imgur.com/3BFV0iu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Will give 60GB for Virtual Hard disk, then Click the Next button: <br/>
<img src="https://i.imgur.com/eaQZEup.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Review the configuration that you have been chosen, then Click the Finish button to exit the wizard:  <br/>
<img src="https://i.imgur.com/TTmgNDn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
The newly created Virtual Machine have been added in the left part of the application, Click the Start button to run the Ubuntu installation: <br/>
<img src="https://i.imgur.com/R8y2fAJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
You may then continue the installation: <br/>
<img src="https://i.imgur.com/hfxabb0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
