<h1>Active Directory Home Lab</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Documented setup of Active Directory, Including a Youtube video with me doing the project.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Diagram of the project Network: <br/>
<img src="https://imgur.com/0AZG1AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Install Windows Server 2019, After setting up virtualbox and doing minor configurations for virtualbox: <br/>
<img src="https://imgur.com/nsc6VLS.png](https://imgur.com/Wx2dEPp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/Wx2dEPp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://imgur.com/T5ADoYL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://imgur.com/a9T9ZZz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Set the Admin username and password: <br/>
<img src="https://imgur.com/xBDN4kh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Change the  name for your home IP to Internet and the other IP to Internal for your Network setup: <br/>
<img src="https://imgur.com/3RkpPNr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Rename the PC to DC for "Domain Controller, then restart the VB: <br/>
<img src="https://imgur.com/vVRjZ8H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Set the Internal IP address in ethernet settings to 172.16.0.1 with subnet mask 255.255.255.0. Give it a DNS address of 127.0.0.1: <br/>
<img src="https://imgur.com/Z5zik94.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Sign out and Sign back in as Admin again with your password: <br/>
<img src="https://imgur.com/KOvT5Kc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Create an Organizational Unit for the Domain, And name it _ADMINS: <br/>
<img src="https://imgur.com/zIWlzmN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://imgur.com/49qKnio.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Create a new User for the _ADMINS Organizational Unit, and name it, this will be your first Domain Admin User Account. Set the Password for it as well, then Sign out: <br/>
<img src="https://imgur.com/ERFGAGQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://imgur.com/5bBdjbS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://imgur.com/j8Irfti.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://imgur.com/FD2ZwBM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
</p>

<p align="center">
In the add roles and features wizard, under server roles tab, select remote access option, then under Role Services select the Routing checkbox and click next : <br/>
<img src="https://imgur.com/mzSQ0Iv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://imgur.com/jvGq4MT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Under Routing and Remote Access, right-click the DC and select "configure and enable routing and remote access, then select network address translation (NAT) option and click next, then select the first option and choose the INTERNET option : <br/>
<img src="https://imgur.com/LEzw6lR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://imgur.com/49Wu0jt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://imgur.com/jxxQdQ9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Launch the utility: <br/>
<img src=".png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Launch the utility: <br/>
<img src=".png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Launch the utility: <br/>
<img src=".png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Launch the utility: <br/>
<img src=".png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Launch the utility: <br/>
<img src=".png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Launch the utility: <br/>
<img src=".png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<p align="center">
Launch the utility: <br/>
<img src=".png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
