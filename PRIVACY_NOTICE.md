# Daniel's Frontier вЂ” Privacy Notice

Version 0.8.2 - 6 November 2026

## Controller and contact

Aleksander Kapitanidis, based in Bulgaria, is the controller of personal data
processed to operate Daniel's Frontier. The game server is privately
self-hosted in Bulgaria.

Privacy and account-data requests: privacy@contact.bratochki.com.
Game support and abuse reports: support@contact.bratochki.com.

## Offline and online use

Offline pilots, saves, preferences and HUD layouts are stored on your device.
An offline pilot does not require an online account and is not automatically
uploaded as online progress. Update checks and downloads still contact their
delivery providers.

Online play uses a server account and authoritative server-side progression.
Other players receive the pilot and world information needed for shared play.
Account emails and password hashes are not included in other players' snapshots.

## Information, purposes and legal bases

| Information | Purpose | Legal basis |
| --- | --- | --- |
| Email, public pilot name, account ID and creation time | Create and identify your account, sign you in and recover access | Perform the requested account/service contract, GDPR Article 6(1)(b) |
| Password submitted for authentication, stored salted password hash, session-token hashes and expiry | Authenticate access and maintain your session | Article 6(1)(b); protection against unauthorized access under Article 6(1)(f) |
| Invitation hashes, expiry/use/revocation records, recovery-code hashes, attempts and login-limiter records | Control admission, recover access and prevent misuse | Article 6(1)(b) for requested access/recovery; Article 6(1)(f) for security |
| Ships, equipment and attributes, balances, inventory, skills, XP/rank, sector, rewards, cooldowns and recent NPC transactions | Run and save your online pilot | Article 6(1)(b) |
| Movement, targets, attacks, timing and command IDs | Synchronize the world and validate actions | Article 6(1)(b); Article 6(1)(f) for fair-play and abuse prevention |
| Sector-chat messages, pilot names/IDs, contacts, presence and group state | Deliver the communication and social features you use | Article 6(1)(b); Article 6(1)(f) for necessary safety and moderation |
| Restrictions, ban reasons and administrator journals, including relevant before/after state | Investigate abuse, handle disputes and repair errors accountably | Article 6(1)(f) |
| IP/connection information, request headers and anti-bot signals | Deliver connections and protect accounts/infrastructure | Article 6(1)(f) |
| Bounded timing, status, byte/frame/snapshot measurements and diagnostic request IDs | Detect failures and diagnose performance | Article 6(1)(f) |
| Support/privacy correspondence and necessary verification details | Answer requests, provide support and exercise data rights | Article 6(1)(b) for requested service support; Article 6(1)(c) for legal duties; Article 6(1)(f) for necessary dispute records |

Our legitimate interests are protecting accounts and infrastructure, preventing
cheating and abuse, investigating disputes and keeping the game reliable.
You may object to processing based on these interests. We assess necessity
and the effect on your rights, with particular care for younger players.

We use Article 6(1)(c) only where a specific legal obligation applies. If an
optional purpose requires consent, we request it separately; you may withdraw
that consent without affecting earlier lawful processing. We do not require
marketing consent to play and do not sell personal data or run advertising.

Required account information is needed for online access. You can use available
offline features without creating an account. We do not routinely ask players
for their real name, postal address, date of birth, government ID, payment
details, camera, microphone or GPS location. Game coordinates are not GPS data.
Names, messages and attachments can nevertheless reveal information you provide.

## Storage on your device and security verification

The client stores pilot saves/backups, a profile catalogue, display/HUD
preferences, logs and update caches/backups. Display settings can include
monitor and window characteristics. Local files may remain after uninstalling.

Registration uses an embedded Microsoft WebView2 window for Cloudflare
Turnstile. Its dedicated local browser profile can retain cookies, cache and
browser storage between checks. Browser permission requests such as camera
and microphone access are denied. Security-provider processing is described
in the provider notices below.

Custom client diagnostics use a bounded memory buffer: at most 4,096 samples and five minutes (high activity can shorten the recorded window). Normal online requests exchange random diagnostic correlation IDs and server timing. Server metrics may be written to one rolling local report when enabled.

The in-game **Send report to support** action is optional and sends the current diagnostic buffer to the private game server. It includes your authenticated public pilot name, client version, delivery time and receipt, plus numeric timings, request status/size, frame/snapshot costs, movement/attack/turn/reset counters, effects/cache counts, managed-memory/allocation/garbage-collection and rendering-resource measurements. The server stores a concurrent numeric server capture for correlation. These are performance observations, not screenshots, chat messages, account email addresses, passwords, session tokens or complete gameplay request bodies. The game does not continuously upload support reports and does not automatically post them into a chat or email.

The operator can retrieve reports for requested troubleshooting. When requested by the operator, authorized support tooling, including AI-assisted tooling, can process selected report contents; the game itself does not send reports directly to an AI provider. Copy/save actions remain available locally. A saved local report remains until you replace or delete it. Review a report or screenshot before sharing it by another channel.

The server's ordinary diagnostic inbox keeps the latest report per player and at most 20 report files. A new submission replaces that player's previous report; count-based rotation is not a guarantee of deletion on a particular day. Operator copies used for an active support case and restricted backups follow the support-case and backup rules below.

If you enable **Remember credentials** on Windows, the client stores the selected account login and password in Windows Credential Manager under your Windows user account. This is optional and is not a plaintext game-settings file. Disabling the option removes the game's remembered credential. Sign-in still sends credentials to the game server over its configured HTTPS connection. Windows account security and local credential-vault access controls apply.

## Recipients and processing locations

- **The operator and authorized service personnel:** access as needed to run,
  secure and support the game. Source contribution alone does not grant access
  to player databases. The operator currently has sole access to the player database.
- **Other players:** relevant pilot IDs/names, ship/world/combat state, sector
  chat and contact/group/presence information. Do not share secrets in chat;
  recipients may keep messages or screenshots.
- **Cloudflare:** traffic protection/tunnel and Turnstile. It receives connection/security metadata
  and can process traffic passing through its services. Its roles depend on
  the service and include its own security purposes. See its
  [privacy policy](https://www.cloudflare.com/privacypolicy/) and
  [Turnstile notice](https://www.cloudflare.com/turnstile-privacy-policy/).
- **Resend:** account-recovery email delivery and any support messages routed
  through its email service to the operator's working inbox. It receives recipient/sender addresses, message
  content and delivery metadata. See its [privacy policy](https://resend.com/legal/privacy-policy)
  and [data-processing terms](https://resend.com/legal/dpa).
- **Proton Mail:** receives and stores support/privacy mail forwarded to the
  operator's private working inbox. The public contact address is separate
  from that inbox. See [Proton's privacy policy](https://proton.me/legal/privacy).
- **GitHub and delivery infrastructure:** update checks/downloads disclose IP
  and ordinary request metadata. The updater sends a game/version user-agent,
  not game-account credentials. See [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
- **Microsoft:** supplies WebView2 and its installation/update services, with
  associated software diagnostics described in the [Microsoft privacy statement](https://privacy.microsoft.com/privacystatement).
- **Authorities or advisers:** only where disclosure is necessary and legally
  justified, limited to relevant information.

The Bulgarian game-server location does not make all processing EU-only.
Resend states that it stores customer email data in the United States and
provides EU Standard Contractual Clauses in its data-processing terms.
Cloudflare's data-processing terms also provide EU Standard Contractual
Clauses for applicable transfers. Proton operates from Switzerland and can
use the locations and subprocessors identified in its privacy information.
Transfers to a country covered by an applicable European Commission adequacy
decision rely on that decision; other restricted transfers require the
applicable contractual or other lawful safeguard.
Contact the privacy address for information about applicable safeguards and
copies, subject to necessary protection of confidential information.

The game does not send gameplay records to a generative-AI service for player
chat or model training. Email/security providers may use their own automated
abuse-detection systems under their terms. Development use of AI tools does
not authorize us to send player records or support messages to an AI assistant.

## Retention

| Category | Retention rule |
| --- | --- |
| Active accounts and online pilots | While the account is used, until closure, or while a documented legitimate need requires limited retention. We review accounts after 24 months of inactivity and give at least 30 days' notice before deleting for inactivity. |
| Verified closure/erasure requests | Remove ordinary active account/pilot data within 30 days after identity verification, subject to necessary legal exceptions. We explain any limited retention. This operational target does not extend statutory response deadlines. |
| Sessions and recovery credentials | Sessions expire after 8 hours and recovery codes after 10 minutes. Expired security records are checked for deletion daily; credentials that remain necessary for an active incident are restricted. Expiry alone does not mean every stored row has already been erased. |
| Routine invitation and administrator records | Up to 90 days after the invitation expires/is used or a routine correction is completed, unless a specific incident or legal need requires limited retention. |
| Support messages | Up to 90 days after the case closes, unless needed for an open dispute or another documented legal purpose. |
| Abuse/ban evidence | Review after 6 months; retain longer only where still necessary to enforce an active restriction, investigate an incident or establish/exercise/defend a legal claim. Review continued retention periodically. |
| Minimal privacy-request register | Review after 12 months and remove unless still needed to demonstrate how a request was handled or meet a specific legal requirement. The register does not retain an unnecessary copy of the full account or identity documents. |
| Operator backups and routine logs | Rotate within 30 days. Backup copies awaiting rotation are access-restricted and are not restored into ordinary use without applying recorded deletions. |
| Chat/events | A shared in-memory queue holds up to 256 recent events and the client chat view up to 80 lines; these are count limits, not fixed deletion times. Copies in abuse cases follow the relevant case rule. Other players' copies are outside our control. |
| Custom diagnostics | At most5minutes/4096samples in memory; latest-per-player server inbox capped at20files until replaced/rotated or removed by support. Selected case copies follow support-case retention; backups follow backup rotation. Local exported files remain until you replace/delete them. |
| Local saves, preferences, browser profiles and update files | Stay on your device until you remove them or the applicable software cleans them up. |

Provider copies follow the applicable provider terms and request procedures.
For Resend's standard Free/Pro/Scale plans, its published service policy states
30-day email/log retention; enterprise arrangements can differ. We coordinate
necessary requests with providers and explain any remaining lawful limits.

We record the reason, access restriction and review date for any exceptional
retention. A ban is not a blanket exemption from erasure rights.

## Your rights

Depending on the circumstances, you can request access, correction, erasure,
restriction or portability, and object to legitimate-interest processing.
Where processing relies on consent, you may withdraw it. Write to the privacy
address; you do not need to use an in-game deletion screen.

We verify identity proportionately and do not ask for your password or recovery
code. We respond without undue delay and normally within one month of receipt.
If a lawful extension is needed, we explain the reason within that month.
Requests are ordinarily free; any lawful refusal or charge is explained.

You may complain to Bulgaria's [Commission for Personal Data Protection](https://cpdp.bg/)
or the competent supervisory authority where you live or work or where the
alleged infringement occurred. You do not need our permission or a prior
support complaint to do so.

## Automated checks, younger players and changes

The service automatically validates game actions, limits requests and expires
sessions. Turnstile checks registration challenges. You may contact support
for human review of disputed access restrictions. We do not use spending-based
reward manipulation or personalized advertising.

Online accounts are restricted to people aged **16 or over**. If we learn that
an under-16 player has an account, we restrict access and assess closure and
deletion, retaining only what is necessary for a lawful purpose.

We publish dated notices and explain material changes. If a new purpose needs
a different legal basis or consent, we address that before beginning the use.
