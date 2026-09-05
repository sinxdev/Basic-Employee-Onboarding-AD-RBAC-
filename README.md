
# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement

Northstar Medical Group outsourced its access management to a Managed Service Provider (MSP), which implemented a flat, unsegmented Active Directory infrastructure lacking standardized Role-Based Access Control (RBAC). As the workforce grew beyond 200 identities, the absence of fine-grained access controls led to severe over-provisioning and direct violations of the Principle of Least Privilege. Furthermore, deficient Identity Lifecycle Management resulted in active orphaned accounts post-termination due to missing automated de-provisioning workflows. Unmonitored access pathways and persistent stale accounts exposed the organization to critical regulatory non-compliance under HIPAA Security Rule standards.



[Provide 3 to 5 sentences describing what was broken at Northstar Medical Group. Mention the MSP mismanagement, lack of structure, manual processes, and HIPAA risks that existed before your project.]

## Solution Overview
To resolve these critical access control vulnerabilities, I architected and deployed a new Active Directory domain featuring a structured Organizational Unit (OU) hierarchy tailored to the organization's functional divisions. I established dedicated security groups within these OUs to enforce a flat Role-Based Access Control (RBAC) model aligned with the Principle of Least Privilege. By mapping permissions directly to job roles and operational needs, each user identity was strictly provisioned with only the access required for their specific position. This structured identity design eliminated unauthorized access pathways and standardized user provisioning, effectively preventing resource over-provisioning and directory sprawl. Ultimately, this remediation neutralized the security risks posed by orphaned accounts and restored strict alignment with HIPAA Security Rule requirements.

[Provide 4 to 6 sentences describing what you built and how it solved the problem. Cover the new domain creation, the structural OU design, the security groups, the flat RBAC model, and how user provisioning was secured.]

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Organizational units and security groups design
* Fully documented my steps end-to-end



