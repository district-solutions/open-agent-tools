# Agent Python Tools

- repo: facebookresearch/craftassist
- repo_uri: https://github.com/facebookresearch/craftassist

## File: facebookresearch_craftassist/client/pybind11/docs/benchmark.py

Prompts

```
['generate dummy C++ pybind11 binding code with a configurable number of classes and functions', 'generate dummy C++ Boost.Python binding code with a configurable number of classes and functions', 'run the benchmark script to compare pybind11 and Boost.Python compilation times and output sizes', 'review the benchmark output to compare compilation times across increasing class counts', 'refactor the nfns and nargs constants to adjust functions per class and arguments per function', 'summarize the Sphinx conf.py configuration variables for the pybind11 documentation project', 'review the generate_doxygen_xml function that runs doxygen to produce XML for Breathe', 'review the setup function that connects generate_doxygen_xml to the builder-inited event', 'refactor the breathe_projects config to point to a different Doxygen output directory', 'test the generate_doxygen_xml function to verify it creates the .build directory and runs doxygen']
```

Usage

```
{'generate_dummy_code_pybind11': 'generate dummy C++ pybind11 binding code with a configurable number of classes and functions', 'generate_dummy_code_boost': 'generate dummy C++ Boost.Python binding code with a configurable number of classes and functions', 'run_benchmark_pybind11_vs_boost': 'run the benchmark script to compare pybind11 and Boost.Python compilation times and output sizes', 'review_benchmark_compile_times': 'review the benchmark output to compare compilation times across increasing class counts', 'refactor_benchmark_constants': 'refactor the nfns and nargs constants to adjust functions per class and arguments per function'}
```

## File: facebookresearch_craftassist/client/pybind11/docs/conf.py

Prompts

```
['generate dummy C++ pybind11 binding code with a configurable number of classes and functions', 'generate dummy C++ Boost.Python binding code with a configurable number of classes and functions', 'run the benchmark script to compare pybind11 and Boost.Python compilation times and output sizes', 'review the benchmark output to compare compilation times across increasing class counts', 'refactor the nfns and nargs constants to adjust functions per class and arguments per function', 'summarize the Sphinx conf.py configuration variables for the pybind11 documentation project', 'review the generate_doxygen_xml function that runs doxygen to produce XML for Breathe', 'review the setup function that connects generate_doxygen_xml to the builder-inited event', 'refactor the breathe_projects config to point to a different Doxygen output directory', 'test the generate_doxygen_xml function to verify it creates the .build directory and runs doxygen']
```

Usage

```
{'summarize_conf': 'summarize the Sphinx conf.py configuration variables for the pybind11 documentation project', 'review_generate_doxygen_xml': 'review the generate_doxygen_xml function that runs doxygen to produce XML for Breathe', 'review_setup': 'review the setup function that connects generate_doxygen_xml to the builder-inited event', 'refactor_breathe_projects': 'refactor the breathe_projects config to point to a different Doxygen output directory', 'test_generate_doxygen_xml': 'test the generate_doxygen_xml function to verify it creates the .build directory and runs doxygen'}
```

