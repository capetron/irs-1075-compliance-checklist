# IRS Publication 1075 Compliance Checklist

A practical, actionable checklist for federal, state, and local government agencies, their contractors, and service providers that receive and handle Federal Tax Information (FTI) under IRC Section 6103.

Last Reviewed: March 2026

---

## Program Governance

- [ ] Designate a Safeguard Security Coordinator (SSC) with authority over FTI protection
- [ ] Designate an alternate SSC for continuity
- [ ] Develop and maintain a Safeguard Security Plan (SSP)
- [ ] Submit the Safeguard Security Report (SSR) to IRS Office of Safeguards annually
- [ ] Establish an FTI security governance committee with IT, legal, and program representation
- [ ] Develop FTI-specific information security policies and procedures
- [ ] Review and update FTI policies at least annually
- [ ] Conduct annual risk assessments for all systems processing FTI
- [ ] Maintain a risk register documenting identified risks, owners, and treatment plans
- [ ] Document all waivers, exceptions, and risk acceptances with management approval

---

## System Inventory and Data Flow

- [ ] Inventory all systems that receive, process, store, or transmit FTI
- [ ] Document all data flows involving FTI (from IRS receipt through processing, storage, and destruction)
- [ ] Identify all locations where FTI is stored (databases, file systems, backups, paper files)
- [ ] Identify all derived data that qualifies as FTI
- [ ] Map FTI data flows across organizational boundaries (to/from contractors, other agencies)
- [ ] Maintain network diagrams showing FTI network segments and security boundaries
- [ ] Update the system inventory and data flow documentation when changes occur
- [ ] Include all contractor systems in the inventory

---

## Personnel Security

- [ ] Conduct background investigations on all personnel with access to FTI before granting access
- [ ] Conduct background investigations appropriate to the level of access (suitability/fitness)
- [ ] Re-investigate personnel at intervals required by Publication 1075
- [ ] Verify background investigation status for all contractors with FTI access
- [ ] Maintain records of all background investigations
- [ ] Restrict FTI access to personnel with a demonstrated need-to-know
- [ ] Revoke FTI access immediately upon personnel separation or role change
- [ ] Collect all FTI materials and access credentials upon personnel departure
- [ ] Maintain a current list of all personnel authorized to access FTI

---

## Security Awareness Training

- [ ] Provide FTI-specific security awareness training to all personnel with FTI access
- [ ] Deliver initial training before granting FTI access
- [ ] Conduct refresher training at least annually
- [ ] Include the following topics: FTI definition, handling requirements, prohibited actions, incident reporting, disposal procedures, penalties for unauthorized disclosure
- [ ] Track training completion and maintain records for audit
- [ ] Update training content to reflect current Publication 1075 requirements and threat landscape
- [ ] Include contractor personnel in the training program
- [ ] Test training effectiveness through quizzes or simulated scenarios

---

## Access Control (NIST AC Family)

- [ ] Implement role-based access control (RBAC) for all FTI systems
- [ ] Enforce the principle of least privilege for all FTI accounts
- [ ] Require unique user IDs for all personnel accessing FTI (no shared accounts)
- [ ] Implement multi-factor authentication (MFA) for remote access to FTI systems
- [ ] Implement MFA for all privileged/administrative access to FTI systems
- [ ] Enforce account lockout after a defined number of failed authentication attempts
- [ ] Disable FTI accounts after 90 days of inactivity
- [ ] Conduct reviews of FTI user accounts at least annually
- [ ] Implement session timeout for inactive FTI sessions
- [ ] Restrict FTI access to government-furnished or approved equipment
- [ ] Implement access controls for FTI in database management systems
- [ ] Log and monitor all access to FTI systems
- [ ] Document and approve all FTI access authorizations

---

## Audit Logging and Accountability (NIST AU Family)

- [ ] Enable audit logging on all FTI systems
- [ ] Log the following events: login/logout, failed authentication, FTI access, FTI modification, FTI deletion, FTI printing, FTI transmission, administrative actions, privilege escalation
- [ ] Include in each log entry: user ID, date/time, event type, success/failure, data object accessed
- [ ] Centralize log collection using a SIEM or log management platform
- [ ] Protect log integrity (write-once storage, access controls, checksums)
- [ ] Retain audit logs for a minimum of 7 years (per IRS requirements)
- [ ] Review audit logs regularly (daily for critical systems, weekly for others)
- [ ] Implement automated alerting for suspicious FTI access patterns
- [ ] Correlate FTI access logs with personnel and access control records
- [ ] Include contractor system logs in centralized monitoring

---

## Configuration Management (NIST CM Family)

- [ ] Establish baseline configurations for all FTI system types
- [ ] Harden FTI systems according to CIS Benchmarks, DISA STIGs, or equivalent standards
- [ ] Implement a formal change management process for FTI systems
- [ ] Test all changes in a non-production environment before deploying to FTI systems
- [ ] Restrict the ability to modify FTI system configurations to authorized administrators
- [ ] Implement file integrity monitoring (FIM) on critical FTI system files
- [ ] Conduct configuration compliance scans at least quarterly
- [ ] Document all deviations from baseline configurations with justification
- [ ] Maintain a configuration management database (CMDB) for FTI systems

---

## Contingency Planning (NIST CP Family)

- [ ] Develop a contingency plan for FTI systems
- [ ] Include recovery time objectives (RTO) and recovery point objectives (RPO)
- [ ] Implement backup procedures for FTI data
- [ ] Encrypt FTI backups using FIPS 140-2 validated encryption
- [ ] Store backup media in a secure off-site location
- [ ] Test contingency plans at least annually
- [ ] Update contingency plans after significant system changes
- [ ] Document roles and responsibilities for contingency operations
- [ ] Ensure backup and recovery procedures maintain FTI confidentiality

---

## Identification and Authentication (NIST IA Family)

- [ ] Implement FIPS 140-2 validated multi-factor authentication for remote FTI access
- [ ] Enforce strong password policies (minimum 12 characters, complexity requirements)
- [ ] Implement account lockout after a defined number of failed attempts
- [ ] Display a system use notification (login banner) on all FTI systems
- [ ] Authenticate all devices connecting to FTI network segments
- [ ] Implement PIV/CAC card authentication where applicable (federal systems)
- [ ] Prohibit the use of shared or group authentication credentials for FTI access
- [ ] Implement re-authentication for privileged actions on FTI systems

---

## Incident Response (NIST IR Family)

- [ ] Develop an incident response plan specific to FTI breaches
- [ ] Define roles and responsibilities for FTI incident response
- [ ] Establish procedures for reporting FTI breaches to IRS Office of Safeguards within 24 hours
- [ ] Establish procedures for reporting suspected criminal FTI violations to TIGTA
- [ ] Maintain contact information for IRS Safeguards and TIGTA reporting
- [ ] Conduct incident response training at least annually
- [ ] Test the incident response plan through tabletop exercises at least annually
- [ ] Document all FTI security incidents, including near-misses
- [ ] Conduct post-incident reviews and implement corrective actions
- [ ] Include FTI incident response procedures in contractor agreements

---

## Media Protection (NIST MP Family)

- [ ] Label all media containing FTI appropriately
- [ ] Restrict access to FTI media to authorized personnel
- [ ] Encrypt FTI on all removable media using FIPS 140-2 validated encryption
- [ ] Track all removable media containing FTI through a media inventory
- [ ] Sanitize FTI media before reuse or disposal per NIST SP 800-88
- [ ] Cross-cut shred paper FTI (minimum DIN 66399 Level P-4 or equivalent)
- [ ] Document all FTI media disposal activities with date, method, and witness
- [ ] Prohibit storage of FTI on unauthorized removable media
- [ ] Implement controls for media in transit (encryption, tracking, chain of custody)

---

## Physical and Environmental Protection (NIST PE Family)

- [ ] Restrict physical access to areas where FTI is processed, stored, or displayed
- [ ] Implement access control mechanisms (badges, PINs, biometrics) for FTI areas
- [ ] Maintain visitor logs for all FTI areas
- [ ] Escort visitors in FTI areas at all times
- [ ] Position screens displaying FTI away from unauthorized viewing (privacy screens)
- [ ] Implement a clean desk policy for areas where paper FTI is handled
- [ ] Store paper FTI in locked containers when not in use
- [ ] Implement environmental controls (fire suppression, HVAC, water detection) for FTI server rooms
- [ ] Conduct periodic physical security assessments of FTI areas
- [ ] Control and document the removal of FTI from secured areas

---

## System and Communications Protection (NIST SC Family)

- [ ] Encrypt FTI in transit using FIPS 140-2 validated cryptographic modules (TLS 1.2+)
- [ ] Encrypt FTI at rest using FIPS 140-2 validated cryptographic modules
- [ ] Segment FTI network segments from non-FTI networks
- [ ] Implement boundary protection (firewalls) between FTI and non-FTI segments
- [ ] Restrict inbound and outbound traffic to/from FTI segments to documented, approved flows
- [ ] Implement DNS filtering and web content filtering on FTI network segments
- [ ] Disable unnecessary protocols and services on FTI systems
- [ ] Implement VPN for all remote access to FTI systems
- [ ] Deploy intrusion detection/prevention systems (IDS/IPS) on FTI network segments
- [ ] Monitor for unauthorized connections to FTI network segments

---

## System and Information Integrity (NIST SI Family)

- [ ] Deploy anti-malware on all FTI systems with automatic updates
- [ ] Conduct vulnerability scanning on FTI systems at least monthly
- [ ] Remediate critical and high vulnerabilities within Publication 1075 timelines
- [ ] Apply security patches to FTI systems within defined timelines
- [ ] Monitor FTI systems for unauthorized changes
- [ ] Implement spam filtering for email systems connected to FTI networks
- [ ] Validate all input to FTI applications
- [ ] Monitor for information leakage from FTI systems
- [ ] Subscribe to security advisories for all FTI system software

---

## Contractor and Third-Party Management

- [ ] Include Publication 1075 requirements in all contracts involving FTI
- [ ] Require contractors to submit safeguard documentation for IRS review
- [ ] Conduct security assessments of contractors before granting FTI access
- [ ] Verify contractor background investigations for all personnel with FTI access
- [ ] Include contractor systems in the agency's SSR
- [ ] Monitor contractor compliance on an ongoing basis
- [ ] Require contractors to report FTI security incidents immediately
- [ ] Include FTI disposal requirements in contractor agreements
- [ ] Ensure subcontractors are held to the same Publication 1075 standards
- [ ] Maintain contracts that allow for IRS Safeguard Reviews of contractor facilities

---

## FTI Disposal

- [ ] Destroy paper FTI by cross-cut shredding (minimum DIN 66399 Level P-4), pulping, or burning
- [ ] Sanitize electronic FTI media per NIST SP 800-88 (clear, purge, or destroy)
- [ ] Document all FTI disposal activities (date, method, media type, responsible person)
- [ ] Require witness verification for bulk FTI disposal
- [ ] Include backup media in the disposal schedule
- [ ] Ensure contractor FTI disposal meets the same standards
- [ ] Obtain certificates of destruction from contractors when applicable
- [ ] Dispose of FTI when no longer needed for the authorized purpose

---

## SSR Preparation

- [ ] Gather current system inventory and update as needed
- [ ] Update network diagrams and data flow documentation
- [ ] Compile security control implementation evidence for each applicable NIST 800-53 control
- [ ] Update contractor and personnel listings
- [ ] Compile training records and background investigation status
- [ ] Document any security incidents during the reporting period
- [ ] Document FTI disposal activities during the reporting period
- [ ] Compile risk assessment results and remediation plans
- [ ] Review the SSR for completeness and accuracy before submission
- [ ] Submit the SSR through the IRS Safeguard Compliance Portal by the annual deadline

---

## Safeguard Review Readiness

- [ ] Maintain all SSR documentation in a readily accessible format
- [ ] Keep previous Safeguard Review findings and CAP documentation available
- [ ] Ensure all corrective actions from previous reviews are fully implemented
- [ ] Brief key personnel on the review process and their roles
- [ ] Prepare evidence packages for each NIST 800-53 control family
- [ ] Verify that physical security measures are in place and functioning
- [ ] Confirm that all systems in the SSR are accurately documented
- [ ] Test incident response procedures before the review
- [ ] Ensure background investigation records are current for all FTI personnel
- [ ] Review contractor compliance documentation for completeness

---

## Need Help with IRS Publication 1075 Compliance?

Petronella Technology Group, Inc. (PTG) provides comprehensive Publication 1075 compliance support, including gap assessments, SSR preparation, NIST SP 800-53 control implementation, and Safeguard Review readiness. PTG's AI-powered compliance tools automate control mapping, evidence collection, and continuous monitoring.

**Call 919-348-4912** or visit [https://petronellatech.com/compliance/irs-1075/](https://petronellatech.com/compliance/irs-1075/) to schedule a free Publication 1075 compliance assessment.

Petronella Technology Group, Inc.
5540 Centerview Dr. Suite 200
Raleigh, NC 27606
