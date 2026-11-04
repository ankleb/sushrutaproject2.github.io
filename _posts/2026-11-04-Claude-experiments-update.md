---
layout: post
title: 'An Update to the Blog Post “Experiments with Claude” (17 July 2026)'
date: 2026-11-04
author: Jason Birch
description: Jason Birch compares Claude’s machine-assisted edition of Sūtrasthāna 6 with his own critical edition
tags: SuśrutaProject AI Claude
---

On 17 July 2026, Dominik Wujastyk posted [Experiments with Claude](https://sushrutaproject2.github.io/blog/2026/Claude-experiments/) on the Project’s blog,
reporting the preliminary results of an experiment in using Claude to edit *Suśrutasaṃhitā*,
Sūtrasthāna 6 (*Ṛtucaryā*). He asked Claude to study 23 chapters critically edited by the Suśruta
team, alongside the witnesses on which they are based, to derive a set of rules or patterns capturing their editorial practices, and then to apply those rules to Saktumiva's mechanical collation of chapter 1.6. The results were posted [here](https://sushrutaproject1.github.io/Sushrutasamhita_Saktumiva2/Claude/provisional-edition_sutrasthana-06_machine-assisted.xml). 

Since then, Jason Birch has critically edited chapter 1.6 on *ṛtucaryā* without consulting Claude’s
edition. He has recently compared his draft edition of the first 20 passages with Claude’s and offers the following general observations.

1. Claude improved on Saktumiva’s mechanical collation of the witnesses by adopting K in more instances where the witnesses differ. In at least one instance, it correctly chose a reading of K that was the *lectio difficilior* and wrote a footnote explaining why the reading is plausible.

2. Claude’s edition was limited by its inability to check the draft transcripts against the manuscripts. This might be possible in the future if Claude is given access to the manuscript images. Many of the defects in Claude’s edition resulted from mistakes in the draft transcripts; examples are given in the detailed comments below.

3. Claude often uncritically favoured K (perhaps because it was told that K is the most important witness). As a result, it adopted incorrect readings of K. In quite a few instances, these incorrect readings were errors in the draft transcript, which Claude failed to identify. For example, it adopted *triṃśatmuhūrttam* (instead of *triṃśanmuhūrttam*), *evauṣadhyau grīṣmaniḥsārā … bhavaty* (instead of *evauṣadhyo grīṣme … bhavanty*) and *śleṣmikāṇāṃ* (instead of *ślaiṣmikāṇān*). Further instances are noted below.

4. Claude included an additional passage in K that is not part of the original work and is marked as
an insertion in the TEI code of the draft transcript). This passage does not fit the syntax of the sentence into which it was inserted. It is a clear example of Claude uncritically accepting the reading of K.

5. Other problems include incorrect word division (e.g., *dvimāsike naivaṃ* instead of *dvimāsikenaivaṃ*), unnecessary footnotes, and incorrect punctuation of the edited text (although punctuation may not have been explicitly mentioned in the prompt).

The section "Significant differences" below gives concrete examples for each case.

## Conclusion

It is clear that Claude has something to offer; its edition was better than Saktumiva’s mechanical collation. When it can do OCR of the manuscripts, it may improve further on its current edition. Nonetheless, its present effort resembles that of Housman’s donkey-editor, who, stuck between two bundles of hay, escapes the paralysis by uncritically choosing one bundle, arbitrarily called the “best,” which in this case was the oldest manuscript, K {% cite hous-1937 -l xxxi %}.  

### References

{% bibliography --cited --group_by none %}

# Significant differences in 1.6.1–20

Significant differences between Claude’s and Birch’s editions of 1.6.1–20 are listed below.

### 1.6.3

Claude and Birch both adopt *saṅkalayati* and both write footnotes on this sentence, which is a *nirukti* of *kāla*. Claude’s footnote simply points out that K preserves the correct form *saṅkalayati* (as opposed to *saṅkālayati* in N and H). Birch considered this obvious and instead commented in his footnote on Ḍalhaṇa’s understanding of *kāla*.

### 1.6.5

Claude adopts *triṃśatmuhūrttam*, which is incorrect sandhi. K and N actually read *triṃśanmuhūrttam*, but the draft transcripts used by Claude had *triṃśatmuhūrttam* for these witnesses.

### 1.6.7

Claude did not insert an avagraha in *āpyāyate ’rkaḥ*. Claude and Birch both accept *balavattarā*, the reading of K<sup>pc</sup> and H, which is the *lectio difficilior*, and Claude adds a footnote explaining why this reading is plausible. Further on, however, Claude adopts *uttarottaraś ca*, K’s reading in the draft transcript, which does not make sense. In fact, K, H and the vulgate read *uttarottarañ ca*.

### 1.6.9

Claude adopts *varṣasaṃvatsaraḥ*, the reading of K<sup>pc</sup> in the draft transcript, which is unsatisfactory. K<sup>pc</sup> actually reads *varṣaḥ saṃvatsaraḥ*, which is better.

### 1.6.10

Claude reads *dvimāsike naivaṃ* instead of *dvimāsikenaivaṃ*, an incorrect word division. Further on, Claude adopts *sa vidāhāt*, the reading of K, H and N, even though these witnesses have a plural verb. Birch adopts the vulgate reading *vidāhāt*, which is better.

### 1.6.11

Claude incorrectly includes the passage *tatra … uttarāyaṇe*, which was added to K and breaks the syntax of the original sentence. Claude states in a footnote that the passage was added by a later hand, an observation probably based on the transcriber’s TEI markup rather than on direct examination of the manuscript. Further on, Claude adopts *evauṣadhyau grīṣmaniḥsārā … bhavaty*, K’s reading in the draft transcript, but K and H in fact read *evauṣadhyo grīṣme … bhavanty*, the correct reading, which Birch adopts. Claude’s footnote points out the problem with the singular verb, but explains that it understands *evauṣadhyau* as a dual subject.

### 1.6.13

Claude adopts *śleṣmikāṇāṃ*, an incorrect transcription of K, which (like N and the vulgate) reads *ślaiṣmikāṇān*. Claude also adopts *sañcayaprakopaśamā*, a reading wrongly attributed to K in the draft transcript, and then writes a footnote stating that the correct reading, *sañcayaprakopopaśamā*, is found in H and N. In fact, K has the same reading as H and N.

### 1.6.14

Claude adopts *haimanam*, the reading of K, and then writes an unnecessary footnote noting that H and N read *hemantam* and *hemanam* respectively.

### 1.6.15

Claude adopts *tūpayayujyamānāḥ*, an incorrect reading of K, but then states in a footnote that this reading is incorrect. The error is in the draft transcript of K. Birch corrected the transcript and adopted *tūpayujyamānāḥ*, the reading of K, N and H.

### 1.6.16

Claude adopts *tāsām*, the correct reading of K, and writes an unnecessary footnote explaining why.

### 1.6.19

Claude adopts K’s *uṣasyante* (a transcription error for *udhvaṃsyante*). The better reading is H’s *udhvasyante*.
