### StartManagedFolderAssistant.ps1
This script will attempt to run MFA once every 15 minutes for the user specified. This is usually used in extreme cases where MFA has not processed in months and a mailbox has reached 50+ GBs in size. (Exchange online has an 100GB mailbox limit.)

This method is usually used in conjunction with the [MRM diagnostic script](https://gallery.technet.microsoft.com/office/Powershell-script-to-2489e63b)
