# Agent Python Tools

- repo: facebookresearch/hiplot
- repo_uri: https://github.com/facebookresearch/hiplot

## File: facebookresearch_hiplot/.circleci/test_e2e.py

Prompts

```
['create a headless Chrome WebDriver instance with browser logging enabled and 1920x1080 window size', 'create a headless Firefox WebDriver instance with browser logging enabled and 1920x1080 window size', 'test HTML demo pages by opening them in a headless browser and checking for console errors', 'use the BROWSERS_FACTORY dictionary to instantiate a Chrome or Firefox WebDriver by name', 'review the test_demo_pages function that polls browser logs until a timeout or Tests done message', 'test a Jupyter notebook by opening it in Chrome via Selenium and clicking the Run button', 'run an end-to-end test that opens a Jupyter notebook in a headless Chrome browser', 'capture screenshots and HTML of a Jupyter notebook at multiple steps during execution', 'check browser logs for errors and HiPlot waiting messages after running a notebook cell', 'assert that a notebook execution produced zero errors and at most one HiPlot wait message']
```

Usage

```
{'create_browser_chrome': 'create a headless Chrome WebDriver instance with browser logging enabled and 1920x1080 window size', 'create_browser_firefox': 'create a headless Firefox WebDriver instance with browser logging enabled and 1920x1080 window size', 'test_demo_pages': 'test HTML demo pages by opening them in a headless browser and checking for console errors', 'use_BROWSERS_FACTORY': 'use the BROWSERS_FACTORY dictionary to instantiate a Chrome or Firefox WebDriver by name', 'review_test_demo_pages': 'review the test_demo_pages function that polls browser logs until a timeout or Tests done message'}
```

## File: facebookresearch_hiplot/.circleci/test_notebook.py

Prompts

```
['create a headless Chrome WebDriver instance with browser logging enabled and 1920x1080 window size', 'create a headless Firefox WebDriver instance with browser logging enabled and 1920x1080 window size', 'test HTML demo pages by opening them in a headless browser and checking for console errors', 'use the BROWSERS_FACTORY dictionary to instantiate a Chrome or Firefox WebDriver by name', 'review the test_demo_pages function that polls browser logs until a timeout or Tests done message', 'test a Jupyter notebook by opening it in Chrome via Selenium and clicking the Run button', 'run an end-to-end test that opens a Jupyter notebook in a headless Chrome browser', 'capture screenshots and HTML of a Jupyter notebook at multiple steps during execution', 'check browser logs for errors and HiPlot waiting messages after running a notebook cell', 'assert that a notebook execution produced zero errors and at most one HiPlot wait message']
```

Usage

```
{'test_jupyter_notebook': 'test a Jupyter notebook by opening it in Chrome via Selenium and clicking the Run button', 'run_e2e_notebook_test': 'run an end-to-end test that opens a Jupyter notebook in a headless Chrome browser', 'capture_notebook_screenshots': 'capture screenshots and HTML of a Jupyter notebook at multiple steps during execution', 'check_browser_logs': 'check browser logs for errors and HiPlot waiting messages after running a notebook cell', 'assert_notebook_execution': 'assert that a notebook execution produced zero errors and at most one HiPlot wait message'}
```

