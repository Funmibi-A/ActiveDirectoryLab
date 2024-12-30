# ActiveDirectoryLab


<img src="https://i.imgur.com/eEU3ybx.jpeg" height="80%" width="80%" alt="windows server installation"/>
 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
The project features an Active Directory home lab, showcasing the deployment and configuration of a Windows Server 2019 and Windows 10 environment using virtualization platforms such as VMware Workstation or Oracle VirtualBox.
<br />

Key highlights include:
- Installing and configuring Active Directory to promote the Windows Server to a Domain Controller.
- Setting up Remote Access Services (RAS) with Network Address Translation (NAT) for routing and internet access.
- Deploying and configuring DHCP with a custom address pool for dynamic IP assignment.
- Demonstrating proficiency in PowerShell scripting to efficiently create over 1,000 users on the Domain Controller.
- This project reflects advanced technical skills in Active Directory, networking, and automation.
<br />


<h2>Languages and Software Used</h2>

- <b>PowerShell</b>
- <b>Oracle virtualbox</b>
- <b>VMware workstation pro</b>
- <b>Windows Server 2019</b>
- <b>Windows 10</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)

<h2>Lab walk-through:</h2>

<p align="center">
Create a new virtual machine and install Windows Server 2019: <br />
<img src="https://imgur.com/wFgVDqX.jpeg" height="80%" width="80%" alt="windows server installation"/>
<br />
<br />
Start the Installation process:  <br/>
<img src="https://imgur.com/bXyQaG0.jpeg" height="80%" width="80%" alt="windows server installation"/>
<br />
<br />
Select the Operating system to install: <br/>
<img src="https://imgur.com/kGIgR6k.jpeg" height="80%" width="80%" alt="windows server installation"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://imgur.com/bN2GPRF.jpeg" height="80%" width="80%" alt="windows server installation"/>
<br />
<br />
Wait for the process to complete (may take some time):  <br/>
<img src="https://imgur.com/wc0kCFu.jpeg" height="80%" width="80%" alt="windows server installation"/>
<img src="https://imgur.com/c18bjd7.jpeg" height="80%" width="80%" alt="windows server installation"/>
<br />
<br />
Installation complete:  <br/>
<img src="https://i.imgur.com/cecDDkC.jpeg" height="80%" width="80%" alt="windows server installation"/>
<br />
<br />
Boot to desktop environment:  <br/>
<img src="https://i.imgur.com/I82R6tp.jpeg" height="80%" width="80%" alt="windows server installation"/>
<br />
<br />
Rename network adapters and assign ip address to the internal NIC: <br/>
<img src="https://i.imgur.com/W7mh53c.jpeg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/ExLLlk2.jpeg" height="80%" width="80%" alt="network adapters"/>
<br />
<br />
Install Active Directory Domain system: <br/>
<img src="https://i.imgur.com/KztKW8O.jpeg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/IH32hdJ.jpeg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/xhDbQC9.jpeg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/UCjOAnF.jpeg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/fEb9e40.jpeg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/07Urty6.jpeg" height="80%" width="80%" alt="network adapters"/>
<br />
<br /> 

Post Deployment Configuration: <br />
<img src="https://i.imgur.com/r7H2wBZ.jpeg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/qGHsabI.jpeg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/07Urty6.jpg" height="80%" width="80%" alt="network adapters"/>

Create an Administrative user account: <br />
<img src="https://i.imgur.com/x9K9zXU.jpg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/8eTkCCm.jpg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/vxRgu6p.jpg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/4LUbgfz.jpg" height="80%" width="80%" alt="network adapters"/>

Install RAS/NAS: <br/>
<img src="https://i.imgur.com/G3VM0V1.jpg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/9wslbNP.jpg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/5krKGKc.jpg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/Op0Mcfr.jpg" height="80%" width="80%" alt="network adapters"/>

Install DHCP services on the DC: <br/>
<img src="https://i.imgur.com/yfgrtQy.jpg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/ELXEZnL.jpg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/KF1ggcp.jpg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/QU2IXfG.jpg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/wRvI7DK.jpg" height="80%" width="80%" alt="network adapters"/>

Setup DHCP Scope: <br/>
<img src="https://i.imgur.com/NNFmemd.jpg" height="80%" width="80%" alt="network adapters"/>

Using Powershell creates a bunch of users in the Active directory
<img src="https://i.imgur.com/YRmeCuc.jpg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/ecCntxW.jpg" height="80%" width="80%" alt="network adapters"/>

Bringing up a new vm, with windows 10, getting an ip address through DHCP and adding it to the domain: <br/>
<img src="https://i.imgur.com/T0oJTL4.jpg" height="80%" width="80%" alt="network adapters"/>
<img src="https://i.imgur.com/vv1RJqX.jpg" height="80%" width="80%" alt="network adapters"/>
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
