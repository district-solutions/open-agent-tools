# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/skills/productivity/powerpoint/scripts/add_slide.py

Prompts

```
['create a new PowerPoint slide from a layout file in an unpacked PPTX directory', 'duplicate an existing PowerPoint slide in an unpacked PPTX directory', 'register a new slide in the [Content_Types].xml of an unpacked PPTX package', 'add a slide relationship entry to presentation.xml.rels in an unpacked PPTX package', 'compute the next available slide ID from presentation.xml in an unpacked PPTX package', 'run clean_unused_files on an unpacked PPTX directory to remove all unreferenced files', "review remove_orphaned_slides to delete slides not listed in the presentation's sldIdLst and their relationships", 'summarize remove_trash_directory to remove the [trash] directory and its contents from an unpacked PPTX', 'refactor update_content_types to remove Content-Type overrides for deleted files from [Content_Types].xml', 'test get_referenced_files to scan all .rels files and return a set of referenced file paths']
```

Usage

```
{'create_slide_from_layout': 'create a new PowerPoint slide from a layout file in an unpacked PPTX directory', 'duplicate_slide': 'duplicate an existing PowerPoint slide in an unpacked PPTX directory', 'add_to_content_types': 'register a new slide in the [Content_Types].xml of an unpacked PPTX package', 'add_to_presentation_rels': 'add a slide relationship entry to presentation.xml.rels in an unpacked PPTX package', 'get_next_slide_id': 'compute the next available slide ID from presentation.xml in an unpacked PPTX package'}
```

## File: NousResearch_hermes-agent/skills/productivity/powerpoint/scripts/clean.py

Prompts

```
['create a new PowerPoint slide from a layout file in an unpacked PPTX directory', 'duplicate an existing PowerPoint slide in an unpacked PPTX directory', 'register a new slide in the [Content_Types].xml of an unpacked PPTX package', 'add a slide relationship entry to presentation.xml.rels in an unpacked PPTX package', 'compute the next available slide ID from presentation.xml in an unpacked PPTX package', 'run clean_unused_files on an unpacked PPTX directory to remove all unreferenced files', "review remove_orphaned_slides to delete slides not listed in the presentation's sldIdLst and their relationships", 'summarize remove_trash_directory to remove the [trash] directory and its contents from an unpacked PPTX', 'refactor update_content_types to remove Content-Type overrides for deleted files from [Content_Types].xml', 'test get_referenced_files to scan all .rels files and return a set of referenced file paths']
```

Usage

```
{'run_clean_unused_files': 'run clean_unused_files on an unpacked PPTX directory to remove all unreferenced files', 'review_remove_orphaned_slides': "review remove_orphaned_slides to delete slides not listed in the presentation's sldIdLst and their relationships", 'summarize_remove_trash_directory': 'summarize remove_trash_directory to remove the [trash] directory and its contents from an unpacked PPTX', 'refactor_update_content_types': 'refactor update_content_types to remove Content-Type overrides for deleted files from [Content_Types].xml', 'test_get_referenced_files': 'test get_referenced_files to scan all .rels files and return a set of referenced file paths'}
```

