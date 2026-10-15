---
name: pisidian-research
description: Examine the Pisidian digital reference corpus, trace edition identifiers and source readings, assess coverage and prepare reproducible inscription research.
version: 0.3.1
---

# Pisidian evidence-first research

Start by asking for the research question and identifying the files you can actually read. Load the authority profile at `ai-skill/references/authority-profile.json`, current status, source register, rights matrix and bundle index. Request exact evidence file paths when absent; do not pretend that links, indices or filenames establish evidence access.

The canonical research files are in the repository; this interface is rebuildable. `data/reference/records.json` is an attributed eDiAna-derived digital reference layer under CC BY-SA 4.0, not an independently collated epigraphic edition. Distinguish catalog document IDs, response group titles, physical objects, source lines and analytical units. Join records by document ID; labels can collide. Disclose catalog/heading discrepancies and archival source versions.

Preserve source sentences, lacunae, uncertainty, references and row pointers. Source-provided morphology, translation and language assignments are source assertions, not adjudicated findings. Keep observation, transformation, computation, interpretation and AI inference distinct. Cite local record IDs, snapshot hashes, source URL, raw response pointers and edition references. Do not invent readings, locators or translations. No independent review is granted by passing machine checks.

Check indexed artifact hashes and `ai-skill/generated/source-state.json` before using a saved bundle; report stale data. The index is not the evidence. Offer one useful next action and exact file requirements when blocked. Follow `references/corpus-project-contract.md` for cross-corpus comparisons: explicit comparable units, source dependence, uncertainty and compatible transformations are required. No automatic transfer of sign values or linguistic relationships.

Consult `DATA-LICENSE-MATRIX.md`, `NOTICE` and `research/rights-evidence.json`. Preserve eDiAna contributor attribution, its hyperlink and CC BY-SA terms. Project-original noncommercial terms do not override upstream permissions. Independently acquired editions and images require their own rights evidence.

## Admission and research workflow

Read `research/admission-policy.json`, `analysis/record-admission.json` and `research/source-issues.json` before interpreting any record. Cite the record ID, exact JSON pointer, captured source version and edition locator if actually established. Empty citation lists must be disclosed. Treat bibliography search results as unresolved candidates. Read `research/edition-dependencies.json` before claiming independent corroboration. Preserve HTML editorial markup and combining marks; marker absence does not establish certainty. Keep `research/source-frontier.json` leads and scholarly proposals separate from admitted readings. Report blocked analytical admission and human review boundaries from `research/pre-expert-maximum.json`.

## Expert handoff
Read `review/handoff-manifest.json` and the relevant record in `review/packets.json`. Read linked checks in `research/source-checks.json` and access limitations in `research/source-access.json`. Keep source inspection separate from independent review. Generate a review request with the exact record hash and evidence fingerprint. Never invent reviewer identity or mark a pending packet reviewed. A structurally valid review is not authenticated expertise and must not automatically admit a canonical reading.

## Continue source work

Use `research/source-worklist.json` to account for every frozen citation and record. A linked source check is a targeted inspection, not full collation or independent review. Edition numbers can change between publications; require textual and bibliographic concordance before joining records. Public download access does not establish redistribution rights. Report remaining acquisition and line-level work explicitly; do not call the corpus complete.

## Collection source work and review handoff

Read `research/collection-work-ledger.json` and `review/collection-packet.json` when preparing a source-work plan or expert request. Check their evidence fingerprint against current inputs with `python scripts/build_collection_handoff.py`. Select exact record keys and retain native units; overlapping views are not additional physical objects. Follow native review links for scientific decisions and admission. Ledger coverage does not establish completed collation, independent review or a terminal pre-expert ceiling. Use `review/collection-decision-template.json` for revision-bound submissions; structural validation cannot authenticate the reviewer or approve the science. Keep restricted local A/B derivatives local.

The frozen eDiAna reference now has an EpiDoc view of all 54 native document records / 99 nonempty rows. Read `docs/EPIDOC-REFERENCE.md`, `interchange/export-manifest.json` and `analysis/upstream-epidoc-validation.json`. Every native record field and exact source row is reversible; source CC-BY-SA-4.0 and unreviewed status remain explicit. Full raw-source annotations, physical geometry, primary-edition collation and scholarly acceptance are outside this view. Upstream conformance is scoped to this frozen reference layer.

## Enforced assertion, dependency and bundle integrity

Read `docs/AI-INTEGRITY.md` and the required `research/cross-corpus-dependencies.json` before source counts or cross-corpus analysis. Use qualified assertion views when provided; original source literals must travel with their reconciliation, uncertainty and identity context. The dependency register does not certify physical identity or linguistic affinity. Shared catalogue references and duplicated digital sources are not independent witnesses. Missing links mean unknown, not independent. `scripts/check_cross_corpus_dependencies.py` screens declared record selections and rejects pooled physical/witness counts and phonetic transfer. Native AI bundle validation checks the dependency projection and local evidence hashes. Bundle publication validates the exact source parent and never rebases or force-pushes the validated artifact. Software and packaging checks do not establish expert or model-behavior acceptance.

Use only `sync-ai-skill.yml` for automatic bundle publication. The native integrity workflow validates evidence without a second publisher. Reject any proposed post-validation rebase of generated artifacts.

## Corpus-native evidence and alternatives

Read `docs/EVIDENCE-AND-ALTERNATIVES.md`, `research/evidence-query-profile.json` and `analysis/evidence-query-coverage.json` for evidence or competing-reading questions. Use `scripts/evidence_query.py` with exact native IDs and an explicit collection when ambiguous. Preserve `native_record`, every uncertainty/editorial mark, source attribution, locator, inspection status and rights. Cite artifact path, JSON pointer and SHA-256; hashes certify bytes only. Treat explicitly linked records as declared ID associations, not physical certification or independent witnesses. Context resources have corpus-level scope and are not automatically about the queried record. Distinguish a named source reading from a legacy queue label, uninspected bibliographic lead, count convention or hypothesis. Do not infer a count of collated alternative pairs or independent witnesses from searchable rows; those metrics remain unknown. Report the native units and scope of each view separately, and defer to the corpus-specific limits. No new readings, expert acceptance or decipherment follows from this interface.

## Bounded attribution review (2026-10-15)

Read `docs/ATTRIBUTION-REVIEW.md` and `research/attribution-review.json` before describing a dispute or source comparison. Run `python scripts/attribution_review.py --case ID` with the referenced evidence available. Preserve complete native evidence and distinguish reading, interpretation, classification, count, identity and representation questions. This checkpoint reviews pinned repository packets; it does not repeat their primary consultation or grant independent review. Inherit the exact author/publication, locator, consultation limits and dependence from each pointer; missing fields remain unknown. Use the case-specific remaining work. Do not count register entries or apparatus notes as fully attributed pairs, physical objects or independent witnesses.

All29 existing source checks plus the bibliography-key issue; numbering, editorial o/theta and e/s conventions, segmentation and classification remain separate. No invented disagreement register.
