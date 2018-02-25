# Installation

- [Introduct Files](#Introduce)
- [Installation Process](#InstallationProcess)

## Introduce

You will see following files from the archive you have downloaded from CodeCanyon to your server or local server

![Downloaded Files](https://res.cloudinary.com/robinbd/image/upload/v1519583179/codecanyon/crm/folder_structure.png "Downloaded Files")
1. SQL file(crm.sql): You have to import the file in your app database
2. The app file(crm.zip), which one use as admin panel
3. The app file(crm-client.zip), which one use as client panel
4. The Documentation(documentation.html)
5. Update Log(update-log.txt), define the change log file with particular version

## InstallationProcess
1. Extract and copy zip files(crm.zip and crm-client.zip) from the archive you have downloaded from CodeCanyon to your server or local server.
2. Create a database in your mySql server.
3. Import the SQL(crm.sql) file in your created database.
4. You will see a `.env` file where you extract zip files, open the `.env` file in any editor.
5. Then setup your database name, username and password.
6. Setup also `.env` file for client panel.


