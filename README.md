<h1>Legacy File Servers Migration and Security Enhancement Project</h1>


<h2>Description</h2>
Project involved upgrading three critical virtual file servers from Windows Server 2008 and 2012 R2 to Windows Server 2022. Due to in-house limitations, new virtual servers were deployed, and data was seamlessly migrated using Robocopy for efficiency and security. This effort showcases expertise in infrastructure upgrades, emphasizing a commitment to technological advancement and operational efficiency for enhanced organizational performance.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Command Prompt</b> 
- <b>Robocopy</b>

<h2>Environments Used </h2>

- <b>Windows Server 2008</b>
- <b>Windows Server 2012 R2</b>
- <b>Windows Server 2022</b>

<h2>Project Summary:</h2>

<h3>Server 1: Windows Server 2008 to Windows Server 2022</h3>

<b>Incompatibility with SentinelOne:</b>

- <b>Existing Windows Server 2008 is incompatible with our newest next-generation antivirus, SentinelOne. Upgrading to Windows Server 2022 ensures seamless integration with SentinelOne, enhancing our defense against emerging threats.</b>

<b>Mimikatz Attack Vulnerability:</b>

- <b>Windows Server 2008 lacks compatibility with security settings against the Mimikatz attack. A previous security incident, involving Mimikatz, affected several of our workspace computers.</b>
- <b>Upgrading to Windows Server 2022 provides advanced security features, mitigating the risk of Mimikatz attacks.</b>

<b>Outdated and Unsupported:</b>

- <b>The server has exceeded a decade in service, and Microsoft officially discontinued support for Windows Server 2008 many years ago.</b>
- <b>Operating an unsupported system exposes the organization to significant security vulnerabilities, warranting an immediate upgrade to ensure robust security measures.</b>
<br />

<h3>Server 2: Windows Server 2012 R2 to Windows Server 2022</h3>

<b>End of Support for Windows Server 2012 R2:</b>

- <b>Microsoft has declared the end of support for Windows Server 2012 R2 on October 10th, 2023.</b>
- <b>The continued use of an unsupported system poses a considerable security risk, with no future updates or patches available.</b>

<b>Folder Access Control Issues:</b>

- <b>The server suffers from a lack of folder access controls, allowing unrestricted access to all folders, including sensitive HR data.</b>
- <b>Upgrading to Windows Server 2022 addresses this critical access control issue, providing enhanced security measures to restrict folder access based on user roles and permissions.</b>
<br />

<h3>Server 3: Windows Server 2012 R2 to Windows Server 2022</h3>

<b>Corrupted Operating System and Data Loss Risk:</b>

- <b>The server is experiencing a degraded state with a corrupted operating system.</b>
- <b>The corrupted system poses a significant risk of data loss during server shutdown or reboot, requiring frequent data recovery from backups.</b>
- <b>Upgrading to Windows Server 2022 resolves the stability issues, eliminating the need for constant data recovery and ensuring the integrity of stored files.</b>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
