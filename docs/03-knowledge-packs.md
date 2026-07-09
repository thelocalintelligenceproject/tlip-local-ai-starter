# 03 - Knowledge Packs / Memory Import

> Status: coming soon. This is a draft outline, not the official TLIP guide yet.

For most community use, add documents before fine-tuning.

A knowledge pack is a folder of source material plus a manifest that explains
where it came from and how it should be used.

## Good Knowledge-Pack Contents

- Markdown notes
- PDFs
- meeting summaries
- resource maps
- FAQs
- local guides
- project docs
- public datasets with clear source links

## Minimum Manifest

Use `templates/knowledge-pack-manifest.yaml`.

The manifest should name:

- title,
- steward,
- sources,
- permissions,
- update date,
- allowed uses,
- private/sensitive material,
- and what should never be inferred from the documents.

## Rule

If a local search/RAG setup solves the problem, do not fine-tune yet.

Fine-tuning changes model behavior. A knowledge pack is easier to inspect,
correct, remove, and update.
