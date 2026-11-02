---
title: "Crow's Nest - 2026-11-02"
date: 2026-11-02T00:00:00+00:00
draft: false
tags: ["roundup"]
---

A roundup of 130 items curated from across the security community.

## News

- [Backdoored Claude Code Extension Found on Open VSX](https://phorion.io/blog/offical-claude-code-vsx-compromise) by [Patrick Wardle](https://x.com/patrickwardle/status/2116096636791537833).
> Phorion found version 2.1.313 of the official Claude Code for VS Code bundle on Open VSX dropping a persistent SSH backdoor on macOS, Linux and Windows. The writeup covers the implant, a bug in its macOS setup logic, and what to hunt for.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://cursor.com/blog/claude-code-extension-security-notice">Cursor: Security Notice on the Claude Code Extension Incident</a> (Florian Roth)</details>

- [Silent Train: Volt Typhoon's Zero-Day Exploitation Framework](https://www.lumen.com/blog/en-us/silent-train-volt-typhoon-operational-framework) by [SwitHak ()](https://x.com/SwitHak/status/2115490931881263369).
> Lumen's Black Lotus Labs exposes the framework Volt Typhoon uses to stage zero-day exploitation and keep long-term access to strategic targets.
  >
  > <details class="story-more"><summary>+2 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/volt-typhoon-hides-zero-day-attacks-using-silent-train-framework">Volt Typhoon hides zero-day attacks using &#x27;Silent Train&#x27; framework</a> (BleepingComputer)<br><a href="https://www.zetter-zeroday.com/silent-train-volt-typhoons-sophisticated-infection-chain-into-us-targets-exposed">Kim Zetter: Silent Train Exposes Volt Typhoon&#x27;s Infection Chain</a> (Kim Zetter)</details>

- [HTTP2Shell: Brotli Flaw Triggers Emergency Patches](https://www.bleepingcomputer.com/news/security/critical-http2shell-brotli-vulnerability-triggers-emergency-patches) by [BleepingComputer](https://x.com/BleepinComputer/status/2114756007029055967).
> The Brotli bug behind last week's Node2Shell (CVE-2026-111497) reaches far past Node.js. Microsoft shipped emergency .NET patches, and Zero Day Engineering reports active exploitation.
  >
  > <details class="story-more"><summary>+2 more on this story</summary><a href="https://www.bleepingcomputer.com/news/microsoft/microsoft-releases-emergency-net-patches-for-critical-brotli-flaw">Microsoft releases emergency .NET patches for critical Brotli flaw</a> (BleepingComputer)<br><a href="https://intelligence.zerodayengineering.com/0-day-alert-cve-2026-111497/">Zero Day Engineering: Brotli CVE-2026-111497 Now Exploited in the Wild</a> (Florian Roth)</details>

- [Australia Takes Over Amadey Backend, Cuts Off 180,000 Bots](https://thehackernews.com/2026/10/australia-gets-into-amadey-malware.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2115028637103587697).
> Australian authorities got inside the Amadey malware infrastructure and severed its access to roughly 180,000 infected computers.

- [KeyDrift: APT Exploits Cisco SD-WAN Auth Bypass](https://blog.talosintelligence.com/uat-11473-keydrift) by Cisco Talos.
> Talos tracks UAT-11473, a sophisticated APT that used the CVE-2026-20127 authentication bypass in Cisco SD-WAN Catalyst Controller to deploy its KeyDrift malware.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/hackers-exploit-cisco-sd-wan-flaw-to-deploy-custom-keydrift-malware">Hackers exploit Cisco SD-WAN flaw to deploy custom KeyDrift malware</a> (BleepingComputer)</details>

- [Police Seize Virtualine Bulletproof Hosting](https://www.bleepingcomputer.com/news/security/police-seize-virtualine-bulletproof-service-tied-to-ransowmare-cybercrime) by [BleepingComputer](https://x.com/BleepinComputer/status/2115546062358204887).
> Law enforcement took down Virtualine, a bulletproof hosting service tied to ransomware and other cybercrime operations.

- [Chinese Attackers Chain PHP2Shell With a Kernel Bug, Root 25 Servers](https://www.theregister.com/security/2026/10/29/suspected-chinese-attackers-built-a-custom-php2shell-exploit-and-rooted-25-servers/5306456) by [Sean Metcalf](https://x.com/PyroTek3/status/2115927654725820491).
> Suspected Chinese operators built a custom PHP2Shell exploit and paired it with a Linux kernel flaw to root 25 servers, including Palo Alto Networks firewalls tied to US government-affiliated organizations. CISA has since added PHP2Shell and the Fragnesia Linux LPE seen in these chains to KEV.
  >
  > <details class="story-more"><summary>+3 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/cisa-confirms-php2shell-vulnerabilities-now-exploited-in-attacks">CISA Adds PHP2Shell Flaws to KEV</a> (BleepingComputer)<br><a href="https://www.bleepingcomputer.com/news/security/cisa-warns-of-fragnesia-linux-flaw-chained-in-php2shell-attacks">CISA: Fragnesia Linux LPE Chained in PHP2Shell Attacks</a> (BleepingComputer)<br><a href="https://php.events.greynoise.io/">GreyNoise: Live Feed of PHP2Shell Intrusions</a> (Steve YARA Synapse Miller)</details>

- [Ivanti Connect Secure: Three-Bug Chain to Unauthenticated Root](https://thehackernews.com/2026/10/attackers-chain-three-ivanti-connect.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2116472263499493446).
> Attackers are chaining three Ivanti Connect Secure flaws to get root on appliances without credentials.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/ivanti-patches-two-more-connect-secure-zero-days-chained-in-attacks">Ivanti patches two more Connect Secure zero-days chained in attacks</a> (BleepingComputer)</details>

- [Inside the $6.3B Binance Hot Wallet Drain](https://www.hypernative.io/insights/blog/inside-the-largest-crypto-theft-of-all-time-the-6-3b-binance-hot-wallet-drain) by [Phil Venables](https://x.com/philvenables/status/2116522848353210450).
> Hypernative reconstructs what it calls the largest crypto theft on record. The FBI has attributed it to North Korea, and Chainalysis is tracking never-before-seen laundering patterns for the stolen funds.
  >
  > <details class="story-more"><summary>+4 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/binance-probes-potential-58-billion-crypto-theft-hack">Binance probes potential $5.8 billion crypto-theft hack</a> (BleepingComputer)<br><a href="https://www.chainalysis.com/blog/binance-exploit-latest-findings-and-response">Chainalysis: Binance Exploit Laundering Patterns</a> (Nicolas Krassas)<br><a href="https://www.fbi.gov/investigate/cyber/alerts/2026/north-korea-responsible-for-6-billion-binance-attack">FBI: North Korea Responsible for the $6 Billion Binance Attack</a> (AndrewMohawk⁽ⁿᵘˡˡ⁾)<br><a href="https://www.bleepingcomputer.com/news/security/fbi-links-63-billion-binance-crypto-heist-to-north-korean-hackers">FBI links $6.3 billion Binance crypto heist to North Korean hackers</a> (BleepingComputer)</details>

- [Linux Multipath TCP Flaw Gives Unauthenticated Remote Root](https://lwn.net/Articles/1104192).
> Anthropic researchers built an exploit for a critical kernel bug that lets unauthenticated attackers run commands as root on servers with MPTCP listeners. LWN has the technical rundown.
  >
  > <details class="story-more"><summary>+2 more on this story</summary><a href="https://www.anthropic.com/research/discovering-vulnerabilities-with-claude">Anthropic: Discovering Vulnerabilities With Claude</a> (Alex Plaskett)<br><a href="https://www.bleepingcomputer.com/news/security/critical-linux-kernel-flaw-allows-remote-root-attacks-on-mptcp-servers">Critical Linux Kernel Flaw Allows Remote Root on MPTCP Servers</a> (BleepingComputer)</details>


<details markdown="1">
<summary>More this week (31)</summary>

- [Hackers hijack Convertr analytics script to steal payment card data](https://www.bleepingcomputer.com/news/security/hackers-hijack-convertr-analytics-script-to-steal-payment-card-data) by [BleepingComputer](https://x.com/BleepinComputer/status/2115186192891142303).
- [Microsoft releases Windows OOB updates to distrust eMudhra certificates](https://www.bleepingcomputer.com/news/microsoft/microsoft-releases-windows-oob-updates-to-distrust-emudhra-certificates) by [BleepingComputer](https://x.com/BleepinComputer/status/2115146692815200535). <details class="story-more"><summary>+3 more on this story</summary><a href="https://msft.it/6014aL3Ri">MSRC: Microsoft&#x27;s Response to the eMudhra CA Issue</a> (SwitHak ())<br><a href="https://support.apple.com/en-us/149555">Apple: Removing the Compromised eMudhra Certificates</a> (thaddeus e. grugq)<br><a href="https://fixemudhra.com/">fixemudhra.com: Check Whether You&#x27;re Affected</a> (SinSinology)</details>
- [Warp discloses breach exposing AI agent logs, user telemetry data](https://www.bleepingcomputer.com/news/security/warp-discloses-breach-exposing-ai-agent-logs-user-telemetry-data) by [BleepingComputer](https://x.com/BleepinComputer/status/2115115315168248276).
- [Apple backports CoreGraphics zero-day patches to older iPhones](https://www.bleepingcomputer.com/news/apple/apple-backports-coregraphics-zero-day-patches-to-older-iphones) by [BleepingComputer](https://x.com/BleepinComputer/status/2115030579477467462).
- [Tailscale SSH Flaws Allowed Root Privilege Escalation](https://tailscale.com/security-bulletins) by [Nicolas Krassas](https://x.com/Dinosn/status/2115128969691599163). <details class="story-more"><summary>+1 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/tailscale-warns-of-serious-ssh-flaws-allowing-root-privilege-escalation">Tailscale warns of SSH flaws allowing root privilege escalation</a> (BleepingComputer)</details>
- [Lazarus Abuses South Korean Security Software to Deploy Malware Using Post-Quantum Encryption](https://thehackernews.com/2026/10/lazarus-abuses-south-korean-security.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2115061578886254892).
- [Keystone to Destroy 18,835 Hardware Wallets After Hackers Steal Device Verification Key](https://thehackernews.com/2026/10/keystone-to-destroy-18835-hardware.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2115061502952505387).
- [Microsoft Authenticator Flaw Let Permissionless Android Apps Steal Work Account Tokens](https://thehackernews.com/2026/10/microsoft-authenticator-flaw-let.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2115061469662634470).
- [TianoCore EDK2 Advisory: PXE Code Execution Before Secure Boot](https://github.com/tianocore/edk2/security/advisories/GHSA-99cj-7hg9-mp4m) by [kmkz](https://x.com/kmkz_security/status/2115562701078560881).
- [Two Critical RCEs in WatchGuard Fireware OS](https://secorizon.com/advisories) by [kmkz](https://x.com/kmkz_security/status/2115417213775532520).
- [NIK C2: The new AI-enabled command-and-control framework](https://blog.talosintelligence.com/nik-c2-new-ai-enabled-framework) by Chetan Raghuprasad.
- [Israeli Spyware Firm Targets Starlink Users Through Ad Bidding](https://www.reuters.com/business/media-telecom/alleged-israeli-spy-company-heavily-targeted-starlink-users-sources-say-2026-10-27) by [nyxgeek](https://x.com/nyxgeek/status/2115268160811081942).
- [ESET APT Activity Report: UNC1151 Destructive Attack](https://web-assets.esetstatic.com/wls/en/papers/threat-reports/eset-apt-activity-report-q2-2026-q3-2026.pdf) by [thaddeus e. grugq](https://x.com/thegrugq/status/2115851508491460829).
- [Polymarket Drained via Compromised Third-Party JavaScript](https://www.bleepingcomputer.com/news/security/polymarket-halts-trading-after-crypto-draining-script-breach-25m-traced) by [BleepingComputer](https://x.com/BleepinComputer/status/2115923606442066006).
- [Chrome extensions with 13.4 million installs caught hijacking searches](https://www.bleepingcomputer.com/news/security/chrome-extensions-with-134-million-installs-caught-hijacking-searches) by [BleepingComputer](https://x.com/BleepinComputer/status/2115838777918722553).
- [New Cisco firewall zero-day exploited to crash SSL VPN devices](https://www.bleepingcomputer.com/news/security/cisco-warns-of-firewall-zero-day-exploited-to-crash-ssl-vpn-devices) by [BleepingComputer](https://x.com/BleepinComputer/status/2115763221231489241).
- [Telegram Android Flaw Lets Attackers Run Code When Users Answer Voice Calls](https://thehackernews.com/2026/10/telegram-android-flaw-lets-attackers.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2115796328483811647).
- [Chinese Hackers Exploit VMware ESXi 0-Day to Hide Activity](https://cybersecuritynews.com/vmware-esx-logging-vulnerability-exploited) by [Sean Metcalf](https://x.com/PyroTek3/status/2115937762851409923).
- [GLPI Mass Assignment Enables Silent Account Takeover](https://www.synacktiv.com/en/advisories/glpi-mass-assignment-in-the-password-reset-flow-enables-post-exploitation-silent-account) by [Synacktiv](https://x.com/Synacktiv/status/2115731361336344911).
- [Supermicro BMC IPMI Security Advisory (October 2026)](https://www.supermicro.com/de-de/support/security_BMC_IPMI_Oct_2026_1).
- [Appraisal by AI: Model-driven victim prioritization in the VOLTA infostealer](https://blog.talosintelligence.com/appraisal-by-ai-model-driven-victim-prioritization-in-the-volta-infostealer) by Ryan Fetterman.
- [CISA says max severity GitLab flaw now exploited in the wild](https://www.bleepingcomputer.com/news/security/hackers-now-exploiting-max-severity-gitlab-flaw-in-attacks) by [BleepingComputer](https://x.com/BleepinComputer/status/2116153394767319205). <details class="story-more"><summary>+2 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/alpine-linux-rebuilds-gitlab-after-attempted-rce-attack">Alpine Linux rebuilds GitLab after attempted RCE attack</a> (BleepingComputer)<br><a href="https://www.bleepingcomputer.com/news/security/over-1-000-gitlab-servers-vulnerable-to-code-execution-attacks">Over 1,000 GitLab servers vulnerable to ongoing RCE attacks</a> (BleepingComputer)</details>
- [Drupal warns of critical Commerce Core flaw exploited in attacks](https://www.bleepingcomputer.com/news/security/drupal-warns-of-critical-commerce-core-flaw-exploited-in-attacks) by [BleepingComputer](https://x.com/BleepinComputer/status/2116111962757120032).
- [New Android SMS of Death exploit can remotely crash unpatched phones](https://www.bleepingcomputer.com/news/security/new-android-sms-of-death-exploit-can-remotely-crash-unpatched-phones) by [Nicolas Krassas](https://x.com/Dinosn/status/2116565293434577145).
- [Trezor: Implant Found in a Resold Hardware Wallet](https://trezor.io/blog/news/implant-reported-in-a-trezor-sold-by-cryptobilis) by [Kim Zetter](https://x.com/KimZetter/status/2116189270558023752). <details class="story-more"><summary>+1 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/trezor-warns-of-suspected-crypto-theft-implant-in-hardware-wallet">Trezor warns of suspected crypto-theft implant in hardware wallet</a> (BleepingComputer)</details>
- [Microsoft: Human-Operated Intrusions via Teams Help-Desk Impersonation](https://msft.it/6010aFi3j) by [Thomas Roccia](https://x.com/fr0gger_/status/2116349801315106979).
- [Chainalysis Discloses a Security Incident](https://www.chainalysis.com/blog/security-incident-october-30) by [scriptjunkie (Matt)](https://x.com/scriptjunkie1/status/2117089909081325576). <details class="story-more"><summary>+1 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/chainalysis-discloses-data-breach-from-offensive-agentic-techniques">Chainalysis discloses data breach from &quot;offensive agentic techniques&quot;</a> (BleepingComputer)</details>
- [BTCPay Server warns of hot wallet thefts targeting outdated instances](https://www.bleepingcomputer.com/news/security/btcpay-server-warns-of-hot-wallet-thefts-targeting-outdated-instances) by [BleepingComputer](https://x.com/BleepinComputer/status/2117271381708624168).
- [Hackers disrupt refrigeration systems at European supermarkets](https://www.bleepingcomputer.com/news/security/hackers-disrupt-refrigeration-systems-at-european-supermarkets) by [BleepingComputer](https://x.com/BleepinComputer/status/2117262688812212626).
- [Synology warns of C3RB3R ransomware attacks targeting NAS devices](https://www.bleepingcomputer.com/news/security/synology-warns-customers-of-ongoing-c3rb3r-ransomware-attacks) by [BleepingComputer](https://x.com/BleepinComputer/status/2117217395697746101).
- [Northflank security breach leads to abuse of customers' AI API keys](https://www.bleepingcomputer.com/news/security/northflank-security-breach-leads-to-abuse-of-customers-ai-api-keys) by [BleepingComputer](https://x.com/BleepinComputer/status/2116591398073876550).

</details>


## Techniques and Write-ups

- [Orange Tsai: Logic-Bug Full Chain Against Microsoft Edge](https://blog.orange.tw/posts/2026-10-the-last-proof-of-human-craft-browser-full-chain) by [Ken Gannon (伊藤 剣)](https://x.com/Yogehi/status/2115502253251674598).
> Orange Tsai pops Microsoft Edge with a chain of logic bugs and walks through each link. A companion video runs the chain the other way, popping Edge from calc.exe.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://www.youtube.com/watch?v=Bh1zglq4mLE">Video: The Chain Flipped, Popping Edge From calc.exe</a> (Orange Tsai)</details>

- [Oracle PeopleSoft SSRF to RCE (CVE-2026-35273)](https://www.zerodayinitiative.com/blog/2026/10/20/cve-2026-35273-ssrf-to-rce-in-oracle-peoplesoft) by [SinSinology](https://x.com/SinSinology/status/2115122521532240024).
> ZDI's Bobby Gould breaks down the bugs behind the recent PeopleSoft attacks, with root cause analysis and a video demo.

- [WESP: Microsoft's Plan to Move EDR Out of the Kernel](https://www.elastic.co/security-labs/blog/windows-endpoint-security-platform-wesp) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2115068044720648562).
> Elastic Security Labs digs into the Windows Endpoint Security Platform preview, the architecture security vendors would use instead of kernel drivers.

- [Turning the Valve: RCE and LPE in Steam](https://www.atredis.com/blog/2026/10/28/turning-the-valve).
> Atredis exploits Valve's Steam platform for both remote code execution and local privilege escalation.

- [Axis Camera Station: Unauth RCE to Every Camera Credential](https://ricardojoserf.github.io/axisrce).
> Chains CVE-2025-30026, CVE-2025-30023 and CVE-2026-63286 from unauthenticated RCE to decrypting the stored credentials for every managed camera.

- [PHP2Shell: Bypassing ASLR With display_errors Off](https://www.praetorian.com/blog/php2shell) by [Michael Weber](https://x.com/BouncyHat/status/2115596993686917489).
> Praetorian shows how to defeat ASLR when error output is disabled, why an exposed phpinfo page makes exploitation much easier, and the interpreter code involved. The community php2shell exploit collection now covers 30 RCE profiles.
  >
  > <details class="story-more"><summary>+2 more on this story</summary><a href="https://andrewmohawk.com/2026/10/26/picking-apart-php2shell">Picking Apart PHP2Shell</a> (AndrewMohawk⁽ⁿᵘˡˡ⁾)<br><a href="https://github.com/devploit/php2shell">php2shell Exploit Collection Grows to 30 RCE Profiles</a> (Spiros Fraganastasis)</details>

- [Autonomous N-Day Exploit Generation for the Windows Kernel](https://youtu.be/03Xh_6_6U4M) by [chompie](https://x.com/chompie1337/status/2115576088747561222).
> chompie's pipeline mixes deterministic and AI-led stages and reports results comparable to Anthropic's using a much less powerful model. Talk video from BSides Canberra.

- [BeyondTrust Remote Support: Unauth File Upload to RCE (CVE-2026-102764)](https://www.rapid7.com/blog/post/ra-rapid7-analysis-unauthenticated-file-upload-to-rce-in-beyondtrust-remote-support-cve-2026-102764) by [SinSinology](https://x.com/SinSinology/status/2116534980494889076).
> Rapid7 publishes the technical details, and a Metasploit module is already available.

- [Pass-ta-key: Stealing Google Password Manager Passkeys From Chrome](https://0rcruxe.github.io/posts/pass-ta-key-golden-attack-decrypting-gpm-passkeys) by [Max](https://x.com/maxime_tz/status/2116796331930816745).
> Pulls the Security Domain Secret from Chrome process memory, decrypts synced passkeys, and forges WebAuthn assertions for account takeover. PoC included.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://github.com/0rcruxe/pass-ta-key">pass-ta-key PoC Tool</a> (topotam)</details>

- [How Hacktron Could Have Backdoored Bash via GNU Savannah](https://www.hacktron.ai/blog/hacking-gnu-savannah).
> Flaws in GNU Savannah, the hosting platform for core GNU projects, would have let an attacker tamper with Bash at the source.


<details markdown="1">
<summary>More this week (31)</summary>

- [Reviving GLPI Agent Abuse With ESC17](https://fenrisk.com/research/esc-17-glpi).
- [Fuzzers vs. AI: Comparing Fuzzilli and BigSleep on JavaScript Engines](https://projectzero.google/2026/10/fuzzing-v-AI.html) by Samuel Groß.
- [GhostAction Crosses Paths With PolinRider](https://blog.gitguardian.com/ghostaction-x-polinrider).
- [Tricks from the Past deployed via signed ChatGPT and Claude binaries](https://research.checkpoint.com/2026/tricks-from-the-past-deployed-via-signed-chatgpt-and-claude-binaries) by [Nicolas Krassas](https://x.com/Dinosn/status/2115082022670782975).
- [Silently Fixed Linux Kernel LPE Reproduced (ZDI-CAN-33367)](https://www.pruva.dev/reproductions/REPRO-2026-00388) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2114965185827913961).
- [ConnectWise App Exposes Entra Tenants: What to Check, With Scripts](https://petri.com/connectwise-app-exposes-entra-tenants) by [Sean Metcalf](https://x.com/PyroTek3/status/2115195635733541326).
- [Cache Me If You Can: XSS in Cloudflare's /cdn-cgi/image/](https://www.slcyber.io/research/cache-me-if-you-can-xss-in-cloudflares-cdn-cgi-image).
- [When Picos Attack: USB Exploit Engineering (Hexacon Slides)](https://www.nccgroup.com/research/when-picos-attack-usb-exploit-engineering) by [Alex Plaskett](https://x.com/alexjplaskett/status/2115047791257121252).
- [Huntress: AI-Operated ConnectWise Intrusion Into Microsoft 365 Tenants](https://www.huntress.com/blog/connectwise-attack-ai) by [Florian Roth](https://x.com/cyb3rops/status/2114859963902214352).
- [Fuzzing complex state machines with LibAFL-QEMU and incremental snapshots](https://blog.quarkslab.com/snapshotting-our-way-to-cve-2026-9539.html) by [Dave Aitel](https://x.com/daveaitel/status/2115130999117844490).
- [iOS 26 Hacked by a Font (CVE-2026-86950 Calif analysis)](https://youtu.be/Nqnf5k8dkkE?is=WOJtp4-JFInDGKHM) by [Simone Margaritelli](https://x.com/evilsocket/status/2115433411641024751).
- [XML Signature Wrapping Auth Bypass in the MPass SAML Library](https://www.masiutin.net/mpass-saml-xml-signature-wrapping.html).
- [Azure API Management as a Policy-Based C2 Redirector](https://redops.at/research/azure-api-management-as-a-policy-based-c2-redirector) by [Panos Gkatziroulis](https://x.com/ipurple/status/2115085001402507606).
- [Top 10 Web Hacking Techniques Archive: Every Nominee Since 2006](https://webhacklist.com/) by [Swissky](https://x.com/pentest_swissky/status/2115454288298377510).
- [EMBRACE: Hacking the Embedded Browsers in Five Desktop AI Assistants](https://forever.security/blog/embrace-hacking-5-ai-assistants-embedded-browsers).
- [TightVNC Viewer Pre-Auth RCE](https://ssd-disclosure.com/tightvnc-viewer-pre-auth-rce).
- [TeamViewer RCE (CVE-2026-11585)](https://remedio.io/research/vulnerability-disclosures/remote-code-execution-in-teamviewer).
- [Chromecast With Google TV 4K Secure Boot Bypass](https://lnkd.in/eAhXWbsV) by [Sick.Codes](https://x.com/sickcodes/status/2115055279431913584).
- [Hacking Back AI Pentesting Agents](https://plaintext.do/en/blog/hacking-back-ai-pentesting-agents) by [thaddeus e. grugq](https://x.com/thegrugq/status/2115536327450268030).
- [Entra Federated Credential Subject Recycling Enables Takeover](https://nicolasuter.ch/til/entra-federated-credentials-subject-recycling) by [DebugPrivilege](https://x.com/DebugPrivilege/status/2115833881547165721).
- [Exploiting Reversing Article 11: Missing Bounds in the Print Spooler](https://exploitreversing.com/2026/10/27/exploiting-reversing-er-series-article-11) by [Stephen Sims](https://x.com/Steph3nSims/status/2115137602638782534).
- [ClickFix Malware Obfuscates msiexec Command Lines to Evade Detection](https://www.threathunter.ai/blog/azure30-nodejs-backdoor-trojanized-msi-clickfix) by [Wietze](https://x.com/Wietze/status/2115476995123417311).
- [Metamorphic compiler](https://herm1tvx.blogspot.com/2026/10/metamorphic-compiler.html) by [tmp.0ut](https://x.com/tmpout/status/2116141247249498206).
- [Credential Harvesting With PDFs and WebSockets](https://g3tsyst3m.com/initial%20access/Using-PDFs-and-Websockets-for-Creative-Credential-Harvesting) by [Mr.Z](https://x.com/zux0x3a/status/2116334068631511315).
- [Malicious Shared ChatGPT Link Leads to Account Takeover](https://www.parameter.ai/labs/we-found-a-gap-at-openai) by [Nicolas Krassas](https://x.com/Dinosn/status/2116384992561701345).
- [Chrome GPU Sandbox Escape via Keyboard Injection (CVE-2026-106378)](https://pwn.ai/blog/chrome-escape) by [Paulos Yibelo](https://x.com/PaulosYibelo/status/2116177179054686279).
- [CodeQLLM: CodeQL Plus Local LLMs for Code Audits (Synacktiv)](https://www.synacktiv.com/sites/default/files/2026-10/tlp-clear-kevin-tellier-hugo-vincent-the-augmented-auditor.pdf) by [Synacktiv](https://x.com/Synacktiv/status/2116181568331165889).
- [GTIG: ARTEX and Friends Enter Agentic Offensive Frameworks](https://cloud.google.com/blog/topics/threat-intelligence/artex-and-friends-enter-agentic-offensive-frameworks) by [Florian Roth](https://x.com/cyb3rops/status/2116863132081742080). <details class="story-more"><summary>+1 more on this story</summary><a href="https://www.crowdstrike.com/en-us/blog/unknown-threat-actor-uses-artex-to-target-south-korean-finance">Unknown Threat Actor Uses AI-Driven ARTEX to Target South Korean Finance - CrowdStrike</a> (Swissky)</details>
- [Linux IPv4 TCP Use-After-Free (CVE-2026-98432)](https://atlasum.net/blog/cve-2026-98432-linux-ipv4-tcp-uaf) by [Rémi GASCOU (Podalirius)](https://x.com/podalirius_/status/2116992394562261145).
- [WordPress Pingback RCE via the Brotli Bug (CVE-2026-111497)](https://fortbridge.co.uk/research/cve-2026-111497-wordpress-pingback-rce-reproduction).
- [Dangerous Device: Exploiting Linux Kernel CVE-2026-31695](https://a13xp0p0v.tech/2026/11/02/CVE-2026-31695.html).

</details>


## Tools and Exploits

- [VulnCheck Initial Access Community Edition](https://www.vulncheck.com/blog/initial-access-community) by [Caleb Gross](https://x.com/noperator/status/2115849465730928666).
> A free, open-source repo of initial access exploits, each shipped with a PCAP, a target Docker container and Snort/Suricata rules. New additions every Monday.

- [ntlmrelayx Fork With the LDAP Signing Bypass](https://github.com/grayhatkiller/impacket) by [n00py](https://x.com/n00py1/status/2115488450006933906).
> A ready-to-use implementation of last week's SpecterOps research on bypassing LDAP signing through NTLM relay re-authentication.

- [StealMyBitcoin Solved: Full PoC Writeup](https://github.com/KillaBoi/StealMyBitcoin-PoC) by [Rich Mirch](https://x.com/0xm1rch/status/2114539322032738568).
> killa solved James Pavur's StealMyBitcoin challenge and published the full PoC. LiveOverflow's PHP2Shell exploit walkthrough for the same challenge is folded in below.
  >
  > <details class="story-more"><summary>+2 more on this story</summary><a href="https://stealmybitcoin.com/">Bad Sector Labs: Universal PHP RCE Is Not Easily Clanked</a> (Bobby Cooke)<br><a href="https://www.youtube.com/watch?v=VhNiMWtOutw">LiveOverflow: Building a PHP2Shell Exploit for StealMyBitcoin</a> (LiveOverflow hextree.io)</details>

- [CredGuardRuntimeShutdown: Turning Off Credential Guard at Runtime](https://github.com/S12cybersecurity/CredGuardRuntimeShutdown) by [Octoberfest7](https://x.com/Octoberfest73/status/2115049778426134902).
> LsaIso.exe exposes a named event that tears down VBS credential isolation. With a SYSTEM token, signal it and dump NT hashes straight from LSASS.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://medium.com/@s12deff/runtime-credential-guard-deactivation-d01cb9eb0062">Runtime Credential Guard Deactivation (Writeup)</a> (S3cur3Th1sSh1t)</details>

- [ElectroNG: Doyensec Open-Sources Its Electron Security Scanner](https://blog.doyensec.com/2026/10/27/electrong-oss.html).
> Doyensec's ElectronJS security scanner, previously a commercial product, is now open source.

- [Cobalt Strike Open-Sources an AWS S3 UDC2 Egress Channel](https://www.cobaltstrike.com/resources/videos/cobalt-strike-technical-walkthrough?source=x) by [Cobalt Strike](https://x.com/_CobaltStrike/status/2115114020323590614).
> The demo covers the AWS infrastructure, Terraform deployment, encrypted Beacon traffic and dynamic pre-signed URL refresh.

- [hashcat-utils: Replace the NTLMv1 Multi Tool With Mode 4000](https://github.com/evilmog/hashcat-utils/blob/master/src/ntlmv1-to-4000.sh) by [n00py](https://x.com/n00py1/status/2115466784258363881).
> EvilMog's ntlmv1-to-4000 script converts captured NTLMv1 for hashcat mode 4000, retiring the ntlmv1 multi tool and its shucking clones. A Hackfest talk on it is coming.

- [TpDirectCallbackHijack: Thread Pool Callback Injection](https://github.com/Maldev-Academy/TpDirectCallbackHijack) by [NULL](https://x.com/NUL0x4C/status/2115871423499780528).
> Overwrites one function pointer in an existing TP_IO, TP_ALPC or TP_JOB object and posts a completion packet, so the victim's own worker thread runs the shellcode. No remote thread and no Get/SetThreadContext.

- [Maninthemeeting: Meeting Audio Capture via WASAPI Loopback](https://github.com/leftp/Maninthemeeting) by [Lefteris Panos](https://x.com/lefterispan/status/2115179367290880310).
> Lefteris Panos captures call audio through WASAPI loopback and transcribes it with a local model.

- [TrustedHive: Windows 11 LPE PoC](https://github.com/dis0rder0x00/TrustedHive) by [Swissky](https://x.com/pentest_swissky/status/2117014194566668386).
> Likely a duplicate of CVE-2026-81963 and now fixed, but the author reports it still works on unpatched Windows 11 and Server 2025.


<details markdown="1">
<summary>More this week (6)</summary>

- [dicozorus: Synacktiv's Wordlist Tooling From hack.lu](https://github.com/synacktiv/dicozorus) by [Synacktiv](https://x.com/Synacktiv/status/2115040451627458739).
- [Linux iSCSI tgt RCE 0-Day Drop](https://warez.sl0p.foo/tgt-iscsi-rce) by [blasty](https://x.com/bl4sty/status/2115394170428723523).
- [goshs: Go File Server Built Out Into an Offensive Helper](https://goshs.de/) by [pfiatde](https://x.com/pfiatde/status/2115004476751004061).
- [sandbox_extension symlink bug on iOS 27.2](https://github.com/speedyfriend433/sandbox_extension-TOCTOU-bug) by [Csaba Fitzl](https://x.com/theevilbit/status/2115401150870814756).
- [Microsoft Practical PKI Part 4: Securing CAs, With Locksmith2](https://techcommunity.microsoft.com/blog/coreinfrastructureandsecurityblog/securing-your-certification-authorities-practical-pki-part-4/4549029) by [Sean Metcalf](https://x.com/PyroTek3/status/2116235373294850240).
- [PoC for Apple CVE-2026-112487](https://github.com/Lyutoon/CVE-2026-112487) by [Gergely Kalman](https://x.com/gergely_kalman/status/2116698728069546284).

</details>



