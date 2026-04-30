# Agent Python Tools

- repo: virattt/ai-hedge-fund
- repo_uri: https://github.com/virattt/ai-hedge-fund

## File: virattt_ai-hedge-fund/v2/signals/base.py

Prompts

```
['create a subclass of BaseSignal that implements the abstract name and compute methods for a new quantitative signal', 'test the _compute_rsi static method that calculates the latest RSI value from a pandas price series', 'refactor the _normalize_to_signal static method to clamp raw float values into a configurable low-high range', 'summarize the _sigmoid static method that maps unbounded float values into the -1 to +1 range via scaled tanh', 'review the _safe_float static method that converts values to float while handling NaN, None, and infinity']
```

Usage

```
{'create_BaseSignal_subclass': 'create a subclass of BaseSignal that implements the abstract name and compute methods for a new quantitative signal', 'test_compute_rsi': 'test the _compute_rsi static method that calculates the latest RSI value from a pandas price series', 'refactor_normalize_to_signal': 'refactor the _normalize_to_signal static method to clamp raw float values into a configurable low-high range', 'summarize_sigmoid': 'summarize the _sigmoid static method that maps unbounded float values into the -1 to +1 range via scaled tanh', 'review_safe_float': 'review the _safe_float static method that converts values to float while handling NaN, None, and infinity'}
```

