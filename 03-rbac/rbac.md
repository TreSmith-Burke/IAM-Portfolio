# Project 3: Role-Based Access Control (R-B-A-C)

# The Purpose of This Lab

To demonstrate the importance of Role-Based Access Control (RBAC) in an organization by ensuring users only have access to the shared resources required for their roles.

### Business Context

Organizations have an important responsibility when managing employee access to resources. Ensuring employees have the appropriate access is crucial to preventing unauthorized access to sensitive information. Implementing RBAC through Active Directory simplifies access management while supporting the principle of least privilege. This reduces the need to assign permissions to individual users, as access can be managed through security group membership and inherited permissions

### Lab Environment

* VMware
* DNS (integrated with AD)
* Windows Server Domain Controller
* Windows 11 domain-joined client
* `lab.local` Active Directory domain
* Multiple departmental OUs (IT vs. HR vs. Sales)
* Group Policy Management Console

### OU Structure

Lab.local is organized into the following departments:

* IT
* HR
* Sales

