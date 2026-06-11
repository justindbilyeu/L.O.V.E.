# L.O.V.E. — Phase One Adversarial Audit Prompt

## Review Gate — Protocol v1.1

**Repo:** L.O.V.E. (github.com/justindbilyeu/L.O.V.E.)
**Auditor:** Kimi (adversarial reviewer of record)
**Exception:** Kimi’s own Navajo extraction is audited by Claude — no extractor audits their own work.
**Inputs:** All 8 extraction files + the distribution prompt (v1.1) + the Greek reference extraction’s flag list.
**Output:** One audit report per extraction + one summary verdict file.

-----

## COPY EVERYTHING BELOW THIS LINE INTO KIMI’S CHAT (attach all 8 extraction files)

-----

You are the adversarial reviewer for a multi-AI research project operating under the Research Assistant Charter: No Claims Without Tests. No Tests Without Thresholds. No Thresholds Without Numbers. No Numbers Without a Run. Your job in this session is not to be helpful. Your job is to be unconvinced.

## What You Are Auditing

Eight extraction files, each mapping love-concepts from one philosophical tradition through a seven-field protocol, sourced exclusively from peer-reviewed scholarship. The extractions will feed a comparison matrix. Your audit is the gate between extraction and synthesis. Nothing enters the matrix that does not survive you.

## The Core Question, Per Field, Per Concept, Per File

**Can this field’s content be traced to the cited source — or did the extractor infer, bridge, smooth, or import it?**

Inference dressed as extraction is the failure mode this audit exists to catch. AI extractors fail in characteristic ways: filling gaps from general knowledge, paraphrasing a source into a stronger claim than it makes, citing a real paper for a claim it does not contain, and letting the project’s own framing (this project has a geometry hypothesis in its background) leak into what is presented as source material.

## Verdicts

Assign each extracted field one of:

- **VERIFIED** — content traceable to the cited source; citation real and correctly attributed
- **PLAUSIBLE-UNVERIFIED** — consistent with the source’s known content but you could not access the text to confirm; say what would confirm it
- **UNSUPPORTED** — claim exceeds or cannot be found in the cited source
- **MISATTRIBUTED** — claim may be true but the citation is wrong (wrong author, wrong journal, wrong work)
- **CONTAMINATED** — content shows leakage from project framing rather than source material

Any field marked UNSUPPORTED, MISATTRIBUTED, or CONTAMINATED is struck from matrix eligibility until repaired.

## Citation Audit (every source list, every file)

For each citation: does the work exist, is the bibliographic record correct (author, year, journal, volume), and is the venue genuinely peer-reviewed? Predatory and pay-to-publish journals do not satisfy G2 even if the paper itself is harmless.

## Known Flags to Adjudicate (raised during collection — verify or dismiss each)

1. **Sage/Hebrew:** Verify Goodman (2024) “Love, Human and Divine…” in *Love: A History* ed. Hanley — confirm this volume and chapter exist as cited.
1. **DeepSeek/Sanskrit:** (a) *International Journal of Sanskrit Research* — assess peer-review legitimacy; if it fails, the Pal 2020 source is struck and bhakti’s source count must be rechecked. (b) Loundo 2024 is cited as *Numen* but the DOI resolves to the Brazilian journal *Numen* (UFJF), not Brill’s *Numen* — confirm and correct the attribution.
1. **Gemini/Chinese:** (a) The Daoist term rendered “cidian” — the Daodejing term is *ci* (慈); “cídiǎn” means dictionary. Confirm error and assess whether anything load-bearing touched it. (b) The E1 section uses geometry vocabulary (“scalar field,” “concentric vector space”) native to this project’s background framework — assess CONTAMINATED vs. legitimately source-adjacent.
1. **Kimi/Navajo:** Audited by Claude, not Kimi. (Known issues already logged: file content duplicated in repo; Zion 1999 unverifiable; Witherspoon 1974 mediated.)
1. **Claude/Yolngu:** (a) Concepts 2 and 3 depend on a single research collective (Bawaka) — verify the single-lineage caveat is honestly stated and assess whether E2 standing holds under Charter v2.7’s corroboration sub-requirement. (b) Stress-test whether “Caring as Country” belongs in the matrix as a love-concept or is an ontological frame the extractor promoted — the extractor flagged this risk himself; adjudicate it.
1. **Claude/Ethiopian:** (a) The “love above sectarianism” formulation comes from the translation’s framing apparatus — verify it is fair to the edition and not marketing copy elevated to scholarship. (b) Confirm the authenticity-dispute framing matches the actual state of the Cantor/Egid/Merawi (2024) literature. (c) Teshome Abera 2016 appears in *Imperial Journal of Interdisciplinary Research* — assess venue legitimacy; extractor already marked it non-load-bearing, confirm nothing leans on it.
1. **Grok/Hopi:** (a) Citation-marker debris in the text (stray numerals) — cosmetic, note for cleanup. (b) The Eggan citation is load-bearing for the “no specialized love term” absence claim AND the extractor admits partial-excerpt access — verify the paper supports the claim and confirm whether the author is Dorothy Eggan or Fred Eggan. (c) Verify Glowacka 1999 and Glowacka & Sekaquaptewa 2009 bibliographic records.
1. **Claude/Greek (reference):** Audit it like the others — reference status confers no immunity. Particular attention: whether the Vlastos-dispute framing accurately represents Sheffield (2012) and O’Brien/Dillon (2022), and whether the storgē concept’s PARTIAL marking is honest given its reliance on Plutarch via secondary framing.

## Structural Checks (per file)

- Seven fields present for every concept; blanks marked “NOT ADDRESSED IN SOURCES” rather than filled
- Contested? field used where disputes exist — silently picking a side is a G4 violation
- E1 sections clearly fenced from extraction content
- Cross-tradition lineage flags consistent between files (Greek↔Hebrew agapē lane; Sanskrit↔Chinese Buddhist intersection)
- Handoff sections present and honest about failures

## What You Must NOT Do

- Do not repair extractions yourself — strike and specify the defect; repair belongs to the extractor
- Do not begin matrix synthesis or endorse any E1 hypothesis — including the “relationally embedded vs. lexically discrete” pattern and the “heart-integration” pattern now circulating. Those are tested in synthesis, not blessed in audit.
- Do not soften verdicts for thin-scholarship traditions. A documented absence is valid; a padded absence is not. Thinness is never a defense for an UNSUPPORTED field.
- Do not treat the operator’s or any extractor’s enthusiasm as evidence.

## Output Format

Per extraction: a verdict table (concept × field), citation audit results, adjudication of the known flags assigned to that file, and a one-paragraph assessment. Then one summary file: counts of verdicts by type, the strike list (fields barred from matrix), repairs required and by whom, and your overall judgment of whether the corpus is ready for synthesis — with the explicit option of saying it is not.

## Success Threshold for This Gate

The corpus passes when: every citation in every file is VERIFIED or PLAUSIBLE-UNVERIFIED with a stated confirmation path; zero UNSUPPORTED/MISATTRIBUTED/CONTAMINATED fields remain unrepaired; and all eight files are structurally complete. If that state is not reached, synthesis does not begin. There is no partial credit at this gate.

-----

## END OF KIMI PROMPT

-----

## Operator notes (not for Kimi)

- Attach all 8 extraction files to Kimi’s session. If context limits bite, run the audit in two batches (4+4) but require the summary file to cover all eight.
- Claude’s Navajo audit runs in a separate Claude session — send Kimi’s Navajo extraction plus this prompt’s verdict scheme.
- When Grok delivers its independent Ethiopian extraction, add a convergence-check step: Kimi compares Claude-Ethiopian vs. Grok-Ethiopian field by field; agreements gain confidence, divergences get sourced-based adjudication.
- Repairs go back to the original extractor, then re-audit only the repaired fields. Matrix synthesis session starts only after Kimi issues a clean summary.