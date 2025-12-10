# phishing-email-analysis
this project was created as part of my cybersecurity internship to demonstrate the process of detecting and reporting phishing emails
 Phishing Email Analysis Report
Intern Name: m.lalitha priya
Internship Title: Cybersecurity Internship
Objective: Identify phishing characteristics in a suspicious email sample.

Objective
To identify common phishing indicators from a suspicious email sample using open-source tools and manual analysis.

Tools Used
Email client (Gmail) or saved email file (.eml/.txt)
MxToolbox Email Header Analyzer
https://lookup.icann.org/en
https://www.redirect-checker.org/
Web browser (for checking URLs and verifying domains)
Sample Phishing Email
Subject: URGENT: Your Account Has Been Suspended – Verify Now!
Claimed Sender: PayPal Support (support@paypaI.com)

Description:
The email claimed the recipient’s PayPal account would be suspended unless they verified their account within 24 hours.

🕵️‍♂️ Analysis Steps
1. Sender Email Address
Displayed: support@paypaI.com
Actual Domain: paypaI.com (uses uppercase “I” instead of lowercase “l”)
✅ Indicator: Spoofed email domain.
2. Email Header Analysis
SPF/DKIM checks: Failed
Return-Path: info@secure-update-check.com
Origin IP: Unrelated to PayPal mail servers
✅ Indicator: Header inconsistencies show the message wasn’t from PayPal.
3. Suspicious Links or Attachments
“Verify Account” button linked to
http://paypal-verification-securelogin.com
Attached file: Account_Verification_Form.zip
✅ Indicator: Malicious link and attachment detected.
4. Urgent or Threatening Language
“Your account will be permanently suspended within 24 hours if you don’t verify now!”

✅ Indicator: Urgency and fear tactics to force user action.

5. Mismatched URLs
Visible link: www.paypal.com
Hover link: paypal-verification-securelogin.com
✅ Indicator: Mismatched URL redirection.
6. Spelling and Grammar Errors
“We regreat to infrom you about your acccount suspenion.”
✅ Indicator: Poor grammar and spelling errors.

Summary of Phishing Indicators
Indicator	Description
Spoofed Sender	Fake “PayPal” address using similar characters
Header Failures	SPF/DKIM mismatch, fake return path
Fake Link	Directs to non-official domain
Urgent Tone	Threat of suspension
Suspicious Attachment	ZIP file with fake verification form
Grammar Errors	Multiple typos
Mismatched URLs	Link text and destination differ
Conclusion
The analyzed email clearly demonstrates multiple phishing traits including spoofed domains, header mismatches, urgency-based language, and fake URLs.
Recommendation: Do not click any links or download attachments. Report the email as phishing.Uploading Screenshot 2025-10-21 181912.png… Screenshot 2025-10-21 183311 Screenshot 2025-10-21 183328 Screenshot 2025-10-21 183341 Screenshot 2025-10-21 183353 Screenshot 2025-10-21 183406 Screenshot 2025-10-21 183428 phishing-email-analysis.zip
