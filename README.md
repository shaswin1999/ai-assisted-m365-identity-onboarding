# ai-assisted-m365-identity-onboarding
Automated M365 User Provisioning and Security Governance pipeline using Power Automate, Microsoft Graph API, and Entra ID

## Solution Overview
The solution automates onboarding using the following flow:
1. User details collected via Microsoft Form
2. Power Automate orchestrates the workflow
3. Decision layer classifies the user (rules / future AI agent)
4. Microsoft Graph API creates the user account
5. User is added to a Security Group
6. Conditional Access enforces MFA and security policies

AI is used **only for decision support**, never for execution.

## Architecture Flow
See the architecture diagram for a high-level view of the system:
<img width="3558" height="580" alt="Flowchart" src="https://github.com/user-attachments/assets/f81a02ed-dc47-4567-9659-5b5a95c2887b" />

## Security Design Principles
- Application permissions with least privilege
- Group-based access control (RBAC)
- Conditional Access applied via Security Groups
- Secrets stored securely, never exposed in code

## Future Enhancements to be considered
- AI agent integration for risk scoring
- Manager approval for privileged roles
- Audit logging and reporting
- Integration with ITSM tools

## Learning Outcomes
- Identity lifecycle design over click-based administration
- API-first automation mindset
- Enterprise-ready security thinking



# Disclaimer
This repository is for learning and architectural demonstration purposes only.
No tenant-specific, confidential, or production credentials are included.





