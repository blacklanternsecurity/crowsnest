---
title: "Crow's Nest - 2026-06-08"
date: 2026-06-08T00:00:00+00:00
draft: false
tags: ["roundup"]
---

A roundup of 44 items curated from across the security community.

## News

- [UN food agency breach exposes 600,000 Gaza households](https://www.bleepingcomputer.com/news/security/un-world-food-programme-breach-affect) by [Nicolas Krassas](https://x.com/Dinosn/status/2062587913443942528).
> The UN World Food Programme discloses a data breach affecting 600,000 households in Gaza.

- [UNC3753 targets US law firms with vishing and physical intrusion](https://goo.gle/49HfT8g) by [scriptjunkie (Matt)](https://x.com/scriptjunkie1/status/2062955335858446570).
> Mandiant details UNC3753 using vishing and RMM tools for data extortion against US law firms, with some operators attempting in-person theft.

- [CISA: SolarWinds Serv-U flaw now actively exploited](https://www.bleepingcomputer.com/news/security/cisa-hackers-now-exploit-solarwinds-s) by [BleepingComputer](https://x.com/BleepinComputer/status/2062976683993383341).
> CISA adds an actively exploited SolarWinds Serv-U vulnerability to the KEV catalog.


<details markdown="1">
<summary>More this week (5)</summary>

- [Cisco Unified CM critical flaw with PoC exploit code](https://www.bleepingcomputer.com/news/security/cisco-warns-of-critical-unified-cm-flaw-w) by [BleepingComputer](https://x.com/BleepinComputer/status/2062492073714954549).
- [IronWorm malware hits 36 npm packages](https://www.bleepingcomputer.com/news/security/new-ironworm-malware-hits-36-packages-) by [Nicolas Krassas](https://x.com/Dinosn/status/2062571722113450272).
- [Amazon mouse is a confirmed BadUSB credential harvester](https://www.amazon.com/dp/B0FX256X3W?amp%3Bamp%3Bth=1).
- [Miasma worm hits 73 Microsoft GitHub repositories](https://thehackernews.com/2026/06/miasma-worm-hits-73-microsoft-github) by [Nicolas Krassas](https://x.com/Dinosn/status/2063175990017196229).
- [Whistleblower accuses IBM of covering up data breaches](https://techcrunch.com/2026/06/05/former-c) by [K̵i̵r̵k̵ ̵T̵r̵y̵c̵h̵e̵l̵](https://x.com/Teach2Breach/status/2063469717684175255).

</details>


## Techniques and Write-ups

- [AI-powered self-replicating worm steals GPU compute to spread](https://arxiv.org/pdf/2606.03811) by [thaddeus e. grugq](https://x.com/thegrugq/status/2062437513898442980).
> A research paper demonstrates an AI worm that reasons its way through networks, steals compute from GPU machines to run its own LLM, and self-replicates across Linux, Windows, and IoT targets.

- [CVE-2026-10880: Unauthenticated Blind SQLi in OSNEXUS QuantaStor](https://blog.blacklanternsecurity.com/p/cve-2026-10880-osnexus-quantastor).
> OSNEXUS QuantaStor through v6.6.1 has an unauthenticated blind SQL injection in the login form. Attackers can recover stored password hashes one character at a time using differing login error responses, with no credentials required.

- [VerdantBamboo deploys BRICKSTORM through compromised MSPs and firewalls](https://www.volexity.com/blog/2026/06/04/verdantbamboo-just-another-brickstorm-in-the-firewall) by [L0Psec](https://x.com/L0Psec/status/2062651716336546304).
> Volexity details how VerdantBamboo breached an MSP to deploy BRICKSTORM across firewalls, NAS, and cloud storage devices, including a zero-day privilege escalation.

- [New technique to detect Chrome incognito mode via Cache API](https://navigator.storage.estimate/) by [AndrewMohawk⁽ⁿᵘˡˡ⁾](https://x.com/AndrewMohawk/status/2063279372690182390).
> Writing tiny responses into a scratch Cache API cache reveals different metadata residue in normal vs. incognito Chrome, because incognito writes to memory instead of disk.

- [Two bytes to RCE: chaining nginx Rift and PoolSlip](https://blog.verichains.io/p/two-bytes-to-rce-chaining-rift-poolslip?r=8jsy48&amp%3Butm_campaign=post&amp%3Butm_medium=web) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2063310556816146699).
> Verichains chains the nginx Rift and PoolSlip vulnerabilities together into a full remote code execution exploit.

- [Unauth RCE as QSECOFR on IBM i via Management Central](https://blog.silentsignal.eu/2026/06/05/unauthenticated-rce-as-qsecofr-via-ibm-i-management-central) by [/r/netsec](https://x.com/_r_netsec/status/2062862771247878287).
> Silent Signal finds an unauthenticated RCE as the system superuser on IBM i Management Central, exploiting a client-controlled verify flag on port 5555.


<details markdown="1">
<summary>More this week (20)</summary>

- [Re:CACHE: 0-click stored XSS on Next.js via type confusion](https://zhero-web-sec.github.io/research-and-things/re-cache-excessive-reflection-type-confusion-and-0-click-sxss-on-nextjs).
- [Remote kernel DoS in Comodo Internet Security](https://malwaretech.com/2026/06/exploiting-a-remote-kernel-vulnerability-in-comodo-internet-security.html) by [vx-underground](https://x.com/vxunderground/status/2062369103847772387).
- [CVE-2025-59199: Windows sandbox escape via Notifications and URIs](https://www.safebreach.com/blog/click-or-trick-cve-2025-59199-escaping-the-sandbox-with-windows-uris) by [winterknife](https://x.com/_winterknife_/status/2061700401385140431).
- [From prompt to pwned: chaining LLM and web bugs to admin](https://blog.quarkslab.com/from-prompt-to-pwned-chaining-llm-and-web-bugs-to-admin.html) by [Dave Aitel](https://x.com/daveaitel/status/2062924798741659669).
- [An exercise in dynamic analysis of unknown Windows mitigations](https://windows-internals.com/an-exercise-in-dynamic-analysis) by [Dave Aitel](https://x.com/daveaitel/status/2062319830779244824).
- [Card skimmer uses Stripe's own API as its C2 and exfil](https://sansec.io/research/stripe-api-skimmer-infrastructure) by [Robin](https://x.com/digininja/status/2062892678371545431).
- [Escaping the PHP sandbox via a UAF on macOS](https://therealcoiffeur.com/c111001.html) by [kmkz](https://x.com/kmkz_security/status/2062600247168147617).
- [Redis CVE-2026-23479 deep dive](https://www.zeroday.cloud/blog/redis-cve-2026-23479-deep-dive) by [kmkz](https://x.com/kmkz_security/status/2062630165499302047).
- [Async picos and custom beacon wakeups in Cobalt Strike](https://www.nccgroup.com/research/async-picos-and-custom-beacon-wakeups-in-cobalt-strike) by [Lefteris Panos](https://x.com/lefterispan/status/2062573065515532521).
- [Evilginx Phishlets 2.0 preview: downgrading FIDO MFA on M365](https://x.com/mrgretzky/status/2062584070593184253) by Kuba Gretzky.
- [BOF cocktails in Cobalt Strike 4.13](https://rastamouse.me/bof-cocktails-) by [Bobby Cooke](https://x.com/0xBoku/status/2062913046226599990).
- [Microsoft finds Claude Code GitHub Action vulnerable to prompt injection](https://www.microsoft.com/en-us/security/blog/2026/06/05/securing-ci-cd-in-agentic-world-claude-code-github-action-case) by [Nicolas Krassas](https://x.com/Dinosn/status/2063176836478103826).
- [Insights into Entra ID's (Un)Conditional Access](https://insinuator.net/2026/05/insights-into-entra-ids-unconditio) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2062808961057685944).
- [Inside MXC: Microsoft's experimental OS-level sandbox for AI agents](https://www.originhq.com/research/mxc-execution-containers-internals) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2062794878996677090).
- [FreeType heap overflow via TrueType SHZ instruction](https://project-zero.issues.chromium.org/issues/505355061) by [Project Zero Bugs](https://x.com/ProjectZeroBugs/status/2062793582428536957).
- [Zero-click HFP/A2DP Bluetooth takeover via L2CAP preemption](https://paste.rs/UkBmF.md) by [/r/netsec](https://x.com/_r_netsec/status/2062926943927128109).
- [Seven years of secrets on a public clipboard, plus stored XSS](https://beyondmemory.io/blog/json-formatter-data-exposure) by [/r/netsec](https://x.com/_r_netsec/status/2062881644697321635).
- [CVE-2026-46640: Twig sandbox bypass payload development](https://gist.github.com/vladko312/39507beaa58eacf3b62e6a6e6cd69128).
- [Chrome sandbox escape UAF earns $90K bounty](https://crbug.com/487338366) by [Alex Plaskett](https://x.com/alexjplaskett/status/2063370777072721972).
- [Pwning V8CTF via a Chrome 0-day in Phi untagging](https://kqx.io/post/cve-2026-4447) by [Alex Plaskett](https://x.com/alexjplaskett/status/2063509737073737951).

</details>


## Tools and Exploits

- [WASMForge: running full Sliver implants entirely in a WASM VM](https://www.praetorian.com/blog/wasmforge-sliver-webassembly) by [Bad Sector Labs](https://x.com/badsectorlabs/status/2062551498324672611).
> Praetorian shims all necessary host APIs to run complete implants with all logic inside a WebAssembly VM, demonstrated with Sliver.

- [EDRChoker: choking the telemetry stream to bypass defenses](https://www.zerosalarium.com/2026/06/edrchoker-choking-telemetry-stream-block-edr.html) by [/r/netsec](https://x.com/_r_netsec/status/2063564897468993923).
> A technique for starving EDR of telemetry by throttling the stream, effectively blinding defenses without killing the agent.


<details markdown="1">
<summary>More this week (8)</summary>

- [VeeamDumper: extracting credentials from Veeam backup databases](https://mwrcybersec.com/gimme-gimme-gimme-your-creds-after-midnight) by [Sean Metcalf](https://x.com/PyroTek3/status/2062669898518614018).
- [AzureRedOps: Entra ID red team tool with Playwright token capture](https://github.com/Mr-Un1k0d3r/AzureRedOps) by [Chihuahua in charge NotMe](https://x.com/jessefmoore/status/2062527118022688973).
- [Anthropic open-sources a reference harness for AI vuln discovery](https://github.com/anthropics/defending-code-reference-harness) by [kmkz](https://x.com/kmkz_security/status/2062503511288418498).
- [Ghostwriter v7: scoped service tokens for LLM integration](https://ghst.ly/4o04tm3) by [Swissky](https://x.com/pentest_swissky/status/2062607102569300438).
- [PE-bear 0.7.2: new features and bugfixes](https://github.com/hasherezade/pe-bear/releases).
- [CVE-2026-8389 exploit released](https://github.com/crixpwn/CVE-2026-8389) by [Bobby Cooke](https://x.com/0xBoku/status/2062723271569850499).
- [Havoc Professional 0.7 K-Noir: Linux implant and stack spoofing](https://x.com/_RastaMouse/status/2062942846005411859) by Rasta Mouse.
- [Ghidra RPC: an agent skill for agentic reverse engineering](https://github.com/cellebrite-labs/ghidra-rpc) by [winterknife](https://x.com/_winterknife_/status/2062911898966798562).

</details>



