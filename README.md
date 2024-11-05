# 
<h1>Windows Server Active Directory Management</h1>

<h2>Description</h2>
Set up a Windows Server environment on Azure to practice Active Directory (AD) management, network configuration, and policy enforcement. This project highlights the capabilities of AD for centralized network security and administration within a cloud environment.

<h2>Technologies and Tools Used</h2>
<ul>
  <li><b>Azure</b> - Virtual Machines, Networking</li>
  <li><b>Windows Server 2022</b> - Active Directory Domain Services (AD DS), Group Policy Management Console (GPMC)</li>
  <li><b>Windows 10 Enterprise</b> - Domain-joined client for testing</li>
</ul>

<h2>Environments Used</h2>
<ul>
  <li><b>Azure Cloud</b> - Windows Server VM, Windows 10 VM</li>
</ul>

<h2>Program Walk-through:</h2>

<p align="center">
Created a  Windows Server 2022 VM on Azure for AD setup: <br/>
<img src="images/Windows Server 2022"/>
<br />
<br />
<p align="center">
RDP into the server  <br/>
<img src="images/RDP"/>
<br />
<br />
Installed Active Directory Domain Services (AD DS) and promoted the server to a domain controller: <br/>
<img src="images/ADDS"/>
<img src="images/promote"/>
<br />
<br />
Set up user accounts, groups, and organizational units (OUs) within Active Directory to simulate organizational structure: <br/>
<img src="images/create acct"/>
<img src="images/add to group"/>
<br />
<br />
Configured Group Policy Objects (GPOs) to enforce security policies across the domain, such as password policies: <br/>
<img src="images/GPO"/>
<img src="images/GPO general"/>
<img src="images/lockout policy"/>
<br />
<br />
Set up file sharing within the AD environment and configured permissions based on group roles: <br/>
<img src="images/fle sharing"/>
<br />
<br />
Joined a Windows 10 Enterprise VM to the domain to test domain join and policy application: <br/>
<img src="images/join"/>
<img src="images/ppolicy"/>
<br />
<br />
Verified policy application and access permissions by logging in as different users within the domain: <br/>
<img src="images/remote access"/>
<img src="images/remote access"/>

</p>
