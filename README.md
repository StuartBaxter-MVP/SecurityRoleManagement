# Title of the sample

> When naming your sample, try to give it a friendly name that describes what it does. Avoid using terms like `PowerApp`, `PowerApps`, `Power App`, etc. -- because that's what all the samples in this repo are all about.
> GOOD 👍:
>     Transmographier
> BAD 👎:
>     Power App Sample
>
> DELETE THIS PARAGRAPH BEFORE SUBMITTING


## Summary

Short summary on functionality and used technologies.

This solution allows admins to manage assignment of teams, users and column secuirty roles to Azure AD synced teams via a cnavas app.

I have also included a Power Automate Cloud Flow to create AAD synced team for demo purposes

![picture of the sample](assets/preview.png)

## Applies to

* [Microsoft Power Apps](https://docs.microsoft.com/powerapps/)



## Compatibility

> Don't worry about this section, we'll take care of it. Unless you really want to...

![Power Apps Source File Pack and Unpack Utility 0.20](https://img.shields.io/badge/Packing%20Tool-0.20-green.svg)
![Premium License](https://img.shields.io/badge/Premium%20License-Not%20Required-green.svg "Premium Power Apps license not required")
![Experimental Features](https://img.shields.io/badge/Experimental%20Features-No-green.svg "Does not rely on experimental features")
![On-Premises Connectors](https://img.shields.io/badge/On--Premises%20Connectors-No-green.svg "Does not use on-premise connectors")
![Custom Connectors](https://img.shields.io/badge/Custom%20Connectors-Not%20Required-green.svg "Does not use custom connectors")

## Authors

> One author per line, please
> DELETE THIS PARAGRAPH BEFORE SUBMITTING

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

## Help

> Note: don't worry about this section, we'll update the links.

We do not support samples, but we this community is always willing to help, and we want to improve these samples. We use GitHub to track issues, which makes it easy for  community members to volunteer their time and help resolve issues.

If you encounter any issues while using this sample, you can [create a new issue](https://github.com/pnp/powerapps-samples/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=bug-report.yml&sample=YOURSAMPLENAME&authors=@YOURGITHUBUSERNAME&title=YOURSAMPLENAME%20-%20).

For questions regarding this sample, [create a new question](https://github.com/pnp/powerapps-samples/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=question.yml&sample=YOURSAMPLENAME&authors=@YOURGITHUBUSERNAME&title=YOURSAMPLENAME%20-%20).

Finally, if you have an idea for improvement, [make a suggestion](https://github.com/pnp/powerapps-samples/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=suggestion.yml&sample=YOURSAMPLENAME&authors=@YOURGITHUBUSERNAME&title=YOURSAMPLENAME%20-%20).

## For more information

- [Overview of creating apps in Power Apps](https://docs.microsoft.com/powerapps/maker/)
- [Power Apps canvas apps documentation](https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/)


<img src="https://telemetry.sharepointpnp.com/powerapps-samples/samples/readme-template" />

