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
<img src="https://i.imgur.com/9zT9FF6.png" height="60%" width="60%" alt="Run installer"/>
<br />
Select your server name in Sever Selection, click Next button:<br />
<img src="https://i.imgur.com/QW2dWD2.png" height="60%" width="60%" alt="Run installer"/>
<br />
Tick Click Next button to proceed with default settings:<br />
<img src="https://i.imgur.com/TCMhE6T.png" height="40%" width="40%" alt="Run installer"/>
<br />
Click Yes button to install Oracle VM Virtualbox Networking feature:<br />
<img src="https://i.imgur.com/s2LgB3z.png" height="40%" width="40%" alt="Run installer"/>
<br />
Click Yes button to install Python Core dependencies:<br />
<img src="https://i.imgur.com/yRzm7lp.png" height="40%" width="40%" alt="Run installer"/>
<br />
Click Install button to begin the installation:<br />
<img src="https://i.imgur.com/xewkZ42.png" height="40%" width="40%" alt="Run installer"/>
<br />
Let it do it's thing:<br />
<img src="https://i.imgur.com/auTZc1z.png" height="40%" width="40%" alt="Run installer"/>
<br />
Installation is done, Click Finish button to exit the setup wizard:<br />
<img src="https://i.imgur.com/KifDEWM.png" height="40%" width="40%" alt="Run installer"/>
<br />
Virtualbox is ready to host your preferred operating system:<br />
<img src="https://i.imgur.com/wlOPsJz.png" height="60%" width="60%" alt="Run installer"/>
<br />


<h2>Program walk-through:</h2>

<p align="center">
 Now let's host some operating system, in this case we'll try Ubuntu Desktop.
<p align="center">
While Virtualbox is running, Click the New button: <br/>
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
