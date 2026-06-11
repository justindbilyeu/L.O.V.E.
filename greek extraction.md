# L.O.V.E. — Phase One Reference Extraction

## Tradition 1 of 8: GREEK

**Extractor:** Claude (reference run)
**Date:** 2026-06-11
**Status:** Complete — flagged ambiguities at bottom
**Protocol version:** Phase One Search Protocol v1.0

-----

## Sources (G2-compliant)

1. Vlastos, G. (1973). “The Individual as Object of Love in Plato.” *Platonic Studies*, Princeton University Press.
1. Sheffield, F. (2012). “The Symposium and Platonic Ethics: Plato, Vlastos, and a Misguided Debate.” *Phronesis* 57(2): 117–141.
1. Price, A.W. “Love and the Individual in Plato’s Phaedrus.” *Classical Quarterly* (Cambridge).
1. O’Brien, C.S. & Dillon, J. (2022). “The Selfishness of Platonic Love?” In *Platonic Love from Antiquity to the Renaissance*, Cambridge University Press.
1. Nygren, A. (1930/1953). *Agape and Eros*. (Plus published critiques: Journal of Moral Theology 1(2), 2012; Springer, *Philia and Agape: Ancient Greek Ethics of Friendship and Christian Theology of Love*, 2021.)
1. Aristotle, *Nicomachean Ethics* VIII–IX, as analyzed in Internet Encyclopedia of Philosophy, “Philosophy of Love” + Springer chapter above.

**Source count: 6 (protocol minimum: 2) ✓**

-----

## Extraction: Four concepts within the Greek tradition

### Concept 1: ERŌS (ἔρως)

|Field                |Extraction                                                                                                                                                                                                                                                                                                                          |
|---------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**Tradition**        |Greek (Platonic)                                                                                                                                                                                                                                                                                                                    |
|**Love concept**     |Erōs — passionate, desiring love                                                                                                                                                                                                                                                                                                    |
|**Core claim**       |Erōs is desire for what one lacks; it is the motive force that drives the soul’s ascent from particular beautiful bodies toward Beauty itself.                                                                                                                                                                                      |
|**Mechanism**        |Lack → desire → pursuit → ascent. Diotima’s ladder: love of one body → all bodies → souls → practices → knowledge → the Form of Beauty. Desire is generative (“birth in beauty”).                                                                                                                                                   |
|**Cost**             |CONTESTED — see Flag 1. On Vlastos’s reading, the cost is borne by the *beloved*: the individual is loved only as an instantiation of qualities, a rung on the ladder, and is in principle replaceable. On the O’Brien/Dillon and Sheffield readings, erōs involves reciprocity and mutual ascent, so the cost is shared discipline.|
|**Protection target**|Not protective in structure — erōs protects the *ascent*, not the beloved. It aims at the lover’s relation to the Good.                                                                                                                                                                                                             |

### Concept 2: PHILIA (φιλία)

|Field                |Extraction                                                                                                                                                                                                                                         |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**Tradition**        |Greek (Aristotelian)                                                                                                                                                                                                                               |
|**Love concept**     |Philia — friendship-love, extending to family, polis, and civic bonds                                                                                                                                                                              |
|**Core claim**       |Philia in its complete form is mutual goodwill between virtuous persons who wish good to each other *for the other’s own sake*.                                                                                                                    |
|**Mechanism**        |Reciprocity + recognition. Aristotle distinguishes friendships of utility, pleasure, and virtue; only the third is complete, because it loves the friend’s character (their essence), not their incidental benefits. Requires shared life and time.|
|**Cost**             |Time, scarcity (complete philia is possible with only a few), and proportionality — Aristotle holds that in unequal friendships, love should be proportional to merit.                                                                             |
|**Protection target**|The friend as a particular, non-replaceable person — and through civic philia, the polis itself.                                                                                                                                                   |

### Concept 3: AGAPĒ (ἀγάπη)

|Field                |Extraction                                                                                                                                                                                                 |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**Tradition**        |Greek (term) / Judeo-Christian (systematization) — see Flag 2                                                                                                                                              |
|**Love concept**     |Agapē — unconditional, self-giving love                                                                                                                                                                    |
|**Core claim**       |Agapē loves independently of the merit or value of its object; on Nygren’s influential formulation, erōs recognizes value and therefore loves, while agapē loves and thereby *creates* value in its object.|
|**Mechanism**        |Unmotivated gift. It does not respond to qualities; it confers worth. Aquinas’s compression: “to will the good of another.” Directionally downward/outward (God→human as template, then human→human).      |
|**Cost**             |Self-sacrifice without expectation of return; renunciation of reciprocity as a condition.                                                                                                                  |
|**Protection target**|The other — universally, without filtering by kinship, merit, or relation.                                                                                                                                 |

### Concept 4: STORGĒ (στοργή)

|Field                |Extraction                                                                                                                                                                                                |
|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**Tradition**        |Greek                                                                                                                                                                                                     |
|**Love concept**     |Storgē — natural familial affection                                                                                                                                                                       |
|**Core claim**       |Storgē is instinctive attachment arising from familiarity and shared life, paradigmatically parent–child.                                                                                                 |
|**Mechanism**        |Proximity + time + biological bond. Not chosen; grows out of household co-existence. Plutarch’s observation: parental storgē makes even timid creatures bold in defense of offspring.                     |
|**Cost**             |Risk of self — the parent endangers itself for the child.                                                                                                                                                 |
|**Protection target**|Offspring / kin. The most explicitly *protective* of the four Greek loves.                                                                                                                                |
|**Note**             |Thinnest scholarly literature of the four — most analysis is via Plutarch and later (C.S. Lewis’s *The Four Loves* is the common modern frame but is not peer-reviewed scholarship). Field marked PARTIAL.|

-----

## Flags (G4 ambiguity log)

**FLAG 1 — Internal scholarly dispute is the norm, not the exception.**
The protocol assumed each tradition yields extractable definitions. It does — but the *cost* field for erōs cannot be filled with one answer, because the scholarship is an active 50-year argument (Vlastos 1973 vs. Nussbaum, Price, Sheffield, O’Brien/Dillon). Protocol amendment proposed: add a seventh field, **“Contested?”** (yes/no + one-line description of the dispute). Otherwise extractors will silently pick a side, and the matrix will encode invisible interpretive choices.

**FLAG 2 — Concept/tradition boundaries leak.**
Agapē is a Greek *word* but its operational definition was built largely by Christian theology (Nygren, Aquinas), which overlaps our Hebrew tradition lane (hesed/ahavah → agapē lineage). The Hebrew extractor must coordinate with this extraction or we will double-count or contradict. Protocol amendment proposed: extractors must flag cross-tradition lineage explicitly.

**FLAG 3 — One tradition ≠ one definition.**
Greek yielded four distinct concepts with four distinct mechanisms. The comparison matrix should be built at the *concept* level, not the tradition level, with tradition as a grouping variable. Otherwise “Greek” collapses four different curvatures into one cell.

**FLAG 4 — Nygren’s dichotomy is load-bearing but contested.**
The cleanest mechanism contrast in the whole extraction (erōs recognizes value / agapē creates value) comes from Nygren 1930, and published critiques argue his method is unsound. We can use the contrast as a *hypothesis generator* but should not treat it as settled scholarship (E2 with an asterisk, not E2 clean).

-----

## Early pattern note (NOT a finding — hypothesis only, E1)

Across the four Greek concepts, the extraction suggests at least three distinct structural axes:

1. **Direction of value**: love responds to value (erōs, philia) vs. confers value (agapē)
1. **Replaceability of the beloved**: replaceable-in-principle (erōs, on Vlastos) vs. irreplaceable (philia, storgē)
1. **Condition of reciprocity**: required (philia) vs. independent (agapē, storgē)

If these axes survive the other seven traditions, they are candidate “load-bearing properties.” Decisive test: do non-Western traditions encode the same axes, or different ones entirely? Hopi/Navajo/Yolngu relational frameworks are the strongest potential falsifiers, since their concepts may not separate lover/beloved the way Greek grammar does.