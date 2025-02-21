## FECFile Release Notes

# February 28, 2024 (Sprint 56)

## Feature updates:

- Roles and Permissions: Added user role of Manager. Committee Administrator can add or update the role of a user as a Manager  [FECFILE-1840](https://fecgov.atlassian.net/browse/FECFILE-1840), [FECFILE-1846]( https://fecgov.atlassian.net/browse/FECFILE-1846), [FECFILE-1886]( https://fecgov.atlassian.net/browse/FECFILE-1886)

## Design (UX/UI) enhancements:

- No Design (UX/UI) enhancements in this sprint

## Bug fixes:

- No bugs or defects in this sprint

## System performance and security:

- Several performance and security enhancements are included in this release

_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._

# February 18, 2024 (Sprint 55)

## Feature updates:

- Report Workflow: For Form 3X, remove delete function from receipt transactions created by loans. [FECFILE-1829](https://fecgov.atlassian.net/browse/FECFILE-1829) 
- Form 3: Add Form 3 to the report selection (behind a feature flag so that it is currently only visible in DEV and STAGE [FECFILE-422](https://fecgov.atlassian.net/browse/FECFILE-422)
- Form 3X: Schedule C: System will now delete loans and debts in future reports when the loan or debt is paid off in the current reporting period [FECFILE-1662](https://fecgov.atlassian.net/browse/FECFILE-1662)
- Login Management and Workflow: System will update email address in application when email is updated in login.gov and system will recognize when a user logs in with a new login.gov account, but having the same email address as a user in the system [FECFILE-1988]( https://fecgov.atlassian.net/browse/FECFILE-1988), [FECFILE-1989]( https://fecgov.atlassian.net/browse/FECFILE-1989)

## Design (UX/UI) enhancements:

- No Design (UX/UI) enhancements in this sprint

## Bug fixes:

- No bugs or defects in this sprint

## System performance and security:

- Several performance and security enhancements are included in this release

_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._


# December 4, 2024 (Sprint 51)

## Feature updates:

- Report Workflow: For Form 3X, remove default report coverage dates from election and special election reports which do not have non-standard dates and alert users to always validate the report coverage dates for the reports where the dates are usually standard monthly or quarterly dates. [FECFILE-1604](https://fecgov.atlassian.net/browse/FECFILE-1604) , [FECFILE-1605](https://fecgov.atlassian.net/browse/FECFILE-1605)
- Contact Management: Updated rules to always display ‘00’ for candidates in single district states and at-large districts [FECFILE-1686](https://fecgov.atlassian.net/browse/FECFILE-1686)

## Design (UX/UI) enhancements:

- Updated user profile page so that names are now populated and entered in ‘First Name’ and ‘Last Name’ order [FECFILE-1690](https://fecgov.atlassian.net/browse/FECFILE-1690)
- Updated input field sizes for fields on the Account Information Page to be more consistent with all other forms on the site. [FECFILE-1758](https://fecgov.atlassian.net/browse/FECFILE-1758)
- Updated stock images throughout the site [FECFILE-1772](https://fecgov.atlassian.net/browse/FECFILE-1772)

## Bug fixes:

- When creating a Loan, the Date Due and Interest Rate fields were not being updated or saved correctly if non-standard dates or rates were entered. This has been resolved. [FECFILE-1786](https://fecgov.atlassian.net/browse/FECFILE-1786)
- First Name and Last Name of Committee Treasurer were populating in reverse when creating a Loan transaction. This has been corrected, and the displayed fields have also been reversed, so it displays as First Name, Last Name. [FECFILE-1756](https://fecgov.atlassian.net/browse/FECFILE-1756)
- On Independent Expenditures, the Candidate District was ‘read only’ if the Candidate Office was ‘House’. That has been updated to now be editable. [FECFILE-1746](https://fecgov.atlassian.net/browse/FECFILE-1746)
- When saving an In-kind Contribution to Candidate, the system would try to save the candidate name as the organization. This has been resolved. [FECFILE-1649](https://fecgov.atlassian.net/browse/FECFILE-1649) 

## System performance and security:

- Several performance and security enhancements are included in this release

_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._
