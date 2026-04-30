# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/skills/installer.py

Prompts

```
['install a skill from a .skill zip archive into the skills custom directory', 'safely extract a skill zip archive with security protections against directory traversal and zip bombs', 'check if a zip member path is absolute or contains directory traversal sequences', 'locate the skill root directory from extracted archive contents filtering out metadata', 'raise an error when attempting to install a skill that already exists in the custom directory', 'get the root path of the skills directory for the deer-flow project', 'load all skills from the skills directory including public and custom categories', 'load only enabled skills from the skills directory using extensions config', 'load skills from a custom path instead of the default skills directory', 'load skills without reading from config, using the default skills root path', 'create a custom skill by writing validated SKILL.md content to the custom skills directory', 'validate a skill name follows hyphen-case lowercase letters digits and hyphens only', "append a timestamped record to a skill's JSONL history file", "read all timestamped history records from a skill's JSONL history file", 'list all custom skills loaded from the skills custom directory', 'ensure a supporting file path is safe relative and within allowed skill subdirectories', 'atomically write skill markdown content to a file using a temporary file and rename', 'parse a SKILL.md file and extract YAML front-matter metadata into a Skill object', "parse a SKILL.md file with category 'public' or 'custom' and return a Skill object", "get the relative path string from the category root to a Skill's directory", "get the full container mount path for a Skill's directory given a base path", "get the full container path to a Skill's SKILL.md file given a base path", 'create a Skill dataclass instance with name, description, category, and path metadata', 'get the container path for a Skill instance mounted at a given base path', "get the full container file path to a Skill's SKILL.md file", "get the relative path string from a Skill's category root to its directory", 'get a readable string representation of a Skill instance with name, description, and category']
```

Usage

```
{'install_skill_from_archive': 'install a skill from a .skill zip archive into the skills custom directory', 'safe_extract_skill_archive': 'safely extract a skill zip archive with security protections against directory traversal and zip bombs', 'is_unsafe_zip_member': 'check if a zip member path is absolute or contains directory traversal sequences', 'resolve_skill_dir_from_archive': 'locate the skill root directory from extracted archive contents filtering out metadata', 'SkillAlreadyExistsError': 'raise an error when attempting to install a skill that already exists in the custom directory'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/skills/loader.py

Prompts

```
['install a skill from a .skill zip archive into the skills custom directory', 'safely extract a skill zip archive with security protections against directory traversal and zip bombs', 'check if a zip member path is absolute or contains directory traversal sequences', 'locate the skill root directory from extracted archive contents filtering out metadata', 'raise an error when attempting to install a skill that already exists in the custom directory', 'get the root path of the skills directory for the deer-flow project', 'load all skills from the skills directory including public and custom categories', 'load only enabled skills from the skills directory using extensions config', 'load skills from a custom path instead of the default skills directory', 'load skills without reading from config, using the default skills root path', 'create a custom skill by writing validated SKILL.md content to the custom skills directory', 'validate a skill name follows hyphen-case lowercase letters digits and hyphens only', "append a timestamped record to a skill's JSONL history file", "read all timestamped history records from a skill's JSONL history file", 'list all custom skills loaded from the skills custom directory', 'ensure a supporting file path is safe relative and within allowed skill subdirectories', 'atomically write skill markdown content to a file using a temporary file and rename', 'parse a SKILL.md file and extract YAML front-matter metadata into a Skill object', "parse a SKILL.md file with category 'public' or 'custom' and return a Skill object", "get the relative path string from the category root to a Skill's directory", "get the full container mount path for a Skill's directory given a base path", "get the full container path to a Skill's SKILL.md file given a base path", 'create a Skill dataclass instance with name, description, category, and path metadata', 'get the container path for a Skill instance mounted at a given base path', "get the full container file path to a Skill's SKILL.md file", "get the relative path string from a Skill's category root to its directory", 'get a readable string representation of a Skill instance with name, description, and category']
```

Usage

```
{'get_skills_root_path': 'get the root path of the skills directory for the deer-flow project', 'load_skills': 'load all skills from the skills directory including public and custom categories', 'load_skills_enabled_only': 'load only enabled skills from the skills directory using extensions config', 'load_skills_custom_path': 'load skills from a custom path instead of the default skills directory', 'load_skills_no_config': 'load skills without reading from config, using the default skills root path'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/skills/manager.py

Prompts

```
['install a skill from a .skill zip archive into the skills custom directory', 'safely extract a skill zip archive with security protections against directory traversal and zip bombs', 'check if a zip member path is absolute or contains directory traversal sequences', 'locate the skill root directory from extracted archive contents filtering out metadata', 'raise an error when attempting to install a skill that already exists in the custom directory', 'get the root path of the skills directory for the deer-flow project', 'load all skills from the skills directory including public and custom categories', 'load only enabled skills from the skills directory using extensions config', 'load skills from a custom path instead of the default skills directory', 'load skills without reading from config, using the default skills root path', 'create a custom skill by writing validated SKILL.md content to the custom skills directory', 'validate a skill name follows hyphen-case lowercase letters digits and hyphens only', "append a timestamped record to a skill's JSONL history file", "read all timestamped history records from a skill's JSONL history file", 'list all custom skills loaded from the skills custom directory', 'ensure a supporting file path is safe relative and within allowed skill subdirectories', 'atomically write skill markdown content to a file using a temporary file and rename', 'parse a SKILL.md file and extract YAML front-matter metadata into a Skill object', "parse a SKILL.md file with category 'public' or 'custom' and return a Skill object", "get the relative path string from the category root to a Skill's directory", "get the full container mount path for a Skill's directory given a base path", "get the full container path to a Skill's SKILL.md file given a base path", 'create a Skill dataclass instance with name, description, category, and path metadata', 'get the container path for a Skill instance mounted at a given base path', "get the full container file path to a Skill's SKILL.md file", "get the relative path string from a Skill's category root to its directory", 'get a readable string representation of a Skill instance with name, description, and category']
```

Usage

```
{'create_custom_skill': 'create a custom skill by writing validated SKILL.md content to the custom skills directory', 'validate_skill_name': 'validate a skill name follows hyphen-case lowercase letters digits and hyphens only', 'append_skill_history': "append a timestamped record to a skill's JSONL history file", 'read_skill_history': "read all timestamped history records from a skill's JSONL history file", 'list_custom_skills': 'list all custom skills loaded from the skills custom directory', 'ensure_safe_support_path': 'ensure a supporting file path is safe relative and within allowed skill subdirectories', 'atomic_write_skill': 'atomically write skill markdown content to a file using a temporary file and rename'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/skills/parser.py

Prompts

```
['install a skill from a .skill zip archive into the skills custom directory', 'safely extract a skill zip archive with security protections against directory traversal and zip bombs', 'check if a zip member path is absolute or contains directory traversal sequences', 'locate the skill root directory from extracted archive contents filtering out metadata', 'raise an error when attempting to install a skill that already exists in the custom directory', 'get the root path of the skills directory for the deer-flow project', 'load all skills from the skills directory including public and custom categories', 'load only enabled skills from the skills directory using extensions config', 'load skills from a custom path instead of the default skills directory', 'load skills without reading from config, using the default skills root path', 'create a custom skill by writing validated SKILL.md content to the custom skills directory', 'validate a skill name follows hyphen-case lowercase letters digits and hyphens only', "append a timestamped record to a skill's JSONL history file", "read all timestamped history records from a skill's JSONL history file", 'list all custom skills loaded from the skills custom directory', 'ensure a supporting file path is safe relative and within allowed skill subdirectories', 'atomically write skill markdown content to a file using a temporary file and rename', 'parse a SKILL.md file and extract YAML front-matter metadata into a Skill object', "parse a SKILL.md file with category 'public' or 'custom' and return a Skill object", "get the relative path string from the category root to a Skill's directory", "get the full container mount path for a Skill's directory given a base path", "get the full container path to a Skill's SKILL.md file given a base path", 'create a Skill dataclass instance with name, description, category, and path metadata', 'get the container path for a Skill instance mounted at a given base path', "get the full container file path to a Skill's SKILL.md file", "get the relative path string from a Skill's category root to its directory", 'get a readable string representation of a Skill instance with name, description, and category']
```

Usage

```
{'parse_skill_file': 'parse a SKILL.md file and extract YAML front-matter metadata into a Skill object', 'parse_skill_file_category': "parse a SKILL.md file with category 'public' or 'custom' and return a Skill object", 'Skill_skill_path': "get the relative path string from the category root to a Skill's directory", 'Skill_get_container_path': "get the full container mount path for a Skill's directory given a base path", 'Skill_get_container_file_path': "get the full container path to a Skill's SKILL.md file given a base path"}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/skills/types.py

Prompts

```
['install a skill from a .skill zip archive into the skills custom directory', 'safely extract a skill zip archive with security protections against directory traversal and zip bombs', 'check if a zip member path is absolute or contains directory traversal sequences', 'locate the skill root directory from extracted archive contents filtering out metadata', 'raise an error when attempting to install a skill that already exists in the custom directory', 'get the root path of the skills directory for the deer-flow project', 'load all skills from the skills directory including public and custom categories', 'load only enabled skills from the skills directory using extensions config', 'load skills from a custom path instead of the default skills directory', 'load skills without reading from config, using the default skills root path', 'create a custom skill by writing validated SKILL.md content to the custom skills directory', 'validate a skill name follows hyphen-case lowercase letters digits and hyphens only', "append a timestamped record to a skill's JSONL history file", "read all timestamped history records from a skill's JSONL history file", 'list all custom skills loaded from the skills custom directory', 'ensure a supporting file path is safe relative and within allowed skill subdirectories', 'atomically write skill markdown content to a file using a temporary file and rename', 'parse a SKILL.md file and extract YAML front-matter metadata into a Skill object', "parse a SKILL.md file with category 'public' or 'custom' and return a Skill object", "get the relative path string from the category root to a Skill's directory", "get the full container mount path for a Skill's directory given a base path", "get the full container path to a Skill's SKILL.md file given a base path", 'create a Skill dataclass instance with name, description, category, and path metadata', 'get the container path for a Skill instance mounted at a given base path', "get the full container file path to a Skill's SKILL.md file", "get the relative path string from a Skill's category root to its directory", 'get a readable string representation of a Skill instance with name, description, and category']
```

Usage

```
{'create_skill_dataclass': 'create a Skill dataclass instance with name, description, category, and path metadata', 'get_skill_container_path': 'get the container path for a Skill instance mounted at a given base path', 'get_skill_container_file_path': "get the full container file path to a Skill's SKILL.md file", 'get_skill_relative_path': "get the relative path string from a Skill's category root to its directory", 'repr_skill_instance': 'get a readable string representation of a Skill instance with name, description, and category'}
```

