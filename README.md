# Power Platform Teams Management


## Summary

Short summary on functionality and used technologies.

This solution allows admins to manage assignment of teams, users and column security roles to Azure AD synced teams via a cnavas app.

I have also included a Power Automate Cloud Flow to create AAD synced team for demo purposes

![picture of the sample](assets/preview.png)

## Applies to

* [Microsoft Power Apps](https://docs.microsoft.com/powerapps/)

## Authors



Solution|Author(s)
--------|---------
ManageSecurityRoles | [Stuart Baxter - Business Applications MVP](LinkToYourGitHubProfile)

## Version history

Version|Date|Comments
-------|----|--------
1.0.0.0|July 22, 2023|Initial release

## Features

> Description of the sample with possible additional details than in short summary.

This sample illustrates the following concepts:

* assigning of security roles to Power Platform Teams by using relate/unrelate
* assigning of column secuirty profiles to Power Platform Teams by using relate/unrelate
* assigning of users to Azure AD groups in a using the Azure Ad connector for Canvas Apps

## Prerequisites

* A Dataverse user account with access to System Admin Security Role
* Permissions to create Azure AD Groups

## Solution Components

> Please list the solution components you use in this sample. See example below.
> DELETE THIS PARAGRAPH BEFORE SUBMITTING

The following solution components are used in this sample:

* Manage Power Platform Teams Canvas App (Canvas app)
* Add a new AAD group and associated Team (Cloud flow)
* AAD Group Admin (Environment variable)
* AAD Manage Security Roles (Connection reference)
* Dataverse Manage Security Roles (Connection reference)
* Manage Security Roles Component Library (Component library)

## Data Sources

Not required

## Minimal Path to Awesome

* [Download](./solution/YOURSAMPLENAME.zip) the solution `.zip` from the `solution` folder
* Within **https://make.powerapps.com**, import the `.zip` file via **Solutions** > **Import solution** > **Browse** and select the `.zip` file you just downloaded.
* Click next.
* ...

## Using the Source Code

You can also use the [Power Apps CLI](https://aka.ms/pac/docs) to pack the source code by following these steps::

* Clone the repository to a local drive
* Pack the source files back into `.zip` file:
  ```bash
  pac solution pack --folder pathtosourcefolder --zipfile pathtosolution  --processCanvasApps
  ```
  Making sure to replace `pathtosourcefolder` to point to the path to this sample's `sourcecode` folder, and `pathtosolution` to point to the path of this solution's `.zip` file (located under the `solution` folder)
* Within **https://make.powerapps.com**, import the `.zip` file via **Solutions** > **Import solution** > **Browse** and select the `.zip` file you just downloaded.
* Click next.
* Click import
* following solution import, run the **Add a new AAD group and associated Team** flow to create a team for demo purposes
* Open the **Manage Power Platform Teams Canvas App** and start using it

## Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

## For more information

- [Overview of creating apps in Power Apps](https://docs.microsoft.com/powerapps/maker/)
- [Power Apps canvas apps documentation](https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/)


