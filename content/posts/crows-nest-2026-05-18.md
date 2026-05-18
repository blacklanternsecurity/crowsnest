---
title: "Crow's Nest - 2026-05-18"
date: 2026-05-18T00:00:00+00:00
draft: false
tags: ["roundup"]
---

A roundup of 44 items curated from across the security community.

## News

- [Bleeding Llama: unauthenticated memory leak in Ollama (CVE-2026-7482)](https://www.cyera.com/research/bleeding-llama-critical-unauthenticated-memory-leak-in-ollama).
> Cyera Research uncovers a critical pre-auth memory disclosure in Ollama. Self-hosted LLM gateways leak adjacent buffer contents to anyone who can hit the API.


<details markdown="1">
<summary>More this week (2)</summary>

- [RansomHouse claims Trellix source-code breach](https://www.bleepingcomputer.com/news/security/trellix-source-code-breach-claimed-by-ransomhouse-hackers) by [BleepingComputer](https://x.com/BleepinComputer/status/2052763427966202314).
- [Zara data breach exposed 197,000 people](https://www.bleepingcomputer.com/news/security/zara-data-breach-exposed-personal-infor) by [BleepingComputer](https://x.com/BleepinComputer/status/2052700692716892489).

</details>


## Techniques and Write-ups

- [MariaDB CVE-2026-32710 deep dive: character-constrained overflow to RCE](https://www.zeroday.cloud/blog/mariadb-cve-2026-32710-deep-dive) by [kmkz](https://x.com/kmkz_security/status/2051386774157435177).
> Tim Becker walks through the heap-grooming primitive Xint used to turn a character-constrained heap overflow in JSON_SCHEMA_VALID into full RCE. ZeroDay Cloud's deep dive on the bug behind GHSA-4rj5-2227-9wgc.

- [EasterBunny: 142-page LAB52 report on APT29 espionage](https://lab52.io/blog) by [Lefteris Panos](https://x.com/lefterispan/status/2052450684264419688).
> LAB52 drops a 142-page open-access report on EasterBunny, an advanced espionage toolset attributed to APT29. Full TTPs, samples, and IOCs in one document.

- [Hacking Microsoft Copilots: CVE-2026-24299 (Copirate 365)](https://embracethered.com/blog/posts/2026/defcon-) by [Max](https://x.com/maxime_tz/status/2051416672553120072).
> Johann Rehberger's DEF CON Singapore talk writeup on CVE-2026-24299. End-to-end exploitation chain against Microsoft Copilot, full slides and PoCs included.

- [Recovering AES-128 from a Bluetooth chip via 10-meter RF eavesdrop](https://x.com/podalirius_/status/2051630625984057523) by Rémi GASCOU (Podalirius).
> Crypto-engine switching noise couples into the chip's 2.4 GHz RF chain and leaks out as radio. Owen Brake's writeup shows the AES-128 key recovered from 10 meters away with nothing but a listener.

- [Chinese OPPO phones crack and emulate MIFARE Classic cards in seconds](https://x.com/samwcyo/status/2050732278171803728) by Sam Curry.
> Iceman flags consumer-grade Chinese smartphones that read, crack, and emulate MIFARE Classic cards out of the box. Hotel keys, access control, transit cards: pocket cloning, no extra hardware.

- [CVE-2026-7865: command injection in Crestron touch panels](https://www.cve.org/CVERecord?id=CVE-2026-7865) by [spaceraccoon | Eugene Lim](https://x.com/spaceraccoonsec/status/2052764024052564087).
> spaceraccoonsec lands a CVE on Crestron's enterprise touch panels for unauthenticated command injection. Firmware patch shipped; expect a long tail of unpatched conference-room units.

- [Salesforce Experience Site pentesting: how to be an apex predator](https://www.reco.ai/blog/salesforce-experience-site-pentest-apex-predator).
> Reco.ai catalogs the novel Salesforce Experience Site attack surface: Apex injection, guest-user privilege confusion, and SOQL primitives that turn a misconfigured site into wide reach.

- [Five-bug chain to arbitrary APK install on Samsung Galaxy S25](https://bugscale.ch/blog/here-we-go-again-a-five-bug-chain-to-arbitrary-apk-install-on-samsung-s25) by [ϻг_ϻε](https://x.com/steventseeley/status/2050048524814016683).
> Bugscale chains five separate bugs in Samsung's cloud gaming component to install arbitrary APKs on the Galaxy S25 from an app with no install permissions.

- [Grok prompt-injected into draining $175K from a crypto wallet](https://x.com/vysecurity/status/2051350708214260040) by Vincent Yiu.
> An attacker fed Grok a prompt that walked the agent into authorizing a 3 billion DRB transfer (about $175,000) on Base. Elegant payload, expensive lesson on AI agents wired to crypto rails.


<details markdown="1">
<summary>More this week (27)</summary>

- [CrystalForge: AdaptixC2 beacon with Crystal Palace loader support](https://github.com/k1ng0fn0th1ng/CrystalForge) by [Panos Gkatziroulis](https://x.com/ipurple/status/2052033266362802628).
- [net_use: modernized BOF for mapped drives via MPR API](https://github.com/atomiczsec/Adrenaline/tree/main/community/net_use) by [Panos Gkatziroulis](https://x.com/ipurple/status/2052085370083299535).
- [morphkatz: polymorphic PE rewriter for Windows x64](https://github.com/0xM) by [Panos Gkatziroulis](https://x.com/ipurple/status/2051737155127394456).
- [Pwning V8CTF with TurboFan type confusion (CVE-2025-2135)](https://www.zellic.io/blog/pwning-v8ctf) by [kmkz](https://x.com/kmkz_security/status/2051787888174490008).
- [Wiz launches zeroday.cloud: writeups for PostgreSQL and MariaDB RCEs](https://zeroday.cloud/) by [kmkz](https://x.com/kmkz_security/status/2051387049991610617).
- [GadgetExplorer: .NET deserialization gadget chain finder](https://github.com/nines-nine/GadgetExplorer) by [Lefteris Panos](https://x.com/lefterispan/status/2047993517104910708).
- [Bug bounty writeup repos: HackerOne, Google VRP, Facebook](https://github.com/reddelexc/hackerone-reports) by [Spiros Fraganastasis](https://x.com/m3g9tr0n/status/2051895958036742233).
- [Finding open-source 0-days with an LLM multi-agent workflow](https://blog.cykor.kr/2026/02/How-I-Found-Open-Source-0-day) by [Spiros Fraganastasis](https://x.com/m3g9tr0n/status/2050692504379359671).
- [The other side of the MCP threat conversation: MCP servers as attack surface](https://www.akamai.com/blog/security/other-side-mcp-threat-conversation) by [Max](https://x.com/maxime_tz/status/2052071812347957516).
- [Impacket IoCs: 50+ defender indicators in one repo](https://github.com/ThatTotallyRealMyth/Impacket-IoCs) by [n00py](https://x.com/n00py1/status/2050182460038918194).
- [MS-RPC-Fuzzer escalates to SYSTEM via recursive structures](https://www.incendium.rocks/posts/Fuzzing-MS-RPC-structures-and-monitoring) by [Rémi GASCOU (Podalirius)](https://x.com/podalirius_/status/2051590484481429801).
- [ShareHound: BloodHound OpenGraph plugin for network shares](https://github.com/p0dalirius/sharehound) by [Rémi GASCOU (Podalirius)](https://x.com/podalirius_/status/2050518777444303244).
- [EnvWatch: scan for exposed cloud secrets locally](https://github.com/cloudbreach/envwatch) by [Renos](https://x.com/r3n_hat/status/2047952113938911567).
- [FreeBSD dhclient: rogue DHCP server gets root RCE (FreeBSD-SA-26:12)](https://www.freebsd.org/security/advisories/FreeBSD-SA-26:12.dhclient.asc) by [Solar Designer](https://x.com/solardiz/status/2050027322212856090).
- [Linux Kernel Runtime Guard (LKRG) 1.0.1 released](https://www.openwall.com/lists/announce/2026/04/23/1) by [Solar Designer](https://x.com/solardiz/status/2047894308464775418).
- [Discovering vulnerabilities in enterprise AV hardware](https://spaceraccoon.dev/discovering-vulnerabilities-enterprise-audiovisual-hardware) by [spaceraccoon | Eugene Lim](https://x.com/spaceraccoonsec/status/2050141894957768937).
- [Preauth root RCE in Oscar-grade nonlinear editing software](https://infosec.exchange/@codecolorist/116490264321417336).
- [Non-determinism of maps in Golang: why, how, and the consequences](https://maxwelldulin.com/BlogPost/Golang-Map-Non-Determinism).
- [Anti-DDoS firm heaped attacks on Brazilian ISPs](https://krebsonsecurity.com/2026/04/anti-ddos-firm-heaped-attacks-on-brazilian-isps).
- [CVE-2026-25654: Siemens SINEC NMS auth bypass priv-esc (ZDI-26-297)](https://www.zerodayinitiative.com/advisories/ZDI-26-297) by [ϻг_ϻε](https://x.com/steventseeley/status/2050082139883053382).
- [ARP-around and find out: hijacking GPO UNC paths for code exec and NTLM relay](https://trustedsec.com/blog/arp-around-and-find-out-hijacking-gpo-unc-paths-for-code-execution-and-ntlm-relay) by [stuk0v](https://x.com/stuk0v_/status/2049881279017939374).
- [VeeamDumper-BOF: credential extraction for Veeam Backup and Replication](https://github.com/MWR-CyberSec/VeeamDumper-BOF) by [Mr.Z](https://x.com/zux0x3a/status/2051955745453727938).
- [zig-bof-template: Cobalt Strike BOFs in Zig](https://github.com/nbaertsch/zig-bof-template) by [Mr.Z](https://x.com/zux0x3a/status/2048073292636905661).
- [zig-pe: reflective PE loader written in Zig](https://github.com/Thoxy67/zig-pe) by [Mr.Z](https://x.com/zux0x3a/status/2047778847177793676).
- [Oh myAudi: poking at Audi's connected vehicle APIs](https://decoder.cloud/2026/05/08/oh-myaudi) by [sailay(valen)](https://x.com/404death/status/2052751778186502204).
- [Former govt contractor convicted for wiping federal databases](https://www.bleepingcomputer.com/news/security/former-govt-contractor-convicte) by [BleepingComputer](https://x.com/BleepinComputer/status/2052671168579059825).
- [JDownloader's official website delivered a Python RAT](https://app.any.run/tasks/e0cecc2d-5571-49fe-a549-cc7d1b8b5908) by [Nicolas Krassas](https://x.com/Dinosn/status/2052766136194699343).

</details>


## Tools and Exploits

- [Zellic audit of rust-coreutils: 113 issues, 44 CVEs](https://www.openwall.com/lists/oss-security/2026/05/02/1) by [Solar Designer](https://x.com/solardiz/status/2050598719699952033).
> Zellic's security audit of uutils coreutils lands 113 findings across two rounds (7 critical, 11 high, 29 medium, 26 low) and 44 CVEs. The very codebase Canonical wants shipped by default.


<details markdown="1">
<summary>More this week (4)</summary>

- [CodeNeedle: stealthy VS Code plugin for arbitrary JS evaluation](https://github.com/chvancooten/code-needle) by [Lefteris Panos](https://x.com/lefterispan/status/2050576650060906625).
- [maSSO: weaponized IdP for Multi-SSO AWS Cognito testing](https://blog.doyensec.com/2026/05/05/cloudsectidbits-masso-cognito-sso.html) by [Maxence SCHMITT](https://x.com/maxenceschmitt/status/2051679190324330865).
- [CVE-2026-41163: bubblewrap setuid root priv-esc via ptrace](https://www.openwall.com/lists/oss-s) by [Solar Designer](https://x.com/solardiz/status/2048953401820475731).
- [CVE-2026-41651: PackageKit TOCTOU leads to local root](https://www.openwall.com/lists/oss-security/2026/04/22/6) by [Solar Designer](https://x.com/solardiz/status/2048953303594111321).

</details>



