---
title: "Crow's Nest - 2026-10-27"
date: 2026-10-27T00:00:00+00:00
draft: false
tags: ["roundup"]
---

A roundup of 255 items curated from across the security community.

> ### [PHP2Shell: Critical Pre-Auth RCE in PHP (CVE-2026-109618)](https://calif.io/php2shell)
>
> Calif.io discovered two critical PHP vulnerabilities enabling unauthenticated remote code execution on stock configurations. Trail of Bits confirmed a production-grade exploit hitting WordPress, MediaWiki, phpBB, and Laravel across both ARM64 and x86-64. Unit 42 confirmed active exploitation in the wild. NSA, FBI, and CISA all recommended taking affected systems offline.
>
> [Kuba Gretzky](https://x.com/mrgretzky/status/2112966013973123332) · [Read more](https://calif.io/php2shell)

## News

- [eMudhra Intermediate CA Compromise](https://emudhra.we-have-a-problem.com/) by [Swissky](https://x.com/pentest_swissky/status/2112931869679665532).
> Private keys for eight TLS certificates were trivially small integers (4, 56, 66, 115, 155, 156, 230, 237). An intermediate CA compromise affecting the web PKI trust chain.

- [OVHcloud CLI Compromised in Supply Chain Attack](https://github.com/ovh/ovhcloud-cli) by [Rémi GASCOU (Podalirius)](https://x.com/podalirius_/status/2112287651281682499).
> Versions v0.11.0 through v0.15.0 of the OVHcloud CLI were compromised by a hacker. Detected and blocked within 90 minutes. No other repos affected.

- [One Hacker Used AI Agents to Breach 100+ Websites for $5,000](https://www.reuters.com/legal/government/how-one-hacker-used-ai-agents-few-thousand-dollars-break-into-scores-sites-2026-10-19) by [Caleb Gross](https://x.com/noperator/status/2112620010514329699).
> Reuters reports a single attacker unleashed AI agents on 1,200+ websites, compromising over 100 for roughly $50 per hack in token costs. IR firms are saturated and turning away work.

- [Storm-0940 Used AI Framework ARTEX for ConnectWise Attack](https://msft.it/6018aakEE) by [Florian Roth](https://x.com/cyb3rops/status/2113048946796822830).
> Microsoft attributes the ConnectWise supply chain compromise to Chinese state-aligned Storm-0940. The group used the agentic AI pentesting framework ARTEX to automate attacks across hundreds of organizations.

- [GitLab CVSS 10.0 Flaw Affects 12 Years of Releases](https://thehackernews.com/2026/10/critical-gitlab-flaw-cvss-100-could.html) by [Vincent Yiu](https://x.com/vysecurity/status/2113173192185643108).
> CVE-2026-110264 allows unauthenticated remote code execution on self-managed GitLab servers. The regex compiler flaw spans every release in the past 12 years.

- [Pentagon's New TSO: A Shadow Agency for Offensive Hacking](https://www.politico.com/news/2026/10/22/technology-support-office-dod-tech-spyware-sabotage-01100327) by [Stefan Esser](https://x.com/i0n1c/status/2113589013881725000).
> Politico reveals TSO, a new DoD agency with significant budget and appetite for offensive hacking tools, spyware, and sabotage capabilities.

- [High Severity BIND 9 DNS Vulnerability (CVE-2026-94300)](https://kb.isc.org/docs/cve-2026-94300) by [Phil Venables](https://x.com/philvenables/status/2113615762170753075).
> Multiple vulnerabilities in BIND 9, the most widely deployed DNS software on the internet, including remote DoS and memory corruption.

- [PHP Warns of Another Unpatched RCE Two Days After PHP2Shell](https://thehackernews.com/2026/10/urgent-php-warns-of-another-unpatched.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2113618341399081389).
> A second critical PHP RCE dropped just two days after the emergency PHP2Shell patches, compounding the patching emergency for PHP operators.

- [Operation IXIM: 3.8 Million Popcorn Time Clients Nearly Botnetted](https://labs.eye.security/operation-ixim-preventing-a-botnet-of-millions-of-popcorn-time-users).
> Eye Security found a Popcorn Time updater connecting to an abandoned domain. Anyone who registered it could push arbitrary executables to 3.8 million clients with elevated privileges.


<details markdown="1">
<summary>More this week (60)</summary>

- [Drupal patches critical RCE flaws, warns exploits may emerge soon](https://www.bleepingcomputer.com/news/security/drupal-patches-critical-rce-flaws-warns-exploits-may-emerge-soon) by [BleepingComputer](https://x.com/BleepinComputer/status/2111465561309827080).
- [BREAKING: AI coding agent OpenCode was breached in what it calls a "large scale distillation attack"](https://x.com/CurtBraz/status/2111609036500021672) by 𝐂𝐮𝐫𝐭𝐢𝐬 𝐁𝐫𝐚𝐳𝐳𝐞𝐥𝐥.
- [Hackers exploit SiteGuard WAF flaw to run commands as SYSTEM, root](https://www.bleepingcomputer.com/news/security/hackers-exploit-siteguard-waf-flaw-to-run-commands-as-system-root) by [BleepingComputer](https://x.com/BleepinComputer/status/2111825678198813158).
- [The EY/Goldman Sachs Breach Breakdown: Support tickets and IT attachments are among enterprise security's biggest...](https://ponderwall.com/index.php/2026/10/18/ey-data-breach-wall-street-goldman-sachs) by [Nicolas Krassas](https://x.com/Dinosn/status/2111933083511353565).
- [16-Year-Old Broadcom Wi-Fi Bug Lets Attackers Take Over Routers Without a Password](https://securityaffairs.com/201268/iot/16-year-old-broadcom-wi-fi-bug-lets-attackers-take-over-routers-without-a-password.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2112007039698584046).
- [Linux KVM guest-host escape rated critical, may represent a new way to attack penguin-powered networking](https://www.theregister.com/virtualization/2026/10/19/linux-kvm-guest-host-escape-rated-critical-may-represent-a-new-way-to-attack-penguin-powered-networking/5303744) by [Nicolas Krassas](https://x.com/Dinosn/status/2112007081599381831).
- [Microsoft fixes exploited Mark of the Web bypass vulnerability](https://www.helpnetsecurity.com/2026/10/14/microsoft-patch-tuesday-cve-2026-96951-motw-bypass) by [Nicolas Krassas](https://x.com/Dinosn/status/2112007182912753743).
- [OpenCode Console Breach May Have Exposed OpenAI, Anthropic, and Google API Keys](https://thehackernews.com/2026/10/opencode-console-breach-may-have.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2112091059014840614).
- [Unpatched Broadcom Wi-Fi Flaw Lets Attackers in Range Run Code as Root on Routers](https://thehackernews.com/2026/10/unpatched-broadcom-wi-fi-flaw-lets.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2112091139385729044).
- [One Compromised Login Exposed Millions of California Students’ Records](https://www.securityweek.com/one-compromised-login-exposed-millions-of-california-students-records) by [Nicolas Krassas](https://x.com/Dinosn/status/2112166276965838859).
- [Fake Web3 Accelerator Uses npm Packages to Spread Malware and Hijack AI Agent Traffic](https://thehackernews.com/2026/10/fake-web3-accelerator-uses-npm-packages.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2112166337132818533).
- [New: Chinese hackers broke into Staples](https://www.404media.co/how-a-massive-chinese-crime-ring-hacked-staples-to-steal-millions) by [thaddeus e. grugq](https://x.com/thegrugq/status/2112343273096577325).
- [Presentation slides (all 107 of them)](https://quentinkaiser.be/assets/qkaiser-broadcom-wps-hexacon-2026.pdf) by [Max](https://x.com/maxime_tz/status/2112463307021893907).
- [Wild story from briankrebs: 1) Dubrovsky, the arrested ransomware negotiator, knew ShinyHunters stole FBI data but...](https://krebsonsecurity.com/2026/10/feds-suspect-ransom-negotiator-ran-shinyhunters-extortion-site) by [Kim Zetter](https://x.com/KimZetter/status/2112233413327343886).
- [Nearly 20 million people may have had their health data exposed in the 2025 breach of Oracle Health’s legacy Cerner...](https://www.hipaajournal.com/oracle-health-data-breach) by [Black Hills Information Security](https://x.com/BHinfoSecurity/status/2112334283155116145).
- [‼ BREAKING: Go has issued an URGENT security update blocking 8 certificate authority keys over undisclosed security...](https://thehackernews.com/2026/10/go-issues-emergency-update-blocking.html) by [Simone Margaritelli](https://x.com/evilsocket/status/2112526708867826059).
- [Hacker gets 8 years for stealing $3.3 million from taxpayers](https://www.bleepingcomputer.com/news/security/hacker-gets-8-years-for-stealing-33-million-from-taxpayers) by [BleepingComputer](https://x.com/BleepinComputer/status/2112534153740582966).
- [DHS bans DeepSeek products across US federal civilian agencies](https://www.bleepingcomputer.com/news/security/dhs-bans-deepseek-products-across-us-federal-civilian-agencies) by [BleepingComputer](https://x.com/BleepinComputer/status/2112549237388960120).
- [Skarvel, a tool developed by twelvesec takes a single indicator of compromise, finds every public repository...](https://github.com/twelvesec/Skarvel) by [Panos Gkatziroulis](https://x.com/ipurple/status/2112574665009082854).
- [Zeabur shutting down after second security breach in two months](https://www.bleepingcomputer.com/news/security/zeabur-shutting-down-after-second-security-breach-in-two-months) by [BleepingComputer](https://x.com/BleepinComputer/status/2112628242309919010).
- [CISA: SafePay ransomware hit over 600 critical infrastructure orgs](https://www.bleepingcomputer.com/news/security/cisa-and-fbi-safepay-ransomware-has-hit-over-600-critical-infrastructure-organizations) by [BleepingComputer](https://x.com/BleepinComputer/status/2112825378486042868).
- [LiteLLM was compromised (Again)](https://x.com/N3mes1s/status/2112889709193998370) by Giuseppe `N3mes1s`.
- [LiteLLM, a Python package for connecting to AI model providers with 92M+ monthly downloads, has been compromised](https://x.com/kmkz_security/status/2112949922299252981) by kmkz.
- [LiteLLM compromised again. AISLE Found Compromised LiteLLM Package 3 Minutes After Release](https://aisle.com/blog/litellm-11070-on-pypi-shipped-a-credential-stealer) by [Nicolas Krassas](https://x.com/Dinosn/status/2112924440715505979).
- [Signal bug could keep your mic - and camera - on after hangup](https://www.theregister.com/security/2026/10/21/signal-bug-could-keep-your-mic-and-camera-on-after-hangup/5304528) by [Nicolas Krassas](https://x.com/Dinosn/status/2112959649116725568).
- [Socket: LiteLLM, a Python package for connecting to AI model providers with 92M+ monthly downloads, has been...](https://x.com/vxunderground/status/2112962053577068684) by vx-underground.
- [CISA: Hackers chain Plex flaws in Plex2Shell attacks to breach servers](https://www.bleepingcomputer.com/news/security/cisa-hackers-chain-plex-flaws-in-plex2shell-attacks-to-breach-servers) by [BleepingComputer](https://x.com/BleepinComputer/status/2112975948089856189).
- [Second Time this year LiteLLM get compromised](https://www.wiz.io/blog/litellm-compromised-steals-credentials) by [Thomas Roccia](https://x.com/fr0gger_/status/2113004514471256418).
- [Lazarus hackers use post-quantum cryptography for malware delivery](https://www.bleepingcomputer.com/news/security/lazarus-hackers-use-post-quantum-cryptography-for-malware-delivery) by [BleepingComputer](https://x.com/BleepinComputer/status/2113005418339344513).
- [Compromised eMudhra intermediate certificates](https://blog.talosintelligence.com/compromised-intermediate-certificates) by Cisco Talos.
- [Japan's Onamae Desktop Cloud hacked, up to 27,000 servers affected](https://www.bleepingcomputer.com/news/security/japans-onamae-desktop-cloud-hacked-up-to-27-000-servers-affected) by [BleepingComputer](https://x.com/BleepinComputer/status/2113023441162957297).
- [If anyone else has compromises to disclose, today's not a bad day to blend in to the background...](https://blog.railway.com/p/security-disclosure-wednesday-october-21st) by [Jon Oberheide](https://x.com/jonoberheide/status/2113040656100684161).
- [Turns out details leaked even sooner than previously believed. AWS saw exploitation on the 17th!](https://aws.amazon.com/blogs/security/amazon-threat-intelligence-identifies-php2shell-exploitation-prior-to-public-disclosure-in-madpot) by [Nick Frichette](https://x.com/Frichette_n/status/2113079581984878794).
- [Nearly 11,000 cybercrime networks disrupted and over 1,400 arrests in Operation Serengeti III targeting business...](https://www.bleepingcomputer.com/news/security/authorities-disrupt-nearly-11-000-cybercrime-networks-in-africa) by [BleepingComputer](https://x.com/BleepinComputer/status/2113185455193698512).
- [Amazon says PHP2Shell exploitation began 4 days before patches](https://www.bleepingcomputer.com/news/security/amazon-says-php2shell-exploitation-began-4-days-before-patches) by [BleepingComputer](https://x.com/BleepinComputer/status/2113256430006387190).
- [‼ALERT - Two new unpatched CVSS 9.0 RCE flaws in Linux's KSMBD SMB server were disclosed on public kernel mailing...](https://thehackernews.com/2026/10/two-cvss-90-linux-ksmbd-rce-flaws.html) by [Florian Roth](https://x.com/cyb3rops/status/2113320734085026170).
- [Arista patches new VeloCloud Orchestrator zero-day exploited in attacks](https://www.bleepingcomputer.com/news/security/arista-patches-new-velocloud-orchestrator-zero-day-exploited-in-attacks) by [BleepingComputer](https://x.com/BleepinComputer/status/2113319125166542937).
- [And as if all these critical vulnerabilities weren't enough, we've also had several reports about threat actors...](https://www.microsoft.com/en-us/security/blog/2026/10/21/storm-0940-uses-artex-agentic-ai-connectwise-supply-chain-compromise) by [Florian Roth](https://x.com/cyb3rops/status/2113334035716165712).
- [LiteLLM release pipeline hacked to distribute info-stealer malware](https://www.bleepingcomputer.com/news/security/litellm-release-pipeline-hacked-to-distribute-info-stealer-malware) by [BleepingComputer](https://x.com/BleepinComputer/status/2113347944132784601).
- [Capcom confirms data breach affecting 11.7 million accounts](https://www.bleepingcomputer.com/news/security/capcom-confirms-data-breach-affecting-117-million-accounts) by [BleepingComputer](https://x.com/BleepinComputer/status/2113365529255707120).
- [Compromised TLS Certificates](https://www.schneier.com/blog/archives/2026/10/compromised-tls-certificates.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2113591934371655880).
- [Crime Stoppers chapter freezes tips after breach breaks anonymity promise](https://www.malwarebytes.com/blog/data-breaches/2026/10/crime-stoppers-chapter-freezes-tips-after-breach-breaks-anonymity-promise) by [Nicolas Krassas](https://x.com/Dinosn/status/2113598262964056557).
- [HPE patches eight max severity RCE and auth bypass AOS flaws](https://www.bleepingcomputer.com/news/security/hpe-patches-eight-max-severity-rce-and-auth-bypass-aos-flaws) by [Nicolas Krassas](https://x.com/Dinosn/status/2113618698703429672).
- [Hackers Breach Enterprise Firewalls and VPNs, Exposing Over 70,000 Credentials](https://thehackernews.com/2026/10/hackers-breach-enterprise-firewalls-and.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2113643433864605860).
- [Quest Diagnostics confirms data breach exposed patient records](https://www.bleepingcomputer.com/news/security/quest-diagnostics-confirms-data-breach-exposed-patient-records) by [BleepingComputer](https://x.com/BleepinComputer/status/2113671895321112986).
- [Exposed Infrastructure Reveals How Ransomware Affiliates Used AI Agents to Execute Intrusions](https://thehackernews.com/2026/10/exposed-infrastructure-reveals-how.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2113698925337039245).
- [ClickFix keeps evolving. MsftSecIntel found compromised sites quietly caching a VBScript in the browser, disguised...](https://x.com/Shammahwoods/status/2113729139018752488) by Ezra Woods.
- [Python2Shell is also a thing now. Advisory](https://github.com/advisories/GHSA-9v8h-qqgm-4m35) by [Swissky](https://x.com/pentest_swissky/status/2113773372001702011).
- [I've been made aware of a post from someone representing Rufus who says I'm very confused about this post](https://github.com/pbatard/rufus/issues/3064).
- [Just wait for people to understand the pillow is as well problematic like brotli](https://thehackernews.com/2026/10/critical-flaw-in-pythons-popular-pillow.html?m=1) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2113867215946846574).
- [BlackX UEFI bootkit exploits Baton Drop flaw to bypass Secure Boot](https://www.bleepingcomputer.com/news/security/blackx-uefi-bootkit-exploits-baton-drop-flaw-to-bypass-secure-boot) by [BleepingComputer](https://x.com/BleepinComputer/status/2113998497686908960).
- [Keystone Hardware Wallet says website breach exposed customer data](https://cryptonews.net/news/security/33645572) by [Nicolas Krassas](https://x.com/Dinosn/status/2114218613057999103).
- [I used slicervm as a forensic environment to explore what MITM would look like with the compromised eMudhra...](https://slicervm.com/blog/reproducing-emudhra-ca-incident-safely) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2114372771698393212).
- [OpenAI AI Agents Demonstrate VM Escapes and Secret Cross-Sandbox Communication](https://thehackernews.com/2026/10/openai-ai-agents-demonstrate-vm-escapes.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2114327775658074479).
- [Hunting the Invisible Trust Boundary: Detecting Third-Party OAuth App Abuse in Microsoft Entra ID](https://www.mitiga.io/blog/connectwise-breach-entra-app-abuse) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2114350583222321169).
- [AI coding agents hijacked using AGENTS.md file in Downloads folder](https://www.bleepingcomputer.com/news/security/ai-coding-agents-hijacked-using-agentsmd-file-in-downloads-folder) by [BleepingComputer](https://x.com/BleepinComputer/status/2114383958028750884).
- [petmergency took out my bsides talk :( here's the devil wears markdown, plus unpick, a tool for vetting AI things...](https://amberbennoui.com/unpick) by [Dan Guido](https://x.com/dguido/status/2114394209105129478).
- [Kernel UaF to Root, part 3: Turning the address we leaked in part 2 into a kernel write, on a Pixel 6 running...](https://www.eshard.com/blog/kernel-uaf-to-root-3-write) by [kmkz](https://x.com/kmkz_security/status/2114695515396862081).
- [Bias in Qwen3-Coder Model](https://www.schneier.com/blog/archives/2026/10/bias-in-qwen3-coder-model.html) by Bruce Schneier.
- [Introducing Neo Triage, available to everyone today](https://go.projectdiscovery.io/triage) by [ProjectDiscovery](https://x.com/pdiscoveryio/status/2114774164922114103).

</details>


## Techniques and Write-ups

- [Bypassing LDAP Signing via NTLM Relay Reauthentication](https://specterops.io/blog/2026/10/23/ldap-signing-bypass-ntlm-relay) by Raj Patel.
> SpecterOps found that LDAP and SMB signing can be bypassed through re-authentication on attacker-owned connections. Signing still enforces, just with the attacker's session key. Microsoft patched SMB silently in September and LDAP in October.

- [Dropping Jev's Prompt-Injection Detection from 83% to 4%](https://securitylabs.datadoghq.com/articles/jev-as-a-judge-how-counterfeit-policy-steers-jev) by [Nick Frichette](https://x.com/Frichette_n/status/2112260736785195388).
> Datadog Security Labs found a technique that tanks Jev's prompt-injection detection rate and bypasses LangChain's experimental tool-risk gating.

- [FortiSIEM gRPC Path Traversal to RCE (CVE-2026-106173)](https://horizon3.ai/attack-research/cve-2026-106173-deep-dive-fortisiem-grpc-path-traversal-file-write-rce) by [/r/netsec](https://x.com/_r_netsec/status/2112530108208841056).
> Horizon3 deep dive on a Fortinet FortiSIEM vulnerability chaining gRPC path traversal with arbitrary file write to achieve remote code execution.

- [Your EDR Has Boundary Issues: Adversarial ML Evasion](https://youtube.com/watch?v=GNDMDI_pO8w&amp%3Bfeature=youtu.be) by [CCob󠁧󠁢󠁷󠁬󠁳󠁿](https://x.com/_EthicalChaos_/status/2113010292162543668).
> SpecterOps researchers harmj0y and tifkin_ demonstrate how adversarial machine learning can evade EDR detection, and how LLMs accelerate the reverse engineering behind it.

- [Header Accordions: QUIC Zero-Day Shuts Down Servers Remotely](https://foxio.io/blog/header-accordions-qpack-amplification-attacks-against-http-3-servers) by [Florian Roth](https://x.com/cyb3rops/status/2113188683012825167).
> FoxIO discovered a QPACK amplification attack that lets anyone remotely crash servers running vulnerable HTTP/3 libraries with a single request.

- [Node2Shell: Brotli Decoder Bug Enables Pre-Auth RCE in Node.js](https://www.imperva.com/blog/node2shell-from-brotli-data-to-remote-code-execution?x=1) by [Bobby Cooke](https://x.com/0xBoku/status/2113385216454934864).
> CVE-2026-111497. A single Brotli-compressed request to any Express app using express.json() achieves code execution. Affects Node.js 22, 24, and 26.

- [Defeating Enforced SMB Signing for Relay](https://blackfield.ch/blog/defeating-enforced-smb-signing) by [Dirk-jan](https://x.com/_dirkjan/status/2113345594676691065).
> Independent research abusing documented SMB re-authentication behavior to defeat enforced signing. PoC released. Patched on recent Windows versions.

- [AI-Assisted Exploit Development: An XNU Case Study](https://unprompted.au/videos/ai-assisted-exploit-development-an-xnu-case-study-blazakis) by [thaddeus e. grugq](https://x.com/thegrugq/status/2113698807783563478).
> Unprompted AU talk walking through practical AI-assisted exploit development against XNU, from vulnerability analysis to working exploit.

- [Trail of Bits: PHP2Shell Exploit Now Production-Grade](https://eliastaylor.com/noexploit) by [Dan Guido](https://x.com/dguido/status/2113825891021144306).
> Working exploit under stock php.ini-production settings with ASLR, multi-worker, and load. Targets WordPress, MediaWiki, phpBB, and Laravel on Apache and nginx, both architectures.

- [WHFB PIN Capture via Hardware Breakpoints](https://github.com/ivancabrera02/WHFB-PinCapture) by [Panos Gkatziroulis](https://x.com/ipurple/status/2114435324218855477).
> Captures Windows Hello for Business PINs by placing a CPU hardware breakpoint on LogonUI.exe's PIN packaging function. Login succeeds normally; the PIN is read from the trapped thread context.


<details markdown="1">
<summary>More this week (126)</summary>

- [Re As you will see this post is a bit special](https://knifecoat.com/Posts/Pok%C3%A9mon+Red+ACE+-+Chaining+%24c3+to+VM+execution) by [Lucas Leong](https://x.com/_wmliang_/status/2112753981415940588).
- [REMnux now supports Apple Silicon and other arm64 systems natively, along with Intel and AMD](https://docs.remnux.org/) by [hasherezade](https://x.com/hasherezade/status/2111857996598759850).
- [GhostShares: Meta's Muse Exposed Prep for a Confidential Call With a Frontier AI Lab Leader](https://blog.claroc.io/ghostshares-muse-passive-dns) by [Nicolas Krassas](https://x.com/Dinosn/status/2111933023419846740).
- [Heartbreaker](https://objective-see.org/blog/blog_0x8A.html) by [Nicolas Krassas](https://x.com/Dinosn/status/2112007295622066362).
- [APT28 is using weaponized Office documents to deliver the Covenant Grunt backdoor](https://x.com/cyb3rops/status/2112130847507669240) by Florian Roth.
- [DHS Officials Asked a Federal Cybersecurity Agency to Secretly Acquire a Voting Machine - and Hack It](https://www.propublica.org/article/cisa-election-security-donald-trump) by [Nicolas Krassas](https://x.com/Dinosn/status/2112149690644873600).
- [This is the official online shop of Estrosa ("an Italian professional nail brand focused on products for nail...](https://x.com/malwrhunterteam/status/2112162125263048922) by MalwareHunterTeam.
- [Six consuming tags. One Safari trick:](https://x.com/garethheyes/status/2112174430696722645) by Gareth Heyes \u2028.
- [Breaking, exclusive: Feds Suspect Ransom Negotiator Ran ShinyHunters Extortion Site U.S](https://infosec.exchange/@briankrebs/117467920904451947).
- [An attack that corrupts a LLM model about one specific fact - no file changes, no process, no network](https://stealthium.io/blog/hands-off-detecting-model-weight-tampering).
- [I found a CRITICAL auth bypass in Laravel (9.2/10) On MySQL/MariaDB, Laravel's token API guard let an...](https://x.com/pentest_swissky/status/2112447732094775741) by Swissky.
- [Me: "If feds get your unlocked Signal, they can ID everyone you talk to regardless of whether they use usernames"](https://scriptjunkie.us/2026/01/tracking-signal-identifiers).
- [> be me > get dm > "smelly, i found goop" > wtf i love goop (malware) > "Someone in South Korea received a Fortinet...](https://52.74.54.75/storage/install.exe) by [vx-underground](https://x.com/vxunderground/status/2112432485107671309).
- [There has been a glitch in the matrix](https://x.com/vxunderground/status/2112442188818718931) by vx-underground.
- [Unauthenticated SQL injection in GLPI (≤ 11.0.8)](https://mobeta.fr/blog/glpi-unauth-sqli) by [/r/netsec](https://x.com/_r_netsec/status/2112447061719416940).
- [Possible new Cellebrite iPhone Radio Zero-Day](https://www.schneier.com/blog/archives/2026/10/possible-new-cellebrite-iphone-radio-zero-day.html) by Bruce Schneier.
- [PackClient RAT Delivered With a Signed Kernel Driver](https://rogueauthority.org/signed-silentsetup-packclient-rat-driver) by [MalwareHunterTeam](https://x.com/malwrhunterteam/status/2112512215098302614).
- [Prompt injection, XSS and SIEM-exfil payloads living in reverse DNS, plus 28 fake Googlebots that passed FCrDNS](https://ellio.tech/en/blog/ignoreallpreviousinstructions-a-peek-into-340-billion-daily-reverse-dns-ptr-records) by [/r/netsec](https://x.com/_r_netsec/status/2112522559090762192).
- [Naruszono poufność niektórych kluczy umożliwiających generowanie zaufanych certyfikatów...](https://blog.mozilla.org/security/2026/10/20/protecting-firefox-users-following-the-compromise-of-emudhra-intermediate-certificates) by [hasherezade](https://x.com/hasherezade/status/2112558608047034820).
- [How I got over 300 Tor exit nodes removed](https://kaba.cx/posts/20261020_Tor) by [/r/netsec](https://x.com/_r_netsec/status/2112537658413154745).
- [All vulnerabilities are now race conditions](https://blog.himanshuanand.com/2026/09/all-vulnerabilities-are-now-race-conditions) by [/r/netsec](https://x.com/_r_netsec/status/2112545209783627957).
- [APT Encyclopedia updated: every claim in the 62 profiles checked against its source, wrong citations fixed or...](https://cyllex.io/encyclopedia?v=1) by [Andy Gill](https://x.com/ZephrFish/status/2112547663501533319).
- [Free real-time Certificate Transparency stream, no API key](https://certstream.dev/free-certstream-api.html) by [/r/netsec](https://x.com/_r_netsec/status/2112552757429457334).
- [Related Hookedge dropper samples uploaded abuse_ch](https://bazaar.abuse.ch/browse/tag/Hookedge) by [hasherezade](https://x.com/hasherezade/status/2112569161423421794).
- [There's only so much code: the rise in vulnerability numbers](https://blog.talosintelligence.com/theres-only-so-much-code-the-rise-in-vulnerability-numbers) by Kri Dontje.
- [The OffiDocs Browser Extension Campaign](https://amibeingpwned.com/blog/offidocs-campaign) by [/r/netsec](https://x.com/_r_netsec/status/2112582956619551052).
- [Auditing Electron Fuses with REA](https://pentestit.com/auditing-electron-fuses-with-rea) by [Mayuresh 🇮🇳](https://x.com/pentestit/status/2112602795690041430).
- [-> Totally not some boring as fuck Mac malware...](https://x.com/malwrhunterteam/status/2112607806964535613) by MalwareHunterTeam.
- [Writing a Beacon Object File (BOF) from Scratch in C](https://by7e.dev/blog/bof-from-scratch-in-c) by [Panos Gkatziroulis](https://x.com/ipurple/status/2112639616780226774).
- [CVE-2026-46633: Proving exploitability of Twig sandbox bypass](https://gist.github.com/vladko312/d61b950f168c791db4786b83dc7a81e6) by [/r/netsec](https://x.com/_r_netsec/status/2112643356685996233).
- [We discovered CVE-2026-101767, an unauthenticated SQL injection in Oracle E-Business Suite that chains to remote...](https://x.com/kmkz_security/status/2112928148543443074) by kmkz.
- [France had more Internet-exposed Danfoss refrigeration dashboards than the rest of the world combined before the...](https://ipinfo.io/blog/france-fridges-hack) by [/r/netsec](https://x.com/_r_netsec/status/2112658454074761349).
- [Reducing the attack surface of deployed services and apps is a fundamental component of software that is secure by...](https://www.anthropic.com/research/attack-surface-reduction) by [Jon Oberheide](https://x.com/jonoberheide/status/2112680657738416321).
- [Swallowtail (AKA APT28 / FancyBear / ForestBlizzard ): Russian🇷🇺 Espionage Group Targets Defense Firms in Two NATO...](https://www.security.com/threat-intelligence/swallowtail-russia-nato-targets) by [SwitHak ()](https://x.com/SwitHak/status/2112676418026918192).
- [Armadin started from one public report of an exposed AI attack platform](https://www.armadin.com/blog-posts/beyond-cairn-the-glass-houses-of-ai-attackers) by [werdhaihai](https://x.com/werdhaihai/status/2112929626276385083).
- [Parasitizing trust: How legitimate infrastructure becomes a delivery pipeline for attackers](https://blog.talosintelligence.com/parasitizing-trust-how-legitimate-infrastructure-becomes-a-delivery-pipeline-for-attackers) by Diana Brown.
- [litellm==1.107.0 on PyPI ships a credential stealer and a backdoor](https://safedep.io/litellm-pypi-compromise-credential-stealer-backdoor) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2112914055119991132).
- [Hiding a DLL from the PEB Loader List (And Why Process Explorer Still Sees It)](https://trainsec.net/library/windows-internals/hiding-a-dll-from-the-peb-loader-list-and-why-process-explorer-still-sees-it) by [Panos Gkatziroulis](https://x.com/ipurple/status/2112920767918690480).
- [Your AI agent fixed the bug, but what else did it change?](https://blog.trailofbits.com/2026/10/21/your-ai-agent-fixed-the-bug-but-what-else-did-it-change).
- [Two critical RCEs in PHP core](https://blog.talosintelligence.com/two-critical-rces-in-php-core) by Cisco Talos.
- [uCreator: virtualization-based Android spyware platform targeting WeChat, Telegram and other messaging apps](https://www.0x0v1.com/ucreator-virtualization-based-android-spyware-platform-targeting-wechat-telegram-and-other-messaging-apps) by [/r/netsec](https://x.com/_r_netsec/status/2112930245259231336).
- [Meet N1: Apple's wireless chip](https://almamatertech.com/notes/n1-1-meet-n1) by [winterknife](https://x.com/_winterknife_/status/2113002348351996263).
- [A single integer overflow in Windows HTTP.sys can lead to local privilege escalation](https://www.coresecurity.com/blog/cve-2026-62735-understanding-httpsys-integer-overflow?source=x) by [SinSinology](https://x.com/SinSinology/status/2113197962159440038).
- [Kimsuky (APT-C-55) is delivering persistent backdoors through multilingual LNK phishing lures After reading the 360...](https://github.com/NextronSystems/iocs/tree/master/reports/Hunting%20Kimsuky:%20Multi-Language%20LNK%20Lures%20Delivering%20Persistent%20Backdoors) by [Florian Roth](https://x.com/cyb3rops/status/2113048965935747260).
- [i jailbroke the nintendo switch 2 so i modded cinnamoroll, peter griffin, hatsune miku, and more into Mario Kart...](https://pepsipu.com/blog/2026-10-switch2-jailbreak-ns2jb) by [Lucas Leong](https://x.com/_wmliang_/status/2114162197446140399).
- [Thrilled to share my latest research on AI-assisted cyberattacks and the ARTEX hacking framework!](https://www.zscaler.com/blogs/security-research/inside-global-ai-assisted-hacking-campaign) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2113216788284821668).
- [It doesn’t stop …](https://vercel.com/kb/bulletin/node-js-security-advisory) by [Florian Roth](https://x.com/cyb3rops/status/2113188251045691511).
- [ESETresearch uncovered MythicRatatoskr, an undocumented Go backdoor hiding its C&C server inside the Yggdrasil mesh...](https://www.welivesecurity.com/en/eset-research/mythicratatoskr-yggdrasil-enabled-backdoor-deployed-uac0099-sandworm-collaboration) by [SwitHak ()](https://x.com/SwitHak/status/2113200223157731826).
- [Japan going all in](https://www.straitstimes.com/asia/east-asia/japans-banks-and-airlines-pull-digital-services-offline-in-scramble-to-fix-php-flaws) by [Stefan Esser](https://x.com/i0n1c/status/2113201144436547984).
- [BSI seziert Windows Hello: Wo Microsofts Anmeldung an Grenzen stößt](https://www.heise.de/news/BSI-seziert-Windows-Hello-Wo-Microsofts-Anmeldung-an-Grenzen-stoesst-11365867.html) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2114352105502941212).
- [Reversing a DPRK-linked toolkit that backdoors VS Code, Cursor, Discord and npm, with an Ethereum dead-drop C2 and a...](https://medium.com/@tarunrd77/north-korea-backdoored-their-vs-code-npm-kept-bringing-it-back-6371da5e74c4?sharedUserId=tarunrd77) by [/r/netsec](https://x.com/_r_netsec/status/2113209586148900932).
- [From Boot Key to Plaintext: How Windows LSA Secrets Are Deciphered from the Registry](https://hideandsec.sh/books/windows-sNL/page/from-boot-key-to-plaintext-how-windows-lsa-secrets-are-deciphered-from-the-registry) by [Panos Gkatziroulis](https://x.com/ipurple/status/2113220793928671450).
- [Maybe some interesting opendir: Also found that this IP was already mentioned earlier this month in this article by...](https://bridewell.com/insights/blogs/detail/artex-ai-linked-infrastructure-observed-scanning-uk-cni-discovery-and-associated-services) by [MalwareHunterTeam](https://x.com/malwrhunterteam/status/2113238463801864577).
- [Link to my slides and talk recording "macOS Mounting Madness" is up on my site](https://theevilbit.github.io/talks) by [Csaba Fitzl](https://x.com/theevilbit/status/2113267313788997952).
- [Microsoft patched PetitPotam in their latest update, EFSRPC now validates shares locally, killing WebDAV coercion ...](https://x.com/maxime_tz/status/2113498437077389807) by Max.
- [Using process coalitions in the XNU kernel to benefit incident response process trees](https://themittenmac.com/blogs/process-coalitions-in-the-xnu-kernel) by [Csaba Fitzl](https://x.com/theevilbit/status/2113326582953631958).
- [Starting on November 4th, Entra ID users will be able to create agent identity blueprints unless this capability is...](https://x.com/DirectoryRanger/status/2113329443120857097) by DirectoryRanger.
- [All you need to know about JA3 & JA4 Fingerprints (and how to collect them)](https://medium.com/@ggabrielhd/all-you-need-to-know-about-ja3-ja4-fingerprints-and-how-to-collect-them-8f189085b61f) by [Panos Gkatziroulis](https://x.com/ipurple/status/2113299973827637374).
- [As part of our Open Defense Initiative, we used dfs-large1 from depthfirstlabs to uncover two memory corruption bugs...](https://x.com/alexjplaskett/status/2113307024649805842) by Alex Plaskett.
- [Markdown Is the New Executable: Attackers Are Dropping Agent Instructions Into Your Downloads Folder From the Web](https://forever.security/blog/hijacking-ai-agents-via-downloads-folder) by [/r/netsec](https://x.com/_r_netsec/status/2113307731654496477).
- [Forewarned...](https://x.com/PyroTek3/status/2113312194150748524) by Sean Metcalf.
- [Exclusive: FoxIO researcher says Bun never answered its May report of a server-crashing HTTP/3 flaw](https://runtimewire.com/article/researcher-says-bun-did-not-answer-may-report-on-http3-flaw-7e4927?rwr=xmu4qsbu&amp%3Brws=llpxf5e1) by [/r/netsec](https://x.com/_r_netsec/status/2113330381328191626).
- [And the security shitshow continues](https://www.oracle.com/security-alerts/alert-cve-2026-91403.html) by [Florian Roth](https://x.com/cyb3rops/status/2113333449901621732).
- [Does it ever end? Accidentally sent unpatched (incl RCE) bugs to public mailing list](https://www.phoronix.com/news/LKML-New-Trend-Vulnerabilities) by [AndrewMohawk⁽ⁿᵘˡˡ⁾](https://x.com/AndrewMohawk/status/2113342653433848136).
- [Unvetted AI agents are accessing U.S. bank accounts](https://www.axios.com/2026/10/22/ai-agents-banks-unauthorized-accounts-access) by [/r/netsec](https://x.com/_r_netsec/status/2113345482240209363).
- [104.194.141[.]56 sunmerksin[.]com placewingarage[.]com Don't check this IP nor these domains, totally nothing...](https://x.com/malwrhunterteam/status/2113378811026825565) by MalwareHunterTeam.
- [The remarkable tale about how Dutch intelligence got access to Jared Kushner's phone is the least impressive...](https://www.vanityfair.com/story/jared-kushner-hacked-phone-secret-negotiations) by [Kim Zetter](https://x.com/KimZetter/status/2113387770655772822).
- [Local Shellcode Execution via SetupIterateCabinetW New Medium post, today we are going to explore a shellcode...](https://medium.com/@s12deff/local-shellcode-execution-via-setupiteratecabinetw-f217b2970aa3) by [Panos Gkatziroulis](https://x.com/ipurple/status/2113399754386235454).
- [Our OSS artifact scanning picked this up too The funny part, at least for us, is that this is a side project built...](https://sitecustomize.py/) by [Florian Roth](https://x.com/cyb3rops/status/2113542253230592018).
- [Regexp compilation fixes related to GitLab's CVE-2026-89078, CVE-2026-93577, CVE-2026-97229 and CVE-2026-110264](https://www.ruby-lang.org/en/news/2026/10/23/regexp-fixes-for-gitlab-cves) by [Nicolas Krassas](https://x.com/Dinosn/status/2113599607980654696).
- [Uninvited guest: How a GRU spy connected to state hackers broke into the African Union’s diplomatic residence in...](https://theins.press/en/inv/298635) by [thaddeus e. grugq](https://x.com/thegrugq/status/2113865173698240828).
- [In his latest write-up, Johann Rehberger (wunderwuzzi23) shows how one trailing dot bypassed Copilot's...](https://embracethered.com/blog/posts/2026/visual-studio-copilot-remote-code-execution) by [Max](https://x.com/maxime_tz/status/2113932807080690005).
- [Infostealers are hijacking the AI train](https://research.checkpoint.com/2026/infostealer-riding-the-ai-train) by [kmkz](https://x.com/kmkz_security/status/2113744255084556780).
- [EMFI adventures part 2: target characterization on STM32H5](https://www.errno.fr/EM_Fault_Injection_STM32H5) by [/r/netsec](https://x.com/_r_netsec/status/2113624823373119706).
- [Incident Response and Threat Landscape Report: Critical Infrastructure Vulnerabilities and Extortion Tactics](https://kylesinvestigation.com/2026/10/23/how-ai-ransomware-and-attacks-on-critical-infrastructure-are-reshaping-the-cyber-threat-landscape) by [/r/netsec](https://x.com/_r_netsec/status/2113624822005813636).
- [It is a weird weird year to be a formal methods expert](https://www.anthropic.com/research/formal-verification) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2114033899479167273).
- [Imperia CMS SiteActive TEMPLATE Unauthenticated SSTI Remote Code Execution (CVE-2026-110355)](https://www.rcesecurity.com/2026/10/imperia-cms-siteactive-template-unauthenticated-ssti-rce-cve-2026-110355) by [/r/netsec](https://x.com/_r_netsec/status/2113647471746490507).
- [New talk up OAIC 2026: Vibe Fuzzing with Sam Lovejoy @_dinolover38 of IBM X-Force Offensive Research](https://www.offensiveaicon.com/vibe-fuzzing) by [Brett Hawkins](https://x.com/h4wkst3r/status/2114693644179357709).
- [Protecting C2 Traffic in Nim](https://jakobfriedl.github.io/blog/nim-c2-traffic) by [Panos Gkatziroulis](https://x.com/ipurple/status/2113663651320356982).
- [Using OpenEngine to continuously discover security vulnerabilities](https://openengine.cc/blog/continuous-security-review) by [/r/netsec](https://x.com/_r_netsec/status/2113677669892325547).
- [In case anyone wants to see how these attacks work and test their detection/response, I did a webinar with...](https://learn.microsoft.com/en-us/entra/id-protection/concept-identity-protection-risks) by [Nikhil Mittal](https://x.com/nikhil_mitt/status/2114400166690402724).
- [Infostealers Are Targeting AI: What Aokigahara Infostealer Reveals About the New Developer Attack Surface](https://blog.checkpoint.com/ai-security/infostealers-are-targeting-ai-what-aokigahara-infostealer-reveals-about-the-new-developer-attack-surface) by [Nicolas Krassas](https://x.com/Dinosn/status/2113694708065358008).
- [Where is the fun in modern security research?](https://atredis.com/blog/2026/10/22/dibs-on-the-fun-part) by [Sean Heelan](https://x.com/seanhn/status/2114332295016698089).
- [Re jonoberheide matthew_d_green waral555 OpenAI AnthropicAI daveaitel halvarflake benhawkes chrisrohlf trailofbits...](https://illusivedan.com/writing/patch-the-planet) by [Jon Oberheide](https://x.com/jonoberheide/status/2113706779108413595).
- [Noticed a fully FUD on VT Cobalt archive that was seen from Singapore](https://x.com/malwrhunterteam/status/2113712374695788574) by MalwareHunterTeam.
- [Python's certifi package provides the trusted root CAs for a huge portion of the Python ecosystem](https://gist.github.com/hdm/2e5ebbffa5f29069a42bb69ea9a045ca) by [HD Moore](https://x.com/hdmoore/status/2113799166870602005).
- [We're thrilled to have contributed a V8 vulnerability to one of this year's four $250K Chrome full chain exploits](https://x.com/noperator/status/2113991331672387801) by Caleb Gross.
- [Cloudflare's new PQ GeoKey Manager: keys that can only unwrap inside a chosen region, wrapped with hybrid ML-KEM +...](https://blog.cloudflare.com/post-quantum-geo-key-manager) by [/r/netsec](https://x.com/_r_netsec/status/2113911713380856141).
- [ADCS Complete Attack Reference](https://xbz0n.sh/blog/adcs-complete-attack-reference) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2114368663994474593).
- [The Broccoli bug (CVE-2026-111497) affected Chrome for ~8 years](https://groups.google.com/a/chromium.org/g/net-dev/c/xdVm8c2GOMQ/m/85uNKUbfnb0J?amp%3Bpli=1) by [Halvar Flake](https://x.com/halvarflake/status/2114020258243838203).
- [New Evidence Shows LiteLLM Secret-Stealing Workflows Ran 11 Days Before Supply Chain Attack - Karlo Zanki SocketSecurity](https://socket.dev/blog/litellm-attack-timeline) by [Swissky](https://x.com/pentest_swissky/status/2114011157149442145).
- [I am evaluating secure sandbox surfaces for high-trust agent environments (benchmarking, SFT, expert on-policy...](https://www.docker.com/products/docker-sandboxes) by [SinSinology](https://x.com/SinSinology/status/2114031408444563667).
- [New blog post: Automating a YubiKey for Agentic Logins](https://jon.oberheide.org/blog/2026/10/24/automating-a-yubikey-for-agentic-logins) by [Jon Oberheide](https://x.com/jonoberheide/status/2114029568621174907).
- [How LLM-Based Penetration Testing Harnesses Work](https://utkusen.substack.com/p/how-llm-based-penetration-testing) by [/r/netsec](https://x.com/_r_netsec/status/2114047607828066791).
- [It looks like they figured out the end to end PoC from our August Wordpress RCE chain, XSS2Shell](https://github.com/Boreas37/CVE-2026-64638-PoC-XSS2Shell-) by [Paulos Yibelo](https://x.com/PaulosYibelo/status/2114062098732880319).
- [Custom Extensions](https://ipurple.team/2026/10/22/custom-extensions) by [Panos Gkatziroulis](https://x.com/ipurple/status/2114085221754634700).
- [‼ ok, this might be the first publicly documented, validated PHP2Shell RCE in the wild](https://github.com/0x4D31/honeypot-data/tree/main/reports/php2shell) by [Dan Guido](https://x.com/dguido/status/2114114690813247967).
- [Happy to have helped LiteLLM recover from this incident behind the scenes](https://docs.litellm.ai/blog/security-incident-oct-21-2026-attack-chain) by [Dan Guido](https://x.com/dguido/status/2114149973407211758).
- [If Andy says so, i would take this from granted. No need for details.](https://unit42.paloaltonetworks.com/cve-2026-109618-cve-2026-109619) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2114265493431349635).
- [Tailworm. We have zero-trust in our infrastructure. (Tailscale audit)](https://tailworm.com/) by [Nicolas Krassas](https://x.com/Dinosn/status/2114302182212153379).
- [Investigating WMI Permanent Event Subscription Persistence DFIR](https://www.forensicfocus.com/articles/investigating-wmi-permanent-event-subscription-persistence) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2114349614509797421).
- [Your Break-Glass Account Is Excluded From Every Policy. It Still May Not Get You In.](https://ridgelinecyber.com/blog/break-glass-account-excluded-but-locked-out) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2114350350777938207).
- [ripgrep as a lolbin](https://www.hexacorn.com/blog/2026/10/25/ripgrep-as-a-lolbin) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2114351409122422947).
- [Field Notes: Reconstructing an Attacker’s Workflow, by malmoeb DFIR](https://dfir.ch/posts/field_note_attacker_workflow) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2114351678476468251).
- [The apps that are supposed to protect you are the best attack vectors](https://x.com/Yanir_/status/2114368230512820293) by Yanir Tsarimi.
- [How abliterated models can get you pwned - pdiscoveryio princechaddha](https://projectdiscovery.io/research/how-abliterated-models-can-get-you-pwned) by [Swissky](https://x.com/pentest_swissky/status/2114384489032122799).
- [GMO INTERNET GROUP Notice Regarding Goodwill Payments to Customers and Compensation for Losses from Unauthorized...](https://group.gmo/en/ir_news/article/691) by [SwitHak ()](https://x.com/SwitHak/status/2114418817359065431).
- [Great Sunday read for all people doing red teaming ⤵ When a Red Team Engagement Gets Detected: Operational...](https://gikaku.net/2026/10/25/red-team-engagement-detected) by [Panos Gkatziroulis](https://x.com/ipurple/status/2114419288547250352).
- [Earlier this year I wrote a blog post about the Secure Kernel](https://antid0te.sg/blog/secure-kernel-first-look-erratum.html) by [Stefan Esser](https://x.com/i0n1c/status/2114456820286923086).
- ["Approximately five hours after this initial execution, Bumblebee deployed an AdaptixC2 beacon (AdgNsy.exe), which...](https://thedfirreport.com/2025/08/05/from-bing-search-to-ransomware-bumblebee-and-adaptixc2-deliver-akira-2) by [Jeff McJunkin](https://x.com/jeffmcjunkin/status/2114499614003089569).
- [These days GLx Runner can run SPTM, TXM, SK and Exclaves in VMAPPLE 4.5 That means GXF and SPRR work natively and...](https://antid0te.sg/glx-research-platform.html) by [Stefan Esser](https://x.com/i0n1c/status/2114598160605626817).
- [StealthBench measures whether autonomous offensive-security agents can finish the job without leaking credentials...](https://stealthbench.com/) by [Swissky](https://x.com/pentest_swissky/status/2114608968165384200).
- [Trojanized PeaZip Signed by Listenmaa Consulting](https://rogueauthority.org/signed-peazip-msi-self-updating-dll-sideload) by [MalwareHunterTeam](https://x.com/malwrhunterteam/status/2114632053472014643).
- [Another interesting project based on LOLBAS, but with telemetry included.](https://adversarial-detection-engineering.github.io/ofndb) by [Panos Gkatziroulis](https://x.com/ipurple/status/2114663156798943518).
- [The AI RCEssion: Why AI-driven security is calling in decades of software tech debt the-ai-rcession-has-begun/](https://blog.tedivm.com/rants/2026/10/the-ai-rcession-has-begun).
- [Interesting AI attack for initial access discovered by Forever Security recently: Website → Auto-downloaded .md →...](https://x.com/ipurple/status/2114750651913981974) by Panos Gkatziroulis.
- [New original SecurityBreakAI research!](https://blog.securitybreak.io/inside-omega-ai-the-rise-of-all-in-one-underground-ai-services-e0a0f91199b4) by [Thomas Roccia](https://x.com/fr0gger_/status/2114764603091550620).
- [You must be wrong ffforward, Microsoft never would help any malware actors, especially not ransomware related ones...](https://blog.deception.pro/blog/kongtuke-systembc-sep-2026) by [MalwareHunterTeam](https://x.com/malwrhunterteam/status/2114765830953263578).
- [How to Intercept HTTP/3 Traffic (QUIC and QPACK Explained)](https://interceptsuite.com/blog/intercept-http3-traffic-quic-qpack-explained).
- [Connection Reuse leading to desync uldnt-exist-anymore/](https://xclow3n.com/post/smuggling-shouldnt-exist-anymore).
- [IDA 9.5 is here: more platforms, more agentic power](https://hex-rays.com/blog/ida-9.5-release) by [Mari0n](https://x.com/pinkflawd/status/2114809186898907173).
- [Choose Your Backend: Three TLS Bugs in GoAhead end-three-tls-bugs-in-goahead](https://foxio.io/blog/choose-your-backend-three-tls-bugs-in-goahead).
- [A community translation can run attacker-chosen code in an exported Godot game...](https://axeghost.offprint.app/a/3mysixmpap723-a-community-translation-can-run-attacker-chosen-code-in-an-exported-godot-game).
- [Backporting security fixes to stable releases](https://blog.trailofbits.com/2026/10/27/backporting-security-fixes-to-stable-releases).
- [Hiding Capabilities in AI Models](https://www.schneier.com/blog/archives/2026/10/hiding-capabilities-in-ai-models.html) by Bruce Schneier.
- [From Arbitrary File Read to Shell: Yet Another RCE in Telerik rik-file-read-to-rce/](https://tantosec.com/blog/2026/10/telerik-file-read-to-rce).

</details>


## Tools and Exploits

- [Broadcom WiFi WPS Vulnerability Checker](https://github.com/qkaiser/broadcom-wps) by [Max](https://x.com/maxime_tz/status/2112059524995481645).
> Tool to check if your WiFi device is vulnerable to the unpatched Broadcom wormable RCE. Known affected devices listed.

- [h3fuzz: HTTP/3 Fuzzer at 100K Requests per Second](https://www.slcyber.io/research/how-practical-is-100k-requests-per-second-introducing-h3fuzz) by [/r/netsec](https://x.com/_r_netsec/status/2112507458468065632).
> SLCyber releases a high-speed HTTP/3 fuzzer capable of 100K requests per second for finding QUIC and HTTP/3 implementation bugs.

- [eMudhra Lab Server for Ludus (Bad Sector Labs)](https://github.com/badsectorlabs/ludus_emudhra_lab_server).
> Ludus lab role to reproduce the eMudhra CA compromise. Mint EV certs for any domain and code-sign any binary in your lab.

- [Pathrunner: AWS Privilege Escalation Framework](https://securitylabs.datadoghq.com/articles/introducing-pathrunner-aws-privilege-escalation-framework) by [/r/netsec](https://x.com/_r_netsec/status/2113632371606200326).
> Datadog Security Labs released a framework for discovering and exploiting AWS IAM privilege escalation paths.

- [Android TV Root Chain via Mali GPU Page-Cache Write](https://gitlab.com/c4psu13/mali-pagecache-root) by [/r/netsec](https://x.com/_r_netsec/status/2113949460992868737).
> Full source release of an autonomous root chain for TCL Android TV exploiting CVE-2022-22706 in the Mali GPU driver.

- [SysWhispers4](https://github.com/JoasASantos/SysWhispers4) by [Rob Fuller](https://x.com/mubix/status/2114351702174543919).
> Next generation of the SysWhispers direct syscall tool for evading EDR userland hooks.

- [node2shell-scanner: Detect Node.js Brotli RCE](https://github.com/assetnote/node2shell-scanner) by [Nicolas Krassas](https://x.com/Dinosn/status/2114227651703439555).
> Assetnote's high-fidelity detection scanner for CVE-2026-111497 (Node2Shell).

- [Breaking the AWS MCP Python Sandbox](https://xplo1t-sec.github.io/posts/breaking-the-aws-mcp-python-sandbox) by [/r/netsec](https://x.com/_r_netsec/status/2114251450650108239).
> Writeup on escaping the Python sandbox in AWS's MCP server implementation.

- [hashcat v8.0.0: PCFG Attacks, Hash Recipes, FPGA bcrypt](https://github.com/hashcat/hashcat/blob/v8.0.0/docs/releases_notes_v8.0.0.md) by [scriptjunkie (Matt)](https://x.com/scriptjunkie1/status/2114456099562893719).
> The largest update in hashcat history. PCFG attacks let you crack passwords using grammar-based models, hash recipes eliminate the need for fixed hash-modes, and bcrypt now runs on FPGA boards.

- [Context Bombs: Making Offensive AI Agents Pay](https://agentic.tracebit.com/factory) by [Panos Gkatziroulis](https://x.com/ipurple/status/2114686939094020327).
> Tracebit introduces context bombs as a defensive technique against agentic AI attackers, poisoning their context windows to burn tokens and derail autonomous exploitation.


<details markdown="1">
<summary>More this week (39)</summary>

- [Plex2Shell vulnerability chain reportedly exploited against outdated Plex servers PoC](https://github.com/code-zm/plex2shell) by [Simone Margaritelli](https://x.com/evilsocket/status/2111900816785232020).
- [SyscallRevenant - a new method of performing clean indirect syscalls](https://github.com/SilentisVox/SyscallRevenant) by [Panos Gkatziroulis](https://x.com/ipurple/status/2112071977909317963).
- [The new Bento DFIR portable toolkit has been released today! Enjoy](https://tsurugi-linux.org/downloads.php) by [Max](https://x.com/maxime_tz/status/2112537617015169430).
- [Major Exegol Wrapper update: Container Profiles Set container creation options once for each use case: image...](https://github.com/ThePorgs/Exegol/releases) by [Charlie Bromberg « Shutdown »](https://x.com/_nwodtuhs/status/2112174692782252375).
- [Three new metasploit exploit modules in the queue for several of the recent Cisco Secure Email Gateway vulns](https://github.com/rapid7/metasploit-framework/pulls?q=is%3Apr+%22Cisco+Secure+Email+Gateway%22) by [kmkz](https://x.com/kmkz_security/status/2112352101409882134).
- [An EDR evasion technique that leverages SendMessage with WM_SETTEXT for stealthy injection, bypassing direct calls...](https://github.com/TwoSevenOneT/PhantomBuffer) by [Panos Gkatziroulis](https://x.com/ipurple/status/2112189540022587608).
- [AI-driven malware analysis framework (written by AI) with 30+ integrated tools, web REPL, and MCP server](https://github.com/JoasASantos/Malvex) by [Panos Gkatziroulis](https://x.com/ipurple/status/2112246043396190601).
- [ARTEX Secondary Development Version: Autonomous Penetration Platform for the Entire Process of External Network...](https://github.com/enwjx/artex-ymh) by [Spiros Fraganastasis](https://x.com/m3g9tr0n/status/2112632204098462067).
- [I’ve been using ProxyBlob for a week on a target running CrowdStrike](https://github.com/quarkslab/proxyblob) by [thaddeus e. grugq](https://x.com/thegrugq/status/2112548189350080666).
- [This is insane. TiDB got absolutely pillaged in this hack. All their data is being released here.](https://fulcrumsec.vg/pingcap) by [mandatory.bsky.social](https://x.com/IAmMandatory/status/2112747248576770050).
- [Raw Bus recordings are a little glitchy. OpenEDR 2.5.1.0 OpenEDR XcitiumHQ](https://github.com/0xdeadbeefnetwork/SCRIPT-SNIFF-LPE) by [chompie](https://x.com/chompie1337/status/2112782534262366319).
- [A project that uses Confluence as a C2](https://github.com/dagowda/ConfluenceC2) by [Panos Gkatziroulis](https://x.com/ipurple/status/2112811420081385845).
- [PHP 8.5.12 released - 90 fixes in 29 components, including security fixes (CVE-2026-109618, CVE-2026-109619)](https://php-net.pro/news/php-8-5-12-released-with-security-fixes) by [Benjamin Delpy](https://x.com/gentilkiwi/status/2112909733904408859).
- [Signet - a code signing wrapper for Mythic C2](https://github.com/Whispergate/Signet) by [Panos Gkatziroulis](https://x.com/ipurple/status/2113537175891648653).
- [One loupe to find the chip](https://hos.direct/boardloupe) by [Max](https://x.com/maxime_tz/status/2114324326937751876).
- [Just open-sourced WinLPEAuditor - a Windows LPE misconfiguration auditor built in C++](https://github.com/0xby7eMe/Windows-LPE-Auditor) by [Panos Gkatziroulis](https://x.com/ipurple/status/2113746858887811110).
- [People running/part of MalwareShops/RedTeams, whats the biggest initial access problem you guys face?](https://github.com/whokilleddb/TTs) by [db](https://x.com/whokilleddb/status/2113599751853846566).
- [PHP2Shell (CVE-2026-109618 / CVE-2026-109619) is being exploited in the wild](https://github.com/blacklanternsecurity/PoCs).
- [We’re still testing how exploitable the Node.js/Brotli bug is, but we’ve found that it’s surprisingly hard to tell...](https://github.com/trailofbits/brotli-checker) by [Giuseppe `N3mes1s`](https://x.com/N3mes1s/status/2113864438675608008).
- [cups local privilege escalation (libcupsfilters 2-2.2.1) --- You can exploit the interaction between cups-browsed...](https://codeberg.org/piratemoo/cowcups) by [scriptjunkie (Matt)](https://x.com/scriptjunkie1/status/2114412838198337900).
- [aicodeking/leanrea: One 8 KB skill that replaces REA (Reverse Engineer Anything): plain CLI tools, no MCP](https://github.com/aicodeking/leanrea) by [Spiros Fraganastasis](https://x.com/m3g9tr0n/status/2114423832429703229).
- [As promised I'm releasing 2 new Wii exploits: Another Pwn & The Haxx Bearers They both come with source code...](https://github.com/ioncodes/wii-exploits) by [Layle](https://x.com/layle_ctf/status/2114013212601655559).
- [Adds protected Active Directory binds to synchronous ldap3 connections](https://github.com/dirkjanm/ldap3-ad-auth) by [Panos Gkatziroulis](https://x.com/ipurple/status/2114052048568160706).
- [Re jonoberheide Why not just use a "virtual" passkey approach where you intercept the Javascript and then use some...](https://github.com/f-bader/TokenTacticsV2) by [DirectoryRanger](https://x.com/DirectoryRanger/status/2114352183839695062).
- [I've just implemented Administrators group's WRITE_DAC permission abuse technique in my custom Windows SAM dumper](https://github.com/PeterGabaldon/WhatAboutSAM/tree/main) by [Peter Gabaldon](https://x.com/PedroGabaldon/status/2114056947112558903).
- [Two more EDR killers just landed on LOLDrivers, both from Jehad Abudagga's (j3h4ck) KillerLand research](https://github.com/redteamfortress/KillerLand) by [Nicolas Krassas](https://x.com/Dinosn/status/2114222354587136084).
- [Offline FairPlay App Store IPA decryption with independent key derivation](https://github.com/EthanArbuckle/fairplay-decrypt) by [Nicolas Krassas](https://x.com/Dinosn/status/2114228594830704947).
- [Proof of concept exploit for CVE-2026-106173, a path traversal file write leading to RCE for Fortinet FortiSIEM](https://github.com/horizon3ai/CVE-2026-106173) by [Nicolas Krassas](https://x.com/Dinosn/status/2114259969755193774).
- [Unthemidator - a fully autonomous Themida / Code Virtualizer / Win License unpacker](https://github.com/x86rc/unthemidator) by [hasherezade](https://x.com/hasherezade/status/2114439540392038499).
- [INTRODUCING: "Wake & Break" - a PSP Exploit for AMD navi31 cards](https://github.com/blasty/wake-and-break) by [blasty](https://x.com/bl4sty/status/2114328295906881825).
- [Confirmed this works. I had a random iPhone app I wanted to look at but it wouldn’t run on any of my jailbreakable...](https://github.com/drwhax/ipatool) by [scriptjunkie (Matt)](https://x.com/scriptjunkie1/status/2114333856979358055).
- [NMG generates parameterized .NET memory shell payloads that inject into IIS/ASP.NET applications without leaving...](https://github.com/baguette168/nmg) by [Panos Gkatziroulis](https://x.com/ipurple/status/2114368613193064480).
- [cvENGINE: the most advanced external attack surface assessment you can get for free](https://github.com/hevnsnt/CVEngine) by [Ring3API 🇺🇦](https://x.com/ntlmrelay/status/2114435287938138148).
- [Node2Shell PoC is now public](https://github.com/syrex1013/CVE-2026-111497-node2shell) by [kmkz](https://x.com/kmkz_security/status/2114601524202545236).
- [Kali Linux 2026.​3 Release (Build-Scripts Refresh): We are back with Kali Linux 2026.​3, the third release of the year!](https://x.com/kalilinux/status/2114630219319611432) by Kali Linux.
- [MISP v3.0 Early Access: a first look at what's new misp cti OpenSource ThreatIntelligence](https://www.misp-project.org/2026/10/16/misp.3.0-early-access.html) by [Max](https://x.com/maxime_tz/status/2114747878232981833).
- [AbliteratedOutTheBox - a fork of llama.cpp that gets any supported model to answer flagged harmful prompts...](https://github.com/heterodoxin/AbliteratedOutTheBox) by [Panos Gkatziroulis](https://x.com/ipurple/status/2114702836948705422).
- [Today we released WhisperHijack, a stealthy process injection PoC that uses thread descriptions to inject payloads...](https://github.com/Maldev-Academy/WhisperHijack) by [Panos Gkatziroulis](https://x.com/ipurple/status/2114752027519807887).
- [PngLoader - hides arbitrary data inside PNG images using two layers: 1⃣ Nibble-to-ASCII encoding - binary →...](https://github.com/i014n/PngLoader) by [Panos Gkatziroulis](https://x.com/ipurple/status/2114762895233851681).

</details>



