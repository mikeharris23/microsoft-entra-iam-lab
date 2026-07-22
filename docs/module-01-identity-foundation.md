# Business Scenario

Harris Financial Group is a fictional financial-services organization with
approximately 75 employees. The organization provides mortgage services,
financial consulting, customer support, compliance oversight, and technology
operations.

The company is implementing Microsoft Entra ID to centralize identity
management, enforce role-based access control, improve user lifecycle
management, and prepare for Zero Trust security controls.

## Business Objectives

- Centralize employee identity management
- Assign access according to job responsibilities
- Reduce individual user access assignments
- Separate administrative and standard accounts
- Apply least-privilege access
- Establish a repeatable onboarding and offboarding process
- Prepare the environment for MFA and Conditional Access



| Department             | Code | Purpose                                 |
| ---------------------- | ---: | --------------------------------------- |
| Executive              | EXEC | Senior leadership                       |
| Information Technology |   IT | Technology and identity administration  |
| Mortgage Operations    | MORT | Loan processing and mortgage services   |
| Compliance and Risk    | COMP | Auditing, risk and regulatory oversight |
| Finance                |  FIN | Accounting and financial reporting      |
| Human Resources        |   HR | Employee lifecycle management           |




# Module 1: Enterprise Identity Foundation

## Objective

Build the initial Microsoft Entra ID identity architecture for a fictional
financial-services organization.

## Environment

- Platform: Microsoft Entra ID
- Organization: Harris Financial Group Lab
- Identity type: Cloud-only identities
- Access model: Department and role-based security groups
- Administrative model: Separate standard and privileged accounts

## Work Completed

- Created fictional employee identities
- Populated identity attributes and manager relationships
- Created department-based security groups
- Created business-role security groups
- Separated standard and administrative accounts
- Assigned a limited Microsoft Entra administrative role
- Created an administrative unit for Mortgage Operations
- Developed an identity inventory and access matrix
- Validated least-privilege access

## Security Principles Applied

- Least privilege
- Separation of duties
- Role-based access control
- Group-based access assignment
- Privileged-account separation
- Standardized naming conventions
- Identity lifecycle readiness

## Business Value

The identity foundation gives Harris Financial Group a consistent and
scalable method for managing workforce identities. Access can be assigned
through departments and business roles rather than directly to individual
employees, reducing administrative effort and the risk of access errors.

