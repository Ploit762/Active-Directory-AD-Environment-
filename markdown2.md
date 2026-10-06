# Assigning a Active Directory (AD) User to a Shared Folder & Drive

When a user is created in AD, they can be assigned to network drives that are on the server. With in the drives you have shared folders. In AD you can manage who get access to those drives and folders, here are the steps grant access to certain folders within a shared drive on a network. Weather the user has `full control`, `modify`, or `Read & execute`, these can all be assigned to users and groups when granting access to the shared folders or drives.
#

* First, access "File Explorer" with in the server and click on "This PC" icon towards the bottom of file explorer on the left side.

  * <img width="134" height="23" alt="Screenshot 2026-09-17 134946" src="https://github.com/user-attachments/assets/b22c05f5-e7d1-4a3f-b5f5-7d71f4d98999" />

* After clicking the icon, click the network drive that you are wanting to access and assign users and groups too it. In this example, drive "Data (F:)" will be the drive that we will be accessing with in the server.
  * <img width="150" height="45" alt="Screenshot 2026-09-17 135001" src="https://github.com/user-attachments/assets/d130eab8-2954-475a-8371-4e433cd93c4f" />

* From here, you can right click on the drive that you are wanting to accesses, click "Properties", and view the "Security" tab. From here you can set users and groups that had been made in AD to access the network drive with certain permissions.

* If you are wanting to give access and certain permissions to a user or group with in the network drive, click on the drive and then locate the folder that you are wanting to access. In this example, I will be accessing a shared folder called "Shared".
  * <img width="339" height="269" alt="Screenshot 2026-09-17 135040" src="https://github.com/user-attachments/assets/33ac8859-7210-44ef-8485-dc82ed2829b6" />

* Right click the folder and then click "Properties". From here you can edit users and groups with in the shared folder to have `Full control`, `Modify`, and `Read & execute` permissions. 
  * <img width="720" height="499" alt="Screenshot 2026-09-17 135122" src="https://github.com/user-attachments/assets/e7c0e2fe-9753-4ef1-abdb-9ea4f05bfd7f" />
  #
* `Full Control` permission grants users or groups full admin access to edit, move, delete, view, and manage the shared folder or the files with in the shared folder.
* `Modify` permission grants users or groups to read, write, and delete anything with the shared folder like full control, but does not give you full admin rights to have ownership of the file or folder to set permissions and edit them.
* `Read & execute` permission grants users or groups to view file content with in the shared folder while not giving access to the ability of editing, creating, or deleting data. 
  
 
