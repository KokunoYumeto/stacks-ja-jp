# Evidence cards: fresh bounded reassessment, 2026-09-19

[Index and evidence labels](README.md)

The public chapter was read at commit `899c3a55fb45a5cde43595fafa0fefc049b63719`, SHA-256 `491787A453B45D5649B8BF9F9165D8EABE6D8FA270A93DC76A95EEF4DFED6560`. These cards do not claim a newly rebuilt PDF or a corpus-wide review.

## JA-BRAUER-001: retaining 斜体

**Evidence:** direct definition-level attestation, with an explicitly documented alternative.

[和久井道久, *代数の理論*, p. 11, bottom note](https://www2.itc.kansai-u.ac.jp/~wakui/AlgebraTheory_for_web.pdf#page=11) calls a unital ring with every nonzero element invertible `斜体 (skew field)`. The text and page image were freshly inspected; retained PDF SHA-256 `DB56A54995DD2360F2D6C63188675B88FCD4CBB25AD82D0836973F84C7013671`.

**Occurrence:** [English definition](https://github.com/stacks/stacks-project/blob/a04446e57ec1fbc252a871afcec7752fb2807b14/brauer.tex#L45-L50); [Japanese definition](https://github.com/KokunoYumeto/stacks-ja-jp/blob/899c3a55fb45a5cde43595fafa0fefc049b63719/editions/2026-09-19-full116/src/brauer.tex#L43-L47).

**Decision:** retain `斜体` in this definition. The attested definition matches the Stacks definition, so this is not a model-only guess. Do not replace it merely because another author favors a synonym.

**Alternative and limit:** [雪江明彦, *私の教科書の用語について*, §2, p. 1](https://www.math.kyoto-u.ac.jp/~yukie/yougo.pdf#page=1) explains a preference for `可除環` in the Wedderburn/Brauer setting. This is a real register alternative, not proof that `斜体` is an error. That essay was consulted by text extraction from the hash-bound PDF `E48BC23B784D47D753917C7C07B09B30612F2BB7241A2E79721E247A933EE0DA`; its previously retained page image renders Japanese characters as boxes and is **not** accepted as successful visual evidence.

**Release status:** the retained `斜体` is present in the linked public definition. **Confidence:** strong same-sense attestation; edition-wide synonym policy remains an editorial choice. Original audit occurrence: `P02-LSA-JA-CH11-B007`.

