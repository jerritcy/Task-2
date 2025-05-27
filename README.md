# Email Phishing and Header Analysis

## Objective
To identify phishing characteristics in suspicious emails and analyze email headers to detect spoofing, failed authentication, and malicious intent.

## Key Indicators of Phishing
- Spoofed sender addresses (e.g., domains using subtle typos)
- Suspicious links redirecting to unrelated domains
- Urgent or threatening language to provoke quick action
- Attachments with risky file types (e.g., `.docm`)
- Poor grammar or generic greetings

## Header Analysis Findings
- SPF: fail or softfail (sender IP not authorized)
- DKIM: fail or none (missing or invalid digital signature)
- DMARC: fail (domain policy not aligned with sender)
- IP origins not matching official servers

## Tools Used
- MXToolbox Email Header Analyzer
- Google Admin Toolbox Message Header Analyzer
- IPInfo.io for IP verification

## Conclusion
Phishing emails commonly use spoofed domains, deceptive content, and fail basic authentication checks. Header analysis is a critical skill in verifying email legitimacy and detecting fraud.

