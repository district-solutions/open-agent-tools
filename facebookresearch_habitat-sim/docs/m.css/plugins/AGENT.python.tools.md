# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/docs/m.css/plugins/ansilexer.py

Prompts

```
['build a Pygments RegexLexer subclass to tokenize ANSI SGR escape codes in terminal output', 'create an HtmlFormatter subclass that converts ANSI color tokens into CSS classes and inline styles', 'test the AnsiLexer to parse ANSI SGR codes including bold, reverse video, and 256-color palette', 'refactor the AnsiLexer _callback method to handle additional ECMA-48 SGR parameters', 'review the HtmlAnsiFormatter wrap and _wrap_code methods for Pygments 2.12+ compatibility', 'convert a Graphviz DOT source string to cleaned SVG output using the dot command', 'configure the font name and font size used for DOT to SVG rendering', 'convert a DOT source string to SVG with a custom CSS size style attribute', 'convert a DOT source string to SVG with custom SVG element attributes', 'convert a point value to rem units based on the configured font size', 'pipe LaTeX code from stdin to the latex2svg CLI and get SVG output on stdout', 'run the latex2svg CLI with a custom preamble file to render LaTeX math to SVG', 'call the latex2svg function with LaTeX code and params dict to get SVG data and dimensions', 'customize the latex2svg default_params dict to change fontsize, template, or preamble before rendering', 'review the default_template and default_preamble variables to understand the LaTeX document structure used for rendering', 'render a LaTeX math formula to SVG using the latex2svg library with custom params', 'fetch a cached LaTeX formula rendering or render it and cache the result', 'load a pickled formula rendering cache from a file to speed up repeated renders', 'save the formula rendering cache to a pickle file and prune unused entries', 'patch dvisvgm SVG output to convert pt to em and replace color codes with CSS classes']
```

Usage

```
{'build_ansi_lexer': 'build a Pygments RegexLexer subclass to tokenize ANSI SGR escape codes in terminal output', 'create_html_ansi_formatter': 'create an HtmlFormatter subclass that converts ANSI color tokens into CSS classes and inline styles', 'test_ansilexer_sgr_parsing': 'test the AnsiLexer to parse ANSI SGR codes including bold, reverse video, and 256-color palette', 'refactor_ansilexer_callback': 'refactor the AnsiLexer _callback method to handle additional ECMA-48 SGR parameters', 'review_htmlansiformatter_wrap': 'review the HtmlAnsiFormatter wrap and _wrap_code methods for Pygments 2.12+ compatibility'}
```

## File: facebookresearch_habitat-sim/docs/m.css/plugins/dot2svg.py

Prompts

```
['build a Pygments RegexLexer subclass to tokenize ANSI SGR escape codes in terminal output', 'create an HtmlFormatter subclass that converts ANSI color tokens into CSS classes and inline styles', 'test the AnsiLexer to parse ANSI SGR codes including bold, reverse video, and 256-color palette', 'refactor the AnsiLexer _callback method to handle additional ECMA-48 SGR parameters', 'review the HtmlAnsiFormatter wrap and _wrap_code methods for Pygments 2.12+ compatibility', 'convert a Graphviz DOT source string to cleaned SVG output using the dot command', 'configure the font name and font size used for DOT to SVG rendering', 'convert a DOT source string to SVG with a custom CSS size style attribute', 'convert a DOT source string to SVG with custom SVG element attributes', 'convert a point value to rem units based on the configured font size', 'pipe LaTeX code from stdin to the latex2svg CLI and get SVG output on stdout', 'run the latex2svg CLI with a custom preamble file to render LaTeX math to SVG', 'call the latex2svg function with LaTeX code and params dict to get SVG data and dimensions', 'customize the latex2svg default_params dict to change fontsize, template, or preamble before rendering', 'review the default_template and default_preamble variables to understand the LaTeX document structure used for rendering', 'render a LaTeX math formula to SVG using the latex2svg library with custom params', 'fetch a cached LaTeX formula rendering or render it and cache the result', 'load a pickled formula rendering cache from a file to speed up repeated renders', 'save the formula rendering cache to a pickle file and prune unused entries', 'patch dvisvgm SVG output to convert pt to em and replace color codes with CSS classes']
```

Usage

```
{'convert_dot_to_svg': 'convert a Graphviz DOT source string to cleaned SVG output using the dot command', 'configure_font_settings': 'configure the font name and font size used for DOT to SVG rendering', 'convert_dot_to_sized_svg': 'convert a DOT source string to SVG with a custom CSS size style attribute', 'convert_dot_to_attributed_svg': 'convert a DOT source string to SVG with custom SVG element attributes', 'convert_pt_to_em': 'convert a point value to rem units based on the configured font size'}
```

## File: facebookresearch_habitat-sim/docs/m.css/plugins/latex2svg.py

Prompts

```
['build a Pygments RegexLexer subclass to tokenize ANSI SGR escape codes in terminal output', 'create an HtmlFormatter subclass that converts ANSI color tokens into CSS classes and inline styles', 'test the AnsiLexer to parse ANSI SGR codes including bold, reverse video, and 256-color palette', 'refactor the AnsiLexer _callback method to handle additional ECMA-48 SGR parameters', 'review the HtmlAnsiFormatter wrap and _wrap_code methods for Pygments 2.12+ compatibility', 'convert a Graphviz DOT source string to cleaned SVG output using the dot command', 'configure the font name and font size used for DOT to SVG rendering', 'convert a DOT source string to SVG with a custom CSS size style attribute', 'convert a DOT source string to SVG with custom SVG element attributes', 'convert a point value to rem units based on the configured font size', 'pipe LaTeX code from stdin to the latex2svg CLI and get SVG output on stdout', 'run the latex2svg CLI with a custom preamble file to render LaTeX math to SVG', 'call the latex2svg function with LaTeX code and params dict to get SVG data and dimensions', 'customize the latex2svg default_params dict to change fontsize, template, or preamble before rendering', 'review the default_template and default_preamble variables to understand the LaTeX document structure used for rendering', 'render a LaTeX math formula to SVG using the latex2svg library with custom params', 'fetch a cached LaTeX formula rendering or render it and cache the result', 'load a pickled formula rendering cache from a file to speed up repeated renders', 'save the formula rendering cache to a pickle file and prune unused entries', 'patch dvisvgm SVG output to convert pt to em and replace color codes with CSS classes']
```

Usage

```
{'run_latex2svg_cli': 'pipe LaTeX code from stdin to the latex2svg CLI and get SVG output on stdout', 'run_latex2svg_with_preamble': 'run the latex2svg CLI with a custom preamble file to render LaTeX math to SVG', 'call_latex2svg_function': 'call the latex2svg function with LaTeX code and params dict to get SVG data and dimensions', 'customize_latex2svg_params': 'customize the latex2svg default_params dict to change fontsize, template, or preamble before rendering', 'review_latex2svg_template': 'review the default_template and default_preamble variables to understand the LaTeX document structure used for rendering'}
```

## File: facebookresearch_habitat-sim/docs/m.css/plugins/latex2svgextra.py

Prompts

```
['build a Pygments RegexLexer subclass to tokenize ANSI SGR escape codes in terminal output', 'create an HtmlFormatter subclass that converts ANSI color tokens into CSS classes and inline styles', 'test the AnsiLexer to parse ANSI SGR codes including bold, reverse video, and 256-color palette', 'refactor the AnsiLexer _callback method to handle additional ECMA-48 SGR parameters', 'review the HtmlAnsiFormatter wrap and _wrap_code methods for Pygments 2.12+ compatibility', 'convert a Graphviz DOT source string to cleaned SVG output using the dot command', 'configure the font name and font size used for DOT to SVG rendering', 'convert a DOT source string to SVG with a custom CSS size style attribute', 'convert a DOT source string to SVG with custom SVG element attributes', 'convert a point value to rem units based on the configured font size', 'pipe LaTeX code from stdin to the latex2svg CLI and get SVG output on stdout', 'run the latex2svg CLI with a custom preamble file to render LaTeX math to SVG', 'call the latex2svg function with LaTeX code and params dict to get SVG data and dimensions', 'customize the latex2svg default_params dict to change fontsize, template, or preamble before rendering', 'review the default_template and default_preamble variables to understand the LaTeX document structure used for rendering', 'render a LaTeX math formula to SVG using the latex2svg library with custom params', 'fetch a cached LaTeX formula rendering or render it and cache the result', 'load a pickled formula rendering cache from a file to speed up repeated renders', 'save the formula rendering cache to a pickle file and prune unused entries', 'patch dvisvgm SVG output to convert pt to em and replace color codes with CSS classes']
```

Usage

```
{'render_latex_formula': 'render a LaTeX math formula to SVG using the latex2svg library with custom params', 'fetch_cached_or_render_formula': 'fetch a cached LaTeX formula rendering or render it and cache the result', 'load_formula_cache': 'load a pickled formula rendering cache from a file to speed up repeated renders', 'save_formula_cache': 'save the formula rendering cache to a pickle file and prune unused entries', 'patch_dvisvgm_output': 'patch dvisvgm SVG output to convert pt to em and replace color codes with CSS classes'}
```

