---
title: "Crow's Nest - 2026-05-11"
date: 2026-05-11T00:00:00+00:00
draft: false
tags: ["roundup"]
---

A roundup of 98 items curated from across the security community.

## News

- [Apache ActiveMQ CVE-2026-40466 exploited in the wild](https://x.com/kmkz_security/status/2052503349107261704) by kmkz.
> VulnCheck sees CVE-2026-40466 burning in active campaigns: authenticated RCE in ActiveMQ via the vm:// protocol, a bypass of the original CVE-2026-34197 fix. 2,700+ exposed instances on Shodan.

- [Mythos: a long-form look at the stakes, impact, and PR](https://blog.kwiatkowski.fr/mythos) by [Kuba Gretzky](https://x.com/mrgretzky/status/2048402750485016759).
> Ivan Kwiatkowski's deep-dive cuts through weeks of hot takes about Anthropic's Mythos: what the actual capability claims are, what they mean for the bug-finding economy, and what the rollout did to industry trust.

- [$57K in Chrome bounties from a $20-a-month AI subscription](https://seclab.stanford.edu/RealWorldAIsec/) by [Mathieu Tarral](https://x.com/mtarral/status/2051679118547120607).
> Calif and Mathieu Tarral pocketed two Chrome bugs and $57,000 from Google's VRP using a $20-per-month AI subscription as the harness. Full methodology coming at the Stanford Real World AI Security Conference.

- [Hugging Face and ClawHub poisoned with 575+ malicious AI skills](https://thehackernews.com/2026/05/weekly-recap-ai-powered-phishing.html) by [Rob Fuller](https://x.com/mubix/status/2052710048292327836).
> Thirteen attacker accounts pushed 575+ trojanized skills onto Hugging Face and ClawHub. Payloads hit both Windows and macOS via hidden commands and indirect prompt injection.

- [Solana router: two critical bugs drain token accounts](https://atlas-it.consulting/post/solana-router-vuln) by [Sam Curry](https://x.com/samwcyo/status/2049596235355689464).
> Two critical bugs in a popular Solana router let an attacker drain every token account it owns. Full writeup at atlas-it.consulting.

- [Bleeding Llama: unauthenticated memory leak in Ollama (CVE-2026-7482)](https://www.cyera.com/research/bleeding-llama-critical-unauthenticated-memory-leak-in-ollama).
> Cyera Research uncovers a critical pre-auth memory disclosure in Ollama. Self-hosted LLM gateways leak adjacent buffer contents to anyone who can hit the API.

- [The WebPKI cert renewal apocalypse](https://cabforum.org/2025/04/11/ballot-sc081v3-introduce-schedule-of-reducing-validity-and-data-reuse-periods).
> Dark Tangent on the CA/B Forum schedule that takes TLS cert validity from 350 days down to 47, plus the deprecation of DANE that left the gap in the first place.

- [Fake OpenAI repo on Hugging Face drops infostealer](https://www.bleepingcomputer.com/news/security/fake-openai-repository-on-hugging-face-pushes-infostealer-malware/) by [BleepingComputer](https://x.com/BleepinComputer/status/2053119603987878351).
> Counterfeit OpenAI repo on Hugging Face served an infostealer to anyone who pip-installed it. Useful reminder that model hubs are a supply-chain surface now.


<details markdown="1">
<summary>More this week (13)</summary>

- [Trenchant exec ordered to pay $10M for selling zero-days to Russia](https://www.zetter-zeroday.com/trenchant-exec-who-sold-zero-days-to-russian-buyer-ordered-to-pay-10-million-in-restitution-to-former-employers).
- [CVE-2026-42511: 21-year-old FreeBSD RCE](https://aisle.com/blog/aisle-discovers-cve-2026-42511-a-21-year-old-freebsd-remote-command-execution-vulnerability).
- [MOVEit Automation: critical auth bypass and priv-esc CVEs](https://community.progress.com/s/article/MOVEit-Automation-Critical-Security-Alert-Bulletin-April-2026-CVE-2026-4670-CVE-2026-5174) by [Vincent Yiu](https://x.com/vysecurity/status/2051009329655066894).
- [RansomHouse claims Trellix source-code breach](https://www.bleepingcomputer.com/news/security/trellix-source-code-breach-claimed-by-ransomhouse-hackers) by [BleepingComputer](https://x.com/BleepinComputer/status/2052763427966202314).
- [Zara data breach exposed 197,000 people](https://www.bleepingcomputer.com/news/security/zara-data-breach-exposed-personal-infor) by [BleepingComputer](https://x.com/BleepinComputer/status/2052700692716892489).
- [Ivanti EPMM zero-day exploited in the wild](https://www.bleepingcomputer.com/news/security/ivanti-warns-of-new-epmm-flaw-exploited-in-) by [BleepingComputer](https://x.com/BleepinComputer/status/2052408380669452372).
- [US military data left exposed despite CISA notification](https://www.scworld.com/brief/us-military-data-exposed-in-leaky-directory-despit) by [Nicolas Krassas](https://x.com/Dinosn/status/2052844685668835807).
- [TCLBANKER trojan spreads via WhatsApp and Outlook](https://thehackernews.com/2026/05/tclbanker-banking-trojan-targets) by [Nicolas Krassas](https://x.com/Dinosn/status/2052825199574221080).
- [Fake call-history apps drained payments from 7.3M Play Store users](https://thehackernews.com/2026/05/fake-call-history-apps-stole) by [Nicolas Krassas](https://x.com/Dinosn/status/2052824002553389536).
- [NVIDIA confirms GeForce NOW breach hitting Armenian users](https://www.bleepingcomputer.com/news/security/nvidia-confirms-geforce-now-data-breac) by [Nicolas Krassas](https://x.com/Dinosn/status/2052823877579940013).
- [Concerning features in the official White House app](https://www.scworld.com/brief/analysis-reveals-concerning-features-in-official-white-) by [Nicolas Krassas](https://x.com/Dinosn/status/2052823856297980159).
- [Skoda discloses customer-shop security incident](https://www.skoda-auto.de/unternehmen/sicherheitsvorfall-skoda-shop) by [Nicolas Krassas](https://x.com/Dinosn/status/2053062375855591564).
- [MSRC raises Windows Insider Preview bounty](https://msft.it/6018v3QZI) by [k0shl](https://x.com/KeyZ3r0/status/2052938029757833246).

</details>


## Techniques and Write-ups

- [MariaDB CVE-2026-32710 deep dive: character-constrained overflow to RCE](https://www.zeroday.cloud/blog/mariadb-cve-2026-32710-deep-dive) by [kmkz](https://x.com/kmkz_security/status/2051386774157435177).
> Tim Becker walks through the heap-grooming primitive Xint used to turn a character-constrained heap overflow in JSON_SCHEMA_VALID into full RCE. ZeroDay Cloud's deep dive on the bug behind GHSA-4rj5-2227-9wgc.

- [EasterBunny: 142-page LAB52 report on APT29 espionage](https://lab52.io/blog) by [Lefteris Panos](https://x.com/lefterispan/status/2052450684264419688).
> LAB52 drops a 142-page open-access report on EasterBunny, an advanced espionage toolset attributed to APT29. Full TTPs, samples, and IOCs in one document.

- [Bypassing Windows auth reflection mitigations via Kerberos coercion](https://www.synacktiv.com/en/publications/bypassing-windows-authentication-reflection-mitigations-for-system-shells-part) by [Load.](https://x.com/loadlow/status/2049868200183996636).
> Synacktiv's yaumn_ closes out his Windows auth-reflection series with a new Kerberos coercion technique that remotely compromises Windows systems even with the post-PetitPotam mitigations on. Bonus payload at the end.

- [Hacking Microsoft Copilots: CVE-2026-24299 (Copirate 365)](https://embracethered.com/blog/posts/2026/defcon-) by [Max](https://x.com/maxime_tz/status/2051416672553120072).
> Johann Rehberger's DEF CON Singapore talk writeup on CVE-2026-24299. End-to-end exploitation chain against Microsoft Copilot, full slides and PoCs included.

- [kCaddy: a malleable Caddy redirector for Evilginx](https://knifesec.com/blog/kcaddy-redirector-evilginx) by [Kuba Gretzky](https://x.com/mrgretzky/status/2049437750940561752).
> Walkthrough on putting Caddy in front of Evilginx as a malleable redirector, with kCaddy automating the wiring. M365 and Google Workspace impersonation flows covered.

- [ShadeStager and Phoenix: two new macOS threats added to Objective-See repo](https://9to5mac.com/2026/04/22/mosyle-identifies-two-new-macos-threats-invisible-to-antivirus-engines) by [Patrick Wardle](https://x.com/patrickwardle/status/2048211532904087593).
> Patrick Wardle uploads two fresh Mosyle-discovered macOS samples to the public Objective-See repo: ShadeStager (stealer) and Phoenix (first-stage persistent backdoor). Password infect3d.

- [Recovering AES-128 from a Bluetooth chip via 10-meter RF eavesdrop](https://x.com/podalirius_/status/2051630625984057523) by Rémi GASCOU (Podalirius).
> Crypto-engine switching noise couples into the chip's 2.4 GHz RF chain and leaks out as radio. Owen Brake's writeup shows the AES-128 key recovered from 10 meters away with nothing but a listener.

- [Chinese OPPO phones crack and emulate MIFARE Classic cards in seconds](https://x.com/samwcyo/status/2050732278171803728) by Sam Curry.
> Iceman flags consumer-grade Chinese smartphones that read, crack, and emulate MIFARE Classic cards out of the box. Hotel keys, access control, transit cards: pocket cloning, no extra hardware.

- [CVE-2026-7865: command injection in Crestron touch panels](https://www.cve.org/CVERecord?id=CVE-2026-7865) by [spaceraccoon | Eugene Lim](https://x.com/spaceraccoonsec/status/2052764024052564087).
> spaceraccoonsec lands a CVE on Crestron's enterprise touch panels for unauthenticated command injection. Firmware patch shipped; expect a long tail of unpatched conference-room units.

- [Needle crypto-stealer C2: plaintext API key unlocks 1,932 victims](https://beelzebub.ai/blog/needle-c2-crypto-stealer-analysis).
> beelzebub.ai reverses the Needle crypto-stealer, finds a plaintext API key inside the Rust binary, and walks back into the operator's panel to enumerate 1,932 victims and the withdrawal config.

- [Honey tokens: bait credentials that catch breaches](https://infisical.com/blog/infisical-honey-tokens).
> Infisical lays out a practical honey-token program: how to seed, deploy, and alert on bait credentials so the first sign of compromise is the attacker tripping a wire.

- [Approve once, exploit forever: trust persistence in AI coding agents](https://mindgard.ai/blog/approve-once-exploit-forever-the-trust-persistence-problem-in-ai-coding-agents).
> Mindgard demonstrates that one-time trust grants in Claude Code, Codex, and Gemini CLI become permanent attack surface. Sticky approvals turn into long-lived backdoors.

- [Salesforce Experience Site pentesting: how to be an apex predator](https://www.reco.ai/blog/salesforce-experience-site-pentest-apex-predator).
> Reco.ai catalogs the novel Salesforce Experience Site attack surface: Apex injection, guest-user privilege confusion, and SOQL primitives that turn a misconfigured site into wide reach.

- [Five-bug chain to arbitrary APK install on Samsung Galaxy S25](https://bugscale.ch/blog/here-we-go-again-a-five-bug-chain-to-arbitrary-apk-install-on-samsung-s25) by [ϻг_ϻε](https://x.com/steventseeley/status/2050048524814016683).
> Bugscale chains five separate bugs in Samsung's cloud gaming component to install arbitrary APKs on the Galaxy S25 from an app with no install permissions.

- [Grok prompt-injected into draining $175K from a crypto wallet](https://x.com/vysecurity/status/2051350708214260040) by Vincent Yiu.
> An attacker fed Grok a prompt that walked the agent into authorizing a 3 billion DRB transfer (about $175,000) on Base. Elegant payload, expensive lesson on AI agents wired to crypto rails.

- [CVE-2026-7270: FreeBSD root with a shell script](https://open.substack.com/pub/calif/p/cve-2026) by [Axel Souchet](https://x.com/0vercl0k/status/2052762732785766630).
> CVE-2026-7270, FreeBSD root via a shell script. Calif's writeup of a setuid-program flaw exploitable without compiling a thing. "My human authorized this post" footer included.

- [Where did the complex Windows malware analyses go](https://r136a1.dev/2026/05/07/where-have-all-the-complex-malware-and-their-analyses-gone).
> R136a1 on why blockbuster Windows malware deep-dives have all but vanished. Threat-economics, tooling, and where the analyst pipeline broke.

- [Getting LLMs drunk to find remote Linux kernel OOB writes](https://heyitsas.im/posts/drinking-llms).
> Pushing LLMs past their confident zone to surface remote kernel OOB writes the static fuzzers kept missing. Worked example with code and harnesses.

- [Entra Connect attacker tradecraft series](https://specterops.io/blog/2024/12/13/attacking-entra-metaverse-part-1) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2053052061734908413).
> SpecterOps' three-part deep dive on attacking Entra Connect from sync account to global compromise. Required reading if you operate against hybrid AD.

- [Windows Hello for Business: Faceplant](https://insinuator.net/2025/08/windows-hello-for-buiness-facepla) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2053051829634621481).
> insinuator plants attacker-controlled biometric templates into Windows Hello for Business and walks back out the front door as the victim.

- [cocomelonc malware persistence series (parts 26 to 29)](https://cocomelonc.github.io/persistence/2024/08/14/malware-pers-26.html) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2053051654560178454).
> Four more entries in cocomelonc's long-running persistence catalog: Edge profiles, scheduled tasks, CertPropSvc registry hijack, and Windows Terminal profiles.


<details markdown="1">
<summary>More this week (45)</summary>

- [Silencing ETW Threat Intelligence via BYOVD](https://medium.com/@s12deff/silencing-etw-threat-intelligence-via-byovd-c2ba9e3bb072) by [Panos Gkatziroulis](https://x.com/ipurple/status/2052501473775243607).
- [Cross-Session Activation: CLSIDs for lateral movement](https://ipurple.team/2026/05/04/cross-session-activation) by [Panos Gkatziroulis](https://x.com/ipurple/status/2052058498926604753).
- [CrystalForge: AdaptixC2 beacon with Crystal Palace loader support](https://github.com/k1ng0fn0th1ng/CrystalForge) by [Panos Gkatziroulis](https://x.com/ipurple/status/2052033266362802628).
- [net_use: modernized BOF for mapped drives via MPR API](https://github.com/atomiczsec/Adrenaline/tree/main/community/net_use) by [Panos Gkatziroulis](https://x.com/ipurple/status/2052085370083299535).
- [Silencing EDR network telemetry via WFP callout patching](https://medium.com/@s12deff/silencing-edr-network-telemetry-wfp-callout-patching-via-byovd-1f9ee7ed0e67) by [Panos Gkatziroulis](https://x.com/ipurple/status/2051776469244764621).
- [morphkatz: polymorphic PE rewriter for Windows x64](https://github.com/0xM) by [Panos Gkatziroulis](https://x.com/ipurple/status/2051737155127394456).
- [CVE-2026-6307: Turbofan JS-to-Wasm deopt type confusion](https://tashita.net/turbofan-js-to-wasm-deopt-type-confusion) by [kmkz](https://x.com/kmkz_security/status/2052504986345468154).
- [Pwning V8CTF with TurboFan type confusion (CVE-2025-2135)](https://www.zellic.io/blog/pwning-v8ctf) by [kmkz](https://x.com/kmkz_security/status/2051787888174490008).
- [Wiz launches zeroday.cloud: writeups for PostgreSQL and MariaDB RCEs](https://zeroday.cloud/) by [kmkz](https://x.com/kmkz_security/status/2051387049991610617).
- [GadgetExplorer: .NET deserialization gadget chain finder](https://github.com/nines-nine/GadgetExplorer) by [Lefteris Panos](https://x.com/lefterispan/status/2047993517104910708).
- [Bug bounty writeup repos: HackerOne, Google VRP, Facebook](https://github.com/reddelexc/hackerone-reports) by [Spiros Fraganastasis](https://x.com/m3g9tr0n/status/2051895958036742233).
- [Finding open-source 0-days with an LLM multi-agent workflow](https://blog.cykor.kr/2026/02/How-I-Found-Open-Source-0-day) by [Spiros Fraganastasis](https://x.com/m3g9tr0n/status/2050692504379359671).
- [LLVM-based devirtualizer beats a VM-protected crackme](https://eversinc33.com/2026/05/07/llvm-devirtualizer) by [Max](https://x.com/maxime_tz/status/2052656320562463089).
- [Wi-Fi pentesting in 2026: WPA3 bypasses and RBCD across forests](https://www.synacktiv.com/en/publications/wireless-infidelity-pentest) by [Max](https://x.com/maxime_tz/status/2052457755391271128).
- [The other side of the MCP threat conversation: MCP servers as attack surface](https://www.akamai.com/blog/security/other-side-mcp-threat-conversation) by [Max](https://x.com/maxime_tz/status/2052071812347957516).
- [Bullying LLMs: autonomous vulnerability research with Claude Code and MCP](https://blog.zsec.uk/bullyingllms) by [Max](https://x.com/maxime_tz/status/2052071367399420367).
- [Impacket IoCs: 50+ defender indicators in one repo](https://github.com/ThatTotallyRealMyth/Impacket-IoCs) by [n00py](https://x.com/n00py1/status/2050182460038918194).
- [New Odyssey macOS stealer hides in PLIST files](https://x.com/patrickwardle/status/2052396305293701130) by Patrick Wardle.
- [3Crypt: a macOS RAT zero AV vendors caught](https://x.com/patrickwardle/status/2049069636608761913) by Patrick Wardle.
- [MS-RPC-Fuzzer escalates to SYSTEM via recursive structures](https://www.incendium.rocks/posts/Fuzzing-MS-RPC-structures-and-monitoring) by [Rémi GASCOU (Podalirius)](https://x.com/podalirius_/status/2051590484481429801).
- [ShareHound: BloodHound OpenGraph plugin for network shares](https://github.com/p0dalirius/sharehound) by [Rémi GASCOU (Podalirius)](https://x.com/podalirius_/status/2050518777444303244).
- [EnvWatch: scan for exposed cloud secrets locally](https://github.com/cloudbreach/envwatch) by [Renos](https://x.com/r3n_hat/status/2047952113938911567).
- [FreeBSD dhclient: rogue DHCP server gets root RCE (FreeBSD-SA-26:12)](https://www.freebsd.org/security/advisories/FreeBSD-SA-26:12.dhclient.asc) by [Solar Designer](https://x.com/solardiz/status/2050027322212856090).
- [Linux Kernel Runtime Guard (LKRG) 1.0.1 released](https://www.openwall.com/lists/announce/2026/04/23/1) by [Solar Designer](https://x.com/solardiz/status/2047894308464775418).
- [Discovering vulnerabilities in enterprise AV hardware](https://spaceraccoon.dev/discovering-vulnerabilities-enterprise-audiovisual-hardware) by [spaceraccoon | Eugene Lim](https://x.com/spaceraccoonsec/status/2050141894957768937).
- [Preauth root RCE in Oscar-grade nonlinear editing software](https://infosec.exchange/@codecolorist/116490264321417336).
- [BitLocker bypass in 5 minutes via CVE-2025-48804 downgrade](https://www.intrinsec.com/en/contournement-bitlocker-la-realite-des-downgrade-attacks).
- [Non-determinism of maps in Golang: why, how, and the consequences](https://maxwelldulin.com/BlogPost/Golang-Map-Non-Determinism).
- [Anti-DDoS firm heaped attacks on Brazilian ISPs](https://krebsonsecurity.com/2026/04/anti-ddos-firm-heaped-attacks-on-brazilian-isps).
- [CVE-2026-25654: Siemens SINEC NMS auth bypass priv-esc (ZDI-26-297)](https://www.zerodayinitiative.com/advisories/ZDI-26-297) by [ϻг_ϻε](https://x.com/steventseeley/status/2050082139883053382).
- [Adobe Reader prototype pollution chained to arbitrary file read](https://starlabs.sg/blog/2026/04-three-bugs-walk-into-a-pdf-prototype-pollution-served-cold) by [ϻг_ϻε](https://x.com/steventseeley/status/2049554347240099999).
- [ARP-around and find out: hijacking GPO UNC paths for code exec and NTLM relay](https://trustedsec.com/blog/arp-around-and-find-out-hijacking-gpo-unc-paths-for-code-execution-and-ntlm-relay) by [stuk0v](https://x.com/stuk0v_/status/2049881279017939374).
- [MiniRAT: Go macOS RAT delivered via compromised npm package](https://www.iru.com/blog/minirat) by [Csaba Fitzl](https://x.com/theevilbit/status/2049249866237280630).
- [VeeamDumper-BOF: credential extraction for Veeam Backup and Replication](https://github.com/MWR-CyberSec/VeeamDumper-BOF) by [Mr.Z](https://x.com/zux0x3a/status/2051955745453727938).
- [zig-bof-template: Cobalt Strike BOFs in Zig](https://github.com/nbaertsch/zig-bof-template) by [Mr.Z](https://x.com/zux0x3a/status/2048073292636905661).
- [zig-pe: reflective PE loader written in Zig](https://github.com/Thoxy67/zig-pe) by [Mr.Z](https://x.com/zux0x3a/status/2047778847177793676).
- [Memory poisoning AI agents via ChromaDB](https://mamtaupadhyay.com/2026/05/09/agent-memory-poisoning-demo).
- [Seclens: role-specific LLM eval for vuln detection](https://arxiv.org/abs/2604.01637).
- [Securing CI/CD: lessons from Cilium](https://cilium.io/blog/2026/05/06/securing-cicd-open-source-lessons-from-cilium).
- [Oh myAudi: poking at Audi's connected vehicle APIs](https://decoder.cloud/2026/05/08/oh-myaudi) by [sailay(valen)](https://x.com/404death/status/2052751778186502204).
- [Skip the LSASS theatre: walk the $MFT instead](https://x.com/404death/status/2052425115800084815) by sailay(valen).
- [Former govt contractor convicted for wiping federal databases](https://www.bleepingcomputer.com/news/security/former-govt-contractor-convicte) by [BleepingComputer](https://x.com/BleepinComputer/status/2052671168579059825).
- [JDownloader's official website delivered a Python RAT](https://app.any.run/tasks/e0cecc2d-5571-49fe-a549-cc7d1b8b5908) by [Nicolas Krassas](https://x.com/Dinosn/status/2052766136194699343).
- [Walking through Windows minifilter drivers](https://hackyboiz.github.io/2025/08/15/banda/Minifilter-Driver/en) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2053051947905626354).
- [Commonly abused administrative utilities](https://www.blackhillsinfosec.com/commonly-abused-admini) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2053051773233799399).

</details>


## Tools and Exploits

- [Zellic audit of rust-coreutils: 113 issues, 44 CVEs](https://www.openwall.com/lists/oss-security/2026/05/02/1) by [Solar Designer](https://x.com/solardiz/status/2050598719699952033).
> Zellic's security audit of uutils coreutils lands 113 findings across two rounds (7 critical, 11 high, 29 medium, 26 low) and 44 CVEs. The very codebase Canonical wants shipped by default.

- [BitlockMove: lateral movement via BitLocker DCOM](https://github.com/rtecCyberSec/BitlockMove) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2053052157583114582).
> A new lateral movement primitive that pivots through BitLocker's DCOM service via COM hijacking. PoC drops from rtecCyberSec.


<details markdown="1">
<summary>More this week (9)</summary>

- [Awesome Google VRP writeups](https://github.com/xdavidhu/awesome-google-vrp-writeups) by [kmkz](https://x.com/kmkz_security/status/2051390343837274290).
- [CodeNeedle: stealthy VS Code plugin for arbitrary JS evaluation](https://github.com/chvancooten/code-needle) by [Lefteris Panos](https://x.com/lefterispan/status/2050576650060906625).
- [maSSO: weaponized IdP for Multi-SSO AWS Cognito testing](https://blog.doyensec.com/2026/05/05/cloudsectidbits-masso-cognito-sso.html) by [Maxence SCHMITT](https://x.com/maxenceschmitt/status/2051679190324330865).
- [CVE-2026-41163: bubblewrap setuid root priv-esc via ptrace](https://www.openwall.com/lists/oss-s) by [Solar Designer](https://x.com/solardiz/status/2048953401820475731).
- [CVE-2026-41651: PackageKit TOCTOU leads to local root](https://www.openwall.com/lists/oss-security/2026/04/22/6) by [Solar Designer](https://x.com/solardiz/status/2048953303594111321).
- [Sentinai-Core: AI auditor that red-teams PRs](https://www.npmjs.com/package/sentinai-core).
- [Quacc++: automated open-source vulnerability discovery](https://www.somersetrecon.com/blog/2026/4/27/quacc-automated-open-source-vulnerability-discovery).
- [AiSOC: open-source AI Security Operations Center](https://github.com/beenuar/AiSOC) by [Nicolas Krassas](https://x.com/Dinosn/status/2053021144748261489).
- [NtWarden: Windows analysis and research toolkit](https://github.com/mrT4ntr4/NtWarden) by [Nicolas Krassas](https://x.com/Dinosn/status/2052998055033487797).

</details>



