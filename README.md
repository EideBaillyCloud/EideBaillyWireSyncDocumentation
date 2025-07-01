![Eide Bailly Wire Sync App Logo](assests/WireSync_Logo.png)

# Eide Bailly WireSync Function Documentation

Thank you for your interest in the Eide Bailly WireSync App.  Thank you for your interest in the Eide Bailly WireSync App. This Dynamics 365 Business Central extension assists organizations in connecting to their financial institution's SFTP site for Lockbox and ACH/Wire transaction retrieval. This functionality relies upon the [Eide Bailly SFTP Lockbox Function](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/eidebaillyllp.azure_sftp_lockbox). This Dynamics 365 Business Central extension will not function as intended without first deploying the [Eide Bailly SFTP Lockbox Function](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/eidebaillyllp.azure_sftp_lockbox) into an Azure subscription. Currently, the [Eide Bailly SFTP Lockbox Function](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/eidebaillyllp.azure_sftp_lockbox) solution supports authentication via username and password or an x509 certificate. These credentials, along with the URL for the lockbox site, are securely stored in an Azure Key Vault which is deployed along with an Azure Function within the same resource group in your Azure subscription as part of the Eide Bailly SFTP Lockbox Solution.

The documentation for the Eide Bailly SFTP Lockbox Solution can be found here: [Eide Bailly SFTP Lockbox Documentation](https://github.com/EideBaillyCloud/EideBaillySFTPLockboxDocumenation) 

## Overview
The application provides an ability to map file settings and setup to a Cash Receipt Journal.  This involves creating a pointer to the Eide Bailly Azure SFTP setup, creating a mapping of the file setup to a Cash Receipt Journal and then importing the files into Cash Receipt.


## Documentation

1. [WireSync Configuration](docs/wiresync-setup.md)
2. [Field Mappings](docs/wiresync-field-mappings.md)
3. [Imported File List](docs/wiresync-files.md)
4. [Invoice Logs](docs/wiresync-invoice-log.md)
5. [Importing Bank Transactions](docs/wiresync-import-transactions.md)
