Ready to use docker 


*********** How can install wsl2 on windows ***********
check your windows version over than 1903 Build 19362
if ARM64 system , need version over than 2004 Build 19041

open wsl
1 - dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart

open Hyper-V
2 - dism.exe /online /enable-feature /featurename:VirutalMachinePlatform /all /norestart
maybe you can see a probleme VirutalMachinePlatform not found , but that's okay.

3 - restart your computer

4 - run powershell as administrator

Set the default version by wsl2
5 - wsl --set-default-version 2

6 - restart your computer (done)


************ How can install ubuntu 20.04 by wsl ************
1 - search linux in Microsoft store
2 - chose ubuntu 20.04 LTS 
3 - get and intall
4 - set a user name and password (done)