# Medical Clinic — HIPAA Security Assessment

## Scenario
Lakeside Family Clinic is a fictional small medical practice providing primary care to local patients. The clinic has about 25 employees — physicians, nurses, billing staff, front desk, and administrative support.

Day to day, the clinic runs on an EHR system, email, shared workstations, scheduling software, billing tools, and cloud-based file storage. Because they're handling protected health information, leadership wanted a clearer picture of where their security posture actually stood and what gaps could turn into compliance, operational, or financial problems.

## Objective
I evaluated the clinic's current security practices against HIPAA Security Rule concepts to find risks affecting the confidentiality, integrity, and availability of electronic protected health information (ePHI). This scenario leans into regulatory requirements, practical risk scoring, and communicating risk in a way that actually supports compliance and business decisions — not just listing findings.

## Scope
This assessment covers:
- Access controls for systems containing patient information
- User account provisioning and deprovisioning
- Multi-factor authentication
- Workstation security
- Email and phishing risk
- Data backup and recovery
- Audit logging and monitoring
- Security awareness training
- Incident response readiness
- Vendor and third-party risk
- Policies and procedures related to patient data protection

Clinical care quality, billing accuracy, legal interpretation of HIPAA, and physical facility safety are outside the scope of this assessment.

## Assumptions
- Findings are based on the fictional clinic environment and stakeholder representations described above, not on technical testing.
- No vulnerability scanning or penetration testing was performed as part of this scenario.
- Risk scoring reflects a point-in-time snapshot and assumes no changes were made during the engagement.

## Deliverables
This folder contains:
- **HIPAA-Security-Assessment.pdf** — written assessment of key security and compliance risks based on HIPAA Security Rule concepts
- **Quantified-Risk-Register.xlsx** — risk register scoring likelihood, impact, risk level, and estimated financial exposure for each identified risk

## Methodology
1. Review the fictional clinic environment and assumptions
2. Identify systems and processes that store, process, or transmit ePHI
3. Evaluate current safeguards against HIPAA Security Rule concepts
4. Document security gaps and the business risk behind each one
5. Score each risk by likelihood, impact, and estimated financial exposure
6. Recommend remediation steps based on risk priority

## Key Risk Themes
- Inconsistent multi-factor authentication
- Shared workstation access concerns
- Limited audit log review
- Weak user offboarding process
- Backup recovery procedures that haven't been tested
- No formal incident response plan
- Limited vendor risk documentation
- Security training not run on a consistent schedule

## Disclaimer
Lakeside Family Clinic is a fictional company created for portfolio purposes. All findings, risks, and recommendations in this folder are fictional and don't represent any real company or client. This isn't legal advice and isn't a formal HIPAA compliance determination.
