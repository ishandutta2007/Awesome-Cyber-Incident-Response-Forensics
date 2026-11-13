# Awesome-Cyber-Incident-Response-Forensics

## Top Cyber Incident Response & Forensics Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on DFIR Retainers, Managed Detection & Response (MDR) & Forensic Investigation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cyber Incident Response & Forensics**. These tools help organizations prepare for, respond to, and recover from security breaches—covering pre-negotiated IR retainers with guaranteed SLAs, managed detection and response (MDR) services, and open-source forensic toolkits for evidence collection and analysis.

**Examples** include Mandiant Incident Response, CrowdStrike Falcon Complete, Palo Alto Unit 42, SentinelOne Vigilance, Arctic Wolf, Cybereason, Sophos Rapid Response, Kroll, Rapid7, and open-source alternatives like SentinelSOC and Velociraptor (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted DFIR, open-source forensic collection, and community-driven incident response tooling—ideal for organizations seeking transparent, vendor-neutral investigation capabilities without retainer commitments. Note that open-source DFIR tooling excels at evidence collection and triage, but does not replace the human expertise and legal privilege that commercial IR retainers provide.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Mandiant Incident Response](https://www.mandiant.com/)** | Industry-leading DFIR retainer with **platform-agnostic** expertise (no EDR lock-in). Offers **no-cost retainer** (time-and-materials pricing upon incident) or **prepaid hours** at discounted rates, with flexibility to repurpose unused hours for proactive services like compromise assessments, red teaming, or tabletop exercises. Standard SLA: **4-hour initial contact**; enhanced **2-hour SLA** available . | No-cost retainer (T&M upon incident); prepaid hours at discounted rates; enhanced 2-hour SLA available | **No-cost retainer** available—no financial commitment until an incident is declared  |
| **[Palo Alto Unit 42](https://unit42.paloaltonetworks.com/)** | Elite DFIR team with **no-cost retainer for qualified AWS Security Incident Response customers**: 250 hours of initial IR services at no cost, **2-hour response SLA**, and 24/7/365 access. Platform-agnostic investigation across endpoints, networks, and multi-cloud environments . | **No-cost retainer** (250 hours for qualified AWS customers); preferred pricing for AWS customers on paid retainers | **250 free IR hours** + 2-hour SLA for qualified AWS Security Incident Response customers  |
| **[CrowdStrike Falcon Complete](https://www.crowdstrike.com/)** | Fully managed MDR service with 24/7 expert monitoring, threat hunting, and remediation. Deeply integrated with Falcon platform. Positioned as **endpoint-centric MDR** rather than platform-agnostic DFIR retainer—best for organizations standardized on CrowdStrike EDR . | ~**$125 per endpoint/year** (SelectHub estimate)  | No free tier; trial via sales  |
| **[SentinelOne Vigilance](https://www.sentinelone.com/)** | Managed detection and response service extending SentinelOne's autonomous EDR. 24/7 SOC monitoring and response. | ~**$27.99 per endpoint/year** (Insight listing)  | No free tier; trial via sales  |
| **[Arctic Wolf](https://arcticwolf.com/)** | Insurance-approved IR team with **JumpStart Retainer** at **$6,000/year**—significantly lower entry point than typical IR retainers. Includes prioritized response time, IR planning, incident runbooks, and **$325/hour discounted IR rate**. | **$6,000/year** (JumpStart Retainer); $325/hour IR rate | No free tier; retainer purchase required for IR services  |
| **[Cybereason](https://www.cybereason.com/)** | DFIR retainer recognized in Gartner Market Guide for four consecutive years. **Resilience Retainer** with flexible contracting, dollar-based model for transparency, discounts toward 50+ consulting services, and dedicated resilience expert. 40+ insurance carrier partnerships . | Quote-only (dollar-based retainer model) | No free tier; demo via sales  |
| **[Sophos Rapid Response](https://www.sophos.com/)** | Incident response service with **fixed 45-day pricing** based on total user and server count. No additional costs beyond the quoted price. | Quote-only (fixed 45-day engagement based on user/server count)  | No free tier; engagement-based pricing  |
| **[Kroll Cyber Risk](https://www.kroll.com/)** | Large global IR provider with full incident lifecycle coverage including DFIR, breach notification, litigation support, and regulatory compliance. Strategic CrowdStrike partnership for rapid response . | Quote-only (enterprise retainer or engagement-based) | No free tier; demo via sales  |
| **[Rapid7 Incident Command](https://www.rapid7.com/)** | Tiered IR retainer packages (Essential, Advanced, Ultimate) with asset-based pricing. Includes 90-day or 13-month subscription options with Quickstart included in Year 1 . | Quote-only (asset-based tiered packages) | No free tier; trial via sales  |
| **[Secureworks Taegis](https://www.secureworks.com/)** | MDR and IR services with Taegis platform. Vulnerability management licensing available per asset. | ~**$37.88 per asset** (VDR license, 1001–2500 volume tier)  | No free tier; demo via sales  |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[SentinelSOC](https://github.com/heysayanallgood/SentinelSOC)** | [![Stars](https://img.shields.io/github/stars/heysayanallgood/SentinelSOC?style=social&color=white)](https://github.com/heysayanallgood/SentinelSOC/stargazers) | **Modular Blue Team and SOC toolkit for Linux and Termux.** Combines threat intelligence, network analysis, log monitoring, digital forensics, incident response, and MITRE ATT&CK correlation into one portable command center. **Dedicated DFIR workflow**: live incident triage, process/network inventory, persistence review, IOC sweep, case creation, evidence collection (file and case), response simulation, and multi-format reporting (HTML/PDF/JSON). Includes SHA-256 hashing and file-type-aware analysis . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Velociraptor](https://github.com/Velocidex/velociraptor)** | [![Stars](https://img.shields.io/github/stars/Velocidex/velociraptor?style=social&color=white)](https://github.com/Velocidex/velociraptor/stargazers) | **The leading open-source endpoint visibility and DFIR platform.** Agent-based collection with VQL (Velociraptor Query Language) for real-time forensic analysis across Windows, macOS, and Linux fleets. Widely used by DFIR teams for incident triage, threat hunting, and evidence preservation at scale. |
| **[TheHive](https://github.com/TheHive-Project/TheHive)** | [![Stars](https://img.shields.io/github/stars/TheHive-Project/TheHive?style=social&color=white)](https://github.com/TheHive-Project/TheHive/stargazers) | Scalable security incident response platform with case management, task tracking, and MISP integration. Self-hosted SOC case management for coordinating IR investigations across teams. |
| **[Volatility](https://github.com/volatilityfoundation/volatility)** | [![Stars](https://img.shields.io/github/stars/volatilityfoundation/volatility?style=social&color=white)](https://github.com/volatilityfoundation/volatility/stargazers) | The standard open-source memory forensics framework. Extracts digital artifacts from volatile memory (RAM) samples—processes, network connections, injected code, and malware traces. Essential for DFIR investigations requiring memory analysis. |

**Frameworks for building custom systems**: The open-source DFIR path is **collection + case management + analysis**. Use **Velociraptor** for endpoint visibility and evidence collection across fleets, **TheHive** for case management and coordination, **Volatility** for memory forensics, and **SentinelSOC** for lightweight Linux/Termux triage—creating a functional investigation capability without retainer commitments. However, **commercial IR retainers provide legal privilege, guaranteed SLAs, and human expertise** that open-source tooling cannot replace .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Incident response and forensic investigations involve legally sensitive evidence and privileged communications; work with legal counsel to ensure evidence handling, chain of custody, and privilege protections are maintained.
- **Open-source DFIR tooling does not replace commercial IR retainers.** Retainers provide guaranteed SLAs (2–4 hours), pre-negotiated terms, legal privilege, and human expertise during high-stakes breaches. Open-source tools (Velociraptor, TheHive, Volatility) excel at evidence collection and analysis but require internal expertise to operate under pressure. **Pricing models vary dramatically**: Arctic Wolf offers a **$6,000/year** entry retainer , Unit 42 provides **250 free hours** for qualified AWS customers , and Mandiant offers a **no-cost retainer** with T&M billing upon incident . CrowdStrike Falcon Complete is **~$125/endpoint/year** for managed MDR, not a DFIR retainer . Always clarify whether a service is MDR (ongoing monitoring) or DFIR (incident-specific investigation) before committing.

---

**Made for SOC analysts, incident responders, forensic investigators, and organizations building cyber resilience.**  
Let's make incident response and forensics more open, effective, and accessible.
