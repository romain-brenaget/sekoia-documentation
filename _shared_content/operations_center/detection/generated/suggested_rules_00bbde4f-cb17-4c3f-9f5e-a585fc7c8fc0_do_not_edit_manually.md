### Related Built-in Rules

The following Sekoia.io built-in rules match the intake **Google Kubernetes Engine**. This documentation is updated automatically and is based solely on the fields used by the intake which are checked against our rules. This means that some rules will be listed but might not be relevant with the intake.

<a href="https://mitre-attack.github.io/attack-navigator/#layerURL=https%3A%2F%2Fraw.githubusercontent.com%2FSEKOIA-IO%2Fdocumentation%2Fmain%2F_shared_content%2Foperations_center%2Fdetection%2Fgenerated%2Fattack_00bbde4f-cb17-4c3f-9f5e-a585fc7c8fc0_do_not_edit_manually.json" class="button primary">SEKOIA.IO x Google Kubernetes Engine on ATT&CK Navigator</a>

<details>
<summary>AdFind Usage</summary>


Detects the usage of the AdFind tool. AdFind.exe is a free tool that extracts information from Active Directory.  Wizard Spider (Bazar, TrickBot, Ryuk), FIN6 and MAZE operators have used AdFind.exe to collect information about Active Directory organizational units and trust objects 

- **Effort:** elementary

</details>

<details>
<summary>Address Space Layout Randomization (ASLR) Alteration</summary>


ASLR is a security feature used by the Operating System to mitigate memory exploit, attacker might want to disable it

- **Effort:** intermediate

</details>

<details>
<summary>Adidnsdump Enumeration</summary>


Detects use of the tool adidnsdump for enumeration and discovering DNS records.

- **Effort:** advanced

</details>

<details>
<summary>Advanced IP Scanner</summary>


Detects the use of Advanced IP Scanner. Seems to be a popular tool for ransomware groups.

- **Effort:** master

</details>

<details>
<summary>Audio Capture via PowerShell</summary>


Detects audio capture via PowerShell Cmdlet

- **Effort:** intermediate

</details>

<details>
<summary>Autorun Keys Modification</summary>


Detects modification of autostart extensibility point (ASEP) in registry. Prerequisites are Logging for Registry events in the Sysmon configuration (events 12 and 13).

- **Effort:** master

</details>

<details>
<summary>AzureEdge in Command Line</summary>


Detects use of azureedge in the command line.

- **Effort:** advanced

</details>

<details>
<summary>BITSAdmin Download</summary>


Detects command to download file using BITSAdmin, a built-in tool in Windows. This technique is used by several threat actors to download scripts or payloads on infected system.

- **Effort:** advanced

</details>

<details>
<summary>BazarLoader Persistence Using Schtasks</summary>


Detects possible BazarLoader persistence using schtasks. BazarLoader will create a Scheduled Task using a specific command line to establish its persistence.

- **Effort:** intermediate

</details>

<details>
<summary>Bloodhound and Sharphound Tools Usage</summary>


Detects default process names and default command line parameters used by Bloodhound and Sharphound tools.

- **Effort:** intermediate

</details>

<details>
<summary>Blue Mockingbird Malware</summary>


Attempts to detect system changes made by Blue Mockingbird

- **Effort:** elementary

</details>

<details>
<summary>CertOC Loading Dll</summary>


Detects when a user installs certificates by using CertOC.exe to loads the target DLL file.

- **Effort:** intermediate

</details>

<details>
<summary>Certificate Authority Modification</summary>


Installation of new certificate(s) in the Certificate Authority can be used to trick user when spoofing website or to add trusted destinations.

- **Effort:** master

</details>

<details>
<summary>Certify Or Certipy</summary>


Detects the use of certify and certipy which are two different tools used to enumerate and abuse Active Directory Certificate Services.

- **Effort:** advanced

</details>

<details>
<summary>Change Default File Association</summary>


When a file is opened, the default program used to open the file (also called the file association or handler) is checked. File association selections are stored in the Windows Registry and can be edited by users, administrators, or programs that have Registry access or by administrators using the built-in assoc utility. Applications can modify the file association for a given file extension to call an arbitrary program when a file with the given extension is opened.

- **Effort:** advanced

</details>

<details>
<summary>Clear EventLogs Through CommandLine</summary>


Detects a command that clears event logs which could indicate an attempt from an attacker to erase its previous traces.

- **Effort:** intermediate

</details>

<details>
<summary>Commonly Used Commands To Stop Services And Remove Backups</summary>


Detects specific commands used regularly by ransomwares to stop services or remove backups

- **Effort:** master

</details>

<details>
<summary>Component Object Model Hijacking</summary>


Detects component object model hijacking. An attacker can establish persistence with COM objects.

- **Effort:** advanced

</details>

<details>
<summary>Compression Followed By Suppression</summary>


Detects when a file is compressed and deleted.

- **Effort:** advanced

</details>

<details>
<summary>Container Credential Access</summary>


Adversaries could abuse containers tools to obtain credential like Kubernetes secret or Kubernetes service account access token

- **Effort:** intermediate

</details>

<details>
<summary>Control Panel Items</summary>


Detects the malicious use of a control panel item

- **Effort:** advanced

</details>

<details>
<summary>Copy Of Legitimate System32 Executable</summary>


A script has copied a System32 executable.

- **Effort:** intermediate

</details>

<details>
<summary>Copying Browser Files With Credentials</summary>


Detects copy of sensitive data (passwords, cookies, credit cards) included in web browsers files.

- **Effort:** elementary

</details>

<details>
<summary>Correlation Multi Service Disable</summary>


The rule detects a high number of services stopped or de-activated in a short period of time.

- **Effort:** master

</details>

<details>
<summary>DHCP Callout DLL Installation</summary>


Detects the installation of a Callout DLL via CalloutDlls and CalloutEnabled parameter in Registry, which can be used to execute code in context of the DHCP server (restart required).

- **Effort:** intermediate

</details>

<details>
<summary>DNS Exfiltration and Tunneling Tools Execution</summary>


Well-known DNS exfiltration tools execution

- **Effort:** intermediate

</details>

<details>
<summary>DNS ServerLevelPluginDll Installation</summary>


Detects the installation of a plugin DLL via ServerLevelPluginDll parameter in Windows Registry or in command line, which can be used to execute code in context of the DNS server (restart required). To fully use this rule, prerequesites are logging for Registry events in the Sysmon configuration (events 12, 13 and 14).

- **Effort:** master

</details>

<details>
<summary>Data Compressed With Rar With Password</summary>


An adversary may compress data in order to make it portable and minimize the amount of data sent over the network, this could be done the popular rar command line program. This is a more specific one for rar where the arguments allow to encrypt both file data and headers with a given password.

- **Effort:** intermediate

</details>

<details>
<summary>Debugging Software Deactivation</summary>


Deactivation of some debugging softwares using taskkill command. It was observed being used by Ransomware operators.

- **Effort:** elementary

</details>

<details>
<summary>Default Encoding To UTF-8 PowerShell</summary>


Detects PowerShell encoding to UTF-8, which is used by Sliver implants. The command line just sets the default encoding to UTF-8 in PowerShell.

- **Effort:** advanced

</details>

<details>
<summary>Disable .NET ETW Through COMPlus_ETWEnabled</summary>


Detects potential adversaries stopping ETW providers recording loaded .NET assemblies. Prerequisites are logging for Registry events or logging command line parameters (both is better). Careful for registry events, if SwiftOnSecurity's SYSMON default configuration is used, you will need to update the configuration to include the .NETFramework registry key path. Same issue with Windows 4657 EventID logging, the registry path must be specified.

- **Effort:** intermediate

</details>

<details>
<summary>Disable Task Manager Through Registry Key</summary>


Detects commands used to disable the Windows Task Manager by modifying the proper registry key in order to impair security tools. This technique is used by the Agent Tesla RAT, among others.

- **Effort:** elementary

</details>

<details>
<summary>Disabled IE Security Features</summary>


Detects from the command lines or the registry, changes that indicate unwanted modifications to registry keys that disable important Internet Explorer security features. This has been used by attackers during Operation Ke3chang.

- **Effort:** advanced

</details>

<details>
<summary>Domain Trust Discovery Through LDAP</summary>


Detects attempts to gather information on domain trust relationships that may be used to identify lateral movement opportunities. "trustedDomain" which is detected here is a Microsoft Active Directory ObjectClass Type that represents a domain that is trusted by, or trusting, the local AD DOMAIN. Several tools are using LDAP queries in the end to get the information (DSQuery, sometimes ADFind as well, etc.)

- **Effort:** elementary

</details>

<details>
<summary>Dynamic Linker Hijacking From Environment Variable</summary>


LD_PRELOAD and LD_LIBRARY_PATH are environment variables used by the Operating System at the runtime to load shared objects (library.ies) when executing a new process, attacker can overwrite this variable to attempts a privileges escalation.

- **Effort:** master

</details>

<details>
<summary>ETW Tampering</summary>


Detects a command that clears or disables any ETW Trace log which could indicate a logging evasion

- **Effort:** intermediate

</details>

<details>
<summary>Equation Group DLL_U Load</summary>


Detects a specific tool and export used by EquationGroup

- **Effort:** elementary

</details>

<details>
<summary>Exfiltration Domain In Command Line</summary>


Detects commands containing a domain linked to http exfiltration.

- **Effort:** intermediate

</details>

<details>
<summary>FromBase64String Command Line</summary>


Detects suspicious FromBase64String expressions in command line arguments.

- **Effort:** master

</details>

<details>
<summary>HackTools Suspicious Process Names In Command Line</summary>


Detects the default process name of several HackTools and also check in command line. This rule is here for quickwins as it obviously has many blind spots.

- **Effort:** intermediate

</details>

<details>
<summary>High Privileges Network Share Removal</summary>


Detects high privileges shares being deleted with the net share command.

- **Effort:** intermediate

</details>

<details>
<summary>ICacls Granting Access To All</summary>


Detects suspicious icacls command granting access to all, used by the ransomware Ryuk to delete every access-based restrictions on files and directories. ICacls is a built-in Windows command to interact with the Discretionary Access Control Lists (DACLs) which can grand adversaries higher permissions on specific files and folders.

- **Effort:** elementary

</details>

<details>
<summary>Inhibit System Recovery Deleting Backups</summary>


Detects adversaries attempts to delete backups or inhibit system recovery. This rule relies on differents known techniques using Windows events logs from Sysmon (ID 1), and PowerShell (ID 4103, 4104).

- **Effort:** intermediate

</details>

<details>
<summary>Invoke-TheHash Commandlets</summary>


Detects suspicious Invoke-TheHash PowerShell commandlet used for performing pass the hash WMI and SMB tasks.

- **Effort:** elementary

</details>

<details>
<summary>KeePass Config XML In Command-Line</summary>


Detects a command-line interaction with the KeePass Config XML file. It could be used to retrieve informations or to be abused for persistence.

- **Effort:** intermediate

</details>

<details>
<summary>Lazarus Loaders</summary>


Detects different loaders used by the Lazarus Group APT

- **Effort:** elementary

</details>

<details>
<summary>Leviathan Registry Key Activity</summary>


Detects registry key used by Leviathan APT in Malaysian focused campaign.

- **Effort:** elementary

</details>

<details>
<summary>Linux Bash Reverse Shell</summary>


To bypass some security equipement or for a sack of simplicity attackers can open raw reverse shell using shell commands

- **Effort:** intermediate

</details>

<details>
<summary>Linux Masquerading Space After Name</summary>


This detection rule identifies a process created from an executable with a space appended to the end of the name.

- **Effort:** intermediate

</details>

<details>
<summary>Linux Shared Lib Injection Via Ldso Preload</summary>


Detect ld.so.preload modification for shared lib injection, technique used by attackers to load arbitrary code into process

- **Effort:** intermediate

</details>

<details>
<summary>Listing Systemd Environment</summary>


Detects a listing of systemd environment variables. This command could be used to do reconnaissance on a compromised host.

- **Effort:** advanced

</details>

<details>
<summary>Logon Scripts (UserInitMprLogonScript)</summary>


Detects creation or execution of UserInitMprLogonScript persistence method. The rule requires to log for process command lines and registry creations or update, which can be done using Sysmon Event IDs 1, 12, 13 and 14.

- **Effort:** advanced

</details>

<details>
<summary>MSBuild Abuse</summary>


Detection of MSBuild uses by attackers to infect an host. Focuses on XML compilation which is a Metasploit payload.

- **Effort:** intermediate

</details>

<details>
<summary>Malicious Browser Extensions</summary>


Detects browser extensions being loaded with the --load-extension and -base-url options, which works on Chromium-based browsers. We are looking for potentially malicious browser extensions. These extensions can get access to informations.

- **Effort:** advanced

</details>

<details>
<summary>Malspam Execution Registering Malicious DLL</summary>


Detects the creation of a file in the C:\Datop folder, or DLL registering a file in the C:\Datop folder. Files located in the Datop folder are very characteristic of malspam execution related to Qakbot or SquirrelWaffle. Prerequisites are Logging for File Creation events, which can be done in the Sysmon configuration (events 11), for the first part of the pattern (TargetFilename).

- **Effort:** elementary

</details>

<details>
<summary>Malware Persistence Registry Key</summary>


Detects registry key used by several malware, especially Formbook spyware in two ways, either the Sysmon registry events, or the commands line.

- **Effort:** master

</details>

<details>
<summary>MalwareBytes Uninstallation</summary>


Detects command line being used by attackers to uninstall Malwarebytes.

- **Effort:** intermediate

</details>

<details>
<summary>MavInject Process Injection</summary>


Detects process injection using the signed Windows tool Mavinject32.exe (which is a LOLBAS)

- **Effort:** intermediate

</details>

<details>
<summary>Microsoft Defender Antivirus Disable Services</summary>


The rule detects attempts to deactivate/disable Windows Defender through command line and registry.

- **Effort:** intermediate

</details>

<details>
<summary>Microsoft Defender Antivirus Disable Using Registry</summary>


The rule detects attempts to deactivate/disable Microsoft Defender Antivirus using registry modification via command line or PowerShell scripts.

- **Effort:** master

</details>

<details>
<summary>Microsoft Defender Antivirus Disabled Base64 Encoded</summary>


Detects attempts to deactivate/disable Windows Defender through base64 encoded PowerShell command line or scripts.

- **Effort:** intermediate

</details>

<details>
<summary>Microsoft Defender Antivirus History Directory Deleted</summary>


Windows Defender history directory has been deleted. This could be an attempt by an attacker to remove its traces.

- **Effort:** elementary

</details>

<details>
<summary>Microsoft Defender Antivirus Restoration Abuse</summary>


The rule detects attempts to abuse Windows Defender file restoration tool. The Windows Defender process is allowed to write files in its own protected directory. This functionality can be used by a threat actor to overwrite Windows Defender files in order to prevent it from running correctly or use Windows Defender to execute a malicious DLL.

- **Effort:** intermediate

</details>

<details>
<summary>Microsoft Defender Antivirus Set-MpPreference Base64 Encoded</summary>


Detects changes of preferences for Windows Defender through command line or PowerShell scripts. Configure Windows Defender using base64-encoded commands is suspicious and could be related to malicious activities.

- **Effort:** intermediate

</details>

<details>
<summary>Microsoft Defender Antivirus Signatures Removed With MpCmdRun</summary>


Detects attempts to remove Windows Defender Signatures using MpCmdRun legitimate Windows Defender executable. No signatures mean Windows Defender will be less effective (or completely useless depending on the option used).

- **Effort:** elementary

</details>

<details>
<summary>Microsoft Exchange PowerShell Snap-Ins To Export Exchange Mailbox Data</summary>


Detects PowerShell SnapIn command line or PowerShell script, often used with Get-Mailbox to export Exchange mailbox data.

- **Effort:** intermediate

</details>

<details>
<summary>Microsoft Office Macro Security Registry Modifications</summary>


Detects registry changes allowing an attacker to make Microsoft Office products runs Macros without warning. Events are collected either from ETW/Sysmon/EDR depending of the integration.

- **Effort:** master

</details>

<details>
<summary>Mimikatz Basic Commands</summary>


Detects Mimikatz most popular commands. 

- **Effort:** elementary

</details>

<details>
<summary>Msdt (Follina) File Browse Process Execution</summary>


Detects various Follina vulnerability exploitation techniques. This is based on the Compatability Troubleshooter which is abused to do code execution.

- **Effort:** elementary

</details>

<details>
<summary>Mustang Panda Dropper</summary>


Detects specific process parameters as used by Mustang Panda droppers

- **Effort:** elementary

</details>

<details>
<summary>NTDS.dit File Interaction Through Command Line</summary>


Detects interaction with the file NTDS.dit through command line. This is usually really suspicious and could indicate an attacker trying copy the file to then look for users password hashes.

- **Effort:** intermediate

</details>

<details>
<summary>NetSh Used To Disable Windows Firewall</summary>


Detects NetSh commands used to disable the Windows Firewall

- **Effort:** advanced

</details>

<details>
<summary>Netsh Allowed Python Program</summary>


Detects netsh command that performs modification on Firewall rules to allow the program python.exe. This activity is most likely related to the deployment of a Python server or an application that needs to communicate over a network. Threat actors could use it for data extraction, hosting a webshell or else.

- **Effort:** intermediate

</details>

<details>
<summary>Netsh Port Forwarding</summary>


Detects netsh commands that enable a port forwarding between to hosts. This can be used by attackers to tunnel RDP or SMB shares for example.

- **Effort:** intermediate

</details>

<details>
<summary>Netsh RDP Port Forwarding</summary>


Detects netsh commands that configure a port forwarding of port 3389 used for RDP. This is commonly used by attackers during lateralization on windows environments.

- **Effort:** elementary

</details>

<details>
<summary>New DLL Added To AppCertDlls Registry Key</summary>


Dynamic-link libraries (DLLs) that are specified in the AppCertDLLs value in the Registry key can be abused to obtain persistence and privilege escalation by causing a malicious DLL to be loaded and run in the context of separate processes on the computer. Logging for Registry events is needed in the Sysmon configuration (events 12 and 13).

- **Effort:** intermediate

</details>

<details>
<summary>Ngrok Process Execution</summary>


Detects possible Ngrok execution, which can be used by attacker for RDP tunneling.

- **Effort:** intermediate

</details>

<details>
<summary>NjRat Registry Changes</summary>


Detects changes for the RUN registry key which happen when a victim is infected by NjRAT. Please note that even if NjRat is well-known for the behavior the rule catches, the rule is a bit larger and could catch other malwares.

- **Effort:** master

</details>

<details>
<summary>Njrat Registry Values</summary>


Detects specifis registry values that are related to njRat usage.

- **Effort:** intermediate

</details>

<details>
<summary>NlTest Usage</summary>


Detects attempts to gather information on domain trust relationships that may be used to identify lateral movement opportunities. These command lines were observed in numerous attacks, but also sometimes from legitimate administrators for debugging purposes. The rule does not cover very basics commands but rather the ones that are interesting for attackers to gather information on a domain.

- **Effort:** advanced

</details>

<details>
<summary>Non-Legitimate Executable Using AcceptEula Parameter</summary>


Detects accepteula in command line with non-legitimate executable name. Some attackers are masquerading SysInternals tools with decoy names to prevent detection.

- **Effort:** advanced

</details>

<details>
<summary>Office Application Startup Office Test</summary>


Detects the addition of office test registry that allows a user to specify an arbitrary DLL that will be executed everytime an Office application is started. An adversaries may abuse the Microsoft Office "Office Test" Registry key to obtain persistence on a compromised system.

- **Effort:** elementary

</details>

<details>
<summary>Outlook Registry Access</summary>


Detection of accesses to Microsoft Outlook registry hive, which might contain sensitive information.

- **Effort:** master

</details>

<details>
<summary>Pandemic Windows Implant</summary>


Detects Pandemic Windows Implant through registry keys or specific command lines. Prerequisites: Logging for Registry events is needed, which can be done in the Sysmon configuration (events 12 and 13).

- **Effort:** master

</details>

<details>
<summary>Phorpiex DriveMgr Command</summary>


Detects specific command used by the Phorpiex botnet to execute a copy of the loader during its self-spreading stage. As described by Microsoft, this behavior is unique and easily identifiable due to the use of folders named with underscores "__" and the PE name "DriveMgr.exe".

- **Effort:** elementary

</details>

<details>
<summary>Phorpiex Process Masquerading</summary>


Detects specific process executable path used by the Phorpiex botnet to masquerade its system process network activity. It looks for a pattern of a system process executable name that is not legitimate and running from a folder that is created via a random algorithm 13-15 numbers long.

- **Effort:** elementary

</details>

<details>
<summary>PowerCat Function Loading</summary>


Detect a basic execution of PowerCat. PowerCat is a PowerShell function allowing to do basic connections, file transfer, shells, relays, generate payloads.

- **Effort:** intermediate

</details>

<details>
<summary>PowerShell AMSI Deactivation Bypass Using .NET Reflection</summary>


Detects Request to amsiInitFailed that can be used to disable AMSI (Antimalware Scan Interface) Scanning. More information about Antimalware Scan Interface https://docs.microsoft.com/en-us/windows/win32/amsi/antimalware-scan-interface-portal.

- **Effort:** advanced

</details>

<details>
<summary>PowerShell Commands Invocation</summary>


Detects the execution to invoke a powershell command. This was used in an intrusion using Gootloader to access Mimikatz.

- **Effort:** advanced

</details>

<details>
<summary>PowerShell Data Compressed</summary>


Detects data compression through a PowerShell command (could be used by an adversary for exfiltration).

- **Effort:** advanced

</details>

<details>
<summary>PowerShell EncodedCommand</summary>


Detects popular file extensions in commands obfuscated in base64 run through the EncodedCommand option.

- **Effort:** advanced

</details>

<details>
<summary>PowerShell Invoke Expression With Registry</summary>


Detects keywords from well-known PowerShell techniques to get registry key values

- **Effort:** advanced

</details>

<details>
<summary>PowerView commandlets 1</summary>


Detects PowerView commandlets which perform network and Windows domain enumeration and exploitation. It provides replaces for almost all Windows net commands, letting you query users, machines, domain controllers, user descriptions, share, sessions, and more.

- **Effort:** advanced

</details>

<details>
<summary>PowerView commandlets 2</summary>


Detects PowerView commandlets which perform network and Windows domain enumeration and exploitation. It provides replaces for almost all Windows net commands, letting you query users, machines, domain controllers, user descriptions, share, sessions, and more.

- **Effort:** master

</details>

<details>
<summary>Powershell AMSI Bypass</summary>


This rule aims to detect attempts to bypass AMSI in powershell using specific techniques.

- **Effort:** advanced

</details>

<details>
<summary>Powershell UploadString Function</summary>


Powershell's `uploadXXX` functions are a category of methods which can be used to exfiltrate data through native means on a Windows host.

- **Effort:** advanced

</details>

<details>
<summary>Powershell Web Request And Windows Script</summary>


Detects the use of PowerShell web request method combined with Windows Script utilities. This has been observed being used by some malware loaders.

- **Effort:** intermediate

</details>

<details>
<summary>Privilege Escalation Awesome Scripts (PEAS)</summary>


Detect PEAS privileges escalation scripts and binaries

- **Effort:** elementary

</details>

<details>
<summary>Process Memory Dump Using Comsvcs</summary>


Detects the use of comsvcs in command line to dump a specific process memory. This technique is used by attackers for privilege escalation and pivot.

- **Effort:** intermediate

</details>

<details>
<summary>Process Memory Dump Using Rdrleakdiag</summary>


Detects the use of rdrleakdiag.exe in command line to dump the memory of a process. This technique is used by attackers for privilege escalation and pivot.

- **Effort:** elementary

</details>

<details>
<summary>Process Trace Alteration</summary>


PTrace syscall provides a means by which one process ("tracer") may observe and control the execution of another process ("tracee") and examine and change the tracee's memory and registers. Attacker might want to abuse ptrace functionnality to analyse memory process. It requires to be admin or set ptrace_scope to 0 to allow all user to trace any process.

- **Effort:** advanced

</details>

<details>
<summary>PsExec Process</summary>


Detects PsExec execution, command line which contains pstools or installation of the PsExec service. PsExec is a SysInternals which can be used to execute a program on another computer. The tool is as much used by attackers as by administrators. 

- **Effort:** advanced

</details>

<details>
<summary>Python HTTP Server</summary>


Detects command used to start a Simple HTTP server in Python. Threat actors could use it for data extraction, hosting a webshell or else.

- **Effort:** intermediate

</details>

<details>
<summary>QakBot Process Creation</summary>


Detects QakBot like process executions

- **Effort:** intermediate

</details>

<details>
<summary>Qakbot Persistence Using Schtasks</summary>


Detects possible Qakbot persistence using schtasks.

- **Effort:** intermediate

</details>

<details>
<summary>Raccine Uninstall</summary>


Detects commands that indicate a Raccine removal from an end system. Raccine is a free ransomware protection tool.

- **Effort:** elementary

</details>

<details>
<summary>Rclone Process</summary>


Detects Rclone executable or Rclone execution by using the process name, the execution through a command obfuscated or not.

- **Effort:** advanced

</details>

<details>
<summary>RedMimicry Winnti Playbook Registry Manipulation</summary>


Detects actions caused by the RedMimicry Winnti playbook. Logging for Registry events is needed in the Sysmon configuration (events 12 and 13).

- **Effort:** elementary

</details>

<details>
<summary>Remote Monitoring and Management Software - AnyDesk</summary>


Detect artifacts related to the installation or execution of the Remote Monitoring and Management tool AnyDesk.

- **Effort:** master

</details>

<details>
<summary>Remote Monitoring and Management Software - Atera</summary>


Detect artifacts related to the installation or execution of the Remote Monitoring and Management tool Atera.

- **Effort:** master

</details>

<details>
<summary>Rubeus Tool Command-line</summary>


Detects command line parameters used by Rubeus, a toolset to interact with Kerberos and abuse it.

- **Effort:** advanced

</details>

<details>
<summary>SOCKS Tunneling Tool</summary>


Detects the usage of a SOCKS tunneling tool, often used by threat actors. These tools often use the socks5 commandline argument, however socks4 can sometimes be used as well. Unfortunately, socks alone (without any number) triggered too many false positives. 

- **Effort:** intermediate

</details>

<details>
<summary>SSH Reverse Socks</summary>


Detects the usage of the -R option combined with StrictHostKeyChecking, which is an indication of using SSH for reverse socks.

- **Effort:** intermediate

</details>

<details>
<summary>Sekoia.io Activity Logs Rule Deactivation Bulk</summary>


Detects a massive rule deactivation observed threw Sekoia.io activity logs.

- **Effort:** master

</details>

<details>
<summary>Sigma Intelligence Windows DRILLAPP Malware</summary>


Sigma RULE to detect DrillAPP or other malicious launch of edge to disable security measures and abuse permissions.

- **Effort:** intermediate

</details>

<details>
<summary>Socat Relaying Socket</summary>


Socat is a linux tool used to relay local socket or internal network connection, this technics is often used by attacker to bypass security equipment such as firewall

- **Effort:** advanced

</details>

<details>
<summary>Socat Reverse Shell Detection</summary>


Socat is a linux tool used to relay or open reverse shell that is often used by attacker to bypass security equipment.

- **Effort:** elementary

</details>

<details>
<summary>Spyware Persistence Using Schtasks</summary>


Detects possible Agent Tesla or Formbook persistence using schtasks. The name of the scheduled task used by these malware is very specific (Updates/randomstring).

- **Effort:** intermediate

</details>

<details>
<summary>Startup Item Created</summary>


Detects when a item is added to the startup directory. An attacker can use this establish persistence.

- **Effort:** intermediate

</details>

<details>
<summary>Stop Backup Services</summary>


Detects adversaries attempts to stop backups services or disable Windows previous files versions feature. This could be related to ransomware operators or legit administrators. This rule relies Windows command line logging and registry logging, and PowerShell (ID 4103, 4104).

- **Effort:** master

</details>

<details>
<summary>Suncrypt Parameters</summary>


Detects SunCrypt ransomware's parameters, most of which are unique.

- **Effort:** elementary

</details>

<details>
<summary>Suspicious Cmd File Copy Command To Network Share</summary>


Copy suspicious files through Windows cmd prompt to network share

- **Effort:** intermediate

</details>

<details>
<summary>Suspicious Cmd.exe Command Line</summary>


Detection on suspicious cmd.exe command line seen being used by some attackers (e.g. Lazarus with Word macros). This requires Windows process command line logging.

- **Effort:** master

</details>

<details>
<summary>Suspicious CommandLine Lsassy Pattern</summary>


Detects the characteristic lsassy loop used to identify lsass PIDs

- **Effort:** intermediate

</details>

<details>
<summary>Suspicious DLL Loading By Ordinal</summary>


Detects suspicious DLL Loading by ordinal number in a non legitimate or rare folders. For example, Sofacy (APT28) used this technique to load their Trojan in a campaign of 2018.

- **Effort:** intermediate

</details>

<details>
<summary>Suspicious Desktopimgdownldr Execution</summary>


Detects a suspicious Desktopimgdownldr execution. Desktopimgdownldr.exe is a Windows binary used to configure lockscreen/desktop image and can be abused to download malicious file.

- **Effort:** intermediate

</details>

<details>
<summary>Suspicious Microsoft Defender Antivirus Exclusion Command</summary>


Detects PowerShell commands aiming to exclude path, process, IP address, or extension from scheduled and real-time scanning. These commands can be used by attackers or malware to avoid being detected by Windows Defender. Depending on the environment and the installed software, this detection rule could raise false positives. We recommend customizing this rule by filtering legitimate processes that use Windows Defender exclusion command in your environment.

- **Effort:** master

</details>

<details>
<summary>Suspicious Netsh DLL Persistence</summary>


Detects persitence via netsh helper. Netsh interacts with other operating system components using dynamic-link library (DLL) files. Adversaries may establish persistence by executing malicious content triggered by Netsh Helper DLLs.

- **Effort:** elementary

</details>

<details>
<summary>Suspicious PowerShell Invocations - Generic</summary>


Detects suspicious PowerShell invocation command parameters through command line logging or ScriptBlock Logging.

- **Effort:** advanced

</details>

<details>
<summary>Suspicious PowerShell Invocations - Specific</summary>


Detects suspicious PowerShell invocation command parameters.

- **Effort:** intermediate

</details>

<details>
<summary>Suspicious PowerShell Keywords</summary>


Detects keywords that could indicate the use of some PowerShell exploitation framework.

- **Effort:** advanced

</details>

<details>
<summary>Suspicious PrinterPorts Creation (CVE-2020-1048)</summary>


Detects new commands that add new printer port which point to suspicious file

- **Effort:** advanced

</details>

<details>
<summary>Suspicious Rundll32.exe Executions</summary>


The process rundll32.exe executes a newly dropped DLL with update /i in the command line. This specific technic was observed at least being used by the IcedID loading mechanism dubbed Gziploader. Some other detections are related to LOLBAS (Living Off The Land Binaries, Scripts and Libraries) usages (like the COM registering).

- **Effort:** intermediate

</details>

<details>
<summary>Suspicious Taskkill Command</summary>


Detects rare taskkill command being used. It could be related to Baby Shark malware.

- **Effort:** intermediate

</details>

<details>
<summary>Suspicious Windows Installer Execution</summary>


Detects suspicious execution of the Windows Installer service (msiexec.exe) which could be used to install a malicious MSI package hosted on a remote server.

- **Effort:** master

</details>

<details>
<summary>Suspicious certutil command</summary>


Detects suspicious certutil command which can be used by threat actors to download and/or decode payload. 

- **Effort:** intermediate

</details>

<details>
<summary>Tactical RMM Installation</summary>


Detection of common Tactical RMM installation arguments that could be abused by some attackers.

- **Effort:** elementary

</details>

<details>
<summary>Tmutil Delete Backups</summary>


Detects when the utility tmutil is used to delete backups. The Time Machine utility is used to restore data from backups, add or remove exclusions, and compare backups.

- **Effort:** elementary

</details>

<details>
<summary>Tmutil Disabled</summary>


Detects when the utility tmutil is disabled. The Time Machine utility is used to restore data from backups, add or remove exclusions, and compare backups.

- **Effort:** elementary

</details>

<details>
<summary>Tmutil Exclude File From Backups</summary>


Detects when the utility tmutil is used to exclude paths from backups.

- **Effort:** master

</details>

<details>
<summary>UAC Bypass Via Sdclt</summary>


Detects changes to HKCU\Software\Classes\exefile\shell\runas\command\isolatedCommand by an attacker in order to bypass User Account Control (UAC)

- **Effort:** elementary

</details>

<details>
<summary>Usage Of Procdump With Common Arguments</summary>


Detects the usage of Procdump sysinternals tool with some common arguments and followed by common patterns.

- **Effort:** advanced

</details>

<details>
<summary>Usage Of Sysinternals Tools</summary>


Detects the usage of Sysinternals Tools due to accepteula key being added to Registry. The rule detects it either from the command line usage or from the regsitry events. For the later prerequisite is logging for registry events in the Sysmon configuration (events 12 and 13).

- **Effort:** master

</details>

<details>
<summary>Venom Multi-hop Proxy agent detection</summary>


Detects Venom Multi-hop Proxy agent.

- **Effort:** intermediate

</details>

<details>
<summary>WMI Install Of Binary</summary>


Detection of WMI used to install a binary on the host. It is often used by attackers as a signed binary to infect an host.

- **Effort:** elementary

</details>

<details>
<summary>WMIC Command To Determine The Antivirus</summary>


Detects WMIC command to determine the antivirus on a system, characteristic of the ZLoader malware (and possibly others)

- **Effort:** advanced

</details>

<details>
<summary>WMIC Uninstall Product</summary>


Detects products being uninstalled using WMIC command.

- **Effort:** intermediate

</details>

<details>
<summary>WMImplant Hack Tool</summary>


WMImplant is a powershell framework used by attacker for reconnaissance and exfiltration, this rule attempts to detect WMimplant arguments and invokes commands. 

- **Effort:** advanced

</details>

<details>
<summary>Wdigest Enable UseLogonCredential</summary>


Detects modification of the Windows Registry value of HKLM\SYSTEM\CurrentControlSet\Control\SecurityProviders\WDigest\UseLogonCredential. This technique is used to extract passwords in clear-text using WDigest. The rule requires to log for Registry Events, which can be done using Sysmon Event IDs 12, 13 and 14.

- **Effort:** elementary

</details>

<details>
<summary>WiFi Credentials Harvesting Using Netsh</summary>


Detects the harvesting of WiFi credentials using netsh.exe.

- **Effort:** advanced

</details>

<details>
<summary>Windows Defender Logging Modification Via Registry</summary>


Detects when the logging for defender is disabled in the registry.

- **Effort:** elementary

</details>

<details>
<summary>Windows Firewall Changes</summary>


Detects changes on Windows Firewall configuration

- **Effort:** master

</details>

<details>
<summary>Windows Registry Persistence COM Key Linking</summary>


Detects COM object hijacking via TreatAs subkey. Logging for Registry events is needed in the Sysmon configuration with this kind of rule `<TargetObject name="testr12" condition="end with">\TreatAs\(Default)</TargetObject>`.

- **Effort:** master

</details>

<details>
<summary>Windows Sandbox Start</summary>


Detection of Windows Sandbox started from the command line with a config file or interactively using a WSB file.

- **Effort:** master

</details>

<details>
<summary>Wmic Process Call Creation</summary>


The WMI command-line (WMIC) utility provides a command-line interface for Windows Management Instrumentation (WMI). WMIC is compatible with existing shells and utility commands. Although WMI is supposed to be an administration tool, it is wildy abused by threat actors. One of the reasons is WMI is quite stealthy. This rule detects the wmic command line launching a process on a remote or local host.

- **Effort:** intermediate

</details>

<details>
<summary>Wmic Service Call</summary>


Detects either remote or local code execution using wmic tool.

- **Effort:** intermediate

</details>

<details>
<summary>XCopy Suspicious Usage</summary>


Detects the usage of xcopy with suspicious command line options (used by Judgment Panda APT in the past). The rule is based on command line only in case xcopy is renamed.

- **Effort:** advanced

</details>

