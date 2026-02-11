# Zendesk-Help-Desk-Lab

## Objective

Simulate a Tier 1 help desk environment using Zendesk to handle real world support tickets from intake to resolution. Practiced triaging requests, setting priorities, troubleshooting user issues, and communicating clearly through professional email correspondence.

### Skills Learned

- Ticket creation, triage, and resolution
- Incident prioritizaition based on impact and urgency
- Active Directory account management
- Clear, professional end user communication

## Ticket 01 - Password Reset

### Ticket Summary
- **Ticket ID:** 001
- **Channel:** Email
- **Category:** Account Access
- **Priority:** Low
- **Status:** Resolved


A member of the sales team submitted a ticket in the morning stating that she had forgotten her password and requested a reset. An initial email was sent to acknowledge the request and confirm that the issue was being worked on.

<img width="861" height="520" alt="ticket1-1" src="https://github.com/user-attachments/assets/417fea75-7cc8-4b6f-b504-e6ea4186dd66" />


Because the issue affected a single user and there was no indication of time sensitivity, the priority was set to low.

<img width="145" height="78" alt="priority_low" src="https://github.com/user-attachments/assets/2e2c6dd6-cffd-443a-aacd-360197632577" />


Here are the steps I took to resolve the issue:

1. Reviewed Active Directory user account status
2. Confirmed the account was not disabled
3. Reset the user’s password in Active Directory
4. Verified “User must change password at next logon” was enabled

<img width="1506" height="1056" alt="reset password" src="https://github.com/user-attachments/assets/d316edb0-a304-4e0f-9112-21038abbecee" />
<img width="1009" height="751" alt="login successful" src="https://github.com/user-attachments/assets/ef8915a0-910f-476f-bc84-3182ef501fae" />

A follow up email was sent to the end user instructing her to sign in using the temporary password and create a new password upon successful logon. After successfully resolving the issue, the ticket was closed.

## Ticket 02 - Account Unlock

### Ticket Summary
- **Ticket ID:** 002
- **Channel:** Email
- **Category:** Account Access
- **Priority:** Low
- **Status:** Resolved

a member of teh sales team submitted a ticket indicating that her account had become locked after multiple unsuccessful login attempts. An initial response was sent to confirm the issue was being reviewed and that an update would follow shortly.

IMAGE

Again, because the issue affected a single user and there was no indication of time sensitivity, the priority was set to low.

IMAGE

Here are the steps I took to resolve the issue:

1. Reviewed the user account status in Active Directory
2. Confirmed the account was locked due to failed login attempts
3. Verified the account was not disabled or expired
4. Unlocked the user account in Active Directory

2 IMAGES

A follow up email was sent confirming that the account had been unlocked and instructing the user to attempt signing in again. She was advised to reach out if any further issues occurred, and the ticket was closed.
