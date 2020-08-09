# SharpCollection
Nightly builds of common C# offensive tools, fresh from their respective master branches built and released in a CDI fashion using Azure DevOps release pipelines. 

Is your favorite tool missing? Feel free to open an issue or DM me on twitter [@Flangvik](https://twitter.com/Flangvik)

# Azure DevOps? 
Each night at 03:00 AM, the Azure DevOps pipeline checks for new commits to all repositories master branch. Branches with changes will be automatically fetched and compiled with different framework targets as well as architectures, before being pushed to this repo. 

The pipeline can be found here:
https://dev.azure.com/FlangvikDev/SharpRelease

# Available builds

| Tools \ .NET Framework | NET 4.0 |  NET 4.5 |  NET 4.7 |
| --------------- | --------------- | --------------- | --------------- |
| ADCollector | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpDump | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| LockLess | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| Seatbelt | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpDPAPI | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpUp | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| Rubeus | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpWMI | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SafetyKatz | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpShares | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpSpray | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpTask | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpDir | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpReg | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpSvc | :x: | :x: |  :heavy_check_mark: |
| Shhmon | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| Watson | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| winPEAS | :x: | :heavy_check_mark: |  :heavy_check_mark: |
| SharpStay | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpFiles | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpHose | :x: | :heavy_check_mark: |  :x: |
| SharpDoor | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| WMIReg | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| scout | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpBlock | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpCloud | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpGPOAbuse | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| PurpleSharp | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpChisel | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| InveighZero | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| BetterSafetyKatz | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpHound3 | :x: | :heavy_check_mark: |  :x: |
| Snaffler | :heavy_check_mark: | :x: |  :x: |
| SearchOutlook | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| SharpMiniDump | :heavy_check_mark: | :heavy_check_mark: |  :x: |
| ADSearch | :x: | :x: |  :heavy_check_mark: |
| AtYourService | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |
| SqlClient | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark: |

# Sources / Credits
Links for all these amazing tools are below :) 

* [SqlClient](https://github.com/FortyNorthSecurity/SqlClient) - C# .NET mssql client for accessing database data through beacon. @FortyNorthSecurity
* [SharpDump](https://github.com/GhostPack/SharpDump) - SharpDump is a C# port of PowerSploit's Out-Minidump.ps1 functionality. @GhostPack
* [LockLess](https://github.com/GhostPack/LockLess) - Allows for the copying of locked files. @GhostPack
* [Seatbelt](https://github.com/GhostPack/Seatbelt) - Performs a number of security oriented host-survey "safety checks". @GhostPack
* [SharpDPAPI](https://github.com/GhostPack/SharpDPAPI) -  C# port of some Mimikatz DPAPI functionality. @GhostPack
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

