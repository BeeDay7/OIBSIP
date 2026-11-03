# Common Network Security Threats

## Introduction
Network security threats are malicious activities designed to disrupt, damage, or gain unauthorized access to a computer network. As organizations become more interconnected, understanding these threats is crucial for protecting sensitive data and maintaining operational integrity.

## 1. DoS/DDoS Attacks
*   **How it works:** A Denial-of-Service (DoS) attack floods a system with traffic to exhaust its resources, making it unavailable to legitimate users. A Distributed Denial-of-Service (DDoS) uses multiple compromised systems (a botnet) to launch the attack.
*   **Real-world Example:** The 2016 Dyn Cyberattack, which used the Mirai botnet to take down major websites like Twitter, Netflix, and Reddit for hours.
*   **Impact:** Severe business disruption, loss of revenue, and reputational damage.
*   **Mitigation Strategies:** 
    1. Implement rate limiting on network devices.
    2. Use DDoS mitigation services (like Cloudflare).
    3. Maintain a robust incident response plan.

## 2. Man-in-the-Middle (MITM) Attacks
*   **How it works:** An attacker secretly intercepts and relays communication between two parties who believe they are directly communicating with each other.
*   **Real-world Example:** The 2017 Equifax breach involved attackers intercepting unencrypted data over a web portal.
*   **Impact:** Theft of sensitive data, including login credentials, financial details, and personal information.
*   **Mitigation Strategies:** 
    1. Enforce strong encryption (TLS/SSL) for all network traffic.
    2. Use Multi-Factor Authentication (MFA).
    3. Implement strict Wi-Fi security protocols (WPA3).

## 3. IP Spoofing
*   **How it works:** An attacker creates IP packets with a forged source IP address to disguise their identity or impersonate another system.
*   **Real-world Example:** The Mirai botnet attacks frequently utilized IP spoofing to overwhelm targets and hide the true sources of the attack.
*   **Impact:** Bypassing IP-based authentication, launching DDoS attacks, and hiding malicious activity.
*   **Mitigation Strategies:** 
    1. Implement ingress and egress filtering on routers.
    2. Use packet filtering to block packets with suspicious source addresses.
    3. Employ cryptographic network protocols (IPsec).

## 4. DNS Poisoning/Spoofing
*   **How it works:** Attackers corrupt the Domain Name System (DNS) records to redirect users from a legitimate website to a malicious one.
*   **Real-world Example:** The 2019 DNSpionage campaign, where attackers hijacked DNS records to redirect traffic to malicious sites.
*   **Impact:** Users are tricked into providing credentials on fake sites, leading to data theft.
*   **Mitigation Strategies:** 
    1. Use DNSSEC (Domain Name System Security Extensions).
    2. Regularly audit DNS records.
    3. Use secure DNS resolvers.

## Comparison Table
| Threat | Attack Vector | Who is at Risk | Difficulty | Mitigation Ease |
| :--- | :--- | :--- | :--- | :--- |
| DoS/DDoS | Network Flood | Web Servers, ISPs | Low | Medium |
| MITM | Network Interception | Public Wi-Fi Users | Medium | Easy |
| IP Spoofing | Packet Forgery | Routers, Firewalls | Medium | Medium |
| DNS Poisoning | DNS Record Alteration | General Internet Users | High | Hard |

## Conclusion: 3 Key Takeaways for a Network Administrator
1. Defense-in-depth is essential; no single security control is foolproof.
2. Continuous monitoring and employee training are critical to detect and prevent MITM and social engineering attacks.
3. Regular patching and implementing secure protocols (like DNSSEC and TLS) protect against spoofing and poisoning.

## References
1. NIST - Computer Security Resource Center
2. CISA - Cybersecurity and Infrastructure Security Agency
3. SANS Institute - Reading Room
4. Krebs on Security (for real-world case studies)
