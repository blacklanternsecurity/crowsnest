---
title: "Crow's Nest - 2026-10-19"
date: 2026-10-19T00:00:00+00:00
draft: false
tags: ["roundup"]
---

A roundup of 238 items curated from across the security community.

> ### [CVE-2026-79957: IDOR Exposes Cleartext Passwords in ServiceNext](https://blog.blacklanternsecurity.com/p/cve-2026-79957-insecure-direct-object)
>
> Black Lantern Security discovered that any authenticated ServiceNext user could enumerate sequential user IDs and pull every account's cleartext password. Fully disclosed and remediated.
>
> [Read more](https://blog.blacklanternsecurity.com/p/cve-2026-79957-insecure-direct-object)

> ### [IIS Shortname Enumeration Still Opens Doors After 16 Years](https://blog.blacklanternsecurity.com/p/iis-shortname-enumeration-in-the?r=rbmdk)
>
> Black Lantern Security breaks down why this medium-CVSS, 16-year-old default-on IIS finding keeps chaining into critical results on real engagements. Also: [Trezor wallets hit with the same implant technique](https://www.zetter-zeroday.com/trezor-wallets-also-compromised-with-implants).
>
> [Read more](https://blog.blacklanternsecurity.com/p/iis-shortname-enumeration-in-the?r=rbmdk)

## News

- [ConnectWise Supply Chain Attack Hits Microsoft 365 Tenants](https://www.linkedin.com/posts/microsoft-threat-intelligence-is-tracking-share-7517121354568028160-zoMA) by [Florian Roth](https://x.com/cyb3rops/status/2111611236387258513).
> A compromised ConnectWise OAuth app gave attackers access to emails, files, and directory data across hundreds of M365 tenants. Persistent access survived credential revocation; MSP blast radius extends to downstream customers.

- [Hardware Implants in Crypto Wallets Steal $100M](https://www.zetter-zeroday.com/who-is-planting-backdoors-in-ledger-crypto-wallets) by [Kim Zetter](https://x.com/KimZetter/status/2110043995355349037).
> Someone embedded hardware implants in Ledger crypto wallets sold by authorized merchants, harvesting seed phrases and hijacking $100M from 300+ accounts. Trezor also affected.

- [FortiBleed: 86,000 Fortinet Devices Compromised Across 194 Countries](https://itnerd.blog/2026/10/07/fbi-secret-service-warn-fortibleed-campaign-has-compromised-86000-devices) by [Black Hills Information Security](https://x.com/BHinfoSecurity/status/2111140516729328117).
> FBI and Secret Service warn that attackers are selling persistent access to compromised Fortinet devices. The campaign looks more APT than smash-and-grab ransomware.

- [Saudi National Arrested for Planting Listening Device at OpenAI](https://www.justice.gov/opa/pr/saudi-national-arrested-installing-surreptitious-audio-recording-device-openai) by [vx-underground](https://x.com/vxunderground/status/2110133876891017295).
> DOJ charged an OpenAI employee with installing a surreptitious audio recording device. Corporate espionage targeting AI labs is now a law enforcement priority.

- [PAN-OS RCE Flaw Exploited in Active Attacks](https://www.bleepingcomputer.com/news/security/palo-alto-networks-warns-of-pan-os-rce-flaw-exploited-in-attacks) by [BleepingComputer](https://x.com/BleepinComputer/status/2110505197705310305).
> Palo Alto Networks warns of an actively exploited RCE in PAN-OS. Patch immediately.

- [October 2026 Patch Tuesday: 1,411 Vulnerabilities, 3 Zero-Days](https://x.com/BleepinComputer/status/2110098145262899231) by BleepingComputer.
> Record-breaking month. 70 critical flaws, 317 RCEs, 677 privilege escalations. One zero-day is actively exploited in the wild.

- [Mystery of NIST Elliptic Curve Random Numbers Solved](https://www.anthropic.com/research/ecdsa-curve-origins).
> Anthropic researchers traced the unexplained constants in NIST elliptic curves to lrand48 calls seeded with Unix timestamps from the 1990s. No backdoor, just 90s engineering.

- [DOJ Actions Against North Korean IT Worker Scheme](https://www.justice.gov/opa/pr/justice-department-announces-coordinated-actions-combat-north-korean-remote-it-worker) by [Nicolas Krassas](https://x.com/Dinosn/status/2111109163535450249).
> Coordinated DOJ takedown targeting DPRK remote IT worker operations that infiltrated 70+ US companies, funneling wages back to the regime.

- [Chinese APT Exploits BeyondTrust Zero-Day (CVE-2026-102764)](https://cloud.google.com/blog/topics/threat-intelligence/armory-castle-exploits-beyondtrust) by [Florian Roth](https://x.com/cyb3rops/status/2111175034685510080).
> Mandiant and GTIG detail exploitation of a BeyondTrust Remote Support zero-day by Chinese nexus espionage actor ARMORY CASTLE (formerly UNC5221).

- [Citizen Lab: Targeted Ads Turned Into a Spyware Pipeline](https://citizenlab.ca/research/how-discover-tech-turned-targeted-ads-into-a-pipeline-for-spyware) by [Ring3API 🇺🇦](https://x.com/ntlmrelay/status/2111412848345653406).
> Citizen Lab documents how Discover Tech repurposed the ad-tech supply chain to deliver commercial spyware to specific targets via programmatic advertising infrastructure.


<details markdown="1">
<summary>More this week (19)</summary>

- [Recon decides how much you find. Fragmented tools and manual chaining leave data behind. Learn # BBOT with Black Lantern Security at @ bsideschs Nov 6. Free seat, optional donation to # BSides . Save](https://www.zeffy.com/en-US/ticketing/bsides-chs-training-bbot-bighuge-bls-osint-tool).
- [RT Polymarket: BREAKING: Japan declares a "state of emergency in cyberspace" as cyberattacks surge, with more than 20 major companies reporting breach...](https://x.com/vysecurity/status/2109814943256297570) by Vincent Yiu.
- [RT Co11ateral: Using ADStrike to Compromise Active Directory Using ADStrike with Qwen 2.5-Coder to orchestrate an attack on our Active Directory. It h...](https://hackers-arise.com/artificial-intelligence-ai-in-cybersecurity-part-28-using-adstrike-to-compromise-active-directory) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2109752924478009420).
- [Home Assistant Green falls again Last year's #Pwn2Own go2shell chain is now public. There's no place like 127.0.00.1 https://mccaulay.co.uk/...](https://mccaulay.co.uk/go2shell-rooting-home-assistant-through-ssdp) by [McCaulay](https://x.com/_mccaulay/status/2107959435561673136).
- [Microsoft Patches More Than 1,400 Security Flaws](https://krebsonsecurity.com/2026/10/microsoft-patches-more-than-1400-security-flaws) by BrianKrebs.
- [RT Unit 42: New #AI malware: C2Agent is an LLM-operated Windows malware with MCP, skills and living-off-the-AI, abusing the victim's own AI coding too...](https://github.com/PaloAltoNetworks/Unit42-timely-threat-intel/blob/main/2026-10-09-C2Agent-malware.txt) by [kmkz](https://x.com/kmkz_security/status/2109952432138547682).
- [RT Steven Adair: We caught another threat actor using zero-day exploits to compromise an edge device - in this case Ivanti Connect Secure. The used a...](https://x.com/maxime_tz/status/2110276573819445406) by Max.
- [U.K. Sanctions Cryptomus for RU Money Laundering](https://krebsonsecurity.com/2026/10/u-k-sanctions-cryptomus-for-ru-money-laundering) by BrianKrebs.
- [FBI raids DPRK IT worker laptop farms in Texas, US nationals arrested https://www.bleepingcomputer.com/news/security/fbi-raids-dprk-it-worker-laptop-f...](https://www.bleepingcomputer.com/news/security/fbi-raids-dprk-it-worker-laptop-farms-in-texas-us-nationals-arrested) by [BleepingComputer](https://x.com/BleepinComputer/status/2110456116152791413).
- [Langflow's Critical Authenticated RCE Flaw Targeted in 1,423 Honeypot Exploit Attempts https://thehackernews.com/2026/10/langflows-critical-authentica...](https://thehackernews.com/2026/10/langflows-critical-authenticated-rce.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2110671202780102818).
- [https://blackmagick.io update: new technique, BM-T3009 "Browser Relay" uses an attacker browser extension with websockets to turn compromised browser ...](https://blackmagick.io/) by [K̵i̵r̵k̵ ̵T̵r̵y̵c̵h̵e̵l̵](https://x.com/Teach2Breach/status/2110573350443421700).
- [Orange Tsai (@orange_8361) is taking the #HEXACON2026 stage on Oct 16 in Paris with the logic-only Microsoft Edge full chain he used at #Pwn2Own Berli...](https://x.com/d3vc0r3/status/2110664478866215319) by DEVCORE.
- [Top 5 most shared links in my network (Oct 15): 1. https://citizenlab.ca/research/how-discover-tech-turned-targeted-ads-into-a-pipeline-for-spyware/ (...](https://www.theregister.com/cyber-crime/2026/10/14/ransomware-gets-personal-we-know-where-you-are-kind-of-stuff/5302939) by [Ring3API 🇺🇦](https://x.com/ntlmrelay/status/2111050379798499815).
- [Zero-click attacks used targeted ads to deliver Candiru spyware https://www.bleepingcomputer.com/news/security/zero-click-attacks-used-targeted-ads-to...](https://www.bleepingcomputer.com/news/security/zero-click-attacks-used-targeted-ads-to-deliver-candiru-spyware) by [BleepingComputer](https://x.com/BleepinComputer/status/2111145223795445964).
- [Burger King Japan data breach exposes 11 million customer records https://www.bleepingcomputer.com/news/security/burger-king-japan-data-breach-exposes...](https://www.bleepingcomputer.com/news/security/burger-king-japan-data-breach-exposes-11-million-customer-records) by [BleepingComputer](https://x.com/BleepinComputer/status/2111065060541903188).
- [Hackers Use Compromised ConnectWise Credential to Sign In to 173 Microsoft 365 Tenants https://thehackernews.com/2026/10/hackers-use-compromised-conne...](https://thehackernews.com/2026/10/hackers-use-compromised-connectwise.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2111392115494367315).
- [ConnectWise SkyKick Breach: How to Check Your Microsoft 365 Tenant](https://specterops.io/blog/2026/10/17/connectwise-skykick-breach-microsoft-365) by rpepple.
- [RT OpenCode: We had a security breach last night related to a large scale distillation attack that impacted 1.4% of OpenCode Console users We have not...](https://x.com/pentest_swissky/status/2111611797526446377) by Swissky.
- [RT Spycraft101: Seven Chinese nationals were arrested on espionage charges in Turkey in May 2025. According to local press reports, the men were opera...](https://x.com/thegrugq/status/2111467357642375173) by thaddeus e. grugq.

</details>


## Techniques and Write-ups

- [PwnEscape: Guest-to-Host KVM Escape (CVE-2026-99999)](https://pwn.ai/blog/pwnescape) by [/r/netsec](https://x.com/_r_netsec/status/2111050357862490428).
> Full guest-to-host escape via KVM. The most-shared link this week across security Twitter, with 21 independent mentions.

- [iOS 27.0.1 Untethered Jailbreak Demoed at Hexacon](https://calif.io/) by [Stefan Esser](https://x.com/i0n1c/status/2111030553889907137).
> Calif.io demonstrated a full untethered jailbreak on iPhone 18 Pro running iOS 27.0.1 at Hexacon. Persists across reboots.

- [Playing It SFAPE: Code Execution in Isolated User Mode](https://blog.doyensec.com/2026/10/13/Sfape.html) by [/r/netsec](https://x.com/_r_netsec/status/2109940545355489546).
> Doyensec research on achieving code execution inside Windows Isolated User Mode, bypassing one of the platform's strongest trust boundaries.

- [XBOW: Zero to Calc in Six Days, Chrome Full-Chain Exploit](https://xbow.com/labs/research/zero-to-calc-in-six-days-inside-xbow-chrome-full-chain) by [d3d aka dead (dead, мёртв, 死了)](https://x.com/deadvolvo/status/2110094905393721492).
> Detailed technical breakdown of a Chrome full-chain exploit developed by XBOW. From initial renderer bug to sandbox escape to code execution in six days.

- [Bypassing AMSI and ETW with a Custom PowerShell Runspace](https://by7e.dev/blog/runspace) by [Panos Gkatziroulis](https://x.com/ipurple/status/2110281068431429781).
> Walkthrough of building a C# custom PowerShell runspace that sidesteps AMSI and ETW telemetry without the usual suspicious API calls.

- [Infinity Core: 6 Linux Kernel Vulns, Galaxy S26 Root](https://github.com/V4bel/InfinityCore) by [V4bel](https://x.com/v4bel/status/2111125711054688759).
> Six vulnerabilities in Linux kernel core subsystems spanning server LPE, container escape, and Android root from untrusted_app on Galaxy S26 Ultra.

- [Big Fish: Exploiting a 37-Year-Old Kernel Bug in OpenBSD](https://calif.io/research/big-fish) by [Nicolas Krassas](https://x.com/Dinosn/status/2111281345364418744).
> Calif.io found and exploited a kernel vulnerability that has been hiding in OpenBSD since 1989. Full writeup from initial discovery to reliable exploitation.

- [Vercel $1M Sandbox Challenge: Linux Kernel Zero-Day Found](https://vercel.com/blog/findings-from-the-1-million-dollar-vercel-sandbox-challenge) by [Paulos Yibelo](https://x.com/PaulosYibelo/status/2110803656471687626).
> 1,285 reports, $242K in bounties, one Linux kernel zero-day discovered via host network packet parsing. No customer data compromise reported.

- [Tesla Model 3: 0-Click RCE via TPMS Sensors](https://www.synacktiv.com/sites/default/files/2024-10/hexacon_0_click_rce_on_tesla_model_3_through_tpms_sensors_light.pdf) by [thaddeus e. grugq](https://x.com/thegrugq/status/2111906092041269708).
> Synacktiv's second interactionless Tesla exploit chain. VCSEC takeover via TPMS gives direct CAN bus access and the potential for kinetic effects.

- [One Parser, Two Bugs](https://quentinkaiser.be/security/2026/10/16/one-parser-two-bugs) by [thaddeus e. grugq](https://x.com/thegrugq/status/2111562581852975274).
> Quentin Kaiser demonstrates how a single parser implementation yields two distinct exploitable bugs. Clean walkthrough of the analysis process.


<details markdown="1">
<summary>More this week (176)</summary>

- [RT UwU Underground: One of us works adjacent to IR and there's been an interesting campaign that we think deserves some attention. The campaign appear...](https://x.com/thegrugq/status/2109937911785529593) by thaddeus e. grugq.
- [> be me > read this comment from peer > brush it off > nah no way > how would Israel not do shrimple email security > don't even bother checking > fas...](https://gov.il/) by [vx-underground](https://x.com/vxunderground/status/2109749718636986390).
- [postmessage XSS on reveal.js (72k+ github stars) I reported in Aug (now fixed).](https://x.com/0xAsm0d3us/status/2108153968308486339) by devansh.
- [Docker Hub flaw let attackers impersonate users, tamper with images https://www.bleepingcomputer.com/news/security/docker-hub-flaw-let-attackers-imper...](https://www.bleepingcomputer.com/news/security/docker-hub-flaw-let-attackers-impersonate-users-tamper-with-images) by [BleepingComputer](https://x.com/BleepinComputer/status/2110027946186400014).
- [A Windows malware loader uses the encrypted Tox messaging network for command-and-control, avoiding reliance on a fixed C2 server. @varonis ...](https://www.bleepingcomputer.com/news/security/inside-avisloader-a-windows-malware-loader-built-to-resist-disruption) by [BleepingComputer](https://x.com/BleepinComputer/status/2109647777873768895).
- [Retail giant Ahold Delhaize, one of the world's largest food retail chains, confirmed today that it was forced to take some systems offline after a "c...](https://www.bleepingcomputer.com/news/security/retail-giant-ahold-delhaize-takes-systems-offline-after-cyberattack) by [BleepingComputer](https://x.com/BleepinComputer/status/2109643103703322697).
- [GitLab warns of max severity code execution vulnerability https://www.bleepingcomputer.com/news/security/gitlab-warns-of-max-severity-rce-flaw-in-rege...](https://www.bleepingcomputer.com/news/security/gitlab-warns-of-max-severity-rce-flaw-in-regex-compiler-engine) by [BleepingComputer](https://x.com/BleepinComputer/status/2109633238759100819).
- [When LLM Gateways Go Wrong: Findings from LiteLLM https://research.checkpoint.com/2026/when-llm-gateways-go-wrong-findings-from-litellm/](https://research.checkpoint.com/2026/when-llm-gateways-go-wrong-findings-from-litellm) by [Nicolas Krassas](https://x.com/Dinosn/status/2110018770303664504).
- [SAP warns of maximum severity OAuth2 SSRF security flaw https://www.bleepingcomputer.com/news/security/sap-warns-of-maximum-severity-oauth2-ssrf-secur...](https://www.bleepingcomputer.com/news/security/sap-warns-of-maximum-severity-oauth2-ssrf-security-flaw) by [Nicolas Krassas](https://x.com/Dinosn/status/2110013399258014154).
- [LG Smart TVs Vulnerable to Pre-Auth Root Takeover From Local Network https://thehackernews.com/2026/10/lg-smart-tvs-vulnerable-to-pre-auth.html](https://thehackernews.com/2026/10/lg-smart-tvs-vulnerable-to-pre-auth.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2109979264976048211).
- [Two Critical MarkLogic Flaws Could Give Delegated Managers Persistent Admin Control https://thehackernews.com/2026/10/two-critical-marklogic-flaws-cou...](https://thehackernews.com/2026/10/two-critical-marklogic-flaws-could-give.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2109943701069877728).
- [Chinese Cars in Norway Stored Military Exercise Footage and Access Codes https://militarnyi.com/en/news/chinese-cars-in-norway-stored-military-exercis...](https://militarnyi.com/en/news/chinese-cars-in-norway-stored-military-exercise-footage-and-access-codes) by [Nicolas Krassas](https://x.com/Dinosn/status/2109845141796335937).
- [A week after I published interview with new CEO of spyware maker Paragon, AccessNow has sent letter to pension owners who invest in AE Industrial Part...](https://www.wired.com/story/the-secrets-of-the-us-spyware-king) by [Kim Zetter](https://x.com/KimZetter/status/2110021090885923184).
- [Quick Friday macOS malware. Shared by @malwrhunterteam: 29fc5399903e47f7aa13f932ed88ea8770456e2ec860898f2b207d53db075355 - st_helper611b_arm64. Talks ...](https://x.com/L0Psec/status/2108663107824345098) by L0Psec.
- [It's Friday so before the weekend, more DPRK from @malwrhunterteam, starting with this script: 7392bccd63277bc5dec54f97384bb956a1c138bde6d519bc87ff104...](https://x.com/L0Psec/status/2106125865696309574) by L0Psec.
- [If you are a threat hunter or Detection engineer - Baseline your wscript usage. The numbers will be staggering and then take it up the chain to get ws...](https://x.com/M_haggis/status/2106395622894866749) by The Haag™.
- [Whtn is not in the command line, it is loaded at runtime. ™](https://activesoc.blackhillsinfosec.com/blog/a-loader-with-no-command-line) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2110000775569244306).
- [New one from @pruvadev now that sandboxes are hot agian: CVE-2026-96812: gVisor directfs openHandle host-FD identity TOCTOU → guest-to-host sandbox e...](https://www.pruva.dev/reproductions/REPRO-2026-00382) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2108514848988397813).
- [Samsung: https://libimagecodec.quram.so Heap Buffer Overflow in DNG Uncompressed Tile Decoding (QuramDngReadImage::readUncompressed) https://project-z...](https://project-zero.issues.chromium.org/issues/527353503) by [Project Zero Bugs](https://x.com/ProjectZeroBugs/status/2109984193501602177).
- [RT Merill Fernando: Did you know that if you have Entra ID P1 there is a new way to block your stolen refresh token from being replayed by the attacke...](https://x.com/PyroTek3/status/2109713586226630998) by Sean Metcalf.
- [Input payload obfuscation is a real game changer here. No AMSI or ETW bypass needed and memory scanner evasion](https://www.msecops.de/blog/posts/rustpack-180-features) by [S3cur3Th1sSh1t](https://x.com/ShitSecure/status/2108926870733668620).
- [UK🇬🇧 FCDO Joint Statement on Iran🇮🇷, 12 October (Official attribution of RAF Fairford🇬🇧 event to Iran IRGC🇮🇷 using cover n...](https://www.gov.uk/government/news/joint-statement-on-iran-12-october) by [SwitHak ()](https://x.com/SwitHak/status/2109691645746720894).
- [In 2023, @Synacktiv researchers identified an authentication bypass in #Danfoss SM800 and SC255/SC355 controllers. The same vulnerability, reported ag...](https://www.synacktiv.com/sites/default/files/2023-10/synacktiv-danfoss-sm800a-multiple-vulnerabilities.pdf) by [Synacktiv](https://x.com/Synacktiv/status/2110035129565401214).
- [We Let AI Fuzz Adobe Reader for a Week. It Found a Critical Zero-Day CVE-2026-81983 https://remedio.io/blog/cve-2026-81983-integer-overflow-vulnerabil...](https://remedio.io/blog/cve-2026-81983-integer-overflow-vulnerability-enables-out-of-bounds-write-in-adobe-acrobat) by [/r/netsec](https://x.com/_r_netsec/status/2110016042802237443).
- [frontier class vulnerabilities: it gets worse before it (maybe) gets better https://shubs.io/frontier-class-vulnerabilities-it-gets-worse-before-it-ma...](https://shubs.io/frontier-class-vulnerabilities-it-gets-worse-before-it-maybe-gets-better) by [/r/netsec](https://x.com/_r_netsec/status/2109812200261239135).
- [The October 2026 Security Update Review](https://www.thezdi.com/blog/2026/10/13/the-october-2026-security-update-review) by Dustin Childs.
- [printer vendors love it when you crack their toner DRM and start selling counterfeit cartridges/refills](https://github.com/morluto/rea) by [blasty](https://x.com/bl4sty/status/2109940370763292833).
- [CVE-2026-107651 Eye of Gnome (eog) Heap Buffer Overflow PoC https://gist.github.com/EgeBalci/2dca1fb72229547a015ca48fae66dddf](https://gist.github.com/EgeBalci/2dca1fb72229547a015ca48fae66dddf) by [ege](https://x.com/egeblc/status/2109692376889667801).
- [Safari wanted a decryption key. @AmirMSafari gave it alert(1). Two fresh XSS vectors using , and onwebkitneedkey just landed in our Por...](https://x.com/garethheyes/status/2109999115841220737) by Gareth Heyes \u2028.
- [Last night I updated Shazzer to improve the fuzz result toast. It's now more compact and you can see fuzz results for each browser in your personal ne...](https://x.com/garethheyes/status/2109969820452303220) by Gareth Heyes \u2028.
- [Another XSS vector for our cheat sheet, this time using Special mention to @AmirMSafari, who found this one and has contributed so many ex...](https://x.com/garethheyes/status/2107463389039689908) by Gareth Heyes \u2028.
- [Building on my research, my colleague @Alex_______C exfiltrated a 600-character hex token instantly using just background images and selectors. No rec...](https://x.com/garethheyes/status/2107127534382969128) by Gareth Heyes \u2028.
- [Chrome's new tag has something to say: Another XSS vector for our cheat sheet, found by @omidxrz.](https://x.com/garethheyes/status/2105651444762481000) by Gareth Heyes \u2028.
- [Chrome added a tag. @omidxrz made it an XSS vector: Now in our XSS cheat sheet.](https://x.com/garethheyes/status/2105289062487855361) by Gareth Heyes \u2028.
- [Full static & memory analysis of Overlord RAT: Go agent architecture HTTP/2 + WebSocket C2 Reflective DLL injection Browser keylogging IOCs ...](https://github.com/kaandemir993/Overlord-RAT-Reverse-Engineering-a-Go-Based-RAT-Injection-Keylogging-C2-Exfiltration-Analysis) by [Panos Gkatziroulis](https://x.com/ipurple/status/2110104550644359639).
- [DLL Injection with SetWinEventHook: The Accessibility Hook as an Injector by @zodiacon https://trainsec.net/library/windows-internals/dll-injection-wi...](https://trainsec.net/library/windows-internals/dll-injection-with-setwineventhook-the-accessibility-hook-as-an-injector) by [Panos Gkatziroulis](https://x.com/ipurple/status/2109996576105959585).
- [The forgotten SSH-Harvester has just been upgraded to use eBPF uprobe! Not only that, #emp3r0r now supports on-demand and in-memory library loading, i...](https://x.com/jm33_m0/status/2106905020298068445) by jm33_ng.
- [RT Matthew Green: “OpenAI in talks to buy Trail of Bits” https://www.theinformation.com/articles/openai-early-talks-buy-security-startup-trail-...](https://www.theinformation.com/articles/openai-early-talks-buy-security-startup-trail-bits) by [kmkz](https://x.com/kmkz_security/status/2110242677820166629).
- [RT Mia: I've finally published the write up on my Pwn2Own exploit!!! https://github.com/newbe3e/Pwn2Own-Automotive-2026-Alpine-iLX-F511-0-Click-RCE-Ex...](https://github.com/newbe3e/Pwn2Own-Automotive-2026-Alpine-iLX-F511-0-Click-RCE-Exploit-Writeup) by [kmkz](https://x.com/kmkz_security/status/2110097975925989542).
- [RT Ziyi Guo: "Bad UVM" - Privilege Escalation, Container Escape via NVIDIA GPU UVM - hijack read-only page cache. More details: https://medium.com/@gu...](https://medium.com/@guoziyi114/bad-uvm-hijack-readonly-page-cache-via-nvidia-uvm-7accc7e3181e) by [kmkz](https://x.com/kmkz_security/status/2109954857721323920).
- [Some possible interesting fake "POS Terminal Maintenance Update" sites giving very low detected malware: https://alohapos-update[.]com/ https://instan...](https://x.com/malwrhunterteam/status/2110094925232537816) by MalwareHunterTeam.
- [](https://rogueauthority.org/spyder-rebuilt-patchwork-downloader) by [MalwareHunterTeam](https://x.com/malwrhunterteam/status/2110049429571108971).
- [PentestAssistant: an LLM harness for autonomous whitebox web application pentesting. Combines source code analysis with dynamic exploitation, vulnerab...](https://github.com/AmadeusITGroup/PentestAssistant) by [Max dcb](https://x.com/max2cbx/status/2109992549502873786).
- [RT 0x12 Dark Development: Stealing Plaintext Windows Credentials New Medium post, in this one we will see how to steal plaintext Windows credentials a...](https://medium.com/@s12deff/stealing-plaintext-windows-credentials-logonstealer-26bbed6c3875) by [Max](https://x.com/maxime_tz/status/2110272061985693829).
- [Break the silence: Kazakhstan-nexus UAT-6275 targets CIS government organizations](https://blog.talosintelligence.com/break-the-silence-kazakhstan-nexus-uat-6275-targets-cis-government-organizations) by Ashley Shen.
- [Cyberattack on Connected Fridges in France](https://www.schneier.com/blog/archives/2026/10/cyberattack-on-connected-fridges-in-france.html) by Bruce Schneier.
- [We backdoored a 7B open model for under $50. Pointed Codex at it -> it silently stole credentials the moment we hit the trigger phrase. ->100% hit rat...](https://x.com/pdiscoveryio/status/2107522665951227970) by ProjectDiscovery.
- [Google's PageBreak Project – Real-World Findings https://bughunters.google.com/blog/pagebreak-real-world-findings](https://bughunters.google.com/blog/pagebreak-real-world-findings) by [Swissky](https://x.com/pentest_swissky/status/2110375070363189593).
- [The Binding Gap: The MCP Tool Your Agent Vetted Is Not the Tool It Calls https://x.com/i/broadcasts/1NxaroYWPoDKj](https://x.com/pomerium_io/status/2110075961727410192) by Pomerium.
- [stackd is out: AWS on your own machine, running a very good approximation of the real thing. Existing AWS emulators weren't enough for me, especially ...](https://x.com/rad9800/status/2106333810237292935) by Rad.
- [Lights Out: BMCs hold immense authority over server hardware and can be an overlooked attack surface. runZero’s BMC research details vulnerabili...](https://www.runzero.com/blog/lights-out-exposed) by [runZero, Inc.](https://x.com/runZeroInc/status/2110027764795379909).
- [RT Zack Korman: OpenAI just revealed that an employee stole over a hundred highly confidential files months ago, and they didn't notice until now. The...](https://x.com/scriptjunkie1/status/2110410495744479733) by scriptjunkie (Matt).
- [RT Joseph Cox: New: an AI company now lets cops identify specific houses, using data from Zillow/Airbnb, based on a single photo. It's part of Raven, ...](https://www.404media.co/ai-company-lets-cops-pinpoint-specific-houses-based-on-a-single-interior-photo) by [thaddeus e. grugq](https://x.com/thegrugq/status/2110403678075277680).
- [RT Dino A. Dai Zovi: Called it. Reverse engineering of mobile apps is now much easier and can be used to target their supporting back-end APIs, possib...](https://www.nict.go.jp/press/2026/10/13-1.html) by [thaddeus e. grugq](https://x.com/thegrugq/status/2110086242721489344).
- [RT Dr. Dan Lomas: Russian-aligned spies upgrade malware used in attacks on Ukrainian transport, energy firms https://therecord.media/russia-ukraine-ma...](https://therecord.media/russia-ukraine-malware-transportation) by [thaddeus e. grugq](https://x.com/thegrugq/status/2110051380367143219).
- [Taking inspiration from @0x3lk's STHACK talk, here is a technique to run your shellcode using CLR's DynamicMethods/JIT internals/Exception handling me...](https://github.com/whokilleddb/3lkToShell) by [db](https://x.com/whokilleddb/status/2110371495767908455).
- [RT Hussein Muhaisen: Just added native @Droid / @FactoryAI support to our open-source firmware reverse engineering toolkit. 5 skills extraction, stati...](https://github.com/OrbitCurve/firmware-reverse-engineering) by [x86byte](https://x.com/x86byte/status/2110345452079964321).
- [We worked a ClickFix chain where every hop before the payload was https://google.com or https://openai.com. The final host wasn't a domain or an IP: i...](https://activesoc.blackhillsinfosec.com/blog/trusted-hops-integer-hosts) by [Black Hills Information Security](https://x.com/BHinfoSecurity/status/2110440068540203492).
- [Cisco patches new Secure Email Gateway zero-day exploited in attacks https://www.bleepingcomputer.com/news/security/cisco-patches-actively-exploited-s...](https://www.bleepingcomputer.com/news/security/cisco-patches-actively-exploited-secure-email-gateway-zero-day) by [BleepingComputer](https://x.com/BleepinComputer/status/2110422760203620843).
- [Hirudo Android malware replaces banking apps to evade security checks https://www.bleepingcomputer.com/news/security/hirudo-android-malware-replaces-b...](https://www.bleepingcomputer.com/news/security/hirudo-android-malware-replaces-banking-apps-to-evade-security-checks) by [BleepingComputer](https://x.com/BleepinComputer/status/2110335545733767171).
- [I've opened up the five VirtualBox issues in the PZ tracker. 4 of them are bypasses of the VB process hardening (including one which is a broken fix from 2019 due to changes in Windows). Of most inter](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-108398).
- [GhostAction Compromises About 1,900 GitHub Accounts, Targets Over 30,000 Repositories https://thehackernews.com/2026/10/ghostaction-compromises-about-...](https://thehackernews.com/2026/10/ghostaction-compromises-about-1900.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2110670990028267994).
- [UK Legal Aid Agency: Hackers stole records dating back to 1978 https://www.bleepingcomputer.com/news/security/uk-legal-aid-agency-hackers-stole-record...](https://www.bleepingcomputer.com/news/security/uk-legal-aid-agency-hackers-stole-records-dating-back-to-1978) by [Nicolas Krassas](https://x.com/Dinosn/status/2110650879569281097).
- [Jev and other decision models can still be tricked with prompt injection https://www.theregister.com/ai-and-ml/2026/10/15/jev-and-other-decision-model...](https://www.theregister.com/ai-and-ml/2026/10/15/jev-and-other-decision-models-can-still-be-tricked-with-prompt-injection/5303184) by [Nicolas Krassas](https://x.com/Dinosn/status/2110643280853487667).
- [This repository contains research and proof-of-concept material for a Windows privilege-boundary issue involving the Windows Health and Optimized Expe...](https://github.com/Beardhammer/CVE-2026-85884) by [Nicolas Krassas](https://x.com/Dinosn/status/2110602375819891007).
- [Anthropic's Sept 2026 threat report: attackers prompt-injected an eval sandbox, stole customer API keys, then burned the victims' own compute to attac...](https://anthropic.com/threat-intelligence-report-september-2026) by [Nicolas Krassas](https://x.com/Dinosn/status/2110567006831566896).
- [Unit 42 Uncovers PEERSTITCH, a Stealthy FortiGate Implant https://unit42.paloaltonetworks.com/fortimanager-cve-2024-47575-peerstitch-malware/](https://unit42.paloaltonetworks.com/fortimanager-cve-2024-47575-peerstitch-malware) by [Nicolas Krassas](https://x.com/Dinosn/status/2110565145143320647).
- [RT Matthew Green: I notified Anthropic of these cross-session replay attacks in May, and was told that “it isn’t an attack”. I continue to be aggra...](https://www.anthropic.com/research/distillation-defenses) by [Nicolas Krassas](https://x.com/Dinosn/status/2110604218453393735).
- [RT TrustedSec: The Yandex data center strikes are sparking an important conversation about infrastructure and cyber operations. Director of Security I...](https://www.newsweek.com/could-ukraine-strikes-russian-data-center-impact-bots-12556164) by [Dave Kennedy](https://x.com/HackingDave/status/2110510864331640908).
- [RT Binary Defense: Last weeks Citrix 0-Day laid an egg and your SIEM likely never saw it. Attackers hid a payload in a NetScaler crash log and dropped...](https://hubs.li/Q04B7yL_0) by [Dave Kennedy](https://x.com/HackingDave/status/2110410076162802103).
- [CVE-2026-89111: SAP Cloud SDK for Python is vulnerable to OAuth2 SSRF that can exfiltrate client credentials when tenant subdomain is attacker-control...](https://www.pruva.dev/reproductions/REPRO-2026-00387) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2110729066164740509).
- [VirtualBox: IDispatch COM Object Interop Process Hardening Bypass EoP https://project-zero.issues.chromium.org/issues/544666386](https://project-zero.issues.chromium.org/issues/544666386) by [Project Zero Bugs](https://x.com/ProjectZeroBugs/status/2110671149113975265).
- [The Q3 Vulnerability Pulse: Discovery ≠ Exploitation](https://blog.talosintelligence.com/the-q3-vulnerability-pulse-discovery-exploitation) by Thorsten Rosendahl.
- [RT TheZDIBugs: [ZDI-26-757|CVE-2026-111105] (0Day) (Telegram rlottie Numeric Truncation Remote Code Execution Vulnerability (CVSS 7.0; Credit: Michael...](https://www.zerodayinitiative.com/advisories/ZDI-26-757) by [SinSinology](https://x.com/SinSinology/status/2110790866809827476).
- [Don't disappoint @lorenzofb click this https://www.404media.co/cops-can-bypass-iphone-automatic-inactivity-reboot-graykey/](https://www.404media.co/cops-can-bypass-iphone-automatic-inactivity-reboot-graykey) by [SwiftOnSecurity](https://x.com/SwiftOnSecurity/status/2110240969559851365).
- [RT CISA Cyber: We added Ivanti Connect Secure vulnerability CVE-2026-104935 to the KEV Catalog after observed exploitation. A remote attacker cou...](https://go.dhs.gov/5Kc) by [SwitHak ()](https://x.com/SwitHak/status/2110191959432196443).
- [If you've got an UniFi Protect AI Key, best get updating @Ubiquiti just patched a 6 bug chain and published the relevant CVEs :) good news is latest v...](https://community.ui.com/releases/Security-Advisory-Bulletin-070-070/e7ffc9fa-9129-4a90-b5e3-d597c5ee7a73) by [Andy Gill](https://x.com/ZephrFish/status/2110347903294156874).
- [Trivy and govulncheck found the same vulnerability, but the code wasn't in the binary https://www.a3thinker.it/articles/not-in-the-binary/](https://www.a3thinker.it/articles/not-in-the-binary) by [/r/netsec](https://x.com/_r_netsec/status/2110740818692878464).
- [AhsayCBS Deep-Dive: Auth Bypass to RCE https://horizon3.ai/attack-research/attack-blogs/ahsaycbs-cve-2026-105133-cve-2026-105134-technical-analysis/](https://horizon3.ai/attack-research/attack-blogs/ahsaycbs-cve-2026-105133-cve-2026-105134-technical-analysis) by [/r/netsec](https://x.com/_r_netsec/status/2110416179038937403).
- [tensorlake@0.5.144: A Worm With Valid Provenance, and the Firewall Rule That Stops It https://hextrap.io/blog/tensorlake05144-a-worm-with-valid-proven...](https://hextrap.io/blog/tensorlake05144-a-worm-with-valid-provenance-and-the-firewall-rule-that-stops-it) by [/r/netsec](https://x.com/_r_netsec/status/2110370880312471773).
- [Vghost (CVE-2026-74580): Linux kernel vhost stale IOTLB cache leading to universal LPE and Guest-to-Host escape vector https://www.openwall.com/lists/...](https://www.openwall.com/lists/oss-security/2026/10/14/2) by [/r/netsec](https://x.com/_r_netsec/status/2110212335889686784).
- [Tech details for these bugs now public https://www.nccgroup.com/research/technical-advisory-microsoft-windows-midi-service-module-escalation-of-privil...](https://www.nccgroup.com/research/technical-advisory-microsoft-windows-uaspstorsys-device-controlled-kernel-pool-oob-write-via-report-luns-cve-2026-68839) by [Alex Plaskett](https://x.com/alexjplaskett/status/2110688730033893853).
- [RT naci: Wrote up my attempt at deobfuscating Luraph-protected Lua: lifting Lua to LLVM IR , then using AI + partial evaluation to strip the VM, and c...](https://nac-l.github.io/2026/10/12/deobfuscating-luraph.html) by [Alex Plaskett](https://x.com/alexjplaskett/status/2110624906476175420).
- [You’d expect a lockfile to make a dependency immutable. But often it doesn’t: a hacked repository can swap in malicious code for the **same package ...](https://blog.trailofbits.com/2026/10/14/package-managers-have-an-integrity-problem) by [Dan Guido](https://x.com/dguido/status/2110724081557409939).
- [RT Mr.Niko: CVE-2026-43748 ANE kernel OOB write direct-path user client. no special entitlements. sandboxed app on iOS and macOS. kANEMaxBuffers ...](https://github.com/vschko/CaseStudies/tree/main/CVE-2026-43748) by [rpw](https://x.com/esizkur/status/2110708721756365272).
- [ReflectivePluginLoader - Maps a DLL from a byte buffer in memory, resolves exports, and calls plugin functions either from anonymous memory (classic r...](https://github.com/racoten/ReflectivePluginLoader) by [Panos Gkatziroulis](https://x.com/ipurple/status/2110995566452945329).
- [A canvas for red team infrastructure and cyber ranges. Compose a topology, export runnable Terraform and Ansible, and deploy it yourself. Your cloud c...](https://github.com/devZero-Security/redStackPRO) by [Panos Gkatziroulis](https://x.com/ipurple/status/2110775902368137575).
- [Cross-process instrumentation for Windows x64 in TypeScript Hook Functions Redirect Threads, and Read/write memory in another process, with n...](https://github.com/woldann/exoproc) by [Panos Gkatziroulis](https://x.com/ipurple/status/2110728338838864359).
- [Nice read by Sentinel and some interesting numbers like: "Ransomware actors successfully disabled security tools in about 48% of intrusions in 2024." ...](https://www.sentinelone.com/blog/bring-your-own-vulnerable-driver-how-edr-killing-became-an-industry) by [Panos Gkatziroulis](https://x.com/ipurple/status/2110445176040693915).
- [Backdooring Open-Weight AI Models](https://www.schneier.com/blog/archives/2026/10/backdooring-open-weight-ai-models.html) by Bruce Schneier.
- [RT dbugs: Three Apple Ecosystem Vulnerabilities: Zero-Click Memory Corruption, iCloud Sender Spoofing, and Root Privilege Escalation Read on dbugs: ht...](https://dbu.gs/news/three-apple-ecosystem-vulnerabilities-zero-click-memory-corruption-icloud-sender-spoofing-and-root-privilege-escalation-20261015) by [kmkz](https://x.com/kmkz_security/status/2111053678006178289).
- [RT JFrog Security: RCE in curl (CVE-2026-92392, HIGH Severity) A malicious HTTP/2 server can turn a use-after-free during uploads into remot...](https://x.com/kmkz_security/status/2110843304787255544) by kmkz.
- [RT HeeChan Kim: 8 vulnerabilities I reported were patched in this Patch Tuesday: 1. CVE-2026-96243 2. CVE-2026-88070 3. CVE-2026-83586 4. CVE-2026-838...](https://x.com/kmkz_security/status/2110668999369380064) by kmkz.
- [RT Mr.Niko: iOS 26.1. WebContent R/W to native calls. pois0nSword chains CVE-2025-43529 into cage-free read64/write64, then beats PAC with CVE-20...](https://github.com/GenericCoding/pois0nSword) by [kmkz](https://x.com/kmkz_security/status/2110613742895444441).
- [RT quarkslab: Reports can be the fun part of a pentest.. if the target uses MyReport. @kaluche_ found a third-party updater running as SYSTEM, an unau...](https://blog.quarkslab.com/myreport-updater-from-grpc-to-system.html) by [kmkz](https://x.com/kmkz_security/status/2110784297439265233).
- [](https://rogueauthority.org/signed-security-health-service-winos-backdoor) by [MalwareHunterTeam](https://x.com/malwrhunterteam/status/2111063629361545305).
- [The are multiple suspicious, recently registered domains resolving to 158.94.210[.]145: cloudeliverrs[.]com cloudeliverenterprise[.]com cloudenterpris...](https://x.com/malwrhunterteam/status/2111017138790056108) by MalwareHunterTeam.
- [EVILGINX EXTENSION IS OUT I am happy to say the free Evilginx Chrome extension has been approved and is finally available for download. ...](https://x.com/mrgretzky/status/2110704979157692697) by Kuba Gretzky.
- [Top 5 most shared links in my network (Oct 14): 1. https://abraxaslabs.tech/research/pfsense-carp-vhid (9 people) 2. https://abraxaslabs.tech/research...](https://abraxaslabs.tech/research/pfsense-openvpn-wizard-crlf) by [Ring3API 🇺🇦](https://x.com/ntlmrelay/status/2110687909959671999).
- [Neat ChatGPT bug Found manually (even after @OpenAI “pointed Astra at its own systems until it ran out of bugs") Local (unpriv'd) attacker: • H...](https://x.com/patrickwardle/status/2110719750351515971) by Patrick Wardle.
- [We found live API keys from NVIDIA, Nutanix and AllenAI employees just sitting on public GitHub. -> some could upload models under the company's name ...](https://x.com/pdiscoveryio/status/2110387041590710506) by ProjectDiscovery.
- [How to use Codex for Bug Bounty research: explore broadly, validate rigorously - @yeswehack https://www.yeswehack.com/learn-bug-bounty/llm-series-code...](https://www.yeswehack.com/learn-bug-bounty/llm-series-codex) by [Swissky](https://x.com/pentest_swissky/status/2111107144770572772).
- [How I Could've Accessed 17 Trillion Microsoft Records - @efaav https://blog.faav.net/how-i-couldve-accessed-17-trillion-microsoft-records](https://blog.faav.net/how-i-couldve-accessed-17-trillion-microsoft-records) by [Swissky](https://x.com/pentest_swissky/status/2110737458166182226).
- [RT Thomas Seigneuret: Little upgrade on NetExec WMI protocol Now NetExec supports SAM, LSA and NTDS dump using only WMI. Thanks a lot to @al3x_n3...](https://x.com/pentest_swissky/status/2110462642859237870) by Swissky.
- [RT Perplexity: We're open sourcing SPACE, the sandbox platform that runs every task in Perplexity Computer. SPACE gives each agent task its own Firecr...](https://github.com/perplexityai/SPACE?tab=Apache-2.0-1-ov-file) by [thaddeus e. grugq](https://x.com/thegrugq/status/2111179845917106318).
- [RT Byron Wan: According to a court document filed by the FBI on Oct 13, Fatai Miao is in a romantic relationship with Wanying “Heather” Zhang (...](https://x.com/thegrugq/status/2110893534731723251) by thaddeus e. grugq.
- [wE foUnd SignS of LiFe wiTh AI WorMs tHat CoLoNize hOusEhOlD deViceS](https://www.theverge.com/ai-artificial-intelligence/1011108/anthropic-self-replicating-ai-smart-devices-risk) by [vx-underground](https://x.com/vxunderground/status/2111216701073445055).
- [RT Meelo: No more setting up and juggling multiple tools when doing an android assessment on a PHYSICAL DEVICE. https://github.com/capt-meelo/loupe #i...](https://github.com/capt-meelo/loupe) by [Mr.Z](https://x.com/zux0x3a/status/2111053788996120937).
- [RT @ArmadinSecurity: We’ve found unauthenticated RCEs across multiple SolarWinds products. This kill chain is in Orion: multiple vulnerabil…](https://x.com/AndrewOliveau/status/2110805570597134784) by Andrew Oliveau.
- [RT Armadin: Armadin researcher @mhskai2017 has uncovered an authenticated RCE vulnerability in Skype for Business Server (CVE-2026-70297, CVSS 8.8). A...](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-70297) by [Andrew Oliveau](https://x.com/AndrewOliveau/status/2110773702359241091).
- [We found a translator extension that changed hands via a lapsed domain and spent 99 days reporting every URL a finance user visited. Endpoint controls...](https://activesoc.blackhillsinfosec.com/blog/a-translator-extension-a-lapsed-domain-and-87000-installs) by [Black Hills Information Security](https://x.com/BHinfoSecurity/status/2110850755196326391).
- [RT Marcus Williams: New misalignment disclosures! 1. June 17: During RL training, a model exploited a government website’s file-download feature to r...](https://x.com/BillDemirkapi/status/2110927025921986587) by Bill Demirkapi.
- [Microsoft: October Windows update may break Smart App Control https://www.bleepingcomputer.com/news/microsoft/kb5127648-windows-security-update-may-br...](https://www.bleepingcomputer.com/news/microsoft/kb5127648-windows-security-update-may-break-smart-app-control) by [BleepingComputer](https://x.com/BleepinComputer/status/2111017646262997452).
- [BAE Systems cyberattack disrupts US federal court operations https://www.bleepingcomputer.com/news/security/bae-systems-cyberattack-disrupts-us-federa...](https://www.bleepingcomputer.com/news/security/bae-systems-cyberattack-disrupts-us-federal-court-operations) by [BleepingComputer](https://x.com/BleepinComputer/status/2110998641057861774).
- [BeyondTrust patches zero-day exploited in attacks since August https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-i...](https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august) by [BleepingComputer](https://x.com/BleepinComputer/status/2110978637646152121).
- [Hackers exploit Collabora RCE flaw to backdoor Nextcloud servers https://www.bleepingcomputer.com/news/security/hackers-exploit-collabora-rce-flaw-to-...](https://www.bleepingcomputer.com/news/security/hackers-exploit-collabora-rce-flaw-to-backdoor-nextcloud-servers) by [BleepingComputer](https://x.com/BleepinComputer/status/2110829398605607206).
- [Hackers hijack D-Link, Ubiquiti devices to resell your stolen bandwidth https://www.bleepingcomputer.com/news/security/hackers-hijack-d-link-ubiquiti-...](https://www.bleepingcomputer.com/news/security/hackers-hijack-d-link-ubiquiti-devices-to-resell-your-stolen-bandwidth) by [BleepingComputer](https://x.com/BleepinComputer/status/2110798191037677631).
- [Fake Arch Linux packages push malware with root privileges https://www.bleepingcomputer.com/news/security/fake-arch-linux-packages-push-malware-with-r...](https://www.bleepingcomputer.com/news/security/fake-arch-linux-packages-push-malware-with-root-privileges) by [BleepingComputer](https://x.com/BleepinComputer/status/2110780972530565459).
- [Critical BlockStrap flaw lets hackers run code on Magento servers https://www.bleepingcomputer.com/news/security/critical-blockstrap-flaw-lets-hackers...](https://www.bleepingcomputer.com/news/security/critical-blockstrap-flaw-lets-hackers-run-code-on-magento-servers) by [Nicolas Krassas](https://x.com/Dinosn/status/2111281025640759462).
- [Threat notice Cisco NX-OS Nexus 3000 and 9000 Switches https://sec.cloudapps.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-napi-rce...](https://sec.cloudapps.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-napi-rce-r2shwu2j) by [Nicolas Krassas](https://x.com/Dinosn/status/2111162425152094412).
- [Deep-Dive into Android Binder UaF (CVE-2023-20938) using Time-Travel Debugging https://www.eshard.com/blog/kernel-uaf-1-trigger](https://www.eshard.com/blog/kernel-uaf-1-trigger) by [Nicolas Krassas](https://x.com/Dinosn/status/2111160181807874398).
- [Gigabyte kernel driver LPE https://github.com/mein-0/KnockGiga](https://github.com/mein-0/KnockGiga) by [Nicolas Krassas](https://x.com/Dinosn/status/2111154885492445511).
- [UAT-11985 Uses Fake Event Invites to Target Taiwan Research Affiliates With Google AitM Phishing https://thehackernews.com/2026/10/uat-11985-uses-fake...](https://thehackernews.com/2026/10/uat-11985-uses-fake-event-invites-to.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2111147768123400346).
- [Rapid7 Analysis: GitLab CI/CD Regex Integer Overflow (CVE-2026-97229) https://www.rapid7.com/blog/post/ra-gitlab-ci-cd-regex-integer-overflow-technica...](https://www.rapid7.com/blog/post/ra-gitlab-ci-cd-regex-integer-overflow-technical-analysis-cve-2026-97229) by [Nicolas Krassas](https://x.com/Dinosn/status/2111109781973090438).
- [Eiliko robot companion exposes private chats and can be hijacked https://www.malwarebytes.com/blog/ai/2026/10/eiliko-robot-companion-exposes-private-c...](https://www.malwarebytes.com/blog/ai/2026/10/eiliko-robot-companion-exposes-private-chats-and-can-be-hijacked) by [Nicolas Krassas](https://x.com/Dinosn/status/2111109118790402077).
- [Israeli firm used online ads to run vast spy operation, researchers say https://www.reuters.com/legal/litigation/israeli-firm-used-online-ads-run-vast...](https://www.reuters.com/legal/litigation/israeli-firm-used-online-ads-run-vast-spy-operation-researchers-say-2026-10-15) by [Nicolas Krassas](https://x.com/Dinosn/status/2111097670693793793).
- [U.S. CISA adds Atlassian flaw to its Known Exploited Vulnerabilities catalog https://securityaffairs.com/201086/hacking/u-s-cisa-adds-atlassian-flaw-t...](https://securityaffairs.com/201086/hacking/u-s-cisa-adds-atlassian-flaw-to-its-known-exploited-vulnerabilities-catalog.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2111075919813046460).
- [RT Enno Rey: Wow! Owning a security appliance by sending an e-mail. In the year 2026 https://sec.cloudapps.cisco.com/security/center/content/CiscoSecu...](https://sec.cloudapps.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-esa-afw-zqYJkjxp) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2110791622359212222).
- [One of the pioneering AI bug finding startups has been acquired.](https://cohere.com/blog/cohere-and-aisle-sign-letter-of-intent-to-advance-cyber-resilient-sovereign-ai) by [Haifei Li](https://x.com/HaifeiLi/status/2110778792100913201).
- [RT Nick Carr: Guess who's back? (back again) • re-emerged [APT]29 September 2026, even larger scale • service providers...](https://www.microsoft.com/en-us/security/blog/2026/07/31/captivecrunch-midnight-blizzard-targets-travelers-worldwide-for-malware-delivery-and-credential-theft) by [Nick Carr](https://x.com/ItsReallyNick/status/2111219504470519896).
- [RT Volexity: .@Volexity has published the third and final installment of its Mind the (Patch) Gap series. Parts 1 and 2 detailed Volexity’s discovery...](https://www.volexity.com/blog/2026/10/16/mind-the-patch-gap-part-3-analysis-with-volexity-volcano-threat-intel-and-mcp) by [L0Psec](https://x.com/L0Psec/status/2111165192377606513).
- [artex-global 1,541 stars Imagine an AI red team that never sleeps. LLM multi-agents autonomously pentest your infrastructure - powered by a Go ...](https://github.com/jiwoochris/artex-global) by [Marco Ramilli](https://x.com/Marco_Ramilli/status/2110826337212526679).
- [RT zoverin: Exploit for CVE-2026-83834: https://github.com/wkpwn/CVE-2026-83834/ (my first windows exploit!!!!)](https://github.com/wkpwn/CVE-2026-83834) by [Peter Gabaldon](https://x.com/PedroGabaldon/status/2110835545429496100).
- [RT Fabian Bader: The current MSSP incident reported by Huntress is a good reminder why you should enable app instance property lock for your applicati...](https://learn.microsoft.com/en-us/entra/identity-platform/howto-configure-app-instance-property-locks) by [SwiftOnSecurity](https://x.com/SwiftOnSecurity/status/2111476391673770138).
- [RT Rich Warren: Re But it doesn't just affect Intune + NSIS - any MDM solution that allows users to self-install apps, and other installer packaging f...](https://blog.amberwolf.com/blog/2026/october/company-portal-self-service-to-system) by [X-C3LL](https://x.com/TheXC3LL/status/2110841245824118897).
- [PhantomBuffer: Effective EDR Evasion Through Stealth Injection https://www.zerosalarium.com/2026/10/PhantomBuffer-Effective-EDR-Evasion-Stealth-Inject...](https://www.zerosalarium.com/2026/10/PhantomBuffer-Effective-EDR-Evasion-Stealth-Injection.html) by [/r/netsec](https://x.com/_r_netsec/status/2111646788088471813).
- [New web obfuscation technique where even just formatting rewrites script logic (Chromium DevTools, prettier, WebCrack, Terser and more) https://trusts...](https://trustsig.eu/blog/javascript-divergence) by [/r/netsec](https://x.com/_r_netsec/status/2111239102012207197).
- [16% of RPKI-covered IPv4 routes still allow a forged-origin hijack that passes validation, the setup behind the Virtualizor update attack https://ipin...](https://ipinfo.io/blog/rpki-protects-70-internet-routes) by [/r/netsec](https://x.com/_r_netsec/status/2111110756368515571).
- [CVE-2026-108082: Symfony ReDoS. One request. Seconds of CPU https://r3verii.github.io/cve/2026/10/16/symfony-cache-control-redos.html](https://r3verii.github.io/cve/2026/10/16/symfony-cache-control-redos.html) by [/r/netsec](https://x.com/_r_netsec/status/2111103206487138457).
- [The Cloudflare Appstore (Appflare) Malware Audit https://mainbrella.com/blog/the-cloudflare-appstore-appflare-malware-audit/](https://mainbrella.com/blog/the-cloudflare-appstore-appflare-malware-audit) by [/r/netsec](https://x.com/_r_netsec/status/2111088106296488439).
- [RT Almamater Technologies: Another M6 gem: return addresses that remember where they came from (PAuth_LR). On M6, Apple's x1 slice signs each return a...](https://almamatertech.com/notes/return-addresses-on-apple-silicon) by [winterknife](https://x.com/_winterknife_/status/2111150311809171846).
- [AI nerds have been out there smoking making themselves look cool… Now they have to run away from the baddies?](https://www.wsj.com/tech/ai/ai-companies-play-cat-and-mouse-with-secret-stealing-spies-160eec6b) by [Adam Chester](https://x.com/_xpn_/status/2111140186004599149).
- [A patch bypass I reported nearly two years ago in Ivanti Connect Secure got patched in 25.1.3.0 .. by just removing the feature completely. Obviously ...](https://blog.amberwolf.com/blog/2026/october/ivanti-custom-signin-page-rce) by [Rich Warren](https://x.com/buffaloverflow/status/2111114886227120524).
- [Andrii and the SOC Prime team have just launched LogTotal and I find the concept quite interesting You can upload a collection of security logs, run d...](https://github.com/socprime/logtotal-sanitizer) by [Florian Roth](https://x.com/cyb3rops/status/2111519772999331942).
- [RT Joseph Cox: Here's how exactly Telegram provides user data to U.S. authorities. A letter recently filed in court shows how Telegram transfers that ...](https://www.404media.co/heres-what-telegram-giving-data-to-the-u-s-government-looks-like) by [Florian Roth](https://x.com/cyb3rops/status/2111132704464863322).
- [RT Joseph Cox: OpenAI continues to enshittify ChatGPT: OpenAI allows advertisers - or really anyone, I tested myself in 5 minutes - upload raw phone num...](https://www.404media.co/how-chatgpt-targets-ads-to-you-based-on-your-prompts-phone-number-and-email) by [Florian Roth](https://x.com/cyb3rops/status/2111010602160467996).
- [RT JPCERTコーディネーションセンター: ブログ JPCERT/CC Eyes「連続不正アクセス事案の攻撃手法に関する調査」公開。調査の過程で攻撃者がAIを利用して既知の脆...](https://blogs.jpcert.or.jp/ja/2026/10/web_api_attacks.html) by [Florian Roth](https://x.com/cyb3rops/status/2111227719824343045).
- [RT Tal Be'ery: Burning a possible @BlackHatEvents submission just to make a point: I modified WhatsApp to permanently rewrite its own chat history by ...](https://x.com/cyb3rops/status/2110821009754361948) by Florian Roth.
- [RT Cyber_OSINT: Google's GTIG and Mandiant reported UNC7017 conducted ephemeral, five-to-ten minute software update tampering against AOMEI, deliverin...](https://cloud.google.com/blog/topics/threat-intelligence/investigating-ephemeral-supply-chain-tampering) by [Dominic Chell](https://x.com/domchell/status/2111581359537852882).
- [RT Low Level: holy shit this is so bad lol. wormable RCE over the air](https://x.com/esizkur/status/2111716479049802164) by rpw.
- [RT James: we found a detail in the @opencode attack that nobody is posting. the fix already existed. a PR in august added turnstile to the legacy cons...](https://x.com/evilsocket/status/2111744265680220500) by Simone Margaritelli.
- [RT Lukasz Olejnik: China is to add 40 technologies to its export blacklist. 23 of them in AI. AI malware that beats antivirus 85% of the time is autom...](https://x.com/halvarflake/status/2111154961447031074) by Halvar Flake.
- [RT Florian Hansemann: ''Reversing embedded WebAssembly: part 1. Cracking the WAMR .aot container in pure C.'' #infosec #pentest #redteam #blueteam htt...](https://cocomelonc.github.io/reverse/2026/09/30/wasm-aot-reversing-1.html) by [hasherezade](https://x.com/hasherezade/status/2111501363377066427).
- [TornadoC2 - Pull-based C2 framework with ten native transports, concurrent multi-profile handlers, and end-to-end ECDSA-signed tasking. Multi-operator...](https://github.com/kamalx06/TornadoC2) by [Panos Gkatziroulis](https://x.com/ipurple/status/2111212812458750369).
- [A red team tool that packages a Windows PE payload into a .wsl file spoofing a real Linux distro installer https://github.com/shaheeryasirofficial/cub...](https://github.com/shaheeryasirofficial/cuban-eight) by [Panos Gkatziroulis](https://x.com/ipurple/status/2111198690320793728).
- [DLL Sideloading for Initial Access and Bypassing Elastic EDR https://akchhat.gitbook.io/dev/initial-access/dll-sideloading-for-initial-access-and-bypa...](https://akchhat.gitbook.io/dev/initial-access/dll-sideloading-for-initial-access-and-bypassing-elastic-edr) by [Panos Gkatziroulis](https://x.com/ipurple/status/2111179488105021566).
- [HostBadger - Read-only Windows host hardening auditor in PowerShell with optional AI analysis https://github.com/g4bri-3l3/HostBadger](https://github.com/g4bri-3l3/HostBadger) by [Panos Gkatziroulis](https://x.com/ipurple/status/2111171831734652955).
- [After You’re In: Field Notes on CRTO Prep and OPSEC https://gikaku.net/2026/10/17/crto-opsec/](https://gikaku.net/2026/10/17/crto-opsec) by [Panos Gkatziroulis](https://x.com/ipurple/status/2111140459120922791).
- [RT spencer: Kudos to Jerry and the team! The enhanced NTLM auditing events introduced last year for Server 2025 and 24H2 have just been backporte...](https://x.com/jeffmcjunkin/status/2111532848113229837) by Jeff McJunkin.
- [RT SpecterOps: PSA for Microsoft 365 admins: Huntress has reported a widespread security incident involving ConnectWise Cloud Backup (formerly SkyKick...](https://x.com/jessefmoore/status/2111593734056124445) by Chihuahua in charge NotMe.
- [Linux malware from scratch: understand the OS, write better malware. Lesson 0 of my "Linux C2 from Scratch" series: https://jm33.me/linux-c2-from-scra...](https://jm33.me/linux-c2-from-scratch-0x00-processes-syscalls-libc-and-tls.html) by [jm33_ng](https://x.com/jm33_m0/status/2111260603084136660).
- [RT starlabs: What a rollercoaster. 7 weeks, 5 RCEs on Pixel 10 & 11, all officially patched by Google today. Chuffed to bits. The bounty won’t have u...](https://x.com/kiddo_pwn/status/2111538556615225512) by kiddo.
- [RT Quentin Kaiser: just confirmed the presence of Broadcom's vulnerable wps_monitor in ZTE F680 v4 deployed by MasMovil, ThailandToT, Telkom, Linkstar...](https://github.com/qkaiser/broadcom-wps/pull/1) by [kmkz](https://x.com/kmkz_security/status/2111534079141146775).
- [RT Angelos T. Kalaitzidis: Hell yeah Cellebrite is dropping SecureROM 0days on stage (variant of usbliter8) !!](https://x.com/kmkz_security/status/2111396040238662017) by kmkz.
- [RT Robert Chen: Another fun bug, we turned a Linux kernel timer UAF into a kernel read/write on Android, root + SELinux permissive. Great work @ryaaga...](https://x.com/kmkz_security/status/2111170340441223303) by kmkz.
- [Not sure what exactly to think about this, but one thing is sure: a supposedly Chinese APT's FUD backdoor generated ~26k certs faking as LAPD is nothi...](https://platform.censys.io/search?q=%28cert.parsed.subject.country%3A+%22US%22+and+cert.parsed.subject.province%3A+%22California%22+and+cert.parsed.subject.locality%3A+%22LA%22+and+cert.parsed.subject.organization%3A+%22LAPD%22+and+cert.parsed.subject.organizational_unit%3A+%22Police+department%22+and+cert.parsed.subject.common_name%3A+%22ROOT%22+%29) by [MalwareHunterTeam](https://x.com/malwrhunterteam/status/2111210393406509255).
- [Top 5 most shared links in my network (Oct 17): 1. https://www.huntress.com/blog/vendor-credential-enables-unauthorized-access (14 people) 2. https://...](https://www.bleepingcomputer.com/news/security/hackers-breach-microsoft-365-tenants-via-connectwise-supply-chain-attack) by [Ring3API 🇺🇦](https://x.com/ntlmrelay/status/2111775320936165389).
- [Agent skills for Ghostwriter - @SpecterOps @cmaddalena https://github.com/GhostManager/ghostwriter-skills/](https://github.com/GhostManager/ghostwriter-skills) by [Swissky](https://x.com/pentest_swissky/status/2111933841086591130).
- [RT Ian Carroll: If Discord is only paying $5k for an RCE in their desktop client, it's probably time to uninstall it](https://bugcrowd.com/disclosures/63864b55-10d6-4e82-a619-192b8c0c99ad/1-click-remote-code-execution-via-twitch-embed) by [Sam Curry](https://x.com/samwcyo/status/2111565196619870389).
- [RT Hash Suite: Hash Suite 4.1 (Windows): ~2.5x speedup on CPUs with AVX-512, SHA-NI. Support for MS Office encrypted files, Pcapng and Capng capture f...](https://hashsuite.openwall.net/download) by [Solar Designer](https://x.com/solardiz/status/2111619935688352216).
- [Closing the week strong, with a chain: 1⃣ App TCC bypass -> allows modifying NIB files 2⃣ DirtyNib reborn without user interaction -> ...](https://x.com/theevilbit/status/2111343754774974668) by Csaba Fitzl.
- [RT Harley Kimball: In an impressive GitHub write-up, @v_metnew documents a sandbox escape in Anthropic's Claude Code CLI (CVE-2026-55607). By using a ...](https://github.com/Metnew/write-ups/tree/main/claude-code-worktree-sandbox-escape) by [vladimir metnew](https://x.com/v_metnew/status/2111432449305493783).
- [> be JayTaelien > security researcher > discovered Discord zero day exploit > send Twitch embed to victim > something something > massive exploit chai...](https://x.com/vxunderground/status/2111926875626893547) by vx-underground.
- [CVE-2026-108097 Deep Dive: Turning a Drupal Field UI Callback Into RCE https:// fortbridge.co.uk/research/cve- 2026-108097-deep-dive-turning-a-drupal-field-ui-callback-into-rce/](https://fortbridge.co.uk/research/cve-2026-108097-deep-dive-turning-a-drupal-field-ui-callback-into-rce).
- [abuse list for ips · NicheDB https:// nichedb.dev/traffic/review](https://nichedb.dev/traffic/review).
- [RT JS0N Haddix: The best practitioner (not lab) AI evals for offensive cybersecurity I follow myself: 1) The @dreadnode dreadindex. Evals al the way d...](https://www.mindfort.ai/blog/introducing-nexbench) by [Max Harley](https://x.com/0xdab0/status/2111539463293636983).

</details>


## Tools and Exploits

- [Fox-IT Releases Cobalt Strike Beacon Corpus](https://blog.fox-it.com/2026/10/13/releasing-the-cobalt-strike-beacon-corpus) by [Florian Roth](https://x.com/cyb3rops/status/2110756582678040579).
> Fox-IT published a large corpus of real-world Cobalt Strike Beacon samples for detection research and signature development.

- [Labyrinth: Malware-as-a-Service Cyber Range for Ludus](https://github.com/Whispergate/Labyrinth) by [Ring3API 🇺🇦](https://x.com/ntlmrelay/status/2109924764001194389).
> Automated offensive development pipeline with CI/CD-driven payload compilation, obfuscation, and EDR evasion testing on the Ludus platform.

- [Hashcat Hash Recipes (Mode 4000)](https://github.com/hashcat/hashcat/blob/master/docs/hashcat-hash-recipe.md) by [Swissky](https://x.com/pentest_swissky/status/2110041634544968118).
> New hashcat feature lets you compose arbitrary hash algorithms as recipes, e.g. md4(utf16le(pass)) or hex(xor(md5_bin(pass), md5_bin(salt))).

- [Exploit Watch Archive](https://github.com/dinosn/exploit-watch-archive) by [Nicolas Krassas](https://x.com/Dinosn/status/2110589345421779115).
> Automated weekly aggregation of 0-day and N-day exploit releases across public sources. Community contributions welcome.

- [Red Team BOFs Collection](https://github.com/chryzsh/redteam-bofs) by [Panos Gkatziroulis](https://x.com/ipurple/status/2110368577752531184).
> Curated collection of Beacon Object Files for post-exploitation: credential hunting, system enumeration, event log analysis, and privilege management.

- [lindm: Open-Source MDM for Linux Fleets](https://github.com/radkawar/lindm) by [Rad](https://x.com/rad9800/status/2110752604032843781).
> Self-hosted, open-source device management for Linux. Your server, your devices. First release (v0.1.0).

- [r2xsql: SQL Interface for Radare2 Databases](https://github.com/radareorg/r2xsql) by [thaddeus e. grugq](https://x.com/thegrugq/status/2110982329883836645).
> Query radare2 databases with SQL, compatible with the xSQL family (IDASQL, GhidraSQL, Binary Ninja SQL). Makes r2 databases AI-agent-friendly.

- [Apex C2 v0.4: Native Agentic AI Operator Interface](https://phantomsec.tools/blog/apex-c2-v04-release) by [Nicolas Krassas](https://x.com/Dinosn/status/2111097282116436119).
> C2 framework with a built-in MCP interface. Connect Claude Code, Cursor, or Codex to the teamserver to enumerate targets, author modules, and adapt in real time.

- [IDWolf: AD and Entra ID Hygiene Auditor](https://github.com/g4bri-3l3/IDWolf) by [Panos Gkatziroulis](https://x.com/ipurple/status/2111137862439879104).
> Read-only PowerShell auditor for Active Directory and Entra ID. Collect once, analyze offline with deterministic findings, attack path mapping, and compliance reports.

- [Stealth Browser MCP: Automate Cloudflare-Protected Sites](https://github.com/vibheksoni/stealth-browser-mcp) by [thaddeus e. grugq](https://x.com/thegrugq/status/2111796223107801283).
> MCP server that drives real Chrome instances to bypass Cloudflare challenges and bot checks for automated security testing workflows.


<details markdown="1">
<summary>More this week (11)</summary>

- [GitHub’s model for secret detection: Finding more secrets with less noise](https://github.blog/ai-and-ml/githubs-model-for-secret-detection-finding-more-secrets-with-less-noise) by Batu Ozturkler.
- [RT SEKTOR7 Institute: Launching payloads via a service recovery. RecoverIt crashes a broken Windows service so its recovery action launches a given pa...](https://hackers-arise.com/defense-evasion-recoverit-using-windows-service-failure-recovery-to-evade-detection) by [Steven Lowson](https://x.com/StevoLowson/status/2109712671696163041).
- [[1/3] Agents can hack. What's holding them back is trust: will they stay in scope? Today we're releasing ScopeBench, a methodology and community ...](https://x.com/dreadnode/status/2107518418664800454) by dreadnode.
- [Just released PoCs for the 6 LibreOffice bugs we found (@b0n0b0__ ). Including an .odb/.odt/.jar triple-polyglot for the RCE and my personal favorite,...](https://x.com/thomasrinsma/status/2108307050379772251) by Thomas Rinsma.
- [#Rikugan vs #Frontkick: who wins the agentic AI showdown? Rikugan is open-source and making waves on IDA. Frontkick is built for Binary Ninja. To...](https://www.synacktiv.com/en/publications/ufc-666-frontkick-vs-rikugan) by [Synacktiv](https://x.com/Synacktiv/status/2110296456582095172).
- [RT Bernardo Quintero: VirusTotal is now available in ChatGPT Scan files, URLs, and domains for potential threats, right from your chat https://chatgpt...](https://chatgpt.com/plugins/plugin_asdk_app_6abadac2d9a08191ae2307c047bb3806) by [hasherezade](https://x.com/hasherezade/status/2110726783670645183).
- [RT Alfie: Finally got around to releasing Trigon for arm64e. Enjoy! https://alfiecg.uk/2026/10/17/Trigon.html](https://alfiecg.uk/2026/10/17/Trigon.html) by [Alex Plaskett](https://x.com/alexjplaskett/status/2111581411081674784).
- [RT Karsten Hahn: New release of PortexAnalyzer GUI v1.0.0 is public X-ray your PE files Release download: https://github.com/struppigel/PortexAnalyzer...](https://github.com/struppigel/PortexAnalyzerGUI/releases) by [hasherezade](https://x.com/hasherezade/status/2111808856825184497).
- [RT OrcaRouter : Emergency release: OrcaCyber Nano 1.0 is now open-weight. Part of our OrcaCyber model series: Nano, Zero, Ultra. Based on our...](https://huggingface.co/orcarouter/OrcaCyber-Nano-1.0) by [Swissky](https://x.com/pentest_swissky/status/2111890885734769018).
- [RT johnny: Open-sourced CryptSn0w, our now obsolete untethered iOS ≤27/≤A20 Pro jailbreak via rare Apple server-side TSS/Cryptex bug. PATCHED, educa...](https://github.com/0xjohnnydev/cryptsn0w?v=2) by [Csaba Fitzl](https://x.com/theevilbit/status/2111340702449741909).
- [RT 丂卄ㄖᗪ卂几 - crack fingers: Two years ago I released the USB Army Knife, this combined WiFi, BTLE & USB attacks into a single dongle with a ...](https://x.com/thegrugq/status/2111454463651360793) by thaddeus e. grugq.

</details>



