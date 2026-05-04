# Agent Python Tools

- repo: facebookresearch/deepfloat
- repo_uri: https://github.com/facebookresearch/deepfloat

## File: facebookresearch_deepfloat/rtl/log/luts/FixedPoint.py

Prompts

```
['create an FXnum fixed-point number with a specified value and default 64-bit fractional precision', 'create an FXfamily with a custom number of fractional bits and optional integer bit limit', 'compute the square root of an FXnum fixed-point number using Newton iteration refinement', 'compute sine, cosine, or tangent of an FXnum angle in radians using Taylor series', 'compute the exponential or natural logarithm of an FXnum using brute-force series expansion', 'generate a SystemVerilog pow2 lookup table module with specified input and output bit widths', 'generate a SystemVerilog log2 lookup table module with specified input and output bit widths', 'generate a SystemVerilog pow2 delta lookup table module for compressed log-linear conversion', 'generate a SystemVerilog log2 delta lookup table module for compressed log-linear conversion', 'compute the fixed-point pow2 expansion with rounding and overlap detection for a given index']
```

Usage

```
{'create_fixed_point_number': 'create an FXnum fixed-point number with a specified value and default 64-bit fractional precision', 'create_fixed_point_family': 'create an FXfamily with a custom number of fractional bits and optional integer bit limit', 'compute_fixed_point_sqrt': 'compute the square root of an FXnum fixed-point number using Newton iteration refinement', 'compute_fixed_point_trig': 'compute sine, cosine, or tangent of an FXnum angle in radians using Taylor series', 'compute_fixed_point_exp_log': 'compute the exponential or natural logarithm of an FXnum using brute-force series expansion'}
```

## File: facebookresearch_deepfloat/rtl/log/luts/gen_tables.py

Prompts

```
['create an FXnum fixed-point number with a specified value and default 64-bit fractional precision', 'create an FXfamily with a custom number of fractional bits and optional integer bit limit', 'compute the square root of an FXnum fixed-point number using Newton iteration refinement', 'compute sine, cosine, or tangent of an FXnum angle in radians using Taylor series', 'compute the exponential or natural logarithm of an FXnum using brute-force series expansion', 'generate a SystemVerilog pow2 lookup table module with specified input and output bit widths', 'generate a SystemVerilog log2 lookup table module with specified input and output bit widths', 'generate a SystemVerilog pow2 delta lookup table module for compressed log-linear conversion', 'generate a SystemVerilog log2 delta lookup table module for compressed log-linear conversion', 'compute the fixed-point pow2 expansion with rounding and overlap detection for a given index']
```

Usage

```
{'generate_pow2_lut': 'generate a SystemVerilog pow2 lookup table module with specified input and output bit widths', 'generate_log2_lut': 'generate a SystemVerilog log2 lookup table module with specified input and output bit widths', 'generate_pow2_delta_lut': 'generate a SystemVerilog pow2 delta lookup table module for compressed log-linear conversion', 'generate_log2_delta_lut': 'generate a SystemVerilog log2 delta lookup table module for compressed log-linear conversion', 'compute_pow2_expansion': 'compute the fixed-point pow2 expansion with rounding and overlap detection for a given index'}
```

