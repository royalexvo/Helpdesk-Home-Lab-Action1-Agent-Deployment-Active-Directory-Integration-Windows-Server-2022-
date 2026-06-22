<h1>Helpdesk Home Lab – Action1 Agent Deployment & Active Directory Integration (Windows Server 2022)</h1>

<h2>Description</h2>

This lab demonstrates how to deploy Action1 agents throughout an Active Directory environment using automated agent deployment. The goal of this lab is to practice deploying endpoint management software, configuring Active Directory integration, onboarding domain-joined systems, monitoring endpoint health, and performing vulnerability remediation through the Action1 platform.

In this lab, the following tasks were completed:

- <b>Reviewed the Action1 management dashboard</b>
- <b>Reviewed Action1 reporting capabilities</b>
- <b>Reviewed Action1 alerting functionality</b>
- <b>Configured Active Directory agent deployment</b>
- <b>Downloaded the Action1 deployment package</b>
- <b>Prepared a Windows Server 2022 domain controller for deployment</b>
- <b>Modified network adapter settings for internet connectivity</b>
- <b>Configured bridge adapter networking</b>
- <b>Connected the domain controller to Action1 cloud services</b>
- <b>Installed the Action1 agent on a domain controller</b>
- <b>Verified successful endpoint registration</b>
- <b>Configured automatic Active Directory discovery</b>
- <b>Configured automated agent deployment settings</b>
- <b>Reviewed Active Directory deployment configuration options</b>
- <b>Validated Active Directory connectivity</b>
- <b>Installed Action1 agents on additional endpoints</b>
- <b>Reviewed endpoint inventory information</b>
- <b>Reviewed endpoint vulnerability information</b>
- <b>Identified missing security updates</b>
- <b>Reviewed overdue software updates</b>
- <b>Deployed updates through Action1</b>
- <b>Monitored update deployment tasks</b>
- <b>Reviewed endpoint remediation capabilities</b>
- <b>Reviewed remote management capabilities</b>
- <b>Reviewed Action1 scripting and automation features</b>

This lab demonstrates how organizations automate software deployment, vulnerability remediation, and endpoint management using centralized endpoint management platforms. :contentReference[oaicite:0]{index=0}

<h2>Languages and Utilities Used</h2>

- <b>Action1</b>
- <b>Windows Server 2022</b>
- <b>Windows 11</b>
- <b>Active Directory</b>
- <b>Oracle VirtualBox</b>
- <b>Control Panel</b>
- <b>TCP/IPv4 Configuration</b>
- <b>Endpoint Management Dashboard</b>

<h2>Environments Used</h2>

- <b>Domain Controller: Windows Server 2022</b>
- <b>Client Machine: Windows 11</b>
- <b>Active Directory Domain Environment</b>
- <b>Oracle VirtualBox</b>
- <b>Action1 Cloud Platform</b>

<h2>Program walk-through:</h2>

<p align="center">
<b>Step 1 – Access the Action1 Dashboard</b><br/><br/>
Sign in to the Action1 portal and review the current endpoint inventory:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Action1-Agent-Deployment-Active-Directory-Integration-Windows-Server-2022-/blob/main/1.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 2 – Download The Agent Deployer from Action1</b><br/><br/>
Navigate to the agent deployment section and download the deployer:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Action1-Agent-Deployment-Active-Directory-Integration-Windows-Server-2022-/blob/main/2.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 3 – Prepare the Domain Controller</b><br/><br/>
Move the deployer installer into the VM environment folder and log in to the Windows Server 2022 domain controller:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Action1-Agent-Deployment-Active-Directory-Integration-Windows-Server-2022-/blob/main/3.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 4 – Configure Internet Connectivity</b><br/><br/>
Modify network settings to allow communication with Action1 cloud services:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Action1-Agent-Deployment-Active-Directory-Integration-Windows-Server-2022-/blob/main/4.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 5 – Launch the Action1 Deployer Installer</b><br/><br/>
Execute the deployment package and begin the Action1 deployer installation process:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Action1-Agent-Deployment-Active-Directory-Integration-Windows-Server-2022-/blob/main/5.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 6 – Verify Endpoint Registration</b><br/><br/>
Confirm the domain controller successfully registers with the Action1 platform:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Action1-Agent-Deployment-Active-Directory-Integration-Windows-Server-2022-/blob/main/6.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 7 – Configure Active Directory Discovery</b><br/><br/>
Configure Active Directory scanning and automatic endpoint deployment settings:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Action1-Agent-Deployment-Active-Directory-Integration-Windows-Server-2022-/blob/main/7.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 8 – Validate Deployment Settings</b><br/><br/>
Review deployment settings and verify Active Directory connectivity:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Action1-Agent-Deployment-Active-Directory-Integration-Windows-Server-2022-/blob/main/8.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 9 – Deploy Agents to Additional Endpoints</b><br/><br/>
Install Action1 agents on additional domain-joined systems:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Action1-Agent-Deployment-Active-Directory-Integration-Windows-Server-2022-/blob/main/9.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 10 – Review Endpoint Inventory</b><br/><br/>
Verify all managed endpoints appear within the Action1 inventory dashboard:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Action1-Agent-Deployment-Active-Directory-Integration-Windows-Server-2022-/blob/main/10.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 11 – Review Vulnerability Information</b><br/><br/>
Identify missing updates and review endpoint vulnerability status:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Action1-Agent-Deployment-Active-Directory-Integration-Windows-Server-2022-/blob/main/11.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 12 – Deploy Software Updates</b><br/><br/>
Select missing updates and initiate the remediation process:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Action1-Agent-Deployment-Active-Directory-Integration-Windows-Server-2022-/blob/main/12.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 13 – Monitor Deployment Progress</b><br/><br/>
Track update installation progress and remediation task execution untill completion:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Action1-Agent-Deployment-Active-Directory-Integration-Windows-Server-2022-/blob/main/13.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>
