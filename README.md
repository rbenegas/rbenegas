### Hi there, I'm Ruben Benegas
I am a Product and Cloud Security Architect with 20 years of experience leading cybersecurity architecture at organizations including Medtronic and Wells Fargo. 

**Core Competencies:**
*   AppSec Architecture & Continuous GRC Automation
*   Quantitative System Architecture
*   Threat Modeling (STRIDE-A) & SAST/SCA Integration (Checkmarx)

**Certifications:**
CISSP | CCSP | CCSK | AWS Cloud Practitioner | GIAC
### Architecture & Security Workflow

```mermaid
graph LR
    Code[Source Code & PRs] --> SAST[Checkmarx SAST / SCA]
    SAST --> Triage[Local LLM / Copilot Remediation]
    Triage --> Deploy[RHEL / Cloud Workloads]
