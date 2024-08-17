# Linux-Systems-Administration
In this module's class activities, you acted as a system administrator to troubleshoot a malfunctioning Linux server.


Step 1: Ensure Permissions on Sensitive Files
The /etc/ directory is where system configuration files exist. Start by navigating to this directory with cd /etc/.

Inspect the file permissions of each of the following files. You should have already done this during an in-class activity, but double check them now. If any file's permissions do not match the descriptions listed here, update the file's permissions.

Permissions on /etc/shadow should allow only root read and write access.

Permissions on /etc/gshadow should allow only root read and write access.

Permissions on /etc/group should allow root read and write access, and allow everyone else read access only.

Permissions on /etc/passwd should allow root read and write access, and allow everyone else read access only.


Step 2: Create User Accounts
In this step, you'll set up various users in the system. For this exercise, use the useradd command. Research this command to determine how to best use this tool to create the user accounts. The necessary commands do not require that you work from a specific directory.

Add user accounts for sam, joe, amy, sara, and admin1.


Step 3: Create User Group and Collaborative Folder
Now, you'll run the commands to fully set up a group on your system.

This requires you to create a group, add users to it, create a shared group folder, and set the group folder owners for this shared folder.

Add the group engineers to the system.

Add users sam, joe, amy, and sara to the managed group. The process is similar to the one you used to add admin1 to the sudo group in the previous step.

Create a shared folder for this group: /home/engineers.

Change ownership on the new engineers' shared folder to the engineers group.


Step 4: Lynis Auditing
The final step on your administrator's list involves running an audit against the system in order to harden it. You'll use the system and security auditing tool Lynis to do so.

Install the Lynis package to your system if it is not already installed.

Check the Lynis documentation for instructions on how to run a system audit.

Run a Lynis system audit with sudo.

Provide a report from the Lynis output with recommendations for how to harden the system.
