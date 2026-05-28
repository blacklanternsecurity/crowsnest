---
title: "Crow's Nest - 2026-05-28"
date: 2026-05-28T00:00:00+00:00
draft: false
tags: ["roundup"]
---

A roundup of 82 items curated from across the security community.

## News

- [Active exploitation of a Cisco Catalyst SD-WAN auth bypass (CVE-2026-20182)](https://blog.talosintelligence.com/sd-wan-ongoing-exploitation) by Cisco Talos.
> Talos is tracking in-the-wild exploitation of CVE-2026-20182, an authentication bypass in Cisco Catalyst SD-WAN Manager and Controller.

- [Pwn2Own Berlin 2026: DEVCORE takes Master of Pwn](https://www.thezdi.com/blog/2026/5/16/pwn2own-berlin-2026-day-three-results-and-master-of-pwn) by Dustin Childs.
> DEVCORE took Master of Pwn at Pwn2Own Berlin 2026, capping an event that paid $1,298,250 for 47 zero-days. Orange Tsai chained three bugs to RCE as SYSTEM on Exchange for $200,000.

- [ShinyHunters leaks 9.4GB of 7-Eleven franchisee data](https://www.technadu.com/7-eleven-data-breach-exposes-over-185000-accounts-in-shinyhunters-extortion-campaign/628347).
> ShinyHunters dumped a 9.4GB database from 7-Eleven franchisee systems after the company refused to pay, exposing over 185,000 accounts.

- [CISA contractor leaked GovCloud keys and passwords on GitHub](https://krebsonsecurity.com/2026/05/cisa-admin-leaked-aws-govcloud-keys-on-github).
> A CISA contractor published GovCloud access keys, plaintext passwords, and SSH keys to a public GitHub repo. Senator Hassan is now pressing CISA and DHS for answers. Also: [lawmakers demand answers](https://krebsonsecurity.com/2026/05/lawmakers-demand-answers-as-cisa-tries-to-contain-data-leak).

- [Iranian-aligned group used Stryker's own Intune to wipe 200,000 devices](https://www.magicsword.io/blog/the-guard-and-the-thief-carpool) by [The Haag™](https://x.com/M_haggis/status/2057795987574288773).
> No malware, just a legitimate admin tool: attackers issued remote wipe commands through Stryker's Microsoft Intune, clearing 200,000 devices across 79 countries. Confirmed in an SEC filing.

- [Composer supply-chain attack compromises laravel-lang packages](https://x.com/N3mes1s/status/2058056263506800796) by Giuseppe `N3mes1s`.
> Multiple laravel-lang Packagist packages were backdoored with autoload-time payloads across 50-plus versions. Pin to a known-good commit and rotate secrets. Also: [bumblebee exposure scanner](https://github.com/perplexityai/bumblebee), [npm staged publishing](https://github.blog/changelog/2026-05-22-staged-publishing-and-new-install-time-controls-for-npm).


<details markdown="1">
<summary>More this week (15)</summary>

- [GitHub Enterprise Server signing-key rotation after internal-repo breach](https://github.blog/security/investigating-unauthorized-access-to-githubs-internal-repositories) by Natalie Guevara.
- [Fast16 malware targeted nuclear-weapons simulation software](https://infosec.exchange/@kimzetter/116584486207385646).
- [Lithuania investigates breach exposing 600,000 registry records](https://www.technadu.com/lithuania-investigates-state-registry-breach-of-600000-records/628417).
- [CVE-2026-9256: new nginx rewrite-module vulnerability (nginx-poolslip)](https://my.f5.com/manage/s/article/K000161377).
- [Netherlands seizes 800 servers, arrests two for aiding Russian cyberattacks](https://krebsonsecurity.com/2026/05/netherlands-seizes-800-servers-arrests-2-for-aiding-cyberattacks).
- [Alleged Kimwolf IoT botmaster arrested in Canada](https://krebsonsecurity.com/2026/05/alleged-kimwolf-botmaster-dort-arrested-charged-in-u-s-and-canada).
- [TrapDoor crypto stealer hits npm, PyPI, and Crates.io](https://x.com/N3mes1s/status/2058609807553102217) by Giuseppe `N3mes1s`.
- [Composio discloses breach via its internal AI agent tooling](https://x.com/N3mes1s/status/2057691769517576230) by Giuseppe `N3mes1s`.
- [FBI’s 2025 Internet Crime Report](https://www.schneier.com/blog/archives/2026/05/fbis-2025-internet-crime-report.html) by Bruce Schneier.
- [Sanctioned and seized, the Dutch-busted hosting network keeps scanning](https://ellio.tech/en/blog/sanctioned-seized-still-scanning-inside-a-russian-bulletproof-hosting-network-targeting-the-eu).
- [Inside CrowdStrike's takedown of a developer-targeting botnet](https://www.crowdstrike.com/en-us/blog/inside-crowdstrike-takedown-of-a-developer-targeting-botnet) by [SwitHak ()](https://x.com/SwitHak/status/2059392293409378553).
- [FBI advisory: ransomware crews abuse the First VPN service](https://ic3.gov/CSA/2026/260521.pdf) by [SwitHak ()](https://x.com/SwitHak/status/2057852923682467919).
- [Microsoft details Fox Tempest's malware-signing-as-a-service](https://msft.it/6015vTCYU) by [SwitHak ()](https://x.com/SwitHak/status/2056792854689730704).
- [INTERPOL's Operation Ramz: 201 arrests across MENA](https://www.interpol.int/en/News-and-Events/News/2026/201-arrests-in-first-of-its-kind-cybercrime-operation-in-MENA-region) by [SwitHak ()](https://x.com/SwitHak/status/2056430467839045670).
- [Microsoft responds to the Nightmare-Eclipse zero-day disclosures](https://www.microsoft.com/en-us/msrc/blog/2026/05/a-shared-responsibility-protecting-customers-through-coordinated-vulnerability-disclosure) by [K̵i̵r̵k̵ ̵T̵r̵y̵c̵h̵e̵l̵](https://x.com/Teach2Breach/status/2059762574263042558).

</details>


## Techniques and Write-ups

- [YellowKey zero-day defeats default Windows 11 BitLocker](https://www.schneier.com/blog/archives/2026/05/zero-day-exploit-against-windows-bitlocker.html) by Bruce Schneier.
> A reliable exploit bypasses BitLocker on default Windows 11 deployments. It needs physical access, but undermines the at-rest protection many orgs assume.

- [RCE in the Strix AI agent sandbox via prompt injection](https://baldur.dk/blog/strix-ai-pentester-rce.html).
> Prompt-injection chain that turns the Strix AI pentest agent's sandbox into reliable remote code execution. A concrete walk-through from injection to impact.

- [Analyzing the Taiwan High-Speed Rail TETRA incident (part 1)](https://www.midnightblue.nl/blog/analyzing-the-taiwan-high-speed-rail-thsr-tetra-cyber-incident-part-1).
> Midnight Blue dissects a cyber incident on Taiwan's high-speed rail, including the TETRA radio angle. Part one of the analysis.

- [CVE-2026-0265: Palo Alto PAN-OS GlobalProtect auth bypass](https://www.hacktron.ai/blog/cve-2026-0265-panos-globalprotect-cas-auth-bypass) by [LiveOverflow](https://x.com/LiveOverflow/status/2057142782460903875).
> An authentication bypass in PAN-OS GlobalProtect CAS auth lets an attacker connect to a target's VPN. Hacktron breaks down the bug.

- [Project Zero: a 0-click exploit chain for the Pixel 10](https://projectzero.google/2026/05/pixel-10-exploit.html) by [Project Zero Bugs](https://x.com/ProjectZeroBugs/status/2054612969166868683).
> Project Zero details "When a Door Closes, a Window Opens," a zero-click exploit chain against the Pixel 10.

- [Detecting Tycoon2FA AITM across Entra ID and Google Workspace](https://www.elastic.co/security-labs/tycoon-2fa-aitm-detection-engineering) by [Samir](https://x.com/SBousseaden/status/2059375397754581476).
> Telemetry fingerprints and ready-to-ship detection rules for Tycoon2FA adversary-in-the-middle attacks across Entra ID and Google Workspace.

- [Vaultjacking: one PIN dumps the whole Google Password Manager vault](https://phishu.net/blogs/blog-vaultjacking-phishing-the-google-password-manager-vault-in-the-phishu-framework.html).
> A phishing technique that turns a single captured PIN into the victim's entire Google Password Manager vault.

- [CVE-2026-40369: a 12-byte kernel increment to LPE and sandbox escape](https://voidsec.com/cve-2026-40369-browser-sandbox-escape) by [SinSinology](https://x.com/SinSinology/status/2057492846043598951).
> VoidSec turns a 12-byte kernel increment into both a local privilege escalation and a browser sandbox escape, with full exploitation strategy.

- [NSA security guidance for MCP-based AI automation](https://www.nsa.gov/Portals/75/documents/Cybersecurity/CSI_MCP_SECURITY.pdf?ver=bmgiSbNQLP6Z_GiWtRt6bg%3D%3D) by [K̵i̵r̵k̵ ̵T̵r̵y̵c̵h̵e̵l̵](https://x.com/Teach2Breach/status/2057564359040069944).
> The NSA publishes security design considerations for AI agent workflows built on MCP, covering the risks of wiring diverse capabilities into one agent.

- [Tenant enumeration is dead](https://www.sprocketsecurity.com/blog/tenant-enumeration-is-dead) by Sprocket Security.
> Microsoft closed the unauthenticated ACS metadata endpoint that dumped every domain in a tenant in one GET. Recon now means stitching together DKIM CNAME lookups, MX brute-forcing, and authenticated Graph queries.

- [A QEMU 0-day, after DEF CON patched the n-day](https://kqx.io/post/qemu-0day) by [Alex Plaskett](https://x.com/alexjplaskett/status/2058792725290303865).
> After DEF CON patched their QEMU n-day, kqx goes hunting and turns up a fresh 0-day in the same hypervisor.

- [An OS built to reverse-engineer CPUs, used on Apple Silicon](https://www.csail.mit.edu/news/study-how-chips-really-work-mit-researchers-built-their-own-operating-system) by [Alex Plaskett](https://x.com/alexjplaskett/status/2056783973376803268).
> MIT researchers built an operating system for reverse engineering CPUs and used it to probe Apple Silicon branch predictors, uncovering Phantom fetches.

- [Kazuar: anatomy of a nation-state botnet](https://www.microsoft.com/en-us/security/blog/2026/05/14/kazuar-anatomy-of-a-nation-state-botnet) by [bohops](https://x.com/bohops/status/2055130487799075300).
> Microsoft dissects Kazuar, the nation-state botnet, breaking down how it is built and operated.


<details markdown="1">
<summary>More this week (34)</summary>

- [Talos discloses TP-Link, Photoshop, OpenVPN, and Norton VPN flaws](https://blog.talosintelligence.com/tp-link-photoshop-openvpn-norton-vpn-vulnerabilities) by Kri Dontje.
- [Tracking a commodity BadIIS malware-as-a-service ecosystem](https://blog.talosintelligence.com/from-pdb-strings-to-maas-tracking-a-commodity-badiis-ecosystem) by Joey Chen.
- [Identifying People Using Wi-Fi Routers](https://www.schneier.com/blog/archives/2026/05/identifying-people-using-wi-fi-routers.html) by Bruce Schneier.
- [AI-assisted kernel exploit on Apple's M5](https://www.schneier.com/blog/archives/2026/05/macos-kernel-memory-corruption-exploit.html) by Bruce Schneier.
- [We hardened zizmor's GitHub Actions static analyzer](https://blog.trailofbits.com/2026/05/22/we-hardened-zizmors-github-actions-static-analyzer).
- [Navigating lax load balancers: when an intersection gets you inside](https://blog.doyensec.com/2026/05/25/cloudsectidbits-elbaph-alb.html).
- [OTP lockout state enabled an OLX account takeover](https://minanagehsalalma.github.io/olx-account-takeover).
- [The War Between Wars: an IRGC front's destructive OT and IT attacks](https://profero.io/blog/war-between-wars).
- [How Mythos did not bypass Apple Memory Integrity Enforcement](https://ironpeak.be/blog/bypassing-apple-mie).
- [Restoring testability in Burp Suite with a custom extension](https://hnsecurity.it/blog/restoring-testability-slides-code-video).
- [Gargoyle, a decade later](https://lospino.so/blog/gargoyle-a-decade-later) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2058914327856378166).
- [CERT.pl on autonomous, LLM-driven fuzzing](https://cert.pl/en/posts/2026/05/autonomous-fuzzing) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2057820551079448915).
- [CVE-2026-9082: unauthenticated SQL injection in Drupal core JSON:API](https://nvd.nist.gov/vuln/detail/CVE-2026-9082) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2057710201009004595).
- [Megalodon sprays fake GitHub PRs to compromise CI/CD](https://www.ox.security/blog/megalodon-cicd-malware-github) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2057552813496930794).
- [Red Team Gold: extracting credentials from MDT shares](https://trustedsec.com/blog/red-team-gold-extracting-credentials-from-mdt-shares) by [Oddvar Moe](https://x.com/Oddvarmoe/status/2055809351521046815).
- [Hunting ROADtools abuse with AADGraphActivityLogs](https://cloudbrothers.info/en/aadgraphactivitylogs) by [Sean Metcalf](https://x.com/PyroTek3/status/2059367643711164655).
- [Mitigating and detecting AITM in Entra ID](https://x.com/PyroTek3/status/2059369308208132263) by Sean Metcalf.
- [Stealthier RDP persistence by bypassing the Remote Desktop Users group](https://x.com/PyroTek3/status/2059369555001012711) by Sean Metcalf.
- [Catching Azure VM RunCommand abuse that activity logs miss](https://github.com/elastic/detection-rules/blob/98fa451f525871ad497e9036f39722093ccd2656/rules/cross-platform/execution_azure_vm_run_command_powershell_unrestricted_script.toml) by [Samir](https://x.com/SBousseaden/status/2057780864897949973).
- [Spelunking through Splunk](https://specterops.io/blog/2026/05/27/spelunking-through-splunk) by Alexander Sou.
- [Bypassing 429 rate limits on Microsoft Graph](https://www.r-tec.net/r-tec-blog-the-429-microsoft-graph-mystery.html) by [S3cur3Th1sSh1t](https://x.com/ShitSecure/status/2057049116530667922).
- [Local models vs frontier models at finding Linux kernel bugs](https://bynar.io/blog/discovery-validation-in-the-linux-kernel-part-3-local-vs-frontier-models) by [SinSinology](https://x.com/SinSinology/status/2057092304838574456).
- [Why NTLM reflection fails on pre-2016 Windows](https://github.com/Pennyw0rth/NetExec/pull/1245) by [Steven Lowson](https://x.com/StevoLowson/status/2057915049964871883).
- [Mapping 1,350 C2 servers across the Middle East](https://hunt.io/blog/middle-east-malicious-infrastructure-report) by [SwitHak ()](https://x.com/SwitHak/status/2057852426716152134).
- [Using the Windows Server 2003 source to make red team tools blend in](https://www.abdulmhsblog.com/posts/useingthewindowssourcecode) by [Rasta Mouse](https://x.com/_RastaMouse/status/2058297581092946407).
- [How vulnerable OLTs could expose entire ISP networks](https://blog.quarkslab.com/how-olts-may-have-exposed-entire-isp-networks.html) by [winterknife](https://x.com/_winterknife_/status/2056814946634146159).
- [An unexpected journey into Microsoft Defender's signatures](https://retooling.io/blog/an-unexpected-journey-into-microsoft-defenders-signature-world) by [Alex Ionescu](https://x.com/aionescu/status/2057516522642251869).
- [Postcards from OffensiveCon 2026](https://www.nccgroup.com/research/postcards-from-berlin-offensivecon-2026) by [Alex Plaskett](https://x.com/alexjplaskett/status/2059242167978074457).
- [A look at the Linux epoll use-after-free](https://guysrd.github.io/) by [Alex Plaskett](https://x.com/alexjplaskett/status/2059168354334605520).
- [An agent pipeline that found five V8 Wasm type-confusion bugs](https://github.com/qriousec/colony_agent) by [Alex Plaskett](https://x.com/alexjplaskett/status/2057504870131769502).
- [PCIe DMA cheats: IOMMU bypass, FPGA hardware, and detection](https://kernullist.github.io/kernullist-blog/posts/pcie-dma-cheats) by [Alex Plaskett](https://x.com/alexjplaskett/status/2057718132295303392).
- [Navigating the iOS MTE landscape](https://fuzzinglabs.com/wp-content/uploads/2026/05/Navigating_iOS_MTE_Landscape.pdf) by [Alex Plaskett](https://x.com/alexjplaskett/status/2056776590223081728).
- [ExploitBench: benchmarking AI exploit generation](https://exploitbench.ai/) by [Alex Plaskett](https://x.com/alexjplaskett/status/2056335016464990275).
- [Reverse engineering and modifying HDD firmware](https://icode4.coffee/?p=1465) by [Alex Plaskett](https://x.com/alexjplaskett/status/2055158450443739365).

</details>


## Tools and Exploits

- [Introducing EvidenceForge: Synthetic security logs that don’t look (as) fake](https://blog.talosintelligence.com/introducing-evidenceforge-synthetic-security-logs-that-dont-look-as-fake) by David J. Bianco.
> Talos open-sources a generator for realistic, multi-format security log datasets, so teams can train analysts and validate detections without hand-built simulations.

- [TailscaleHound: mapping Tailscale attack paths in BloodHound](https://specterops.io/blog/2026/05/21/tailscalehound) by Andrew Gomez.
> A BloodHound OpenGraph collector that maps Tailscale users, devices, ACLs, routes, and keys so you can answer who can reach what.

- [TREVORspray adds DKIM-based tenant enumeration](https://github.com/blacklanternsecurity/TREVORspray/pull/54).
> TREVORspray adapts to the post-ACS world: it now pulls M365 tenant names from DKIM selector CNAMEs during recon, and adds a --user-enum flag for scripted spraying.


<details markdown="1">
<summary>More this week (11)</summary>

- [Mona tellme: AI-assisted crash triage](https://www.corelan.be/index.php/2026/05/14/mona-tellme).
- [LOLRMM: spotting and blocking the RMM tools attackers abuse](https://lolrmm.io/tools/screenconnect) by [The Haag™](https://x.com/M_haggis/status/2057471170262528392).
- [FortiGate SSL-VPN honeypot adds AI summaries and AD validation](https://github.com/PeterGabaldon/Fortigate.VPN-SSL.Honeypot) by [Peter Gabaldon](https://x.com/PedroGabaldon/status/2056466735234994343).
- [The Relay Bible: an NTLM relay reference](https://github.com/rootsecdev/relay_bible) by [Sean Metcalf](https://x.com/PyroTek3/status/2057504555902943559).
- [MiniPlasma: standard-user to SYSTEM LPE on patched Windows 11](https://github.com/Nightmare-Eclipse/MiniPlasma) by [Samir](https://x.com/SBousseaden/status/2055645767583367635).
- [CLR-STOMP: in-memory .NET via module stomping to fool ETW and AMSI](https://github.com/nettitude/CLR-STOMP) by [S3cur3Th1sSh1t](https://x.com/ShitSecure/status/2057876490109272423).
- [Microsoft open-sources Rampart and Clarity for agentic AI safety](https://msft.it/6010vpmBQ) by [SwitHak ()](https://x.com/SwitHak/status/2057157073536753810).
- [Metasploit module for Hikvision NVR RCE (CVE-2025-66177)](https://github.com/ang3lL/CVE-2025-66177/tree/main) by [X-C3LL](https://x.com/TheXC3LL/status/2058492192272830769).
- [Impacket 0.13.1 adds new relay surfaces](https://www.coresecurity.com/blog/whats-new-impacket-0131) by [Rasta Mouse](https://x.com/_RastaMouse/status/2056980735374856532).
- [Striga: lifting x86 to LLVM IR in Python](https://secret.club/2026/05/21/striga.html) by [winterknife](https://x.com/_winterknife_/status/2057749177023521167).
- [xpcspy updated for the latest Frida, now in OWASP MASTG](https://mas.owasp.org/MASTG/tools/ios/MASTG-TOOL-0150) by [Abdelrahman](https://x.com/ab__rizk/status/2057441539488366712).

</details>



