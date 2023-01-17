# CAI-Softener
PowerShell script and exe that disables security on Windows so that Computer Arts applications can be installed.

This script is a PowerShell script that makes changes to the system settings of a Windows computer. It disables User Account Control (UAC), disables Data Execution Prevention (DEP), disables the firewall, and configures .vbs files to run as administrator. These changes can potentially make the computer more vulnerable to security threats, so it is important to use caution when running this script.

It also prompts the user for a restart, It's asking the user if they would like to restart the computer now or later to apply the changes.

It is important to note that running the script with the command (Set-ExecutionPolicy Unrestricted) to allow PowerShell to run scripts before running this script. It also important to know that disabling UAC requires a computer restart and disabling the firewall will make the computer more vulnerable to security threats, so it is important to use caution when making these changes.
