# Beyond Static Thresholds: Context-Aware Correlation for Brute-Force Detection in a SIEM

### A Reproducible Simulation Study with MITRE ATT&CK Mapping

**Author:** Anuj Kumar  
**Programme:** Master of Computer Applications (Cloud Computing & DevOps)  
**Institution:** University Institute of Computing, Chandigarh University

## 📄 Research Paper

This research studies how context-aware correlation rules can improve brute-force detection in a Security Information and Event Management (SIEM) system compared with traditional static thresholds.

**[📥 Read the Full Research Paper (PDF)](./SIEM_Brute_Force_Detection_Research_Paper_Anuj_Kumar%20%281%292.pdf)**

## Abstract

Traditional SIEM detection rules rely on fixed thresholds for failed logins, which can produce excessive false alerts or miss password-spraying and low-and-slow attacks.

This study compares static detection rules with context-aware rules using a reproducible simulation of a Windows domain. It evaluates detection recall, false alerts per day, and mean time to detect (MTTD), with mappings to MITRE ATT&CK techniques.

## Key Findings

- **97% campaign recall** using context-aware rules in the simulated environment.
- **5.0 average false alerts per day** for the context-aware configuration.
- Comparison with static, per-source and per-account threshold rules.
- Ablation study and sensitivity analysis for incomplete source baselines.
- Replay of a public password-spraying dataset.

*Note: These results are based primarily on simulation and should not be interpreted as guaranteed real-world performance.*

## Technologies and Topics

- Security Information and Event Management (SIEM)
- Cybersecurity and detection engineering
- Brute-force detection and password spraying
- Windows Security Events 4624 and 4625
- MITRE ATT&CK: T1110, T1110.001, T1110.003 and T1078
- Security Operations Center (SOC)

## Research Scope

The study explores context-aware detection using account source baselines, distinct-account correlation, and longer detection windows.

## Repository Contents

- Research paper (PDF)

## Author

**Anuj Kumar**  
MCA — Cloud Computing & DevOps  
University Institute of Computing, Chandigarh University
