<h1>[Mini] Install software in a Linux Distribution</h1>

<h2>Description</h2>
In this lab example, I run through how to install software within a Linux distribution using the Advanced Package Tool (APT) and "sudo" command to install and uninstall applications in a Linux Bash Shell.
<br />
For this example, we will be installing/ uninstalling Suricata and tcpdump, network security applications which are used to capture and analyze network traffic!
<br/>
By the end of this mini lab, we will know how to manage installed applications by <br/>
- installing applications, <br/>
- uninstall applications, and  <br/>
- list installed applications. <br/>
<br/>
What a powerful skill!

<h2>Languages and Utilities Used</h2>

- <b>Bash Shell</b> 
- <b>Oracle VM Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 10 Pro</b> (22H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/qXf2UDE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
1. Ensure the APT application is installed by typing in "apt" into the command line interpreter:
 <br/>
<img src="https://i.imgur.com/W0suBxp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2. Install the Suricata application by typing in "sudo apt install suricata": <br/>
<img src="https://i.imgur.com/M88IA91.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
3. Uninstall Suricata by typing in "sudo apt remove suricata:  <br/>
<img src="https://i.imgur.com/d68Gw6W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
4. Install the tcpdump application by typing in "sudo apt install tcpdump":  <br/>
<img src="https://i.imgur.com/XdSsdV3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
5. List the installed applications by typing in "apt list --installed":  <br/>
You should be able to see tcpdump installed, but not suricata at this point.
<img src="https://i.imgur.com/mSL8it0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
6. Reinstall the Suricata application:  <br/>
<img src="https://i.imgur.com/sMy2VUZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
7. List the installed applications again by typing in "apt list --installed":  <br/>
You should be able to see tcpdump AND suricata installed at this point.
<img src="https://i.imgur.com/gfIXgOW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
