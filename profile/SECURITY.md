# Security Policy & Safe Linking at Jmpy.me

At Jmpy.me, we take the trust our users place in us seriously. Link management is not just about shortening; it's about ensuring every redirection is safe, transparent, and secure.

## 🛡️ Our 5-Layer Security Engine

Every link created on Jmpy.me undergoes a rigorous security scan at the time of creation and continuously throughout its lifecycle.

1.  **Local Blacklist (Immediate):** Instant check against our internal database of known malicious domains and hashes.
2.  **Cloaking & Evasion Detection:** Our proprietary **CloakDetector** identifies URLs that attempt to show different content to security scanners than to real users.
3.  **Google Safe Browsing Integration:** Real-time verification against Google's massive index of malware and phishing threats.
4.  **Multi-Vendor Aggregation (VirusTotal):** For new or suspicious links, we leverage aggregate data from 70+ antivirus scanners and URL/domain blacklisting services.
5.  **Offline-to-Online Protection:** QR codes generated on our platform are scanned with the same high-standard engines to prevent "Quishing" (QR Phishing).

## 🔐 Advanced Link Protection

Beyond malware scanning, we provide enterprise-level tools to keep your links private:
- **Password Protection:** Encrypt access to sensitive URLs.
- **Expiration Gating:** Set links to automatically disable after a certain date or a specific number of clicks.
- **On-Demand TLS:** All branded domains and subdomains are automatically provisioned with SSL certificates via our **Caddy** edge proxy.

## 🐛 Reporting a Vulnerability

We appreciate the efforts of security researchers. If you find a vulnerability in our platform:
1. **Scope:** Please report issues related to data leaks, authentication bypass, or security engine evasion.
2. **Contact:** Please email **security@jmpy.me** with a detailed proof of concept.
3. **Responsible Disclosure:** We ask that you give us reasonable time to investigate and fix the issue before public disclosure.

## 🦾 Team-Based Access Control
Your data isolation is our priority. Our **Team Management** engine ensures that:
- **Owner-Level Isolation:** Team members only see links and analytics designated by the team owner.
- **Permission Proximity:** Roles and groups prevent unauthorized members from editing or deleting critical assets.
- **Secure Invitations:** invitations are email-validated and require active acceptance before granting workspace access.

## 🤖 Bot & Abuse Protection
Our backend implements advanced rate-limiting and bot classification to prevent link abuse and ensure high-quality analytics for your marketing campaigns.

Built for the modern web. Optimized for trust.
