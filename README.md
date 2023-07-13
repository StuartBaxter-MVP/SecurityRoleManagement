# SecurityRoleManagement

## Solution Overview

This Solution contains the following components:
- **Request Role Canvas App** : a simple app where users can request a role, generating an approval workflow via a cloudflow
- **Security Roles Manager Canvas App**: a simple app where environment admins can assign and remove access to a role
- **Add a new AAD Group and associated team**: a manual cloud flow to allow admins to create a new AAD group and a releated Dataverse Team
- **Request Role**: a cloud flow to assign a role to a user (not currently in use)
- **Request Role with Approval**: A cloud flow triggered when a user asks for a new role in the request role canvas app
- **Remove role**: a cloud flow triggered when a user asks for a role to be removed within the request role canvas app
-**Component Library** containing the components used in both canvas apps
-**Required connection references**
-**Environment Variable** for admin user and approvers

## Installation instructions

Download either the managed or unmanaged solution from the repo
Import the solution
create connections (if required)
Set environment variables:
- **AAD Group Admin** should be set to the GUID of a user with permissions to create Dataverse Teams and AAD groups. this user will be set to the group owner and team administrator 
- **Role approvers** is a comma separated list of users who can approve requests for new roles submitted via the request roles canvas app
Run the Add a new AAD Group and associated team flow to create the groups you want to assign
Apply security roles to the team(s) created by your flow runs as required via Power Platform Admin Centre