# Zendesk-Help-Desk-Lab

## Objective

The Zendesk Help Desk Lab was designed to simulate a Tier 1 IT support environment using a ticketing system. The objective of this project was to practice creating, triaging, prioritizing, and resolving end-user support requests while documenting issues and communicating resolutions through professional, email-based correspondence. This lab emphasizes real-world help desk workflows, ticket lifecycle management, and service-level awareness.


### Skills Learned

- Ticket Creation, Triage, and Resolution
- Incident Prioritization & Escalation
- Professional Email-Based Technical Support
- SLA Awareness & Ticket Lifecycle Management 

### Tools Used

- **Zendesk** – Ticketing system used to create, triage, prioritize, document, and resolve end-user support requests  
- **Email (Zendesk Email Integration)** – Simulated professional email-based technical support and user communication  
- **Windows 11** – End-user operating systems used to simulate common user issues and requests  

## Showcase

### Ticket 01 - Password Reset

#### Ticket Summary
- **Ticket ID:** 001
- **Channel:** Email
- **Category:** Account Access
- **Priority:** Low
- **Status:** Resolved

---

#### User Description
The user reported being unable to sign in to their workstation after multiple failed login attempts and requested assistance resetting their password.

---

#### Environment
- Domain-joined Windows 11 workstation
- Active Directory user account
- Zendesk email-based support

---

#### Initial Triage
- Verified user identity
- Confirmed issue impacted only the user account
- Determined no broader system outage
- Classified as a Tier 1 account access issue

---

#### Troubleshooting & Investigation
1. Reviewed Active Directory user account status
2. Confirmed the account was not disabled
3. Identified that the password was expired
4. Reset the user’s password in Active Directory
5. Verified “User must change password at next logon” was enabled

---

#### Resolution
The user’s password was reset in Active Directory. The user was instructed to sign in using the temporary password and create a new password upon successful login.

---

#### User Communication (Email)

##### Initial Response
> Hello end-user,  
>  
> Thank you for contacting IT support. I’ve received your request and am currently reviewing your account. I’ll follow up shortly with next steps.  
>  
> Best regards,  
> Joshua  
> IT Support

##### Resolution Email
> Hello end-user,  
>  
> Your password has been reset successfully. Please sign in using the temporary password provided and update your password when prompted.  
>  
> If you experience any further issues, feel free to reply to this email.  
>  
> Best regards,  
> Joshua  
> IT Support

---

#### Outcome
- User successfully logged in
- No further issues reported
- Ticket closed within SLA

---

#### Key Takeaways
- Practiced identity verification and account management
- Reinforced clear, professional email communication
- Followed structured Tier 1 troubleshooting workflow

### Ticket 02 - Account Unlock

#### Ticket Summary
- **Ticket ID:** 002
- **Channel:** Email
- **Category:** Account Access
- **Priority:** Low
- **Status:** Resolved

---

#### User Description
The user reported being unable to sign in to their workstation after entering an incorrect password multiple times and received a message indicating their account was locked.

---

#### Environment
- Domain-joined Windows 11 workstation
- Active Directory user account
- Zendesk email-based support

---

#### Initial Triage
- Verified user identity
- Confirmed issue impacted only the user account
- Determined the issue occurred after multiple failed login attempts
- Classified as a Tier 1 account access issue

---

#### Troubleshooting & Investigation
1. Reviewed the user account status in Active Directory
2. Confirmed the account was locked due to failed login attempts
3. Verified the account was not disabled or expired
4. Unlocked the user account in Active Directory
5. Confirmed no additional access restrictions were present

---

#### Resolution
The user’s account was successfully unlocked in Active Directory. The user was instructed to attempt logging in again and confirm successful access.

---

#### User Communication (Email)

##### Initial Response
> Hello end-user,  
>  
> Thank you for contacting IT support. I’m reviewing your account now and will follow up shortly with an update.  
>  
> Best regards,  
> Joshua  
> IT Support

##### Resolution Email
> Hello end-user,  
>  
> Your account has been unlocked successfully. Please try signing in again.  
>  
> If you continue to experience any issues or need further assistance, feel free to reply to this email.  
>  
> Best regards,  
> Joshua  
> IT Support

---

#### Outcome
- User successfully signed in
- No further login issues reported
- Ticket resolved within SLA

---

#### Key Takeaways
- Practiced identifying and resolving account lockout scenarios
- Reinforced proper verification of account status prior to changes
- Demonstrated professional, user-focused email communication
- Followed a structured Tier 1 troubleshooting workflow


### Support Scenarios Simulated

- Password reset and account access issues  
- Locked user accounts requiring verification and resolution  
- General IT inquiries submitted via email  
- Priority-based ticket triage and escalation decisions  
- Follow-up communication and ticket closure documentation

