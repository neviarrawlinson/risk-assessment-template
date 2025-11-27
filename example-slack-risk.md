# Risk Assessment: Slack Integration

## Risk Overview

**Risk Title:** Unauthorized Data Access via Slack App

**Risk Description:**  
Third-party Slack integrations may expose sensitive customer data through misconfigured APIs, lack of governance, or excessive permissions. Slack apps are not consistently reviewed or monitored post-approval.

**Category:** Compliance

**Risk Owner:** IT Governance Lead

---

## ⚙️ Risk Evaluation

| Element         | Rating (1–5) | Notes                                |
|----------------|--------------|--------------------------------------|
| Likelihood      | 3            | Many integrations are already in use |
| Impact          | 4            | Potential exposure of sensitive PII  |
| Inherent Risk   | 12           |                                      |

---

## Controls and Mitigation

**Controls in Place:**  
- Manual Slack App review process  
- OAuth scopes limited during provisioning  
- Jira intake process required for new integrations  

**Residual Risk Score:**  
6

**Mitigation Plan:**  
- Implement Slack Enterprise Grid governance  
- Automatically expire unused apps  
- Publish Slack governance policy  
- Move app review ownership under IT Governance

---

## Review & Monitoring

**Next Review Date:** January 2026

**Reviewed By:** Neviar Rawlinson

---

## Notes

Risk identified during SOC 2 audit preparation. Related to Jira ticket `GOV-42`.
