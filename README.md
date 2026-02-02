# ai-assisted-m365-identity-onboarding
Automated M365 User Provisioning and Security Governance pipeline using Power Automate, Microsoft Graph API, and Entra ID


##Overview
This project demonstrates a secure, API-driven identity onboarding workflow for Microsoft 365, enhanced with an AI-assisted decision layer while maintaining strict security and governance controls.

The goal is to move from manual, portal-based onboarding to a scalable, policy-driven identity lifecycle design.

##Problem Statement
Manual user onboarding often leads to:
- Inconsistent access assignments
- Security gaps
- Over-privileged accounts
- Poor auditability

This design focuses on reducing risk through automation, standardization, and identity-first thinking.


##Highlights
- Microsoft Graph API via App Registration
- Least-privilege API permissions
- Group-based access assignment
- Conditional Access enforcement for MFA
- AI-assisted classification with human-in-the-loop control


##Role of AI
AI is used *only for decision support*, not execution.

##AI responsibilities:
- Suggest onboarding access profiles
- Flag ambiguous or risky requests

##AI does NOT:
- Call Microsoft Graph directly
- Assign permissions autonomously
- Bypass security policies

All execution remains deterministic, auditable, and policy-driven.


##Security & Governance Principles
- No direct role or permission assignment
- Conditional Access enforced via group membership
- Clear separation of decision, execution, and enforcement
- Designed with Zero Trust principles in mind


##Learning Outcomes
- Identity lifecycle design over click-based administration
- API-first automation mindset
- Responsible AI integration with guardrails
- Enterprise-ready security thinking



# Disclaimer
This repository is for learning and architectural demonstration purposes only.
No tenant-specific, confidential, or production credentials are included.





