# Octopus Lite for ForgeRock

**Octopus Lite™** provides ForgeRock users with the fastest and safest
way to close the desktop security gap. The first desktop MFA solution to
integrate fully with the ForgeRock directory and mobile app, **Octopus
Lite™** offers unprecedented endpoint security using the familiar
ForgeRock authenticator. The solution offers end users the best MFA
experience while relieving IT teams from the expensive and cumbersome
deployment of OTP tokens and security keys to protect workstations.

**Octopus Lite™** is a plug-and-play solution that is easy to install on
employee endpoints. No dedicated server is required, enabling fast
deployment for the entire workforce. ForgeRock customers can now
dramatically boost their domain security, improve user experience, and
take the first step toward becoming fully passwordless in the future.

To sign up for a [14-day free trial of **Octopus Lite™**, click
here](https://go.doubleoctopus.com/octopus-lite-free-trial).

![](.//media/image1.png)

## Authentication Flow

The high-level workflow for authentication to Windows / Mac using
**Octopus Lite™** is shown in the diagram below.

![Diagram Description automatically generated](.//media/image2.png)

## Getting Started

Before you begin, you will need to obtain the Octopus Lite for Windows
MSI package from Secret Double Octopus. Please contact us
at <sales@doubleoctopus.com> for assistance or for more information.

For assistance with technical issues, please
contact <support@doubleoctopus.com> or <frank.gasparovic@forgerock.com>

## Prerequisites

Before beginning installation, verify that:

  - Workstations have **Windows 10** and support **TPM version 2.0**

  - The ForgeRock IAM environment is connected to Active Directory

  - Users are enrolled on the ForgeRock Authenticator App

  - You have obtained the Octopus Lite for Windows MSI package

# MSI Deployment of Octopus Lite

Silent installation allows administrators to push the installation to
all client machines from a central tool (e.g., GPO). All required
components are installed as part of the deployment.

**Note:** Administrator permissions are required to run the Octopus Lite
MSI.

To perform silent installation:

1.  **Open the command prompt as Admin**, and run  
    *Octopus Lite For Windows (64bit).msi*

2.  Run *Octopus Lite for windowsxx.msi*:  
    *C:\\\>msiexec -i Octopus Lite For Windows 64bit – xx\_xxx\_xx.msi
    /qn*

![](.//media/image3.png)

The figure below shows the Windows Login screen following successful
installation.

![](.//media/image4.png)

[Click here to watch the demo
video](https://vimeo.com/523806230/2aa0b92ca5) demonstrating the login
flow.
