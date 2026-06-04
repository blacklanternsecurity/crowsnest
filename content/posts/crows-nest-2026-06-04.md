---
title: "Crow's Nest - 2026-06-04"
date: 2026-06-04T00:00:00+00:00
draft: false
tags: ["roundup"]
---

A roundup of 89 items curated from across the security community.

## News

- [Hackers Used Meta’s AI Support Bot to Seize Instagram Accounts](https://krebsonsecurity.com/2026/06/hackers-used-metas-ai-support-bot-to-seize-instagram-accounts) by BrianKrebs.
> Pro-Iran hackers hijacked high-profile Instagram accounts, including the Obama White House, by tricking Meta's AI support bot into resetting passwords with a spoofed hometown IP.

- [Dutch police dismantle a 17-million-device botnet](https://www.technadu.com/massive-17-million-device-botnet-in-the-netherlands-dismantled-in-a-police-and-ncsc-joint-operation/628801).
> Dutch police and the NCSC dismantled a 17-million-device botnet operating on 200 servers seized from a local hosting provider.

- [Red Hat npm packages compromised via CI/CD pipeline](https://x.com/cyb3rops/status/2061472860963516564) by Florian Roth.
> Multiple @redhat-cloud-services npm packages ship malicious preinstall hooks from a compromised GitHub Actions OIDC pipeline, targeting cloud tokens, /proc/mem secrets, and persisting through Claude Code and VS Code injection.

- [Four coordinated npm supply-chain campaigns, 176 packages](https://www.sonatype.com/blog/inside-a-176-package-npm-campaign-built-to-beat-your-internal-dependencies).
> Sonatype maps four npm campaigns running across May and June, including a 176-package set built to beat internal dependency checks, with IOCs and detection notes.

- [HTTP/2 Bomb pins 32GB of server memory in 10 seconds](https://blog.calif.io/p/codex-discovered-a-hidden-http2-bomb) by [Stefan Esser](https://x.com/i0n1c/status/2062033827871052194).
> A remote DoS across nginx, Apache, IIS, Envoy, and Cloudflare Pingora: one client pins 32GB of server memory in about 10 seconds. Found by Codex, with no patch at disclosure. Also: [Hacker News coverage](https://thehackernews.com/2026/06/new-http2-bomb-vulnerability-allows.html).


<details markdown="1">
<summary>More this week (15)</summary>

- [Microsoft Threatening Security Researcher](https://www.schneier.com/blog/archives/2026/06/microsoft-threatening-security-researcher.html) by Bruce Schneier.
- [Vulnerability Disclosure in the Age of AI](https://www.schneier.com/blog/archives/2026/06/vulnerability-disclosure-in-the-age-of-ai.html) by Bruce Schneier.
- [Iran uses selective internet restoration to track and arrest protesters](https://irannewswire.org/digital-trap-iran-internet-surveillance-january-protesters).
- [Severe Starlette vulnerability disclosed](https://badhost.org/).
- [Dutch server seizure also disrupted Iranian cyber operations](https://blog.checkpoint.com/security/the-server-seizure-that-affects-also-irans-cyber-operations).
- [US military personnel targeted via commercial location data](https://www.documentcloud.org/documents/28167310-department-of-defense-letter-to-ron-wyden).
- [Metasploit wrap-up: Dirty Frag LPEs and Citrix NetScaler scanner](https://www.rapid7.com/blog/post/pt-metasploit-wrap-up-05-29-2026).
- [Dashlane vaults accessed after a 2FA brute-force](https://support.dashlane.com/hc/en-us/articles/36038764990866-Security-advisory-Brute-force-attack-on-Dashlane-user-accounts?7194ef805fa2d04b0f7e8c9521f97343=).
- [ESET APT Activity Report Q4 2025 to Q1 2026](https://web-assets.esetstatic.com/wls/en/papers/threat-reports/eset-apt-activity-report-q4-2025-q1-2026.pdf) by [Dominic Chell](https://x.com/domchell/status/2060673725263958304).
- [Out-of-band SharePoint RCE patch (CVE-2026-45659)](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-45659) by [Dominic Chell](https://x.com/domchell/status/2059336476224110755).
- [EU Cyber Resilience Act 24-hour reporting takes effect in September](https://www.platanor.com/blog/cyber-resilience-act).
- [Quantum Health appears to be handling a breach](https://infosec.exchange/@briankrebs/116686966584593973).
- [Google patches 124 Android flaws, one actively exploited](https://www.bleepingcomputer.com/news/security/google-fixes-one-actively-exploited-android-zero-day-124-flaws).
- [Keycloak secrets disclosure and account takeover](https://github.com/keycloak/keycloak/issues/49220) by [kmkz](https://x.com/kmkz_security/status/2061467171960570062).
- [BIRD/BIRD2: stack buffer overflow in BGP AS_PATH matching](https://www.openwall.com/lists/oss-security/2026) by [Solar Designer](https://x.com/solardiz/status/2061655301170811362).

</details>


## Techniques and Write-ups

- [AI audit of FreeBSD: 15 kernel bugs found](https://blog.calif.io/p/an-ai-audit-of-freebsd).
> Calif runs an AI-driven audit of FreeBSD and surfaces 15 kernel bugs, including 3 RCEs, 5 LPEs, and a bhyve escape.

- [A 4-byte heap overflow to RCE in Minecraft via STB image parsing](https://osec.io/blog/2026-06-02-minecraft-heap-overflow-to-rce).
> A four-byte heap overflow in the STB image-parsing library escalated all the way to remote code execution in Minecraft.

- [LLM-driven pipeline for EDR signature reduction](https://www.praetorian.com/blog/llm-edr-signature-reduction) by [Jack Halon](https://x.com/jack_halon/status/2060459709195599883).
> Praetorian builds a pipeline using LLMs to keep offensive tools alive longer by reducing their EDR signature footprint, compiling Sliver, Chisel, and GhostPack to WASM.

- [1-click GitHub token theft via a VSCode bug](https://x.com/jeffmcjunkin/status/2061944647623311400) by Jeff McJunkin.
> Clicking one link in github.dev hands an attacker an OAuth token with read and write access to all your repos, including private ones. Dropped publicly because the researcher did not want to deal with MSRC.

- [Jellyfin RCE via a .NET JIT memfd gadget](https://www.sonarsource.com/blog/jellyfin-remote-code-execution?amp%3Butm_source=twitter&amp%3Butm_campaign=research&amp%3Butm_content=social-jellyfin-rce-260602-&amp%3Butm_term=---&amp%3Bs_category=Organic&amp%3Bs_source=Social+Media&amp%3Bs_origin=social) by [kmkz](https://x.com/kmkz_security/status/2061915700831133845).
> Sonar exploits an argument injection in Jellyfin using a .NET JIT compiler gadget: the runtime's memfd-backed code pages turn file writes into shellcode execution.

- [DarkReplica: Redis Lua engine use-after-free to RCE (CVE-2026-23631)](https://www.zeroday.cloud/blog/redis-cve-2026-23631-dark-replica) by [kmkz](https://x.com/kmkz_security/status/2061829024473571695).
> Wiz details DarkReplica, a use-after-free in Redis's built-in Lua engine that reaches remote code execution, one of five Redis RCEs disclosed in 48 hours.


<details markdown="1">
<summary>More this week (51)</summary>

- [DICOM heap overflow: a technical deep dive](https://blog.talosintelligence.com/dicom-pydicom-gdcm-and-orthanc-a-technical-tour-of-what-really-happens-in-the-heap) by Emmanuel Tacheau.
- [CVE-2026-4387: StrongDM auth state file reuse](https://specterops.io/blog/2026/06/01/cve-2026-4387-strongdm-state-file-reuse) by Hope Walker.
- [NuGet code execution as a service](https://tierzerosecurity.co.nz/2026/06/02/nuget-code-execution.html).
- [Poisoning Claude Code: one GitHub issue to break the supply chain](https://flatt.tech/research/posts/poisoning-claude-code-one-github-issue-to-break-the-supply-chain).
- [Stealing passwords via HTML injection under a strict CSP](https://afine.com/blogs/stealing-passwords-via-html-injection-under-a-strict-csp).
- [Subnet discovery through multi-protocol TTL tracing](https://ifritnoises.org/articles/pattern-screamer).
- [ThinkPad firmware reverse-engineering toolchain](https://tetdrad0n.codeberg.page/thinkpad-fw-analysis).
- [Mapping a botnet by its backend: 1,001 IPs across 64 countries](https://honeylabs.net/blog/mapping-a-botnet-by-its-back-end).
- [Fooling around with encrypted reasoning blobs](https://blog.cryptographyengineering.com/2026/05/29/fooling-around-with-encrypted-reasoning-blobs).
- [The word "Toad" gave any website full control of Chrome's top VPN](https://amibeingpwned.com/blog/urban-vpn-postmessage-command-injection).
- [Visual Studio extensions revisited](https://www.mdsec.co.uk/2026/05/visual-studio-extensions-revisited).
- [The open redirect variant that is actually a vulnerability](https://www.youtube.com/watch?v=eTdeFbWROeg).
- [Detecting Nimbus Manticore (UNC1549)](https://eu1.hubs.ly/H0vPgF80) by [Florian Roth](https://x.com/cyb3rops/status/2061509436988956764).
- [RedSun: local privilege escalation via Defender's remediation workflow](https://open.substack.com/pub/calif/p/redsun-exploiting-windows-defenders?r=26yra9&amp%3Butm_campaign=post&amp%3Butm_medium=web) by [Florian Roth](https://x.com/cyb3rops/status/2061504321909334093).
- [z386: an FPGA 386 built from the original microcode](https://github.com/nand2mario/z386) by [Daax](https://x.com/daaximus/status/2059047429689766295).
- [Exploiting ML-DSA bugs: post-quantum code as an attack surface](https://cr.yp.to/papers.html) by [Dave Aitel](https://x.com/daveaitel/status/2061822968217366687).
- [Azure Front Door cache poisoning to 0-click XSS](https://malicious.group/smuggling-through-the-front-door-achieving-0-click-xss-with-cache-poisoning) by [d3d aka dead (dead, мёртв, 死了)](https://x.com/deadvolvo/status/2060794961105236410).
- [Skill scanners do not catch malicious AI skills](https://blog.trailofbits.com/2026/06/03/the-sorry-state-of-skill-distribution).
- [Katana: BadUSB attacks driven through a PC speaker](https://blog.nns.ee/2026/06/03/katana-badusb).
- [Weaponizing legitimate iDEAL payment links in phishing](https://zolder.io/blog/ideal-payment-link-abuse-in-phishing).
- [Golang code review notes, part two](https://www.elttam.com/blog/golang-code-review-notes-ii).
- [Hidden permissions found after adding a detection rule](https://profero.io/blog/hiddenperms).
- [Device code phishing forensics in BEC investigations](https://research.eye.security/device-code-phishing-forensics).
- [Finding XSS in Shazzer, the XSS testing tool](https://jorianwoltjer.com/blog/p/stories/finding-xss-on-shazzer) by [Gareth Heyes \u2028](https://x.com/garethheyes/status/2059907574686744775).
- [What hands-free, LLM-driven vulnerability research looks like](https://claroty.com/team82/research/hands-free-what-llm-driven-vulnerability-research-looks-like).
- [Exploits were never the point](https://open.substack.com/pub/arunninghacker/p/exploits-were-never-the-point?r=ypuvf&amp%3Butm_campaign=post-expanded-share&amp%3Butm_medium=post+viewer) by [Halvar Flake](https://x.com/halvarflake/status/2062216914282107378).
- [Fake Ghidra and dnSpy sites push malware through a TDS](https://research.checkpoint.com/2026/impersonation-click-hijacking-and-tds-inside-a-malware-distrib…) by [hasherezade](https://x.com/hasherezade/status/2062191671769457128).
- [Tracking Kimsuky APT infrastructure](https://idanmalihi.com/tracking-north-korea-nation-state-apt-infrastructure-kimsuky) by [hasherezade](https://x.com/hasherezade/status/2062113753974333701).
- [Inside a UEFI bootkit that hides in Hyper-V and manipulates EPT](https://back.engineering/blog/04/02/2026) by [hasherezade](https://x.com/hasherezade/status/2061768423479157024).
- [BYOVD to loot LSASS, bypassing HVCI on Windows 11 25H2](https://g3tsyst3m.com/byovd/BYOVD-and-Looting-LSASS-in-the-Modern-EDR-Era) by [hasherezade](https://x.com/hasherezade/status/2060697095158354423).
- [Reading kernel MTE panics on Apple Silicon](https://binarygecko.com/blog/looking-at-kernel-mte-panics-on-apple-silicon) by [Stefan Esser](https://x.com/i0n1c/status/2061850338420773280).
- [Two bypasses for Chrome's Sanitizer API](https://slcyber.io/resea) by [shubs](https://x.com/infosec_au/status/2057714139091579022).
- [Keys to the Kingdom: Drupal Core CVE-2026-9082 deep dive](https://slcyber.io/research-center/keys-to-the-kingdom-anonymous-sql-injection-in-drupal-core-cve-2026-9082) by [shubs](https://x.com/infosec_au/status/2057484346093887921).
- [Bring Your Own RWX Region DLL (BYORWXDLL)](https://medium.com/@s12deff/bring-your-own-rwx-region-dll-byorwxdll-0283951d34e9) by [Panos Gkatziroulis](https://x.com/ipurple/status/2062104005556236318).
- [Automating Entra ID tenant destruction with AI](https://netwrix.com/en/resources/blog/automating-entra-id-tenant-destruction-with-ai) by [Panos Gkatziroulis](https://x.com/ipurple/status/2057812192402031015).
- [CVE-2026-41089 PoC](https://github.com/0xABCD01/CVE-2026-41089) by [Chihuahua in charge NotMe](https://x.com/jessefmoore/status/2061628868625371461).
- [CVE-2026-8326: SparkView path traversal to RCE as root](https://github.com/advisories/GHSA-fhv3-q37g-rjx5) by [kmkz](https://x.com/kmkz_security/status/2062174340532129895).
- [CVE-2026-46333: a ptrace logic bug for Linux privilege escalation](https://cdn2.qualys.com/advisory/2026/05/20/cve-2026-46333-ptrace.txt) by [kmkz](https://x.com/kmkz_security/status/2062177519348879424).
- [ETW internals deep dive](https://kernullist.github.io/kernullist-blog/posts/etw-internals-deep-dive) by [kmkz](https://x.com/kmkz_security/status/2062094734701539667).
- [Adobe Acrobat eScript use-after-free RCE](https://blog.exodusintel.com/2026/06/01/adobe-acrobat-reader-escript-api-use-after-free-remote-code-execution) by [kmkz](https://x.com/kmkz_security/status/2061903404637544479).
- [CVE-2026-0826: unauthenticated stack overflow in HP Poly VoIP phones](https://r-7.co/4wQuXul) by [kmkz](https://x.com/kmkz_security/status/2061887853521469440).
- [Chrome exploit mitigations deep dive](https://zerodayengineering.com/research/chrome-) by [kmkz](https://x.com/kmkz_security/status/2062095224797610338).
- [Fake Claude Code, real malware: ACR Stealer campaign targeting AI developers](https://www.straiker.ai/blog/acr-stealer-claude-code-impersonation-campaign) by [Malware Unicorn](https://x.com/malwareunicorn/status/2059698263494955165).
- [Unpatched RCE in Gogs via git rebase argument injection](https://www.rapid7.com/blog/post/ve-authenticated-rce-via-argument-injection-gogs-unfixed) by [Metasploit Project](https://x.com/metasploit/status/2060457784852787613).
- [FlutterShell: a macOS backdoor that weaponizes AI summarization](https://unit42.paloaltonetworks.com/flutterbridge-new-fluttershell-backdoor) by [Patrick Wardle](https://x.com/patrickwardle/status/2062154383727493602).
- [The 9.3 critical dependency confusion Microsoft dismissed](https://www.wahidfayad.com/blog.html?post=micros) by [Swissky](https://x.com/pentest_swissky/status/2062188123660996650).
- [Drupal CVE-2026-9082 to RCE on PostgreSQL superuser](https://blog.lexfo.fr/drupal-postgresql-sqli-to-rce.html) by [Swissky](https://x.com/pentest_swissky/status/2060010465187516703).
- [Unpatched NTLM coercion via the Windows Search URI handler](https://www.huntress.com/blog/unpatched-ntlm-coercion-windows-search-uri-handler) by [Rémi GASCOU (Podalirius)](https://x.com/podalirius_/status/2061814118399488387).
- [StubZero: $148K RCE in Google Cloud production](https://brutecat.com/articles/google-cloud-rce) by [Sam Curry](https://x.com/samwcyo/status/2058160239271198745).
- [CIFSwitch: Linux local root via forged cifs.spnego upcall](https://www.openwall.com/lists/oss-s) by [Solar Designer](https://x.com/solardiz/status/2059933475570856090).
- [Vulnerability Spoiler Alert: catching CVEs before publication](https://spaceraccoon.dev/negative-days-vulnerability-spoiler-alert) by [spaceraccoon | Eugene Lim](https://x.com/spaceraccoonsec/status/2058558318961172798).

</details>


## Tools and Exploits

- [HijackLibs adds Sigma coverage for 600+ DLL hijacks](https://hijacklibs.net/).
> HijackLibs.net refreshes with over 600 documented DLL hijacking cases, machine-readable feeds, and Sigma detection content for every DLL.

- [MogVMP: a devirtualizer for VMProtect 3.5](https://github.com/eversinc33/MogVMP) by [hasherezade](https://x.com/hasherezade/status/2061240676495282303).
> A VMProtect 3.5 devirtualizer built on Remill that lifts the whole x86 code of the VM, released as code.

- [Project Onyx: EDR evasion via AI telemetry spoofing and WASM](https://github.com/X-3306/Project-Onyx) by [Panos Gkatziroulis](https://x.com/ipurple/status/2058990735244898449).
> A red team PoC pipeline that combines AI-driven telemetry spoofing with WASM sandboxing to evade modern EDR systems.


<details markdown="1">
<summary>More this week (9)</summary>

- [LLMReaper: exfiltrating AI conversations via browser extensions](https://thewhiteh4t.github.io/blog/ai-chat-llmreaper).
- [TinyTracer 4.0: PIN-based binary tracer updated](https://github.com/hasherezade/tiny_tracer/releases).
- [Invoke-WindowsSearch: stealthy file enumeration via the Windows Search DB](https://x.com/checkymander/status/2061585154515087669) by One punch mander.
- [Cowrie 3.0: the SSH/Telnet honeypot now pip-installable](https://x.com/chrissanders88/status/2059265304228724982) by Chris Sanders.
- [PseudoForge: an IDA plugin for Windows driver analysis](https://github.com/kernullist/PseudoForge) by [hasherezade](https://x.com/hasherezade/status/2060799283683901607).
- [goLoL: scan a host for usable LOLBAS techniques](https://github.com/aaron-kidwell/goLoL) by [Panos Gkatziroulis](https://x.com/ipurple/status/2057830414392213564).
- [RustyPacker: a Rust shellcode packer with indirect syscalls](https://github.com/Whitecat18/RustyPacker.git) by [kmkz](https://x.com/kmkz_security/status/2061529901954388047).
- [YARA and PowerShell scanner for github.dev token theft artifacts](https://gist.github.com/Samirbous/59b2e32c93665101e43aaa67b2ccf5b4) by [Ring3API 🇺🇦](https://x.com/ntlmrelay/status/2062233702613008896).
- [Outpacket: impacket workflows mapped to modern alternatives](https://github.com/n00py/Outpacket) by [Swissky](https://x.com/pentest_swissky/status/2059959871684948166).

</details>



