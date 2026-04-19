# Australian Cyber Security Framework Comparison
## Author: Ritesh Ade
## Date: April 2026

## Overview
This document compares three key cyber security frameworks
relevant to Australian organisations, with focus on Victorian
public sector applicability.

## Framework Summary
| Framework | Mandatory | Scope | Regulator |
|-----------|-----------|-------|-----------|
| VPDSF | Yes - Victorian public sector | Data security and privacy | OVIC |
| Essential Eight | Recommended - all Australian orgs | Cyber attack mitigation | ASD/ACSC |
| ISO 27001 | Voluntary - any organisation | Information security management | ISO/IEC |

## VPDSF Key Requirements
- Protective Data Security Plan (PDSP) required
- Annual security attestation to OVIC
- Data classification: Public, Sensitive, Protected
- 4 security outcomes: Governance, Information Asset
  Management, Risk Management, Protective Controls
- Designated Data Security Contact required

## Essential Eight Strategies
1. Application Control
2. Patch Applications
3. Configure Microsoft Office Macro Settings
4. User Application Hardening
5. Restrict Administrative Privileges
6. Patch Operating Systems
7. Multi-Factor Authentication
8. Regular Backups

## Essential Eight Maturity Levels
- Level 0: Not implemented
- Level 1: Partly aligned - mitigates commodity threats
- Level 2: Mostly aligned - mitigates targeted threats
- Level 3: Fully aligned - mitigates advanced threats

## Framework Mapping
| VPDSF Outcome | Essential Eight Control | ISO 27001 Clause |
|---------------|------------------------|------------------|
| Governance | Restrict Admin Privileges | A.6 Organisation of IS |
| Information Asset Management | Application Control | A.8 Asset Management |
| Risk Management | Patch Applications + Patch OS | A.12 Operations Security |
| Protective Controls | MFA + App Control + Backups | A.9 Access Control |

## Data Classification Comparison
| VPDSF | Australian Government | ISO 27001 |
|-------|----------------------|-----------|
| Public | Official | Organisation defined |
| Sensitive | Official Sensitive | Organisa