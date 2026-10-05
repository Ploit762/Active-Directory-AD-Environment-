# Installing & Configuring Active Directory

Here are the steps to installing Active Directory (AD) on Windows. Keep in mind that Active Directory server role can only be installed on a Windows Server, which will come with AD, but you will still need to configure it. You can install Remote Server Admin tools (RSAT) on a standard Windows device to manage server remotely that has AD. Remember, that Windows 11 Home does not support Active Directory, or any RSAT tools. You will need Windows 11 Pro or enterprise to install Active Directory management tools. 
#

*  Open the Start menu, then click on Settings. Press `Win + I` shortcut to also open the Windows settings.
*  Navigate to Apps and select Optional features.
*  Click the View features button next to "Add an optional feature".
*  Type `RSAT` or `Active Directory` in the search box.
*  Check the box for `RSAT`: `Active Directory Domain Services and Lightweight Directory Services Tools`.
*  Click "Next", then click Install and wait for the download to finish.
*  Once installed, press `Win + R`, or right click the Windows icon and click `Run`. Type `dsa.msc`, and press "Enter" to open Active Directory Users and Computers.


