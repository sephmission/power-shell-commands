# Powershell Commands
Use these commands to help you in technical and administration support to our users/computers


## Restore Points

1. To see the system restore points, you need to enter the command `Get-ComputerRestorePoint`

2. To restore in a given time, type `Restore-Computer` resets the computer at the time of the restore point specified in ***SequenceNumber*** . To discover this number, run `Get-ComputerRestorePoint` , after which, the wizard goes about its task without a prompt.

3. To create a recovery point in PowerShell, use: `Checkpoint-Computer -description <description>`

## Processes

1. To see all the processes, type `Get-Process | ogv`
2. To stop a process, type `Stop-Process -name <ProcessName>`

## Renaming a Computer
1. Type `Rename-Computer <Name>`

