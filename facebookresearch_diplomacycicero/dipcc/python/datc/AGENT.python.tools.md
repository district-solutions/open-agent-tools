# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/dipcc/python/datc/parse_datc.py

Prompts

```
['parse a string of DIP orders into a dictionary mapping powers to their normalized orders', 'parse a single DATC test HTML snippet into its name, description, orders, and result string', 'parse all DATC tests from an HTML file and return a list of parsed test tuples', 'run the interactive CLI to collect user inputs for DATC test move outcomes with caching', 'review the parse_orders function to understand how it normalizes SUPPORTS, CONVOYS, BUILD, DISBAND, and REMOVE keywords', 'render a C++ gtest test case from parsed DATC Diplomacy test data and expected results', 'render a C++ gtest assertion to verify a unit moved from source to destination location', 'render a C++ gtest assertion to verify a Diplomacy order succeeded or failed as expected', 'render a C++ gtest assertion to verify whether a unit was dislodged at a given location', 'render a C++ gtest assertion to verify whether a retreat order is possible or not']
```

Usage

```
{'parse_orders_from_text': 'parse a string of DIP orders into a dictionary mapping powers to their normalized orders', 'parse_test_from_html': 'parse a single DATC test HTML snippet into its name, description, orders, and result string', 'parse_tests_from_html_file': 'parse all DATC tests from an HTML file and return a list of parsed test tuples', 'run_interactive_test_collector': 'run the interactive CLI to collect user inputs for DATC test move outcomes with caching', 'review_parse_orders_normalization': 'review the parse_orders function to understand how it normalizes SUPPORTS, CONVOYS, BUILD, DISBAND, and REMOVE keywords'}
```

## File: facebookresearch_diplomacycicero/dipcc/python/datc/render_tests.py

Prompts

```
['parse a string of DIP orders into a dictionary mapping powers to their normalized orders', 'parse a single DATC test HTML snippet into its name, description, orders, and result string', 'parse all DATC tests from an HTML file and return a list of parsed test tuples', 'run the interactive CLI to collect user inputs for DATC test move outcomes with caching', 'review the parse_orders function to understand how it normalizes SUPPORTS, CONVOYS, BUILD, DISBAND, and REMOVE keywords', 'render a C++ gtest test case from parsed DATC Diplomacy test data and expected results', 'render a C++ gtest assertion to verify a unit moved from source to destination location', 'render a C++ gtest assertion to verify a Diplomacy order succeeded or failed as expected', 'render a C++ gtest assertion to verify whether a unit was dislodged at a given location', 'render a C++ gtest assertion to verify whether a retreat order is possible or not']
```

Usage

```
{'render_and_print_test': 'render a C++ gtest test case from parsed DATC Diplomacy test data and expected results', 'render_and_print_expect_move': 'render a C++ gtest assertion to verify a unit moved from source to destination location', 'render_and_print_expect_success': 'render a C++ gtest assertion to verify a Diplomacy order succeeded or failed as expected', 'render_and_print_expect_dislodge': 'render a C++ gtest assertion to verify whether a unit was dislodged at a given location', 'render_and_print_expect_retreat_order': 'render a C++ gtest assertion to verify whether a retreat order is possible or not'}
```

