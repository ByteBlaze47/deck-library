# Japanese (Tokyo Standard) — N5 Sentence-Based Curriculum Blueprint

## 1. Total Scope Assessment

N5 is the entry tier of the JLPT framework, targeting roughly **800 core vocabulary items**, **100 kanji**, and **~150 discrete grammar patterns** (copula forms, the three verb conjugation groups, い/な-adjective inflection, core particles, and beginner sentence-final expressions).

For a sentence-based method to be effective, each vocabulary item and grammar pattern needs 3–5 contextual exposures (first-encounter, contrastive, negative-form, question-form, and mixed-review). Applying that ratio to the N5 inventory yields a working target of:

**~720 sentences**, split into **25 controlled batches** (average 20–40 sentences per batch).

Batch size is deliberately capped below 40 sentences regardless of theme, since the limiting factor for later AI-generation quality is *output length per call*, not linguistic difficulty — smaller batches prevent truncation and let each sentence receive full annotation (romaji/furigana, particle breakdown, translation).

## 2. Batch Breakdown Table

| Batch # | Core Theme / Situation | Grammatical/Syntactic Focus | Sentence Count |
|---|---|---|---|
| 1 | Greetings & Self-Introduction | は (topic marker), です copula | 25 |
| 2 | Numbers, Dates, Time | Native/Sino-Japanese numbers, time particle に | 30 |
| 3 | Family & People | Possessive の, in-group/out-group family terms | 25 |
| 4 | Existence (あります/います) | Animate vs. inanimate existence verbs, location に | 30 |
| 5 | Daily Routine Verbs — Present | Verb groups I/II/III, ます-form conjugation | 35 |
| 6 | Daily Routine Verbs — Past | ました / ませんでした | 30 |
| 7 | Object Marking & Transitive Verbs | を particle, strict SOV word order | 30 |
| 8 | い-Adjectives | Predicate conjugation, negation (~くない) | 30 |
| 9 | な-Adjectives | な-linking to nouns, negation (~じゃない) | 30 |
| 10 | Likes, Dislikes, Ability | が with 好き/嫌い/上手/下手 | 25 |
| 11 | Location & Directions | に vs で contrast, こ/そ/あ/ど location words | 30 |
| 12 | Shopping & Prices | Counters (つ/個/枚 etc.), ~をください | 30 |
| 13 | Food & Restaurant Ordering | て-form for ordering, polite requests | 30 |
| 14 | Comparison (Basic) | より, ~の方が | 25 |
| 15 | Demonstratives (こそあど系) | これ/それ/あれ/どれ vs この/その/あの/どの | 25 |
| 16 | Te-Form Formation | Conjugation rules across all three verb groups | 35 |
| 17 | Te-Form: Requests & Permission | ~てください, ~てもいいです | 30 |
| 18 | Te-Form: Prohibition & Sequencing | ~てはいけません, ~てから | 30 |
| 19 | Progressive/Resultant State | ~ています (ongoing action vs. resulting state) | 30 |
| 20 | Desire & Suggestion | ~たいです, ~ましょう, ~ませんか | 30 |
| 21 | Basic Potential | できる, 分かる, わかります | 20 |
| 22 | Giving & Receiving (Basic) | あげる / もらう / くれる directionality | 25 |
| 23 | Weather, Seasons, Hobbies | ~と思います (simple opinion) | 25 |
| 24 | Question Formation & Sentence-Final Particles | か, ね, よ nuance | 25 |

**Total: 680 sentences**

## 3. Linguistic Justification

- **Topic vs. subject (は vs が):** English has no equivalent split; batches 1–4 isolate は before が is introduced in batch 10, preventing early conflation.
- **Verb-final (SOV) order:** English learners default to SVO. Object-marking (Batch 7) and te-form batches (16–18) are placed only after learners are fluent with predicate-final sentence construction, so word order is drilled before it is complicated by clause-chaining.
- **Three-way verb conjugation system (Group I/godan, Group II/ichidan, Group III/irregular):** Unlike English's largely uniform verb morphology, Japanese requires stem-recognition. Batches 5, 6, and 16 isolate each group's conjugation pattern separately before mixing them in review.
- **Adjective type-switching (い vs な):** English adjectives don't inflect; Japanese い-adjectives conjugate like verbs while な-adjectives behave like nouns. Splitting Batches 8–9 prevents cross-contamination of negation rules.
- **Particle density:** に, で, を, の, と, も each carry distinct grammatical roles with no single English preposition equivalent — batches sequence one particle-pair contrast at a time (に vs で in Batch 11) rather than introducing all particles simultaneously.
- **Script-mixing (kanji/hiragana/katakana) is intentionally excluded from grammar batches** per your instruction, but sentence outputs will still model correct orthographic mixing since real-world exposure requires it.
