# Creating A New User in Active Directory 

Active Directory can help manage users and assigned them to groups with in a domain. Here are the steps to take so that users can be created.
#

* Log into the server and access `Active Directory Users and Computers`. One way to get to it is through `Server Manager < Tools < Active Directory Users and Computers`.
  * <img width="750" height="450" alt="Screenshot 2026-09-17 134721" src="https://github.com/user-attachments/assets/5090077f-3334-4cb0-a7b3-8dc51cb60bfd" />

* You will then get prompted with a page that list the domain that you are accessing.
  * <img width="500" height="450" alt="Screenshot 2026-09-17 133123" src="https://github.com/user-attachments/assets/b624054c-c6ac-4768-98f8-3263d4317fea" />
 

* You will see a list of users on the domain that you are managing on the right side, and on the left you will see other selections regarding the users like "groups", "disabled users", "active users" and etc. On that page, you will see certain controls above that look like this..
  * <img width="149" height="19" alt="Screenshot 2026-09-17 133321" src="https://github.com/user-attachments/assets/cb7696c3-9a46-4a13-9729-f7b0e2f7b9f6" />

* Click the icon on the far left as you see above. The icon has a person with a asterisk symbol at the top left of it like this, `*`. 

* You will then be prompted to fill out information about the new user. Usually organizations have a pattern on how users are created and formatted. You can copy a existing user and the user information for the prompt will be auto filled with the common information for a new user.
  * <img width="750" height="450" alt="Screenshot 2026-09-17 133425" src="https://github.com/user-attachments/assets/762cf9d9-28be-4452-ba8f-27f90948e230" />

* After the new user is created, you can double click it. You will then be prompted with different options to select from, see example below...
   * <img width="400" height="450" alt="Screenshot 2026-09-17 133923" src="https://github.com/user-attachments/assets/27eea296-fd87-4144-8988-98feed76c789" />
#

 * From here you can reset the password for the user account, unlock and lock the user account, and assign the user to groups. Some organizations or businesses require users to have a 2 factor authentication method before signing into their account on the domain. Assigning a user to a group that pushes out policies like a 2 factor authentication method can be very useful and a great way to prove integrity that the person is who they say they are, and have confidentiality for the user information before accessing it. 

* Click the `Member of` tab with in the User Properties prompt.
  * <img width="400" height="450" alt="Screenshot 2026-09-17 134105" src="https://github.com/user-attachments/assets/78d77912-2553-46dc-8ad3-94da65902503" />

* A user can be added to a group in this way and have policies assigned to them. Other accounts and admin accounts can also have access to the created user account, you can assign them certain permissions for certain groups as well.
  * <img width="400" height="450" alt="Screenshot 2026-09-17 134135" src="https://github.com/user-attachments/assets/116ae2af-f7fd-4598-898e-407e2dcb9383" />

* Controls like `Full control` gives a account and groups full control over the account, `Read` on gives rights to look over things but can not edit anything, and `Write` is the able edit anything with in the users account.
#

User management is great to use when users are needing certain policies and specialties for their account. Use this when accessing a server with permission.
   
  
