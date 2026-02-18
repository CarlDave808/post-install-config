<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>

<img width="891" height="382" alt="Screenshot 2026-02-18 102257" src="https://github.com/user-attachments/assets/cad8fd4b-8a9e-4c00-a3f6-0bd40e2261e0" />

With osTicket now fully configured, we'll move on to system administration tasks by setting up new roles within the help desk. This will enable you to effectively control user access and permissions.

<img width="891" height="382" alt="Screenshot 2026-02-18 102257" src="https://github.com/user-attachments/assets/621b4f2a-fb05-4db1-819c-0b49e409d5fb" />

<img width="886" height="553" alt="Screenshot 2026-02-18 102724" src="https://github.com/user-attachments/assets/26309e3d-6425-415f-9a87-aea9a4a7c114" />

<img width="886" height="678" alt="Screenshot 2026-02-18 102748" src="https://github.com/user-attachments/assets/966a18f2-949f-44db-9618-0ff890814a2e" />

<img width="886" height="544" alt="Screenshot 2026-02-18 104523" src="https://github.com/user-attachments/assets/a5a3fc31-24b4-4768-b5c2-292457ee779a" />

<img width="884" height="400" alt="Screenshot 2026-02-18 104550" src="https://github.com/user-attachments/assets/d94553da-a27f-43c0-a8ff-0242a8771cbd" />

To set up new roles in the help desk, navigate to Admin Panel->Agents->Roles. Select "Add New Role", then enter a name for the role such as "Supreme Admin".

From There, you can define the permissions and responsibilties assigned to the role. Since this is a Supreme Admin role, be sure to enable all available permissions to grant complete administrative access.

<img width="889" height="352" alt="Screenshot 2026-02-18 105431" src="https://github.com/user-attachments/assets/7079b4d9-7e87-43fb-a094-2bb9e824797a" />

<img width="651" height="575" alt="Screenshot 2026-02-18 110937" src="https://github.com/user-attachments/assets/b92b372e-495c-4bc0-bb14-1bd787c8dc5b" />

Go to the Agents tab and click on the Departments button. From there, you can create a new department and assign agents to department according to their roles within the help desk.

Create a department called "SysAdmins", which will be used specifically for Supreme Admins.

You can also configure additional settings within the Departments tab, such as SLAs, department managers, and email settings, to ensure everything is tailored to your help desk's operational requirements.

<img width="889" height="554" alt="Screenshot 2026-02-18 111540" src="https://github.com/user-attachments/assets/f3050422-8451-493b-85ba-7b852aca2a50" />

To set up teams, go to Admin Panel->Agents->Teams. Teams enable you to group agents from different departments so they can collaborate more efficiently.

Create a team called "Online Banking" and add agents from the relevant departments as required.

