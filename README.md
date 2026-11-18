# Hospital Active Directory Lab

CNA transitioning into Healthcare IT. I built this lab to learn how hospitals manage users, security and shared files.

## What I Did - Part 1: Active Directory
- Built an Active Directory in Windows Server for a Hospital
- Created an Organizational Unit (OU) for the staff
- Created Security Group for Hosp Staff Group
- Created user account, added user to the group and verified user appears in Active Directory Users and Computers

## What I Did - Part 2: Group Policy + Shared Drive
- Created shared drive: HospitalShare with group permissions for Hospital Staff
- Applied Group Policy: Password Policy (12 char min, 90-day max age, 24 passwords remembered, lockout after 5 attempts)
- Tested login as J.Doe and verified access to HospitalShare
- Fixed drive mapping issue so shared drive shows correctly

## Why This Matters for Healthcare IT
In a hospital, this is how you protect patient data - only the right staff can access the right shared drive, passwords are enforced and workstations are secured so PHI isn't left open.

## Tools Used
- Windows Server
- ADUC
- Group Policy
- VirtualBox

## Skills
- OU Structure Design
- User and Group Management
- IT Support Fundamentals
- Group Policy and Shared Drive Management

## Screenshot
<img width="1913" height="1080" alt="Hosp Staff Group png" src="https://github.com/user-attachments/assets/4d07752e-4c90-4737-a68e-aa55cae14be9" />
