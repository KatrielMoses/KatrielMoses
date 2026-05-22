<pre align="center"><code>K A T R I E L   M O S E S
principal security engineer / researcher / open-source auditor
</code></pre>

<p align="center">
<samp>
I break software carefully, write reports privately, and publish only after the fix lands.
</samp>
</p>

<p align="center">
<a href="mailto:katriel@rootaccess.tech"><img alt="email" src="https://img.shields.io/badge/mail-katriel%40rootaccess.tech-111111?style=flat-square&labelColor=111111&color=111111"></a>
<a href="https://linkedin.com/in/katriel-moses"><img alt="linkedin" src="https://img.shields.io/badge/linkedin-katriel--moses-111111?style=flat-square&labelColor=111111&color=111111"></a>
<a href="https://github.com/KatrielMoses/cves"><img alt="cves" src="https://img.shields.io/badge/advisories-KatrielMoses%2Fcves-111111?style=flat-square&labelColor=111111&color=111111"></a>
</p>

<br>

```console
rootaccess :: session opened
scope      :: enterprise networking, offensive security, OSS disclosure
role       :: Principal Security Engineer @ Lavelle Networks
mode       :: manual audit > proof of concept > private report > coordinated fix
```

I lead security for India's fast-growing enterprise networking stack, then spend weekends auditing open-source projects that people quietly depend on. The work is simple: find the broken thing, prove it cleanly, tell the maintainer first, and leave the ecosystem safer than I found it.

<br>

| audited projects | CVEs filed | RCE chains | largest target |
|:--:|:--:|:--:|:--:|
| <b>11</b> | <b>20+</b> | <b>5</b> | <b>23k stars</b> |

<br>

### `~/tools`

<table>
<tr>
<td width="50%" valign="top">

<pre><code>$ open MailAccess
</code></pre>

<b><a href="https://github.com/KatrielMoses/MailAccess">MailAccess</a></b>
<br>
Self-hostable email OSINT platform for mapping exposure across 800+ platforms, breach sources, DNS records, and the open web.

<sub><samp>Python / OSINT / pip install mailaccess</samp></sub>

</td>
<td width="50%" valign="top">

<pre><code>$ open VoidAccess
</code></pre>

<b><a href="https://github.com/KatrielMoses/voidaccess">VoidAccess</a></b>
<br>
Dark web threat-intelligence platform with Tor search, entity extraction, relationship graphing, and STIX 2.1 / MISP / Sigma export.

<sub><samp>Go / Docker / MIT</samp></sub>

</td>
</tr>
</table>

<br>

### `~/advisories`

| project | advisory | severity | class |
|:--|:--|:--:|:--|
| algernon | CVE-2026-43981 | High | Race condition, DoS via shared LState |
| algernon | CVE-2026-43982 | High | Path traversal file write via `savein()` |
| quark-auto-save | CVE-2026-45228 | Medium | Stored XSS via System Configuration |
| quark-auto-save | CVE-2026-45229 | High | Mass assignment, credential takeover |
| claude-hud | CVE-2026-47090 | Low | Terminal injection via OSC 8 hyperlinks |
| claude-hud | CVE-2026-47091 | Medium | Path traversal via `transcript_path` |
| claude-hud | CVE-2026-47092 | High | Arbitrary command execution via COMSPEC |

<sub><samp>18+ more in pipeline. Published advisories live at <a href="https://github.com/KatrielMoses/cves">github.com/KatrielMoses/cves</a>.</samp></sub>

<br><br>

### `~/audit-offer`

```text
free security audits for open-source projects

deliverables
  full manual source-code audit
  private report with working proof-of-concept
  CVEs filed and advisories published after fixes are live
  certificate confirming the project was reviewed and patched

condition
  the project has to be open source

turnaround
  one weekend, two at most
```

<br>

<div align="center">

<samp>
responsible disclosure, fix first, publish after
</samp>

</div>
