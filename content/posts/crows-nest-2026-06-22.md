---
title: "Crow's Nest - 2026-06-22"
date: 2026-06-22T00:00:00+00:00
draft: false
tags: ["roundup"]
---

A roundup of 126 items curated from across the security community.

## News

- [Mastra-AI npm Supply Chain Attack Hits 80+ Packages](https://x.com/HackingDave/status/2067233153459106140) by Dave Kennedy.
> An attacker hijacked npm accounts to inject a phantom dependency into 80+ Mastra-AI packages. The malicious payload arrived via a "dayjs" typosquat that ran a post-install script to download and execute a remote binary.

- [Operation Endgame Dismantles SocGholish Infrastructure](https://www.proofpoint.com/us/blog/threat-insight/sayonara-socgholish-operation-endgame-disrupts-major-cybercrime-operation?amp%3Butm_medium=social_organic) by [SwitHak ()](https://x.com/SwitHak/status/2067866513571246159).
> International law enforcement took down 100 servers and domains, remediating nearly 15,000 websites. SocGholish's "FakeUpdates" web inject framework has been a persistent ransomware delivery vector since 2018.

- [Splunk Enterprise RCE Added to CISA KEV](https://socradar.io/blog/cve-2026-20253-cisa-splunk-enterprise-rce) by [kmkz](https://x.com/kmkz_security/status/2068362247869497439).
> CVE-2026-20253, a CVSS 9.8 unauthenticated file write flaw with a public exploit chain leading to RCE, is now confirmed actively exploited. Patch to Splunk 10.0.7 or 10.2.4 immediately.


<details markdown="1">
<summary>More this week (7)</summary>

- [Flock Cameras Are Being Used for Stalking](https://www.schneier.com/blog/archives/2026/06/flock-cameras-are-being-used-for-stalking.html) by Bruce Schneier.
- [Ethical hacker Could've Rickrolled the Entire FIFA World Cup. All he Needed Was his ID https://bobdahacker.com/blog/fifa-hack](https://bobdahacker.com/blog/fifa-hack) by [Nicolas Krassas](https://x.com/Dinosn/status/2067201444697211211).
- [RT Mandiant (part of Google Cloud): PRC-nexus actor UNC6508 targeted North American research, exploiting REDCap servers to deploy INFINITERED malware....](https://cloud.google.com/blog/topics/threat-intelligence/prc-targets-us-medical-research) by [SwitHak ()](https://x.com/SwitHak/status/2066776446584901802).
- [Texas govt data breach exposes over 3 million driver’s licenses https://www.bleepingcomputer.com/news/security/texas-govt-data-breach-exposes-over-3-...](https://www.bleepingcomputer.com/news/security/texas-govt-data-breach-exposes-over-3-) by [BleepingComputer](https://x.com/BleepinComputer/status/2068004108070535616).
- [Nintendo America Employee Data Exposed After Shadowbyt3$ Targets TinyPulse https://hackread.com/nintendo-america-employee-data-shadowbyt3-tinypulse/](https://hackread.com/nintendo-america-employee-data-shadowbyt3-tinypulse) by [Nicolas Krassas](https://x.com/Dinosn/status/2068001095545200706).
- [RT International Cyber Digest: ‼ BREAKING: A breach at competitive-intelligence platform Klue let attackers steal OAuth tokens and pull Salesfo...](https://x.com/Dinosn/status/2068002851658326141) by Nicolas Krassas.
- [RT Katie Knowles: What's an Agent ID compromise look like? This post shows how compromise of a blueprint can lead to compromise of ALL its agents...](https://securitylabs.datadoghq.com/articles/agent-id-inside-agent-compromise) by [Nick Frichette](https://x.com/Frichette_n/status/2067621712800141564).

</details>


## Techniques and Write-ups

- [Twelve Bytes to Escape the Browser Sandbox](https://core-jmp.org/2026/06/cve-2026-40369-twelve-bytes-browser-sandbox-es) by [Dominic Chell](https://x.com/domchell/status/2067353797073011083).
> CVE-2026-40369 turns a minimal 12-byte controlled write into a full browser sandbox escape. The writeup walks through the exploit chain from renderer compromise to arbitrary code execution outside the sandbox.

- [Ivanti Sentry: Command Injection and Auth Bypass Chain](https://dbugs.ptsecurity.com/vulnerability/CVE-2026-10523) by [kmkz](https://x.com/kmkz_security/status/2067337263369887907).
> CVE-2026-10520 and CVE-2026-10523 chain an unauthenticated OS command injection with an authentication bypass in Ivanti Sentry. Together they give remote attackers full system-level code execution without credentials.

- [From ISP Router to Kernel RCE via MediaTek WPS Driver](https://hacefresko.com/posts/rce-on-isp-router-and-mediatek-0day) by [scriptjunkie (Matt)](https://x.com/scriptjunkie1/status/2067448567115944348).
> CVE-2026-20452 is a heap overflow in MediaTek's WPS kernel driver. The writeup covers the full journey from initial router recon through command injection to unauthenticated kernel-level code execution.

- [FreeBSD kTLS Page-Cache Write: A Dirty Pipe Analogue](https://www.openwall.com/lists/oss-security/2026/06/10/20) by [Solar Designer](https://x.com/solardiz/status/2067477460933820899).
> CVE-2026-45257 exploits in-place AES-GCM decryption in FreeBSD's kTLS-RX path to write into the page cache and escalate to local root. The bug mirrors Linux's Dirty Pipe, was introduced around 2020, and shipped in FreeBSD 13.0.

- [First Public KVM/arm64 Guest-to-Host Escape](https://openwall.com/lists/oss-security) by [Solar Designer](https://x.com/solardiz/status/2067477410296054234).
> CVE-2026-46316 allows a guest VM to execute commands on the host with kernel privileges. Believed to be the first publicly documented guest-to-host escape exploit targeting KVM on ARM64. Full exploit attached to the oss-security post.

- [Unpatched NTLM Leak in Windows search: URI Handler](https://www.huntress.com/blog/unpatched-ntlm-leak-windows-search-uri-handler) by [Dave Kennedy](https://x.com/HackingDave/status/2068085352523293176).
> The NTLM leakage primitive in the Windows search: URI handler is identical in mechanism and severity to CVE-2026-33829 in the Snipping Tool. Microsoft closed the report without issuing a CVE or patch.

- [Squidbleed: Heartbleed-style Memory Leak in Squid Proxy](https://blog.calif.io/p/squidbleed-cve-2026-47729) by [/r/netsec](https://x.com/_r_netsec/status/2067917327111504130).
> CVE-2026-47729 leaks internal memory from every version of Squid Proxy in its default configuration. The vulnerability is a Heartbleed analogue, letting remote attackers read arbitrary server memory without authentication.

- [Langflow Multi-CVE Exploit Kit: Path Traversal to RCE](https://x.com/kmkz_security/status/2068455026553389478) by kmkz.
> Three Langflow vulnerabilities chained together: a path traversal (CVE-2026-7524), a lambda eval (CVE-2026-7700), and a CodeParser command injection (CVE-2026-7687). The exploit kit uses symlink-based archive extraction to drop webshells for persistent RCE.

- [nginx-quicburst: RCE in Nginx QUIC (CVE-2026-42530)](https://x.com/mrgretzky/status/2068267739760750699) by Kuba Gretzky.
> A use-after-free in the QPACK encoder of nginx's HTTP/3 stack gives remote code execution. Only the third nginx vulnerability since 2014 to receive the project's "major" severity rating. Upgrade if you run Nginx 1.31 with QUIC enabled.

- [Eight Kernel Driver LPE Vulnerabilities Found with LLM Assistance](https://x.com/senzee1984/status/2068475267102752988) by Winslow.
> A researcher used LLM-assisted analysis to discover eight credited local privilege escalation vulnerabilities across Windows kernel drivers, all now with assigned CVEs.


<details markdown="1">
<summary>More this week (91)</summary>

- [RT 7h3h4ckv157: Kernel-Exploit-Dojo Curated archive of 100+ Linux kernel exploitation CTF challenges, organized by bug class, exploitation primit...](https://github.com/mito753/Kernel-Exploit-Dojo) by [X-C3LL](https://x.com/TheXC3LL/status/2066634088786583994).
- [SearchLeak: How We Turned M365 Copilot Into a One-Click Data Exfiltration Weapon https://www.varonis.com/blog/searchleak](https://www.varonis.com/blog/searchleak) by [/r/netsec](https://x.com/_r_netsec/status/2066516848246673745).
- [RT Brian in Pittsburgh: So, we need to figure out what is going on with CVE-2026-41089, the Netlogon vulnerability that Microsoft patched in May and t...](https://x.com/daveaitel/status/2066132905491882482) by Dave Aitel.
- [https://maorsabag.github.io/posts/adaptix-stealthpalace/sleeping-beauty-ii/](https://maorsabag.github.io/posts/adaptix-stealthpalace/sleeping-beauty-ii) by [HackerRalf](https://x.com/hacker_ralf/status/2066175175620493361).
- [RT Csaba Fitzl: Big changes to user TCC.db in macOS Golden Gate! It seems that it finally got the protection it deserves. It was moved to: /p...](https://x.com/howardnoakley/status/2066472942238671282) by Howard Oakley, Eclectic Light Co.
- [HallWatch - User-mode detector that catches indirect syscalls. Traps Hell's Hall, Tartarus' Gate, RecycledGate, and VEH syscalls & Many more https://g...](https://github.com/Zypherion-Technologies/HallWatch) by [Panos Gkatziroulis](https://x.com/ipurple/status/2066749594906595628).
- [RT kl_secservices: Recent TOCTOU vulnerability in PackageKit allows attackers to escalate privileges to root. The vulnerability, Pack2TheRoot (CVE-202...](https://purpleshift.io/purple/2026-06-09-rsgr) by [kmkz](https://x.com/kmkz_security/status/2066773549554053413).
- [RT : https://labs.infoguard.ch/posts/ghost-sender/ "When an organisation uses Exchange Online (or on-premises exchange in hybrid mode) with a thir...](https://labs.infoguard.ch/posts/ghost-sender) by [Max](https://x.com/maxime_tz/status/2066549869569847613).
- [RT Gergely Kalman: Here's the exploit of a new Full TCC bypass @theevilbit and I just found. It's also the demonstration of a new technique we can't s...](https://x.com/theevilbit/status/2066580972871549278) by Csaba Fitzl.
- [RT Rishi: CVE-2026-53435, a high severity (CVSS 8.8) deserialization vulnerability in Jenkins is now seeing active exploitation as per @DefusedCy...](https://github.com/rxerium/rxerium-templates/blob/main/2026/CVE-2026-53435.yaml) by [Vincent Yiu](https://x.com/vysecurity/status/2066846692524294248).
- [RT Nightmare Eclipse: I'm back (maybe), new drip (blog), got some interesting stuff that might be worth reading, https://blog.projectnightcrawler.dev/...](https://blog.projectnightcrawler.dev/posts/2026-06-15-some-updates-about-my-current-plans-and-more-about-the-recent-defender-exploits-rogueplanet-redsun-bluehammer) by [sailay(valen)](https://x.com/404death/status/2066695108951728520).
- ["[This] means these vulnerabilities remain present in both Windows 10 and 11 as a “forever-day” – an exploitable vulnerability that the software ve...](https://www.blackhillsinfosec.com/proxy-execution-via-webview2) by [Black Hills Information Security](https://x.com/BHinfoSecurity/status/2066959051347333551).
- [Last week Stephan Borosh gave us a live demo on a ClickOnce-based Command-and-Control (C2) framework. ClickOnce Commander is a powerful new tool for p...](https://www.youtube.com/watch?v=acijx_Tb5DU&amp%3Bt=266s) by [Black Hills Information Security](https://x.com/BHinfoSecurity/status/2066595660326109542).
- [RT hackyboiz: [1day-1line] CVE-2026-21241: Use-After-Free LPE Vulnerability Caused by I/O Mini-Completion Packet Lifetime Management Error in Windows ...](https://hackyboiz.github.io/2026/06/15/Libera/CVE-2026-21241) by [Souhail Hammou](https://x.com/Dark_Puzzle/status/2066868790340497686).
- [Getting a CVE Without Shipping Slop https://www.credrelay.com/p/getting-a-cve-without-shipping-slop](https://www.credrelay.com/p/getting-a-cve-without-shipping-slop) by [Nicolas Krassas](https://x.com/Dinosn/status/2067109930461700423).
- [RT : So you might already have noticed kerberoast output changes since April, the enforcement phase with manual rollback. "The Windows updates rel...](https://support.microsoft.com/en-us/topic/how-to-manage-kerberos-kdc-usage-of-rc4-for-service-account-ticket-issuance-changes-related-to-cve-2026-20833-1ebcda33-720a-4da8-93c1-b0496e1910dc) by [Sean Metcalf](https://x.com/PyroTek3/status/2066878396253057432).
- [RT watchTowr: Noise, hysteria, confusion, and AI slop surround CVE-2026-35273 - we believe this is the first-stage SSRF in the Oracle PeopleSoft RCE c...](https://x.com/SinSinology/status/2066720063000863223) by SinSinology.
- [New entry added to the #LOLBAS Project: Proxy execution via system-native scp.exe. Takes any remote destination, doesn't actually have to run an ...](https://lolbas-project.github.io/lolbas/Binaries/Scp) by [Wietze](https://x.com/Wietze/status/2066868684161712328).
- [RT James 󠁧󠁢󠁷󠁬󠁳󠁿: Talk is over and reel is finally public. https://github.com/trustedsec/Reel](https://github.com/trustedsec/Reel) by [Rasta Mouse](https://x.com/_RastaMouse/status/2066861079414653392).
- [PrizeBuzz phishing network analysis https://phisheye.com/blog/prizebuzz-phishing-network](https://phisheye.com/blog/prizebuzz-phishing-network) by [/r/netsec](https://x.com/_r_netsec/status/2067041555664523353).
- [27 Years in the Dark: OpenBSD Fixes Ancient Remote Kernel Auth Bypass https://blog.argus-systems.ai/blog/openbsd-pap-27-year-auth-bypass.html](https://blog.argus-systems.ai/blog/openbsd-pap-27-year-auth-bypass.html) by [/r/netsec](https://x.com/_r_netsec/status/2066981158550954428).
- [RT LCFR: a sloppy unreliable exploit for this nice cBPF uaf that doesn't require bpf (ebpf) privs (cap_bpf/unpriv bpf) tested on centos10. 4.5 -> 7.1 ...](https://gist.github.com/lcfr-eth/ee5757422613354f5e2cd099d8a0ad7a) by [Alex Plaskett](https://x.com/alexjplaskett/status/2067477451807064243).
- [RT LukeGix: Excited to share this! Zombie COTables: Resurrecting Freed Memory to Escape VirtualBox. This blog post describes the exploitation process ...](https://blog.exodusintel.com/2026/06/15/zombie-cotables-resurrecting-freed-memory-to-escape-virtualbox) by [Alex Plaskett](https://x.com/alexjplaskett/status/2066875335266734303).
- [Scripting the disassembler: Local agentic reverse engineering through vbdec’s live COM object model](https://blog.talosintelligence.com/scripting-the-disassembler) by David Zimmer.
- [RT 1ce0ear: Slides for our OffensiveCon talk (by me and @jmartijnb) https://androidoffsec.withgoogle.com/slides/art_imagination_gpu_offensivecon_2026....](https://androidoffsec.withgoogle.com/slides/art_imagination_gpu_offensivecon_2026) by [chompie](https://x.com/chompie1337/status/2066763893490454772).
- [Embedding Forbidden Text in Spyware to Discourage AI Analysis](https://www.schneier.com/blog/archives/2026/06/embedding-forbidden-text-in-spyware-to-discourage-ai-analysis.html) by Bruce Schneier.
- [Big news! Accenture is investing $4B to build an industry-transforming cybersecurity platform, and runZero is thrilled to be part of this vision! Accenture intends to acquire a majority stake in Dra](https://www.runzero.com/newsroom/accenture-acquisition).
- [So AMD apparently disabled TSME on consumer CPUs through a firmware update and refuses to explain why. WTF is happening here?](https://arstechnica.com/security/2026/06/users-cry-foul-after-amd-stripped-memory-crypto-from-its-consumer-cpus) by [Florian Roth](https://x.com/cyb3rops/status/2067301762642379044).
- [RT Google VRP (Google Bug Hunters): Check out Tomas' post and article on hacking Google using Git integrations. One of these reports even won him Most...](https://nopnop.pro/2026/06/17/exploiting-git-integrations-in-cloud-services) by [Dave Aitel](https://x.com/daveaitel/status/2067570529716797622).
- [RT SpecterOps: Kubernetes assessments just got easier. @RonJonArod dropped two new Mythic extensions for helping with initial access on container-cent...](https://ghst.ly/4uoCWMs) by [Arun](https://x.com/dazzyddos/status/2067249912971186254).
- [New, from me: 'Popa' Botnet Linked to Publicly Traded Israeli Firm "For the past four years, a sprawling Android-based botnet called Popa has forced millions of consumer TV boxes to relay Internet tra](https://krebsonsecurity.com/2026/06/popa-botnet-linked-to-publicly-traded-israeli-firm).
- [RT RWXstoned: Smuggling C2 traffic within Slack's links previews. A PoC using Mythic. https://rwxstoned.github.io/2026-06-18-Slack-links-preview-for-C...](https://rwxstoned.github.io/2026-06-18-Slack-links-preview-for-C) by [Panos Gkatziroulis](https://x.com/ipurple/status/2067544855144751217).
- [Malicious YAML files that could be executed via WinGET can be detected using the Sysmon config below. The config covers: Process Creation Networ...](https://ipurple.team/2026/06/09/winget) by [Panos Gkatziroulis](https://x.com/ipurple/status/2067348491953754261).
- [Since @TwoSevenOneT dropped the EDRChoker article, I’ve noticed some inaccurate detection guidance around the registry key monitoring. Spec...](https://ipurple.team/2026/06/17/qos-policies) by [Panos Gkatziroulis](https://x.com/ipurple/status/2067260989410594891).
- [RT theabysslabs: Lost in Truncation. Analysis of a NTOSKRNL Heap Overflow https://theabysslabs.github.io/patch-diffing/exploitation/windowskernel/2026...](https://theabysslabs.github.io/patch-diffing/exploitation/windowskernel/2026) by [kmkz](https://x.com/kmkz_security/status/2067337151818207472).
- [RT Densel: First public macOS kernel memory corruption exploit on Apple M5 Calif Team https://blog.calif.io/p/first-public-ke...](https://blog.calif.io/p/first-public-ke) by [kmkz](https://x.com/kmkz_security/status/2067322727506067914).
- [RT Panos Gkatziroulis : Hopefully, more techniques will be added, but this project is very interesting for Purple Teamers and Defenders https://ii...](https://iimp0ster.github.io/detection-chokepoints/chokepoints/lsass-credential-dumping) by [Max](https://x.com/maxime_tz/status/2067272584010285510).
- [RT Nathan McNulty: Did you know SSPR for admins is always enabled even if you have SSPR set to None? It also doesn't honor your authentication methods...](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-sspr-policy?tabs=ms-powershell) by [Max](https://x.com/maxime_tz/status/2067145254470345111).
- [RT Mr.Un1k0d3r: We often talk about EDR evasion, but what about honeypot detection. Nothing new here, but a good reminder that detecting honeypots mak...](https://offsec.cypfer.com/blog/Honeypot-detection) by [Max](https://x.com/maxime_tz/status/2067662869882188032).
- [RT Ananay: New checkm8 style BootROM exploit for iPhone XS and iPhone 11 just dropped! It’s hardware level and unpatchable by a software update, whic...](https://ps.tc/pages/blog-usbliter8.html) by [scriptjunkie (Matt)](https://x.com/scriptjunkie1/status/2067810672394608788).
- [RT Dino A. Dai Zovi: This is very, very smart:](https://open.substack.com/pub/calif/p/how-to-format-a-ciphertext?r=26yra9&amp%3Butm_campaign=post&amp%3Butm_medium=web) by [thaddeus e. grugq](https://x.com/thegrugq/status/2067851729430069486).
- [RT Dustin Volz: Great story here by my former colleague @bobmcmillan on built-in backdoors in consumer devices that allow nation-state hackers to crea...](https://www.wsj.com/tech/cybersecurity/how-hackers-found-a-back-door-into-the-american-living-room-c117cb9f?st=yRJeM6&amp%3Breflink=desktopwebshare_permalink) by [thaddeus e. grugq](https://x.com/thegrugq/status/2067860257553158330).
- [RT mRr3b00t: Can confirm @Huntio is super cool! I combined this with @defused, @GreyNoiseIO , @shodanhq, @censysio and @ipinfo (i know there's probabl...](https://www.pwndefend.com/2026/06/18/fortibleed) by [thaddeus e. grugq](https://x.com/thegrugq/status/2067860454215675979).
- [RT Dr. Dan Lomas: France shuts down clandestine Chinese 'police stations' operating on its territory https://www.lemonde.fr/en/france/article/2026/06/...](https://www.lemonde.fr/en/france/article/2026/06) by [thaddeus e. grugq](https://x.com/thegrugq/status/2067633575789519337).
- [Be sure to check out @b0n0b0__ 's FFmpeg shenanigans in this Kdenlive calc pop :)](https://codeanlabs.com/2026/06/cve-2026-45184-popping-calc-on-kdenlive) by [Thomas Rinsma](https://x.com/thomasrinsma/status/2067587860530684309).
- [Gentlemen ransomware uses multiple EDR killers to disable defenses https://www.bleepingcomputer.com/news/security/gentlemen-ransomware-uses-multiple-e...](https://www.bleepingcomputer.com/news/security/gentlemen-ransomware-uses-multiple-e) by [BleepingComputer](https://x.com/BleepinComputer/status/2067737153241497806).
- [UnCanny - Another new coercion primitive with LPE 0day - machine-account NTLM coercion from a non-admin user via Windows Store InstallService plugin r...](https://github.com/0xHossam/UnCanny) by [Nicolas Krassas](https://x.com/Dinosn/status/2068021091684024748).
- [The first unpatchable iPhone exploit in six years targets chips still running Apple's latest iOS https://www.techspot.com/news/112820-first-unpatchabl...](https://www.techspot.com/news/112820-first-unpatchabl) by [Nicolas Krassas](https://x.com/Dinosn/status/2068020776003915826).
- [A Practical Guide to Detection Engineering in CrowdStrike NG-SIEM https://medium.com/@joe88cornell/a-practical-guide-to-detection-engineering-in-crowd...](https://medium.com/@joe88cornell/a-practical-guide-to-detection-engineering-in-crowd) by [Nicolas Krassas](https://x.com/Dinosn/status/2068001195730354600).
- [OpenBSD MPLS kernel stack leaks remotely (CVE-2026-56099) https://pop.argus-systems.ai/advisory/adv-040.html](https://pop.argus-systems.ai/advisory/adv-040.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2067997440641306870).
- [CryptoBandits Malware Doubles as a Backdoor, Abuses Tor https://www.securityweek.com/cryptobandits-malware-doubles-as-a-backdoor-abuses-tor/](https://www.securityweek.com/cryptobandits-malware-doubles-as-a-backdoor-abuses-tor) by [Nicolas Krassas](https://x.com/Dinosn/status/2067941706591326639).
- [RT DirectoryRanger: Hardening Intune, by @Carlos_Perez Part 1: The Privileged Roles Nobody Talks About https://trustedsec.com/blog/the-privileged-role...](https://trustedsec.com/blog/the-privileged-role) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2067368529821565077).
- [RT Binary Defense: The most effective malware doesn't always hide. Sometimes it blends in so well that it looks like the technologies your business de...](https://binarydefense.com/resources/blog/bluerabbit-a-golang-based-backdoor-with-ransomware-and-destructive-capabilities?amp%3Butm_medium=organic_social&amp%3Butm_campaign=bluerabbit_backdoor_ransomware_blog) by [Dave Kennedy](https://x.com/HackingDave/status/2068009831353511962).
- [Don't look now, but it seems Gizmodo's homepage is now serving up a Clickfix attack. Basics of the Click-Fix exploit, which causes a pasted URL to fetch malware via Windows Powershell. https:// krebso](https://krebsonsecurity.com/2025/03/clickfix-how-to-infect-your-pc-in-three-easy-steps).
- [Microsoft’s move to remove trust for cross-signed kernel drivers is a huge step forward for Windows security. What many organizations may not realize...](https://techcommunity.microsoft.com/blog/windows-itpro-blog/advancing-windows-driver-security-removing-trust-for-the-cross-signed-driver-pro/4504818) by [The Haag™](https://x.com/M_haggis/status/2067659724787695970).
- [RT Origin: We pointed Google Antigravity's hidden updater at a server we ran. The signed binary pulled down an unsigned payload, replaced itself with ...](https://www.originhq.com/research/a-morning-reversing-antigravity) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2067704727177965899).
- [RT vx-underground: > be pakistan government > develop custom malware > used to target high profile targets > used against indian military and politica...](https://www.securonix.com/blog/sheetcreep-evolved-google-sheets-rat) by [Suraj](https://x.com/PwnFunction/status/2067608776702877990).
- [I found an authenticated RCE in Netwrix Password Secure this year which got fixed this month. For everyone using it - update now! https://communi...](https://community.netwrix.com/t/adv-2026-008-multiple-vulnerabilities-in-netwrix-password-secure/133168) by [S3cur3Th1sSh1t](https://x.com/ShitSecure/status/2067858530388918575).
- [RT Mehmet Ergene: This is a big change for BYOVD https://techcommunity.microsoft.com/blog/windows-itpro-blog/advancing-windows-driver-security-removin...](https://techcommunity.microsoft.com/blog/windows-itpro-blog/advancing-windows-driver-security-removin) by [SwiftOnSecurity](https://x.com/SwiftOnSecurity/status/2067811477499617447).
- [RT Police nationale: L’OFAC démantèle un groupe de hackers français Mardi 9 juin, l’office anti-cybercriminalité (OFAC) a interpellé 7 hac...](https://x.com/SwitHak/status/2067963023428354405) by SwitHak ().
- [Kernel LPEs dropping before patches are widely available? It's been a wild month for Linux defenders. Our CIO @r3n1k breaks down how tried-and-true ha...](https://www.synacktiv.com/en/publications/surviving-the-surge-of-new-linux-lpe-defense-in-depth-not-dead) by [Synacktiv](https://x.com/Synacktiv/status/2067955478320058727).
- [Chaining Security Bugs in Discuz! X5.0: from Race Condition to Pre-Auth RCE https:// karmainsecurity.com/chaining-b ugs-in-discuz-from-race-condition-to-rce](https://karmainsecurity.com/chaining-bugs-in-discuz-from-race-condition-to-rce).
- [Would you like some malware served at the very top of DuckDuckGo? https://timsh.org/drainer-at-the-top-of-duckduckgo/](https://timsh.org/drainer-at-the-top-of-duckduckgo) by [/r/netsec](https://x.com/_r_netsec/status/2068234417949245802).
- [BUMSRAKETE™ - The Most Beautiful, Most Tremendous FreeBSD Vulnerability In The History Of Computing. BELIEVE ME. https://bumsrake.de/](https://bumsrake.de/) by [/r/netsec](https://x.com/_r_netsec/status/2068234415382421800).
- [Use-after-free in the QPACK encoder of nginx HTTP/3 - CVE-2026-42530 https://cystack.net/vi/research/cve-2026-42530-nginx-en](https://cystack.net/vi/research/cve-2026-42530-nginx-en) by [/r/netsec](https://x.com/_r_netsec/status/2068053222795915316).
- [CVE-2026-5667: Unauthenticated Remote Control of Mitsubishi MAC-577IF-2E WiFi Adapters via Probe Request Reconnaissance https://innerfirez.github.io/p...](https://innerfirez.github.io/p) by [/r/netsec](https://x.com/_r_netsec/status/2067671960683979106).
- [Just published - “An Introduction to AI Coding Agent Security” going through security architecture and common mistakes found in the commonly used (C...](https://www.nccgroup.com/media/jtepwx1t/nccgroup_codingagentswhitepaper.pdf) by [Alex Plaskett](https://x.com/alexjplaskett/status/2067964036797329860).
- [RT Zy: Slides for my Zer0Con 2026 talk "Attacking Apple Display Co-processor" is out ~ : https://github.com/dgh05t/Zer0con_2026_Attacking_Apple_DCP/bl...](https://github.com/dgh05t/Zer0con_2026_Attacking_Apple_DCP/bl) by [Alex Plaskett](https://x.com/alexjplaskett/status/2067623531374858643).
- [RT Alexis Rapin: Is the idea of APT groups as unitary, monolithic entities (a PLA unit, an MSS bureau) still viable? When it comes to China, maybe not...](https://bindinghook.com/understanding-modern-chinese-cyber-operations-means-shifting-from-apt-to-composite-responsibility) by [Dave Aitel](https://x.com/daveaitel/status/2068296569812586790).
- [RT Swissky: We've Been Here Before: Decompilers, Fuzzers, and Now AI - @clearseclabs https://www.clearseclabs.com/blog/weve-been-here-before-ai-vulner...](https://www.clearseclabs.com/blog/weve-been-here-before-ai-vulner) by [Dave Aitel](https://x.com/daveaitel/status/2067634093479637382).
- [RT RedTeam Recipes | RTR: We dropped our complete OSMR notes index on the blog. It’s a raw technical reference for macOS security researchers, coveri...](https://redteamrecipes.com/blog/2025/12/osmrnotes) by [Dominic Chell](https://x.com/domchell/status/2068360264601260397).
- [RT FBI Cyber Division: Today, as part of Operation Endgame, the FBI joins our international law enforcement partners in announcing the disruption of S...](https://www.politie.nl/en/news/2026/juni/18/11-international-law-enforcement-initiate-hunt-on-malware-group-socgholis…) by [Dominic Chell](https://x.com/domchell/status/2067711555710382091).
- [saw grok can run commands directly in the chat now looked at the requests, got a clanker to build a terminal ui around it hades (xai's internal sandbo...](https://falsneg.github.io/grok-hades-terminal) by [freddy](https://x.com/falsneg/status/2068192262375268704).
- [RT Karsten Hahn: I published an API tracer for kernel mode drivers using speakeasy emulation AI notice: It's vibe-coded. I manually analyzed ~20 drive...](https://github.com/struppigel/hedgehog-tools/tree/main/ktrace) by [hasherezade](https://x.com/hasherezade/status/2068452503579164729).
- [RT Tim Blazytko: The slides from our @reconmtl talk with @nicolodev on agentic deobfuscation are now online. Topics: commercial VMs, anti-cheat, DRM s...](https://synthesis.to/presentations/recon26_agentic_deobfuscation.pdf) by [hasherezade](https://x.com/hasherezade/status/2068087518629683709).
- [RT Elastic Security Labs: OXLOADER is staging shellcode in the PE .reloc section. Detection rates are low. New research from Elastic Security Labs. Le...](https://x.com/hasherezade/status/2068065643610644522) by hasherezade.
- [LACUNA Chain: Ghost Frames - defeats all EDR layers of call-stack-based detection https://0xmaz.me/posts/LACUNA-Chain-Ghost-Frames-defeats-All-EDR-lay...](https://0xmaz.me/posts/LACUNA-Chain-Ghost-Frames-defeats-All-EDR-lay) by [Panos Gkatziroulis](https://x.com/ipurple/status/2068375152719491325).
- [NOW - a C tool that converts raw shellcode bytes into human-readable English text - either a plain list of codewords or fluent natural-looking prose w...](https://github.com/NirvanaOn/NOW) by [Panos Gkatziroulis](https://x.com/ipurple/status/2067935927775740346).
- [RT CloudBreach: We published our Offensive Azure Security Cheatsheet Built from commands, notes, and practical knowledge gathered while cre...](https://github.com/cloudbreach/Cheatsheets/blob/main/Offensive%20Azure%20Security%20Cheatsheet.md) by [Panos Gkatziroulis](https://x.com/ipurple/status/2067726365915267445).
- [RT SpecterOps: The first version of BloodHound MCP proved an LLM could talk to BloodHound. The next version taught a more important lesson: MCP design...](https://ghst.ly/4exgf2O) by [Chihuahua in charge NotMe](https://x.com/jessefmoore/status/2067805572322472162).
- [doc=new DOMParser().parseFromString(` <select> <button> <noscript> <selectedcontent></selectedcontent> </noscript> </button> <option> <style></noscrip...](https://x.com/kinugawamasato/status/2068052991937266104) by Masato Kinugawa.
- [RT Florian Hansemann: ''CVE-2026-41096: Heap Overflow in the Windows DNS Client'' #infosec #pentest #redteam #blueteam https://www.m0n1x90.dev/blog/vr...](https://www.m0n1x90.dev/blog/vr) by [kmkz](https://x.com/kmkz_security/status/2068361661430280615).
- [The 401 That Fooled Me N-Day Review of CVE-2025-49706 in SharePoint https://y4nush.com/posts/the-401-that-fooled-me-n-day-review-of-cve-2025-49706-in-...](https://y4nush.com/posts/the-401-that-fooled-me-n-day-review-of-cve-2025-49706-in-) by [kmkz](https://x.com/kmkz_security/status/2068239495275716689).
- [RT Varik: Been exploring WebKit/JSC exploitation and wrote up a step-by-step walkthrough - from a caged OOB bug to cage-free arbitrary R/W with diagra...](https://varik.dev/blog/jsc/jsc-exploitation-primitives-part-1) by [kmkz](https://x.com/kmkz_security/status/2068235664684962115).
- [RT Swissky: The Mythos We Have At Home: A Patch-Diffing Pipeline for N-Day Generation - Tyler Holmwood - @originhq https://www.originhq.com/blog/patch...](https://www.originhq.com/blog/patch) by [kmkz](https://x.com/kmkz_security/status/2068008442644529207).
- [RT allthingsida: Slides are out. Please grab them from here: https://github.com/allthingsida/allthingsida/tree/main/presentations#select--from-binary-...](https://github.com/allthingsida/allthingsida/tree/main/presentations) by [Max](https://x.com/maxime_tz/status/2068251558085591503).
- [RT Praetorian: AMSI and ETW are built to watch the .NET runtime. So we took the runtime away. WasmForge compiles Rubeus and Seatbelt to WebAssemb...](https://www.praetorian.com/blog/wasmforge-csharp-ghostpack-edr-evasion) by [Max](https://x.com/maxime_tz/status/2068310659180232848).
- [RT Mr. OS: https://github.com/synacktiv/DCOMIllusionist DCOMIllusionist Windows fileless latteral movement technique. #github #tools](https://github.com/synacktiv/DCOMIllusionist) by [Max](https://x.com/maxime_tz/status/2067931184345080251).
- [RT Hossam: I published a small repo for some fresh windows execution-path hunting, covering a BOF for the undocumented Shell.HWEventHandlerShellExecut...](https://github.com/0xHossam/ShellHWEventExec) by [Ring3API 🇺🇦](https://x.com/ntlmrelay/status/2068409968915628164).
- [setresuid(): Glitching Google's TV Streamer from adb to root - @raelizecom https://raelize.com/blog/setresuid-glitching-google-tv-streamer-from-adb-...](https://raelize.com/blog/setresuid-glitching-google-tv-streamer-from-adb-) by [Swissky](https://x.com/pentest_swissky/status/2068425151218405852).
- [RT @yeahbutnahbut: SurfaceBroker EoP https://thecontractor.io/ms-surface-eop-system/?tw](https://thecontractor.io/ms-surface-eop-system?tw=) by [scriptjunkie (Matt)](https://x.com/scriptjunkie1/status/2068519671800750315).

</details>


## Tools and Exploits

- [BloodHound 9.3.0 Released with Full-Path Highlighting](https://bloodhound.specterops.io/resources/release-notes/2026-06-17) by [Chihuahua in charge NotMe](https://x.com/jessefmoore/status/2067806097390686525).
> The latest BloodHound release adds full-path highlighting that dims irrelevant paths when a node is selected. SpecterOps also published a deep dive on redesigning BloodHound MCP, arguing that smaller, focused tools beat large API surfaces for LLM integration.

- [Turnado: Assessing TURN Server Abuse for C2 Traffic](https://blog.syss.com/posts/turnado) by [pfiatde](https://x.com/pfiatde/status/2067854336906920294).
> SySS breaks down how APTs abuse Microsoft TURN relay servers to disguise C2 traffic as legitimate Teams connections and releases Turnado, a tool for testing your own TURN infrastructure for the same weaknesses.


<details markdown="1">
<summary>More this week (13)</summary>

- [Security Detections MCP v3.3.0 is live Added Jamf Protect macOS custom analytic detections New nightly sync + MCP/web support for Ja...](https://www.npmjs.com/package/security-detections-mcp) by [The Haag™](https://x.com/M_haggis/status/2067219960523333753).
- [RT Ido Veltzman: I released EtwSuite: A Windows native ETW inspection suite for listing providers, reading metadata, parsing manifests, creating sessi...](https://github.com/idov31/EtwSuite) by [winterknife](https://x.com/_winterknife_/status/2066921681273102791).
- [i love this exploit! universal SELinux bypass still works to this day. I released it for Qualcomm based processors and just realized I never released ...](https://github.com/chompie1337/s8_2019_2215_poc_exynos) by [chompie](https://x.com/chompie1337/status/2066375021980012864).
- [RT Nextron Research : Our artifact scanner flagged 5 malicious NPM packages related to the same infostealer campaign: @petitcode/eb-retry@1.3...](https://github.com//test/releases/download/v1.0.0) by [Florian Roth](https://x.com/cyb3rops/status/2067517264182600163).
- [RT Jiří Vinopal: Hello Reversers! Excited to release my port of @washi_dev awesome #Ghidra #NativeAOT plugin - now running natively in #IDA...](https://github.com/Dump-GUY/ida-nativeaot) by [Florian Roth](https://x.com/cyb3rops/status/2066888338670293067).
- [RT Open Source Security mailing list: OpenBSD sppp_pap_input: PAP authentication bypass https://www.openwall.com/lists/oss-security/2026/06/16/9 PAP A...](https://www.openwall.com/lists/oss-security/2026/06/16/9) by [Solar Designer](https://x.com/solardiz/status/2067477904913522784).
- [Ludus Feature Friday! The new 2.2.0 release brings "sources" which allow you to easily add blueprints, templates, and roles to your Ludus host. We even converted @M4yFly GOAD to a fully Ludus-native b](https://ludus.cloud/changelog/2.2.0).
- [RT FBI Cyber Division: Today the FBI released a #PSA warning the public about cyber criminal use of traffic distribution systems (TDSs) to gain access...](https://www.ic3.gov/PSA/2026/PSA260618) by [SwitHak ()](https://x.com/SwitHak/status/2067867471588061346).
- [Nothing beats the feeling when someone is inspired by your work and builds off it to release something even cooler. These slides have me hyped for the...](https://github.com/Print3M/MyTalks/blob/main/2026_06_x33fcon_Bring_Your_Own_Everything_-_The_Final_Approach.pdf) by [Bad Sector Labs](https://x.com/badsectorlabs/status/2068056211522502755).
- [This week's release adds a full unauthenticated RCE chain for Paperclip AI, an NTLM relay-to-self local priv esc module, a VS Code extension persisten...](https://www.rapid7.com/blog/post/pt-metasploit-wrap-up-19-06-2026) by [Metasploit Project](https://x.com/metasploit/status/2068021804870893856).
- [RT BallisKit: Running Sliver from a Word Macro on macOS? Yes it's very easy with the future DarwinOps release! C & Obj-C support , Native ARM64 , JIT-...](https://x.com/ntlmrelay/status/2067954341525279127) by Ring3API 🇺🇦.
- [RT ElektroKill: #dnSpyEx 6.6.0 has been released. After 2 years, finally a new stable release :D https://github.com/dnSpyEx/dnSpy/releases/tag/v6.6.0](https://github.com/dnSpyEx/dnSpy/releases/tag/v6.6.0) by [Swissky](https://x.com/pentest_swissky/status/2068385623493190001).
- [RT Caido: Testing WebSocket messages in Caido wasn't possible before v0.57.0. Now it is. Send WS messages straight from the Replay page: - Create...](https://www.caido.io/download) by [Swissky](https://x.com/pentest_swissky/status/2068023695679922372).

</details>



