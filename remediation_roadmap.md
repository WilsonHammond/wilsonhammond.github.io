# Project Violet Ledger Case Study

## Company Profile

CivicCare Nexus is a fictional healthcare analytics and payment coordination company with 8,400 employees, 147 active vendors, and 3.2 billion dollars in annual revenue. Its ecosystem supports claims analytics, payment reconciliation, document storage, customer support, executive reporting, and contractor operations.

The environment contains Protected Health Information, payment metadata, customer identifiers, claims documents, and internal financial reporting. That combination creates legal, operational, privacy, and shareholder confidence exposure.

## Incident Narrative

A third party analytics vendor retained privileged Application Programming Interface access after a modernization project ended. The access path remained active because the quarterly vendor access review was not completed and because the vendor security assessment had expired 14 months earlier.

A contractor device associated with the vendor was infected by infostealer malware. Attackers reused session credentials, accessed the vendor platform, and leveraged dormant Application Programming Interface permissions to reach sensitive CivicCare Nexus data.

The attackers remained active for 23 days before detection. Public disclosure was delayed by 11 days because Legal, Security, Compliance, Communications, and Procurement did not have a clear escalation model.

## Root Cause

The breach was not only a technical failure. It was a governance failure shaped by human behavior and process decay.

The failed control pattern included incomplete supplier inventory, stale privileged access, weak evidence review, expired assessments, poor exception management, unclear ownership, fragmented monitoring, and ineffective training measurement.

## Business Impact

1. Estimated total exposure, 18.7 million dollars
2. Estimated remediation cost, 4.21 million dollars
3. 6 open high risks
4. 7 human controls below target
5. Projected residual risk reduction after remediation, 68 percent

## Analyst Interpretation

The important finding is that several controls existed in policy but failed in practice. This means the enterprise had control design without control effectiveness. A mature recovery program must therefore repair not only tooling, but also ownership, evidence quality, approval behavior, escalation discipline, and executive governance.
