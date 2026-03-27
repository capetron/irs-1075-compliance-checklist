# IRS Publication 1075 Compliance Checklist

A comprehensive compliance checklist and implementation guide for federal, state, and local government agencies, their contractors, and service providers that receive and handle Federal Tax Information (FTI). This resource covers IRS Publication 1075 requirements, Safeguard Security Report (SSR) procedures, IRC Section 6103 confidentiality rules, and practical steps for protecting FTI.

Last Reviewed: March 2026

## Table of Contents

- [What Is IRS Publication 1075?](#what-is-irs-publication-1075)
- [Who Must Comply with IRS Publication 1075?](#who-must-comply-with-irs-publication-1075)
- [IRC Section 6103: The Legal Foundation](#irc-section-6103-the-legal-foundation)
- [Key Publication 1075 Requirements](#key-publication-1075-requirements)
- [Federal Tax Information Defined](#federal-tax-information-defined)
- [Safeguard Security Report (SSR)](#safeguard-security-report-ssr)
- [How IRS Publication 1075 Maps to NIST SP 800-53](#how-irs-publication-1075-maps-to-nist-sp-800-53)
- [IRS Safeguard Reviews and Audits](#irs-safeguard-reviews-and-audits)
- [Compliance Checklist Summary](#compliance-checklist-summary)
- [Common Pitfalls and How to Avoid Them](#common-pitfalls-and-how-to-avoid-them)
- [Frequently Asked Questions](#frequently-asked-questions)
- [About Petronella Technology Group](#about-petronella-technology-group)
- [Additional Resources](#additional-resources)

## What Is IRS Publication 1075?

IRS Publication 1075, titled "Tax Information Security Guidelines for Federal, State, and Local Agencies," is the authoritative document published by the Internal Revenue Service (IRS) that establishes the minimum security standards for all entities that receive Federal Tax Information (FTI) from the IRS. The publication prescribes the technical, physical, and administrative safeguards that agencies and their contractors must implement to protect FTI from unauthorized access, disclosure, use, or destruction.

Publication 1075 is not advisory; it is mandatory. Any agency that receives FTI through an authorized disclosure under Internal Revenue Code (IRC) Section 6103 must comply with Publication 1075's requirements in full. The IRS Office of Safeguards, within the IRS Government Liaison, Disclosure, and Safeguards (GLDS) division, administers the safeguard program and conducts regular reviews to verify compliance.

The current version of Publication 1075 (revised 2024) incorporates requirements drawn directly from NIST Special Publication 800-53 Rev. 5. In fact, Publication 1075 is one of the clearest examples of a NIST 800-53 overlay in practice: it takes the NIST SP 800-53 Moderate baseline as its foundation and adds IRS-specific parameters, enhancements, and supplemental controls tailored to the unique sensitivity of tax information.

Publication 1075 applies to all forms of FTI, whether electronic, paper, or verbal. The scope of protection extends from the moment an agency receives FTI through its entire lifecycle, including processing, storage, transmission, and destruction.

Failure to comply with Publication 1075 has significant consequences. The IRS can suspend or terminate an agency's access to FTI, which can cripple programs that depend on tax data for eligibility determinations, child support enforcement, treasury offset processing, and other critical government functions.

## Who Must Comply with IRS Publication 1075?

**State tax agencies** that receive FTI from the IRS for state tax administration purposes. This is the most common category and includes state departments of revenue, taxation, and finance.

**State human services agencies** that receive FTI for administering programs such as Temporary Assistance for Needy Families (TANF), Supplemental Nutrition Assistance Program (SNAP), Medicaid, and other federal and state benefit programs.

**State child support enforcement agencies** that receive FTI to locate non-custodial parents and establish or enforce child support obligations.

**State workforce agencies** that receive FTI for unemployment insurance and workforce development programs.

**Federal agencies** that receive FTI under various IRC 6103 provisions, including the Social Security Administration, Department of Health and Human Services, Department of Justice, and others.

**Local government agencies** that receive FTI through state agencies for local program administration, such as local social services departments, local tax offices, and county treasurers.

**Contractors, subcontractors, and service providers** that process, store, or transmit FTI on behalf of an authorized agency. This includes IT managed service providers, cloud hosting providers, data processing vendors, and consulting firms.

**Universities and research institutions** that receive FTI under IRC 6103(j) for statistical research purposes authorized by federal law.

**State and local auditors** who may access FTI during the course of auditing agency programs.

In total, over 300 federal, state, and local agencies receive FTI from the IRS, along with thousands of contractors and subcontractors that support these agencies. All of these entities are subject to Publication 1075.

## IRC Section 6103: The Legal Foundation

The legal authority for both the disclosure of FTI and the requirement to safeguard it comes from IRC Section 6103. This section of the Internal Revenue Code establishes that tax returns and return information are confidential and may not be disclosed except as authorized by specific provisions of the code.

Key IRC 6103 provisions relevant to Publication 1075 compliance:

**Section 6103(d):** Authorizes disclosure of FTI to state tax officials for state tax administration purposes. This is the most commonly used provision and covers the largest volume of FTI disclosures.

**Section 6103(l):** Authorizes disclosure of FTI to various federal and state agencies for specific non-tax purposes, including:
- 6103(l)(1): Social Security Administration for benefit administration
- 6103(l)(5): State/local child support enforcement agencies
- 6103(l)(7): Federal/state/local agencies administering specified federal/state benefit programs (TANF, SNAP, Medicaid, etc.)
- 6103(l)(10): Department of Health and Human Services for Medicare and Medicaid administration
- 6103(l)(20): Federal Bureau of Prisons for incarcerated taxpayer verification
- 6103(l)(21): Student financial assistance programs

**Section 6103(j):** Authorizes disclosure for statistical research purposes, primarily to the Census Bureau and other authorized research entities.

**Section 6103(p)(4):** Establishes the safeguard requirements that form the legal mandate for Publication 1075. This section requires that all agencies receiving FTI:
1. Establish and maintain a satisfactory security program
2. Restrict access to FTI to authorized persons
3. Provide physical security for FTI
4. Protect electronic FTI through technical controls
5. Report any incident of unauthorized access or disclosure
6. Dispose of FTI when no longer needed

Violations of IRC 6103 are subject to criminal penalties under IRC Section 7213 (unauthorized disclosure, a felony punishable by up to 5 years imprisonment and $5,000 fine) and IRC Section 7213A (unauthorized inspection, punishable by up to 1 year imprisonment and $1,000 fine). Civil damages under IRC Section 7431 may also apply.

## Key Publication 1075 Requirements

Publication 1075 organizes its requirements into several major areas:

### Administrative Safeguards
- Designate a Safeguard Security Coordinator responsible for FTI protection
- Develop and maintain a Safeguard Security Plan (SSP)
- Submit a Safeguard Security Report (SSR) to the IRS annually
- Conduct background investigations on all personnel with access to FTI
- Implement security awareness training specific to FTI handling
- Establish and enforce information security policies and procedures
- Conduct periodic risk assessments
- Manage the security of third-party contractors with access to FTI

### Physical Safeguards
- Restrict physical access to areas where FTI is received, processed, stored, or destroyed
- Implement visitor control procedures for areas containing FTI
- Use locked containers (safes, file cabinets) for paper FTI when not in use
- Position computer screens displaying FTI away from unauthorized viewing
- Implement clean desk policies for areas where FTI is handled
- Control the removal of FTI from secure areas
- Implement environmental controls (fire suppression, temperature, humidity) for areas containing FTI systems

### Technical Safeguards
- Implement access controls consistent with NIST SP 800-53 Moderate baseline
- Enforce multi-factor authentication for remote access to FTI systems
- Encrypt FTI in transit using FIPS 140-2 validated cryptographic modules
- Encrypt FTI at rest using FIPS 140-2 validated cryptographic modules
- Implement audit logging for all access to and actions on FTI
- Deploy intrusion detection/prevention systems on FTI network segments
- Conduct vulnerability scanning at least monthly on FTI systems
- Implement media sanitization procedures meeting NIST SP 800-88 guidelines
- Segment FTI systems from non-FTI systems on the network
- Implement a system development lifecycle (SDLC) that incorporates security for FTI systems

### Incident Response
- Establish an incident response plan specific to FTI breaches
- Report all unauthorized access, disclosure, or use of FTI to the IRS Office of Safeguards and the Treasury Inspector General for Tax Administration (TIGTA) within 24 hours
- Report suspected criminal violations to TIGTA
- Conduct post-incident analysis and implement corrective actions
- Maintain records of all FTI-related security incidents

### Disposal
- Destroy paper FTI by cross-cut shredding, pulping, or burning
- Destroy electronic FTI using methods consistent with NIST SP 800-88 (clear, purge, or destroy)
- Document all FTI disposal activities
- Ensure contractor disposal meets the same standards

## Federal Tax Information Defined

Federal Tax Information (FTI) is defined broadly by the IRS and includes:

**Tax returns.** Form 1040, Form 1120, and all other tax returns filed with the IRS.

**Return information.** Any information the IRS receives, processes, or determines related to a taxpayer's liability or potential liability, including:
- Taxpayer names, addresses, and Social Security Numbers received from the IRS
- Filing status, income amounts, deduction amounts, credit amounts
- Whether a return was filed, the date filed, and the amount of tax paid
- Transaction codes, account balances, and payment history
- Information derived from IRS data (calculations, determinations based on FTI)

**Derived information.** Information created by the receiving agency that is extracted from, based on, or derived from FTI. This is a critical concept: if an agency uses FTI as an input to calculate an eligibility determination, the resulting data may still be FTI and subject to all Publication 1075 safeguards.

**Key distinctions:**
- FTI retains its character as FTI regardless of how many times it is copied, processed, or transformed
- FTI does not lose its protected status when combined with non-FTI data
- Information is no longer FTI only when it cannot be associated with or used to identify (directly or indirectly) a specific taxpayer
- Verbal disclosure of FTI (e.g., reading tax data to someone) is still subject to all safeguard requirements

## Safeguard Security Report (SSR)

The Safeguard Security Report is the primary compliance documentation that agencies must submit annually to the IRS Office of Safeguards. The SSR documents the agency's security posture, describes the systems and processes used to protect FTI, and reports on the agency's compliance with Publication 1075 requirements.

### SSR Contents
The SSR must include:

1. **Agency profile.** Organizational structure, mission, programs receiving FTI
2. **Points of contact.** Safeguard Security Coordinator and alternates
3. **System inventory.** All systems that receive, process, store, or transmit FTI
4. **Network diagrams.** Showing FTI data flows, network segmentation, security controls
5. **Security controls.** Documentation of each applicable NIST SP 800-53 control
6. **Contractor information.** All contractors and subcontractors with access to FTI
7. **Background investigation status.** Status of background checks for all FTI personnel
8. **Training records.** Status of security awareness training for FTI personnel
9. **Incident reports.** Any security incidents involving FTI during the reporting period
10. **Disposal documentation.** Records of FTI disposal activities
11. **Risk assessment results.** Most recent risk assessment findings and remediation plans

### SSR Submission
- SSRs are submitted electronically through the IRS Safeguard Compliance Portal
- Annual submission is required, with updates as significant changes occur
- The IRS reviews SSRs and may request additional information or clarification
- SSR findings may trigger a Safeguard Review (on-site audit)

## How IRS Publication 1075 Maps to NIST SP 800-53

IRS Publication 1075 is one of the most direct implementations of NIST SP 800-53 in the government compliance landscape. The relationship is explicit and structural:

**Publication 1075 adopts the NIST SP 800-53 Rev. 5 Moderate baseline** as its foundation. This means that every control in the NIST Moderate baseline is applicable to FTI systems unless explicitly tailored or excluded by Publication 1075.

**IRS-specific parameters and enhancements.** Publication 1075 adds IRS-specific values to many NIST SP 800-53 controls. For example:
- **AC-2 Account Management:** Publication 1075 requires that all FTI user accounts be reviewed at least annually (more frequently than the base NIST Moderate requirement)
- **AU-2 Event Logging:** Publication 1075 specifies the exact events that must be logged for FTI systems, including all access to, creation, modification, and deletion of FTI
- **IA-2 Identification and Authentication:** Publication 1075 requires FIPS 140-2 validated multi-factor authentication for all remote access to FTI systems
- **IR-6 Incident Reporting:** Publication 1075 requires notification to IRS and TIGTA within 24 hours of discovering an FTI breach, which is more stringent than the base NIST requirement
- **MP-6 Media Sanitization:** Publication 1075 requires sanitization consistent with NIST SP 800-88 and maintains specific destruction requirements for paper FTI
- **SC-28 Protection of Information at Rest:** Publication 1075 requires FIPS 140-2 validated encryption for all FTI at rest, a specific parameterization of the NIST control

**All 20 NIST SP 800-53 control families are addressed.** Publication 1075's technical controls map to:
- Access Control (AC)
- Awareness and Training (AT)
- Audit and Accountability (AU)
- Security Assessment and Authorization (CA)
- Configuration Management (CM)
- Contingency Planning (CP)
- Identification and Authentication (IA)
- Incident Response (IR)
- Maintenance (MA)
- Media Protection (MP)
- Physical and Environmental Protection (PE)
- Planning (PL)
- Program Management (PM)
- Personnel Security (PS)
- Risk Assessment (RA)
- System and Services Acquisition (SA)
- System and Communications Protection (SC)
- System and Information Integrity (SI)
- Supply Chain Risk Management (SR)
- PII Processing and Transparency (PT)

**Practical implication.** Organizations that already maintain compliance with NIST SP 800-53 Moderate baseline have approximately 80% to 90% of the Publication 1075 technical controls in place. The remaining gap consists of IRS-specific parameterizations, supplemental requirements, and FTI-specific procedural controls.

For agencies that also need to comply with FISMA, FedRAMP, CMMC, or HIPAA, the shared NIST SP 800-53 foundation means significant control reuse. A well-implemented NIST SP 800-53 Moderate baseline can support compliance across multiple frameworks simultaneously.

## IRS Safeguard Reviews and Audits

The IRS Office of Safeguards conducts periodic Safeguard Reviews (on-site audits) to verify that agencies are complying with Publication 1075 requirements. Understanding the review process is essential for maintaining compliance.

### Review Frequency
- State tax agencies with the largest FTI volumes are typically reviewed every 3 years
- Other agencies may be reviewed less frequently, based on risk
- Agencies with identified deficiencies may be reviewed more frequently
- The IRS may conduct unannounced reviews in response to reported incidents

### Review Process
1. **Notification.** The IRS notifies the agency approximately 60 to 90 days before the review
2. **Pre-review questionnaire.** The agency completes a detailed questionnaire about its security posture
3. **On-site review.** IRS Safeguard reviewers conduct multi-day on-site inspections covering physical security, technical controls, policy documentation, and personnel
4. **Findings report.** The IRS issues a findings report identifying deficiencies
5. **Corrective Action Plan (CAP).** The agency must submit a CAP addressing all findings
6. **CAP monitoring.** The IRS monitors the agency's progress in implementing corrective actions

### Common Review Findings
- Incomplete or outdated system inventories in the SSR
- Insufficient network segmentation between FTI and non-FTI systems
- Background investigations not completed for all FTI personnel
- Missing or incomplete audit logs for FTI access
- Encryption not implemented for FTI at rest
- Contractor oversight gaps
- Outdated or untested incident response plans

## Compliance Checklist Summary

The detailed compliance checklist is available in [compliance-checklist.md](compliance-checklist.md). At a high level, Publication 1075 compliance involves the following phases:

### Phase 1: Program Establishment (Months 1 to 3)
- Designate a Safeguard Security Coordinator
- Inventory all systems and data flows involving FTI
- Identify all personnel and contractors with FTI access
- Conduct initial gap assessment against Publication 1075 requirements
- Develop a remediation roadmap

### Phase 2: Control Implementation (Months 2 to 8)
- Implement NIST SP 800-53 Moderate baseline controls with IRS parameters
- Deploy encryption for FTI at rest and in transit (FIPS 140-2)
- Implement network segmentation for FTI systems
- Deploy audit logging and monitoring
- Establish background investigation processes
- Implement FTI-specific security awareness training

### Phase 3: Documentation and SSR (Months 6 to 10)
- Develop Safeguard Security Plan (SSP)
- Complete the Safeguard Security Report (SSR)
- Document all security controls and their implementation
- Prepare network diagrams and data flow documentation
- Compile contractor and personnel documentation

### Phase 4: Continuous Operations
- Submit annual SSR updates
- Conduct periodic risk assessments
- Monitor and respond to security events
- Maintain training and background investigation currency
- Prepare for Safeguard Reviews
- Manage FTI disposal per requirements

## Common Pitfalls and How to Avoid Them

**Underestimating the scope of FTI.** Agencies often fail to track FTI through all of its transformations and copies. FTI that is extracted, derived, or combined with other data may still be FTI. Conduct thorough data flow mapping to identify every location where FTI exists.

**Insufficient contractor oversight.** Agencies are responsible for ensuring their contractors comply with Publication 1075. This means conducting security assessments of contractors, including FTI-specific requirements in contracts, and monitoring contractor compliance. The IRS holds the agency, not the contractor, accountable for FTI protection.

**Network segmentation failures.** FTI systems must be segmented from non-FTI systems. Many agencies struggle with this because FTI is used in systems that also process non-FTI data. Proper segmentation may require re-architecting networks, which takes time and resources.

**Background investigation backlogs.** All personnel with access to FTI must undergo background investigations before receiving access. Agencies with high turnover or large contractor workforces may struggle to keep investigations current. Plan ahead and build investigation timelines into hiring and contracting processes.

**Encryption gaps.** Publication 1075 requires FIPS 140-2 validated encryption for FTI in transit and at rest. Not all encryption solutions are FIPS validated. Verify that your encryption products appear on the NIST Cryptographic Module Validation Program (CMVP) list.

**Incident reporting delays.** FTI breaches must be reported to IRS and TIGTA within 24 hours. Agencies without a well-rehearsed incident response plan may miss this deadline, which can result in additional findings during Safeguard Reviews.

**SSR quality issues.** The SSR is a comprehensive document that requires detailed technical information. Agencies that treat it as a paperwork exercise rather than a meaningful security assessment often produce SSRs that trigger additional IRS scrutiny or Safeguard Reviews.

## Frequently Asked Questions

**Q: What is the difference between Publication 1075 and NIST SP 800-53?**
A: NIST SP 800-53 is a general-purpose catalog of security and privacy controls for federal information systems. Publication 1075 takes the NIST SP 800-53 Moderate baseline and adds IRS-specific parameters, enhancements, and requirements tailored to protecting Federal Tax Information. Publication 1075 is a NIST SP 800-53 overlay specific to FTI.

**Q: Does Publication 1075 apply to cloud environments?**
A: Yes. Agencies that use cloud services to process, store, or transmit FTI must ensure that the cloud environment meets all Publication 1075 requirements. The cloud service provider must be included in the agency's SSR, and the agency must maintain contractual controls over the provider's handling of FTI. FedRAMP authorization alone does not satisfy Publication 1075 requirements; IRS-specific parameters must also be met.

**Q: How often is the SSR submitted?**
A: The SSR must be submitted annually to the IRS Office of Safeguards. Agencies must also submit updates when significant changes occur, such as new systems processing FTI, changes in contractor arrangements, or security incidents.

**Q: What triggers an IRS Safeguard Review?**
A: The IRS selects agencies for Safeguard Reviews based on several factors: the volume of FTI received, the time since the last review, findings from previous reviews, incidents reported, and SSR quality. Agencies that receive large volumes of FTI (such as state tax agencies) are typically reviewed every 3 years.

**Q: What happens if an agency fails a Safeguard Review?**
A: The IRS issues a findings report with identified deficiencies. The agency must submit a Corrective Action Plan (CAP) and implement remediation within the specified timeframe. If deficiencies are severe or remain unaddressed, the IRS can suspend or terminate the agency's access to FTI, which can shut down the programs that depend on that data.

**Q: Does Publication 1075 require FIPS 140-2 or FIPS 140-3?**
A: Publication 1075 currently references FIPS 140-2. However, NIST's Cryptographic Module Validation Program (CMVP) has transitioned to FIPS 140-3 for new validations. Products validated under FIPS 140-2 remain acceptable. Agencies should plan for FIPS 140-3 in future procurement decisions.

**Q: How does Publication 1075 handle remote work and telework?**
A: Publication 1075 requires that FTI accessed remotely be protected with FIPS 140-2 validated encryption and multi-factor authentication. The agency must ensure that remote work environments meet physical security requirements (e.g., FTI is not visible to unauthorized persons, paper FTI is secured when not in use). Remote access policies must be documented in the SSP and SSR.

**Q: Can FTI be stored on mobile devices?**
A: Publication 1075 permits FTI on mobile devices only if the device meets all applicable security requirements, including FIPS 140-2 encryption, device management, remote wipe capability, and strong authentication. Many agencies prohibit FTI on mobile devices as a practical matter because meeting all requirements is difficult.

**Q: What are the penalties for unauthorized disclosure of FTI?**
A: IRC Section 7213 makes willful unauthorized disclosure of FTI a felony punishable by up to 5 years imprisonment and a fine of up to $5,000. IRC Section 7213A makes unauthorized inspection (access without disclosure) a misdemeanor punishable by up to 1 year imprisonment and a fine of up to $1,000. Civil damages under IRC Section 7431 allow affected taxpayers to sue for $1,000 per unauthorized disclosure or actual damages, whichever is greater, plus costs and attorney fees.

## About Petronella Technology Group

This checklist is maintained by **Craig Petronella** and the compliance team at **Petronella Technology Group, Inc. (PTG)**.

**Craig Petronella's credentials:**
- CMMC Registered Practitioner
- Licensed Digital Forensic Examiner #604180
- Cisco CCNA, CWNE
- MIT Artificial Intelligence Certificate
- Amazon #1 Best-Selling Author of 14+ cybersecurity books
- 23+ years in cybersecurity

PTG provides comprehensive Publication 1075 compliance support for government agencies and their contractors, including gap assessments, SSR preparation, control implementation, and Safeguard Review readiness. PTG uses its own private AI fleet, including on-premise LLMs and custom GPU infrastructure, to accelerate compliance assessments and automate NIST SP 800-53 control mapping. PTG's patented technology stack automates what competitors do manually, and as a Licensed Digital Forensic Examiner, Craig Petronella brings forensic investigation capability that most compliance firms cannot offer. When a breach occurs involving FTI, PTG can investigate, preserve evidence, and support the mandatory reporting to IRS and TIGTA.

**Contact PTG:**
- Phone: 919-348-4912
- Web: [https://petronellatech.com/compliance/irs-1075/](https://petronellatech.com/compliance/irs-1075/)
- Address: 5540 Centerview Dr. Suite 200, Raleigh, NC 27606

Call 919-348-4912 or visit [https://petronellatech.com/compliance/irs-1075/](https://petronellatech.com/compliance/irs-1075/) to schedule a free Publication 1075 compliance assessment.

## Additional Resources

- [IRS Publication 1075 (current version)](https://www.irs.gov/privacy-disclosure/safeguards-program)
- [IRC Section 6103](https://www.law.cornell.edu/uscode/text/26/6103)
- [NIST SP 800-53 Rev. 5 Control Catalog](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
- [NIST SP 800-88 Rev. 1 Guidelines for Media Sanitization](https://csrc.nist.gov/publications/detail/sp/800-88/rev-1/final)
- [FIPS 140-2 Validated Modules (CMVP)](https://csrc.nist.gov/projects/cryptographic-module-validation-program)
- [Treasury Inspector General for Tax Administration (TIGTA)](https://www.treasury.gov/tigta/)
- [PTG Compliance Services](https://petronellatech.com/compliance/)
- [PTG NIST Compliance Hub](https://petronellatech.com/nist/)
- [PTG NIST 800-53 Compliance](https://petronellatech.com/compliance/nist-800-53-compliance/)
- [PTG AI Services](https://petronellatech.com/ai/)
- [PTG Cybersecurity Services](https://petronellatech.com/cybersecurity/)
- [PTG Compliance Packages](https://petronellatech.com/compliance/packages/)

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
