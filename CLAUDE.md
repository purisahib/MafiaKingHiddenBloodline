# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Hindi-language long-format audiobook story titled **"Mafia King: Hidden Bloodline"** (माफिया किंग: हिडन ब्लडलाइन), written for the Pocket FM platform. Planned: **650 episodes across 5 seasons** (Season 1: 150, S2: 130, S3: 130, S4: 120, S5: 120).

**Premise:** Uday Singh, a humiliated son-in-law in a Jaipur haveli, discovers he is the son of Vikrant Singh — not a "don" but a "rokne wala" (one who stops) — whose legacy is a letter, a revolver, four silver coins identifying four trusted allies, and Pratap Malik's diary. The core philosophical spine of the story is Vikrant's line: *"मेरा असली वारिस वो होगा जो अश्विन को मारेगा नहीं, रोकेगा।"* ("My true heir will not kill Ashwin — he will stop him.")

## Repository Structure

- `Chapter/Chapter{N}.txt` — Written episodes. **Ch. 1–62 written; Ch. 63 is next.** Always run `ls Chapter/Chapter*.txt` before assuming the count.
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

## Canon established through Ch. 42 (do not contradict)

Story has diverged substantially from the original Season 1 outline. Current canon:

### Core reveals (Ch. 1–29)
- **The four coins:** (1) Inspector Raghav Singh — received his coin Ch. 26. (2) Maulvi Abdul Rahman Chacha of the small mosque behind the old cemetery — holds the diary. (3) An old servant of Manmohan now in Banaras — unvisited. (4) A **woman**, name withheld; Abdul Chacha will only reveal her when "उदय का दिल एक बहुत बड़े धक्के के बाद टूट चुका होगा."
- **Vikrant was a "namazi don":** prayed fajr with Abdul Rahman in Pratap Malik's back room. Pratap was Vikrant's *childhood brother*, not his enemy; Pratap's death was an accident Ashwin misread as murder. This is the hinge of the whole series.
- **Ananya:** Kiyara's dead elder sister; buried 25 years under the kitchen's false cupboard; cremated Ch. 26 at a Shiva temple behind the Galta hills.
- **Devraj (Bhanumati's brother):** exposed as Ashwin's first "inside man" Ch. 24; held by Jagga's men at a secret location.
- **Vikas Singh:** exposed Ch. 27 as Ashwin's planted child — a faint blue "R" tattoo on his right wrist. His 25-year mission was to seize the haveli by killing Kiyara. Mask cracked Ch. 29 under Kiyara's 5-minute talk about a fever night from age 6; by Ch. 36 he has chosen the haveli's side (resting at Bhanumati's side, fingers intertwined while sleeping).
- **The iron box (opened Ch. 25) contained:** Vikrant's revolver with the lion-sword family seal, four silver coins, and Vikrant's letter to Uday.
- **Uday's promise to Kiyara at the Galta stream (Ch. 26):** two-sided — "रोकने" का और ज़रूरत पड़ी तो "गिराने" का.

### Reveals from Arc 3–4 (Ch. 30–42)
- **Kaushalya's letter and bangle (Ch. 30):** The wooden box Ranvijay brought contained Uday's childhood photo (with Vikrant and Ashwin together), Kaushalya's letter establishing Ashwin as her brother → Ashwin is Uday's **mama** (maternal uncle). Ranvijay is Uday's **चचेरा भाई** (cousin). Kaushalya's bangle is now on the table in Uday's room in place of the revolver each night.
- **Rukmini Devi:** Ashwin's deceased wife, Ranvijay's mother. Her picture is the emotional key to Ashwin — seeing it, he wept and first recognized Ranvijay properly. Ranvijay carries it with him.
- **Arc 4 — छत का टकराव (Ch. 31–42, complete):** Six of Ashwin's men descended on the haveli roof. Key events: Jagga's first lathi strike; Ramu revealed on the roof that his son Sohan was killed by one of these very men 25 years ago — he shot that man dead and was himself wounded (deep abdominal cut). Ranvijay fought against Ashwin's men. Four men fled, two were neutralized. Ramu underwent surgery at SMS Hospital (Ch. 40–41); surgery successful, now in ICU. Ramu's last words before anesthesia: "जग्गा भाई, मेरा हिसाब आज पूरा हुआ।"
- **Chunnilal's tunnel (Ch. 37):** A path from the haveli basement through an old dry well in the adjacent alley — emergency escape route known only to the inner ring.
- **Prabhat Singh Rathod (Ch. 38):** Ashwin's longtime "salaahkar" (advisor), now exposed as a traitor. He has been running an arms warehouse on Ajmer Road, land registered in Ashwin's name — framing Ashwin while profiting independently. Raghav Singh produced the 20-year-old file; Uday sent it to Ranvijay who showed it to Ashwin. Prabhat is now the immediate active antagonist. He is not "running" — he is the type who launches a pre-emptive strike.
- **Ashwin's "mama" contact (Ch. 38–39):** Ashwin called Uday directly. Uday said "mama ji" — the first time the word was spoken aloud. Ashwin said: "तू बिलकुल अपनी माँ पर गया है." Ashwin also admitted to Ranvijay (Ch. 39–40): "प्रताप की मौत हादसा था। मुझे पता था। प्रभात ने दुश्मनी खड़ी की, मैंने मान ली — क्योंकि मुझे एक वजह चाहिए थी।" He then issued the "ruko" (stop) order to Sultan — first time in 25 years.
- **Three-step rule:** Uday has operationalized Vikrant's "rokna" philosophy — "पहले बोलना, फिर रोकना, फिर गोली।" Three chances before force.
- **Harnam and Ikbal:** Former Ashwin loyalists who guarded the haveli gate; switched to the haveli's side after the roof confrontation. Now on rotating duty at the front gate with Chunnilal.
- **Kalaram:** Jagga's man, drives the old white Maruti; ran the hospital run with Ramu.
- **Arc 5 begins with Ch. 43:** Teaser from Ch. 42 — "मामा का बुलावा." Uday and Ranvijay's first open conversation as cousins (चचेरे भाई), each telling the other their 25-year story. Morning after the 72-hour arc.

## Working on this story

- **Before writing a new chapter**, read the last 1–2 written chapters' closing teasers — they are contracts for what must happen next. Don't invent around them.
- **When the user asks for "next chapter,"** check the current highest `Chapter{N}.txt`, then cross-reference the corresponding episode bullet in the relevant season file. The season file is the plan; the previous chapter's teaser is the obligation.
- **When user requests word-count adjustments**, treat 3000–5000 as the binding range.
- **Do not resurrect the original (pre-rewrite) Season 1–6 outlines.** They are gone. Five season files now exist, renamed to `सीजन {N} का पूरा आउटलाइन.txt` without episode counts in filenames.
- **Character additions** stay in `आउटलाइन/List of Characters.txt` only if the user asks — don't preemptively edit it.

## Key characters (as of Ch. 42)

- **Uday Vikrant Singh** — protagonist; transitioning from humiliated son-in-law to "rokne wala" heir; now recognized as haveli's malik by the inner ring.
- **Kiyara** — wife; emotional anchor and co-agent; stabilized every person in the haveli after the roof arc; sleeps in the veranda waiting for Uday to return.
- **Vikrant Singh** — deceased father; revealed as "rokne wala," not a don.
- **Bhanumati Devi** — mother-in-law; former antagonist, now grieving mother (Ananya buried, Vikas reclaiming himself).
- **Manmohan Singh** — father-in-law; confessed the basement's history Ch. 23; cleared of "inside man" suspicion Ch. 27; feeling relief as the next generation takes over.
- **Jagga Tiger** — Vikrant's old loyalist, Uday's strategic mentor; revealed to have a missing son Kamal (25 years); now sitting by Ramu's ICU bedside as a brother, not a tiger.
- **Ashwin Malik** — main antagonist turning ambiguous; knows Pratap's death was an accident but built his life on the lie; gave first "ruko" order after Ranvijay's confrontation; potential reconciliation arc ahead.
- **Ranvijay Malik** — Ashwin's son, Uday's cousin (चचेरा भाई); fought against his own father's men on the haveli roof; returned to Ashwin's bungalow as a potential inside spy; carries Rukmini's picture.
- **Vikas Singh** — Ashwin's planted child; mask cracked, choosing the haveli; mask of "dushman" gone, new identity unformed.
- **Prabhat Singh Rathod** — new active antagonist; Ashwin's exposed former advisor running a shadow arms network; will strike pre-emptively now that his cover is blown.
- **Inspector Raghav Singh** — first coin holder; activated Ch. 38 (security alert + file delivery); reliable ally.
- **Abdul Rahman Chacha** — second coin holder; holds the fourth coin's secret (the unnamed woman); will reveal only after Uday's heart is broken.
- **Ramu** — haveli's oldest retainer; son Sohan's killer shot dead on the roof; Ramu wounded, surgery successful, in ICU. His "hisab" is settled.
- **Ganga Bai** — haveli cook; runs her kitchen as a "qila"; kept oil hot through the night as a weapon.
- **Chunnilal** — knows the basement tunnel; sleeps at the tunnel entrance; keeper of the oldest secret passage.
- **Kalaram** — Jagga's driver; minimal words, total reliability.
- **Harnam, Ikbal** — former Ashwin men, now haveli's front-gate guards on new allegiance.
