# Mastering Active Directory & Azure: Permissions, Security Groups, and PowerShell Scripts

[![Watch the video](https://github.com/KLavallais/KLavallais/blob/assets/Mastering%20AD%20and%20Azure.png)](https://youtu.be/j_g_Btgh_dE)

## Summary

In this video, I walk you through how I manage Active Directory and Azure, focusing on creating permissions for folders, system users, and security groups. Using two virtual machines in Microsoft Azure, I demonstrate how to set up folder permissions, generate random usernames with PowerShell, and assign users to security groups like "Accountants."

This tutorial is hands-on and practical, showing you exactly how I handle folder permissions (read, write, and no access) and verify these settings across both my domain controller and client machines.

Whether you're new to cloud technology or looking to improve your skills in Azure AD management, I’ll provide useful tips and techniques to help you better manage your IT environments.

---

## Tools/Programs Used:
- **Microsoft Azure**: I use Azure to create and manage virtual machines.
- **Active Directory (AD)**: Essential for managing users, groups, and permissions in a networked environment.
- **Remote Desktop Connection**: I use this to access and manage my virtual machines.
- **PowerShell**: I automate the generation of random usernames using a custom script.
- **Windows Server 2022**: The operating system running on my domain controller and client machines.

---

## Skills Demonstrated:
- **Active Directory Setup & Management**: I show how to create user accounts, security groups, and manage folder permissions.
- **PowerShell Scripting**: Watch as I automate user creation by generating random usernames with a custom script.
- **Folder Permissions Management**: I demonstrate how to set up and manage read, write, and no access permissions for different folders and groups.
- **Security Group Assignment**: I create and assign users to security groups, like "Accountants," and apply group-based folder permissions.
- **Real-time Troubleshooting**: I verify permissions on client machines, ensuring that the correct access levels are applied in real time.

---

## What You’ll Learn:

- **Active Directory & Azure Integration**: See how I integrate Active Directory with Azure and manage users and security groups effectively.
- **PowerShell Mastery**: Learn how I execute a PowerShell script to generate 1,000 random usernames, showcasing PowerShell’s flexibility for user management.
- **Permissions Handling**: I explain folder permissions like read, write, and no access, showing how they affect user behavior.
- **Security Group Management**: Watch me create and assign users to security groups like "Accountants" and manage group-based folder permissions.
- **Practical Demonstrations**: Follow along as I demonstrate real-time folder permission management and user interaction, both in the domain controller and client environments.

---

## Video Walkthrough

### Step 1: PowerShell Script for Random Usernames

I start by demonstrating a custom PowerShell script that generates 1,000 random usernames. I run the script in PowerShell ISE, select one of the generated usernames, and log in to proceed with the rest of the steps.

### Step 2: Assigning Users to Security Groups

After generating usernames, I create a security group called "Accountants" in Active Directory and assign the randomly generated user to it. I explain why assigning users to the right security groups is crucial for managing folder permissions.

### Step 3: Folder Permissions Setup

I create four folders in the domain controller, each with different permissions:
- **Accounting Folder**: Assigned to the "Accountants" group with read and write permissions.
- **No Access Folder**: Restricted folder where users have no permissions.
- **Write Access Folder**: Users are granted write permissions.
- **Read Access Folder**: Users are given read-only access.

### Step 4: Verifying Permissions on Client Machine

I then log into the client machine using the randomly generated user ("fur.wax") to test the folder permissions:
- In the **Accounting Folder**, I verify both read and write access.
- In the **No Access Folder**, access is completely denied.
- In the **Write Access Folder**, I test writing and saving files.
- In the **Read Access Folder**, I show that writing is restricted, as expected for read-only access.

### Step 5: Conclusion

I wrap up by confirming the folder permissions and giving a final overview of how these settings work in real-world scenarios. I also highlight the benefits of automating user creation and managing permissions at scale in an IT environment.

---

## Final Thoughts

This tutorial provides an in-depth look at how I manage Active Directory and Azure environments, including PowerShell scripting for user automation and folder permission management. Whether you're a beginner or an experienced IT professional, this guide offers practical skills that you can apply in your own environments.


---

### For my previous post where I install Active Directory, go [here](https://github.com/KLavallais/InstallAD).

