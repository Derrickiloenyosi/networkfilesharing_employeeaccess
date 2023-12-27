# networkfilesharing_employeeaccess


<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)


<h2>Deployment and Configuration Steps</h2>

<p>
<a href="https://imgur.com/NC5E1v4"><img src="https://i.imgur.com/NC5E1v4.png" title="source: imgur.com" height="80%" width="80%" alt="Disk Sanitization Steps"/></a>
</p>
<p>
<p>
The image above shows an "employee" who is receiving access to certain files. There will be several access given on the following images. 
</p>
<br />

<p>
<a href="https://imgur.com/7ELMv6j"><img src="https://i.imgur.com/7ELMv6j.png" title="source: imgur.com" /></a>
</p>
<p>
The above image further illustrates the process of adding individuals onto the database and selecting what type of permission they have for certain files be it read access, writes access, read and write, etc.
</p>
<br />

<p>
<a href="https://imgur.com/Jq3U0I8"><img src="https://i.imgur.com/Jq3U0I8.png" title="source: imgur.com" /></a>
</p>
<p>
This image is some of the folders that various users will have access to depending upon their groups, position, project, etc. 
</p>
<br />
</p>
</p>
<a href="https://imgur.com/6p4CNPF"><img src="https://i.imgur.com/6p4CNPF.png" title="source: imgur.com" /></a>
</p>
<p>
This image is an example of a document that our "employee" has access to since it is within the "employee's" clearance. In this example the employee has a "read" access so the document is able to be viewed by the employee. 
</p>
<br />
<a href="https://imgur.com/5SMgEJF"><img src="https://i.imgur.com/5SMgEJF.png" title="source: imgur.com" /></a>
</p>
<p>
In this example, the "employee" tried to open up an Accountant file but does not have access to this. This is what it looks like for a user to not have access to a file they tried to open.
</p>
</p>
<p>
  <a href="https://imgur.com/GI8lJEN"><img src="https://i.imgur.com/GI8lJEN.png" title="source: imgur.com" /></a>
Going back to Active Directy,"Security_Groups" was created. This group is created with the intention of adding the "Accountants" and managing their accessiblity easily and efficiently. For example, if need be one can give access or share files that are strictly for employees in the accountant department without worrying about accidentally sharing those files with another department or sending access to each individual in the accountant department. 
</p>
