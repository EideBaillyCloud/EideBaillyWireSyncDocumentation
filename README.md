![Eide Bailly Wire Sync App Logo](assests/WireSync_Logo.png)

# Eide Bailly WireSync Function Documentation

Thank you for your interest in the Eide Bailly WireSync App.  This Business Central extension will assist organizations in connecting to a finanical insituation's SFTP site for Lockbox and ACH/Wire transaction retrieval.  Currently, the solution only supports authentication via a user name and x509 certificate.  These credentials, along with the URL for the lockbox site, are securely stored in an Azure Key Vault which is deployed along with the function in the same resource group.  This functionality utilizes the Eide Bailly SFTP Function which is NOT intended to stand alone, rather it should be used in conjuction with the Eide Bailly WireSync app.  

## Overview
The application provides an ability to map file settings and setup to a Cash Receipt Journal.  This involves creating a pointer to the Eide Bailly Azure SFTP setup, creating a mapping of the file setup to a Cash Receipt Journal and then importing the files into Cash Receipt.


## Documentation

1. [WireSync Configuration](docs/wiresync-setup.md)
2. [Field Mappings](docs/wiresync-field-mappings.md)
3. [Imported File List](docs/wiresync-files.md)
4. [Invoice Logs](docs/wiresync-invoice-log.md)
5. [Importing Bank Transactions](docs/wiresync-import-transactions.md)
