# Project 1: Small Business Active Directory Environment

### Business Context

Lab.local is a small company that is expected to grow in the near future. As the organization grows, utilizing an organized Active Directory environment is crucial for managing its users, computers, security groups, and administrative access.

### Lab Environment

* Windows Server Domain Controller
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

### Setting Up IT User in AD

* IT user is created within the IT OU
* Security group is created for appropriate access
* Delegated control is configured for the IT user

# The Purpose of This Lab

To demonstrate that when an identity is onboarded to the organization, the principle of least privilege is defined. Managing access to employees is crucial in a world that relies heavily on securing resources. Segmenting users into containers that define their roles will establish a hardened environment. Delegated control is an important process that defines what the user is authorized to do.
