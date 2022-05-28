<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
Project consists of a simple PowerShell script that creates several new users in a domain. The domain controller is located in a virtual machine using VirtualBox and a separate client virtual machine is also used to join the new domain
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>VirtualBoxt</b>

<h2>Environments Used </h2>

- <b>Windows 10 Server</b>
- <b>Windows 10</b>

<h2>Project walk-through:</h2>

<p align="center">
Creating users for the domain using 1_CREATE_USERS.ps1: <br/>
<img src="https://user-images.githubusercontent.com/106448466/170840304-8c2598bd-01c5-43cf-bd52-9cc7cf19bcde.png" height="80%" width="80%" alt="Creating Users"/>
<br />
<br />
Adding the client to the domain:  <br/>
<img src="https://user-images.githubusercontent.com/106448466/170840818-95202a8a-528b-4ec9-b117-38a6cf76c123.png" height="80%" width="80%" alt="Add Client"/>
<br />
<br />
Logging into client machine using domain credentials: <br/>
<img src="https://user-images.githubusercontent.com/106448466/170841117-a8a2d764-a0c0-44d2-b5d9-02e7d7666ce1.png" height="80%" width="80%" alt="Login to Client"/>
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
