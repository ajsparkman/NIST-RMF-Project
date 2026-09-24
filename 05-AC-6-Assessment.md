# AC-6 - Least Privilege Assessment

## Control

AC-6 - Least Privilege

## Purpose

The purpose of this control is to ensure that users are only given the access and permissions necessary to perform their job responsibilities.

## Assessment Question

Are users at Sparkman Systems LLC limited to only the permissions they need?

## Evidence Requested

To assess AC-6, the following evidence would be requested:

- Active Directory group membership
- List of local administrator accounts
- File server permissions
- Role-based access assignments
- Privileged account approval records

## Evidence Reviewed

The following fictional evidence was reviewed:

- Five employees had local administrator privileges on their assigned laptops
- Only two of those employees had job duties requiring administrative access
- All 25 employees had read access to the company-wide shared file directory
- Finance records were restricted to members of the Finance security group
- No documented approval process existed for granting local administrator privileges

## Assessment Result

Status: Partially Satisfied

## Finding

Sparkman Systems LLC has granted local administrator privileges to employees who do not require elevated access for their job responsibilities. The company also lacks a documented approval process for assigning privileged access.

## Risk

Unnecessary administrative privileges increase the likelihood that malware, user error, or compromised accounts could cause greater damage to company systems.

## Recommendation

Remove unnecessary local administrator privileges and implement a documented approval process for granting and reviewing privileged access.