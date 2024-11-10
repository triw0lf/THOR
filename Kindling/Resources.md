# 🪵 Resources for Threat Hunting

## Overview
Before submitting a hunt to HEARTH, it's valuable to gather intelligence and inspiration from various sources. This guide provides resources and methods for developing threat hunting ideas.

## Intelligence Sources

### 1. Threat Intelligence Platforms
- **MITRE ATT&CK**
  - Browse tactics and techniques
  - Study documented adversary behaviors
  - Review procedure examples
- **CISA Alerts**
  - Recent vulnerability announcements
  - Threat actor TTPs
  - Incident reports
- **Industry ISACs**
  - Sector-specific threats
  - Emerging attack patterns
  - Shared intelligence reports

### 2. Security Research
- **Academic Papers**
  - [SANS Cyber Security Research Papers](https://www.sans.edu/cyber-research/)
  - [Google Scholar](https://scholar.google.com/)
- **Security Blogs**
  - Vendor security blogs
  - Independent researchers
  - Threat Research teams
- **Conference Materials**
  - BlackHat presentations
  - DEF CON talks
  - BSides talks
  - Other conference presentations (use Google or check YouTube)

### 3. Community Resources
- **Twitter/X Security Community**
  - Follow threat researchers
  - Track #infosec and #threathunting tags
  - Monitor vendor security accounts
- **GitHub Repositories**
  - Detection rules repositories
  - Threat hunting tools
  - Attack simulation projects
- **Security Forums**
  - Reddit ([r/netsec](https://www.reddit.com/r/netsec/), r/blueteam](https://www.reddit.com/r/blueteam/), [r/purpleteam](https://www.reddit.com/r/purpleteam/), [r/redteam](https://www.reddit.com/r/redteam/))
  - InfoSec Slack / Discord communities
 
## Resource Directory

### Threat Research Blogs
- [Unit42 - Palo Alto Networks](https://unit42.paloaltonetworks.com/)
- [The DFIR Report](https://thedfirreport.com/)
- [Google Cloud Security Blog](https://cloud.google.com/blog/topics/threat-intelligence)
- [Talos Intelligence](https://blog.talosintelligence.com/)
- [Splunk Threat Research Team](https://www.splunk.com/en_us/blog/author/secmrkt-research.html)
- [Kaspersky SecureList](https://securelist.com/)
- [ThreatPost](https://threatpost.com/)
- [Malwarebytes Blog](https://www.malwarebytes.com/blog)
- [Red Canary Threat Detection Report](https://redcanary.com/threat-detection-report/)
- [CERT-EU Blog](https://cert.europa.eu/blog)
- [WeLiveSecurity by ESET](https://www.welivesecurity.com/en/)
- [ThreatConnect Blog](https://threatconnect.com/blog/)
- [CrowdStrike Blog](https://www.crowdstrike.com/en-us/blog/)
- [McAfee Labs Blog](https://www.mcafee.com/blogs/other-blogs/mcafee-labs)
- [Recorded Future Blog](https://www.recordedfuture.com/blog)
- [CyberArk Research Blog](https://www.cyberark.com/resources/threat-research-blog)

### Frameworks and Playbooks
- [MITRE ATT&CK Framework](https://attack.mitre.org/)
  - Comprehensive adversary tactics and techniques
  - Real-world examples and procedures
  - Mapping to detection strategies

- [Threat Hunter Playbook](https://threathunterplaybook.com/)
  - Open-source hunting methodologies
  - Practical analytics
  - Implementation guides

- [ThreatHuntingProject](https://github.com/ThreatHuntingProject/ThreatHunting)
  - Use cases
  - Technical procedures
  - Sample queries

### Threat Intelligence Resources
- [CISA Advisories](https://www.cisa.gov/news-events/cybersecurity-advisories)
- [AlienVault OTX](https://otx.alienvault.com/)
- [IBM X-Force Exchange](https://exchange.xforce.ibmcloud.com/)
- [SANS Internet Storm Center](https://isc.sans.edu/)

### Documentation Resources
- [Windows Event Documentation](https://docs.microsoft.com/en-us/windows/security/threat-protection/auditing/audit-logon-events)
- [AWS CloudTrail Documentation](https://aws.amazon.com/cloudtrail/)
- [Azure Security Documentation](https://docs.microsoft.com/en-us/azure/security/)
- [Google Cloud Documentation](https://cloud.google.com/docs/)

## Idea Development Methods

### 1. Current Events Analysis
- Monitor news for security incidents
- Study published incident reports
- Review disclosed vulnerabilities
- Track threat actor campaigns

### 2. Internal Intelligence
- Review past security incidents
- Analyze failed attack attempts
- Study successful compromises
- Examine detection gaps

### 3. Data-Driven Approach
- Audit available data sources
- Identify unexplored data sets
- Review logging coverage
- Map detection capabilities

## Idea Refinement Process

### 1. Initial Capture
- Document basic concept
- Note relevant data sources
- List potential techniques
- Record references

### 2. Research Phase
- Gather supporting evidence
- Find similar approaches
- Document limitations
- Identify requirements

### 3. Validation Questions
- Is the idea testable?
- Are data sources available?
- What tools are needed?
- Is it practically implementable?

## Converting to HEARTH Submission

### 1. Determine Hunt Type
- **Flames** (Hypothesis-Driven)
  - Clear adversary behavior
  - Specific activity patterns
  - Testable hypothesis
- **Embers** (Baseline)
  - Normal behavior patterns
  - Environmental baselines
  - Deviation detection
- **Alchemy** (Model-Assisted)
  - Algorithm requirements
  - Data science approach
  - Pattern recognition

### 2. Documentation Requirements
- Complete hypothesis statement
- Supporting references
- Implementation details
- Required resources

### 3. Submission Preparation
- Use official template
- Include all references
- Document assumptions
- Note limitations

## Tips for Success

1. **Start Small**
   - Focus on specific behaviors
   - Limit initial scope
   - Build on basics

2. **Validate Feasibility**
   - Check data availability
   - Verify tool access
   - Test basic concepts

3. **Document Everything**
   - Record sources
   - Note decisions
   - Track changes
   - Save references

4. **Seek Feedback**
   - Share early drafts
   - Request peer review
   - Incorporate suggestions
   - Iterate based on input

Remember: The best hunt ideas often start as simple observations or questions. Use this guide to help develop your initial concepts into full-fledged HEARTH submissions.
