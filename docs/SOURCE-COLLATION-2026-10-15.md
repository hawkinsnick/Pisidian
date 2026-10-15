# Selected source collation — 2026-10-15

Four selected comparisons. Preserve the2023 edition line/vacat assertions, Adiego2017 circumflex conventions and Adiego2012 questioned restoration separately from linguistic interpretation, frozen source strings and physical sign adjudication.

Scope: selected source-located tasks. This is a fresh, bounded publication check with a separate consultation state for every source. It is not a complete critical edition, exhaustive literature search, independent expert review or project examination of an ancient object.

## Findings and remaining work

| Task | Source observations | Remaining work |
|---|---|---|
| PIS-N25-2023 | The p.188 no.2 edition prints three name groups and a final vacat marker. The following apparatus contrasts earlier segmentation; the proposed grammatical relation is an interpretation. | Preserve the marker separately from letters; inventory6.9.82 is a2023 source assertion, not current object certification. Sign/photograph assessment remains open. |
| PIS-N24-2023 | The p.190 no.7 edition has two printed lines with a final vacat marker; the captured reference has a single source row. Name/gender interpretation must be evaluated separately from the proposed letters and layout. | Retain two-line layout as an edition assertion, not a certified physical line map. Inventory6.7.82 remains dated source metadata. |
| PIS-KESME2-AMBIGUITIES | On pp.2–3, Adiego explicitly uses circumflex-o for o/theta alternatives and circumflex-e for e/s alternatives. His Latin rendering and segmentation are analytical conventions over Greek-script evidence. | Do not reinterpret either circumflex as a secure phoneme or normalize the frozen mixed-script source characters. Keep symbol identity, source uncertainty and word segmentation separate. |
| PIS-ADIEGO2012-N37 | The p.19 proposed table has eight onomastic formulas, with the third middle name bracketed and questioned. The count depends on treating Pigerdotaris as a compound genitive; it is not an independently observed person count. | Do not strip the question mark from the table’s restoration or convert formula groups into certain individuals; full edition/object assessment remains open. |

## Consultation receipts

| Source | Modality | Inspected locus | Limits |
|---|---|---|---|
| [Asuman Coşkun Abuagla (2023), Nominative and Genitive Endings of Some Epichoric Personal Names in Light of Inscriptions from Tymbriada, Adalya26,185–196.](https://akmedmedia.ku.edu.tr/Adalya/Adalya_2023/Coskun_Abuagla_Offprint.pdf) | DIRECT_RENDERED_PDF_PAGE_IMAGES | p.188, no.2 and n.12 (PDF ordinal10); p.190, no.7 and n.25 (PDF ordinal12) | Printed edition and discussion inspected; museum inventories are dated publication assertions. Figure-level damaged-sign and current-inventory verification remain open. |
| [Ignasi-Xavier Adiego (2012), Minima Pisidica: nota sobre la estructura de una inscripción pisidia de Timbriada,17–26.](https://forumeditrice.it/percorsi/lingua-e-letteratura/studi-in-onore/per-roberto-gusmani/minima-pisidica-nota-sobre-la-estructura-de-una/download_capitolo) | DIRECT_RENDERED_PDF_PAGE_IMAGES | p.19, proposed eight-formula table and following discussion (PDF ordinal4) | Publication inspection only; no project object autopsy or independent review. |
| [Ignasi-Xavier Adiego (2017), The longest Pisidian inscription (Kesme2), Journal of Language Relationship15,1–18.](https://www.jolr.ru/files/(202)jlr2017-15-1-2(1-18).pdf) | DIRECT_RENDERED_PDF_PAGE_IMAGES | p.2, reproduced edition and graphical problems (PDF ordinal2); p.3, conventions, transliteration and segmentation assumptions (PDF ordinal3) | Publication inspection only; no project object autopsy or independent review. |

The JSON packet retains bibliographic identities, exact native comparison/check pointers, PDF byte hashes where acquired, and page-render hashes for inspected pages. PDF files, rendered page images and full protected editions are not redistributed. A web-text consultation has no PDF byte hash and cannot certify diacritics or figure details. Access failures are route-specific observations, not proof that lawful copies do not exist.

## Reproduce the integrity checks

```sh
python scripts/source_collation.py --check
python scripts/source_collation.py --case 'PIS-N25-2023'
python -m unittest discover -s scripts -p test_source_collation.py
```

Researchers with a lawfully obtained copy can match it to an inspected PDF receipt using `python scripts/source_collation.py --verify-source SOURCE_ID /path/to/source.pdf`. A byte match establishes source version, not scholarly correctness or permission to redistribute it.

Canonical/frozen readings are unchanged. A correction to project source-attribution notation does not accept a reading. See `research/source-collation-2026-10-15.json` for case-specific source voices, uncertainty carriers and remaining work.
