# Plan of Action and Milestones

## POA&M Item 1: Formalize Data Classification

Weakness  
Restricted data is not consistently labeled or tied to access control decisions.

Risk  
Users may access healthcare, finance, or federal data without a clear business need.

Corrective Action  
Create a data classification standard covering restricted, confidential, internal, and public data. Tag storage locations according to data type and required handling.

Milestones  
1. Draft classification standard.  
2. Identify all repositories containing restricted data.  
3. Label restricted repositories.  
4. Tie labels to access policies.  
5. Validate through access review.

Evidence  
Approved classification standard, repository inventory, access policy screenshots, review ticket.

Owner  
Governance Risk and Compliance Owner.

Target Completion  
60 days.

## POA&M Item 2: Enforce Multifactor Authentication

Weakness  
Some privileged and vendor administrator accounts do not have enforced multifactor authentication.

Risk  
Credential compromise could lead to unauthorized access to regulated data.

Corrective Action  
Require multifactor authentication for all privileged, remote, and vendor access. Any exception must be time limited and approved by the Qualified Individual or equivalent accountable security leader.

Milestones  
1. Export privileged and vendor account list.  
2. Identify accounts without multifactor authentication.  
3. Enforce policy.  
4. Document exceptions.  
5. Test access.

Evidence  
Identity provider policy export, exception log, test screenshots.

Owner  
Identity and Access Management Owner.

Target Completion  
30 days.

## POA&M Item 3: Improve Logging and Monitoring

Weakness  
Logs are not consistently collected, retained, or reviewed across the application, cloud platform, and identity provider.

Risk  
Security incidents may not be detected or investigated in time.

Corrective Action  
Define required log sources, retention period, alert rules, and review cadence.

Milestones  
1. Build log source inventory.  
2. Define required events.  
3. Configure alert rules.  
4. Document retention settings.  
5. Perform sample review.

Evidence  
Log source inventory, alert configuration, review record.

Owner  
Security Operations Owner.

Target Completion  
45 days.

## POA&M Item 4: Strengthen Vendor Oversight

Weakness  
Vendor reviews are not consistently documented for vendors touching restricted data.

Risk  
Third party weaknesses could expose healthcare, finance, or federal data.

Corrective Action  
Tier vendors by data sensitivity and business criticality. Require documented due diligence, contracts, reassessment, and exit planning.

Milestones  
1. Build vendor inventory.  
2. Assign vendor risk tiers.  
3. Collect security documents.  
4. Confirm contract requirements.  
5. Schedule annual reviews.

Evidence  
Vendor inventory, tiering worksheet, contracts, questionnaires, review calendar.

Owner  
Vendor Risk Owner.

Target Completion  
75 days.

## POA&M Item 5: Build Cross Sector Incident Decision Matrix

Weakness  
The incident response plan does not clearly separate healthcare, finance, and federal obligations.

Risk  
The organization may delay escalation or choose the wrong notification path.

Corrective Action  
Add an incident decision matrix that identifies affected data type, regulator, contract owner, legal contact, evidence needed, and notification pathway.

Milestones  
1. Draft matrix.  
2. Review with legal, privacy, security, and federal program owner.  
3. Run tabletop exercise.  
4. Update incident response plan.  
5. Train responders.

Evidence  
Approved matrix, tabletop results, updated incident response plan, training records.

Owner  
Incident Response Owner.

Target Completion  
60 days.
