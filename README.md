# Setting Up and Managing a Microsoft Entra ID Environment

## Overview
In this lab, I set up a Microsoft Entra ID tenant and worked through essential identity and access management tasks, such as creating users, managing groups, licensing, configuring Conditional Access, enabling Multi-Factor Authentication (MFA), and collaborating with external users.

## Environment Details

- **Platform**: Microsoft Entra ID + Microsoft 365  
- **Tenant Type**: Cloud-only  
- **Subscription**: Microsoft 365 Business Premium (Trial)  
- **Admin Role**: Global Administrator  

## What I Did

1. **Created Internal and External Users**  
   - Created three users with different roles and attributes: 
     - User 1: Basic user role (01, 02, 03)
     - User 2: Guest role - external (04)
   ![06 Users Overview](path/to/screenshot6.png)

3. **Assigned Roles to Myself**  
   - Assigned necessary roles to myself, including Global Administrator.
   ![05 Role Assignment](path/to/screenshot5.png)

4. **Set Up MFA**  
   - Configured Multi-Factor Authentication (MFA) for myself.
   ![Screenshot 7](path/to/screenshot7.png)

5. **Created a New Tenant**  
   - Encountered an issue with obtaining an M365 trial license for the original tenant. Created a new tenant and replicated the user setup to continue testing.
   ![Screenshot 8](path/to/screenshot8.png)
   ![Screenshot 9](path/to/screenshot9.png)
   ![Screenshot 10](path/to/screenshot10.png)


6. **Assigned Licenses to Users**  
   - Assigned Microsoft 365 Business Premium licenses to users for trial testing.
   ![Screenshot 11](path/to/screenshot11.png)
   ![Screenshot 12](path/to/screenshot12.png)
   ![Screenshot 13](path/to/screenshot13.png)

7. **Modified User Licenses**  
   - Adjusted the licenses for internal users based on their roles and requirements.
   ![Screenshot 14](path/to/screenshot14.png)

8. **Created a Security Group**  
   - Created a security group and added internal users to it for role-based management.
   ![Screenshot 15](path/to/screenshot15.png)
   ![Screenshot 16](path/to/screenshot16.png)

9. **Assigned Licenses to Security Group**  
   - Assigned licenses to the security group to streamline user management.
   ![Screenshot 17](path/to/screenshot17.png)

10. **Configured MFA on Security Group**  
   - Set up MFA for the entire security group to enforce additional security measures.
   ![Screenshot 18](path/to/screenshot18.png)

11. **Reviewed Audit Logs**  
   - Analysed audit logs to ensure proper activity tracking and troubleshooting.
   ![Screenshot 19](path/to/screenshot19.png)

## Issues Encountered
- **License Acquisition Issue**: Initially could not obtain a Microsoft 365 trial license for the existing tenant. As a workaround, I created a new tenant and replicated the environment for testing.

## Tools Used
- Microsoft Entra admin center
- Microsoft 365 Admin Center

## Conclusion
I successfully set up and tested core features of Microsoft Entra ID, including user and group management, license assignment, MFA, and Conditional Access. The environment is now fully functional and ready for further testing and integration.
