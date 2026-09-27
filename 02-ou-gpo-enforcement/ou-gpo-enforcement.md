# Project 2: OU-Scoped Group Policy Enforcement

# The Purpose of This Lab

To demonstrate how important a GPO is to an organization. GPOs can be linked to computers, users or OUs providing centralized management, so an organization's resources are secured across the environment. In a domain environment, GPOs are routinely utilized to restrict actions and enforce a consistent policy.

### Business Context

The IT department has been requested to test and apply different group policies to their organization. For testing purposes, a GPO was applied to the HR OU and compared against an IT OU. 

### Lab Environment

* VMware
* DNS (integrated with AD)
* Windows Server Domain Controller
* Windows 11 domain-joined client
* `lab.local` Active Directory domain
* Multiple departmental OUs (IT vs. HR)
* Group Policy Management Console

### OU Structure

Lab.local is organized into the following departments:

* IT
* HR

### Setting Up GPO for an HR OU

* GPO was created and linked to the HR OU.
* Policy created was "Remove Recycle Bin from desktop".
* Policy applied at next user login.
