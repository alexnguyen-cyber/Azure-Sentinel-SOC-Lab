<h1>Azure Sentinel SOC Lab</h1>

<h2>Description</h2>

- Configured a vulnerable Windows 10 virtual machine in Microsoft Azure, intentionally exposing it to the public internet to attract and capture real-world brute-force attacks.
- Utilized the Azure Monitoring Agent to aggregate security event logs into a Log Analytics Workspace, which was then integrated with Microsoft Sentinel (SIEM) for centralized monitoring.
- Developed custom Kusto Query Language (KQL) scripts to filter raw security data and created a geographic attack map in Azure Workbooks to visualize global threat actors in real-time.

<h2>Languages and Utilities Used</h2>

- <b>Azure Monitoring Agent (AMA)</b>
- <b>Event Viewer</b>
- <b>Remote Desktop Protocol (RDP)</b>
- <b>Terminal</b>
- <b>Azure Workbooks</b>

<h2>Environments Used </h2>

- <b>Microsoft Azure</b>
- <b>Windows 10</b>
- <b>Azure Sentinel (Microsoft Sentinel)</b>
- <b>Log Analytics Workspace</b>

<h2>Program walk-through:</h2>

<p align="center">
The Identity: <br/>
<img src="https://i.imgur.com/FymPRFf.png" height="80%" width="80%"/>
<br />
<br />
The Automation: <br/>
<img src="https://i.imgur.com/pIv27RK.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/ix9lacB.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/pGBevxN.png" height="80%" width="80%"/>
<br />
<br />
Active Directory Users & Computers (The 1,000 Users):  <br/>
<img src="https://i.imgur.com/CBIYFhb.png" height="80%" width="80%"/>
<br />
<br />
DHCP Lease Confirmation: <br/>
<img src="https://i.imgur.com/jqKzCve.png" height="80%" width="80%"/>
<br />
<br />
Command Prompt ipconfig & ping:  <br/>
<img src="https://i.imgur.com/UOa35TN.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/QXOd5NZ.png" height="80%" width="80%"/>
</p>
