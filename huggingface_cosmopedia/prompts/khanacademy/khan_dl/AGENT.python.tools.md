# Agent Python Tools

- repo: huggingface/cosmopedia
- repo_uri: https://github.com/huggingface/cosmopedia

## File: huggingface_cosmopedia/prompts/khanacademy/khan_dl/khan_dl.py

Prompts

```
['use KhanDL to download a Khan Academy course by URL and return its title, unit titles, and subunits', 'use KhanDL to fetch all course names and URLs for a given Khan Academy domain page', 'use KhanDL to generate file path slugs for all video lessons in a Khan Academy course', 'use KhanDL to retrieve URLs for every course across all Khan Academy domains', 'use KhanDL to reset all course state variables to their initial empty values', 'run khan-dl in interactive mode to select and download a Khan Academy course', 'run khan-dl to download a specific Khan Academy course by providing its URL', 'run khan-dl to download all courses from all domains and save to khan_courses.json', 'review the set_log_level function that configures logging verbosity from 1 to 3', 'review the main function that parses CLI args for interactive, course URL, or all modes']
```

Usage

```
{'download_khan_course': 'use KhanDL to download a Khan Academy course by URL and return its title, unit titles, and subunits', 'get_khan_courses_by_domain': 'use KhanDL to fetch all course names and URLs for a given Khan Academy domain page', 'get_khan_course_slugs': 'use KhanDL to generate file path slugs for all video lessons in a Khan Academy course', 'get_all_khan_courses': 'use KhanDL to retrieve URLs for every course across all Khan Academy domains', 'reset_khan_dl_state': 'use KhanDL to reset all course state variables to their initial empty values'}
```

## File: huggingface_cosmopedia/prompts/khanacademy/khan_dl/main.py

Prompts

```
['use KhanDL to download a Khan Academy course by URL and return its title, unit titles, and subunits', 'use KhanDL to fetch all course names and URLs for a given Khan Academy domain page', 'use KhanDL to generate file path slugs for all video lessons in a Khan Academy course', 'use KhanDL to retrieve URLs for every course across all Khan Academy domains', 'use KhanDL to reset all course state variables to their initial empty values', 'run khan-dl in interactive mode to select and download a Khan Academy course', 'run khan-dl to download a specific Khan Academy course by providing its URL', 'run khan-dl to download all courses from all domains and save to khan_courses.json', 'review the set_log_level function that configures logging verbosity from 1 to 3', 'review the main function that parses CLI args for interactive, course URL, or all modes']
```

Usage

```
{'run_interactive_download': 'run khan-dl in interactive mode to select and download a Khan Academy course', 'run_download_course_url': 'run khan-dl to download a specific Khan Academy course by providing its URL', 'run_download_all_courses': 'run khan-dl to download all courses from all domains and save to khan_courses.json', 'review_set_log_level': 'review the set_log_level function that configures logging verbosity from 1 to 3', 'review_main_cli': 'review the main function that parses CLI args for interactive, course URL, or all modes'}
```

