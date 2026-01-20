# 8-cloud-account
#CLI – Based Cloud Access (Device Code Login)
- Cloud Provider Used : Microsoft Azure
- Authentication Method : The access was obtained using Azure CLI device-code approval in a browser by a peer , where no passwords, access keys, tokens or secret files were shared.
- Purpose :  This alternative proves that cloud operations can be done entirely via CLI using device-code authentication when account signup is not possible.
- SecurityNote : The access was granted only for the duration of the task and was revoked upon completion.
  
##Step of CLI-based cloud access :
1.  Installed and used the Azure CLI on my system.
2.  Logged in using device-code, where a peer approved access using a one-time code.
3.  Verified successful login by checking the active account, subscription, and tenant context through CLI commands.
4.  Listed available Azure regions, resource groups, existing resources, and enabled providers using the CLI.
5.  Created a temporary, free-tier-safe resource group to demonstrate CLI-based cloud operations.
6.  Verified that the resource group was successfully created.
7. Deleted the resource group after verification to ensure proper cleanup.
8.  Confirmed that the resource was removed and that no resources were left behind.
9. Completed all tasks entirely through the command line, and temporary access was revoked after completion.

