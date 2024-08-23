<h1>Security-Groups-Least-Privilege</h1>

<h2>Description</h2>
Project consists of setting up network file shares and permissions, utilizing the concept of least privilege.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows Explorer</b>
- <b>Shared Network Files</b> 

<h2>Environments Used </h2>

- <b>Windows 11, Windows Server</b>

<h2>Program walk-through:</h2>

<h1>Network File Sharing and Permissions</h1>

<h3>Step 1: </h3>
<p> go to the DC and create 4 folders named: read-access, read/write access, no-access, security group</p>

![1](https://github.com/user-attachments/assets/1f2978a4-e09b-49b4-b255-0da8af12c488)


____


<h3>Step 2:  </h3>
<p>go to the sharing tab under the properties of the each folder, click share, add the users or groups that need access and set the appropriate permission level based on the principle of least privilege</p>


![2](https://github.com/user-attachments/assets/1c33ae85-55dc-46b7-a17f-5e2bcccd35f6)


_____


<h3>Step 3: </h3>
<p>from a different device and different domain user account, verify access or no access and permission level based on the user or group currently logged in. if any action is not allowed for your user account, you will need appropriate credentials to make write any changes</p>


![3](https://github.com/user-attachments/assets/997e065f-1536-412b-baba-f327d6e086f3)



____


![4](https://github.com/user-attachments/assets/e77f6153-ac72-457c-9839-21d0bb231bda)


____


security groups can also be added for large groups of users, departments, etc.


![5](https://github.com/user-attachments/assets/2296a89c-46d2-4f38-9d92-baaaca1f2145)


____



<h2> Final Thoughts </h2>

<p> In closing, the "network file shares and permissions" project streamlines our  .</p>
