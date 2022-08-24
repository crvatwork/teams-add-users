# Bulk Add Thing

Insipired by [This post](https://www.sharepointdiary.com/2021/08/bulk-add-users-to-microsoft-teams-using-powershell.html)

## Setup

 Make sure the following is done in powershell (as admin) before running the script

1. ```Set-ExecutionPolicy RemoteSigned```
2. ```Install-Module MicrosoftTeams```
3. ```Import-Module MicrosoftTeams```
4. ```Connect-MicrosoftTeams```

Afterwards you can clean up with

1. ```Uninstall-Module -Name MicrosoftTeams```
2. ```Set-ExecutionPolicy Restricted```
