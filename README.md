# Phishing Email Analysis Report – Task 2

## Sample Email Details
**Subject:** Urgent: Your Account Password Needs to Be Updated Immediately  
**From:** security@micr0soft-support.com  
**Body Summary:** Claims suspicious account activity and urges the recipient to reset their password and confirm banking details through provided links.

---

## Phishing Indicators Found

1. **Spoofed Sender Domain**  
   - The email is from `micr0soft-support.com` where the letter 'o' is replaced with the number '0'.
   - Legitimate Microsoft communications use domains ending with `microsoft.com`.

2. **Urgency in Language**  
   - Uses urgent and pressuring terms like *"Urgent"*, *"immediately"*, and *"prompt attention"* to force quick action.

3. **Suspicious Links**  
   - The links “Reset Password Now” and “Verify Banking Details” are displayed as text without revealing actual URLs.
   - Likely redirect to phishing or malicious websites.

4. **Request for Sensitive Data**  
   - Asks for both **account password** and **banking information** — legitimate companies never request such details via email.

5. **Generic Greeting**  
   - Addressed as “Dear User” instead of using the recipient’s actual name.
   - Indicates bulk phishing rather than targeted communication.

6. **No Account Reference**  
   - No mention of account number, username, or specific service information.

7. **Likely Technical Failures (if header analyzed)**  
   - Email headers would likely show SPF, DKIM, and DMARC failures.
   - Possible mismatch between sending IP and legitimate Microsoft mail servers.

8. **Social Engineering Tactics**  
   - Combines fear of account compromise with urgency to make the victim act without verification.

---

## Conclusion
This is a **phishing email**. Multiple indicators confirm it: spoofed domain, urgent tone, suspicious links, and requests for sensitive information.  

**Recommended Actions:**
- Do not click any links or download attachments.
- Report the email to your email provider or security team.
- Delete the email after reporting.

---

## Key Concepts Learned
- Identifying spoofed domains in email addresses.
- Recognizing urgency and fear tactics in phishing.
- Understanding why sensitive data should never be requested via email.
- Basics of email header analysis.
