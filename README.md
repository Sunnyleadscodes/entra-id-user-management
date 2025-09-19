# Create and Manage Microsoft Entra ID Users in the Portal
📖 Introduction

Microsoft Entra ID is a core identity and access management platform within Azure. It goes beyond storing credentials by enabling centralized authentication, authorization, and security management.
In this hands-on lab, I practiced performing common administrative tasks for user accounts in Entra ID, including creating, modifying, resetting, revoking, and deleting users.

🛠️ Lab Objectives

Log in to the Azure portal and navigate to Microsoft Entra ID.

Create new Entra ID user accounts.

Modify user account properties and reset passwords.

Revoke user sessions.

Delete and restore user accounts.

🚀 Steps Performed
1. Create Microsoft Entra ID User Accounts

Navigated to Entra ID → Users → New User → Create new user.

Entered a User principal name and Display name for each account.

Reviewed configurable properties, then created two new accounts.

Verified users appeared in the All users list after refreshing.

2. Modify a User Account

Opened the user profile and explored available settings.

Edited properties such as First name, Last name, Job title.

Reset the user password, generating a temporary password.

3. Revoke Access

From the user profile, selected Revoke sessions to log the user out of active sessions.

4. Delete a User Account

Selected a user in the All users list and deleted it.

Verified the account appeared in the Deleted users list.

Noted that deleted users can be restored or permanently deleted within 30 days.

✅ Key Learnings

Entra ID provides a central hub for identity management in Azure.

Administrators can quickly handle lifecycle tasks: creation, updates, password resets, session revocation, and deletion.

Deleted accounts are soft-deleted for 30 days, allowing recovery if needed.

User management is foundational for both day-to-day operations and exam prep (AZ-104, SC-300, etc.).

🏆 Conclusion

This lab reinforced the importance of proper identity lifecycle management in Microsoft Entra ID. These skills are critical for securing cloud environments and ensuring smooth access management.entra-id-user-management
Hands-on lab demonstrating how to create, manage, and delete users in Microsoft Entra ID using the Azure portal
