# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

FortiGuard Labs’ network telemetry has observed active exploitation of known vulnerabilities in Drupal Core and the WP-Automatic WordPress plugin for initial access. Following compromise, attackers deploy multiple web shells and utilities to enable lateral movement, privilege escalation, and the installation of remote access trojans (RATs). 

 The **Outbreak Response - ShadowSilk Data Exfiltration Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.0.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/shadowsilk-data-exfiltration) contains information about the outbreak alert **Outbreak Response - ShadowSilk Data Exfiltration Attack**. 

## Background: 

ShadowSilk is an advanced persistent threat (APT) group active since at least 2023. The group has targeted nearly three dozen organizations across Central Asia and the Asia-Pacific region, with a particular focus on government entities. 

Investigations by Group-IB confirmed numerous victims within the Central Asian government sector. ShadowSilk operations are characterized by the use of publicly available exploits, penetration-testing frameworks, and infrastructure sourced from the dark web to facilitate large-scale data exfiltration campaigns. 

## Announced: 

FortiGuard customers are protected by multiple layers of defense against these exploits. However, immediate patching of affected system is strongly advised, if not done already. The FortiGuard Incident Response is available to assist with investigation and remediation in cases of suspected compromise. 

## Latest Developments: 

August 28, 2025: FortiGuard Labs published a Threat Signal Report.
https://www.fortiguard.com/threat-signal-report/6190/shadowsilk-data-exfiltration-attack

August 27, 2025: In June 2025 Group-IB observed renewed activity and new infrastructure, identified additional government victims in Central Asia, and collected new IOCs.
https://www.group-ib.com/blog/shadowsilk/ 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|