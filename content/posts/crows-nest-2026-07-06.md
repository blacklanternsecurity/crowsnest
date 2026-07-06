---
title: "Crow's Nest - 2026-07-06"
date: 2026-07-06T00:00:00+00:00
draft: false
tags: ["roundup"]
---

A roundup of 160 items curated from across the security community.

## News

- [FBI PSA: TeamPCP Data Extortion Group Behind Longest Supply-Chain Hack Streak](https://www.ic3.gov/CSA/2026/260702.pdf).
> FBI releases a PSA on TeamPCP, a data extortion group responsible for the longest running streak of software supply-chain hacks on record, including compromises of Trivy, CheckMarx, LiteLLM, and at least 3,800 GitHub repositories.

- [Iranian Hacker Arrested for IRGC-Backed University IP Theft Campaign](https://www.zetter-zeroday.com/arrest-of-iranian-hacker-spotlights-irans-movement-into-economic-espionage-and-ip-theft) by [Kim Zetter](https://x.com/KimZetter/status/2072279630929600929).
> An Iranian hacker arrested in Montenegro for hacking over 100 US universities on behalf of the IRGC highlights Iran's shift toward economic espionage and intellectual property theft.

- [Startup Sues Palo Alto Networks Over AI-Hallucinated Espionage Report](https://www.theregister.com/legal/2026/07/02/startup-sues-palo-alto-networks-koi-security-saying-an-ai-hallucinated-report-falsely-linked-it-to-chinese-espionage/5266201).
> A startup is suing Palo Alto Networks after an AI-generated threat report falsely linked them to Chinese espionage. A cautionary tale about AI in threat intelligence attribution.

- [Scattered Spider Member Arrested in Finland, Extradited to US](https://www.justice.gov/opa/pr/alleged-member-criminal-cyber-hacking-group-scattered-spider-arrested-finland-and-extradited) by [Florian Roth](https://x.com/cyb3rops/status/2072551453470642601).
> DOJ announces the arrest of an alleged Scattered Spider member in Finland. Court documents reveal Microsoft's GDID telemetry was used to track the suspect across VPNs and reimages.

- [Russian Cybercrime Forum XSS.is Shut Down, Admin Arrested](https://www.scworld.com/brief/major-russia) by [thaddeus e. grugq](https://x.com/thegrugq/status/2072969635285315802).
> Major Russian-language cybercrime forum XSS.is has been shut down and its alleged administrator arrested in a law enforcement operation.

- [JadePuffer Ransomware Used AI Agent to Automate Entire Attack](https://www.bleepingcomputer.com/news/security/jadepuffer-ransomware-used-ai-agent-to-au) by [BleepingComputer](https://x.com/BleepinComputer/status/2073411069276565578).
> First documented case of a ransomware group deploying an autonomous AI agent to execute the full attack chain, from initial access through encryption.

- [19-Year-Old Linux Kernel Zero-Day Enables Local Privilege Escalation](https://gmo-cybersecurity.com/blog/19-year-old-linux-kernel-zero-day) by [Alex Plaskett](https://x.com/alexjplaskett/status/2073021336197177454).
> GMO Cybersecurity reports a privilege escalation vulnerability that went unnoticed in the Linux kernel for over 19 years. Now patched.

- [Bad Epoll: Linux Kernel LPE Reaches 99% Reliability (CVE-2026-46242)](https://thehackernews.com/2026/07/new-bad-epoll-linux-kernel-flaw-lets.html) by [Florian Roth](https://x.com/cyb3rops/status/2073171520210219221).
> A new Linux kernel vulnerability affecting 6.4+ kernels and newer Android devices. PoC achieves 99% reliability for local-to-root escalation and may trigger from Chrome's renderer sandbox.

- [Lazarus-Linked npm Malware Campaign Still Active](https://gist.github.com/marius-benthin/d504e656a646f6dd0885fd48a0f84225) by [Florian Roth](https://x.com/cyb3rops/status/2073001710377734393).
> Nextron Research confirms the Lazarus-linked npm supply chain campaign is ongoing, with new packages using fresh JSONKeeper URLs and C2 infrastructure dropping and executing payloads via Node.


<details markdown="1">
<summary>More this week (10)</summary>

- [Using #Helm and #Kubernetes in your CI/CD pipeline? An attacker only needs access to the values.yaml file to compromise your cluster. Recent research ...](https://www.synacktiv.com/en/publications/charting-your-way-in-helm-template-injection) by [Synacktiv](https://x.com/Synacktiv/status/2071590009094668304).
- [I somehow missed out on the latest big Tor update for our # DefCon .onion server. I'm in the process of upgrading. https:// gitlab.torproject.org/tpo/core /tor/-/raw/tor-0.4.9.11/ChangeLog # Tor # Pri](https://gitlab.torproject.org/tpo/core/tor/-/raw/tor-0.4.9.11/ChangeLog).
- [RT The Hacker News: A new #Linux kernel exploit (CVE-2026-46331) gets root without modifying a single file on disk. It poisons the cached copy of...](https://thehackernews.com/2026/06/new-linux-pedit-cow-exploit-enables.html) by [Simone Margaritelli](https://x.com/evilsocket/status/2070559207976231312).
- [RT REcon: For those who are looking for talk slides you can find them in schedules for the speaker who have uploaded their slides https://cfp.recon.cx...](https://cfp.recon.cx/recon-2026/schedule) by [hasherezade](https://x.com/hasherezade/status/2071239817099170065).
- [RT hacker.house: Wild things going on at the water coolers of @HuntressLabs this week. According to a former employee, an insider threat has been tipp...](https://x.com/kmkz_security/status/2072949320907735082) by kmkz.
- [RT VulnCheck: VulnCheck recently disclosed CVE-2026-53805, an NVIDIA GEN3C inference API flaw that could let unauthenticated attackers run code on vul...](https://www.vulncheck.com/blog/nvidia-gen3c-unauth-pickle-rce) by [kmkz](https://x.com/kmkz_security/status/2072452303634698249).
- [Dawg, the Peter Stokes affadavit (nerd from Scattered Spider who was arrested) is fucked This dude was on Snapchat sending people pictures of him with...](https://x.com/vxunderground/status/2072725773367074823) by vx-underground.
- [RT SEKTOR7 Institute: Analysis of how IPv6 auto-configuration enables MITM6 and NTLM relay for domain compromise. A post by @RESecurity Source: https:...](https://www.resecurity.com/blog/article/mitm6-ntlm-relay-how-ipv6-auto-configuration-leads-to-full-domain-compromise) by [Steven Lowson](https://x.com/StevoLowson/status/2073364447070998731).
- [RT Ayush Anand: If you detect Advanced IP Scanner, stop treating it like “just recon.” It often means the attacker already has an interactive deskto...](https://x.com/SwiftOnSecurity/status/2073061248313249996) by SwiftOnSecurity.
- [RT vx-underground: > Peter Stokes > Scattered Spider guy > Arrested > Microsoft helps FBI > Read court documents > Page 12 > Microsoft tracks Stokes f...](https://x.com/cyb3rops/status/2073512089843306874) by Florian Roth.

</details>


## Techniques and Write-ups

- [FBI Seizes NetNut Proxy Platform and Popa Botnet](https://krebsonsecurity.com/2026/07/fbi-seizes-netnut-proxy-platform-popa-botnet).
> FBI seizes hundreds of domains associated with NetNut, a residential proxy service operated by Israeli company Alarum Technologies, connected to the 2-million-device Popa botnet.

- [gluegate: Proxy Memory Allocation Through Firefox's Signed mozglue.dll](https://github.com/sbousseaden/gluegate) by [Samir](https://x.com/SBousseaden/status/2070213318397317373).
> Routes memory allocation APIs through Firefox's signed mozglue.dll so the allocating module appears as a trusted Firefox component. Includes detection guidance.

- [FreeBSD Local Root and ASLR Bypass Found with LLM Assistance](https://www.freebsd.org/security/advisories/FreeBSD-SA-26:39.execve.asc) by [Synacktiv](https://x.com/Synacktiv/status/2072596705145418191).
> Synacktiv pointed a local LLM at FreeBSD and found a local root exploit plus an ASLR bypass on SUID binaries. Both now patched as CVE-2026-49415 and CVE-2026-49414.

- [Pre-Auth RCE in Argo CD via Helm Chart Misconfiguration](https://www.synacktiv.com/en/publications/caught-in-the-octopus-trap-unauthenticated-rce-in-argo-cd-with-codeql) by [Synacktiv](https://x.com/Synacktiv/status/2072333695088751078).
> Synacktiv demonstrates how a single Helm chart misconfiguration leads to full Kubernetes cluster compromise through unauthenticated RCE in Argo CD, found using CodeQL.

- [Adobe ColdFusion CVE Bonanza (APSB26-68)](https://labs.watchtowr.com/its-37oc-and-all-we-can-think-about-is-coldfusion-adobe-coldfusion-security-bulletin-apsb26-68-cve-bonanza) by [/r/netsec](https://x.com/_r_netsec/status/2072722741422436634).
> watchTowr dissects a batch of CVEs in Adobe ColdFusion from security bulletin APSB26-68, with detailed root cause analysis.

- [DuneSlide: Zero-Click Prompt Injection to RCE in Cursor IDE](https://www.catonetworks.com/blog/duneslide-two-critical-rce-vulnerabilities) by [/r/netsec](https://x.com/_r_netsec/status/2072356578423099811).
> Two critical RCE vulnerabilities in the Cursor IDE allow zero-click exploitation through prompt injection, turning an AI code editor into a remote code execution vector.

- [LLM-Powered EDR Analysis: Extracting Local Rulesets and YARA Rules](https://specterops.io/blog/2026/06/29/llm-powered-edr-analysis) by [Adam Chester](https://x.com/_xpn_/status/2071701942821081586).
> SpecterOps demonstrates how simple LLM harnesses can extract EDR rulesets, YARA rules, and behavioral detections from local endpoint agents. The barrier to reverse-engineering defensive tooling just dropped to a single prompt.

- [Pre-Auth RCE in Progress Kemp LoadMaster (CVE-2026-8037)](https://labs.watchtowr.com/enterprise-tech-i) by [Piotr Bazydło](https://x.com/chudyPB/status/2071850578012156381).
> watchTowr analyzes CVE-2026-8037, an uninitialized heap vulnerability in Progress Kemp LoadMaster that leads to pre-authentication remote code execution.

- [Tradecraft Garden: Cobalt Strike Creator Publishes Evasion Tradecraft Openly](https://tradecraftgarden.org/) by [hasherezade](https://x.com/hasherezade/status/2071979536166588431).
> Raphael Mudge returned to the industry and is publishing evasion tradecraft openly. Crystal Palace provides position-independent code, binary transformation, register randomization, and a PICO convention for reusable tradecraft modules.

- [Time Travel Debugging MCP Server for Reverse Engineering](https://specterops.io/blog/2026/06/26/time-travel-debugging-with-codex) by [Chihuahua in charge NotMe](https://x.com/jessefmoore/status/2071327721125519792).
> SpecterOps releases a Time Travel Debugging MCP server for Windows, enabling LLM-powered reverse engineering workflows through recorded execution traces.

- [CitrixBleed 2.0: Pre-Auth Memory Overread in Citrix NetScaler (CVE-2026-8451)](https://labs.watchtowr.com/citrixbleed-to-infinity-and-beyond-citrix-netscaler-pre-auth-memory-overread-cve-2026-8451) by [kmkz](https://x.com/kmkz_security/status/2072054651189428672).
> watchTowr identified and disclosed a zero-day memory overread in Citrix NetScaler appliances. Patches now available. If you run NetScaler, patch immediately.

- [Harden Windows Security: Comprehensive Hardening App Hits App Store](https://hotcakex.github.io/) by [SwiftOnSecurity](https://x.com/SwiftOnSecurity/status/2073505197347746113).
> CyberCakeX's Harden Windows Security app has matured into a full-featured hardening platform, now available on the Microsoft Store. Described as "$250k cyber consultant advice" for home users.

- [CrowdStrike Bypass via Certreq and AD-CS for Local Privilege Escalation](https://www.abdulmhsblog.com/posts/iammachine) by [Arun](https://x.com/dazzyddos/status/2073421222378123460).
> A new method to escalate privileges from a Microsoft Virtual Account using only certreq (a LoLBin) and AD-CS, successfully bypassing CrowdStrike without potato-class exploits.

- [Apache ActiveMQ RCE Bypass on Fully Patched 6.2.5](https://www.crowdfense.com/apache-activemq-rce-bypass) by [kmkz](https://x.com/kmkz_security/status/2073134634133496002).
> Crowdfense chains two bypasses into a fresh RCE on fully patched Apache ActiveMQ 6.2.5 on Windows via WebDAV, found while researching CVE-2026-34197.

- [France to Stop Certifying Non-Quantum-Safe Encryption](https://www.schneier.com/blog/archives/2026/07/france-to-stop-certifying-non-quantum-safe-encryption.html) by Bruce Schneier.
> France's ANSSI will halt certification of security products lacking quantum-resistant encryption, forcing government bodies and critical infrastructure operators to migrate.


<details markdown="1">
<summary>More this week (113)</summary>

- [The email provider Securence (US Internet, now owned by a joint venture between T-Mobile and KKR) has disabled its administrative portal for a week now, although email is still flowing. The company wo](https://krebsonsecurity.com/2024/02/u-s-internet-leaked-years-of-internal-customer-emails).
- [zlib bugs?! We're all gonna die before that gets patched everywhere. https:// blog.trailofbits.com/2026/07/0 2/field-reports-from-patch-the-planet/](https://blog.trailofbits.com/2026/07/02/field-reports-from-patch-the-planet).
- [Migrated my blog and published a new post. It covers a common type confusion vulnerability pattern I found last year in RPC servers. I don’t think th...](https://whereisk0shl.top/post/From%20context_handle%20to%20type%20confusion) by [k0shl](https://x.com/KeyZ3r0/status/2070342306612556154).
- [RT Armadin: Claude Cowork runs agent tasks in a local Linux VM. From a host foothold, Armadin's red team sideloaded into the signed claude.exe, recons...](https://www.armadin.com/blog-posts/exploiting-root-execution-in-claude-coworks-sandbox) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2072546321014079601).
- [RT Adnan Khan: There is an unpatched #GitHub privesc #0day actively exploited right now that allows dumping Actions secrets/OIDC abuse without workflo...](https://github.blog/changelog/2026-06-18-control-who-and-what-triggers-github-actions-workflows) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2070556431175045128).
- [Interesting food for thought concerning payload dev... Same basic unsigned console app (calls MessageBoxA and exits): - Left: Compiled w/ mingw-gcc - ...](https://x.com/Octoberfest73/status/2072696703019602254) by Octoberfest7.
- [PowerVR: virtual/physical unit confusion in DevmemIntComputeVirtualIndicesFromLogical() leads to OOB kernel write https://project-zero.issues.chromium...](https://project-zero.issues.chromium.org/issues/488368218) by [Project Zero Bugs](https://x.com/ProjectZeroBugs/status/2071533844914929759).
- [Quick Assist is a built-in Windows remote support tool that's increasingly abused in social engineering campaigns. Because it's installed by default o...](https://github.com/elastic/detection-rules/blob/main/rules/windows/command_and_control_quick_assist_fullcontrol_sharing.toml) by [Samir](https://x.com/SBousseaden/status/2072342329558540558).
- [I could not find source code so I asked my friend Claude to create some code for this to better understand it. https://github.com/S3cur3Th1sSh1t/Kassa...](https://github.com/S3cur3Th1sSh1t/Kassa) by [S3cur3Th1sSh1t](https://x.com/ShitSecure/status/2072299046207635529).
- [Essential. There is a sub 1% population of networks for this isn't just an instant win for them if you're not using LAPS.](https://lithnet.io/products/access-manager) by [SwiftOnSecurity](https://x.com/SwiftOnSecurity/status/2072750724983755137).
- [RT crep1x: Together with @yeswehack and @plebourhis, we documented a campaign targeting vulnerability researchers, pen-testers, and possibly cybercrim...](https://www.sekoia.com/blog/dont-eat-the-chocopocs-how-vulnerability-researchers-were-repeatedly-targeted-by-trojanised-exploits) by [SwitHak ()](https://x.com/SwitHak/status/2072711605066907675).
- [RT Rem: I get to be that guy again! @HuntressLabs has once again observed a large influx of successful malicious authentications against SonicWall SSL...](https://x.com/SwitHak/status/2072784899883270260) by SwitHak ().
- [Effective July 14, 2026, Adobe is moving from monthly to twice-monthly2⃣ publication of Adobe Security Bulletins and Advisories...](https://blog.adobe.com/security/protecting-customers-faster-how-adobe-is-responding-to-ai-accelerated-vulnerability-discovery) by [SwitHak ()](https://x.com/SwitHak/status/2072079285146530092).
- [RT CISA Cyber: Russian Intelligence Services cyber threat actors are conducting phishing campaigns on commercial messaging apps. Read our updated PSA ...](https://go.dhs.gov/5xh) by [SwitHak ()](https://x.com/SwitHak/status/2070554103122423904).
- [Kindle research, exploitation methodology, and jailbreak development. Missed @_leHACK_? @SidewayRE's talk, "Bootstrapping Kindle Research for the...](https://www.synacktiv.com/sites/default/files/2026-06/bootstrapping_kindle_research_lehack_2026.pdf) by [Synacktiv](https://x.com/Synacktiv/status/2071889118754144506).
- [Been working on this post for a few weeks, here's the second part of my LLM/AI-Assisted work flow series looking at harnesses and how they're designed...](https://blog.zsec.uk/harnessing-harnesses) by [Andy Gill](https://x.com/ZephrFish/status/2070873231372775611).
- [FIFA was saved this time https://bobdahacker.com/blog/fifa-hack](https://bobdahacker.com/blog/fifa-hack) by [/r/netsec](https://x.com/_r_netsec/status/2072718966464950439).
- [Detecting Agentic AI Threats in Claude: Sigma Rules and Correlation Detections for the Execution Layer https://www.papermtn.co.uk/detecting-agentic-th...](https://www.papermtn.co.uk/detecting-agentic-th) by [/r/netsec](https://x.com/_r_netsec/status/2072375451763487219).
- [Privilege escalation to root in Lima QEMU guests via a world-writable agent socket (CVE-2026-53657) https://syntetisk.tech/blog/posts/privilege-escala...](https://syntetisk.tech/blog/posts/privilege-escala) by [/r/netsec](https://x.com/_r_netsec/status/2072311278459367704).
- [Symfony YAML Security Audit - Shielder https://www.shielder.com/blog/2026/06/symfony-yaml-security-audit/](https://www.shielder.com/blog/2026/06/symfony-yaml-security-audit) by [/r/netsec](https://x.com/_r_netsec/status/2072303730654118387).
- [Trusted by NVIDIA, Amazon and Banks, This Extension Let Any Website run a drive-by RCE. CVSS 9.3 https://amibeingpwned.com/blog/signer-digital-rce](https://amibeingpwned.com/blog/signer-digital-rce) by [/r/netsec](https://x.com/_r_netsec/status/2071922466935677191).
- [Auditing OpenReception: 16 CVEs in an end-to-end encrypted appointment booking platform (unauthenticated admin creation, account takeover, E2E bypass)...](https://moltenbit.net/posts/auditing-openreception) by [/r/netsec](https://x.com/_r_netsec/status/2071899817882865969).
- [RT Cisco Talos Intelligence Group: Malware authors often hide their tracks using COM, but our latest guide provides the roadmap you need to decode tho...](https://cs.co/6014BDgbFs) by [Arris Huijgen](https://x.com/bitsadmin/status/2071312544543781099).
- [RT Abdul Mhanni: Wrote a new blog about caveats with tools detecting(or mis detecting) relay exploit primitives against http(ESC8) and MSSQL endpoints...](https://www.abdulmhsblog.com/posts/pitfallswithepa) by [Arris Huijgen](https://x.com/bitsadmin/status/2071311812058878273).
- [RT International Cyber Digest: Re Link: https://blog.otterpwn.com/projects/heavener](https://blog.otterpwn.com/projects/heavener) by [bohops](https://x.com/bohops/status/2071222786370994410).
- [New blog by my colleagues Dave (@johnnyspandex) and Adam: Microsoft Graph API - Hidden Exclusions with Overly Scoped Permissions https://blog.amb...](https://blog.amberwolf.com/blog/2026/june/microsoft-graph-api---hidden-exclusions-with-overly-scoped-permissions) by [Rich Warren](https://x.com/buffaloverflow/status/2069878871080481114).
- [RT @MalwareBibleJP: EDRのテーブル完全性チェックをすり抜けるWindowsプロセスインジェクション手法が公開されています。従来手法がPEB(Process-Environment-Bl...](https://x.com/cyb3rops/status/2072750551771578411) by Florian Roth.
- [RT Zscaler ThreatLabz: Zscaler ThreatLabz has identified malicious websites that use indirect prompt injection (IPI) attacks to manipulate AI agents. ...](https://www.zscaler.com/blogs/security-research/indirect-prompt-injection-web-content-targets-ai-agents) by [Florian Roth](https://x.com/cyb3rops/status/2072750633988354396).
- [RT Eyal Sela: n4d is an active exploitation campaign that installs an implent on internet-exposed MCP endpoints that provide code execution tools. The...](https://x.com/cyb3rops/status/2072686694566961407) by Florian Roth.
- [RT BleepingComputer: CISA: Microsoft SharePoint RCE flaw now actively exploited https://www.bleepingcomputer.com/news/security/cisa-microsoft-sharepoi...](https://www.bleepingcomputer.com/news/security/cisa-microsoft-sharepoi) by [Florian Roth](https://x.com/cyb3rops/status/2072686878529089735).
- [RT blackorbird: Attackers systematically query LLMs to probe which fake domain names the models are most prone to generating for target brands. This p...](https://x.com/cyb3rops/status/2072551211853594867) by Florian Roth.
- [RT BleepingComputer: FortiBleed credential-theft campaign linked to Lynx ransomware https://www.bleepingcomputer.com/news/security/fortibleed-credenti...](https://www.bleepingcomputer.com/news/security/fortibleed-credenti) by [Florian Roth](https://x.com/cyb3rops/status/2072551793800659252).
- [RT Expel: The Gentlemen ransomware, in a BYOVD attack, used a zero-day exploit to kill EDRs before deploying their payload. The driver they abused was...](https://x.com/daveaitel/status/2072717955163476035) by Dave Aitel.
- [RT itszn: We found another exploitable V8 JIT bug CVE-2026-14431; fixed in the most recent Chrome update This one was an interesting case of sloppy mo...](https://x.com/daveaitel/status/2072588150380044686) by Dave Aitel.
- [RT SpecterOps: Testing an LLM once is easy. Testing it consistently is harder. Neeraj Gupta's latest GhostWorks research introduces Jailbreaker, an op...](https://ghst.ly/4gdCHk1) by [Matt Nelson](https://x.com/enigma0x3/status/2071703118883020921).
- [Flock Cameras Can Surveil Cars Without License Plates](https://www.schneier.com/blog/archives/2026/07/flock-cameras-can-surveil-cars-without-license-plates.html) by Bruce Schneier.
- [RT International Cyber Digest: ‼ BREAKING: Apple's Hide My Email lets almost anyone uncover the real address behind a "hidden" alias, and Apple has...](https://x.com/evilsocket/status/2072284511631499323) by Simone Margaritelli.
- [Carnage. LOL.](https://github.com/WICG/declarative-partial-updates/blob/main/patching-explainer.md) by [Gareth Heyes \u2028](https://x.com/garethheyes/status/2073016922761802149).
- [Not only NFC-Laboratory, @Jose4Vi is also playing with Emulation, take a look at his other project: https://github.com/josevcm/hce-laboratory](https://github.com/josevcm/hce-laboratory) by [Benjamin Delpy](https://x.com/gentilkiwi/status/2072675797786132957).
- [RT Jonathan Bar Or (JBO) 🇮🇱🇺🇸🇺🇦: Made a thing - Arbitrary Code Execution in Sid Meier's Civilization! https://github.com/yo-yo-yo-jb...](https://github.com/yo-yo-yo-jb) by [Gergely Kalman](https://x.com/gergely_kalman/status/2073010736943509544).
- [RT cr3ghost: Orange Tsai found hidden character transformations buried in Windows ANSI encoding that most applications have no idea exist. WorstFit ex...](https://blog.orange.tw/posts/2025-01-worstfit-unveiling-hidden-transformers-in-windows-ansi) by [Gergely Kalman](https://x.com/gergely_kalman/status/2071902399845839167).
- [RT Check Point Research: Can a website turn into ransomware on Android? We found an AI-generated malware sample that suggests the answer is closer to ...](https://research.checkpoint.com/2026/browser-only-ransomware-from-llm-hallucinations-to-a-practical-attack-technique) by [hasherezade](https://x.com/hasherezade/status/2072296439254769913).
- [RT Thomas Roccia : FuzzingLabs has created a curated repo of offensive MCP servers you can wire to your agents! https://github.com/FuzzingLab...](https://github.com/FuzzingLab) by [hasherezade](https://x.com/hasherezade/status/2072364597466575144).
- [RT YungBinary: New blog is out! Digging into an obfuscating compiler used in building EKZ Stealer, a CLI-based infostealer delivered after a Fortinet ...](https://www.esentire.com/blog/fortinet-vulnerability-cve-2026-35616-and-ekz-stealer-attacking-obfuscating-compilers-with-binary-ninja-workflows) by [hasherezade](https://x.com/hasherezade/status/2072297396529176902).
- [RT cr3ghost: Satoshi Tanda found bugs in Microsoft's own Hyper-V hypervisor and HVCI implementation as a by-product of learning how they work. Let tha...](https://x.com/hasherezade/status/2070473400607187042) by hasherezade.
- [RT dbugs: Analysis of the CVE-2026-45504 vulnerability in Microsoft Exchange that allows reading arbitrary files PT ID: PT-2026-47976 The article...](https://hawktrace.com/blog/CVE-2026-45504) by [batuu](https://x.com/int20z/status/2070515410898722900).
- [TABPE: A monthly Windows PE baseline dataset for Cyber-security researchers https://github.com/onhexgroup/TABPE](https://github.com/onhexgroup/TABPE) by [Panos Gkatziroulis](https://x.com/ipurple/status/2073088101782597893).
- [RT Swissky: Re @ipurple The official front-end is here https://swisskyrepo.github.io/PayloadsAllTheThings/](https://swisskyrepo.github.io/PayloadsAllTheThings) by [Panos Gkatziroulis](https://x.com/ipurple/status/2073010129260147163).
- [TEB, PEB and List of Loaded Modules https://proteqtum.com/posts/02-win-x64-shellcode-teb-peb_en/](https://proteqtum.com/posts/02-win-x64-shellcode-teb-peb_en) by [Panos Gkatziroulis](https://x.com/ipurple/status/2072822920364061136).
- [GadgetSniper - Scans PE32+ binaries for instruction sequences of the form "call X ; jmp qword ptr [non-volatile-reg]", the exact primitive needed to b...](https://github.com/ZakiPedio/GadgetSniper) by [Panos Gkatziroulis](https://x.com/ipurple/status/2072774831045542312).
- [skewrun - an Active Directory time discovery toolkit for Red Teams. Dynamically resolves the Domain Controller's time via network protocols (CLDAP, SM...](https://github.com/JVBotelho/skewrun) by [Panos Gkatziroulis](https://x.com/ipurple/status/2072764841765281841).
- [Read the description ⤵ https://github.com/n0qword/win32k-callback-detouring](https://github.com/n0qword/win32k-callback-detouring) by [Panos Gkatziroulis](https://x.com/ipurple/status/2072533567494660537).
- [An x64 BOF that enables the Chrome DevTools Protocol msedge.exe chrome.exe Talk: Modern Session Hijacking by Living off the DevTools Prot...](https://github.com/KingOfTheNOPs/CDP-Enable-BOF) by [Panos Gkatziroulis](https://x.com/ipurple/status/2072337709775913106).
- [RT 0x12 Dark Development: PEB Corruption: A Remote Process Crash Technique New Medium post, explores a direct approach to process termination: remote ...](https://medium.com/@s12deff/peb-corruption-a-remote-process-crash-technique-4b25f8887678) by [Panos Gkatziroulis](https://x.com/ipurple/status/2072075041206943905).
- [RT Nick VanGilder: Last night I added a new section to http://redteam.community called Books (https://www.redteam.community/books). The premise is sup...](https://www.redteam.community/books) by [Chihuahua in charge NotMe](https://x.com/jessefmoore/status/2071042002339447265).
- [RT Off-By-One Conference: Welcome Evangelos Daravigkas (@freddo_1337) & Ben Koo (@kiddo_pwn) of Team DDOS to @offbyoneconf! They present "No Time to P...](https://offbyone.sg/talk/evangelosdaravigkas-benkoo) by [kiddo](https://x.com/kiddo_pwn/status/2072198054388937029).
- ["Cohesity TranZman (formerly developed by Stone Ram) is a migration appliance used to transition, merge, or replatform enterprise backup environments"...](https://github.com/GregDurys/security-advisories/tree/main/cohesity-tranzman) by [kmkz](https://x.com/kmkz_security/status/2072941276958269685).
- [Zscaler ThreatLabz identified a new campaign in-the-wild, tracked as Operation Neusploit, targeting countries in the Central and Eastern European regi...](https://lnkd.in/ddNnNvXv) by [kmkz](https://x.com/kmkz_security/status/2072611618622488967).
- [RT Jλckλι: CVE-2026-6307 PoC + Report: [PoC]: https://github.com/J4ck3LSyN-Gen2/CVE-2026-6307-Longinus [Report]: https://github.com/J4ck3LSyN-Gen2/...](https://github.com/J4ck3LSyN-Gen2/CVE-2026-6307-Longinus) by [kmkz](https://x.com/kmkz_security/status/2072653933751742694).
- [RT dbugs: Container escape via IPv6 fragmentation bug in Linux kernel Researcher demonstrated PoC "IPV6_FRAG_ESCAPE" exploiting a memory-handling flaw...](https://github.com/sgkdev/ipv6_frag_escape) by [kmkz](https://x.com/kmkz_security/status/2072419608145924343).
- [RT 8kSec: This blog reverse-engineers how Apple's MIE works inside the iOS 26 kernel - hardware memory tagging that mitigates buffer overflows, UaF, a...](https://8ksec.io/mie-deep-dive-kernel) by [kmkz](https://x.com/kmkz_security/status/2072300930356154825).
- [RT Dark Web Informer: ‼ One POST to RCE: Unauthenticated Code Execution in Langflow (CVE-2026-33017) https://darkwebinformer.com/one-post-to-rce-un...](https://darkwebinformer.com/one-post-to-rce-un) by [kmkz](https://x.com/kmkz_security/status/2072277653181141388).
- [Maybe interesting...](https://dmpdump.github.io/posts/Backdoor_iKuai_Routers) by [MalwareHunterTeam](https://x.com/malwrhunterteam/status/2072755915992727861).
- [RT Karl: Here are the slides from our @WEareTROOPERS presentation - "Modern Adventures in Azure Privilege Escalation" This was a fantastic conference ...](https://notpayloads.blob.core.windows.net/slides/Azure_PrivEsc_Troopers-2026.pdf) by [Max](https://x.com/maxime_tz/status/2072681009888252067).
- [RT Kyle Meyer: As every bug bounty hunter and offensive security firm is building their own agentic testing platform… this is so massive](https://securitycontext.dev/) by [ProjectDiscovery](https://x.com/pdiscoveryio/status/2072619304504443144).
- [RT Marc Smeets: How the f can we still be having NTLM insecurities in the year 2026. Just how?! At this rate we will not be done with NTLM by 2033, mi...](https://securityonline.info/ntlm-reflection-cve-2026-24294) by [Rémi GASCOU (Podalirius)](https://x.com/podalirius_/status/2072678543251653077).
- [RT V12: And here's postgres bidirectional RCE no admin required, client infects server, server infects client](https://x.com/rdjgr/status/2073324898861064413) by Rick de Jager.
- [RT Doug Burks: Wireshark is a great tool but looking at traffic packet by packet can be overwhelming and you may lose the plot of the story. It's much...](https://github.com/dougburks/so-crates) by [thaddeus e. grugq](https://x.com/thegrugq/status/2072971770911703308).
- [RT Ionut Popescu: The mythos report for #curl 2026-05-06 made public: https://gist.github.com/bagder/c9b83a19f30e82e41b11f6315465b17a](https://gist.github.com/bagder/c9b83a19f30e82e41b11f6315465b17a) by [Vincent Yiu](https://x.com/vysecurity/status/2073521055235514872).
- ["Welcome to GoGatoZ - a purpose-built Go tool for GitLab CI/CD security auditing that can perform and automate the entire CI/CD kill chain." Read mor...](https://www.blackhillsinfosec.com/auditing-gitlab-the-ci-cd-kill-chain) by [Black Hills Information Security](https://x.com/BHinfoSecurity/status/2072772420092469754).
- [55.2% of respondents to Bitdefender's 2026 Cybersecurity assessment were instructed to keep silent when they should have contacted the authorities. "R...](https://thehackernews.com/2026/07/2026-cybersecurity-assessment-gap.html) by [Black Lantern Security (BLSOPS)](https://x.com/BlackLanternLLC/status/2072695984216293878).
- [ARToken PhaaS exposes EvilTokens' Microsoft 365 phishing toolkit https://www.bleepingcomputer.com/news/security/artoken-phaas-exposes-eviltokens-micro...](https://www.bleepingcomputer.com/news/security/artoken-phaas-exposes-eviltokens-micro) by [BleepingComputer](https://x.com/BleepinComputer/status/2073047924037054902).
- [we need this ... https://github.com/lautarovculic/ioscpy](https://github.com/lautarovculic/ioscpy) by [Dimitri Os](https://x.com/Ch0pin/status/2073074166283067801).
- [RT Enno Rey: Bitlocker downgrade attacks https://archives.pass-the-salt.org/Pass%20the%20SALT/2026/slides/PTS2026-TALK-13-bitlocker_talk_deck.pdf [PDF...](https://archives.pass-the-salt.org/Pass%20the%20SALT/2026/slides/PTS2026-TALK-13-bitlocker_talk_deck.pdf) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2073542707528491075).
- [Plex Explorer. learning aid for security researchers explaining Microsoft’s Dataverse plugin sandbox architecture, aka Plex. By @kidtronnix @WEareTRO...](https://github.com/beyondtrust/plex-explorer) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2073032447722127537).
- [RT Fabian Bader: Running Microsoft Defender for Endpoint on Linux? Then better wait with updating or manually re-enable and start it after the next re...](https://learn.microsoft.com/en-us/defender-endpoint/microsoft-defender-endpoint-releases) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2073032741281522141).
- [RT 𝕡𝕨𝕟𝕚𝕖: Windows has an undocumented kernel function called MiReadWriteVirtualMemory. It's what NtReadVirtualMemory and NtWriteVirtual...](https://x.com/DirectoryRanger/status/2072693970560332107) by DirectoryRanger.
- [RT spencer: I've spent a good portion of the last 2 days testing coercion attacks against Server 2025. It's holding up surprisingly well. IT Admins, i...](https://x.com/SwiftOnSecurity/status/2073111792213987763) by SwiftOnSecurity.
- [People concerned about Windows telemetry, might I recommend the Windows Restricted Traffic Limited Functionality Baseline: https://learn.microsoft.com...](https://learn.microsoft.com/en-us/windows/privacy/manage-connections-from-windows-operating-system-components-to-microsoft-services) by [winterknife](https://x.com/_winterknife_/status/2073800291074400354).
- [Matched an almost ten year old rule that I remember very well - everyone interested in the China Nexus should take a look at this sample](https://x.com/cyb3rops/status/2073835145056886980) by Florian Roth.
- [RT Smukx.E: how i ruined my vacation by reverse engineering wsc ! https://blog.es3n1n.eu/posts/how-i-ruined-my-vacation #reversing](https://blog.es3n1n.eu/posts/how-i-ruined-my-vacation) by [Florian Roth](https://x.com/cyb3rops/status/2073171472260989255).
- [If a vuln is publicly exploited and ends up in CISA’s KEV catalog, patching is only half the job!! We also need to know how to determine whether a se...](https://www.bleepingcomputer.com/news/security/cisa-microsoft-sharepoint-rce-flaw-now-actively-exploited) by [Florian Roth](https://x.com/cyb3rops/status/2072999596389793823).
- [RT dbugs: LDAP Ping as a blind spot in AD discovery Researchers from (@HuntressLabs, @4ndr3w6S) showed that using ".LDAP Ping" (also called ".cLDAP") ...](https://www.huntress.com/blog/ldap-active-directory-detection-part-six) by [Florian Roth](https://x.com/cyb3rops/status/2073094273008881849).
- [I've added performance/feature vectors to Shazzer. Along with stats. You can now see which browsers perform better. It uses the same shared fuzzing ne...](https://shazzer.co.uk/stats/performance) by [Gareth Heyes \u2028](https://x.com/garethheyes/status/2073364837824930087).
- [RT zhero;: Pleased to publish a browser-related research paper (w/@inzo____) titled: One trigram at a time: XSLeak via Universal CSS Injection and DoS...](https://zhero-web-sec.github.io/research-and-things/one-trigram-at-a-time-xsleak-via-universal-css-injection-and-dos-in-opera-) by [Gareth Heyes \u2028](https://x.com/garethheyes/status/2073084687359115332).
- [RT Martin Sohn Christensen: #TROOPERS26 afterglow: @4ndr3w6S on building a solid LDAP detection stack - why signature-based detection is failing and v...](https://x.com/harmj0y/status/2073150977189007723) by Will Schroeder.
- [RT r1cksec: A sleepmask based on Ekko that preserves unwind data at sleep time. https://github.com/kapla0011/InsomniacUnwinding #infosec #cybersecurit...](https://github.com/kapla0011/InsomniacUnwinding) by [hasherezade](https://x.com/hasherezade/status/2073807961894387725).
- [RT Pass the SALT Conference: ALL VIDEOS & SLIDES(*) ARE ONLINE Our video team & Ubicast friends are terrific, period! Videos: http...](https://passthesalt.ubicast.tv/channels) by [hasherezade](https://x.com/hasherezade/status/2073373212390339027).
- [Extend log analysis with Logistician 1.3 https://eclecticlight.co/2026/07/06/extend-log-analysis-with-logistician-1-3/ via @howardnoakley](https://eclecticlight.co/2026/07/06/extend-log-analysis-with-logistician-1-3) by [Howard Oakley, Eclectic Light Co](https://x.com/howardnoakley/status/2074018366054875481).
- [Hunting Sleeping Giants - Detecting Encrypted Beacon Sleep Obfuscation https://justruss.tech/index.php/2026/06/21/hunting-sleeping-giants-detecting-en...](https://justruss.tech/index.php/2026/06/21/hunting-sleeping-giants-detecting-en) by [Panos Gkatziroulis](https://x.com/ipurple/status/2073808449784197454).
- [Havoc C2 BOF port of the KslD.sys BYOVD technique. Credential extraction from lsass via physical memory, no OpenProcess, no auditable API calls https:...](https://github.com/Muz1K1zuM/kslkatz_bof) by [Panos Gkatziroulis](https://x.com/ipurple/status/2073736025071865918).
- [Exploring cross-domain & cross-forest RBCD: part 2 https://www.synacktiv.com/en/publications/exploring-cross-domain-cross-forest-rbcd-part-2](https://www.synacktiv.com/en/publications/exploring-cross-domain-cross-forest-rbcd-part-2) by [Panos Gkatziroulis](https://x.com/ipurple/status/2073699473016992145).
- [RT CodeX: Open sourcing another of my random BOFs that I think may be useful to people. Obtains location data, thats pretty much it. May be useful if ...](https://github.com/CodeXTF2/GeoLocation_BOF) by [Panos Gkatziroulis](https://x.com/ipurple/status/2073499130547028222).
- [Feature-rich single-binary file server for red teamers and developers. A powerful python3 -m http.server replacement HTTP/S WebDAV FTP/SFTP SM...](https://github.com/goshs-labs/goshs) by [Panos Gkatziroulis](https://x.com/ipurple/status/2073453283247554611).
- [ironcurtain - A secure runtime for autonomous AI agents, where security policy is derived from a human-readable constitution https://github.com/provos...](https://github.com/provos) by [Panos Gkatziroulis](https://x.com/ipurple/status/2073425330560221222).
- [Active Directory Post-Exploitation and Relay Automation Utilities https://github.com/JssNGC/harpyTools](https://github.com/JssNGC/harpyTools) by [Panos Gkatziroulis](https://x.com/ipurple/status/2073385392452088193).
- [Automatically deploying Mythic C2 in Azure using Terraform https://github.com/qmadev/tf-mythic-azure](https://github.com/qmadev/tf-mythic-azure) by [Panos Gkatziroulis](https://x.com/ipurple/status/2073297264299176132).
- [RT DirectoryRanger: MSFDefender: Metasploit Windows Modules Detonation & Analysis #DFIR https://bloo.io/blog/msfdefender-metasploit-windows-modules-de...](https://bloo.io/blog/msfdefender-metasploit-windows-modules-de) by [Chihuahua in charge NotMe](https://x.com/jessefmoore/status/2073783328227078442).
- [RT JS0N Haddix: Re https://arcanum-sec.github.io/ai-sec-resources/](https://arcanum-sec.github.io/ai-sec-resources) by [Chihuahua in charge NotMe](https://x.com/jessefmoore/status/2073449707259777334).
- [Remove the threat of certain LOLBAS based on analysis at @magicswordio from Mandiant, Red Canary, CrowdStrike vendors reports! https://www.magicsword....](https://www.magicsword.io/blog/the-top-10-techniques-havent-changed-in-a-decade) by [Chihuahua in charge NotMe](https://x.com/jessefmoore/status/2073116947479417221).
- [RT Smukx.E: Breaking eBPF Security: How Kernel Rootkits Blind Observability Tools TLDR:- Deep technical analysis of eBPF-based security solutions thro...](https://matheuzsecurity.github.io/hacking/ebpf-security-tools-hacking) by [kmkz](https://x.com/kmkz_security/status/2073859090938208626).
- [RT Florian Hansemann: ''CVE-2025-38352 (Part 1) - In-the-wild Android Kernel Vulnerability Analysis + PoC'' #infosec #pentest #redteam #blueteam https...](https://faith2dxy.xyz/2025-12-22/cve_2025_38352_analysis) by [kmkz](https://x.com/kmkz_security/status/2073773818904969427).
- [Is it only me or 2026 seems to be "the year of the path traversal vulns" ?](https://www.openwall.com/lists/oss-security/2026/07/04/8) by [kmkz](https://x.com/kmkz_security/status/2073754619507802328).
- [RT Open Source Security mailing list: CVE-2026-43503: Linux kernel: Analysis of the "DirtyClone" LPE (Dirty Frag family variant) https://www.openwall....](https://www.openwall.com/lists/oss-security/2026/07/02/1) by [kmkz](https://x.com/kmkz_security/status/2073667285336592751).
- [Fun story: #Apache patched a Tomcat padding oracle and shipped a worse bug doing it. #CVE-2026-29146: EncryptInterceptor defaults to AES/CBC/PKCS5, a ...](https://www.cyberkendra.com/2026/04/apache-tomcats-security-fix-opened-door.html) by [kmkz](https://x.com/kmkz_security/status/2073445849133117846).
- [RT bynario: Now that Canonical has fully patched CVE-2026-31694, we're sharing our code (along with a lil demo) for the FUSE LPE Source @ https:/...](https://github.com/BynarIO/pocs/tree/main/linux/cve-2026-31694) by [kmkz](https://x.com/kmkz_security/status/2073392011902603492).
- [Playing Around With ADIDNS RPC Internals https:// blog.paradoxis.nl/playing-arou nd-with-adidns-rpc-internals-0c59c15d0a15](https://blog.paradoxis.nl/playing-around-with-adidns-rpc-internals-0c59c15d0a15).
- [Windows Service - Playbook & Detection Strategies https:// ipurple.team/2026/07/06/window s-service/](https://ipurple.team/2026/07/06/windows-service).
- [This time @1ZRR4H looked at a possible interesting finding I gave him... turned out to be some botnet called N4D, but it is not some usual botnet it s...](https://x.com/malwrhunterteam/status/2073103603657523213) by MalwareHunterTeam.
- [RT : https://techcommunity.microsoft.com/blog/windows-itpro-blog/reducing-ntlm-dependency-iakerb-and-localkdc-in-windows-insider-preview/4524615 ...](https://techcommunity.microsoft.com/blog/windows-itpro-blog/reducing-ntlm-dependency-iakerb-and-localkdc-in-windows-insider-preview/4524615) by [Max](https://x.com/maxime_tz/status/2073497228790915162).
- [RT ret2src: Escalating from On-prem to Entra through MITM Attacks My colleague @0x64616e just published his latest research on lateral movement betwee...](https://securitylog.sva.de/2026/offsec/escalating-from-on-prem-to-entra-through-mitm-attacks) by [Max](https://x.com/maxime_tz/status/2073495154585985317).
- [RT William R. Messmer: You might notice a few changes if you update WinDbg from the store. For "attach to process", there is now a "Show processes fro...](https://x.com/maxime_tz/status/2073714524922789931) by Max.
- [RT Unrealisedd: Microsoft patched UnDefend (CVE-2026-45498) back in May but all they did was block one locking method. The actual root cause, permissi...](https://github.com/Unrealisedd/exploitarium/tree/main/defender-signature-lock-bypass) by [Max](https://x.com/maxime_tz/status/2074071821826064626).

</details>


## Tools and Exploits

- [CredSpy: Unauthenticated Microsoft Account Auth Method Enumeration](https://github.com/RedByte1337/CredSpy) by [Keanu Nys](https://x.com/RedByte1337/status/2072228723563061437).
> New open-source tool for unauthenticated enumeration of authentication methods on Microsoft accounts, revealing whether targets use passkeys, certificate auth, or passwordless push.

- [Disposable Tooling: LLM-Generated Mythic C2 Agents From Prompt to Deployment](https://specterops.io/blog/2026/06/24/disposable-tooling-building-llm-generated-mythic-agents-from-prompt-to-deployment) by [Chihuahua in charge NotMe](https://x.com/jessefmoore/status/2070895680412164379).
> SpecterOps built Oracle, a framework that generates, compiles, deploys, and QA-tests Mythic C2 agents autonomously across Python, Go, Zig, C#, and Rust. Every agent is unique and disposable.

- [Kali Linux 2026.2 Released](https://www.kali.org/blog/kali-linux-2026-2-release?amp%3Butm_medium=twitter) by [Kali Linux](https://x.com/kalilinux/status/2071629609049944499).
> Q2 release brings GNOME 50, KDE 6.6, new helper scripts, APT format changes, and VM boot tweaks.

- [Cutter 2.5 Released with Rizin 0.9.1](https://github.com/rizinorg/cutter/releases/tag/v2.5.0) by [Max](https://x.com/maxime_tz/status/2072373720589668410).
> Major release of the open-source reverse engineering platform adds config var preferences, searchable keybindings, debugging tooltips, and improved type management.

- [cargo-audit Now Checks If Your Code Actually Calls Vulnerable Functions](https://crates.io/crates/cargo-audit) by [Lee Chagolla-Christensen](https://x.com/tifkin_/status/2072790389241880725).
> Trail of Bits added binary-level reachability analysis to cargo-audit 0.22.2+. It checks whether vulnerable functions are actually called, labeling matches as "Affected" to separate real exposure from noise.

- [NOX: Modular Attack Surface Management Framework in Go](https://github.com/kernelstub/Nox) by [Florian Roth](https://x.com/cyb3rops/status/2073419998182162833).
> A modular ASM and vulnerability scanning framework with 299 built-in modules covering OSINT, subdomain enumeration, DNS, port scanning, web fingerprinting, and active security testing.

- [OpenUDC2: Open Source Cobalt Strike UDC2 Spec for C2 Interop](https://github.com/CodeXTF2/OpenUDC2) by [Panos Gkatziroulis](https://x.com/ipurple/status/2073433486916988980).
> Open-source implementation of the Cobalt Strike UDC2 spec, enabling open-source C2 frameworks to benefit from existing CS tooling. Ships with Adaptix PoC and drop-in UDC2 support.


<details markdown="1">
<summary>More this week (6)</summary>

- [How GitHub used secret scanning to reach inbox zero](https://github.blog/security/application-security/how-github-used-secret-scanning-to-reach-inbox-zero) by Natalie Guevara.
- [Brute Ratel 2.6 Catalyst is released and available for download. This version includes major changes to the Commander and Badger for various QOL and O...](https://x.com/NinjaParanoid/status/2070473328242930037) by Chetan Nayak (Brute Ratel C4 Author).
- [Binary Hardening released cfgrip v1.0.0 - PE/ELF x86/x64 control flow graph extractor. Resolves indirect branches through GOT, jump tables, register t...](https://github.com/BinaryHardening/cfgrip) by [x86byte](https://x.com/x86byte/status/2072663195458695261).
- [RT Armadin: MLOKit could already steal an enterprise's ML models and training data. Its new release runs code inside the infrastructure that builds th...](https://blackhat.com/us-26/arsenal/schedule) by [Sudheer Varma](https://x.com/0xpwnisher/status/2072947367548960999).
- [Friday @magicswordio Feature Share First party support of CLM-Forge and our (soon to be released) Magic-Atomics. Import from CLM-Forge||Magic-Ato...](https://github.com/magicsword-io/CLM-Forge) by [The Haag™](https://x.com/M_haggis/status/2073140364022849847).
- [RT The Vertex Project: Synapse 3.0 Beta is now available! Built on 10+ years of analyst feedback, Synapse 3.0 introduces a redesigned data model,...](https://vertex.link/synapse-v3) by [visi stark](https://x.com/invisig0th/status/2072305824723096059).

</details>



