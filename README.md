# Cybersecurity Internship Tasks

This repository contains my work for a Cyber Security Internship.

It includes:

* Vulnerability Assessment
* Phishing Detection & Awareness
* API Security Risk Analysis
# Cyber Security Task 1 – Vulnerability Assessment

## Website Tested
http://testphp.vulnweb.com

## Scope
Read-only vulnerability assessment of a public demo website.

## Tools Used
- Nmap
- OWASP ZAP (Passive Scan)
- Browser DevTools
- Canva

## Findings
- Missing Anti-Clickjacking Header
- Absence of Anti-CSRF Tokens
- Server Version Disclosure

## Evidence
Screenshots and scan outputs are included in this repository.
# Cyber Security Task 2 – Phishing Detection & Awareness

## Objective

The goal of this task is to analyze phishing email examples and identify common phishing indicators to help users recognize and avoid phishing attacks.

## Phishing Email Examples

* Urgent: Your Account Will Be Locked
* PayPal Account Suspended
* Amazon Order Verification Required
* Office365 Password Expiring
* Bank Account Verification Required

## Phishing Indicators Identified

* Fake or suspicious sender domains
* Urgency or fear-based messages
* Suspicious links
* Generic greetings
* Requests for sensitive information

## Risk Classification

The analyzed emails were classified into:

* Phishing
* Suspicious

## Prevention Guidelines

### Do’s

* Check sender email address carefully
* Hover over links before clicking
* Enable two-factor authentication
* Report suspicious emails

### Don’ts

* Do not click unknown links
* Do not download attachments from unknown sources
* Never share passwords or OTPs

## Deliverable

A **Phishing Detection & Awareness Report** was created and uploaded to this repository as a PDF file.
# Cyber Security Task 3 – API Security Risk Analysis

## Objective

The goal of this task is to analyze public APIs and identify potential security risks such as open endpoints, excessive data exposure, and missing authentication mechanisms.

## API Tested

https://jsonplaceholder.typicode.com

## Scope

Read-only security analysis of publicly available API endpoints using safe GET requests.

## Endpoints Analyzed

* /users
* /posts
* /comments
* /albums

## Tools Used

 * Google Chrome Browser
 * JSONPlaceholder Public Test API
 * Microsoft Word

## Testing Methodology

* Reviewed API documentation for available endpoints
* Sent GET requests to the API using a browser
* Inspected API responses for sensitive data exposure
* Checked whether authentication or authorization was required
* Identified potential security risks in API responses
* Documented findings in a structured security report

## Security Risks Identified

* Open API endpoints without authentication
* Excessive data exposure in API responses
* Email addresses visible in API responses
* Lack of rate limiting for API requests

## Business Impact

* Unauthorized users may access sensitive information such as user emails and personal data.
* Public access to API endpoints may allow attackers to collect information or abuse the system.

## Recommendations

* Implement authentication mechanisms such as API keys or OAuth tokens
* Limit sensitive information returned in API responses
* Apply rate limiting to prevent abuse
* Restrict API access using proper authorization controls

## Deliverable

An **API Security Risk Analysis Report** was created in Microsoft Word and exported as a PDF.
The report and supporting screenshots were uploaded to this repository.




## Deliverable
Vulnerability Assessment Report created in Canva and exported as PDF.
