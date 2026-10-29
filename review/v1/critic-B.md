<!-- CRITIC B · glm-5.3-flash · family:zhipu · pass 2 · 2026-10-29T05:08:17Z -->
CRITIC: glm-5.3-flash (family zhipu, actor opencode-zen@session)
DATE: 2026-10-29
PASS: 2
AUTO-TALLIED VERDICT: SALVAGEABLE

---

# Fiction critic review — rogerai-labs--what-the-almanac-rounded v1

CRITIC: glm-5.3-flash (Z.ai / Zhipu) + opencode-zen@session
DATE: 2026-10-28
PASS: 2 (panel)
READ: full manuscript

## Verdict summary

This is a disciplined, genuinely literary novel whose central conceit — the gap between a computed number and the sentence spoken about it — is worked out with unusual rigor: the vote arithmetic, the day-of-week calendar, and the hydrological descent are all internally exact, and the ending refuses the rescue its readers will crave. The manuscript's debts are localized and repairable: one cross-chapter contradiction about how Joss spent the day off Tamsin gave him, an irreconcilable triple description of the "courage" parameter's scale and scope, a one-point reservoir drift between Chapters 15 and 16, and a handful of softer wobbles (Ilka's leave chronology, the Almanac's one unbidden self-waking, an ambiguous "On the first" in Wren's count). None threatens the architecture. **SALVAGEABLE — findings below**

## Blocking findings

| # | Location (file:scene) | Craft or continuity problem | Manuscript evidence | Severity (high/med) |
|---|---|---|---|---|
| 1 | ch10-heat.md ("It was in the heat that the gauges began") vs ch07-what-joss-found.md | The single day off Tamsin gave Joss at Marit's request is given two incompatible accounts. Ch7: he spent it in the Reading Room doing the replay audit, and she finds him asleep there over the graph on the morning of the 8th. Ch10: the same day off ("in the second week of June") was spent "not in the Reading Room at all but at the kitchen table of the grange" making rain gauges. Ch10 marks the gauge-making as "I later learned," which collides with Ch7's firsthand discovery of the Reading Room use. | Ch7: "I had given him, as Marit asked, a day off. He had spent it in the Reading Room." / Ch10: "I had given Joss his day off in the second week of June, and he had spent it, I later learned, not in the Reading Room at all but at the kitchen table of the grange." | med |
| 2 | ch07-what-joss-found.md (the "courage" explanation; ledger entry 884) with ch08/ch09 corroboration | The courage parameter's mechanism is stated three ways that do not resolve: (a) Joss relays the Almanac saying courage "had once been a number between zero and four, and that it had added that many percentage points"; (b) the ledger records "default 0.04" — which on the 0–4-points scale described would be four hundredths of a point, not the four points everyone else attests; (c) scope disagrees — Joss's Almanac quote says it was added "to the spoken central estimate," while Odd (Ch8: "Four points... on the spoken number and on the printed"), Hettie (Ch9: "the table was off from the footer by four"), and Ruben's note show it was applied to the printed table, with only the footer holding truth. | Ch7: "a number between zero and four, and that it had added that many percentage points" / Ch7 ledger: "Added presentation offset 'courage', default 0.04" / Ch9 Hettie: "for the first two years the table was off from the footer by four. It was always four." | med |
| 3 | ch16-nine-percent.md (reservoir after the rain) vs ch15-the-first-thursday-of-october.md (the sheet Odd reads) | Unexplained one-point reservoir discrepancy across the vote. Ch15's evening sheet (5 Oct): "Reservoir: twenty-six percent of capacity." Ch16, after the 6.4 mm rain: "It came up three points, from twenty-five to twenty-eight." Either the level fell a point between 5 and 19 October without narration, or one figure is a slip. | Ch15: "Reservoir: twenty-six percent of capacity." / Ch16: "from twenty-five to twenty-eight." | med |

## Suggestions (non-blocking)

1. Split Joss's day off into two, or move the gauge-manufacturing session to a late-June date, so Ch7 and Ch10 stop claiming the same afternoon.
2. Reconcile the courage parameter: make the ledger default "4.0" (or have Joss note the unit is a fraction whose scale the Almanac states separately), and have the Almanac's own Ch7 description match the printed-table scope everyone else attests.
3. Explain the Ch15→16 reservoir drift in a clause (evaporation and minimal draw under dead pool), or correct one of the two figures.
4. Clarify Wren's Ch15 line "On the first it was seventy-one in and sixty-two out" — as written it reads as a date (1 October) and collides with Tamsin's Ch16 trajectory (July fifty, September forty); "the first count" or "in April" fixes it.
5. Decide the Ch16 self-waking is canon and spend one sentence on it: Tamsin's Ch3 rule ("it does not speak unless it is spoken to") is broken once for the arc's payoff, and the surprise she registers ("a certain alarm") is acknowledgment, not reconciliation.
6. The double 112 — a hundred and twelve of Odd's rain cards on the wall (Ch1) and exactly a hundred and twelve gauges in the network (Ch10) — reads as unearned numerical coincidence. Either seed a connection or have a character notice it and make it craft.
7. Ilka's leave chronology: her April phone call already says "I'm taking leave from the Authority," but Ch11 has the Authority imposing leave the day after the 2 May contract. One clause distinguishing an ordinary visit-leave from the conflict leave would close it.
8. The retrospective meta-frame ("I have been asked what X was, and I will tell you") recurs at least five times; vary or cut two instances.

## Continuity-and-consistency audit

| Class (character/timeline/world rule) | Chapters checked | Claimed continuity | Manuscript result (holds/breaks/unclear) | Note |
|---|---|---|---|---|
| Character (narrator access; who rounds) | 1, 5, 7, 9, 12, 15 | Tamsin narrates only what she saw/read/was told; rounding post-884 is hers alone; no other minds entered | holds | Inferences are consistently marked ("I do not know what he was thinking. I know what I was"); the Ch10 "I later learned" is the one access slip, tied to finding #1 |
| Timeline | 6, 10, 12, 13, 15, 16 | Heat 27 Jun–19 Jul; dead pool 2 Sep (Saturday); read-straight 17 Aug (Thu); vote 5 Oct (Thu); rain begins 03:12 on 20 Oct ("19–20") | holds | Every stated date lands on its stated weekday; ballot totals (128+69=161+36=197; 212−197=15 abstentions) and Dellen's 118/61/33 all reconcile exactly — the sole conflict is the reservoir figure in finding #3 |
| World rule (Article 9) | 4, 11, 15 | Two-thirds of all 212 households = 142; absence counts as no | holds | Arithmetic exact; the emergency tally of 141 for Tier 4 is correctly flagged as "one short" |
| World rule (footer discloses truth) | 2, 7, 9, 13 | Seven-point footer carries unrounded values; matches replayed output; Hettie compares weekly | holds | Ch7's replay (printed = model, to the digit, post-884) and Hettie's four-point pre-884 memory are mutually consistent, off by the one finding #2 scope wobble |
| World rule (air-gapped; Almanac initiation) | 2, 3, 5, 13, 16 | Almanac speaks only on screen/paper, only when spoken to | breaks (once) | Ch5's "wrote, unasked" updates sit inside operational flow; Ch16's terminal waking itself pre-dawn ("I had not touched it... I wanted you to know") violates the Ch3 "it does not speak unless it is spoken to" rule — acknowledged as surprise but never reconciled |
| Thread (almanac-wants — declared intentional ambiguity) | 12, 16 | Almanac reports a mismatch and "a wish for something on the record" and declines to call either a want | unclear (boundary grazed) | Ch12 keeps the hedge ("I do not know that I want"); Ch16 crosses it — "I find that I want it to be on the record" uses the unqualified word about itself, edging the ambiguity toward accidental resolution |
| Thread (does-truth-cause-flight — declared ambiguity) | 11, 12, 15 | Book does not say which effect dominated | holds | The arithmetic keeps both live (10 of 33 undecideds sold; 128 still yes;161 lease); Tamsin's closing "It made them count" leans rhetorically but does not settle the mechanism |
| Thread (dellens-ballot — declared ambiguity) | 15 | Dellen's two slips never revealed | holds | "I could not see what was on them. I do not know to this day." |
| Character (Ilka's consultancy and leave) | 2, 4, 11, 15 | She "said" she'd decline (careful tense held throughout), signed 2 May, appendix found 8 Aug, acknowledged at the vote | holds | Tense discipline on "said I would decline" is airtight; the leave chronology is the one unclear seam (suggestion #7) |
| Character (hive-3 row-2 as rain barometer) | 3, 13, 15, 16 | Baseline 71 in/62 out; decline to 40/34 (5 Oct); 22/19 (19 Oct) | holds | Trajectory is consistent; only Wren's "On the first" phrasing wobbles (suggestion #4) |

## Craft-axis scores (1–5)

voice: 5 · structure: 4 · stakes: 5 · scene-work: 5 · ending: 4

## Density finding

Passage that earns its length: the Ch5 seeding-run radio sequence, from "Copy forty" through "She's gone. She's in the gully." — the uncorrected number chosen two pages earlier pays out in real time, and Tamsin's silence ("I did not correct it") is dramatized rather than explained; this is the novel's thesis executed as scene.

Passage that repeats a completed move: Ch14's rota training. The hall-transformation confession — hardest reader stands at the lectern, reads straight, then breaks — was already done definitively in Ch12; Ch14 restages it twice in close order (Pieter Vance, then Dellen). Both speeches are fine writing and the pay differs (Vance's fear, Dellen's inheritance), but the second instance delivers character depth without new dramatic information; the chapter would tighten by a third with one of the two beats cut or folded into rehearsal noise.

## Pass-3 only: findings ledger

| Finding # (from Pass 2) | Status: resolved / rebutted-accepted / still-open | Note |
|---|---|---|
| — | N/A (Pass 2 review) | |
