# **CONNECT TO SQL SERVER**

Since I am using VS Code let's start by installing the mssql extension.

After installing the extension we need to Add Connection. Here's the info needed:
  - Server name (type ```SELECT @@SERVERNAME```) and copy-paste into VS Code.
  - Database is optional, not needed for now
  - Integration type: Integrated means Windows Authentication
  - Profile Name: A name of your choice to the connection

After that click the Enable Trust Server Certificate button.