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

<img width="853" height="279" alt="ticket1-2" src="https://github.com/user-attachments/assets/1b6f203c-aa68-49d7-b2cf-0f4bdbed9a75" />


## Ticket 02 - Account Unlock

### Ticket Summary
- **Ticket ID:** 002
- **Channel:** Email
- **Category:** Account Access
- **Priority:** Low
- **Status:** Resolved

a member of the sales team submitted a ticket indicating that her account had become locked after multiple unsuccessful login attempts. An initial response was sent to confirm the issue was being reviewed and that an update would follow shortly.

<img width="857" height="478" alt="ticket2-1" src="https://github.com/user-attachments/assets/84d35006-404d-40cf-8a63-cca0a7ab3243" />

Again, because the issue affected a single user and there was no indication of time sensitivity, the priority was set to low.

<img width="145" height="78" alt="priority_low" src="https://github.com/user-attachments/assets/937ca802-d4fb-40d7-b5ae-fb2601d187b2" />


Here are the steps I took to resolve the issue:

1. Reviewed the user account status in Active Directory
2. Confirmed the account was locked due to failed login attempts
3. Verified the account was not disabled or expired
4. Unlocked the user account in Active Directory

<img width="1007" height="751" alt="ad_account_locked" src="https://github.com/user-attachments/assets/3cf9a558-f905-4201-972c-9385c8b08f82" />
<img width="820" height="1075" alt="ad_account_unlocked" src="https://github.com/user-attachments/assets/3f20b525-d7b6-4b10-9706-436e4e9ea65c" />
<img width="1009" height="751" alt="login successful" src="https://github.com/user-attachments/assets/f4b32f64-d600-4d7b-97db-9836b2c295f0" />


A follow up email was sent confirming that the account had been unlocked and instructing the user to attempt signing in again. She was advised to reach out if any further issues occurred, and the ticket was closed.
<img width="792" height="253" alt="ticket2-2" src="https://github.com/user-attachments/assets/e1a50065-cbc9-4962-9c6e-bf41ab3fd9d8" />
