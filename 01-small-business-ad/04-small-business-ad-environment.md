# Project 1: Small Business Active Directory Environment

# The Purpose of This Lab

To demonstrate that when an identity is onboarded to the organization, the principle of least privilege is defined. Managing access to employees is crucial in a world that relies heavily on securing resources. Segmenting users into containers that define their roles will establish a hardened environment. Delegated control is an important process that defines what the user is authorized to do.

### Business Context

Lab.local is a small company that is expected to grow in the near future. As the organization grows, utilizing an organized Active Directory environment is crucial for managing its users, computers, security groups, and administrative access.

### Lab Environment

* VMware
* DNS (integrated with AD)
*  Windows Server Domain Controller
* Windows 11 domain-joined client
* `lab.local` Active Directory domain
* Multiple departmental OUs
* User and security group configuration
* Delegated administration

### OU Structure

Lab.local is organized into the following departments:

* IT
* HR
* Sales

![OUs](https://github.com/TreSmith-Burke/IAM-Portfolio/blob/b55acfccbad0abc709f79b3edd7e2ca477ef45e7/01-small-business-ad/project-screenshots/4.%20OUs.png)

### Creation of IT User in ADUC

* IT user is created within the IT OU.

![Creating User in AD](https://github.com/TreSmith-Burke/IAM-Portfolio/blob/7686044dd6646873b91d0fcb1288e54880fb7213/01-small-business-ad/project-screenshots/01.%20Create%20User.png)

### Creation of Security Group
  
* Security group is created for appropriate access.

This summarizes the group the user is placed in and would determine the folders, files, and access permitted.

![SG is created](https://github.com/TreSmith-Burke/IAM-Portfolio/blob/7686044dd6646873b91d0fcb1288e54880fb7213/01-small-business-ad/project-screenshots/02.%20Create%20Security%20Group.png)

### Delegate Control for IT user

* Delegated control is configured for the IT user.

This summarizes what type of control the user can do within this OU.

![Delegated control](https://github.com/TreSmith-Burke/IAM-Portfolio/blob/7686044dd6646873b91d0fcb1288e54880fb7213/01-small-business-ad/project-screenshots/03.%20Delegate%20Control.png)
