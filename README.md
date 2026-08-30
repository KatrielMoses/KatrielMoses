<div align="center">

### katriel moses

`building top-tier security tooling · breaking open source & filing the CVEs`

[rootaccess.tech](https://rootaccess.tech) &nbsp;·&nbsp; [advisories](https://github.com/KatrielMoses/cves)

</div>

<br>

<!-- ─────────────  THE TOOLS  ───────────── -->

<table width="100%">
<tr>
<td align="center" width="50%" valign="top">
<a href="https://github.com/KatrielMoses/MailAccess"><img src="assets/mailaccess-logo.svg" width="340" alt="mailaccess"></a>
<br><br>
<b>Email OSINT across 2500+ platforms</b>
<br>
<sub>breach detection · identity clustering · DNS &amp; web exposure · no API keys</sub>
<br><br>
<code>pip install mailaccess</code>
<br><br>
<a href="https://github.com/KatrielMoses/MailAccess"><img src="https://img.shields.io/github/stars/KatrielMoses/MailAccess?style=flat&label=stars&labelColor=0D0D0D&color=8A1C2B" alt="stars"></a>
<img src="https://img.shields.io/badge/python-0D0D0D?style=flat&logo=python&logoColor=8A1C2B" alt="python">
</td>
<td align="center" width="50%" valign="top">
<a href="https://github.com/KatrielMoses/voidaccess"><img src="assets/voidaccess-logo.png" width="340" alt="voidaccess"></a>
<br><br>
<b>Self-hosted dark-web OSINT</b>
<br>
<sub>automated threat intel · query → graph in 13 steps · relationship mapping</sub>
<br><br>
<code>pip install voidaccess</code>
<br><br>
<a href="https://github.com/KatrielMoses/voidaccess"><img src="https://img.shields.io/github/stars/KatrielMoses/voidaccess?style=flat&label=stars&labelColor=1E1E32&color=6C6CE5" alt="stars"></a>
<img src="https://img.shields.io/badge/python-1E1E32?style=flat&logo=python&logoColor=6C6CE5" alt="python">
</td>
</tr>
</table>

<br>

<!-- ─────────────  NOTABLE CVEs  ───────────── -->

### notable CVEs

<sub>found by manual source review, reported privately, published after the fix shipped.</sub>

| cve | target | class | severity |
|:--|:--|:--|:--|
| [CVE-2026-50112](https://www.cve.org/CVERecord?id=CVE-2026-50112) | **Apache CloudStack** | RCE + SSRF → root on KVM host | 🔴 Critical |
| [CVE-2026-58123](https://www.cve.org/CVERecord?id=CVE-2026-58123) | **Hermes WebUI** | unauthenticated RCE (terminal API) | 🔴 Critical · 9.3 |
| [CVE-2026-53975](https://www.cve.org/CVERecord?id=CVE-2026-53975) | **OpenChamber** | unauthenticated RCE (command injection) | 🔴 Critical · 9.3 |
| [CVE-2026-53983](https://www.cve.org/CVERecord?id=CVE-2026-53983) | **Ground Station** | blind SSRF (orbital data URL) | 🔴 Critical · 9.2 |
| [CVE-2026-10142](https://www.cve.org/CVERecord?id=CVE-2026-10142) | **kafka-python** | DoS (excessive memory allocation) | 🟠 High · 8.7 |

<details>
<summary><sub>more disclosures</sub></summary>

<br>

| cve | target | class | severity |
|:--|:--|:--|:--|
| [CVE-2026-45229](https://www.cve.org/CVERecord?id=CVE-2026-45229) | quark-auto-save | mass assignment → credential takeover | High |
| [CVE-2026-47092](https://www.cve.org/CVERecord?id=CVE-2026-47092) | claude-hud | arbitrary command execution via COMSPEC | High |
| [CVE-2026-43982](https://www.cve.org/CVERecord?id=CVE-2026-43982) | algernon | path-traversal file write via `savein()` | High |
| [CVE-2026-43981](https://www.cve.org/CVERecord?id=CVE-2026-43981) | algernon | race condition → DoS via shared LState | High |
| [CVE-2026-47091](https://www.cve.org/CVERecord?id=CVE-2026-47091) | claude-hud | path traversal via `transcript_path` | Medium |
| [CVE-2026-45228](https://www.cve.org/CVERecord?id=CVE-2026-45228) | quark-auto-save | stored XSS via system configuration | Medium |
| [CVE-2026-47090](https://www.cve.org/CVERecord?id=CVE-2026-47090) | claude-hud | terminal injection via OSC 8 hyperlinks | Low |

</details>

<sub>full writeups → [github.com/KatrielMoses/cves](https://github.com/KatrielMoses/cves)</sub>

<br>

<!-- ─────────────  FREE AUDITS  ───────────── -->

### free audits

open source? i'll break it for free.

```text
you get   →  full manual source review
          →  private report with a working PoC
          →  CVE filed + advisory published, after your fix ships
          →  a note confirming the project was reviewed & patched
catch     →  it has to be open source
turnaround→  a weekend. two at most.
```

<br>

<div align="center">
<sub><b>responsible disclosure</b> &nbsp;·&nbsp; <b>fix first</b> &nbsp;·&nbsp; <b>publish after</b></sub>
</div>
