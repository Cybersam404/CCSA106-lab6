# CCSA106 Lab 6: Security Operations Monitoring

Lab report and demonstration for CCSA106 (Check Point CCSA, ICDFA).

 - **Student:** Jegede Samuel Aduragbemi
- **Report:** [CCSA106_Lab06_C11_26_CCSA_17113.pdf](CCSA106_Lab06_C11_26_CCSA_17113.pdf)
- **Demo video:** https://drive.google.com/file/d/1_P3DiDJ9p5xyvemr5ZxiK-aIv0ufVkRU/view?usp=sharing

## What the report covers

**Lab 6A: Elevate Traffic View**
- A1: Log Server review (A-SMS logging settings, storage thresholds, retention) with a 14-day indexed plus 7-day raw-log capacity calculation and recommendation.
- A2: Rule tracking and the Allowed Traffic query. I identified rule 2 (Security Gateway Access rule, Track = Log) in the Alpha-Standard policy.
- A3: Custom Accept and Drop queries for source 10.1.1.201, run in SmartView Web.
- A4: Interpretation of one firewall event, with a Top observation and its limits.

**Lab 6B: Monitor System States**
- B1: Gateway status and system counters in SmartView Monitor and Device Status.
- B2: A security (firewall) log compared with an audit log.

## Environment limitation

Only the management server (A-SMS) was running. The gateways and the log server were down, so no fresh traffic could be generated. I used historical firewall logs dated 12 April 2026, found in SmartView Web. SmartConsole's SmartLog stopped working during the lab, so the queries were run in SmartView Web. Each limit is documented where it applies in the report.

## Evidence

Screenshots E1 to E6 are embedded in the PDF. Credentials and personal data are redacted. No configuration was changed: every object was closed with Cancel.

## AI assistance

I used Claude (Anthropic) to explain the monitoring concepts, plan the steps and review the wording. I carried out all lab steps and took all screenshots myself.
