# BitlockerPIN
Intune Bitlocker PIN Capability

The goal of this solution is to enable the end user to enter a Bitlocker PIN upon login once Windows Autopilot has completed. 
Since the PIN requires elevated rights, to bypass this we leverage the ServiceUI.exe file from the Microsoft Deployment Toolkit and use it to run the Powershell script as System via a scheduled task and display to the user.
