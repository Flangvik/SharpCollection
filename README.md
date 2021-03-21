# SharpCollection
Nightly builds of common C# offensive tools, fresh from their respective master branches built and released in a CDI fashion using Azure DevOps release pipelines. 

Is your favorite tool missing? Feel free to open an issue or DM me on twitter [@Flangvik](https://twitter.com/Flangvik)    
**Please note that Cobalt Strike's execute-assembly only accepts binaries compiled with the "Any CPU" configuration.**

# Azure DevOps? 
Each night at 03:00 AM, the Azure DevOps pipeline checks for new commits to all repositories master branch. Branches with changes will be automatically fetched and compiled with different framework targets as well as architectures, before being pushed to this repo. 

The pipeline can be found here:
https://dev.azure.com/FlangvikDev/SharpRelease

# OpSec

Should I blindly deploy any of these binaries during real-life engagements?    
**F*ck no**, always look through anything that you deploy on a client machine or network. Eg https://github.com/dnSpy/dnSpy   
Deploying anything blindly from this repo should be reserved for Lab environment, VM's , HTB, detection mapping, and so forth. 


# Available builds

| Tools \ .NET Framework | NET 4.0 |  NET 4.5 |  NET 4.7 |
| --------------- | --------------- | --------------- | --------------- |
| ADCollector | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| ADSearch | :x: | :x: |  :heavy_check_mark: |
| AtYourService | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| BetterSafetyKatz | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| Grouper2 |  :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| InveighZero | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| LockLess | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| PurpleSharp | :x: | :heavy_check_mark: | :heavy_check_mark: |
| Rubeus | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SafetyKatz | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SauronEye |  :x: | :x: |  :heavy_check_mark:|
| scout | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SearchOutlook | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| Seatbelt | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Sharp-SMBExec |  :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| SharpAllowedToAct |  :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| SharpAppLocker | :x: | :heavy_check_mark: | :heavy_check_mark: |
| SharpBlock | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpChisel | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpChrome | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpChromium | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| SharpCloud | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpCrashEventLog | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| SharpDir | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpDoor | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpDPAPI | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpDump | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| SharpFiles | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpGPOAbuse | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpHandler |  :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| SharpHose | :x: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpHound3 | :x: | :heavy_check_mark: |  :x: |
| SharpKatz | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| SharpLaps |  :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| SharpMapExec |  :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| SharpMiniDump | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpMove |  :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| SharpRDP | :x: | :heavy_check_mark: |  :heavy_check_mark:|
| SharpReg | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpSecDump | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| SharpShares | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| SharpSphere |  :x: | :heavy_check_mark: |  :heavy_check_mark:|
| SharpSpray | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpStay | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpSvc | :x: | :x: |  :heavy_check_mark: |
| SharpTask | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| SharpUp | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| SharpView | :x: | :heavy_check_mark: |  :heavy_check_mark:|
| SharpWMI | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpZeroLogon | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| Shhmon | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| Snaffler | :heavy_check_mark: | :x: | :x: |
| SqlClient | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| StandIn |  :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| StickyNotesExtract | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|
| SweetPotato | :x: | :heavy_check_mark: |  :heavy_check_mark:|
| ThunderFox |:heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| TruffleSnout | :x: | :heavy_check_mark: |  :heavy_check_mark:|
| Watson | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| winPEAS | :x: | :heavy_check_mark: |  :heavy_check_mark: |
| WMIReg | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:|

# Sources / Credits
Links for all these amazing tools are below :) 
* [SharpLaps](https://github.com/swisskyrepo/SharpLAPS) - A C# tool to retrieve LAPS passwords from LDAP @pentest_swissky
* [Sharp-SMBExec](https://github.com/checkymander/Sharp-SMBExec) -  A native C# conversion of Kevin Robertsons Invoke-SMBExec powershell script @checkymander
* [SharpSphere](https://github.com/JamesCooteUK/SharpSphere) -  C# SharpSphere has the ability to interact with the guest operating systems of virtual machines managed by vCenter. @jkcoote & @grzryc
* [Grouper2](https://github.com/l0ss/Grouper2) -  C# tool to help find security-related misconfigurations in Active Directory Group Policy. @mikeloss
* [SauronEye](https://github.com/vivami/SauronEye) -  C# search tool find specific files containing specific keywords (.doc, .docx, .xls, .xlsx). @_vivami
* [SharpMove](https://github.com/0xthirteen/SharpMove) -  C# tool for performing lateral movement techniques @0xthirteen
* [SharpHandler](https://github.com/jfmaes/SharpHandler) -  C# tool for stealing/duping handles to LSASS @Jean_Maes_1994
* [SharpMapExec](https://github.com/cube0x0/SharpMapExec) -  C# version of @byt3bl33d3r's tool CrackMapExec @cube0x0
* [SharpAllowedToAct](https://github.com/pkb1s/SharpAllowedToAct) -  C# implementation of a computer object takeover through Resource-Based Constrained Delegation (msDS-AllowedToActOnBehalfOfOtherIdentity) @pkb1s
@leechristensen
* [StandIn](https://github.com/FuzzySecurity/StandIn) -  C# based small AD post-compromise toolkit. @FuzzySec
* [TruffleSnout](https://github.com/dsnezhkov/TruffleSnout) -  C# based iterative AD discovery toolkit for offensive operators. @dsnezhkov
* [SharpSecDump](https://github.com/G0ldenGunSec/SharpSecDump) -  C# port of the remote SAM + LSA Secrets dumping functionality of impacket's secretsdump.py @G0ldenGunSec
* [SharpCrashEventLog](https://github.com/slyd0g/SharpCrashEventLog) -  C# port of LogServiceCrash @slyd0g @limbenjamin
* [SharpKatz](https://github.com/b4rtik/SharpKatz) -  PURE C# port of significant MimiKatz functionality such as logonpasswords, dcsync, etc. @b4rtik
* [SharpZeroLogon](https://github.com/nccgroup/nccfsas/tree/main/Tools/SharpZeroLogon) -  C# port of CVE-2020-1472 , a.k.a. Zerologon. @buffaloverflow
* [SharpChromium](https://github.com/djhohnstein/SharpChromium) -  C# Project to retrieve Chromium data, such as cookies, history and saved logins. @djhohnstein
* [SharpRDP](https://github.com/0xthirteen/SharpRDP) - C# Remote Desktop Protocol Console Application for Authenticated Command Execution @0xthirteen
* [StickyNotesExtract](https://github.com/V1V1/SharpScribbles) - C# tool that extracts data from the Windows Sticky Notes database. @V1V1 
* [ThunderFox](https://github.com/V1V1/SharpScribbles) - C# Retrieves data (contacts, emails, history, cookies and credentials) from Thunderbird and Firefox. @V1V1 
* [SharpAppLocker](https://github.com/Flangvik/SharpAppLocker) - C# port of the Get-AppLockerPolicy PS cmdlet with extended features @Flangvik
* [SqlClient](https://github.com/FortyNorthSecurity/SqlClient) - C# .NET mssql client for accessing database data through beacon. @FortyNorthSecurity
* [SharpDump](https://github.com/GhostPack/SharpDump) - SharpDump is a C# port of PowerSploit's Out-Minidump.ps1 functionality. @GhostPack
* [SharpView](https://github.com/tevora-threat/SharpView) - C# implementation of harmj0y's PowerView. @tevora-threat
* [LockLess](https://github.com/GhostPack/LockLess) - Allows for the copying of locked files. @GhostPack
* [Seatbelt](https://github.com/GhostPack/Seatbelt) - Performs a number of security oriented host-survey "safety checks". @GhostPack
* [SharpDPAPI](https://github.com/GhostPack/SharpDPAPI) -  C# port of some Mimikatz DPAPI functionality. @GhostPack
* [SharpChrome](https://github.com/GhostPack/SharpDPAPI) - Chrome-specific implementation of SharpDPAPI capable of cookies and logins decryption/triage. @GhostPack
* [SharpUp](https://github.com/GhostPack/SharpUp) -  C# port of various PowerUp functionality. @GhostPack
* [Rubeus](https://github.com/GhostPack/Rubeus) -  C# toolset for raw Kerberos interaction and abuses. @GhostPack
* [SharpWMI](https://github.com/GhostPack/SharpWMI) -   C# implementation of various WMI functionality. @GhostPack
* [SafetyKatz](https://github.com/GhostPack/SafetyKatz) - Combination of slightly modified version of @gentilkiwi's Mimikatz project and @subTee's .NET PE Loader.  @GhostPack
* [SharpShares](https://github.com/djhohnstein/SharpShares) - Enumerate all network shares in the current domain. @djhohnstein
* [SharpSpray](https://github.com/jnqpblc/SharpSpray) - C# tool to perform a password spraying attack against all users of a domain using LDAP. @jnqpblc
* [SharpTask](https://github.com/jnqpblc/SharpTask) -  C# tool to interact with the Task Scheduler service api. @jnqpblc
* [SharpDir](https://github.com/jnqpblc/SharpDir) - C# tool to search both local and remote file systems for files. @jnqpblc
* [SharpReg](https://github.com/jnqpblc/SharpReg) - C# tool to interact with the Remote Registry service api. @jnqpblc
* [SharpSvc](https://github.com/jnqpblc/SharpSvc) - C# tool to interact with the SC Manager API. @jnqpblc (Only NET 4.7)
* [Shhmon](https://github.com/matterpreter/Shhmon) - Neutering Sysmon via driver unload. @Shhmon
* [Watson](https://github.com/rasta-mouse/Watson) - Enumerate missing KBs and suggest exploits for useful Privilege Escalation vulnerabilities . @rasta-mouse
* [winPEAS](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite) - PEASS - Privilege Escalation Awesome Scripts (winPEAS). @carlospolop
* [SharpStay](https://github.com/0xthirteen/SharpStay) - .NET project for installing Persistence. @0xthirteen
* [SharpFiles](https://github.com/fullmetalcache/SharpFiles) - C# tool to search for files based on SharpShares output. @fullmetalcache
* [SharpHose](https://github.com/ustayready/SharpHose) - Asynchronous Password Spraying Tool in C# for Windows Environments . @ustayready
* [SharpDoor](https://github.com/infosecn1nja/SharpDoor) - C# tool to allow multiple RDP (Remote Desktop) sessions by patching termsrv.dll file. @infosecn1nja
* [WMIReg](https://github.com/airzero24/WMIReg) - C# PoC to interact with local/remote registry hives through WMI. @airzero24
* [scout](https://github.com/jaredhaight/scout) - A .NET assembly for performing recon against hosts on a network . @jaredhaight
* [SharpBlock](https://github.com/CCob/SharpBlock) - A method of bypassing EDR's active projection DLL's by preventing entry point exection. @CCob
* [SweetPotato](https://github.com/CCob/SweetPotato) - Local Service to SYSTEM privilege escalation from Windows 7 to Windows 10 / Server 2019 . @CCob
* [SharpCloud](https://github.com/chrismaddalena/SharpCloud) - Simple C# for checking for the existence of credential files related to AWS, Microsoft Azure, and Google Compute. @chrismaddalena
* [SharpGPOAbuse](https://github.com/FSecureLABS/SharpGPOAbuse) - SharpGPOAbuse is a .NET application written in C# that can be used to take advantage of a user's edit rights on a Group Policy Object (GPO). @FSecureLABS
* [PurpleSharp](https://github.com/mvelazc0/PurpleSharp) - C# adversary simulation tool that executes adversary techniques with the purpose of generating attack telemetry in monitored Windows environments. @mvelazc0
* [SharpChisel](https://github.com/shantanu561993/SharpChisel) -  C# Chisel Wrapper. @shantanu561993
* [InveighZero](https://github.com/Kevin-Robertson/InveighZero) - Windows C# LLMNR/mDNS/NBNS/DNS/DHCPv6 spoofer/man-in-the-middle tool . @Kevin-Robertson
* [BetterSafetyKatz](https://github.com/Flangvik/BetterSafetyKatz) - Fork of SafetyKatz dynamically fetches the latest Mimikatz, runtime patching signatures and PE loads Mimikatz into memory. @Flangvik
* [SharpHound3](https://github.com/BloodHoundAD/SharpHound3) - C# Rewrite of the BloodHound Ingestor. @BloodHoundAD
* [Snaffler](https://github.com/SnaffCon/Snaffler) - C# tool for pentesters to help find delicious candy needles (creds mostly, but it's flexible). @SnaffCon
* [SearchOutlook](https://github.com/RedLectroid/SearchOutlook) - C# tool to search through a running instance of Outlook for keywords @RedLectroid
* [SharpMiniDump](https://github.com/b4rtik/SharpMiniDump) - C# tool to Create a minidump of the LSASS process from memory  @b4rtik
* [ADSearch](https://github.com/tomcarver16/ADSearch) - C# tool to help query AD via the LDAP protocol @tomcarver16 (Only NET 4.7)
* [ADCollector](https://github.com/dev-2null/ADCollector) - C# tool to quickly extract valuable information from the Active Directory environment @dev-2null
* [AtYourService](https://github.com/mitchmoser/AtYourService) - C# .NET Assembly for Service Enumeration @mitchmoser

