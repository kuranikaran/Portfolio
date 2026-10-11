# Public Research and Security Advisory Index

**Karan Kurani | Independent Security Research**  
**Last updated:** 11 October 2026  
**CNA status:** Applicant only. All CVE IDs below were assigned by the respective authorized CNAs - **not** by this research site.

This public index brings together original, non-embargoed research notes authored here and existing public supplier/GitHub advisories that acknowledge Karan Kurani's reporting or collaboration. The external advisories remain the authoritative technical sources. This is not a claim of CNA authority or exclusive discovery credit.

## Independently published research notes on this site

| Research note | Scope | Authoritative advisory |
| --- | --- | --- |
| [CVE-2026-32230 - Uptime Kuma private monitor information exposure](CVE-2026-32230.md) | Missing public-monitor check | [Vendor advisory](https://github.com/louislam/uptime-kuma/security/advisories/GHSA-c7hf-c5p5-5g6h) |
| [CVE-2026-44304 - Netflix Lemur LDAP filter injection](CVE-2026-44304.md) | LDAP username escaping / privilege escalation | [Vendor advisory](https://github.com/Netflix/lemur/security/advisories/GHSA-3r34-vq8m-39gh) |
| [CVE-2026-28970 - Apple SwiftNIO CRLF injection](CVE-2026-28970.md) | Outbound HTTP start-line validation | [Vendor advisory](https://github.com/apple/swift-nio/security/advisories/GHSA-cq87-8r7h-962v) |

## External advisories and public researcher acknowledgments

| CVE ID | Project / product | Publicly described issue | Primary public source |
| --- | --- | --- | --- |
| [CVE-2026-55440](https://www.cve.org/CVERecord?id=CVE-2026-55440) | Microsoft UFO | Authenticated session-squatting / availability impact | [Supplier / GitHub advisory](https://github.com/microsoft/UFO/security/advisories/GHSA-hxjv-fmjf-wmjf) |
| [CVE-2026-44304](https://www.cve.org/CVERecord?id=CVE-2026-44304) | Netflix Lemur | LDAP filter injection / privilege escalation | [Supplier / GitHub advisory](https://github.com/Netflix/lemur/security/advisories/GHSA-3r34-vq8m-39gh) |
| [CVE-2026-44305](https://www.cve.org/CVERecord?id=CVE-2026-44305) | Netflix Lemur | LDAP TLS certificate validation disabled | [Supplier / GitHub advisory](https://github.com/Netflix/lemur/security/advisories/GHSA-vr7c-r5gj-j3w5) |
| [CVE-2026-28970](https://www.cve.org/CVERecord?id=CVE-2026-28970) | Apple SwiftNIO | CRLF injection in outbound HTTP start-line fields | [Supplier / GitHub advisory](https://github.com/apple/swift-nio/security/advisories/GHSA-cq87-8r7h-962v) |
| [CVE-2026-28898](https://www.cve.org/CVERecord?id=CVE-2026-28898) | Apple SwiftNIO HTTP/2 | HTTP/2 to HTTP/1 request smuggling | [Supplier / GitHub advisory](https://github.com/apple/swift-nio-http2/security/advisories/GHSA-4px2-pw77-vc85) |
| [CVE-2026-35627](https://www.cve.org/CVERecord?id=CVE-2026-35627) | OpenClaw | Unauthenticated pre-policy Nostr processing | [Supplier / GitHub advisory](https://github.com/openclaw/openclaw/security/advisories/GHSA-65h8-27jh-q8wv) |
| [CVE-2026-32230](https://www.cve.org/CVERecord?id=CVE-2026-32230) | Uptime Kuma | Private monitor ping data exposure | [Supplier / GitHub advisory](https://github.com/louislam/uptime-kuma/security/advisories/GHSA-c7hf-c5p5-5g6h) |

## Attribution and disclosure notes

- The external advisories are **publications by their issuing suppliers or platforms**. The list above is a verified research-credit index; it does not count seven new original publications on this website.
- The portfolio also describes field validation involving CVE-2025-55182 (React Server Components). That ID describes a broader pre-existing vulnerability and is deliberately **not** presented here as an original CVE assignment or a public advisory credit for this researcher.
- Only findings cleared for public disclosure appear in this archive. Employer/client assessments, private exploit evidence, nonpublic vendor conversations and embargoed details are excluded.
- A CVE ID is a vulnerability identifier, not a bounty, award or proof of exclusive discovery. Official CVE Records and the suppliers' advisory pages take precedence if any detail differs.

For privately coordinated vulnerabilities or corrections, read the [Disclosure Policy](../VULNERABILITY_DISCLOSURE_POLICY.md) and contact **karankurani3k@gmail.com**.

## Future publication process

Each new eligible public research note will be added here with publication and revision dates, affected versions where verified, impact and root cause, vendor notification status, remediation guidance and authoritative references. No embargoed details will be placed in this public index.
