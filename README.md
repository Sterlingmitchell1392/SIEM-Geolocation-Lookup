# SIEM-Geolocation-Lookup


<h2>Description</h2>
<b>The Powershell script in this repository is filters Windows Event Log information for failed RDP attacks and using a third party API IPgeolocation.io to collect geographic information about the attackers location.
</b>
<br />
<br />
The script is setup via  Azure Sentinel (SIEM) and connectsto a live virtual machine acting as a honey pot with allowed firewall rules to make us discoverable to test the attacks.
We will observe live attacks (RDP Brute Force) from all around the world and is plotted it on an Azure Sentinel Map.
<br />
<br />




- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Languages Used</h2>
<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API



<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="https://i.imgur.com/krRFrK5.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
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
