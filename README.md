# FTPClient
FTP client that connects to the filezilla server , you can perform functions such as uploading/downloading files, creating/renaming/deleting folders , moving between directories

# Function
- Conexion with server
- Dowload/Upload files
- Move between directory
- Create/Delete directory
- Rename files/directory
- List files

# Admin Function`s
- Create/Delete/Update/Read Users
- Create/Delete/Update/Read configurations

# Getting Started
Follow these steps to set up and run the FTP Client application successfully.

1. Clone the Repository
First, clone the project to your local machine:
git clone https://github.com/your-username/ftp-client.git

2. Download and Install the FTP Server
This application is designed to work with FileZilla Server.
Download FileZilla Server from the official website:
https://filezilla-project.org/download.php?type=server
Install it on your local machine following the installer instructions.

3. Configure FileZilla Server
Once installed:
Set up the FTP server to run on:
IP address: 127.0.0.1
Port: 21 (default FTP port)
Make sure to create at least one FTP user account with appropriate directory access for testing.

4. Check the resources Folder
Before running the client, make sure to verify the contents of the resources/ folder:
This folder contains:
User data (login credentials and roles)
FTP configuration files

⚠️ Important: Do not change the format or structure of these files. The application depends on the expected layout. Any modifications may prevent the system from working properly.
   
