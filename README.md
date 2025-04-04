<h1>Active Directory Lab</h1>



<h2>Description</h2>
Project consists of setting up PFsense to act as a default gateway to connect our users to the domain.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PFsense</b> 
- <b>VMware Workstation Pro</b>


<h2>Environments Used </h2>

- <b>Windows 10 Pro</b> (Ensure it is the Pro version, Windows 10 Home will not connect to domain)
- <b>Windows Server 2022</b>

<h2>Chapter 1: Installing/Configuring PFsense </h2>

<p align="center">
  After installing VMware you need to get a iso copy of PFsense, the version I am using is 2.60 <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
