# Agent Python Tools

- repo: facebookresearch/sweetrl
- repo_uri: https://github.com/facebookresearch/sweet_rl

## File: facebookresearch_sweetrl/sweet_rl/utils/code_utils.py

Prompts

```
['run a function definition string and evaluate a test case to get the output', 'safely execute a function in a subprocess with timeout and security checks', 'test a candidate function against ground truth by comparing outputs on test cases', 'evaluate a list of trajectories by checking correctness of generated code against ground truth', 'execute a function definition in a subprocess and return the result via a multiprocessing queue', 'replace Unsplash random image URLs with picsum.photos placeholder images in text', 'create a headless Firefox Selenium WebDriver instance for browser automation', 'render an HTML snippet to a full page PNG screenshot using a Selenium driver', 'extract HTML snippets from text and replace them with a SEE RENDERED HTML placeholder', 'summarize the webpage utilities module for HTML rendering, URL replacement, and screenshot capture']
```

Usage

```
{'run_get_function_output': 'run a function definition string and evaluate a test case to get the output', 'run_subprocess_get_function_output': 'safely execute a function in a subprocess with timeout and security checks', 'test_check_correctness': 'test a candidate function against ground truth by comparing outputs on test cases', 'run_code_evaluate': 'evaluate a list of trajectories by checking correctness of generated code against ground truth', 'run_queue_get_function_output': 'execute a function definition in a subprocess and return the result via a multiprocessing queue'}
```

## File: facebookresearch_sweetrl/sweet_rl/utils/webpage_utils.py

Prompts

```
['run a function definition string and evaluate a test case to get the output', 'safely execute a function in a subprocess with timeout and security checks', 'test a candidate function against ground truth by comparing outputs on test cases', 'evaluate a list of trajectories by checking correctness of generated code against ground truth', 'execute a function definition in a subprocess and return the result via a multiprocessing queue', 'replace Unsplash random image URLs with picsum.photos placeholder images in text', 'create a headless Firefox Selenium WebDriver instance for browser automation', 'render an HTML snippet to a full page PNG screenshot using a Selenium driver', 'extract HTML snippets from text and replace them with a SEE RENDERED HTML placeholder', 'summarize the webpage utilities module for HTML rendering, URL replacement, and screenshot capture']
```

Usage

```
{'replace_unsplash_urls': 'replace Unsplash random image URLs with picsum.photos placeholder images in text', 'get_headless_firefox_driver': 'create a headless Firefox Selenium WebDriver instance for browser automation', 'render_html_to_screenshot': 'render an HTML snippet to a full page PNG screenshot using a Selenium driver', 'extract_html_from_text': 'extract HTML snippets from text and replace them with a SEE RENDERED HTML placeholder', 'summarize_webpage_utils': 'summarize the webpage utilities module for HTML rendering, URL replacement, and screenshot capture'}
```

