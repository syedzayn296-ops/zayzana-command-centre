# Fishing Competition Platforms — Research Checkpoint
**Prepared:** 15 October 2026  
**Owner/context:** Zayzana Tech opportunity research  
**Status:** Preliminary desk research; no vendor demos, organiser quotes, or direct confirmation from Toyota/KZN have been completed.

## Objective
Investigate existing fishing competition software before considering building a new product. The possible workflow problem is that catch submissions move through angler/team WhatsApp groups and are then manually transferred by a secretary into a competition spreadsheet. This is based on Zayn's recollection of a Toyota in-house competition and is not yet a verified current process.

## Competition workflow described by Zayn
- Toyota in-house competition: eight rounds across the year, generally preferring Sundays to accommodate work and religious commitments.
- Results are recorded per round and accumulate towards annual standings; round/category winners are also recognised at the year-end function.
- A three-day AGM gathering is held where teams fish and stay together.
- Catch evidence includes a photo showing the approved measurement method and a named witness recorded in the message, apparently for dispute verification.
- Participants are expected to know species eligibility rules.
- Categories/awards mentioned: edible and inedible fish; largest fish in each category; total number of fish; most different species; male, female and junior divisions; and some species-specific competitions where different species earn different points.
- Anglers also used a separate species-and-length input app to estimate fish weight in kg/lb. The app name is currently unknown.
- Reported admin flow: angler → team WhatsApp group → team captain forwards to main fishing group → secretary manually enters details into a specific Excel spreadsheet → results/standings.
- Exact rules, scoring formula, spreadsheet design, current tools and purchasing authority remain unverified.

## Platform A: LetItSwim Fishing Tournaments
Links:
- Google Play: https://play.google.com/store/apps/details?id=com.twofivethreetechnologies.letitswim
- Product overview: https://apppage.net/preview/com.twofivethreetechnologies.letitswim

What published information indicates:
- Fishing competition catch submission using photo/video evidence against a prescribed template.
- Submissions go to a score master.
- Length-based submissions and real-time leaderboards are described.
- It is presented for Southern African fishing competitions.

Not yet confirmed:
- Edible/inedible categories and the full award mix.
- Male/female/junior divisions.
- Species-specific point tables.
- Eight-round cumulative team scoring and annual awards.
- Witness fields, export to spreadsheet, current availability/support, organiser pricing.
- Whether it can fit the Toyota/KZN association's exact rules.

## Platform B: Keepnet Weigh Bay
Links:
- Weigh Bay online app: https://www.keepnet.co/apps/keepnet-weigh-bay/online
- Features: https://www.keepnet.co/features
- Amateur tournaments: https://www.keepnet.co/for/amateur-tournaments
- South African Apple App Store listing: https://apps.apple.com/za/app/keepnet-weigh-bay-fishing-app/id1289354734

What official/public information indicates:
- Organisers can create competitions and teams, invite anglers, receive catch submissions, and review/void submissions.
- Species-specific scoring factors are supported.
- Team and individual formats are supported.
- Length and weight competition formats are supported.
- An offline option is described for remote locations.
- Public event listings include some South African/KwaZulu-Natal competition activity; this does NOT establish that Toyota or KZN association uses Keepnet.

Publicly listed angler subscription prices seen on the South African Apple App Store:
- One week: R99.99
- One month: R199.99
- Six months: R349.99
- One year: R699.99

Important pricing caveat: these are app subscription prices for anglers, not a confirmed association/organiser quote. Ask Keepnet for organiser pricing, team/season limits, support and terms.

Not yet confirmed for this specific use case:
- Exact support for edible/inedible awards, male/female/junior divisions, largest fish, total fish, species diversity and event-specific scoring in the required combination.
- Eight-round cumulative season standings and end-of-year awards.
- Witness details and evidence requirements.
- Exports, data ownership, local support, setup costs and organiser pricing.

## Preliminary comparison
| Capability | LetItSwim | Keepnet Weigh Bay |
|---|---|---|
| Photo/video catch evidence | Published as supported | Published as supported |
| Organiser/score-master review | Score-master workflow described | Review/void submissions described |
| Leaderboards | Published as supported | Published as supported |
| Species-specific scoring | Not confirmed | Published as supported |
| Team/individual formats | Not confirmed | Published as supported |
| Length/weight formats | Length-focused information found | Both length and weight described |
| Offline operation | Not confirmed | Offline option described |
| Eight-round cumulative standings | Not confirmed | Needs practical test |
| Exact Toyota award/division rules | Not confirmed | Needs practical test |
| Organiser price | Not found | Obtain quote |

## Current assessment
Keepnet is the first platform to test against the real workflow because its published feature set appears broader for scoring configuration and team formats. This is a research priority, not a conclusion that it is the right solution. LetItSwim should also be contacted to confirm current functionality and whether it handles season-long team competition.

## Recommended next actions — do not build yet
1. Ask Sundesh (KZN association secretary contact) about the current workflow, pain points, existing systems and whether a digital competition platform has been considered. There has already been email outreach; check the existing thread and response status before sending anything new.
2. Inspect/test the Keepnet demo with a checklist based on the exact Toyota rules.
3. Contact Keepnet for a written organiser quote covering eight rounds, teams, annual standings, awards, evidence review, exports and support.
4. Contact LetItSwim to verify current availability, rules flexibility, season-long scoring and pricing.
5. If possible, obtain a redacted example of the competition spreadsheet and the written rules. Do not share personal competitor data.
6. Decide between adopting/configuring an existing platform, offering a small setup/administration service, integrating a missing feature, or building only if a validated gap remains.

## Commercial guardrails
- Do not treat interest or recollection as a confirmed buyer or current requirement.
- Do not build before validating needs, decision-maker, budget and willingness to pay.
- Do not replace the existing weight-estimation app unless research shows a real gap.
- Keep manual approval for disputed/invalid catches and official results.
- The best potential product gap may be a specific combination of South African club rules, team/season scoring, witness/evidence records and secretary-friendly reporting—but this remains a hypothesis.

## Source note
This is a preliminary summary of public product pages and user-provided recollections, not an independent product audit. Features, links, pricing and availability should be rechecked before making purchasing or build decisions.
