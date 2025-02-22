<h1>Data Carving using Scalpel </h1>

 ## [Video Demonstration (9:16)](https://drive.google.com/file/d/1TV4_Lvy94kclhVAjgHCTh1uaBdW2j8QT/view?usp=sharing)

<h2>Description</h2>

This video demonstrates a Backdoor exploitation to the Metasploitable2 virtual machine. 
<br />

<h2>Lab walk-through:</h2>

<p align="center">Running nmap -sV to display the port version
<br/>
<img src="https://i.imgur.com/XG72ubw.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<p align="center">Starting Metasploit
<br/>
<img src="https://i.imgur.com/kL9DD1Z.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center"> Searching for an exploit for port 21 version fsftpd 2.3.4
<br/>
<img src="https://i.imgur.com/7DiSnss.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
 <p align="center">Metasploit shows a backdoor exploit 
<br/>
<img src="https://i.imgur.com/nizR4VG.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">Show options
<br/>
<img src="https://i.imgur.com/x7t6eFP.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">Setting up the correct ip address for the Metasploitable2 victim machine
<br/>
<img src="https://i.imgur.com/jXFrXf1.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">Displaying the required settings
<br/>
<img src="https://i.imgur.com/3hhT6c6.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">Performing the exploitation and displaying the ip address of the Metasploitable2 machine 10.0.2.3
<br/>
<img src="https://i.imgur.com/XoMmqVP.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">Creating a new user inside Metasploitable2 machine 10.0.2.3
<br/>
<img src="https://i.imgur.com/KuROM4Y.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">Verifying that the new user boxy has been added to /etc/passwd
<br/>
<img src="https://i.imgur.com/ZlCAY5g.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">The new user boxy is displayed at the bottom of the list
<br/>
<img src="https://i.imgur.com/VOf7ipH.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">Making the new user boxy an admin
<br/>
<img src="https://i.imgur.com/uy8DdTG.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
