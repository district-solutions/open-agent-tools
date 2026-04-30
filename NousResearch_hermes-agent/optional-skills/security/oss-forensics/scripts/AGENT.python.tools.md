# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/optional-skills/security/oss-forensics/scripts/evidence-store.py

Prompts

```
['add a piece of evidence to the OSS forensics evidence store with source, content, type, and optional actor and URL', 'list all evidence entries in the store, optionally filtered by type or actor', 'verify SHA-256 integrity of all evidence entries and report any mismatches', 'search evidence entries by keyword across content, source, actor, and URL fields', 'export the full evidence registry and chain of custody as a Markdown table to stdout', 'get investigation statistics including total count, breakdown by type and verification, and unique actors']
```

Usage

```
{'add_evidence_entry': 'add a piece of evidence to the OSS forensics evidence store with source, content, type, and optional actor and URL', 'list_evidence_entries': 'list all evidence entries in the store, optionally filtered by type or actor', 'verify_evidence_integrity': 'verify SHA-256 integrity of all evidence entries and report any mismatches', 'query_evidence_by_keyword': 'search evidence entries by keyword across content, source, actor, and URL fields', 'export_evidence_as_markdown': 'export the full evidence registry and chain of custody as a Markdown table to stdout', 'get_evidence_summary': 'get investigation statistics including total count, breakdown by type and verification, and unique actors'}
```

