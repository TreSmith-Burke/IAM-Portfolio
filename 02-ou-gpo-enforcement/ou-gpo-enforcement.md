# Project 2: OU-Scoped Group Policy Enforcement

# The Purpose of This Lab

To demonstrate how important GPOs are to an organization. GPOs can be linked to OUs and applied to users or computers, providing centralized management across the environment. In a domain environment, GPOs are routinely utilized to restrict actions, enforce consistent policies, and manage configurations across the organization.

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

### Linking GPO to an HR OU

* GPO was created and linked to the HR OU.

Group Policy Management is where administrators configure policies and restrictions that apply to users and computers within an organization.

![Linking GPO to HR OU](https://github.com/TreSmith-Burke/IAM-Portfolio/blob/a5c2264cb324d4364343721ffb7e4457f3ce64e3/02-ou-gpo-enforcement/project-screenshots/1.%20Link%20GPO%20to%20HR%20OU.png)


### GPO Enabled

* Policy enabled was "Remove Recycle Bin from desktop".

When the HR user navigates to their desktop, they will not be able to see the Recycle Bin icon display.

![GPO Policy enabled](https://github.com/TreSmith-Burke/IAM-Portfolio/blob/a5c2264cb324d4364343721ffb7e4457f3ce64e3/02-ou-gpo-enforcement/project-screenshots/2.%20Enable%20Remove%20Recycle%20Bin%20icon%20from%20desktop%20GPO.png)

### GPO Successfully Applied

* Confirmation that the Recycle  Bin is not being shown.

  ![GPO successfully applied to HR user](https://github.com/TreSmith-Burke/IAM-Portfolio/blob/a5c2264cb324d4364343721ffb7e4457f3ce64e3/02-ou-gpo-enforcement/project-screenshots/3.%20Confirmation%20Recycle%20Bin%20is%20removed.png)

