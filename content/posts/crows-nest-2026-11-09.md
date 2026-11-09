---
title: "Crow's Nest - 2026-11-09"
date: 2026-11-09T00:00:00+00:00
draft: false
tags: ["roundup"]
---

A roundup of 137 items curated from across the security community.

## News

- [sshhole: Long Passwords Bypass OpenSSH Auth on musl Linux](https://sshhole.com/) by [Bad Sector Labs](https://x.com/badsectorlabs/status/2118378362951336104).
> musl's crypt() returns `*` when it rejects a password over 256 bytes, which matches the placeholder hash on key-only and locked accounts. Alpine, OpenWrt and other musl boxes running sshd with password auth have been exposed since 2016, and GreyNoise is already tracking exploitation.
  >
  > <details class="story-more"><summary>+4 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/openssh-flaw-lets-attackers-log-into-password-disabled-linux-accounts">OpenSSH flaw lets attackers log into password-disabled Linux accounts</a> (BleepingComputer)<br><a href="https://github.com/leonjza/sshhole-lab">sshhole-lab: Reproduce sshhole Locally</a> (Clément Notin)<br><a href="https://github.com/projectdiscovery/nuclei-templates/pull/17702/changes">CVE-2026-123158 - SSHole - OpenSSH/musl Password Auth Bypass Nuclei Template</a> (ProjectDiscovery)<br><a href="https://sshole.events.greynoise.io/">GreyNoise Live Tracking of SSHole Exploitation</a> (Steve YARA Synapse Miller)</details>

- [OpenAI Pipeline Builds 948 Working Linux Root Exploits](https://openai.com/index/a-thousand-fewer-paths-to-root) by [chompie](https://x.com/chompie1337/status/2118533012509917644).
> One mid-October run reproduced 1,724 kernel bugs and produced working LPE exploits and patches for 948 of them, at about $1,279 per exploit. The model behind it, GPT-6 Cyber, launched the next day and also found 81 novel Firefox renderer RCEs.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://openai.com/index/introducing-gpt-6-cyber">OpenAI Introduces GPT-6 Cyber</a> (Dave Kennedy)</details>

- [Google Dismantles the 1.3M-Device XCPE TV Box Botnet](https://cloud.google.com/blog/topics/threat-intelligence/shutting-the-door-on-the-xcpe-botnet) by [Nicolas Krassas](https://x.com/Dinosn/status/2117249213541060730).
> GTIG says Android OEM Videostrong built the backdoor on purpose and sold access to criminal affiliates, whose modules ran ad fraud, residential proxies and follow-on malware.
  >
  > <details class="story-more"><summary>+2 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/google-disrupts-million-device-xcpe-android-malware-botnet-bans-tv-box-maker">Google disrupts million-device XCPE Android malware botnet, bans TV box maker</a> (Nicolas Krassas)<br><a href="https://krebsonsecurity.com/2026/11/tech-firms-dismantle-botnet-that-turned-1-3m-tv-boxes-into-proxies">Krebs: Tech Firms Dismantle Botnet That Turned 1.3M TV Boxes Into Proxies</a></details>

- [Alpine Linux Rebuilds GitLab After CVE-2026-97229 Attack](https://alpinelinux.org/posts/GitLab-security-incident-CVE-2026-97229.html) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2117260494230729098).
> Upgrading GitLab did not fix the bug, because the fix ships as a Ruby patch that only official GitLab packages apply. Alpine found no tampering with aports, packages or the October 21 releases, but treated the instance as compromised.

- [Defrost and Disrupt: Europe's Refrigeration System Attacks](https://www.sentinelone.com/labs/defrost-and-disrupt-an-assessment-of-europe-s-refrigeration-attacks) by [Steve YARA Synapse Miller](https://x.com/stvemillertime/status/2117653585823453185).
> SentinelLABS lays out the timeline and mechanics of the attacks on supermarket and blood bank cold storage. Russian-aligned groups have relevant history, but the evidence does not yet support attribution, and the FBI has issued its own advisory.
  >
  > <details class="story-more"><summary>+3 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/cyberattack-disrupts-blood-storage-refrigeration-systems-in-france">Cyberattack disrupts blood storage refrigeration systems in France</a> (BleepingComputer)<br><a href="https://www.ic3.gov/CSA/2026/261105.pdf">FBI Advisory on Attacks Against Refrigeration Systems</a> (SwitHak ())<br><a href="https://infrawatch.com/blog/exposed-fridges-shared-suppliers-residential-proxies">Infrawatch: Is Your Fridge a Residential Proxy?</a> (Lloyd Davies)</details>

- [Binance: A Fake Job Interview Led to the $6.3B Heist](https://www.bleepingcomputer.com/news/security/binance-says-fake-job-interview-led-to-63-billion-crypto-heist) by [BleepingComputer](https://x.com/BleepinComputer/status/2117709918148931700).
> TraderTraitor approached a Binance engineer through a real job platform in September and got malware installed during a fake interview, which opened the path to wallet infrastructure. Security Alliance profiles the group's playbook.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://radar.securityalliance.org/tradertraitor-vs-contagious-interview-a-look-at-binances-initial-incident-report">Security Alliance: TraderTraitor vs Contagious Interview</a> (AndrewMohawk⁽ⁿᵘˡˡ⁾)</details>

- [APT Flaw Lets a MitM Swap Verified Packages for Root RCE](https://thehackernews.com/2026/11/debian-and-ubuntu-apt-flaw-lets-mitm.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2118043291857916123).
> CVE-2026-109518 sits in APT's resumed HTTP downloads, which can merge two different downloads after verification. Retries are on by default from Debian 12 and Ubuntu 22.04, and Max Justicz found it in two hours of AI-assisted review.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://x.com/esizkur/status/2118396749547294786">I used an AI for two hours and found a zero-day that would let a nation-state hack any server running stock Ubuntu</a> (rpw)</details>

- [APT29 Watering Holes Serve N-Day Exploits to Phones](https://www.sekoia.com/blog/poisoned-source-apt29-watering-holes-targets-mobile-devices-with-n-day-exploits) by [Florian Roth](https://x.com/cyb3rops/status/2118095927177257307).
> Sekoia tracks a campaign that hijacked a web analytics script on legitimate sites to push n-day exploits to iOS and Android visitors.
  >
  > <details class="story-more"><summary>+2 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/hackers-use-n-day-exploits-in-zero-click-attacks-on-ios-android-devices">Hackers use n-day exploits in zero-click attacks on iOS, Android devices</a> (BleepingComputer)<br><a href="https://thehackernews.com/2026/11/apt29-linked-hackers-hijack-web.html">APT29-Linked Hackers Hijack Web Analytics Script to Deliver iOS and Android Exploits</a> (Nicolas Krassas)</details>

- [Runaway ARTEX Agent Breached WorkOS After Escaping Its Sandbox](https://www.bleepingcomputer.com/news/security/runaway-ai-hacking-agent-behind-workos-breach-after-escaping-sandbox) by [BleepingComputer](https://x.com/BleepinComputer/status/2118832715097076160).
> WorkOS first blamed an attacker running the ARTEX framework. A researcher then came forward and said the agent escaped its test environment and hit WorkOS by accident.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/workos-says-attacker-used-artex-ai-to-breach-internal-sales-app">WorkOS says attacker used ARTEX AI to breach internal sales app</a> (BleepingComputer)</details>

- [Unauthenticated RCE in React Server Components](https://github.com/react/react/security/advisories/GHSA-xqc2-xf4c-x3h3) by [Vincent Yiu](https://x.com/vysecurity/status/2119477546979086385).
> A crafted RSC Flight payload carrying typed arrays reaches code execution in react-server-dom-webpack, turbopack and parcel. Upgrade to 19.0.9, 19.1.10, 19.2.9 or 19.3.1, or Next.js 16.4.1.


<details markdown="1">
<summary>More this week (24)</summary>

- [Critical Langflow Flaws Could Let Unauthenticated Attackers Run Code on Servers](https://thehackernews.com/2026/11/critical-langflow-flaws-could-let.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2117250287274717216).
- [cPGuard Update Channel Compromised to Push a Backdoor](https://opsshield.com/notice/cpguard-update-channel-compromise.html). <details class="story-more"><summary>+1 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/hackers-hijack-cpguard-autoupdate-to-deploy-backdoor-steal-data">Hackers hijack cPGuard autoupdate to deploy backdoor, steal data</a> (BleepingComputer)</details>
- [Dreadnode Is Joining CrowdStrike](https://www.dreadnode.io/research/dreadnode-is-joining-crowdstrike) by [dreadnode](https://x.com/dreadnode/status/2117602707280433475).
- [DreamHost confirms data breach exposed FTP logins and webmail sessions](https://www.bleepingcomputer.com/news/security/dreamhost-confirms-data-breach-exposed-ftp-logins-and-webmail-sessions) by [BleepingComputer](https://x.com/BleepinComputer/status/2118057250015109177).
- [NIKKE PC game launcher hacked to spread remote access, data-stealing malware](https://www.bleepingcomputer.com/news/security/nikke-pc-game-launcher-hacked-to-spread-remote-access-data-stealing-malware) by [BleepingComputer](https://x.com/BleepinComputer/status/2118025248251547670). <details class="story-more"><summary>+1 more on this story</summary><a href="https://cyberinsider.com/nikke-pc-launcher-malware-remote-access-tool">NIKKE PC launcher delivered malware that let hackers control players’ computers</a> (Nicolas Krassas)</details>
- [SonicWall warns of unpatched flaws in end-of-life GMS software](https://www.bleepingcomputer.com/news/security/sonicwall-warns-of-unpatched-flaws-in-end-of-life-gms-software) by [BleepingComputer](https://x.com/BleepinComputer/status/2117990940375707779).
- [US charges two Canadians accused of hacking US universities](https://www.bleepingcomputer.com/news/security/us-charges-two-canadians-accused-of-hacking-us-universities) by [BleepingComputer](https://x.com/BleepinComputer/status/2117968502518665314).
- [Police seizes over 100 servers in investment scam crackdown](https://www.bleepingcomputer.com/news/security/police-seizes-over-100-servers-in-investment-scam-crackdown) by [BleepingComputer](https://x.com/BleepinComputer/status/2117611285135118773).
- [CVE-2026-58868: Critical Android Bug Could Let Attackers Run Remote Code](https://securityaffairs.com/202414/mobile-2/cve-2026-58868-critical-android-bug-could-let-attackers-run-remote-code.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2117967017445876196).
- [Rails Fixes Active Storage Arbitrary File Read and Write](https://rubyonrails.org/2026/11/4/Rails-8.0.5.2-and-8.1.4.1-have-been-released) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2117968713597038745). <details class="story-more"><summary>+1 more on this story</summary><a href="https://github.com/rails/rails/security/advisories/GHSA-f3w6-w445-fwh9">Rails Advisory: Active Storage ImageMagick MSL Coder Allows Arbitrary File Write</a> (Giuseppe &#96;N3mes1s&#96;)</details>
- [Krebs: Residential Proxies Running on White House Devices](https://krebsonsecurity.com/2026/11/want-to-rent-an-internet-address-at-the-white-house). <details class="story-more"><summary>+1 more on this story</summary><a href="https://layer3intel.com/blog/residential-proxies-white-house-network">Layer3: Residential Proxies Detected on White House Network</a> (MalwareHunterTeam)</details>
- [GitBook Discloses a Targeted Attack Using AI Agents](https://www.gitbook.com/status/security-incident-2026-11-03) by [SwitHak ()](https://x.com/SwitHak/status/2117698950694420656).
- [Synacktiv: SQL Injection and Stored XSS in GLPI 11](https://www.synacktiv.com/en/advisories/sql-injection-and-stored-xss-vulnerabilities-in-glpi-11) by [Synacktiv](https://x.com/Synacktiv/status/2117900493015978193).
- [Kaspersky: CyberStrikeAI Used in Real Intrusions](https://securelist.com/cyberstrikeai-attacks/121715) by [Florian Roth](https://x.com/cyb3rops/status/2118015000807972912).
- [SonicWall warns of new SSL-VPN MFA bypass flaw exploited in attacks](https://www.bleepingcomputer.com/news/security/sonicwall-warns-of-new-ssl-vpn-mfa-bypass-flaw-exploited-in-attacks) by [BleepingComputer](https://x.com/BleepinComputer/status/2118856246228820028). <details class="story-more"><summary>+1 more on this story</summary><a href="https://www.securityweek.com/sonicwall-patches-exploited-sonicos-bug-that-weakens-vpn-logins">SonicWall Patches Exploited SonicOS Vulnerability That Weakens VPN Logins</a> (Nicolas Krassas)</details>
- [Fake security tools on GitHub push backdoors and infostealers](https://www.bleepingcomputer.com/news/security/fake-security-tools-on-github-push-backdoors-and-infostealers) by [BleepingComputer](https://x.com/BleepinComputer/status/2118777215710068912).
- [QNAP says hackers breaching NAS devices in Plex2Shell attacks](https://www.bleepingcomputer.com/news/security/qnap-says-hackers-breaching-nas-devices-in-plex2shell-attacks) by [BleepingComputer](https://x.com/BleepinComputer/status/2118751439820300679).
- [Chainalysis says breach exposed credentials for all customers](https://www.bleepingcomputer.com/news/security/chainalysis-says-breach-exposed-credentials-for-all-customers) by [BleepingComputer](https://x.com/BleepinComputer/status/2118709343151366164).
- [D-Link warns of multiple zero-days in DGS-3130 Series switches](https://www.bleepingcomputer.com/news/security/d-link-warns-of-multiple-zero-days-in-dgs-3130-series-switches) by [BleepingComputer](https://x.com/BleepinComputer/status/2118684227147350081).
- [Hackers backdoor Linux servers using trojanized CWP web server](https://www.bleepingcomputer.com/news/security/hackers-backdoor-linux-servers-using-trojanized-cwp-web-server) by [BleepingComputer](https://x.com/BleepinComputer/status/2118378984064860614).
- [DigiCert data breach exposes customer information, identity documents](https://www.bleepingcomputer.com/news/security/digicert-data-breach-exposes-customer-information-identity-documents) by [BleepingComputer](https://x.com/BleepinComputer/status/2118376075277340952). <details class="story-more"><summary>+1 more on this story</summary><a href="https://www.theregister.com/security/2026/11/06/digicert-admits-16-month-security-lapse-exposed-customer-information/5308097">DigiCert admits 16-month security lapse exposed customer information</a> (Nicolas Krassas)</details>
- [Suspected Chinese-Nexus Exploitation of vCenter CVE-2026-59310](https://medium.com/@quirso_de/global-exploitation-of-cve-2026-59310-by-suspected-chinese-nexus-apt-related-cve-2026-59309-443a79e1466d) by [Leo Tsaousis](https://x.com/LAripping/status/2118356736071397808).
- [Microsoft Paint RCE Fix Is Out, but Windows Update Won't Deliver It](https://thehackernews.com/2026/11/microsoft-paint-rce-fix-now-available.html) by [Sean Metcalf](https://x.com/PyroTek3/status/2118755760582861147).
- [Hackers pull off $133 million French bank heist via service provider](https://www.bleepingcomputer.com/news/security/hackers-pull-off-133-million-french-bank-heist-via-service-provider) by [BleepingComputer](https://x.com/BleepinComputer/status/2119089297642918202).

</details>


## Techniques and Write-ups

- [Barracuda ESG Pre-Auth Remote Root RCE](https://labs.watchtowr.com/barracuda-networks-is-your-new-best-friend-barracuda-email-security-gateway-pre-auth-remote-root-rce-cve-2026-116606-cve-2026-111560) by Sina Kheirkhah (@SinSinology).
> watchTowr chains CVE-2026-116606 and CVE-2026-111560 into unauthenticated root on the email gateway that UNC4841 hit as a zero-day in 2023.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/barracuda-warns-of-critical-flaws-allowing-root-access-to-devices">Barracuda warns of critical flaws allowing root access to devices</a> (BleepingComputer)</details>

- [Abusing Unauthenticated iSCSI Target Server in AD](https://specterops.io/blog/2026/11/04/unauthenticated-iscsi-target-server) by Garrett Foster.
> Without CHAP, guessing the right initiator IQN lets you mount a shared virtual disk and read it past NTFS permissions. Garrett Foster points to SPNs shared with Hyper-V, failover clusters and DFS as places to look.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://x.com/badsectorlabs/status/2118085207450415168">ludus.domain in the screenshot means you know it&#x27;s going to be a good post</a> (Bad Sector Labs)</details>

- [Dangerous Device: Exploiting CVE-2026-31695 in the Linux Kernel](https://ptswarm.com/blog/dangerous-device-exploiting-cve-2026-31695-in-the-linux-kernel-via-struct-device) by [Arseniy Sharoglazov](https://x.com/_mohemiv/status/2117226107531608507).
> Alexander Popov found, fixed and exploited a race condition born from a logic bug in network device management, using struct device as the attack surface.

- [Keycloak SAML Login Hijack to Realm Admin](https://abraxaslabs.tech/research/keycloak-saml-redirect-param-split) by [Vincent Yiu](https://x.com/vysecurity/status/2117719864324608464).
> Placing an encoded SAMLResponse ahead of the signed one hijacks another user's broker login with no Keycloak account, given a redirect-signing SAML broker. A second bug lets a help-desk admin grant itself manage-realm through a pre-built composite role.

- [Pre-Auth RCE in Opengear Console Servers](https://www.armadin.com/blog-posts/compromising-the-out-of-band-management-plane-pre-auth-rce-via-heap-overflow-in-opengear-console-servers) by [werdhaihai](https://x.com/werdhaihai/status/2117793805533581746).
> A heap overflow in the HTTP header parser plus a stdin FILE structure hijack gives unauthenticated code execution on the box that manages everything else out of band.

- [Two Firecracker MicroVM Escapes in One Week](https://www.coinspect.com/blog/firecracker-escape) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2118109294558068818).
> Coinspect breaks isolation when snapshots restore with the File memory backend and balloon or virtio-mem devices (CVE-2026-122192, fixed in 1.16.2). pwn.ai separately reached root on the host by hijacking a vCPU thread from inside the guest.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://pwn.ai/blog/firecracker-escape">Firecracker VM Escape: PwnEscape Part 2.</a> (Nicolas Krassas)</details>

- [Ghost in the Script: Ghostscript Memory Corruption to RCE](https://www.liondawnlabs.com/blog/ghost-in-the-script) by [SinSinology](https://x.com/SinSinology/status/2118051663894184030).
> Image upload and document conversion features hand attacker files to Ghostscript, and Liondawn Labs turns this bug into RCE across several applications. The post closes with defensive guidance.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://x.com/SinSinology/status/2118051650510188738">Author Thread on the Liondawn Labs Ghostscript Exploit</a> (SinSinology)</details>

- [WordPress Core Pre-Auth RCE During Core Updates](https://xint.io/blog/wordpress-core-update-attack) by [Dave Aitel](https://x.com/daveaitel/status/2117778539030421864).
> A race between update steps exposes setup-config.php long enough to reach code execution. Xint warns that the first update to the fixed 7.1.4 release is itself an attack window, and CISA has added CVE-2026-119977 to KEV.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://www.bleepingcomputer.com/news/security/cisa-flags-wordpress-rce-flaw-as-actively-exploited-in-attacks">CISA flags WordPress RCE flaw as actively exploited in attacks</a> (BleepingComputer)</details>

- [Graph API Change Notifications for Persistence and Exfil](https://www.netspi.com/blog/technical-blog/cloud-pentesting/leveraging-microsoft-graph-api-change-notifications-for-data-exfiltration) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2118443140109701427).
> NetSPI's Thomas Elling turns Microsoft Graph change notification subscriptions into a persistence and data exfiltration channel for cloud engagements.

- [Hacking Two Automakers Through ForgeRock](https://samcurry.net/forgerock) by [Sam Curry](https://x.com/samwcyo/status/2119030320171266117).
> Shubham Shah and Sam Curry chained a ForgeRock path confusion into RCE on the login servers, then minted sessions to locate, unlock and start customers' cars. Shubs also published a companion post on unlocking one brand's cars in most of the world.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://shubs.io/unlocking-any-car-from-x-brand-in-most-of-the-world">unlocking any car from X brand in most of the world</a> (Nicolas Krassas)</details>


<details markdown="1">
<summary>More this week (34)</summary>

- [Jailbreaking a Renault Navigation Unit to Change the Clock](https://blog.nns.ee/2026/11/02/renault-hack).
- [Detecting Frida's Stalker Instrumentation](https://www.romainthomas.fr/post/26-10-frida-stalker-detection).
- [Project Zero: Heap OOB Read and Write in the Brotli Decoder](https://project-zero.issues.chromium.org/issues/565308158) by [Project Zero Bugs](https://x.com/ProjectZeroBugs/status/2117225924492181996).
- [Blacktop's OffensiveCON Japan 2026 Slides](https://blacktop.github.io/presentations/offensivecon_tokyo_2026/HTML/index.html) by [Alex Plaskett](https://x.com/alexjplaskett/status/2117488561301991867).
- [A Primer on TETRA Authentication Flaws](https://www.midnightblue.nl/blog/tetra-authentication-flaws).
- [DLL Sideloading Chain Hidden in a Signed Binary's Certificate Table](https://github.com/NextronSystems/iocs/tree/master/reports/rrcfg_implant) by [Florian Roth](https://x.com/cyb3rops/status/2117302531818946874).
- [Thousands of Malicious Commands Hidden in Flowise Greeter Messages](https://era.security/blog/greeter-flowise-ai-infrastructure-attack).
- [Slides: 0clicks in an AI World (Stefan Esser and Bruce Dang)](https://github.com/pwnlambda/talks/blob/main/unprompted_0clicks.pdf) by [Stefan Esser](https://x.com/i0n1c/status/2117662187582062893).
- [Microsoft Defender for Identity evasions in 2026 – Part I](https://cirosec.de/en/news/microsoft-defender-for-identity-evasions-in-2026-part-i) by [Panos Gkatziroulis](https://x.com/ipurple/status/2117685381319610399).
- [shedskin: PowerShell leaves its skin, Defender scans somebody else's](https://cornfield.sh/shedskin) by [Panos Gkatziroulis](https://x.com/ipurple/status/2116977211404419278).
- [Pixel 6 Binder UAF Exploit Chain, Part 4 (CVE-2023-20938)](https://eshard.com/blog/kernel-uaf-4-read) by [kmkz](https://x.com/kmkz_security/status/2117363448824709509).
- [CVE-2026-98432: Linux Kernel IPv4 TCP Use-After-Free Root Cause, Detection and Mitigation](https://pentestit.com/cve-2026-98432-linux-kernel-ipv4-tcp-use-after-free) by [Mayuresh 🇮🇳](https://x.com/pentestit/status/2117080414938640580). <details class="story-more"><summary>+1 more on this story</summary><a href="https://x.com/solardiz/status/2118073551869911306">1/ CVE-2026-98432, the remote Linux TCP bug: I reproduced it after just a few hours with a local LLM</a> (Solar Designer)</details>
- [Pivoting From a Single IOC Into an Ivanti Zero-Day Operation](https://etugen.io/blog/ivanti-zero-day-operation) by [thaddeus e. grugq](https://x.com/thegrugq/status/2117927406749274371). <details class="story-more"><summary>+1 more on this story</summary><a href="https://www.virustotal.com/gui/file/17277527c95289a7ce8d9f69b07829edfd2e099bd664d79e54d3e9cad2d8307b">here&#x27;s the privilege escalation exploit (CVE-2026-111357) from the latest Ivanti itw exploit chain..</a> (Rich Warren)</details>
- [The Quiet Phase: Detecting Active Directory Group Enumeration](https://trustedsec.com/blog/the-quiet-phase-active-directory-group-enumeration) by [Dave Kennedy](https://x.com/HackingDave/status/2117711146988007768).
- [Free Workshop: Harness Engineering for Vulnerability Research](https://grahamhelton.github.io/harness-engineering-workshop-book/introduction.html) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2118030681649668481).
- [Browser cache smuggling: tried and tested on Windows, viable on macOS?](https://phorion.io/blog/browser-cache-smuggling-macos) by [Alfie Champion](https://x.com/ajpc500/status/2117662969702068721).
- [Inside the AI Operator: What an AI Attacker Writes Down After It Fails](https://profero.io/blog/inside-the-ai-operator) by [Florian Roth](https://x.com/cyb3rops/status/2118015113743495530).
- [Hacking on Autopilot: Inside ARTEX Cybercrime Campaigns](https://research.checkpoint.com/2026/hacking-on-autopilot-inside-artex-cybercrime-campaigns) by [hasherezade](https://x.com/hasherezade/status/2118396356368994454). <details class="story-more"><summary>+2 more on this story</summary><a href="https://cyberscoop.com/china-vapor-panda-agentic-ai-artex-campaign-crowdstrike">CrowdStrike: China-Backed Group Uses ARTEX for Agentic Intrusions</a> (Florian Roth)<br><a href="https://securityaffairs.com/202607/ai/inside-artex-ai-hacking-tools-exposed-servers-and-south-korean-bank-breaches.html">Inside ARTEX: AI Hacking Tools, Exposed Servers and South Korean Bank Breaches</a> (Nicolas Krassas)</details>
- [ChatGPT Lockdown Mode Bypass for Phishing and Silent Exfiltration](https://research.checkpoint.com/2026/chatgpt-lockdown-mode-bypass-phishing-malware-delivery-and-silent-data-exfiltration) by [hasherezade](https://x.com/hasherezade/status/2118348484172521815).
- [Genetec Security Center Zero-Day (CVE-2026-65422)](https://xen-i0.github.io/post-genetec-cve-2026-65422.html) by [kmkz](https://x.com/kmkz_security/status/2118073884465672655).
- [NOpal: Microsoft Project Opal Features in Red Team Tradecraft](https://16cdd728-52b5-4665-b161-30113ba1b7e4.usrfiles.com/ugd/16cdd7_5a66da4cbf9d41b08f6b4e51adde3ec1.pdf) by [Nikhil Mittal](https://x.com/nikhil_mitt/status/2118334357245222974).
- [Chamilo LMS: It's Raining 0days (Quarkslab)](https://blog.quarkslab.com/chamilo-lms-its-raining-0days-hallelujah-its-raining-0days.html) by [Swissky](https://x.com/pentest_swissky/status/2117981944231206997).
- [Slides: 100 Exploits Later (Groß and Lippautz, OffensiveCon Tokyo)](https://saelo.github.io/presentations/offensivecon_26_100_exploits_later.pdf) by [Sean Heelan](https://x.com/seanhn/status/2118667700910366996).
- [Pwn2Own Berlin 2026: LMStudio RCE Chain Writeup](https://blog.drstra.in/posts/a-missed-from-pwn2own-berlin-2026-and-full-disclosure-on-lmstudio-rce) by [ϻг_ϻε](https://x.com/steventseeley/status/2118301209069306103).
- [Principal Problems: App Registrations, Service Principals, and the Hidden Risk of Multi-Tenant Apps](https://specterops.io/blog/2026/11/06/app-registrations-vs-service-principals) by Lee Robinson.
- [DEF CON 34 Videos and Slides Are Up](https://media.defcon.org/DEF%20CON%2034/DEF%20CON%2034%20video%20and%20slides).
- [Seven Apache OFBiz Vulns Including Three Unauthenticated RCEs](https://cryptocat.me/blog/research/projects) by [Nicolas Krassas](https://x.com/Dinosn/status/2118662927704277144).
- [Token Theft in Microsoft Entra ID, Part 4: OAuth 2.0 Standard Gaps](https://insinuator.net/2026/11/token-theft-in-microsoft-entra-id-part-4-of-4-oauth-2.0-standard-gaps) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2118097793478951359).
- [Project Zero: Samsung HEIF Parser Arbitrary Read](https://project-zero.issues.chromium.org/issues/537266509) by [Project Zero Bugs](https://x.com/ProjectZeroBugs/status/2118287507834175999). <details class="story-more"><summary>+1 more on this story</summary><a href="https://project-zero.issues.chromium.org/issues/542139339">Samsung Heap Buffer Overflow (OOB Write) in IMA-ADPCM WAV Decoding (WAVSource::read)</a> (Project Zero Bugs)</details>
- [Code Execution on Meta Ray-Ban Smart Glasses](https://p0pcycle.com/2026/11/06/hacking-the-meta-ray-ban-smartglasses) by [SinSinology](https://x.com/SinSinology/status/2118779341924364774).
- [Samsung CVE-2026-21155 (SVE-2026-3546) Writeup](https://github.com/UnsignedChad/CVE-2026-21155-SVE-2026-3546) by [kmkz](https://x.com/kmkz_security/status/2119199399360291018). <details class="story-more"><summary>+1 more on this story</summary><a href="https://github.com/Gabriel2392/SVE-2026-3546">For Exynos enthusiasts: You can now fuse your own secure boot keys in your device, allowing to permanently run...</a> (rpw)</details>
- [Operation Snowball: Inside an Autonomous AI Intrusion Campaign](https://malbearlabs.com/posts/operation-snowball-inside-an-autonomous-ai-intrusion-campaign) by [Sudheer Varma](https://x.com/0xpwnisher/status/2119514695698690226).
- [AI Coding Assistants Are Shipping Secrets in settings.local.json](https://reykur.io/blog/ai-coding-assistant-shipping-secrets) by [Nicolas Krassas](https://x.com/Dinosn/status/2119340443615863255). <details class="story-more"><summary>+1 more on this story</summary><a href="https://thehackernews.com/2026/11/claude-codes-dont-ask-again-file.html">Claude Code&#x27;s “Don&#x27;t Ask Again” File Exposes Passwords and Keys in 1,122 Public Copies on GitHub</a> (Nicolas Krassas)</details>
- [Stolen App Credentials, Real Access: An Actor Is Signing Into Entra ID and Azure DevOps as Your Workloads](https://www.todyl.com/blog/stolen-app-credentials-real-access-an-actor-is-signing-into-entra-id-and-azure-devops-as-your-workloads) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2119571875944939739).

</details>


## Tools and Exploits

- [Impacket Adds MS-RPRN HTTP Auth Coercion (PR #2361)](https://github.com/fortra/impacket/pull/2361) by [Max](https://x.com/maxime_tz/status/2118071733710094789).
> The PR adds MS-RPRN opnum 88 and an example script to coerce HTTP authentication from Windows hosts for relay. It was inspired by sudonoodle's IPP coercion BOF, which forces machine-account HTTP auth through the WSD port monitor.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://github.com/sudonoodle/BOF-coerce-ipp">BOF-coerce-ipp: Coerce Machine HTTP Auth Through IPP</a> (Panos Gkatziroulis)</details>

- [keyeroo: NTLM Relay to LDAP With Signing Enforced](https://github.com/grayhatkiller/keyeroo) by [Panos Gkatziroulis](https://x.com/ipurple/status/2119053010592788489).
> The October update killed Switcheroo's stacked-bind trick, and keyeroo still relays a coerced victim to LDAP on a fully patched DC that requires signing. RelayInformer gained a check that tells you whether a DC is exposed without relaying anything.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://github.com/zyn3rgy/RelayInformer/tree/feature/ldap-signing-bypass">RelayInformer Adds an LDAP Signing Bypass Check</a> (stuk0v)</details>

- [Brute Ratel 2.7 Released](https://x.com/NinjaParanoid/status/2117201122142425306) by Chetan Nayak (Brute Ratel C4 Author).
> Adds redesigned CET and CFG compatible stack spoofing, a new C-VM interpreter, bind TCP badgers and EDR compatibility updates.

- [tprtdll.dll as an ntdll Stand-In to Dodge EDR Hooks](https://github.com/ivancabrera02/tprtdll-Injection) by [Panos Gkatziroulis](https://x.com/ipurple/status/2117250385509241153).
> tprtdll.dll exports equivalents of some ntdll functions at separate addresses, so calls through it skip hooks placed only on ntdll.

- [defender_observer: Record and Replay Defender ETW Telemetry](https://github.com/dobin/defender_observer) by [Panos Gkatziroulis](https://x.com/ipurple/status/2117968102717554834).
> dobin's .NET tool captures, records, replays and analyzes Defender AV and EDR ETW events in real time. A companion post walks through the Antimalware Engine event set.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://blog.deeb.ch/posts/defender-am-events">Microsoft-Antimalware-Engine ETW events</a> (Panos Gkatziroulis)</details>

- [OOBscan: Find Unpatched BMC and Out-of-Band Management Bugs](https://github.com/runZeroInc/oobscan) by [Lee Chagolla-Christensen](https://x.com/tifkin_/status/2118076605167997410).
> runZero's Lights Out research covers OpenBMC, iDRAC, iLO, XCC2, Supermicro and others, and many of the issues still have no patch. OOBscan now detects all of them.

- [WebClientRelayUp: No-Fix LPE on Domain-Joined Workstations](https://github.com/Hack0ura/WebClientRelayUp) by [Steven Lowson](https://x.com/StevoLowson/status/2118941494929158506).
> Raphaël Huon of Advens builds on DavRelayUp for a local privilege escalation that works on default Windows 10 and 11 domain-joined workstations.

- [adshell-rs: Interactive AD Attack Shell Over LDAP or ADWS](https://github.com/g0h4n/adshell-rs) by [n00py](https://x.com/n00py1/status/2118940089917329882).
> Quentin Texier's Rust shell runs RBCD, shadow credentials, DCSync, password resets and object reads over LDAP(S) or the ADWS SOAP port every DC exposes on 9389. RustHound-CE 2.5.40 now collects over ADWS too.
  >
  > <details class="story-more"><summary>+1 more on this story</summary><a href="https://github.com/g0h4n/RustHound-CE/releases/tag/v2.5.40">RustHound-CE 2.5.40 Adds ADWS Collection</a> (n00py)</details>

- [dawgyg Open-Sources 100+ Apple PoCs and Fuzzers](https://github.com/dawgyg/AppleResearch) by [thaddeus e. grugq](https://x.com/thegrugq/status/2119031573484085413).
> Winding down in the Apple Security Bounty program, dawgyg published PoCs for real CVEs alongside the fuzzers that found them.

- [SecureDeskDown: Logitech G HUB Driver to SYSTEM](https://github.com/dennywise/SecureDeskDown) by [Vincent Yiu](https://x.com/vysecurity/status/2118999245592432889).
> Any user can open the G HUB virtual HID driver and inject keystrokes as SYSTEM, which the author turns into a UAC bypass. Logitech rated it informative, so there is no fix.


<details markdown="1">
<summary>More this week (9)</summary>

- [Suzaku Cloud Log Hunting: Vulnpocalypse Release](https://github.com/Yamato-Security/suzaku) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2116938028132511999).
- [Mac Monitor 3.0 Adds a CLI and 13 New Features](https://github.com/Brandon7CC/mac-monitor/releases/tag/v3.0.0) by [L0Psec](https://x.com/L0Psec/status/2117298773713977466).
- [wifit3: A Successor to Wifite](https://github.com/derv82/wifit3) by [Vincent Yiu](https://x.com/vysecurity/status/2117512275171139587).
- [HyperDbg v0.25 Released](https://github.com/HyperDbg/HyperDbg/releases/tag/v0.25) by [Björn Ruytenberg](https://x.com/0Xiphorus/status/2117283954235527334).
- [HyperLoader: Hypervisor-Isolated Shellcode Execution](https://github.com/S12cybersecurity/HyperLoader) by [Panos Gkatziroulis](https://x.com/ipurple/status/2118257257779781990). <details class="story-more"><summary>+1 more on this story</summary><a href="https://medium.com/@s12deff/executing-shellcode-in-an-isolated-vcpu-5ac0cc4baaac">Executing Shellcode in an Isolated vCPU</a> (Peter Gabaldon)</details>
- [LogonStealer: Credential Provider Abuse to Steal Logon Passwords](https://github.com/S12cybersecurity/LogonStealer) by [Panos Gkatziroulis](https://x.com/ipurple/status/2118241948028809586).
- [RAMP: Cracked Hash Analysis and Rule Generation](https://github.com/netmux/ramp) by [Max](https://x.com/maxime_tz/status/2118286550232346992).
- [Sysinternals Brings Autoruns to Linux and Process Explorer to macOS](https://techcommunity.microsoft.com/blog/sysinternals-blog/autoruns-for-linux-procexp-for-macos-macos-tools-linux-tools-proexp-procmon-psto/4570783) by [DebugPrivilege](https://x.com/DebugPrivilege/status/2118607109277331739).
- [VerifiedIDA: Evidence-Backed LLM Reverse Engineering in IDA](https://github.com/SentineLabs/verified-ida/tree/main) by [Max](https://x.com/maxime_tz/status/2118593697281388706). <details class="story-more"><summary>+1 more on this story</summary><a href="https://www.sentinelone.com/labs/verifiedida-making-llm-driven-reverse-engineering-inspectable-continuable-and-reusable">SentinelLABS: Making LLM-Driven Reversing Inspectable</a> (AndrewMohawk⁽ⁿᵘˡˡ⁾)</details>

</details>



