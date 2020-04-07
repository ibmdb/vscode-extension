# vscode-extension
vscode extenstion for db2 as db2connect

# Prerequisites
node.js and npm

### This repository is mainly to track the issues related to db2connect vscode extension available on https://marketplace.visualstudio.com.
Please open an issue [here](https://github.com/ibmdb/vscode-extension/issues) for any kind of help or to report a bug.

## For z/OS and iSeries Connectivity

For connectivity against DB2 for LUW or Informix Server using db2connect vscode extension, 
no license file is required. However, if you want to use db2connect vscode extension 
against DB2 for z/OS or DB2 for i(AS400) Servers, you must have db2connect 
license of version 11.1 if server is not db2connectactivated to accept
unlimited number of client connection. You can buy db2connect license from IBM.
The connectivity can be enabled either on server using db2connectactivate
utility or on client using client side license file. If you have client side
license file, just `.../extensions/db2connect/node_modules/ibm_db/installer/clidriver/license` folder to be effective.

To know more about license and purchasing cost, please contact [IBM Customer Support](http://www-05.ibm.com/support/operations/zz/en/selectcountrylang.html).
