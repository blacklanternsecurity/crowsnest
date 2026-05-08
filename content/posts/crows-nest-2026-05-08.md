---
title: "Crow's Nest - 2026-05-08"
date: 2026-05-08T00:00:00+00:00
draft: false
tags: ["roundup"]
---

A roundup of 189 items curated from across the security community.

## 📰 News

- [Claude Mythos Has Found 271 Zero-Days in Firefox](https://www.schneier.com/blog/archives/2026/04/claude-mythos-has-found-271-zero-days-in-firefox.html) by Bruce Schneier.
> 271 Firefox bugs found by Claude Mythos in collaboration with Mozilla. Schneier breaks down the disclosure and what it means for browser security at scale.

- [Defender for Endpoint: restrict response actions on high-value assets](https://learn.microsoft.com/en-us/defender-endpoint/restrict-response-actions-high-value-assets) by [Sean Metcalf](https://x.com/PyroTek3/status/2051707239463817401).
> Defender for Endpoint adds a public preview to restrict live response actions on high-value assets. The control SOC analysts running scripts as SYSTEM on tier 0 boxes have been asking for.

- [Bitwarden CLI compromised via Checkmarx npm Trusted Publishing](https://socket.dev/blog/bitwarden-cli-compromised) by [/r/netsec](https://x.com/_r_netsec/status/2047446189075996881).
> Bitwarden CLI was published as a malicious npm package after a compromise in the Checkmarx Trusted Publishing pipeline. Socket walks through the attack chain and the affected versions.

- [AAD Graph activity logs land in Azure Monitor](https://learn.microsoft.com/en-us/azure/azure-monitor/reference/tables/aadgraphactivitylogs) by [Alberto Verza](https://x.com/acap4z/status/2051574930446110751).
> Microsoft now ships AAD Graph activity logs through Azure Monitor. Defenders finally get the table they have been waiting on for hunting credential abuse against Entra.

- [UK AISI evaluates GPT-5.5 cyber capabilities](https://www.aisi.gov.uk/blog/our-evaluation-of-openais-gpt-5-5-cyber-capabilities) by [DANΞ](https://x.com/cryps1s/status/2049879762169167898).
> UK AISI evaluation of GPT-5.5 cyber capabilities. The model completed an end-to-end exploitation chain that AISI estimates would take a human expert ~20 hours.

- [Defender removes DigiCert AuthRoot registry entries](https://bugzilla.mozilla.org/show_bug.cgi?id=2033170) by [Florian Roth ⚡️](https://x.com/cyb3rops/status/2050960444592996521).
> Microsoft Defender flagged DigiCert AuthRoot registry entries and removed them on a chunk of endpoints. Looks like a detection mistake rather than a trust-store response, but worth knowing if you saw the alerts.

- [Canvas breach disrupts schools and colleges nationwide](https://krebsonsecurity.com/2026/05/canvas-breach-disrupts-schools-colleges-nationwide) by BrianKrebs.
> Ongoing data extortion attack against the Canvas LMS disrupted classes at thousands of US school districts and universities. Attackers defaced the login page with a ransom demand threatening to leak data on 275 million students and faculty across nearly 9,000 institutions.

- [OpenAI launches GPT-5.5 Cyber for defensive workflows](https://x.com/daveaitel/status/2052518939817545766) by Dave Aitel.
> OpenAI ships GPT-5.5 with Trusted Access for Cyber, plus a Limited Preview of GPT-5.5-Cyber. Targeted at secure code review, vulnerability triage, detection engineering, malware analysis, and patch validation.

- [Dirty Frag: universal Linux LPE chaining xfrm-ESP and rxrpc](https://dirtyfrag.io/) by [Dominic Chell 👻](https://x.com/domchell/status/2052502167236301157).
> Universal Linux LPE chaining xfrm-ESP and rxrpc bugs. No race, no panic on failure, deterministic. Even with the copy.fail mitigation applied, every major distro is still vulnerable.

- [DigiCert breach traced to malicious screensaver in a support chat](https://x.com/domchell/status/2052267296328909131) by Dominic Chell 👻.
> A DigiCert support analyst opened a .scr file from a customer chat. EDR blocked four infection attempts; the fifth got through. Over the next 11 days the attacker pulled 27 valid code-signing certificates from DigiCert's internal portal before an outside researcher tipped DigiCert off.

- [Chrome silently installs a 4 GB Gemini Nano model](https://awesomeagents.ai/news/chrome-gemini-nano-silent-install) by [Simone Margaritelli](https://x.com/evilsocket/status/2052336397651005576).
> Chrome silently installs a 4 GB Gemini Nano model file on user devices, no consent prompt, and re-downloads it if you delete it. Turns out the binary is a 6.3B INT4 build of Gemma 3 Nano with FP16 scales.

- [TAPOcalypse Now: exploiting TP-Link smart devices](https://labs.taszk.io/articles/post/tapocalypse) by [Gergely Kalman](https://x.com/gergely_kalman/status/2049608256511709619).
> Taszk Security Labs releases TAPOcalypse: exploiting TP-Link smart devices via LAN, browser, and the cloud account. Vendor fixed some, the rest stand at embargo expiry.

- [LAB52: 142-page EasterBunny report on APT29](https://lab52.io/blog/easterbunny) by [hasherezade](https://x.com/hasherezade/status/2052056422855147685).
> LAB52 publishes a 142-page open-access report on EasterBunny, advanced espionage artifacts attributed to APT29. Plenty for IR teams to feed into hunts.

- [Unauth PII leak in Salesforce Marketing Cloud (ExactTarget)](https://slcyber.io/research-center/ghosts-of-encryption-past-salesforce-exacttarget) by [shubs](https://x.com/infosec_au/status/2051608640109613380).
> SLCyber's research team disclosed a vulnerability that leaked PII and emails stored inside Salesforce Marketing Cloud instances, for any customer, with no authentication required. Writeup includes the disclosure timeline.


<details markdown="1">
<summary>More this week (9)</summary>

- [Anti-DDoS Firm Heaped Attacks on Brazilian ISPs](https://krebsonsecurity.com/2026/04/anti-ddos-firm-heaped-attacks-on-brazilian-isps) by BrianKrebs.
- [DarkSword Malware](https://www.schneier.com/blog/archives/2026/05/darksword-malware.html) by Bruce Schneier.
- [What Anthropic’s Mythos Means for the Future of Cybersecurity](https://www.schneier.com/blog/archives/2026/04/what-anthropics-mythos-means-for-the-future-of-cybersecurity.html) by Bruce Schneier.
- [Medieval Encrypted Letter Decoded](https://www.schneier.com/blog/archives/2026/04/medieval-encrypted-letter-decoded.html) by Bruce Schneier.
- [RT Logan D: Tired of EDR? From Joe Trudeau on the Depth Security team, and now public after numerous field-tested, successful engagements, introducing...](https://github.com/depthsecurity/PositiveIntent) by [Dave Cossa](https://x.com/G0ldenGunSec/status/2052226819303092230).
- [RT Socket: Update: Socket confirmed the Intercom compromise began with a local install of pyannote-audio, which pulled in compromised PyPI lightning a...](https://x.com/N3mes1s/status/2050085501504209219) by Giuseppe `N3mes1s`.
- [Affiliate of #Conti / #Tommyleaks / #Akira #Ransomware sentenced to Prison](https://www.justice.gov/opa/pr/member-prolific-russian-ransomware-group-sentenced-prison) by [SwitHak (👁)](https://x.com/SwitHak/status/2051610219319288224).
- [RT blasty: to celebrate the release of Copy Fail and the professional way the embargo and disclosure was handled by all involved parties i have sacrif...](https://gist.github.com/blasty/d7b5d0599b154c9ec83c182acbd56e8b) by [Alex Plaskett](https://x.com/alexjplaskett/status/2050102141637816788).
- [RT Alex Neff: Targeted Keberoasting with NetExec🔥 If you have Write privileges over a user, you can temporarily add an SPN to your target user, req...](https://x.com/harmj0y/status/2049238506321616919) by Will Schroeder.

</details>


## 📝 Techniques and Write-ups

- [Insights into the clustering and reuse of phone numbers in scam emails](https://blog.talosintelligence.com/insights-into-the-clustering-and-reuse-of-phone-numbers-in-scam-emails) by Omid Mirzaei.
> Cisco Talos starts collecting phone numbers found in scam emails as IOCs and reports on cluster reuse patterns across campaigns.

- [Rowhammer Attack Against NVIDIA Chips](https://www.schneier.com/blog/archives/2026/05/rowhammer-attack-against-nvidia-chips.html) by Bruce Schneier.
> New Rowhammer attack against NVIDIA Ampere GPUs. GDDR bitflips give adversaries full control of CPU memory; the boundary GPUs were thought to provide turns out to be permeable.

- [CVE-2026-33824: Remote Code Execution in Windows IKEv2](https://www.thezdi.com/blog/2026/4/22/cve-2026-33824-remote-code-execution-in-windows-ikev2) by TrendAI Research Team.
> TrendAI Research details a wormable double-free in the Windows IKE service. Recently patched. Reachable on internet-facing IPsec VPN endpoints.

- [MAD Bugs: QEMU and UTM escape](https://open.substack.com/pub/calif/p/mad-bugs-qemu-and-utm-escape?r=26yra9) by [Axel Souchet](https://x.com/0vercl0k/status/2049500782480003508).
> Calif team's writeup of a QEMU and UTM virtual machine escape, with PoCs.

- [MAD Bugs: RCE in the Ladybird browser](https://open.substack.com/pub/calif/p/mad-bugs-rce-in-ladybird?r=26yra9) by [Axel Souchet](https://x.com/0vercl0k/status/2047691304428298643).
> Calif team's writeup of an RCE in the Ladybird browser, with PoC. Part of the MAD Bugs series.

- [Palo Alto CVE-2026-0300: PAN-OS captive portal exploited in the wild](https://x.com/AndrewMohawk/status/2051933452157514150) by AndrewMohawk⁽ⁿᵘˡˡ⁾.
> Buffer overflow in PAN-OS captive portal (CVE-2026-0300) actively exploited. Unauthenticated attackers hit the User-ID Authentication Portal with crafted packets. CVSS 9.3.

- [Bypassing Windows authentication reflection mitigations](https://www.synacktiv.com/en/publications/bypassing-windows-authentication-reflection-mitigations-for-system-shells-part-1) by [Aurélien Chalot](https://x.com/Defte_/status/2048808441016143942).
> Synacktiv kicks off a series on bypassing the CVE-2025-33073 mitigations to pop SYSTEM shells via authentication reflection. Part one is up.

- [Under the Hood of AFD.sys (4-part reverse engineering series)](https://leftarcode.com/posts/afd-reverse-engineering-part1) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2052153429431079146).
> Four-part deep dive into Windows' AFD.sys, the kernel-side backbone of socket I/O. Covers undocumented interfaces, the TCP handshake, sending and receiving packets.

- [VS Code Dev Tunnels: the accidental C2 framework](https://specterops.io/blog/2026/05/06/dev-tunnels-the-accidental-c2) by [N7WEra](https://x.com/N7WEra/status/2052310783971729506).
> REST then WebSocket then SSH then MsgPack RPC. SpecterOps takes apart VS Code Dev Tunnels and finds a C2 framework underneath, with remote exec and file ops on top.

- [cPanel/WHM auth bypass CVE-2026-41940](https://labs.watchtowr.com/the-internet-is-falling-down-falling-down-falling-down-cpanel-whm-authentication-bypass-cve-2026-41940?123=) by [SinSinology](https://x.com/SinSinology/status/2049542180776100326).
> Auth bypass in cPanel/WHM tracked as CVE-2026-41940, full writeup from watchTowr. Also: [high-fidelity scanner from assetnote](https://slcyber.io/research-center/high-fidelity-check-for-the-cpanel-authentication-bypass-cve-2026-41940).

- [Synacktiv: over-the-air exploitation of the Philips Hue Bridge](https://www.synacktiv.com/en/publications/make-it-blink-over-the-air-exploitation-of-the-philips-hue-bridge) by [Synacktiv](https://x.com/Synacktiv/status/2052049115018649832).
> Synacktiv's writeup of an over-the-air Philips Hue Bridge compromise via a Zigbee bug, demoed at Pwn2Own Cork 2025.

- [OpenAI on the origin of frontier-model jailbreaks](https://openai.com/index/where-the-goblins-came-from) by [K̵i̵r̵k̵ ̵T̵r̵y̵c̵h̵e̵l̵](https://x.com/Teach2Breach/status/2049727149754438053).
> OpenAI on the origin and shape of jailbreak attacks against frontier models. Useful framing if you are building or defending agentic systems.

- [Adobe Acrobat zero-day sat on VirusTotal for 136 days before a CVE](https://nefariousplan.com/posts/adobe-acrobat) by [/r/netsec](https://x.com/_r_netsec/status/2047382014685597958).
> CVE-2026-34621 was uploaded to VirusTotal months before Adobe assigned a CVE. NefariousPlan walks through the disclosure-timeline gap and what it means for defenders relying on VT as an early-warning signal.

- [KernelToUserInjector dodges ETW threat-intelligence sensors](https://github.com/winterknife/EVENSTAR/tree/master/KernelToUserInjector) by [winterknife 🌻](https://x.com/_winterknife_/status/2052089180197413208).
> winterknife updates KernelToUserInjector to dodge ALLOCVM, WRITEVM, PROTECTVM, and QUEUEUSERAPC ETW threat-intelligence sensors, with sample EtwTi logs in the repo.

- [Codex on the wire: agent features as tradecraft](https://www.originhq.com/blog/codex-on-the-wire) by [winterknife 🌻](https://x.com/_winterknife_/status/2049771774733066456).
> Origin on Codex on the Wire: agent features become tradecraft when they ship documented IPC for remote sessions. One bind flag turns a compromised endpoint into a remotely controlled agent.

- [DSCourier: WinGet COM API as a post-exploitation primitive](https://eclipsesec.com/posts/DSCourier) by [Bad Sector Labs](https://x.com/badsectorlabs/status/2047432170612900269).
> Novel post-exploitation via WinGet's COM API, executing through Microsoft-signed binaries. Also: [Octoberfest7's BOF POC](https://github.com/Octoberfest7/DSCourier_BOF).

- [Goodbye secure pool, hello KDP pool](https://windows-internals.com/goodbye-secure-pool-hello-kdp-pool) by [chompie](https://x.com/chompie1337/status/2047454005308305764).
> Yarden Shafir on KDP pool, the Windows kernel feature replacing the secure pool. Quick read on how it works and what the migration looks like.

- [ARP around and find out: hijacking GPO UNC paths](https://trustedsec.com/blog/arp-around-and-find-out-hijacking-gpo-unc-paths-for-code-execution-and-ntlm-relay?hss_channel=tw-403811306) by [codewhisperer84](https://x.com/codewhisperer84/status/2050036059732426931).
> TrustedSec on hijacking trusted Group Policy UNC paths for code execution and NTLM relay, no rogue GPO infrastructure or SYSVOL modifications required.

- [Kerberos with Titanis: walking the auth flow](https://trustedsec.com/blog/kerberos-with-titanis?hss_channel=tw-403811306) by [codewhisperer84](https://x.com/codewhisperer84/status/2047346713053085911).
> TrustedSec walks the full Kerberos authentication flow and shows how to drive every stage of it with the Titanis toolset.

- [DAEMON Tools supply chain: Sigma rules from Nextron](https://github.com/SigmaHQ/sigma/pull/5988) by [Florian Roth ⚡️](https://x.com/cyb3rops/status/2052045047399428490).
> Kaspersky disclosed a DAEMON Tools supply chain compromise active since April 8, with thousands of infections across 100+ countries. Nextron contributed Sigma rules covering DNS lookups to the typosquatted C2, execution of trojanized binaries, and stage-drop activity.

- [Two command injections in Windows context menus](https://specterops.io/blog/2026/05/07/shift-happens-uncovering-two-built-in-command-injections-in-windows-context-menus) by Remi GASCOU.
> SpecterOps finds two command injection bugs in the Windows Explorer "Open PowerShell window here" context menu. A folder name like `folder; calc` triggers arbitrary PowerShell when the user shift-right-clicks.

- [MariaDB CVE-2026-32710: heap-grooming RCE in JSON_SCHEMA_VALID](https://www.zeroday.cloud/blog/mariadb-cve-2026-32710-deep-dive) by [Dave Aitel](https://x.com/daveaitel/status/2051347516541567418).
> Tim Becker writes up the heap-grooming technique behind a character-constrained overflow in MariaDB's JSON_SCHEMA_VALID, turned into full RCE. Discovered by Xint Code and disclosed at ZeroDay Cloud.

- [MCP server OAuth registration is wide open](https://openyoutu.be/wyxveABHu3I) by [Arun](https://x.com/dazzyddos/status/2052554014806679904).
> Most MCP servers ship with a wide-open OAuth registration endpoint. One curl command is enough to land an account takeover. Timely if you have AI agents wired into LAN-side MCP servers.

- [EDR internals research and bypass](https://0xdbgman.github.io/posts/edr-internals-research-and-bypass) by [Arun](https://x.com/dazzyddos/status/2052550869795942462).
> A tour through EDR internals and the bypass primitives that fall out of them. The author flags it as their last blog post on the topic.

- [SpecterOps: what red team actually means](https://ghst.ly/4uk1qaj) by [Arun](https://x.com/dazzyddos/status/2052167454097612903).
> SpecterOps on what red team actually means once you strip out the vendor-speak. The right question is whether you would detect an attacker already inside.

- [The defensive stack is exposed](https://trustedsec.com/blog/the-defensive-stack-is-exposed) by [d3d aka dead (dead, мёртв, 死了)](https://x.com/deadvolvo/status/2051726115924795529).
> AI is shifting the economics of probing the defensive stack itself. TrustedSec walks through how the tools defenders depend on are quietly becoming part of the attack surface.

- [dMSA Ouroboros: self-sustaining credential extraction on Server 2025](https://www.huntress.com/blog/dmsa-ouroboros-credential-extraction-windows-server-2025) by [Andrea P](https://x.com/decoder_it/status/2051408699537645784).
> Huntress on dMSA Ouroboros: six commands of self-sustaining credential extraction on patched Server 2025. Survives deletion of the original attacker account.

- [Trail of Bits beats Google's zero-knowledge proof of quantum cryptanalysis](https://blog.trailofbits.com/2026/04/17/we-beat-googles-zero-knowledge-proof-of-quantum-cryptanalysis) by [Dan Guido](https://x.com/dguido/status/2052442147593326731).
> Trail of Bits cryptanalyzes Google's zero-knowledge proof of quantum cryptanalysis and finds a way to forge it. Worth reading whether or not you follow PQC arguments.

- [Linux LPE wave: copy.fail across major distros](https://xint.io/blog/copy-fail-linux-distributions) by [Gergely Kalman](https://x.com/gergely_kalman/status/2049681017556881800).
> Trivially exploitable Linux LPE in coreutils, reachable on every major distro from the last nine years. Also: [meta site](https://copy.fail/), [retr0 explainer](https://retr0.zip/blog/cve-2026-31431-copy-fail.html), [Go port from Bad Sector Labs](https://github.com/badsectorlabs/copyfail-go), [Ubuntu Rust coreutils race conditions](https://seclists.org/oss-sec/2026/q2/332).

- [MAD Bugs: 21-year-old PHP unserialize use-after-free](https://open.substack.com/pub/calif/p/mad-bugs-finding-and-exploiting-a?r=26yra9&amp%3Butm_campaign=post&amp%3Butm_medium=web) by [Stefan Esser](https://x.com/i0n1c/status/2050503042240307645).
> A 21-year-old PHP unserialize use-after-free that survived two decades of audit. The Calif team welcomes Stefan Esser back with a fresh writeup.


<details markdown="1">
<summary>More this week (117)</summary>

- [UAT-8302 and its box full of malware](https://blog.talosintelligence.com/uat-8302) by Jungsoo An.
- [CloudZ RAT potentially steals OTP messages using Pheno plugin](https://blog.talosintelligence.com/cloudz-pheno-infostealer) by Alex Karkins.
- [AI-powered honeypots: Turning the tables on malicious AI agents](https://blog.talosintelligence.com/ai-powered-honeypots-turning-the-tables-on-malicious-ai-agents) by Martin Lee.
- [UAT-4356's Targeting of Cisco Firepower Devices](https://blog.talosintelligence.com/uat-4356-firestarter) by Cisco Talos.
- [Hacking Polymarket](https://www.schneier.com/blog/archives/2026/05/hacking-polymarket.html) by Bruce Schneier.
- [Fast16 Malware](https://www.schneier.com/blog/archives/2026/04/fast16-malware.html) by Bruce Schneier.
- [Identity APM Has Gone Mainstream. The Hard Work Is Just Starting.](https://specterops.io/blog/2026/04/28/identity-apm-has-gone-mainstream-the-hard-work-is-just-starting) by Jared Atkinson.
- [C/C++ checklist challenges, solved](https://blog.trailofbits.com/2026/05/05/c/c-checklist-challenges-solved).
- [Extending Ruzzy with LibAFL](https://blog.trailofbits.com/2026/04/29/extending-ruzzy-with-libafl).
- [RT HyperDbg: Major milestone forward for HyperDbg supporting #Linux. We've made a major progress on porting HyperDbg to Linux (still a long road ahead...](https://github.com/HyperDbg/HyperDbg/tree/dev/hyperdbg/linux) by [Björn Ruytenberg](https://x.com/0Xiphorus/status/2049499743915544974).
- [RT Francisco Falcon: A rogue DHCP server can inject arbitrary dhclient.conf directives via malicious DHCP options and get RCE as root in systems runni...](https://www.freebsd.org/security/advisories/FreeBSD-SA-26:12.dhclient.asc) by [Axel Souchet](https://x.com/0vercl0k/status/2049865707828150604).
- [RT freefirex: I don't know where this idea that you can't call CRT functions in bof's started coming from but it's just another function, you don't ne...](https://github.com/trustedsec/CS-Situational-Awareness-BOF/blob/ee9459cc4f42c6b025797bad22ffe8d9f1cf6487/src/common/bofdefs.h) by [Bobby Cooke](https://x.com/0xBoku/status/2052309392679469492).
- [RT HN Security: To kick off his collaboration with @PortSwigger as a Burp Suite Ambassador, our Research Lead @apps3c just published the 10th article ...](https://hnsecurity.it/blog/extending-burp-suite-for-fun-and-profit-the-montoya-way-part-10) by [raptor](https://x.com/0xdea/status/2051641320200908848).
- [Neat](https://x.com/AndrewMohawk/status/2051932731890651556) by AndrewMohawk⁽ⁿᵘˡˡ⁾.
- [RT solst/ICE of Astarte: ACAB includes DNSSEC](https://dnssecmenot.fly.dev/) by [AndrewMohawk⁽ⁿᵘˡˡ⁾](https://x.com/AndrewMohawk/status/2051942454627008848).
- [RT Medbdy(🔆): A breakdown of what happened and how @grok got tricked to send debtreliefbot:native tokens 1-Preparation NFT gift unlocks tools The a...](https://x.com/AndrewMohawk/status/2051280325687275849) by AndrewMohawk⁽ⁿᵘˡˡ⁾.
- [RT 1377 High-yield Nukes: A v8 dcheck == $500, I would start searching for how to find XSS & CSRF bugs right now.](https://bughunters.google.com/blog/evolving-the-android-chrome-vrps-for-the-ai-era) by [AndrewMohawk⁽ⁿᵘˡˡ⁾](https://x.com/AndrewMohawk/status/2050238879936999891).
- [**NEW** BHIS | Blog Have you ever wanted an easy match/replace extension for Burp Suite? Check out the new tool, Swapper, available through the @PortS...](https://www.blackhillsinfosec.com/swapper) by [Black Hills Information Security](https://x.com/BHinfoSecurity/status/2052078567349952874).
- ["What would happen if we replaced PAM with a malicious version? In theory, because PAM receives clear text credentials during authentication, we could...](https://www.blackhillsinfosec.com/the-p-in-pam-is-for-persistence-linux-persistence-technique) by [Black Hills Information Security](https://x.com/BHinfoSecurity/status/2051712528124694648).
- [RT Panos Gkatziroulis 🦄: For Purple Teams, SOC analysts, and detection engineers seeking detection guidance on the SharpHound collector, I’ve publ...](https://ipurple.team/2024/07/15/sharphound-detection) by [Black Hills Information Security](https://x.com/BHinfoSecurity/status/2049579184729534729).
- [**NEW** BHIS | Blog Which Active Directory enumeration tools look suspicious, and which are trusted by Microsoft? A Practical Guide to BloodHound Data...](https://www.blackhillsinfosec.com/bloodhound-data-collection) by [Black Hills Information Security](https://x.com/BHinfoSecurity/status/2049534539324690765).
- ["The databases have since been secured, but the incident highlights a critical issue for businesses that think AI chatbots are a silver bullet or a tu...](https://www.blackhillsinfosec.com/lessons-from-a-chatbot-incident) by [Black Hills Information Security](https://x.com/BHinfoSecurity/status/2048091920724074567).
- [RT Ken Gannon (伊藤 剣): YayPart3OfAPromonShieldBypassYay https://djini.ai/a-look-at-a-promon-shield-bypass-part-3/](https://djini.ai/a-look-at-a-promon-shield-bypass-part-3) by [Dimitri Os](https://x.com/Ch0pin/status/2049486273123954837).
- [RT DirectoryRanger: M365Pwned. Red Team tooling for Microsoft 365 exploitation via Microsoft Graph API, by @OtterHacker https://github.com/OtterHacker...](https://github.com/OtterHacker) by [DebugPrivilege](https://x.com/DebugPrivilege/status/2048082629145096636).
- [PCPJack | Cloud Worm Evicts TeamPCP and Steals Credentials at Scale https://www.sentinelone.com/labs/cloud-worm-evicts-teampcp-and-steals-credentials-...](https://www.sentinelone.com/labs/cloud-worm-evicts-teampcp-and-steals-credentials-) by [Nicolas Krassas](https://x.com/Dinosn/status/2052334454685700432).
- [Fake Claude AI website delivers new 'Beagle' Windows malware https://www.bleepingcomputer.com/news/security/fake-claude-ai-website-delivers-new-beagle...](https://www.bleepingcomputer.com/news/security/fake-claude-ai-website-delivers-new-beagle) by [Nicolas Krassas](https://x.com/Dinosn/status/2052334399488774514).
- [Claude AI Guided Hackers Toward OT Assets During Water Utility Intrusion https://www.securityweek.com/claude-ai-guided-hackers-toward-ot-assets-during...](https://www.securityweek.com/claude-ai-guided-hackers-toward-ot-assets-during) by [Nicolas Krassas](https://x.com/Dinosn/status/2052298673757827235).
- [pyghidra-mcp Meets Ghidra GUI: Drive Project-Wide RE with Local AI https://clearbluejar.github.io/posts/pyghidra-mcp-meets-ghidra-gui-drive-project-wi...](https://clearbluejar.github.io/posts/pyghidra-mcp-meets-ghidra-gui-drive-project-wi) by [Nicolas Krassas](https://x.com/Dinosn/status/2052221221995991351).
- [RT striga: For a Fistful of Dollars: Less than $100 of Compute Surfaces Pre-auth RCE in Apache httpd Write-up: https://www.striga.ai/research/apache-h...](https://www.striga.ai/research/apache-h) by [Nicolas Krassas](https://x.com/Dinosn/status/2052246598231437749).
- [http://SQLRecon.Microsoft SQL Server toolkit that is designed for offensive reconnaissance and post-exploitation. https://github.com/skahwah/SQLRecon](https://github.com/skahwah/SQLRecon) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2052154739857473718).
- [Abusing delegation with Impacket https://hunio.org/posts/security/abusing-delegation-with-impacket/](https://hunio.org/posts/security/abusing-delegation-with-impacket) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2052153839604613592).
- [Get-SPNPrivilegedUsers. PowerShell security auditing tool that identifies AD users with SPNs who are members of high-privilege groups. Optionally perf...](https://github.com/mr-r3b00t/kerberoast_audit) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2051764096312180890).
- [Yamato Security's Windows Event Log Configuration Guide For DFIR And Threat Hunting https://github.com/Yamato-Security/EnableWindowsLogSettings](https://github.com/Yamato-Security/EnableWindowsLogSettings) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2051763828891787594).
- [RT Ru Campbell: Updated and improved: Defender for Endpoint feature and capability comparison by OS GET IT: https://campbell.scot/updated-may-2026-mde...](https://campbell.scot/updated-may-2026-mde) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2052153582405722571).
- [RT Panos Gkatziroulis 🦄: morphkatz - Polymorphic PE rewriter for Windows x64 , rewrites binaries into semantically identical but byte-different var...](https://github.com/0xMohammedHassan/morphkatz) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2052153855392014384).
- [RT Co11ateral: During pentests we often have to deal with tasks that can be automated. Some of the best tools for this are ADScan and ADPulse. ADScan ...](https://hackers-arise.com/offensive-security-speeding-up-active-directory-pentests-with-adscan-and-adpulse) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2051413626947256785).
- [RT quarkslab: Do you know how Entra ID applications work? What about the security mess they can bring and what they can quietly break? New blog post o...](https://blog.quarkslab.com/auditing-application-permissions-in-microsoft-entra-id-hidden-risks-pitfalls-and-quarkslabs-qazpt-tool.html) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2052155181442220515).
- [Golang intentionally introduced randomness into map iterations and the keying of maps. This articles discusses why, how, and the consequences of doing...](https://maxwelldulin.com/BlogPost/Golang-Map-Non-Determinism) by [Maxwell ꓘ Dulin (Strikeout)](https://x.com/Dooflin5/status/2052032647363547373).
- [RT Felix Wilhelm: Max (@Dooflin5) is one of the best in the game at breaking cross-chain bridges. Check out his latest post on an interesting Across b...](https://x.com/Dooflin5/status/2049531723365621909) by Maxwell ꓘ Dulin (Strikeout).
- [RT Pavel Yosifovich: New video: creating COM objects with the class moniker. Most of you know CoCreateInstance. Here is another way: class moniker. I ...](https://youtu.be/P-L-gTjbtSI) by [Dave Cossa](https://x.com/G0ldenGunSec/status/2049583836195852548).
- [RT Binary Defense: Trusted processes are doing the work. That’s the problem. Phantom Stealer blends into normal system behavior, abusing Microsoft-si...](https://binarydefense.com/resources/blog/chasing-phantoms-how-a-multi-stage-stealer-abuses-signed-binaries-to-disappear?amp%3Butm_medium=organic_social&amp%3Butm_campaign=chasing_phantoms_multi_stage_stealer_blog) by [Dave Kennedy](https://x.com/HackingDave/status/2051363975506391163).
- [RT BeyondTrust Phantom Labs™: New research! Security Researcher, Sergio Garcia (@MrCloudSec) uncovers a major risk in AWS Bedrock API keys: the “pha...](https://www.beyondtrust.com/blog/entry/aws-bedrock-security-api-keys?amp%3Butm_medium=organic+social&amp%3Butm_content=phantomlabs) by [Ryan](https://x.com/Haus3c/status/2051723936501522921).
- [RT s1r1us (mohan): when react2shell hit last year, i think vercel handled it brilliantly. to protect their users, they paid $50,000 for every bypass r...](https://www.hacktron.ai/blog/react2shell-vercel-waf-bypass) by [LiveOverflow 🔴](https://x.com/LiveOverflow/status/2051379968186208652).
- [RT MagicSword: Komari just landed in LOLRMM and this one's different. Komari doesn't need to be abused to function as a C2. The control channel ships ...](https://lolrmm.io/tools/komari) by [The Haag™](https://x.com/M_haggis/status/2051691604348457114).
- [RT Kostas: RMM hunting is one of those areas where defenders get stuck because the answer is rarely “just block it.” On a day-to-day basis, from the...](https://x.com/M_haggis/status/2049611903773954178) by The Haag™.
- [RT Red Canary, a Zscaler company: Stop wrestling with complex tool syntax. 🛠️ By leveraging MCP for Atomic Red Team, Hare shows off a "fuzzy API" ...](https://www.youtube.com/watch?v=V2NrCskEau0&t=1266s) by [The Haag™](https://x.com/M_haggis/status/2047811915251085394).
- [RT MagicSword: Another LOLRMM in the bucket - this time, renamed, delivered via phishing, and signed with a legitimate cert. Lunixar RMM. Disguised as...](https://lolrmm.io/tools/lunixar) by [The Haag™](https://x.com/M_haggis/status/2047715109603037424).
- [RT Adnan Khan: The activity log by on https://github.com/intercom/intercom-node/activity is brutal. 1. Backdoor shipped to NPM via OIDC (done automati...](https://github.com/intercom/intercom-node/activity) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2049936389291069921).
- [RT Zellic: The core utilities that run every Linux system have been rewritten in Rust. We audited them. Before shipping uutils coreutils with Ubuntu 2...](https://x.com/N3mes1s/status/2051036696452505980) by Giuseppe `N3mes1s`.
- [RT Shielder: Can a hostile container sneak past your eBPF tracing? Sometimes, yes. With @OSTIFofficial & @CloudNativeFdn we audited Inspektor Gadget -...](https://www.shielder.com/blog/2026/04/inspektor-gadget-security-audit) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2049883208762737095).
- [RT JulietSecurity: we tested CVE-2026-31431 ("Copy Fail") on real Kubernetes clusters. PSS Restricted didn't block it. RuntimeDefault didn't block it....](https://x.com/N3mes1s/status/2049877229480337873) by Giuseppe `N3mes1s`.
- [RT grsecurity: Creating a separate post so more people see this: the mitigation recommended by http://Theori.io for http://copy.fail *WILL NOT WORK* f...](https://theori.io/) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2049689486020260067).
- [RT DbgMan ^_^: DrvEye automates kernel driver analysis to uncover IOCTL paths , symbolic, dangerous primitives, and exploitable code paths, then gener...](https://github.com/0xDbgMan/DrvEye) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2049719151984263487).
- [This is some really nice work. A deep dive into what legitimate Windows network traffic looks like and how Impacket differs. Lots of goodness for both...](https://github.com/ThatTotallyRealMyth/Impacket-IoCs) by [Octoberfest7](https://x.com/Octoberfest73/status/2050149229633364314).
- [PrestaShop version fingerprinting checking core modules versions. https://labs.itresit.es/2026/04/29/prestashop-the-art-of-core-module-fingerprinting/](https://labs.itresit.es/2026/04/29/prestashop-the-art-of-core-module-fingerprinting) by [Peter Gabaldon](https://x.com/PedroGabaldon/status/2049388046718521663).
- [RT James Kettle: We've launched a new @WebSecAcademy topic on exploiting AI-powered security scanners! Learn how to use indirect prompt injection to s...](https://x.com/PortSwiggerRes/status/2048804281977839850) by PortSwigger Research.
- [RT DirectoryRanger: Securing Entra ID Administration: Tier 0, by @PyroTek3 https://trustedsec.com/blog/securing-entra-id-administration-tier-0](https://trustedsec.com/blog/securing-entra-id-administration-tier-0) by [Sean Metcalf](https://x.com/PyroTek3/status/2051686988210712787).
- [RT 0x12 Dark Development: Overwriting Process Creation Kernel Callbacks New Medium post: after identifying security drivers (EDRs/AV) monitoring the s...](https://medium.com/@s12deff/overwriting-process-creation-kernel-callbacks-8c9f73980eb7) by [Silky](https://x.com/S1lky_1337/status/2047429973313519971).
- [good to see EXISTING Elastic generic privesc behavior detection/protection triggering on the RedSun LPE exploit with no prior knowledge of the vuln-de...](https://github.com/elastic/protections-artifacts/blob/c28c16baea1b0c9d2ebc63dfc1880635890fd91e/behavior/rules/windows/privilege_escalation_potential_privilege_escalation_via_file_redirection.toml) by [Samir](https://x.com/SBousseaden/status/2051423558073549017).
- [RT Ruben Groenewoud: Looking for Linux detection for Copy Fail (CVE-2026-31431) + similar SUID privesc flows? This rule focuses on the underlying abus...](https://github.com/elastic/detection-rules/pull/6018) by [Samir](https://x.com/SBousseaden/status/2049822668233290209).
- [++ Existing Elastic SIEM rules that looks exactly for RMM behavior drift vs just RMM existence (I may blog some other tricks to spot susp RMM use 😃...](https://github.com/elastic/detection-rules/blob/f7387bb10d4938c63954d969892a9e30f03f4a25/rules/windows/command_and_control_newly_observed_screenconnect_host_server.toml) by [Samir](https://x.com/SBousseaden/status/2049791618195026387).
- [https://www.npmjs.com/package/@cap-js/postgres/v/2.2.2?activeTab=code (hit and run) https://github.com/elastic/detection-rules/blob/bf40d2108b41902b33...](https://www.npmjs.com/package/@cap-js/postgres/v/2.2.2?activeTab=code) by [Samir](https://x.com/SBousseaden/status/2049559702728491238).
- [RT Mika Ayenson: 👿One YAML change can exfiltrate every secret in your CI run. 🛡️ Here's an pen-sourced CI/CD Abuse Detector prototype - flags m...](https://github.com/elastic/cicd-abuse-detector) by [Samir](https://x.com/SBousseaden/status/2049226808537633086).
- [RT MSec Operations: Our first Blog post is live, Introduction to RustPack 🔥 https://www.msecops.de/blog/posts/rustpack-intro/ More to follow in the...](https://www.msecops.de/blog/posts/rustpack-intro) by [S3cur3Th1sSh1t](https://x.com/ShitSecure/status/2050648165653569803).
- [RT incendiumrocks: It's been a while since I wrote a blog post. My new post writes about some cool updates to the MS-RPC-Fuzzer for recursively fuzzin...](https://www.incendium.rocks/posts/Fuzzing-MS-RPC-structures-and-monitoring) by [Steven Lowson](https://x.com/StevoLowson/status/2051351253679005718).
- [RT DirectoryRanger: RelayKing.comprehensive relay detection and enumeration tool designed to identify relay attack opportunities in Active Directory e...](https://github.com/depthsecurity/RelayKing-Depth) by [Steven Lowson](https://x.com/StevoLowson/status/2050602447249252767).
- [RT Haidar: So here is new local privilege escalation zero-day I discovered, not patched yet too :). In simple terms, if you have a service like RDP th...](https://securelist.com/phantomrpc-rpc-vulnerability/119428) by [Steven Lowson](https://x.com/StevoLowson/status/2047621700028699132).
- [RT ESET Research: #ESETresearch uncovered a multiplatform supply-chain attack by the 🇰🇵 #ScarCruft APT group targeting the Yanbian region via ba...](https://www.welivesecurity.com/en/eset-research/rigged-game-scarcruft-compromises-gaming-platform-supply-chain-attack) by [SwitHak (👁)](https://x.com/SwitHak/status/2051605760979734698).
- [RT Cursor: Our agent harness makes models inside Cursor faster, smarter, and more token-efficient. Here's how we test improvements to the harness, mon...](https://cursor.com/blog/continually-improving-agent-harness) by [K̵i̵r̵k̵ ̵T̵r̵y̵c̵h̵e̵l̵](https://x.com/Teach2Breach/status/2049962460984078443).
- [RT Matt Johansen: Re He began by replicating Mythos findings with his specialized harness. Then went on to find more critical novel zero days in open ...](https://www.provos.org/p/finding-zero-days-with-any-model) by [K̵i̵r̵k̵ ̵T̵r̵y̵c̵h̵e̵l̵](https://x.com/Teach2Breach/status/2049893241751851259).
- [RT Kaptor Security: We dive deeper into the new 𝗕𝗹𝗶𝗻𝗱 𝗣𝗿𝗼𝗺𝗽𝘁 𝗜𝗻𝗷𝗲𝗰𝘁𝗶𝗼𝗻 technique. Unified ...](https://kaptor.ai/blog/blind-prompt-injection.html) by [X-C3LL](https://x.com/TheXC3LL/status/2048710962518135164).
- [Some powerful built-in Windows 11 programs are allowed to write files to Defender’s working directory: \System32\msiexec.exe \Register-CimProvider.ex...](https://x.com/TwoSevenOneT/status/2050768734772695507) by Two Seven One Three.
- [Challenge: Drop #mimikatz onto a drive with the latest Windows 11. 1. Found a way to write a file into Windows Defender’s working directory: Success ...](https://x.com/TwoSevenOneT/status/2050767406034002347) by Two Seven One Three.
- [RT BlackSnufkin: new repo: Cheshire 🐱 Adaptix C2 service plugin that lets you test payloads against LitterBox without leaving the Adaptix client. p...](https://github.com/BlackSnufkin/Cheshire) by [Rasta Mouse](https://x.com/_RastaMouse/status/2051704966822158768).
- [Atomic BOFs https://rastamouse.me/atomic-bofs/](https://rastamouse.me/atomic-bofs) by [Rasta Mouse](https://x.com/_RastaMouse/status/2048024129492722134).
- [RT x64dbg: Re There is also a pre-alpha Linux version brewing 👀](https://x.com/_RastaMouse/status/2047596459885748461) by Rasta Mouse.
- [RT PT SWARM: 🧑‍🚒 Our researcher Mikhail Sukhov shares his knowledge and experience in analyzing FreeIPA environments. He also introduces his ne...](https://swarm.ptsecurity.com/thinking-in-graphs-with-ipahound) by [Arseniy Sharoglazov](https://x.com/_mohemiv/status/2049779746850885880).
- [BloodHound in CLI 🐍 can be useful when I want to run a batch of tests. Reminds me a bit of bloodhound-quickwin by @kaluche_ Added in Exegol images ...](https://github.com/DotNetRussell/BloodBash) by [Charlie Bromberg « Shutdown »](https://x.com/_nwodtuhs/status/2047748910282658070).
- [Large-scale security audit of 1,764 "vibe-coded" apps: 7% have wide-open Supabase DBs, 15% of Bolt apps ship hardcoded API keys, plus IDOR and zero-au...](https://securityscanner.dev/reports/2026-q2) by [/r/netsec](https://x.com/_r_netsec/status/2047955795346952400).
- [STIX Visualizer - Threat Intelligence Graph Explorer https://cyber.netsecops.io/stix-viz/](https://cyber.netsecops.io/stix-viz) by [/r/netsec](https://x.com/_r_netsec/status/2047884072668823968).
- [Detect Shulfar Malware Encrypted TCP C&C Traffic Using PacketSmith Yara-X Detection Module https://blog.netomize.ca/detect-shulfar-malware-encrypted-t...](https://blog.netomize.ca/detect-shulfar-malware-encrypted-t) by [/r/netsec](https://x.com/_r_netsec/status/2047778376975520231).
- [Media player pivot: How I got back into my own server https://addadi.github.io/2026/04/17/how-i-hacked-back-into-my-server-through-a-media-player/](https://addadi.github.io/2026/04/17/how-i-hacked-back-into-my-server-through-a-media-player) by [/r/netsec](https://x.com/_r_netsec/status/2047767051239125452).
- [ShinyHunters Claims Sale of Anthropic Claude Mythos AI Model Data and Internal Documents https://breachnews.com/breaches/shinyhunters-claims-sale-of-a...](https://breachnews.com/breaches/shinyhunters-claims-sale-of-a) by [/r/netsec](https://x.com/_r_netsec/status/2047661354660811156).
- [What Really Happened In There? A Tamper-Evident Audit Trail for AI Agents https://nono.sh/blog/secure-agent-audit](https://nono.sh/blog/secure-agent-audit) by [/r/netsec](https://x.com/_r_netsec/status/2047612283338281042).
- [UK Biobank Health Data of 500K Listed for Sale in China https://www.verity.news/story/2026/uk-biobank-health-data-of-k-listed-for-sale-in-china?p=re45...](https://www.verity.news/story/2026/uk-biobank-health-data-of-k-listed-for-sale-in-china?p=re45) by [/r/netsec](https://x.com/_r_netsec/status/2047446187863900508).
- [RT Alexandre Becholey: Chapter 2 of the ARM hypervisor series is out. We go over taking ownership of the page tables, memory configuration, copying th...](https://0xabe.io/hypervisor/arm/2026/04/30/HvArm-Chapter-2.html) by [winterknife 🌻](https://x.com/_winterknife_/status/2050460937325322511).
- [RT profdeibert: New @citizenlab report uncovers two separate China-based cyber espionage campaigns targeting journalists, human rights defenders, exil...](https://citizenlab.ca/research/how-chinese-actors-use-impersonation-and-stolen-narratives-to-perpetuate-digital-transnational-repression) by [winterknife 🌻](https://x.com/_winterknife_/status/2049102997788012568).
- [RT Vector 35: The debugger got some real love in our latest update. Hardware breakpoints and conditional breakpoints have both landed, and the new deb...](https://binary.ninja/2026/04/13/binary-ninja-5.3-jotunheim.html) by [winterknife 🌻](https://x.com/_winterknife_/status/2048840824641802255).
- [RT ENKI WhiteHat: [1/2] CVE-2026-32223: heap overflow in usbprint.sys (IOCTL 0x220064). Malformed USB descriptor, Named Pipe spray + Ghost Chunk for k...](https://www.enki.co.kr/en/media-center/blog/plug-me-if-you-can-exploiting-usb-printer-drivers-in-windows) by [winterknife 🌻](https://x.com/_winterknife_/status/2048650172180070528).
- [RT littlelailo: Had a lot of fun reversing Coruna over the last couple weeks and decided it would be worth to write it all up before I forget - so enj...](https://littlelailo.github.io/writeups/coruna.html) by [Alex Plaskett](https://x.com/alexjplaskett/status/2050833526820335628).
- [RT lukas seidel: a new paper on efficient firmware fuzzing has arrived! Khost uses near-native execution and rehosts ARM firmware inside KVM on an ARM...](https://x.com/alexjplaskett/status/2050102751573446693) by Alex Plaskett.
- [RT Ckrielle: Another i0rs post, this time from @0x3dward who takes it upon himself to write a POC for a recently discovered heap buffer overflow in Po...](https://i0.rs/blog/smashing-pgcrypto-for-fun-and-profit-analyzing-and-exploiting-cve-2026-2005) by [Alex Plaskett](https://x.com/alexjplaskett/status/2049376215643955253).
- [Reminder for Mac users: please update your OpenAI macOS apps by Friday, May 8. As we shared last month, we're rotating macOS signing certificates afte...](https://openai.com/index/axios-developer-tool-compromise) by [DANΞ](https://x.com/cryps1s/status/2052137993042047072).
- [Ransomware operator's day job was as a ransomware negotiator (where he siphoned victim info). It's rare to catch me speechless, but that... wow... tha...](https://x.com/curi0usJack/status/2050248125093138630) by Jason Lang.
- [RT Nextron Research ⚡️: Another day another suspicious WHQL-signed driver... We identified a signed sample of RedDriver, a malicious kernel driver t...](https://x.com/cyb3rops/status/2052327655551160639) by Florian Roth ⚡️.
- [Good write-up by Unfold on detecting CVE-2026-41940, the #cPanel & WHM auth bypass analyzed by watchTowr What I like about it: they don’t stop at det...](https://www.unfold.ai/blog/cpanel-exploit-cve-2026-41940) by [Florian Roth ⚡️](https://x.com/cyb3rops/status/2052315078901264881).
- [Checking a Linux system for CopyFail exploitation traces with THOR Cloud Lite The video is 1 min long It shows: - creating a THOR Cloud Lite campaign ...](https://thorcloud-lite.nextron-systems.com/ui/campaign) by [Florian Roth ⚡️](https://x.com/cyb3rops/status/2051268923971018817).
- [Built a fun little project this weekend: surface-watch It’s a lightweight external attack surface monitoring framework that builds scope from known F...](https://github.com/Nextron-Labs/surface-watch) by [Florian Roth ⚡️](https://x.com/cyb3rops/status/2050969327763959865).
- [RT International Cyber Digest: 🚨 Frontier AI models are forcing Oracle to move from quarterly to monthly critical security patches. Starting May 20...](https://x.com/daveaitel/status/2051386870307709098) by Dave Aitel.
- [RT Tim Becker: Full technical writeup + exploit technique for this 20-year-old bug in PostgreSQL https://www.zeroday.cloud/blog/postgres-xint](https://www.zeroday.cloud/blog/postgres-xint) by [Dave Aitel](https://x.com/daveaitel/status/2051347498728403277).
- [Some huge progress with Pickle C2, it can now load "modules" after compilation, they can be added at compiled-time or after execution!. The demo here ...](https://x.com/dmcxblue/status/2049864741774901277) by David.
- [RT Brad Spengler: Re Associated blog: https://www.linkedin.com/pulse/afalg-page-cache-cross-container-pivot-part-i-massimiliano-oldani-jgfyf/](https://www.linkedin.com/pulse/afalg-page-cache-cross-container-pivot-part-i-massimiliano-oldani-jgfyf) by [Dominic Chell 👻](https://x.com/domchell/status/2052310137189056803).
- [RT Brad Spengler: A gift from sgrakkyu: https://github.com/sgkdev/page_inject/](https://github.com/sgkdev/page_inject) by [Dominic Chell 👻](https://x.com/domchell/status/2052310120055361998).
- [RT Ollie Whitehouse: At @NCSC we have released 'Understanding adversarial attacks against Machine Learning and AI' which introduces a common language ...](https://www.ncsc.gov.uk/paper/understanding-adversarial-attacks-against-machine-learning-and-ai) by [Dominic Chell 👻](https://x.com/domchell/status/2050602165736030287).
- [RT genoff 🪿: my bike rides stopped syncing, so i decompiled the firmware. found a hidden dev mode. sent 3 bytes over BLE. my cycling computer now s...](https://x.com/evilsocket/status/2050912088852185188) by Simone Margaritelli.
- [🤓 Web based prompt injection is when a threat actor tries to exploit your LLM through hidden prompts inside a web page. They embed malicious instru...](https://promptintel.novahunting.ai/prompt/abb39e8f-ac14-43d9-9747-2d537aa420d5) by [Thomas Roccia 🤘](https://x.com/fr0gger_/status/2051534684707016748).
- [RT SEKTOR7 Institute: Compile-time C obfuscator. Macro-header for obfuscating C code at time of compilation, targeting TCC on Windows x86/x64, a tool ...](https://github.com/DosX-dev/obfus.h) by [hasherezade](https://x.com/hasherezade/status/2052394618432479682).
- [RT Virus Bulletin: Malwarebytes' Gabriele Orini details how NWHStealer operators are abusing Bun to spread a Rust-based infostealer. Because Bun is st...](https://www.malwarebytes.com/blog/threat-intel/2026/05/attackers-adopt-javascript-runtime-bun-to-spread-nwhstealer) by [hasherezade](https://x.com/hasherezade/status/2052330363683270923).
- [RT Omri Segev Moyal: Our team just published research on a malware campaign that hit 25+ organizations, several in Israel. The attacker built it so ba...](https://x.com/hasherezade/status/2051984327836057699) by hasherezade.
- [RT Nextron Research ⚡️: Anti-Tampering Kernel Driver Deep Dive We have found an interesting WHQL-signed vulnerable kernel driver that protects proce...](https://x.com/hasherezade/status/2051663846734024761) by hasherezade.
- [RT Virus Bulletin: Trend Micro reports QLNX, a Linux RAT that combines credential harvesting with deeper system tampering. The malware dynamically com...](https://www.trendmicro.com/en_us/research/26/e/quasar-linux-qlnx-a-silent-foothold-in-the-software-supply-chain.html) by [hasherezade](https://x.com/hasherezade/status/2051671378772795837).
- [RT Guillermo Suarez-Tangil: Perplexity, Claude, Grok, and ChatGPT have been leaking your conversations alongside cookies to third-party ad and trackin...](https://leakylm.github.io/) by [hasherezade](https://x.com/hasherezade/status/2051441977271435772).
- [RT 0xor0ne: Benchmarking Claude Opus 4.6 against Tigress obfuscation (@elasticseclabs) https://www.elastic.co/security-labs/llm-reversing-vs-llm-obfus...](https://www.elastic.co/security-labs/llm-reversing-vs-llm-obfus) by [hasherezade](https://x.com/hasherezade/status/2051380063640117265).
- [RT Cybersecurity by Cyberkid: 🛠️Nice introduction to Windows kernel exploitation for beginners 🔹Part 1: https://mdanilor.github.io/posts/hevd-0...](https://mdanilor.github.io/posts/hevd-0) by [hasherezade](https://x.com/hasherezade/status/2051231327534342425).
- [RT Roger: It's been a while since I wanted to fully understand how the original kamakiri (not the linecode one) exploit worked, so I put up a little w...](https://blog.r0rt1z2.com/posts/dissecting-a-mantis) by [hasherezade](https://x.com/hasherezade/status/2051300563942244368).
- [RT Smukx.E: Exploiting Reversing (ER) series. An step by step Exploitation Technique of Windows Cloud Files Mini Filter Driver Elevation of Privilege ...](https://exploitreversing.com/wp-content/uploads/2026/04/exploit_reversing_09.pdf) by [hasherezade](https://x.com/hasherezade/status/2050589296571134405).
- [RT Hacktron AI: Mythos showed that frontier models can find complex vulnerabilities with a skilled operator in the loop. But for applications that don...](https://www.hacktron.ai/blog/why-mythos-doesnt-matter-for-us) by [shubs](https://x.com/infosec_au/status/2050370620882579471).

</details>


## 🛠️ Tools and Exploits

- [Trailmark turns code into graphs](https://blog.trailofbits.com/2026/04/23/trailmark-turns-code-into-graphs).
> Trail of Bits open-sources Trailmark, a library that parses source code into a queryable call graph (functions, classes, call relationships, semantic metadata) exposed through a Python API that Claude skills can call directly.

- [BlackArrow opens up its talks repository](https://github.com/blackarrowsec/talks) by [BlackArrow](https://x.com/BlackArrowSec/status/2051256944636117349).
> BlackArrow opens up the materials from every talk they have given. Slides, PoCs, and code in one repo.

- [GreyNoise Project Swarm: in-the-wild exploitation telemetry for $1](https://x.com/ItsReallyNick/status/2049906190906228862) by Nick Carr.
> GreyNoise launches Project Swarm. Sensors deployed across the internet to catch in-the-wild exploitation of edge-facing apps, with telemetry available for $1. Andrew Morris frames it as the AI-era response to faster vulnerability discovery.

- [Invoke-ADLabBuildOut adds AD sites and subnets](https://github.com/PyroTek3/ADLab) by [Sean Metcalf](https://x.com/PyroTek3/status/2051360756373868729).
> Sean Metcalf updates Invoke-ADLabBuildOut to spin up AD sites, subnets, and site links on top of the lab build, with common security misconfigurations baked in.

- [MSSQLHound rewritten in Go](https://github.com/Mayyhem/MSSQLHound) by [S3cur3Th1sSh1t](https://x.com/ShitSecure/status/2047991206190145810).
> MSSQLHound rewritten in Go: 17 minutes down to 17 seconds in lab, plus SOCKS proxying, Kerberos and NT hash auth, and pathfinding into BloodHound.

- [SOAPy gains Kerberos auth over ADWS](https://github.com/logangoins/SOAPy) by [Logan Goins](https://x.com/_logangoins/status/2048869191382368471).
> SOAPy now does kerberos auth over ADWS in Python, an integration nobody had bothered to ship in two years. Bigger release coming.

- [net_use BOF: drive mapping without net.exe](https://github.com/atomiczsec/Adrenaline/tree/main/community/net_use) by [Adam Chester 🏴‍☠️](https://x.com/_xpn_/status/2052043344163823887).
> net_use BOF: a modernized port of TrustedSec's SA repo entry for adding, listing, and removing mapped drives via the Windows MPR API. Avoids the telemetry from spawning net.exe or PowerShell.

- [mona v3 released](https://github.com/corelan/mona3) by [ς๏гєɭคภς0๔3г (corelanc0d3r@infosec.exchange)](https://x.com/corelanc0d3r/status/2050177857532370966).
> mona v3 ships: Python 2 and 3, 32 and 64-bit targets, WinDBG and WinDBGX, faster and leaner. The exploit-dev sidekick gets a long-overdue refresh.

- [claude-red: offensive-security skills for Claude](https://github.com/SnailSploit/Claude-Red) by [Jason Lang](https://x.com/curi0usJack/status/2048526433606115762).
> claude-red is a curated library of offensive-security skills for the Claude skills system, each one a structured SKILL.md priming Claude with methodology for a specific attack surface.

- [Puzzle: malware via Windows minifilter abuse](https://github.com/Kudaes/Puzzle) by [hasherezade](https://x.com/hasherezade/status/2050904396704215149).
> Puzzle deploys malware in monitored environments by abusing Windows minifilter functionality. Includes utilities and PoCs to interact with minifilters and explore static and runtime analysis evasion.

- [Microsoft EventLogExpert: an improved Event Viewer](https://github.com/microsoft/EventLogExpert) by [Chris Nickerson](https://x.com/indi303/status/2050058609023651846).
> Microsoft quietly publishes EventLogExpert, an improved Event Viewer for IT and helpdesk teams. Open source, modern UI.


<details markdown="1">
<summary>More this week (8)</summary>

- [Securing the git push pipeline: Responding to a critical remote code execution vulnerability](https://github.blog/security/securing-the-git-push-pipeline-responding-to-a-critical-remote-code-execution-vulnerability) by Alexis Wales.
- [RT asymmetric research: Today we're launching Crucible, a coverage-guided fuzzing framework for Solana programs. Built for Anchor, with v2 support fro...](https://x.com/Dooflin5/status/2051383456182182187) by Maxwell ꓘ Dulin (Strikeout).
- [RT Chris Laub: A Rust dev just killed Headless Chrome. It's called Obscura. The open-source headless browser purpose-built for AI agents and scrapers ...](https://x.com/StevoLowson/status/2048164457168167312) by Steven Lowson.
- [RT Cursor: Cursor Security Review is now available for Teams and Enterprise plans. Run two types of always-on agents: 1. Security Reviewer checks ever...](https://x.com/Teach2Breach/status/2049959559179989441) by K̵i̵r̵k̵ ̵T̵r̵y̵c̵h̵e̵l̵.
- [RT Andy Nguyen: ps5-linux has been released! You can now turn your PS5 Phat console on 3.xx and 4.xx FWs into a fully functional Linux PC gaming devic...](https://github.com/ps5-linux/ps5-linux-loader) by [Alex Plaskett](https://x.com/alexjplaskett/status/2049374142076481642).
- [RT Pwnie Awards: 🚨Nominations for the 2026 Pwnie Awards are now open! Best bug? Worst Bug? Incredible research? Cataclysmic fuckups that knocked ov...](https://tally.so/r/441Aro) by [Alex Plaskett](https://x.com/alexjplaskett/status/2050430686218051926).
- [RT Doug Burks: Just two weeks after the initial release of OhMyPCAP, version 2.0 is here! This new version has TONS of new features including some req...](https://x.com/chrissanders88/status/2051422129912975386) by Chris Sanders 🔎 🧠.
- [RT Bishop Fox: Attackers already see your AI infrastructure. Now you can too. Introducing AIMap, an open-source tool to discover, analyze, and test ex...](https://x.com/dazzyddos/status/2051435057387327721) by Arun.

</details>



