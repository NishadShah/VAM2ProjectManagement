# FedRAMP/Cloud VA Application ATO Process

CLOUD AUTHORIZATION CHECKLIST FOR DEPLOYMENTS WITHIN THE VAEC

| PHASE     | TASK     | DESCRIPTION                                    | REQ'D | ARTIFACT | TARGET | VA SOP     |
|-----------|----------|------------------------------------------------|-------|----------|--------|------------|
| Cloud ATO | RV Entry | RiskVision Entry of cloud-based VA application | Y     |          | RV     | Appendix A |
|           | App Q&A  | CSP / VA Applicaiton questionnaire             | Y     |          | RV     | Appendix A |
|           | CRSP     | Customer Responsibilities Security Plan        | Y     |          | RV     | Appendix A |


### Appendix A – FedRAMP/Cloud – VA Requirements 

FedRAMP Authorized Cloud Service Provider (CSP) Reciprocity (Agency ATO) Process

Federal Risk and Authorization Management Program (FedRAMP) is designed to assist agencies in meeting FISMA requirements for cloud systems.  CSPs must meet FedRAMP in order to do business with US government agencies as part of the “Cloud first policy”.  FedRAMP is designed as a “do once, use many” framework to create efficiency in government procurement of cloud services.  As part of the program, CSPs pursuing FedRAMP are required to be independently assessed by a Third Party Assessment Organization (3PAO).  Per the “Acceptance of FEDRAMP Authorization Memo” issued on August 11, 2015 by the Deputy Assistant Secretary for Information Security, “existing Federal Risk and Authorization Management Program (FedRAMP) authorizations for certified FedRAMP Cloud Service Provider cloud systems should be evaluated, and reused when possible, to reduce the overall time required to grant an authorization and begin using a cloud service.”.

The Cloud/FedRAMP Reciprocity ATO process consists of the following steps:

Note: A contract must be in place before requesting a RiskVision entry of the FedRAMP Cloud Service Provider. In the absence of a contract, RVWG will not entertain any such request.  

1.	Designate an ISO and System Owner to the project.

2.	Coordinate with the RVWG to request a RiskVision entry of the FedRAMP Cloud Service Provider.  Reference section 2 (Authorization Prerequisites) for action steps.

3.	System Owner and ISO will complete the CSP system questionnaire within RiskVision to define the system acronym, security categorization, operational status, system type, cloud computing service model [Infrastructure-as-a-Service (IaaS), Platform-as-a-Service (PaaS), Software-as-a-Service (SaaS), etc.], and cloud service type (private, public, hybrid).

4.	ISO will request FedRAMP repository access for CSP authorization documentation package by completing the FedRAMP Agency Access Request Form and emailing to Information Security Risk Management (ISRM) at vaoisisrmrmf@va.gov.

5.	ISO will map the CSP authorization documentation artifacts to the VA ATO documentation requirements in RiskVision.  Then review and assess the CSP’s 3PAO FedRAMP authorized SSP using the NIST/CAG-20 scoresheet provided by OIS.  All documents will be uploaded to the Documents tab in RiskVision.

6.	CSP authorization package in RiskVision will then be advanced to OIS and Certification Authority (CA) for review.  Additionally, VA determines if the CSP system appropriately addresses any and all necessary VA and Department of Homeland Security (DHS) Trusted Internet Connection (TIC) requirements (e.g., all external systems, including cloud solutions, hosted from facilities or data centers outside of the VA network and boundary must comply with DHS TIC requirements and VA’s external connection agreements) before progressing to the VA CISO and Designated Accrediting Authority (DAA) for agency ATO consideration. 


### Cloud-Based VA Application / Third-Party System ATO Process

The Cloud/FedRAMP cloud-based VA Application / Workload / Third-Party System ATO process consists of the following steps:

1.	Coordinate with the RVWG to request a RiskVision entry of the cloud-based VA Application / Workload / Third-Party System.  Reference section 2 (Authorization Prerequisites) for action steps.

2.	System Owner and ISO will complete the CSP/VA Application / Workload / Third-Party System questionnaire within RiskVision to define the system acronym, security categorization, operational status, system type, etc.

3.	Customer Responsibilities Security Plan provided by the CSP ISO will be completed by the System Owner.  This set of security controls is documented in the FedRAMP authorized CSP Customer Responsibilities Matrix.  The security plan controls have been mapped to VA 6500 requirements.  

4.	ISO will review the completed Customer Responsibilities Security Plan for proper implementation details and uploads to the Documents tab in RiskVision.
The cloud-based VA Application / Workload / Third-Party System in RiskVision will then be advanced to OIS and Certification Authority (CA) for review before progressing to the VA CISO and Designated Accrediting Authority (DAA) for agency ATO consideration.


## Other Federal Agency (Non-FedRAMP) ATO Acceptance

The cybersecurity requirements for VA information systems will be managed through the Risk Management Framework (RMF) consistent with the principals established in National Institute of Standards and Technology (NIST) Special Publication (SP) 800-37.  Reciprocal acceptance of other federal agency system authorizations will be implemented to the maximum extent possible.  Refusals must be timely, documented, and reported to the responsible VA Authorizing Official.  

VA employees and contract staff working for the VA are prohibited from sending VA data outside the VA Network without an Authority to Operate signed by the VA Authorizing Official.

1.	Any project seeking to use another federal agency ATO must contact the vaoisisrmrmf@va.gov to initiate the process.

2.	A review of the other agency ATO process will be initiated to ensure it meets VA requirements for NIST 800-53 implementation; ATO package review is allowed; and POAM management and tracking is in place.  In the event the other agency will not share the entire A&A package, negotiations will ensue between VA and the other agency to obtain an agreed upon subset of the required documentation.

3.	Once an agreement/understanding is in place to review the other agency package, an entry in RiskVision will be created using the VA 6500.3 Contractor/FedRAMP program.

4.	The other Federal Agency ATO memo, along with additional documentation, will be uploaded to the documents tab in RiskVision.  Additional documentation may include a list of open POAMs, required artifacts, Interconnection Security Agreements (ISA)/Memorandum of Understanding (MOU).
5.	Questionnaires will be answered and any customer responsible controls, if necessary, will be completed and uploaded to the documents tab.
6.	The workflow will be progressed to the VA Authorizing Official for review and approval.
o	 	If the VA AO refuses reciprocity of the other agency ATO, a memo will be developed and sent to the VA project staff for notification.



## Authorization to Operate (ATO) Requirements - 2019-02-02

```
Table of Contents
1. Purpose
2. Scope
3. Authorization Prerequisites
4. Assessment & Authorization (A&A) Requirements

  4.1 Registration Requirements
    4.1.1 Application Registration
    
  4.2 Security Documentation Requirements
    4.2.1 System Security Plan (SSP)
    4.2.2 Minor Application Self-Assessment
    4.2.3 Signatory Authority
    4.2.4 Risk Assessment (RA)
    4.2.5 Configuration Management Plan (CMP)
    4.2.6 Incident Response Plan (IRP)
    4.2.7 Information Security Contingency Plan (ISCP)
    4.2.8 Disaster Recovery Plan (DRP)
    4.2.9 Privacy Impact Assessment (PIA)
    4.2.10 Interconnection Security Agreement (ISA)/Memorandum of Understanding (MOU)
    4.2.11 Secure Design Review
  
  4.3 Technical/Testing Requirements
    4.3.1 Nessus Scan/[Discovery Scan (part of Nessus scan)]
      4.3.1.1	Database Scan
    4.3.2 Quality Code Review
    4.3.3 Secure Code Review
    4.3.4 Penetration Test / Application Assessment
    4.3.5 Security Configuration Compliance Data
    4.3.6 Security Control Assessment (SCA)
    4.3.7 Control Implementation Evidence
    4.3.8 Enterprise Discovery Scan

  4.4	Closing	20

Appendix A – FedRAMP/Cloud – VA Requirements
Appendix B – Authorization Requirements Quick Reference Guide
Appendix C – Job Aid: Security Information
Appendix D – Minor Applications Self-Assessment SOP
Appendix E – A&A System/Facility DRP and ISCP Requirements
Appendix F – Links/URLs/E-Mail Addresses
```
