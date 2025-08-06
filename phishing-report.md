# Task 2: Phishing Email Analysis Report

## 🎯 Objective
Analyze a phishing email sample to identify phishing characteristics.

---

## ✉️ 1. Sender’s Email Address
- **From:** microsofth@email-lrecords.com
- **Legitimate Microsoft domain should be:** @microsoft.com
- ⛔ **Domain mismatch**

---

## 📜 2. Header Analysis
- **SPF:** FAIL
- **DKIM:** NONE
- **DMARC:** NONE
✅ These indicate spoofing.

---

## 🔗 3. Suspicious Links
- **Button Label:** View alert details
- **Actual Link:** (not visible in screenshot)
- Likely a credential harvesting site.
- ⚠️ Always hover links to check the real URL.

---

## 🚨 4. Urgent / Threatening Language
- "A high-severity alert has been triggered"
- "Phish delivered"
- **Purpose:** create panic and prompt immediate clicking.

---

## ✏️ 5. Spelling / Grammar Errors
- "microsofth@email-lrecords.com" looks like a typo.
- Inconsistent formatting.

---

## ✅ Summary of Phishing Indicators

| Indicator                     | Found   |
|------------------------------|---------|
| Suspicious Sender Domain     | ✅      |
| Failed SPF/DKIM              | ✅      |
| Urgent Language              | ✅      |
| Suspicious Links             | ⚠️      |
| Brand Spoofing               | ✅      |

---

## 📸 6. Evidence Screenshot
![Phishing Email Screenshot](screenshots/phishing-email.png)

---

## 📝 Conclusion
This is a **high-confidence phishing attempt** designed to steal Office 365 credentials.
