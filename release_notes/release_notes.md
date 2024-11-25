# TBD - DRAFT (Sprint 51)

## Feature updates:

- Report Workflow: For Form 3X, remove default report coverage dates from election and special election reports which do not have non-standard dates and alert users to always validate the report coverage dates for the reports where the dates are usually standard monthly or quarterly dates. [FECFILE-1604](https://fecgov.atlassian.net/browse/FECFILE-1604) , [FECFILE-1605](https://fecgov.atlassian.net/browse/FECFILE-1605)
- Contact Management: Updated rules to always display ‘00’ for candidates in single district states and at-large districts [FECFILE-1686](https://fecgov.atlassian.net/browse/FECFILE-1686)

## Design (UX/UI) enhancements:

- Updated user profile page where ‘Last Name’ was listed before ‘First Name’ so that names are now populated and entered ‘First Name’ and ‘Last Name’ order [FECFILE-1690](https://fecgov.atlassian.net/browse/FECFILE-1690)
- Updated input field sizes for fields on the Account Information Page to be more consistent with all other forms on the site. [FECFILE-1758](https://fecgov.atlassian.net/browse/FECFILE-1758)
- Updated stock images throughout the application [FECFILE-1772](https://fecgov.atlassian.net/browse/FECFILE-1772)

## Bug fixes:

- When creating a Loan, the Date Due and Interest Rate fields were not being updated or saved correctly if non-standard dates or rates were entered. This has been resolved. [FECFILE-1786](https://fecgov.atlassian.net/browse/FECFILE-1786)
- First Name and Last Name of Committee Treasurer were populating in reverse when creating a Loan transaction. This has been corrected, and the displayed fields have also been reversed, so it displays as First Name, Last Name. [FECFILE-1756](https://fecgov.atlassian.net/browse/FECFILE-1756)
- On Independent Expenditures, the Candidate District was ‘read only’ if the Candidate Office was ‘House’. That has been updated to now be editable. [FECFILE-1746](https://fecgov.atlassian.net/browse/FECFILE-1746)
- When saving an In-kind Contribution to Candidate, the system would try to save the candidate name as the organization. This has been resolved. [FECFILE-1649](https://fecgov.atlassian.net/browse/FECFILE-1649) 

## System performance and security:

- Several performance and security enhancements are included in this release

_For a more detailed look at what has changed, see our technical release notes [here](https://github.com/fecgov/fecfile-web-api/releases)._
