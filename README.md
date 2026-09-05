# Phishing Detection & Email Investigation Lab

## Overview
A defensive blue-team lab demonstrating a repeatable process for analyzing suspicious emails, extracting indicators, evaluating authentication results, and documenting a final analyst verdict.

## Skills Demonstrated
- Email header analysis
- Sender/domain investigation
- URL and IOC extraction
- SPF, DKIM, and DMARC interpretation
- Attachment/hash triage
- Threat-intelligence enrichment
- Phishing triage and incident reporting

## Investigation Workflow
```text
Suspicious Email
      ↓
Preserve / Review Headers
      ↓
Sender + Authentication Analysis
      ↓
URL / Domain / Attachment Triage
      ↓
IOC Enrichment
      ↓
Risk Assessment
      ↓
Verdict + Recommended Response
```

## Analyst Checklist
- Review From, Reply-To, Return-Path, and Received headers.
- Check SPF/DKIM/DMARC results where available.
- Examine display-name/domain inconsistencies.
- Extract URLs/domains without unnecessarily visiting suspicious links.
- Hash attachments and use safe analysis workflows.
- Evaluate urgency, credential requests, payment requests, and social-engineering indicators.
- Record evidence supporting the final verdict.

## Evidence To Add
Use sanitized training emails or emails you are authorized to analyze. Remove personal information and sensitive message content before publishing.

## Resume-Ready Summary
**Phishing Investigation Lab** — Conducted structured phishing-email triage using header analysis, SPF/DKIM/DMARC review, IOC extraction, URL/domain analysis, safe attachment triage, and threat-intelligence enrichment to produce documented analyst verdicts and response recommendations.

## Status
Investigation framework complete; sanitized case studies will be added later.
