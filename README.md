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
The Architecture: <br/>
<img src="https://i.imgur.com/AZoESxJ.png" height="80%" width="80%"/>
<br />
<br />
KQL Query in Action: <br/>
<img src="https://i.imgur.com/WPL5IJ8.png" height="80%" width="80%"/>
<br />
<br />
Architecture & Resource Configuration:  <br/>
<img src="https://i.imgur.com/FVtf5Gh.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/CfGyMxQ.png" height="80%" width="80%"/>
<br />
<br />
Log Source Verification: <br/>
<img src="https://i.imgur.com/dlZofbT.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/NZcaaft.png" height="80%" width="80%"/>
</p>
