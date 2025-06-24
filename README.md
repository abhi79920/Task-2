# Task 2 - Phishing Email Analysis (Example 2)

## 🔍 Sample Email
This sample phishing email pretends to be from Amazon and uses a fake billing issue to lure the victim.

## 🚩 Identified Phishing Traits:
- **Fake Sender:** `admin@amaz0n-support.com` uses a zero `0` instead of the letter `o`.
- **Urgent Language:** "Order will be cancelled in 12 hours" creates panic.
- **Malicious Link:** `http://amazon-support.billing-secure-check.ru/verify` redirects to a suspicious Russian domain.
- **Suspicious Attachment:** `invoice.pdf.exe` is a disguised executable.
- **Header Analysis:** SPF failure and mismatched domains.

## 🛠 Tools Used:
- [MxToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- Manual inspection techniques (hovering links, checking headers)

## 🎯 Outcome:
Improved skills in identifying and analyzing phishing attempts, including spoofed domains and social engineering tricks.
