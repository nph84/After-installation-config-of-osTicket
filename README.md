<p align="center">
<img src="https://github.com/user-attachments/assets/0c9a5058-f465-477c-be11-3de15009f17b" height="350" width="350"
</p>

<h1>Post-Installation Setup</h1>
This tutorial outlines the setup of osTicket after installation.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket system
- Internet Information Services (IIS)
- PHP 7.3.8
- PHP manager for IIs
- Rewrite module
- MySQL
- Visual C++

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Installation Steps</h2>

<p>
In your web browser, navigate to localhost/osTicket and click on Sign In. <br /> <br />
<img src="https://github.com/user-attachments/assets/4b385489-2bf1-4b8f-84e6-a8c8fb13edb5" height="80%" width="80%"/>
</p>
<br />


<p>
Click on sign in here next to "I'm an agent". <br /> <br />
<img src="https://github.com/user-attachments/assets/4a1b742b-d119-4b39-90bb-bd1e22bbf314" height="80%" width="80%"/>
</p>
<br />



<p>
On this screen, sign in with your osTicket credentials to log in as an agent. <br /> <br />
<img src="https://github.com/user-attachments/assets/f5d44647-0a54-48e3-aa8e-d3ca8b15e7af" height="80%" width="80%"/>
</p>
<br />


<p>
System agent panel for helpdesk workers. <br /> <br />
<img src="https://github.com/user-attachments/assets/b3e93f39-cce2-41a7-a38e-d40d1d0e7cfc" height="80%" width="80%"/>
</p>
<br />


<p>
System admin panel for configuring settings on the back end. <br /> <br />
<img src="https://github.com/user-attachments/assets/4277e5fc-b37d-4747-9c7a-86f6a1c94d5b" height="80%" width="80%"/>
</p>
<br />


<p>
From the admin settings screen, go to the Agents tab. <br /> <br />
<img src="https://github.com/user-attachments/assets/16122de4-f638-4b48-a877-64ec8b8cf218" height="80%" width="80%"/>
</p>
<br />



<p>
On the next screen, click "Roles" to change the permissions. <br /> <br />
<img src="https://github.com/user-attachments/assets/5617bbe9-e394-4d8d-97d3-a5c1eaac2a7c" height="80%" width="80%"/>
</p>
<br />



<p>
On these screens, click "Add New Role". <br /> <br />
<img src="https://github.com/user-attachments/assets/81031974-4bf0-4b5b-88fe-91a007d6b720" height="80%" width="80%"/>
<img src="https://github.com/user-attachments/assets/045acdb1-469c-4fe1-aab7-ea47ea0ccabe" height="80%" width="80%"/>
</p>
<br />



<p>
Full permissions for tickets and tasks are given to this user. After setting permissions, click "Add Role". <br /> <br />
<img src="https://github.com/user-attachments/assets/eb9fa8fb-fbb8-41e9-bf93-ab6dbf584a46" height="80%" width="80%"/>
<img src="https://github.com/user-attachments/assets/d2bd5e3c-5764-4bca-a8fd-e8eb3fb418a8" height="80%" width="80%"/>
</p>
<br />



<p>
The Supreme Admin role is visible now. <br /> <br />
<img src="https://github.com/user-attachments/assets/16341a19-d90e-43ce-9aa9-7b9e8034c0b4" height="80%" width="80%"/>
</p>
<br />



<p>
Click on the "Departments" link and then click on "Add New Department". <br /> <br />
<img src="https://github.com/user-attachments/assets/90d157b7-c22d-44dd-ad04-e66bcd43f8d6" height="80%" width="80%"/>
<img src="https://github.com/user-attachments/assets/af03b78c-7098-4ea1-8fcd-7616fe3ae53e" height="80%" width="80%"/>
</p>
<br />



<p>
Click on "Teams" link and then the "Add New Team" button. <br /> <br />
<img src="https://github.com/user-attachments/assets/488b2e08-3ceb-4ada-9dab-ce41e8d634a2" height="80%" width="80%"/>
</p>
<br />



<p>
Choose desired team name and create team. <br /> <br />
<img src="https://github.com/user-attachments/assets/df4dd6d8-d903-4e0d-a21b-b74669179788" height="80%" width="80%"/>
</p>
<br />



<p>
In the admin panel, click Settings, then Users and make sure the Registration Required box is unchecked. <br /> <br />
<img src="https://github.com/user-attachments/assets/15e97b90-d8ec-4a85-b96b-6955fd38d6f9" height="80%" width="80%"/>
</p>
<br />


<p>
Click the agent tab, then click add new agent. <br /> <br />
<img src="https://github.com/user-attachments/assets/52bc2b92-6796-4ade-abc3-58d31e0ba86e" height="80%" width="80%"/>
</p>
<br />


<p> 
New osTicket agent creation screen (After entering the agent's name, user name, and granting an email; you must choose the access level, permissions and put the agent inside a team for the agent creation process to continue. <br /> <br />
<img src="https://github.com/user-attachments/assets/6a1f99ae-4900-4849-824c-39b9fecdf677" height="80%" width="80%"/>
<img src="https://github.com/user-attachments/assets/561f92e6-e66c-4502-9018-6b11f4700b95" height="80%" width="80%"/>
<img src="https://github.com/user-attachments/assets/c09cd082-0b49-413a-8d20-344477c18339" height="80%" width="80%"/>
</p>
<br />



<p>
Agents tab > Agents > click set password button and uncheck "send the agent a password reset email". <br /> <br />
<img src="https://github.com/user-attachments/assets/a8280aaa-60fd-426a-b272-1fc8b4906e52" height="80%" width="80%"/>
</p>
<br />



<p>
Go to the agent panel to add a new user. <br /> <br />
<img src="https://github.com/user-attachments/assets/297dcb92-e2e7-446e-b642-719b92a40d58" height="80%" width="80%"/>
<img src="https://github.com/user-attachments/assets/faa94ffd-01f9-4f24-a2ff-50ebd9555bb1" height="80%" width="80%"/>
<img src="https://github.com/user-attachments/assets/65122814-e4ec-4671-a5ae-a50d76cc65c6" height="80%" width="80%"/>
</p>
<br />




<p>
Go to admin panel > manage > SLA. <br /> <br />
<img src="https://github.com/user-attachments/assets/a2ff9990-a27d-422e-9c65-e88a2286eb09" height="80%" width="80%"/>
<img src="https://github.com/user-attachments/assets/8006e296-0b7b-4034-8589-2a3901ab1146" height="80%" width="80%"/>
</p>
<br />




<p>
From the admin panel navigate to manage > help topics to add a new help topic. <br /> <br />
<img src="https://github.com/user-attachments/assets/d3c3601f-17cf-45a0-a628-75aa558ff6ea" height="80%" width="80%"/>
</p>
<br />



<p>
New help topic added <br /> <br />
<img src="https://github.com/user-attachments/assets/bd45714a-59b9-4f75-8d5e-7f0ea16487f8" height="80%" width="80%"/>
<img src="https://github.com/user-attachments/assets/59d5396c-7829-4db1-bb9e-32dc9d602515" height="80%" width="80%"/>
</p>
<br />




































