# Building-a-Cbersecurity-Lab

## Objective
To establish a practical, hands-on cybersecurity lab environment for learning and testing real-world scenarios, gain expertise in deploying and managing security tools and techniques, Simulate and mitigate security threats,also prepare for real-world cybersecurity roles, such as SOC analyst, penetration tester, or systems administrator. This includes setting up essential tools and systems for penetration testing, vulnerability assessment, network analysis, and secure system configurations.
 
<h2>Languages and Utilities Used</h2>

- <b>Oracle Virtualbox</b> 
- <b>Kali Linux</b>
- <b>Metasploitable</b>

<h2>Environments Used </h2>

- <b>Windows 10 Enterprise</b> 
- <b>Windows Server 2022</b> 

<h2>Program walk-through:</h2>
Firstly we would download all the files we need which include;

- Oracle VirtualBox
[https://www.virtualbox.org/wiki/Downloads] or Go to google, search for Oracle VirtualBox and click the first link presented as a result, click download

  Oracle VirtualBox is a type 2 software-based hypervisor

- Windows Server 2022
[https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022]

- Windows 10 Enterprise
[https://www.microsoft.com/en-us/evalcenter/evaluate-windows-10-enterprise]

- Metasploitable
[https://sourceforge.net/projects/metasploitable/]

  An intentionally vulnerable virtual machine designed for training, exploit testing, and general target practice

- Kali Linux 
[https://www.kali.org/get-kali/#kali-virtual-machines] or Go to google, search for Get Kali Linux, click the first link presented as a result, click virtual machine, click virtual box. 

Nota bene: I strongly recommend creating a new folder to store the downloaded files. 

# Downloads
<p align="center">
 : <br/>
Download VirtualBox: <br/>
 Click on the corresponding operating system you have; there are options for MacOS, Windows, Linux and Solaris.
<img src="https://imgur.com/1w7qPhN.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<br />
<br />
 Downloaded file:  <br/>
<img src="https://imgur.com/oG77khJ.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<br />
<br />
Select the ISO download 64-bit edition : <br/>
<img src="https://imgur.com/NhooXIz.png height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<br />
<br />
Downloaded file:  <br/>
<img src="https://imgur.com/Nv8WwV6.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<br />
<br />
Dowload Windows 10 Enterprise: Select the ISO file <br/>
<img src="https://imgur.com/i2MDWIB.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<br />
<br />
Select the corresponding ISO Enterprise download:  <br/>
<img src="https://imgur.com/6zsawvN.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<br />
<br />
Downloaded file:  <br/>
<img src="https://imgur.com/87n7ILy.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<br />
<br />
Download Metasploitable (may take some time):  <br/>
<img src="https://imgur.com/FE7MeBz.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<br />
<br />
Downloaded file:  <br/>
<img src="https://imgur.com/DrlaREc.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<br />
<br />
Download Kali-Linux and unzip (may take some time):  <br/>
<img src="https://imgur.com/0ihBrGt.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<br />
<br />
Downloaded file (7 Zip): <br/>
<img src="https://imgur.com/87ER2eJ.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<br />
<br />
 
 # Setup and Installation
 <p align="center">
 <br/>
 Install and open VirtualBox:  <br/>
<img src="https://imgur.com/pN8fwY0.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<br />
<br />
Set-up Kali-linux in the virtual environment; Click "Add" in VirtualBox, select the extracted file <br/>
<img src="https://imgur.com/YBWUdi8.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>
<img src="https://imgur.com/GLFy3Ad.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Log-in: username: kali, password: kali  <br/>
<img src="https://imgur.com/muQ5CkL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/6TJOoJS.png" height="80%" width="80%" alt="Disk Sanitization Step"/>
<br />
<br />
Setup Windows Server 2022; Click New in VirtualBox, fill name: Windows Server 2022,  add a destination folder, type: Microsoft Windows  the parameters   <br/>
<img src="https://imgur.com/u9mvILb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
For the hardware, we selected 4MB and 1 CPU:  <br/>
<img src="https://i.imgur.com/0rOXxin.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the file location, choose VirtualBox Disk Image (VDI) as it can only be used by VirtualBox. Finish setup :  <br/>
<img src="https://i.imgur.com/5PK7F5k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open Windows Server 2022 on VirtualBox:  <br/>
<img src="https://imgur.com/gCvUJJy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Select the downloaded Windows Server 2022 file when prompted. Click "Mount and Retry Boot"  <br/>
<img src="https://imgur.com/bLFxPla.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Complete installation and Setup procees:  <br/>
<img src="https://i.imgur.com/kXoYssq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />Observe the wiped disk:  <br/>
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
