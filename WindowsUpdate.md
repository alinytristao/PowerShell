# PowerShell
1- Update windows update with powershell

  First step to automate the windows upgrade process without WSUS.


PS C:\WINDOWS\system32> Get-History

  Id CommandLine                                                                                                                                       
  -- -----------                                                                                                                                       
   1 $PSVersionTable.PSVersion                                                                                                                                                                      
   2 Install-Module PSWindowsUpdate                                                                                                                    
   3 Get-Command –module PSWindowsUpdate                                                                                                               
   4 Add-WUServiceManager -ServiceID 7971f918-a847-4430-9279-4a52d1efe18d                                                                         
   5 Get-WUInstall –MicrosoftUpdate –AcceptAll –AutoReboot                                                                                             



PS C:\WINDOWS\system32> 
