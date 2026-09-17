<div align="center">

<img src="assets/lockup.png" alt="rainpwn" width="260">

<a href="https://rainpwn.blog"><img src="assets/line.svg" alt="Most of it is reading. The findings are in what nobody documented." width="680"></a>

[![Blog](https://img.shields.io/badge/rainpwn.blog-1a1d21?style=flat-square&labelColor=08090a&logo=firefoxbrowser&logoColor=9FEF00)](https://rainpwn.blog) [![Mastodon](https://img.shields.io/badge/@rainpwn-1a1d21?style=flat-square&labelColor=08090a&logo=mastodon&logoColor=9FEF00)](https://infosec.exchange/@rainpwn) [![LinkedIn](https://img.shields.io/badge/LinkedIn-1a1d21?style=flat-square&labelColor=08090a&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyBmaWxsPSIjOUZFRjAwIiByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cGF0aCBkPSJNMjAuNDQ3IDIwLjQ1MmgtMy41NTR2LTUuNTY5YzAtMS4zMjgtLjAyNy0zLjAzNy0xLjg1Mi0zLjAzNy0xLjg1MyAwLTIuMTM2IDEuNDQ1LTIuMTM2IDIuOTM5djUuNjY3SDkuMzUxVjloMy40MTR2MS41NjFoLjA0NmMuNDc3LS45IDEuNjM3LTEuODUgMy4zNy0xLjg1IDMuNjAxIDAgNC4yNjcgMi4zNyA0LjI2NyA1LjQ1NXY2LjI4NnpNNS4zMzcgNy40MzNjLTEuMTQ0IDAtMi4wNjMtLjkyNi0yLjA2My0yLjA2NSAwLTEuMTM4LjkyLTIuMDYzIDIuMDYzLTIuMDYzIDEuMTQgMCAyLjA2NC45MjUgMi4wNjQgMi4wNjMgMCAxLjEzOS0uOTI1IDIuMDY1LTIuMDY0IDIuMDY1em0xLjc4MiAxMy4wMTlIMy41NTVWOWgzLjU2NHYxMS40NTJ6TTIyLjIyNSAwSDEuNzcxQy43OTIgMCAwIC43NzQgMCAxLjcyOXYyMC41NDJDMCAyMy4yMjcuNzkyIDI0IDEuNzcxIDI0aDIwLjQ1MUMyMy4yIDI0IDI0IDIzLjIyNyAyNCAyMi4yNzFWMS43MjlDMjQgLjc3NCAyMy4yIDAgMjIuMjIyIDBoLjAwM3oiLz48L3N2Zz4%3D)](https://www.linkedin.com/in/rainpwn/) [![Email](https://img.shields.io/badge/rainpwn@protonmail.com-1a1d21?style=flat-square&labelColor=08090a&logo=protonmail&logoColor=9FEF00)](mailto:rainpwn@protonmail.com) [![Proof of concept code](https://img.shields.io/badge/exploits-1a1d21?style=flat-square&labelColor=08090a&logo=github&logoColor=9FEF00)](https://github.com/rainpwn/exploits) [![RSS feed](https://img.shields.io/badge/feed-1a1d21?style=flat-square&labelColor=08090a&logo=rss&logoColor=9FEF00)](https://rainpwn.blog/feed.xml)

![20 findings](https://img.shields.io/badge/findings-20-1a1d21?style=flat-square&labelColor=08090a) ![19 on NVD](https://img.shields.io/badge/on_NVD-19-1a1d21?style=flat-square&labelColor=08090a) ![since March 2022](https://img.shields.io/badge/since-March_2022-1a1d21?style=flat-square&labelColor=08090a) ![all patched](https://img.shields.io/badge/status-all_patched-1a1d21?style=flat-square&labelColor=08090a)

[Findings](#findings) &middot; [Published work](#published-work) &middot; [Contact](#contact)

</div>

---

Alessandro Sgreccia. I do vulnerability research on network security appliances: firewalls, access points and security routers. Twenty findings since March 2022, all patched. Nineteen carry a CVE on NVD, and the twentieth is waiting on MITRE. Mostly ZYXEL, plus UANIA and Breldo Italia.

## Findings

Legend: ![critical](https://img.shields.io/badge/-e5484d?style=flat-square) critical &middot; ![high](https://img.shields.io/badge/-f0791e?style=flat-square) high &middot; ![medium](https://img.shields.io/badge/-e0b341?style=flat-square) medium

| Year | | Total |
|---|---|---|
| `2022` | ![1 critical](https://img.shields.io/badge/-e5484d?style=flat-square)![1 medium](https://img.shields.io/badge/-e0b341?style=flat-square) | 2 |
| `2023` | ![1 high](https://img.shields.io/badge/-f0791e?style=flat-square)![7 medium](https://img.shields.io/badge/-e0b341?style=flat-square)![](https://img.shields.io/badge/-e0b341?style=flat-square)![](https://img.shields.io/badge/-e0b341?style=flat-square)![](https://img.shields.io/badge/-e0b341?style=flat-square)![](https://img.shields.io/badge/-e0b341?style=flat-square)![](https://img.shields.io/badge/-e0b341?style=flat-square)![](https://img.shields.io/badge/-e0b341?style=flat-square) | 8 |
| `2024` | ![2 high](https://img.shields.io/badge/-f0791e?style=flat-square)![](https://img.shields.io/badge/-f0791e?style=flat-square)![1 medium](https://img.shields.io/badge/-e0b341?style=flat-square) | 3 |
| `2025` | ![4 high](https://img.shields.io/badge/-f0791e?style=flat-square)![](https://img.shields.io/badge/-f0791e?style=flat-square)![](https://img.shields.io/badge/-f0791e?style=flat-square)![](https://img.shields.io/badge/-f0791e?style=flat-square)![1 medium](https://img.shields.io/badge/-e0b341?style=flat-square) | 5 |
| `2026` | ![2 high](https://img.shields.io/badge/-f0791e?style=flat-square)![](https://img.shields.io/badge/-f0791e?style=flat-square) | 2 |

Six of the 2023 findings went out on the same day, 28 November.

| Class | | Total |
|---|---|---|
| Command injection | ![4 high](https://img.shields.io/badge/-f0791e?style=flat-square)![](https://img.shields.io/badge/-f0791e?style=flat-square)![](https://img.shields.io/badge/-f0791e?style=flat-square)![](https://img.shields.io/badge/-f0791e?style=flat-square) | 4 |
| Privilege escalation | ![2 high](https://img.shields.io/badge/-f0791e?style=flat-square)![](https://img.shields.io/badge/-f0791e?style=flat-square)![2 medium](https://img.shields.io/badge/-e0b341?style=flat-square)![](https://img.shields.io/badge/-e0b341?style=flat-square) | 4 |
| Information disclosure | ![3 medium](https://img.shields.io/badge/-e0b341?style=flat-square)![](https://img.shields.io/badge/-e0b341?style=flat-square)![](https://img.shields.io/badge/-e0b341?style=flat-square) | 3 |
| Authentication bypass | ![1 critical](https://img.shields.io/badge/-e5484d?style=flat-square)![1 high](https://img.shields.io/badge/-f0791e?style=flat-square) | 2 |
| Buffer overflow | ![2 medium](https://img.shields.io/badge/-e0b341?style=flat-square)![](https://img.shields.io/badge/-e0b341?style=flat-square) | 2 |
| Cross-site scripting | ![2 medium](https://img.shields.io/badge/-e0b341?style=flat-square)![](https://img.shields.io/badge/-e0b341?style=flat-square) | 2 |
| Remote code execution | ![2 high](https://img.shields.io/badge/-f0791e?style=flat-square)![](https://img.shields.io/badge/-f0791e?style=flat-square) | 2 |
| Open redirect | ![1 medium](https://img.shields.io/badge/-e0b341?style=flat-square) | 1 |

One of the twenty is critical. A 2022 authentication bypass on the USG and ZyWALL series, CVSS 9.8, where the CGI program handed administrative access to a request that never logged in.

<details>
<summary>All twenty, newest first</summary>

<br>

| Identifier | CVSS | Product | Advisory | Writeup |
|---|---|---|---|---|
| `pending` | ![CVSS 8.8, high](https://img.shields.io/badge/8.8-high-f0791e?style=flat-square&labelColor=08090a) | UaniaOS | [advisory](https://www.uania.com/security/) | [writeup](https://rainpwn.blog/blog/uania-os-rce) |
| [CVE-2025-11730](https://nvd.nist.gov/vuln/detail/CVE-2025-11730) | ![CVSS 7.2, high](https://img.shields.io/badge/7.2-high-f0791e?style=flat-square&labelColor=08090a) | Firewall | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-post-authentication-command-injection-vulnerability-in-the-ddns-configuration-cli-command-of-zld-firewalls-02-05-2026) | [writeup](https://rainpwn.blog/blog/cve-2025-11730) |
| [CVE-2025-9133](https://nvd.nist.gov/vuln/detail/CVE-2025-9133) | ![CVSS 8.2, high](https://img.shields.io/badge/8.2-high-f0791e?style=flat-square&labelColor=08090a) | Firewall | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-post-authentication-command-injection-and-missing-authorization-vulnerabilities-in-zld-firewalls-10-21-2025) | [writeup](https://rainpwn.blog/blog/cve-2025-9133) |
| [CVE-2025-8078](https://nvd.nist.gov/vuln/detail/CVE-2025-8078) | ![CVSS 7.2, high](https://img.shields.io/badge/7.2-high-f0791e?style=flat-square&labelColor=08090a) | Firewall | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-post-authentication-command-injection-and-missing-authorization-vulnerabilities-in-zld-firewalls-10-21-2025) | [writeup](https://rainpwn.blog/blog/cve-2025-8078) |
| [CVE-2025-1731](https://nvd.nist.gov/vuln/detail/CVE-2025-1731) | ![CVSS 7.8, high](https://img.shields.io/badge/7.8-high-f0791e?style=flat-square&labelColor=08090a) | FLEX H Series | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-incorrect-permission-assignment-and-improper-privilege-management-vulnerabilities-in-usg-flex-h-series-firewalls-04-22-2025) | [writeup](https://rainpwn.blog/blog/cve-2025-1731_cve-2025-1732) |
| [CVE-2025-1732](https://nvd.nist.gov/vuln/detail/CVE-2025-1732) | ![CVSS 6.7, medium](https://img.shields.io/badge/6.7-medium-e0b341?style=flat-square&labelColor=08090a) | FLEX H Series | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-incorrect-permission-assignment-and-improper-privilege-management-vulnerabilities-in-usg-flex-h-series-firewalls-04-22-2025) | [writeup](https://rainpwn.blog/blog/cve-2025-1731_cve-2025-1732) |
| [CVE-2024-12398](https://nvd.nist.gov/vuln/detail/CVE-2024-12398) | ![CVSS 8.8, high](https://img.shields.io/badge/8.8-high-f0791e?style=flat-square&labelColor=08090a) | AP, Security Router | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-improper-privilege-management-vulnerability-in-aps-and-security-router-devices-01-14-2025) | [writeup](https://rainpwn.blog/blog/cve-2024-12398) |
| [CVE-2024-9677](https://nvd.nist.gov/vuln/detail/CVE-2024-9677) | ![CVSS 7.8, high](https://img.shields.io/badge/7.8-high-f0791e?style=flat-square&labelColor=08090a) | USG FLEX H | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-insufficiently-protected-credentials-vulnerability-in-firewalls-10-22-2024) |  |
| [CVE-2024-7203](https://nvd.nist.gov/vuln/detail/CVE-2024-7203) | ![CVSS 7.2, high](https://img.shields.io/badge/7.2-high-f0791e?style=flat-square&labelColor=08090a) | Firewall | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-multiple-vulnerabilities-in-firewalls-09-03-2024) | [writeup](https://rainpwn.blog/blog/cve-2024-7203) |
| [CVE-2024-1575](https://nvd.nist.gov/vuln/detail/CVE-2024-1575) | ![CVSS 6.5, medium](https://img.shields.io/badge/6.5-medium-e0b341?style=flat-square&labelColor=08090a) | Access Point | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-improper-privilege-management-vulnerability-in-aps-07-23-2024) |  |
| [CVE-2023-5797](https://nvd.nist.gov/vuln/detail/CVE-2023-5797) | ![CVSS 5.5, medium](https://img.shields.io/badge/5.5-medium-e0b341?style=flat-square&labelColor=08090a) | Firewall | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-multiple-vulnerabilities-in-firewalls-and-aps) |  |
| [CVE-2023-5960](https://nvd.nist.gov/vuln/detail/CVE-2023-5960) | ![CVSS 5.5, medium](https://img.shields.io/badge/5.5-medium-e0b341?style=flat-square&labelColor=08090a) | Firewall | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-multiple-vulnerabilities-in-firewalls-and-aps) |  |
| [CVE-2023-37926](https://nvd.nist.gov/vuln/detail/CVE-2023-37926) | ![CVSS 5.5, medium](https://img.shields.io/badge/5.5-medium-e0b341?style=flat-square&labelColor=08090a) | Firewall | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-multiple-vulnerabilities-in-firewalls-and-aps) |  |
| [CVE-2023-37925](https://nvd.nist.gov/vuln/detail/CVE-2023-37925) | ![CVSS 5.5, medium](https://img.shields.io/badge/5.5-medium-e0b341?style=flat-square&labelColor=08090a) | Firewall, Access Point | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-multiple-vulnerabilities-in-firewalls-and-aps) | [writeup](https://rainpwn.blog/blog/cve-2023-37925) |
| [CVE-2023-4397](https://nvd.nist.gov/vuln/detail/CVE-2023-4397) | ![CVSS 4.4, medium](https://img.shields.io/badge/4.4-medium-e0b341?style=flat-square&labelColor=08090a) | Firewall | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-multiple-vulnerabilities-in-firewalls-and-aps) |  |
| [CVE-2023-5650](https://nvd.nist.gov/vuln/detail/CVE-2023-5650) | ![CVSS 5.5, medium](https://img.shields.io/badge/5.5-medium-e0b341?style=flat-square&labelColor=08090a) | Firewall | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-multiple-vulnerabilities-in-firewalls-and-aps) |  |
| [CVE-2023-27990](https://nvd.nist.gov/vuln/detail/CVE-2023-27990) | ![CVSS 4.8, medium](https://img.shields.io/badge/4.8-medium-e0b341?style=flat-square&labelColor=08090a) | Firewall | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-xss-vulnerability-and-post-authentication-command-injection-vulnerability-in-firewalls) |  |
| [CVE-2023-27991](https://nvd.nist.gov/vuln/detail/CVE-2023-27991) | ![CVSS 8.8, high](https://img.shields.io/badge/8.8-high-f0791e?style=flat-square&labelColor=08090a) | Firewall | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-xss-vulnerability-and-post-authentication-command-injection-vulnerability-in-firewalls) | [writeup](https://rainpwn.blog/blog/cve-2023-27991) |
| [CVE-2022-40603](https://nvd.nist.gov/vuln/detail/cve-2022-40603) | ![CVSS 6.1, medium](https://img.shields.io/badge/6.1-medium-e0b341?style=flat-square&labelColor=08090a) | Firewall | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-xss-vulnerability-in-firewalls) |  |
| [CVE-2022-0342](https://nvd.nist.gov/vuln/detail/CVE-2022-0342) | ![CVSS 9.8, critical](https://img.shields.io/badge/9.8-critical-e5484d?style=flat-square&labelColor=08090a) | Firewall | [advisory](https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-authentication-bypass-vulnerability-of-firewalls) |  |

</details>

## Published work

- [Writeups](https://rainpwn.blog/blog), thirteen of them, each with its disclosure timeline at the end.
- The [CVE index](https://rainpwn.blog/cve) puts every identifier next to its score and the vendor advisory.
- Seven proof of concept scripts are in [rainpwn/exploits](https://github.com/rainpwn/exploits).
- [/work](https://rainpwn.blog/work) is the page for a vendor: the ways of handing a device over, and what each one misses.

## Contact

rainpwn@protonmail.com, and the [PGP key](https://rainpwn.blog/contact/rainpwn.asc) if you would rather encrypt it.

---

<div align="center"><i>From the surface to root.</i></div>
