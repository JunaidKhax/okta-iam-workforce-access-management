# Okta IAM Workforce Access Management

## Workforce Identity & Access Management using Okta

This project documents my understanding of Workforce Identity and Access Management (IAM) using Okta. The objective is to understand how organizations manage employee identities, control application access, enforce authentication security, and monitor access-related activities.

> **Learning Note:** I currently do not have access to an Okta Workforce Identity trial using my personal Gmail because the trial requires a business email. Therefore, this project is based on my learning, study, and understanding of Okta IAM concepts and workflows. The configurations described below represent the concepts I studied rather than claiming independent access to an Okta production or trial tenant.

## Key Objectives

- User lifecycle management
- Group-based access control
- Role-based access management
- Multi-Factor Authentication (MFA)
- Application access governance
- Audit logging and monitoring
- Least-privilege access

## Tools & Technologies

- Okta Workforce Identity
- Okta Verify (MFA)
- SaaS Applications
- Identity and Access Management (IAM)
- Role-Based Access Control (RBAC)

## Implementation Workflow

1. Created users to simulate employee onboarding and workforce identity management.

2. Configured security groups to organize users according to their roles and access requirements.

3. Assigned applications to appropriate groups to control which users could access specific SaaS applications.

4. Configured Multi-Factor Authentication (MFA) to provide an additional layer of authentication security.

5. Reviewed authentication and system audit logs to understand user activity, access events, and administrative actions.

6. Applied the principle of least privilege by providing users only the access required for their assigned role.

## IAM Concepts Covered

### User Lifecycle Management

User accounts are created when employees join an organization and can later be updated, suspended, or removed when their employment or access requirements change.

### Group-Based Access Control

Groups can be used to organize users based on departments, roles, or responsibilities. Applications and access policies can then be assigned to groups instead of managing every user individually.

### Multi-Factor Authentication

MFA adds another verification step during authentication. This helps protect accounts even if a user's password is compromised.

### Application Access Management

IAM platforms such as Okta can be used to manage employee access to business applications. Access can be controlled based on the user's role or group membership.

### Audit Logging

Audit logs provide visibility into activities such as user creation, login attempts, application access, group changes, and administrative actions. These logs can help with troubleshooting, monitoring, and audit investigations.

## Security & Compliance Concepts

- Least Privilege Access
- Role-Based Access Control
- Access Governance
- Authentication Security
- User Lifecycle Management
- Audit Evidence Collection
- Security Monitoring
- Compliance Readiness

## Real-World Scenario

A company hires a new employee in the IT department.

The IT administrator creates the employee's identity, adds the employee to the appropriate security group, and provides access to the applications required for the employee's role.

MFA is enabled to strengthen authentication security.

If the employee changes departments, their group membership and application access can be reviewed and updated.

When the employee leaves the organization, their access can be disabled or removed.

This demonstrates how IAM helps organizations manage **who has access, what they can access, and how that access is controlled and monitored**.

## Outcome

This project helped me understand the fundamentals of Workforce IAM and how identity platforms such as Okta can be used for user management, access control, authentication security, application access, and audit monitoring.

The project strengthened my understanding of IAM concepts relevant to entry-level **IT Support, Identity & Access Management, IT Operations, and System Administration** roles.


## Important Note

> **Learning & Documentation Project**
>
> I currently do not have access to an Okta Workforce Identity tenant because Okta's trial environment requires a business email for registration. Therefore, I was unable to independently perform the configurations in an Okta tenant.
>
> This repository is based on my study and understanding of Workforce Identity & Access Management concepts in Okta. The implementation approach and workflows have been studied using an existing Okta IAM project shared by a friend who works with Okta in an enterprise IAM environment.
>
> I understand the concepts demonstrated in this project, including:
>
> * User lifecycle management
> * Group-based access control
> * Role-based access
> * Application assignments
> * Multi-Factor Authentication (MFA)
> * Least-privilege access
> * Authentication and access controls
> * Audit logs and monitoring
> * Access governance
>
> **Note:** The Okta tenant configuration was not performed by me personally. This repository is intended to document my learning and understanding of Okta IAM concepts rather than claim production or independent tenant administration experience.

