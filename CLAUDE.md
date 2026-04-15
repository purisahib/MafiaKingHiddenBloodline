# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Hindi-language long-format audiobook story titled **"Mafia King: Hidden Bloodline"** (माफिया किंग: हिडन ब्लडलाइन), written for the Pocket FM platform. Planned: **650 episodes across 5 seasons** (Season 1: 150, S2: 130, S3: 130, S4: 120, S5: 120).

**Premise:** Uday Singh, a humiliated son-in-law in a Jaipur haveli, discovers he is the son of Vikrant Singh — not a "don" but a "rokne wala" (one who stops) — whose legacy is a letter, a revolver, four silver coins identifying four trusted allies, and Pratap Malik's diary. The core philosophical spine of the story is Vikrant's line: *"मेरा असली वारिस वो होगा जो अश्विन को मारेगा नहीं, रोकेगा।"* ("My true heir will not kill Ashwin — he will stop him.")

## Repository Structure

- `Chapter{N}.txt` — Written episodes. Chapters 1–29 written. Check `ls Chapter*.txt` before assuming count.
- `आउटलाइन/Gudline.txt` — Pocket FM format rules.
- `आउटलाइन/List of Characters.txt` — Character profiles.
- `आउटलाइन/सीजन/सीजन {N} का पूरा आउटलाइन.txt` — Five season files. **These outlines were rewritten to match the actual written chapters and override any earlier plan.** When asked "what's next," read the current season file — not earlier memory of the plan.
- `आउटलाइन/Example/` — Reference style chapters.

## Writing Rules (strict)

- **Devanagari only.** No Roman/transliterated Hindi.
- **Novel prose, not screenplay.** Single-narrator audiobook — every dialogue must be woven into narration ("उसने कहा — ..."), never speaker-labeled lines.
- **Episode length: 3000–5000 words.** Hard bounds. Trim if over, expand if under. (Earlier chapters 1–12 were under target; 24+ hit the window.)
- **Structure every episode:** (1) opening recap paragraph summarizing the previous episode's key beats, (2) scene work with a mid-episode high point, (3) closing "अगले एपिसोड में —" teaser paragraph setting up the next hook.
- **Tone:** modern conversational Hindi, not literary/formal.
- **Rhythm of conflict:** small conflict per episode, large turn every ~10 episodes, season-ending catastrophe.
- **Time granularity:** the recent chapters track real-time down to the minute (e.g. "रात के दो बजकर तीन मिनट") — keep this compression when scenes are tense.

## Canon established through Ch. 29 (do not contradict)

Story has diverged substantially from the original Season 1 outline. Current canon:

- **The four coins:** (1) Inspector Raghav Singh — received his coin in Ch. 26. (2) Maulvi Abdul Rahman Chacha of the small mosque behind the old cemetery — holds the diary. (3) An old servant of Manmohan now in Banaras — unvisited. (4) A **woman**, name withheld; Abdul Chacha will only reveal her when "उदय का दिल एक बहुत बड़े धक्के के बाद टूट चुका होगा."
- **Vikrant was a "namazi don":** prayed fajr with Abdul Rahman in Pratap Malik's back room. Pratap was Vikrant's *childhood brother*, not his enemy; Pratap's death was an accident Ashwin misread as murder. This is the hinge of the whole series.
- **Ananya:** Kiyara's dead elder sister; buried 25 years under the kitchen's false cupboard; cremated in Ch. 26 at a Shiva temple behind the Galta hills.
- **Devraj (Bhanumati's brother):** exposed as Ashwin's first "inside man" in Ch. 24; held by Jagga's men at a secret location, never delivered to Ashwin or the police.
- **Vikas Singh:** exposed in Ch. 27 as Ashwin's planted child — a faint blue "R" tattoo on his right wrist, matched to Ranvijay Malik's identical "R" from a single afternoon in Ashwin's courtyard 25 years ago. His 25-year "qismat" is to seize the haveli by killing his nominal sister Kiyara. In Ch. 29 his mask cracked under Kiyara's 5-minute talk about a fever night from age 6.
- **Ranvijay Malik:** Ashwin's son, thought to be studying in Delhi, actually in Jaipur. First direct on-page appearance at the haveli's back gate in Ch. 29 carrying a wooden box. His first question to Uday: "क्या तुम्हारे बाप विक्रांत सिंह के पास मेरी माँ की कोई तस्वीर थी?" — signaling he is a potential future ally, not a flat villain.
- **The iron box (opened Ch. 25) contained:** Vikrant's revolver with the lion-sword family seal, four silver coins, and Vikrant's letter to Uday.
- **Uday's promise to Kiyara at the Galta stream (Ch. 26):** two-sided — "रोकने" का और ज़रूरत पड़ी तो "गिराने" का.

## Working on this story

- **Before writing a new chapter**, read the last 1–2 written chapters' closing teasers — they are contracts for what must happen next. Don't invent around them.
- **When the user asks for "next chapter,"** check the current highest `Chapter{N}.txt`, then cross-reference the corresponding episode bullet in the relevant season file. The season file is the plan; the previous chapter's teaser is the obligation.
- **When user requests word-count adjustments**, treat 3000–5000 as the binding range.
- **Do not resurrect the original (pre-rewrite) Season 1–6 outlines.** They are gone. Five season files now exist, renamed to `सीजन {N} का पूरा आउटलाइन.txt` without episode counts in filenames.
- **Character additions** stay in `आउटलाइन/List of Characters.txt` only if the user asks — don't preemptively edit it.

## Key characters (as of Ch. 29)

- **Uday Vikrant Singh** — protagonist; transitioning from humiliated son-in-law to "rokne wala" heir.
- **Kiyara** — wife; emotional anchor; co-agent, not passive. Promised to walk beside, not behind.
- **Vikrant Singh** — deceased father; revealed as "rokne wala," not a don.
- **Bhanumati Devi** — mother-in-law; former antagonist, now grieving mother (Ananya, Vikas).
- **Manmohan Singh** — father-in-law; confessed the basement's history in Ch. 23; cleared of "inside man" suspicion in Ch. 27.
- **Jagga Tiger** — Vikrant's old loyalist, Uday's strategic mentor.
- **Ashwin Malik** — main antagonist; believes (wrongly) Vikrant killed his father Pratap.
- **Ranvijay Malik** — Ashwin's son; ambiguous future-ally.
- **Vikas Singh** — Ashwin's planted child; mask cracked Ch. 29.
- **Inspector Raghav Singh** — first coin holder; Vikrant's debtor.
- **Abdul Rahman Chacha** — second coin holder; mosque mouthpiece for Vikrant's philosophy.
- **Ramu, Ganga Bai, Chunnilal** — haveli's long-trusted inner ring.
