Item,Amount_or_Value,Rationale
Category,Estimated Amount,Rationale
Legal counsel and investigation,2400000,"Outside counsel, forensic review, privilege management"
Regulatory response reserve,3800000,"Potential penalties, settlement support, reporting obligations"
Customer notification and support,2100000,"Notification, call center, identity protection assistance"
Incident response consulting,1500000,"Containment, evidence handling, technical root cause analysis"
Revenue and customer attrition impact,5200000,Modeled loss from contract churn and delayed renewals
Cyber insurance premium impact,900000,Projected premium increase and deductible impact
Shareholder confidence impact,2800000,"Investor relations, volatility response, market confidence program"
Subtotal exposure,=SUM(B2:B8),
Contingency reserve,=B9*0.15,15 percent planning reserve
Estimated total exposure,=B9+B10,
,,
Remediation Item,Estimated Cost,Rationale
Centralized GRC platform and vendor inventory,850000,"Workflow, evidence repository, renewal gating"
IAM modernization and privileged access governance,1200000,"Access certification, service account controls, phishing resistant MFA"
SIEM log onboarding and vendor anomaly detection,950000,"API telemetry, alert tuning, dashboards"
Supplier contract refresh and legal operations,420000,"Security addendum, audit rights, notification timelines"
Human control redesign and simulations,280000,"Behavior based training, reviewer sampling, tabletop exercises"
Program management and internal audit validation,510000,"Roadmap tracking, evidence testing, audit sampling"
Estimated remediation cost,=SUM(B14:B19),
,,
Risk Reduction Inputs,Value,Rationale
Current average residual risk,=Dashboard!B7,Linked to risk register
Target average residual risk after roadmap,5.5,Expected post implementation average
Risk points reduced,=B23-B24,
Projected risk reduction,"=IFERROR(B25/B23,0)",
