<h1>Organizational Unit </h1>


<h2>Description</h2>
<n>In this lab, we will create an Organizational Unit</n>

The efficient management of Windows Active Directory starts with the creation of Organizational Units (OUs). For the uninitiated, an OU is a container within Active Directory that holds domain objects—primarily users and groups, but also computers and even other OUs. By using OUs, organizations can apply group policies. More importantly, from my perspective as an IT trainer and consultant, using OUs allows an organization to delegate administrative authority within the domain. This delegation is crucial for letting help desk staff and local system administrators do their jobs without letting them into the whole domain.

**NOTE:** The information provided here is for educational purposes only and should not be used to harm or disrupt systems or networks without proper authorization.
Unauthorized access to computer systems and networks is illegal and can result in severe penalties. Please use this information responsibly and ethically.
<br />

<h2> Languages and Utilities Used</h2>

- <b>VMware Workstation</b>

- <b>Server Manager</b>

<h2>Environments Used </h2>

- <b>Windows 16</b>

<h2>LAB walk-through:</h2>

<p align="center">
1. Click the Start menu and open "Server Manager": <br/>
<img src="https://imgur.com/KrVQtTd.png" height="80%" width="80%" alt="Server Manager"/>
<br />
<br />
2. In the Server Manager window, from the upper right corner, click Tools, and from the list that appears, select Active Directory Users and Computers<br/>
<img src="https://imgur.com/G5UAASh.png" height="80%" width="80%" alt="Server Manager Window"/>
<br />
<br />
3. In the Active Directory Users and Computers window, from the left pane, right click the domain and navigate to New > Organizational Unit<br/>
<img src="https://imgur.com/pYKMajP.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
4. In the New Object - Organizational Unit dialog box, in the Name text box, type "Management" and click OK: 
<br/>
<br/>
<img src="https://imgur.com/QVwzZXE.png" height="80%" width="80%" alt="Management"/>
<br />
<br />
You will observe the Management organizational unit in the left pane of the Active Directory Users and Computers window.
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
