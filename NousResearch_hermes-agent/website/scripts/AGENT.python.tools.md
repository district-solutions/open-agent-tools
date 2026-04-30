# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/website/scripts/extract-skills.py

Prompts

```
['create a list of skill metadata by extracting from local SKILL.md files in the repository', 'create a list of skill metadata by extracting from cached index JSON files', 'run the script to extract all skills and write them to website/src/data/skills.json', "create a consolidated skill list by merging small categories into 'other'", 'create a category label from a list of skill tags using a tag-to-category mapping', 'run the generate-skill-docs script to generate Docusaurus pages from SKILL.md files', 'build a bundled skills catalog markdown page with tables linking to per-skill pages', 'build an optional skills catalog markdown page with install instructions and per-skill links', 'render a Docusaurus markdown page from a SKILL.md file with frontmatter, metadata table, and escaped body', 'write the Docusaurus sidebar to nest all per-skill pages under Skills with Bundled and Optional categories']
```

Usage

```
{'create_extract_local_skills': 'create a list of skill metadata by extracting from local SKILL.md files in the repository', 'create_extract_cached_index_skills': 'create a list of skill metadata by extracting from cached index JSON files', 'run_extract_skills': 'run the script to extract all skills and write them to website/src/data/skills.json', 'create_consolidate_categories': "create a consolidated skill list by merging small categories into 'other'", 'create_guess_category': 'create a category label from a list of skill tags using a tag-to-category mapping'}
```

## File: NousResearch_hermes-agent/website/scripts/generate-skill-docs.py

Prompts

```
['create a list of skill metadata by extracting from local SKILL.md files in the repository', 'create a list of skill metadata by extracting from cached index JSON files', 'run the script to extract all skills and write them to website/src/data/skills.json', "create a consolidated skill list by merging small categories into 'other'", 'create a category label from a list of skill tags using a tag-to-category mapping', 'run the generate-skill-docs script to generate Docusaurus pages from SKILL.md files', 'build a bundled skills catalog markdown page with tables linking to per-skill pages', 'build an optional skills catalog markdown page with install instructions and per-skill links', 'render a Docusaurus markdown page from a SKILL.md file with frontmatter, metadata table, and escaped body', 'write the Docusaurus sidebar to nest all per-skill pages under Skills with Bundled and Optional categories']
```

Usage

```
{'run_generate_skill_docs': 'run the generate-skill-docs script to generate Docusaurus pages from SKILL.md files', 'build_catalog_md_bundled': 'build a bundled skills catalog markdown page with tables linking to per-skill pages', 'build_catalog_md_optional': 'build an optional skills catalog markdown page with install instructions and per-skill links', 'render_skill_page': 'render a Docusaurus markdown page from a SKILL.md file with frontmatter, metadata table, and escaped body', 'write_sidebar': 'write the Docusaurus sidebar to nest all per-skill pages under Skills with Bundled and Optional categories'}
```

