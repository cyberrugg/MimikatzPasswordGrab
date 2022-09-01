<h1>MimikatzPasswordGrab</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Project consists of a VirtualBox environment loaded with Kali Linux, a Windows 10 machine and a Windows Domain Controller. The assumption is that network has already been breached. Mimikatz is used to gather the NTLM passwords from Windows. John the Ripper or Hashcat is used to crack the hashes. 
<br />


<h2>Linux Distribution Used</h2>

- <b>Kali Linux 2022.3(attacker)</b> 


<h2>Programs</h2>

- <b>Mimikatz </b> 
- <b>Hashcat </b> 

<h2>Environments Used </h2>

- <b>Windows 10 </b> 
- <b>Windows DC </b>

<h2>Program walk-through:</h2>

<p align="center">
Oracle VM Lab <br/>
<img src="https://imgur.com/llgR957.png" height="75%" width="75%"%" alt="MimikatzPasswordGrab"/>
<br />
<br />
Different networks Kali can access:  <br/>
<img src="https://imgur.com/JqSNEDl.png" height="80%" width="80%" alt="MimikatzPasswordGrab"/>
<br />
<br />
ip addr-Different IP addresses for different networks: <br/>
<img src="https://i.imgur.com/mqk2nRr.png" height="80%" width="80%" alt="MimikatzPasswordGrab"/>
<br />
<br />
Kali part of Red Team Lab: <br/>
<img src="https://i.imgur.com/JqSNEDl.png" height="80%" width="80%" alt="MimikatzPasswordGrab"/>
<br />
<br />
Nmap of Red Team Lab:  <br/>
<img src="https://i.imgur.com/Q3hMQzl.png" height="80%" width="80%" alt="MimikatzPasswordGrab"/>
<br />
<br />
Mimikatz launched on DC machine:  <br/>
<img src="https://i.imgur.com/zFhHMz8.png" height="80%" width="80%" alt="MimikatzPasswordGrab"/>
<br />
<br />
Begin retrieval of domain users’ creds:  <br/>
<img src="https://i.imgur.com/lDy4wul.png" height="80%" width="80%" alt="MimikatzPasswordGrab"/>
<br />
<br />
NTLM hashes from domain users 1:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="
<br />
<br />
NTLM hashes from domain users 2:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="
<br />
<br />
Mimikatz launched on DC machine:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="                                                                         
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
