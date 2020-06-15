# SharpCollection
Nightly builds of common C# offensive tools, fresh from their respective master branches built and released in a CDI fashion using Azure DevOps release pipelines. 

Is your favorite tool missing? Feel free to open an issue or DM me on twitter [@Flangvik](https://twitter.com/Flangvik)

# Azure DevOps? 
Each night at 03:00 AM, the Azure DevOps pipeline checks for new commits to all repositories master branch. Branches with changes will be automatically fetched and compiled with different framework targets as well as architectures, before being pushed to this repo. 

The pipeline can be found here:
https://dev.azure.com/FlangvikDev/SharpRelease

# Sources / Credits
Links for all these amazing tools are below :) 

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
* [SharpReg](https://github.com/jnqpblc/SharpReg - C# tool to interact with the Remote Registry service api. @jnqpblc
* [SharpSvc](https://github.com/jnqpblc/SharpSvc) - C# tool to interact with the SC Manager API. @jnqpblc
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

