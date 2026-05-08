---
title: "Crow's Nest - 2026-05-08"
date: 2026-05-08T00:00:00+00:00
draft: false
tags: ["roundup"]
---

A roundup of 38 items curated from across the security community.

## 📰 News

- [Defender for Endpoint: restrict response actions on high-value assets](https://learn.microsoft.com/en-us/defender-endpoint/restrict-response-actions-high-value-assets) by [Sean Metcalf](https://x.com/PyroTek3/status/2051707239463817401).
> Defender for Endpoint adds a public preview to restrict live response actions on high-value assets. The control SOC analysts running scripts as SYSTEM on tier 0 boxes have been asking for.

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

- [Chrome silently installs a 4 GB Gemini Nano model](https://awesomeagents.ai/news/chrome-gemini-nano-silent-install) by [Simone Margaritelli](https://x.com/evilsocket/status/2052336397651005576).
> Chrome silently installs a 4 GB Gemini Nano model file on user devices, no consent prompt, and re-downloads it if you delete it. Turns out the binary is a 6.3B INT4 build of Gemma 3 Nano with FP16 scales.

- [TAPOcalypse Now: exploiting TP-Link smart devices](https://labs.taszk.io/articles/post/tapocalypse) by [Gergely Kalman](https://x.com/gergely_kalman/status/2049608256511709619).
> Taszk Security Labs releases TAPOcalypse: exploiting TP-Link smart devices via LAN, browser, and the cloud account. Vendor fixed some, the rest stand at embargo expiry.

- [LAB52: 142-page EasterBunny report on APT29](https://lab52.io/blog/easterbunny) by [hasherezade](https://x.com/hasherezade/status/2052056422855147685).
> LAB52 publishes a 142-page open-access report on EasterBunny, advanced espionage artifacts attributed to APT29. Plenty for IR teams to feed into hunts.


## 📝 Techniques and Write-ups

- [Bypassing Windows authentication reflection mitigations](https://www.synacktiv.com/en/publications/bypassing-windows-authentication-reflection-mitigations-for-system-shells-part-1) by [Aurélien Chalot](https://x.com/Defte_/status/2048808441016143942).
> Synacktiv kicks off a series on bypassing the CVE-2025-33073 mitigations to pop SYSTEM shells via authentication reflection. Part one is up.

- [VS Code Dev Tunnels: the accidental C2 framework](https://specterops.io/blog/2026/05/06/dev-tunnels-the-accidental-c2) by [N7WEra](https://x.com/N7WEra/status/2052310783971729506).
> REST then WebSocket then SSH then MsgPack RPC. SpecterOps takes apart VS Code Dev Tunnels and finds a C2 framework underneath, with remote exec and file ops on top.

- [cPanel/WHM auth bypass CVE-2026-41940](https://labs.watchtowr.com/the-internet-is-falling-down-falling-down-falling-down-cpanel-whm-authentication-bypass-cve-2026-41940?123=) by [SinSinology](https://x.com/SinSinology/status/2049542180776100326).
> Auth bypass in cPanel/WHM tracked as CVE-2026-41940, full writeup from watchTowr. Also: [high-fidelity scanner from assetnote](https://slcyber.io/research-center/high-fidelity-check-for-the-cpanel-authentication-bypass-cve-2026-41940).

- [OpenAI on the origin of frontier-model jailbreaks](https://openai.com/index/where-the-goblins-came-from) by [K̵i̵r̵k̵ ̵T̵r̵y̵c̵h̵e̵l̵](https://x.com/Teach2Breach/status/2049727149754438053).
> OpenAI on the origin and shape of jailbreak attacks against frontier models. Useful framing if you are building or defending agentic systems.

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

- [Two command injections in Windows context menus](https://specterops.io/blog/2026/05/07/shift-happens-uncovering-two-built-in-command-injections-in-windows-context-menus) by Remi GASCOU.
> SpecterOps finds two command injection bugs in the Windows Explorer "Open PowerShell window here" context menu. A folder name like `folder; calc` triggers arbitrary PowerShell when the user shift-right-clicks.

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


## 🛠️ Tools and Exploits

- [BlackArrow opens up its talks repository](https://github.com/blackarrowsec/talks) by [BlackArrow](https://x.com/BlackArrowSec/status/2051256944636117349).
> BlackArrow opens up the materials from every talk they have given. Slides, PoCs, and code in one repo.

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



