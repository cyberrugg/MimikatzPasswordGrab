<h1>MimikatzPasswordGrab</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Project consists of a VirtualBox environment loaded with Kali Linux, a Windows 10 machine and a Windows Domain Controller. The assumption is that network has already been breached. Mimikatz is used to gather the NTLM passwords from Windows. John the Ripper or Hashcat is used to crack the hashes. 
<br />


<h2>Machines Used</h2>

- <b>Kali Linux (attacker)</b> 
- <b>Diskpart</b>

<h2>Programs Used</h2>
- <b>Mimikatz</b> 
- <b>Hashcat</b> 
- 
<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Windows DC</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Oracle VM Lab <br/>
<img src="https://imgur.com/llgR957.png" height="75%" width="75%"%" alt="MimikatzPasswordGrab"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://imgur.com/JqSNEDl.png" height="80%" width="80" alt="MimikatzPasswordGrab"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="MimikatzPasswordGrab"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="MimikatzPasswordGrab"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="MimikatzPasswordGrab"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="MimikatzPasswordGrab"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="MimikatzPasswordGrab"/>
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
