<h1>Active Diretory Home Lab</h1>

 ### Youtube Demonstration - Coming Soon!

<h2>Description</h2>
In this lab, I'm going to use Powershell to add users to an Active Directory home lab environment using Oracle Virtualbox.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Oracle Virtualbox</b> 
- <b>Powershell
- Active Directory</b>


<h2>Environments Used </h2>

- <b>Windows Server2019</b>

<h2>Program walk-through:</h2>

<p align="center">
I will run a script called Create Users taking in a text file called sample-name.txt: <br/>
<img src="https://imgur.com/zF0lwpd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Here is file. It contains users with both first and last name:  <br/>
<img src=https://imgur.com/25GCwTw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
This script will take in a text file, create an organizational unit named _USERS. It will then take 
the text file and create a user with a first and last name, display name, user name, and password. 
To create the display and username the script splits the first initial and last name 
(ex. James Smith as jsmith): <br/>
<img src="https://imgur.com/zTHJasS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Looking at Active Directory before running the script:  <br/>
<img src="https://imgur.com/JNQIXJv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Here is the script running:  <br/>
<img src="https://imgur.com/rzvYmTJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Script complete:  <br/>
<img src="https://imgur.com/np1ZUNj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Over 1500 users have been added:  <br/>
<img src="https://imgur.com/2ki9SJi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
