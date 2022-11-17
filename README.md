<p align="center">
<img src="https://i.imgur.com/AeiqMDZ.png" alt="Traffic Examination"/>
</p>

<h1>Network-File-Shares-and-Permissions</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Domain Controller/Client Machine)
- Remote Desktop
- Shared Network Files

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

</p>
<p>
In this lab we will be settingup shared network files & permissions. We will create folders in the DC-1 VM and share them on the network certain files will have certain permissions. Only designated people will be able to view certain files. Lets get started. First go to the c:/ drive on the DC-1 machine and create 4 folders. "read-access" "read/write-access" "no-access" and "accounting".
</p>
<br />

<p>
<img src="https://i.imgur.com/k70dozS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After the fodlers have been created what you want to do is share them on the network so that the client-1 machine can view them. We can also set the permissions of the folders in DC-1. Set the folders to the appropriate permissions. "read-access" should be read only for domain users, "read/write access" shuld have read/write permissions for domain users. Lastly "no-access" should have read/write permissions for domain admins only.
</p>
<br />

<p>
<img src="https://i.imgur.com/wcpB5Ex.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/hku11Pt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
If we login to the client machine with a normal user account we can test out the shared files we just created. 
</p>
<br />
<p>
<img src="https://i.imgur.com/wcpB5Ex.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/hku11Pt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
</p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.  
</p>
<br />
<p>
<img src="https://i.imgur.com/wcpB5Ex.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/hku11Pt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
