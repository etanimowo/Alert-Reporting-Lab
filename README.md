# Alert-Reporting-Lab
## Alert Reporting – TryHackMe Lab
### Overview
This project documents my hands-on experience completing the SOC L1 Alert Reporting lab on TryHackMe.
The lab focuses on one of the most critical responsibilities of a Tier 1 SOC Analyst: accurately documenting, escalating, and communicating security alerts to ensure effective incident response and smooth handover to senior analysts.

Through this lab, I practiced writing structured alert reports, determining when escalation is required, and handling real-world SOC communication scenarios using industry-aligned workflows.

### Objectives
The primary objectives of this lab were to:
- Understand the importance of formal alert reporting in a SOC environment
- Learn how to document investigations clearly and consistently
- Apply the Five Ws (Who, What, When, Where, Why) framework for alert reports
- Identify when and how to escalate True Positive alerts to L2 analysts
- Practice SOC communication procedures during critical and unexpected scenarios

### Lab Scope & Scenarios
During this lab, I worked through multiple SOC scenarios involving:
- Writing detailed alert reports before alert closure or escalation
- Escalating high-risk or unclear alerts to L2 analysts
- Communicating with internal teams such as IT and HR when validation was required
- Handling operational challenges such as unavailable L2 analysts or SIEM issues
- Managing alert overload while prioritizing critical incidents

### Tools & Technologies Used
- TryHackMe SOC Labs
- SIEM Alert Interface (simulated)
- Incident Reporting Templates
- SOC Escalation Workflows
- Corporate Communication Channels (simulated)

### Skills Developed
- SOC Alert Triage & Documentation
- Incident Reporting Using the Five Ws Framework
- Alert Escalation Decision-Making
- SOC Communication & Crisis Handling
- Analytical Thinking & Attention to Detail
- Professional Security Writing

### Alert Reporting Methodology
Each alert report was structured to provide clarity and actionable context for L2 analysts:

### Five Ws Reporting Framework
-	Who: User, account, or process involved
- What: Exact suspicious action or sequence of events
- When: Timestamp of activity start and end
- Where: Affected host, IP address, or external resource
- Why: Analyst reasoning behind the final verdict

This approach ensures reports are understandable, reproducible, and useful for deeper investigation or DFIR activities.

### Escalation Criteria
Alerts were escalated to L2 analysts when:
- Indicators suggested a major cyberattack
- Remediation actions (host isolation, password reset, malware removal) were required
- External communication (management, customers, or legal entities) was necessary
- The alert was unclear or beyond L1 confidence

Escalation involved alert reassignment and direct communication to reduce response time.

### SOC Communication Practices
The lab emphasized effective communication during high-pressure situations, including:
- Escalating critical alerts when L2 analysts are unavailable
- Validating compromised accounts using out-of-band communication
- Managing alert surges while maintaining incident priority
- Reporting misclassified alerts immediately to minimize risk
- Documenting SIEM or logging issues rather than ignoring alerts

### Lessons Learned
- Alert reporting is not optional — it preserves context and accelerates response
- Clear documentation reduces duplication of effort for senior analysts
- Escalation is a strength, not a weakness, when uncertainty exists
- Effective SOC communication can prevent operational and security failures
- Even small misclassifications can have long-term security impacts

### Conclusion
This lab reinforced three foundational SOC Tier 1 skills: alert reporting, escalation, and communication.
Mastering these skills ensures security incidents are handled efficiently, escalated appropriately, and clearly communicated across teams.

This project demonstrates my readiness to operate in a real-world SOC environment as an entry-level SOC Analyst, following professional standards and best practices.

### Reference
•	TryHackMe – SOC Level 1: Alert Reporting

### Sample Alert Reports
This repository includes real-world styled SOC alert reports demonstrating both escalation and closure decisions:

- True Positive Alert Report:
Documents an unauthorized privilege escalation, including investigation details, reasoning, and escalation to L2.

- False Positive Alert Report:
Demonstrates proper validation of a legitimate login event and correct closure without escalation.

These reports follow the Five Ws framework and align with industry SOC reporting standards.
