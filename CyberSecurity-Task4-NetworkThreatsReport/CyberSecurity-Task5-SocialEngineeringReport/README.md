# Social Engineering Attacks

## Introduction
Social engineering is the art of manipulating people into giving up confidential information. It is considered one of the most effective attack vectors because it bypasses technical security controls by exploiting human psychology, such as trust, fear, or curiosity.

## 1. Phishing
*   **How it works:** Attackers send fraudulent messages (emails, texts, or voice calls) designed to trick the recipient into revealing sensitive data or clicking malicious links. Types include spear phishing (targeted), whaling (targeting executives), vishing (voice), and smishing (SMS).
*   **Real-world Case Study:** The 2020 Twitter hack. Attackers called Twitter employees, posing as IT support, and tricked them into providing credentials that allowed access to high-profile accounts.
*   **Prevention Recommendations:** 
    1. Implement multi-factor authentication (MFA) everywhere.
    2. Conduct regular employee phishing simulations and training.
    3. Verify sender email addresses carefully.
    4. Use email filtering/spam blockers.

## 2. Pretexting
*   **How it works:** The attacker invents a scenario (a pretext) to engage the victim and steal information. They might pose as an auditor, a police officer, or a coworker who needs urgent help.
*   **Real-world Case Study:** The 2011 RSA SecurID breach. Attackers sent a phishing email with an Excel attachment to specific employees. When opened, it installed malware, but the initial engagement relied on a pretext of a legitimate recruitment process.
*   **Prevention Measures:** 
    1. Establish strict protocols for verifying identities before sharing data.
    2. Train employees to question unusual requests, even if they appear to come from authority figures.
    3. Never share passwords or sensitive info over the phone or email.

## 3. Baiting
*   **How it works:** Attackers leave physical media (like infected USB drives) in public places hoping someone will plug them in. Digital baiting involves offering free downloads (like music or movies) that actually contain malware.
*   **Real-world Case Study:** The Stuxnet worm (widely believed to have been introduced via a USB drive). In another common scenario, attackers drop USBs labeled "Payroll" or "Confidential" in a company parking lot.
*   **Prevention Measures:** 
    1. Ban unauthorized USB devices on corporate networks.
    2. Disable Autorun features on all computers.
    3. Educate employees never to plug in found devices.
    4. Only download software from official, trusted sources.

## Bonus: Quid Pro Quo
*   **How it works:** The attacker offers a service or benefit (a "favor") in exchange for information. For example, calling employees claiming to be from IT and offering to "fix" a slow computer if they provide their login credentials.
*   **Prevention:** Verify the identity of anyone offering unsolicited tech support or services.

## Comparison Table
| Attack Type | Primary Target | Psychological Lever Exploited | Best Countermeasure |
| :--- | :--- | :--- | :--- |
| Phishing | General Users | Urgency / Fear | Email Filtering & MFA |
| Pretexting | Specific Employees | Trust / Authority | Identity Verification Protocols |
| Baiting | Curious Individuals | Curiosity / Greed | USB Restrictions & Training |
| Quid Pro Quo | Helpdesk / IT | Desire for Help | Strict IT Support Protocols |

## Organisational Recommendations: 5-Point Employee Security Awareness Checklist
1. **Verify Before Trusting:** Always verify unexpected requests via a second communication channel (e.g., call the person back).
2. **Think Before Clicking:** Hover over links to check URLs before clicking. Do not open unexpected attachments.
3. **Use Strong Authentication:** Enable MFA on all accounts and use a password manager.
4. **Report Suspicious Activity:** Create a "no-blame" culture where employees can easily report mistakes or suspicious emails to IT.
5. **Secure Physical Spaces:** Do not leave laptops unlocked or plug in unknown USB drives.

## References
1. CISA - Social Engineering Guide
2. SANS Institute - Reading Room (Social Engineering)
3. Wired - "The Twitter Hack Was a Masterclass in Social Engineering"
4. Krebs on Security
