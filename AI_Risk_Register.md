
# AI Risk Register

## 1. Purpose
This register documents identified AI risks, their severity, ownership and mitigation status.

## 2. Risk Register

| Risk ID | Risk Category | Risk Description | Likelihood | Impact | Risk Score | Risk Level |
|---|---|---|---|---|---|---|
| R001 | Bias | Unfair candidate screening | 4 | 5 | 20 | Critical |
| R002 | Privacy | Exposure of personal data | 3 | 5 | 15 | High |
| R003 | Accuracy | Incorrect AI decisions | 4 | 4 | 16 | High |
| R004 | Transparency | Unclear AI decision-making | 3 | 3 | 9 | Medium |
| R005 | Security | Unauthorized data access | 3 | 5 | 15 | High |

## 3. Risk Ownership

| Risk ID | Responsible Team |
|---|---|
| R001 | AI Governance Team |
| R002 | Data Protection Team |
| R003 | AI Development Team |
| R004 | Compliance Team |
| R005 | Information Security Team |

## 4. Risk Treatment Status

| Risk ID | Recommended Action | Status |
|---|---|---|
| R001 | Conduct bias testing | Pending |
| R002 | Implement privacy controls | Pending |
| R003 | Validate AI outputs | Pending |
| R004 | Improve transparency | Pending |
| R005 | Strengthen access controls | Pending |

## 5. Monitoring
- Review risks periodically.
- Track mitigation progress.
- Update risk scores after controls are implemented.
- Escalate critical risks to management.

## Control Assessment – AI Hiring System

| Risk ID | Risk | Existing Control | Control Owner | Evidence Required | Effectiveness |
|---|---|---|---|---|---|
| R-01 | Gender Bias | Bias testing and monitoring | AI/ML Team | Bias testing reports and model validation results | Not Verified |
| R-02 | Candidate Data Exposure | Encryption and access restrictions | Information Security | Encryption configuration and access logs | Not Verified |
| R-03 | Incorrect Candidate Ranking | Human review of shortlisted candidates | HR Team | Human review records and override logs | Not Verified |
| R-04 | Lack of Transparency | Candidate notification and explanation process | HR / AI Governance | Candidate notices and explanation records | Not Verified |
| R-05 | Excessive Employee Access | Role-Based Access Control (RBAC) | Information Security | Access matrix and access review records | Not Verified |

### Assessment Rule

A control must not be marked Effective based only on management confirmation or policy documentation.

Evidence must be reviewed and control operation must be verified before effectiveness is confirmed.

## Evidence Review Findings

| Risk ID | Evidence Gap | Auditor Decision | Status |
|---|---|---|---|
| R-01 | Bias testing report missing | Request testing evidence | Open |
| R-02 | Access logs missing | Request access logs | Open |
| R-03 | Human review records missing | Request review records | Open |
| R-04 | Implementation proof missing | Request usage evidence | Open |
| R-05 | Access review records missing | Request access review evidence | Open |

### Overall Audit Conclusion

The submitted documentation is insufficient to verify the operating effectiveness of the identified controls. All five risks remain open pending evidence review.

Residual risk scores have not been reduced because control effectiveness has not yet been established.

## Sample Evidence Testing – R-01 Gender Bias

### Scenario
The organization submitted a hypothetical bias testing report dated 10 November 2026.

### Evidence Observation
The report indicated different shortlisting rates for male and female candidates.

### Auditor Analysis
The existence of a testing report does not establish that the AI system is fair.

Further investigation is required to understand:
- Whether the difference is statistically and practically significant.
- Whether the dataset contains historical gender bias.
- Whether model features or selection criteria contribute to the disparity.
- Whether the organization has investigated the root cause.

### Auditor Recommendation
1. Request detailed bias testing results and methodology.
2. Obtain root-cause analysis.
3. Request documented corrective actions.
4. Review results after remediation.
5. Reassess control effectiveness.

### Audit Decision
**Status: Open – Further Investigation Required**

**Control Effectiveness: Not Verified**

**Residual Risk: Not Reassessed**

Note: This is a hypothetical training scenario, not actual testing of a deployed AI model.

## Sample Evidence Testing – R-02 Candidate Data Privacy

### Scenario
The organization submitted hypothetical encryption configuration and data access policy documents.

### Evidence Observation
- Encryption configuration was provided.
- Data access policy was available.
- Employee access logs were not provided.
- Periodic access review evidence was missing.

### Auditor Analysis
Encryption alone is insufficient to establish effective access governance.

The absence of access logs and periodic access reviews creates an evidence gap regarding unauthorized or excessive employee access.

### Auditor Recommendation
1. Request system access logs.
2. Verify role-based access restrictions.
3. Review employee access permissions.
4. Check periodic access review records.
5. Verify whether inappropriate access is detected and addressed.

### Audit Decision
**Status: Open – Evidence Verification Pending**

**Control Effectiveness: Not Verified**

**Residual Risk: Not Reassessed**

Note: This is a hypothetical training scenario.

## 6. Conclusion
The AI Risk Register provides a structured way to track, prioritize and monitor AI-related risks.

## Sample Evidence Testing – R-03 AI Accuracy and Human Oversight

### Scenario
The organization claims that HR personnel review AI-generated candidate rankings before final selection.

### Evidence Observation
- Human oversight policy was provided.
- AI ranking methodology was documented.
- Actual HR review records were not provided.
- AI recommendation override records were unavailable.

### Auditor Analysis
The submitted documents establish the existence of a documented process but do not demonstrate that human oversight operates effectively.

### Auditor Recommendation
1. Request actual HR review records.
2. Obtain AI recommendation override logs.
3. Verify whether HR can challenge AI-generated rankings.
4. Review procedures for handling incorrect rankings.
5. Assess whether human reviewers have sufficient authority and information.

### Audit Decision
**Status: Open – Operating Evidence Pending**

**Control Effectiveness: Not Verified**

**Residual Risk: Not Reassessed**

Note: This is a hypothetical training scenario.

## Sample Evidence Testing – R-04 Transparency and Explainability

### Scenario
The organization claims that candidates are informed when AI is used in recruitment decisions.

### Evidence Observation
- AI transparency policy was provided.
- Candidate notification template was available.
- Actual notification delivery records were missing.
- Documented explanations of AI-generated recommendations were unavailable.

### Auditor Analysis
The existence of a transparency policy and notification template does not demonstrate that candidates receive meaningful information about AI-assisted decisions.

### Auditor Recommendation
1. Request actual candidate notification records.
2. Verify disclosure of AI involvement in recruitment.
3. Review whether candidates receive understandable explanations.
4. Check whether a process exists to raise concerns or request human review.
5. Verify implementation through sample records.

### Audit Decision
**Status: Open – Implementation Evidence Pending**

**Control Effectiveness: Not Verified**

**Residual Risk: Not Reassessed**

Note: This is a hypothetical training scenario.
