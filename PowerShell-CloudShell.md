Reactions:

Task 1 - Verify user account

Task 2 - Verify that user should be capable of running PowerShell/CloudShell

Task 3 - Has user been compromised externally? (HaveIBeenPwned)
Playbook: https://github.com/rod-trent/SentinelPlaybooks/tree/master/HaveIBeenPwned-Email

Task 4 - Identify IP address

Task 5 - Verify IP address ownership, location
Playbook: https://github.com/rod-trent/SentinelPlaybooks/tree/master/IPAddr2GEO2Comments 

Task 6 - If local PowerShell, verify process and script. 
KQL for Computer, SubjectUserName, SubjectDomainName, Process, CommandLine, ParentProcessName
https://github.com/rod-trent/SentinelKQL/blob/master/PowerShellExecution.txt 
