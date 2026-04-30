# Agent Python Tools

- repo: huggingface/controlnetaux
- repo_uri: https://github.com/huggingface/controlnet_aux

## File: huggingface_controlnetaux/src/controlnet_aux/leres/pix2pix/options/base_options.py

Prompts

```
['create a BaseOptions instance and call initialize to define CLI arguments for pix2pix training', 'call gather_options on a BaseOptions subclass to parse and collect model-specific command line arguments', 'call parse on a BaseOptions subclass to fully parse options, process suffix, and set GPU device IDs', 'call print_options on a BaseOptions instance to print and save parsed options to a text file', 'call initialize on a BaseOptions instance to add common training and test arguments to an argparse parser', 'initialize an argparse parser with test-specific options like aspect_ratio, phase, eval mode, and num_test', 'parse command-line test options for the pix2pix4depth model with eval mode and num_test settings', 'configure the test phase options with aspect ratio, eval mode, and number of test images', 'set default test values including model pix2pix4depth and load_size matching crop_size', 'gather and parse all test options inherited from BaseOptions plus test-specific arguments']
```

Usage

```
{'create_BaseOptions_parser': 'create a BaseOptions instance and call initialize to define CLI arguments for pix2pix training', 'gather_options_BaseOptions': 'call gather_options on a BaseOptions subclass to parse and collect model-specific command line arguments', 'parse_BaseOptions': 'call parse on a BaseOptions subclass to fully parse options, process suffix, and set GPU device IDs', 'print_options_BaseOptions': 'call print_options on a BaseOptions instance to print and save parsed options to a text file', 'initialize_BaseOptions_arguments': 'call initialize on a BaseOptions instance to add common training and test arguments to an argparse parser'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/leres/pix2pix/options/test_options.py

Prompts

```
['create a BaseOptions instance and call initialize to define CLI arguments for pix2pix training', 'call gather_options on a BaseOptions subclass to parse and collect model-specific command line arguments', 'call parse on a BaseOptions subclass to fully parse options, process suffix, and set GPU device IDs', 'call print_options on a BaseOptions instance to print and save parsed options to a text file', 'call initialize on a BaseOptions instance to add common training and test arguments to an argparse parser', 'initialize an argparse parser with test-specific options like aspect_ratio, phase, eval mode, and num_test', 'parse command-line test options for the pix2pix4depth model with eval mode and num_test settings', 'configure the test phase options with aspect ratio, eval mode, and number of test images', 'set default test values including model pix2pix4depth and load_size matching crop_size', 'gather and parse all test options inherited from BaseOptions plus test-specific arguments']
```

Usage

```
{'initialize_test_parser': 'initialize an argparse parser with test-specific options like aspect_ratio, phase, eval mode, and num_test', 'parse_test_options': 'parse command-line test options for the pix2pix4depth model with eval mode and num_test settings', 'configure_test_phase': 'configure the test phase options with aspect ratio, eval mode, and number of test images', 'set_test_defaults': 'set default test values including model pix2pix4depth and load_size matching crop_size', 'gather_test_options': 'gather and parse all test options inherited from BaseOptions plus test-specific arguments'}
```

