# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/debug_utils/comparator/dims_spec/dim_parser.py

Prompts

```
['parse a single dimension token string and return a DimSpec with name and parallel modifiers', 'parse a fused dimension token with sub-dims separated by asterisks enclosed in parentheses', 'parse a special squeeze dimension token by name without additional modifiers', 'parse a single dimension name with optional modifiers using regex matching', 'parse a fused dimension token into a DimSpec with multiple sub-dim names joined by asterisks', 'parse a dims string like "b s[cp:zigzag] h[tp] d # dp:=moe_dp ep:replicated" into a DimsSpec object', "resolve a dims string and return tensor-compatible names with '1' replaced by singleton0, singleton1, etc.", "sanitize a list of dim names by replacing '1' with singleton0, singleton1, etc. for named tensor compatibility", 'filter out squeeze dims (name="1") from a list of DimSpec objects', "check if a dim name is a singleton name starting with 'singleton' followed by a digit", 'test the find_dim_index function to locate a dimension spec by its name', 'test the resolve_dim_by_name function to map a dimension name to its tensor axis index', 'create a tensor with named dimensions using apply_dim_names and refine_names', 'test the strip_dim_names function to remove all dimension names from a tensor', 'refactor the apply_dim_names function to validate tensor dimension count before renaming', 'create a DimSpec with a name string and optional parallel modifiers for tensor dimension specification', 'create a DimsSpec from a list of DimSpec objects with optional dp group alias and replicated axes', 'create a ParallelModifier with a parallel axis, optional ordering, and optional reduction for distributed tensor layout', "test the DimSpec sub_dims property to split fused dimension names like 'num_heads*head_dim' into sub-dim lists", 'test the DimSpec is_fused property to check if a dimension name contains multiple sub-dimensions joined by asterisk']
```

Usage

```
{'parse_dim_single': 'parse a single dimension token string and return a DimSpec with name and parallel modifiers', 'parse_dim_fused': 'parse a fused dimension token with sub-dims separated by asterisks enclosed in parentheses', 'parse_dim_squeeze': 'parse a special squeeze dimension token by name without additional modifiers', 'parse_single_dim': 'parse a single dimension name with optional modifiers using regex matching', 'parse_fused_dim': 'parse a fused dimension token into a DimSpec with multiple sub-dim names joined by asterisks'}
```

## File: sgl-project_sglang/python/sglang/srt/debug_utils/comparator/dims_spec/dims_parser.py

Prompts

```
['parse a single dimension token string and return a DimSpec with name and parallel modifiers', 'parse a fused dimension token with sub-dims separated by asterisks enclosed in parentheses', 'parse a special squeeze dimension token by name without additional modifiers', 'parse a single dimension name with optional modifiers using regex matching', 'parse a fused dimension token into a DimSpec with multiple sub-dim names joined by asterisks', 'parse a dims string like "b s[cp:zigzag] h[tp] d # dp:=moe_dp ep:replicated" into a DimsSpec object', "resolve a dims string and return tensor-compatible names with '1' replaced by singleton0, singleton1, etc.", "sanitize a list of dim names by replacing '1' with singleton0, singleton1, etc. for named tensor compatibility", 'filter out squeeze dims (name="1") from a list of DimSpec objects', "check if a dim name is a singleton name starting with 'singleton' followed by a digit", 'test the find_dim_index function to locate a dimension spec by its name', 'test the resolve_dim_by_name function to map a dimension name to its tensor axis index', 'create a tensor with named dimensions using apply_dim_names and refine_names', 'test the strip_dim_names function to remove all dimension names from a tensor', 'refactor the apply_dim_names function to validate tensor dimension count before renaming', 'create a DimSpec with a name string and optional parallel modifiers for tensor dimension specification', 'create a DimsSpec from a list of DimSpec objects with optional dp group alias and replicated axes', 'create a ParallelModifier with a parallel axis, optional ordering, and optional reduction for distributed tensor layout', "test the DimSpec sub_dims property to split fused dimension names like 'num_heads*head_dim' into sub-dim lists", 'test the DimSpec is_fused property to check if a dimension name contains multiple sub-dimensions joined by asterisk']
```

Usage

```
{'parse_dims': 'parse a dims string like "b s[cp:zigzag] h[tp] d # dp:=moe_dp ep:replicated" into a DimsSpec object', 'resolve_dim_names': "resolve a dims string and return tensor-compatible names with '1' replaced by singleton0, singleton1, etc.", 'sanitize_names': "sanitize a list of dim names by replacing '1' with singleton0, singleton1, etc. for named tensor compatibility", 'filter_out_squeeze_dims': 'filter out squeeze dims (name="1") from a list of DimSpec objects', 'is_singleton_name': "check if a dim name is a singleton name starting with 'singleton' followed by a digit"}
```

## File: sgl-project_sglang/python/sglang/srt/debug_utils/comparator/dims_spec/tensor_naming.py

Prompts

```
['parse a single dimension token string and return a DimSpec with name and parallel modifiers', 'parse a fused dimension token with sub-dims separated by asterisks enclosed in parentheses', 'parse a special squeeze dimension token by name without additional modifiers', 'parse a single dimension name with optional modifiers using regex matching', 'parse a fused dimension token into a DimSpec with multiple sub-dim names joined by asterisks', 'parse a dims string like "b s[cp:zigzag] h[tp] d # dp:=moe_dp ep:replicated" into a DimsSpec object', "resolve a dims string and return tensor-compatible names with '1' replaced by singleton0, singleton1, etc.", "sanitize a list of dim names by replacing '1' with singleton0, singleton1, etc. for named tensor compatibility", 'filter out squeeze dims (name="1") from a list of DimSpec objects', "check if a dim name is a singleton name starting with 'singleton' followed by a digit", 'test the find_dim_index function to locate a dimension spec by its name', 'test the resolve_dim_by_name function to map a dimension name to its tensor axis index', 'create a tensor with named dimensions using apply_dim_names and refine_names', 'test the strip_dim_names function to remove all dimension names from a tensor', 'refactor the apply_dim_names function to validate tensor dimension count before renaming', 'create a DimSpec with a name string and optional parallel modifiers for tensor dimension specification', 'create a DimsSpec from a list of DimSpec objects with optional dp group alias and replicated axes', 'create a ParallelModifier with a parallel axis, optional ordering, and optional reduction for distributed tensor layout', "test the DimSpec sub_dims property to split fused dimension names like 'num_heads*head_dim' into sub-dim lists", 'test the DimSpec is_fused property to check if a dimension name contains multiple sub-dimensions joined by asterisk']
```

Usage

```
{'test_find_dim_index': 'test the find_dim_index function to locate a dimension spec by its name', 'test_resolve_dim_by_name': 'test the resolve_dim_by_name function to map a dimension name to its tensor axis index', 'create_apply_dim_names': 'create a tensor with named dimensions using apply_dim_names and refine_names', 'test_strip_dim_names': 'test the strip_dim_names function to remove all dimension names from a tensor', 'refactor_apply_dim_names': 'refactor the apply_dim_names function to validate tensor dimension count before renaming'}
```

## File: sgl-project_sglang/python/sglang/srt/debug_utils/comparator/dims_spec/types.py

Prompts

```
['parse a single dimension token string and return a DimSpec with name and parallel modifiers', 'parse a fused dimension token with sub-dims separated by asterisks enclosed in parentheses', 'parse a special squeeze dimension token by name without additional modifiers', 'parse a single dimension name with optional modifiers using regex matching', 'parse a fused dimension token into a DimSpec with multiple sub-dim names joined by asterisks', 'parse a dims string like "b s[cp:zigzag] h[tp] d # dp:=moe_dp ep:replicated" into a DimsSpec object', "resolve a dims string and return tensor-compatible names with '1' replaced by singleton0, singleton1, etc.", "sanitize a list of dim names by replacing '1' with singleton0, singleton1, etc. for named tensor compatibility", 'filter out squeeze dims (name="1") from a list of DimSpec objects', "check if a dim name is a singleton name starting with 'singleton' followed by a digit", 'test the find_dim_index function to locate a dimension spec by its name', 'test the resolve_dim_by_name function to map a dimension name to its tensor axis index', 'create a tensor with named dimensions using apply_dim_names and refine_names', 'test the strip_dim_names function to remove all dimension names from a tensor', 'refactor the apply_dim_names function to validate tensor dimension count before renaming', 'create a DimSpec with a name string and optional parallel modifiers for tensor dimension specification', 'create a DimsSpec from a list of DimSpec objects with optional dp group alias and replicated axes', 'create a ParallelModifier with a parallel axis, optional ordering, and optional reduction for distributed tensor layout', "test the DimSpec sub_dims property to split fused dimension names like 'num_heads*head_dim' into sub-dim lists", 'test the DimSpec is_fused property to check if a dimension name contains multiple sub-dimensions joined by asterisk']
```

Usage

```
{'create_DimSpec': 'create a DimSpec with a name string and optional parallel modifiers for tensor dimension specification', 'create_DimsSpec': 'create a DimsSpec from a list of DimSpec objects with optional dp group alias and replicated axes', 'create_ParallelModifier': 'create a ParallelModifier with a parallel axis, optional ordering, and optional reduction for distributed tensor layout', 'test_DimSpec_sub_dims': "test the DimSpec sub_dims property to split fused dimension names like 'num_heads*head_dim' into sub-dim lists", 'test_DimSpec_is_fused': 'test the DimSpec is_fused property to check if a dimension name contains multiple sub-dimensions joined by asterisk'}
```

