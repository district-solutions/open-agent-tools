# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/crypten/mpc/provider/homomorphic_provider.py

Prompts

```
['review the HomomorphicProvider class that extends TupleProvider with HE name and unimplemented MPC methods', 'summarize the HomomorphicProvider stub class with generate_additive_triple, square, generate_xor_triple, wrap_rng, and B2A_rng methods', 'review the generate_additive_triple method that generates multiplicative triples of given sizes', 'review the generate_xor_triple method that generates xor triples of a given size', 'review the wrap_rng method that generates random shared tensors and their wraps', 'create a subclass of TupleProvider that implements generate_additive_triple for MPC multiplicative triples', 'enable tracing on a TupleProvider instance to cache all tuple generation requests to disk', 'save the request and tuple cache to disk and later load it back into a TupleProvider', 'fill the tuple_cache by replaying cached requests from the request_cache list', 'create a TupleProvider subclass that implements generate_binary_triple for XOR triples in MPC', 'generate additive triples of given sizes using a torch operation and return ArithmeticSharedTensors', 'generate xor triples of given size and return BinarySharedTensors for MPC protocols', 'generate a square double of given size and return the value and its square as ArithmeticSharedTensors', 'generate a random shared tensor and its wrap count for arithmetic secret sharing across parties', 'generate a random bit tensor shared as both arithmetic and binary shared tensors for conversion', 'generate square doubles as arithmetic shared tensors via the TrustedThirdParty square method for MPC squaring', 'generate random shared tensors and their wrap counts using the TrustedThirdParty wrap_rng method for comparison protocols', 'generate random bit tensors as both arithmetic and binary shared tensors using the TrustedThirdParty B2A_rng method']
```

Usage

```
{'review_HomomorphicProvider': 'review the HomomorphicProvider class that extends TupleProvider with HE name and unimplemented MPC methods', 'summarize_HomomorphicProvider': 'summarize the HomomorphicProvider stub class with generate_additive_triple, square, generate_xor_triple, wrap_rng, and B2A_rng methods', 'review_generate_additive_triple': 'review the generate_additive_triple method that generates multiplicative triples of given sizes', 'review_generate_xor_triple': 'review the generate_xor_triple method that generates xor triples of a given size', 'review_wrap_rng': 'review the wrap_rng method that generates random shared tensors and their wraps'}
```

## File: facebookresearch_crypten/crypten/mpc/provider/provider.py

Prompts

```
['review the HomomorphicProvider class that extends TupleProvider with HE name and unimplemented MPC methods', 'summarize the HomomorphicProvider stub class with generate_additive_triple, square, generate_xor_triple, wrap_rng, and B2A_rng methods', 'review the generate_additive_triple method that generates multiplicative triples of given sizes', 'review the generate_xor_triple method that generates xor triples of a given size', 'review the wrap_rng method that generates random shared tensors and their wraps', 'create a subclass of TupleProvider that implements generate_additive_triple for MPC multiplicative triples', 'enable tracing on a TupleProvider instance to cache all tuple generation requests to disk', 'save the request and tuple cache to disk and later load it back into a TupleProvider', 'fill the tuple_cache by replaying cached requests from the request_cache list', 'create a TupleProvider subclass that implements generate_binary_triple for XOR triples in MPC', 'generate additive triples of given sizes using a torch operation and return ArithmeticSharedTensors', 'generate xor triples of given size and return BinarySharedTensors for MPC protocols', 'generate a square double of given size and return the value and its square as ArithmeticSharedTensors', 'generate a random shared tensor and its wrap count for arithmetic secret sharing across parties', 'generate a random bit tensor shared as both arithmetic and binary shared tensors for conversion', 'generate square doubles as arithmetic shared tensors via the TrustedThirdParty square method for MPC squaring', 'generate random shared tensors and their wrap counts using the TrustedThirdParty wrap_rng method for comparison protocols', 'generate random bit tensors as both arithmetic and binary shared tensors using the TrustedThirdParty B2A_rng method']
```

Usage

```
{'create_tuple_provider_subclass': 'create a subclass of TupleProvider that implements generate_additive_triple for MPC multiplicative triples', 'trace_tuple_requests': 'enable tracing on a TupleProvider instance to cache all tuple generation requests to disk', 'save_and_load_cache': 'save the request and tuple cache to disk and later load it back into a TupleProvider', 'fill_tuple_cache': 'fill the tuple_cache by replaying cached requests from the request_cache list', 'generate_binary_triple_subclass': 'create a TupleProvider subclass that implements generate_binary_triple for XOR triples in MPC'}
```

## File: facebookresearch_crypten/crypten/mpc/provider/tfp_provider.py

Prompts

```
['review the HomomorphicProvider class that extends TupleProvider with HE name and unimplemented MPC methods', 'summarize the HomomorphicProvider stub class with generate_additive_triple, square, generate_xor_triple, wrap_rng, and B2A_rng methods', 'review the generate_additive_triple method that generates multiplicative triples of given sizes', 'review the generate_xor_triple method that generates xor triples of a given size', 'review the wrap_rng method that generates random shared tensors and their wraps', 'create a subclass of TupleProvider that implements generate_additive_triple for MPC multiplicative triples', 'enable tracing on a TupleProvider instance to cache all tuple generation requests to disk', 'save the request and tuple cache to disk and later load it back into a TupleProvider', 'fill the tuple_cache by replaying cached requests from the request_cache list', 'create a TupleProvider subclass that implements generate_binary_triple for XOR triples in MPC', 'generate additive triples of given sizes using a torch operation and return ArithmeticSharedTensors', 'generate xor triples of given size and return BinarySharedTensors for MPC protocols', 'generate a square double of given size and return the value and its square as ArithmeticSharedTensors', 'generate a random shared tensor and its wrap count for arithmetic secret sharing across parties', 'generate a random bit tensor shared as both arithmetic and binary shared tensors for conversion', 'generate square doubles as arithmetic shared tensors via the TrustedThirdParty square method for MPC squaring', 'generate random shared tensors and their wrap counts using the TrustedThirdParty wrap_rng method for comparison protocols', 'generate random bit tensors as both arithmetic and binary shared tensors using the TrustedThirdParty B2A_rng method']
```

Usage

```
{'generate_additive_triple': 'generate additive triples of given sizes using a torch operation and return ArithmeticSharedTensors', 'generate_binary_triple': 'generate xor triples of given size and return BinarySharedTensors for MPC protocols', 'square': 'generate a square double of given size and return the value and its square as ArithmeticSharedTensors', 'wrap_rng': 'generate a random shared tensor and its wrap count for arithmetic secret sharing across parties', 'B2A_rng': 'generate a random bit tensor shared as both arithmetic and binary shared tensors for conversion'}
```

## File: facebookresearch_crypten/crypten/mpc/provider/ttp_provider.py

Prompts

```
['review the HomomorphicProvider class that extends TupleProvider with HE name and unimplemented MPC methods', 'summarize the HomomorphicProvider stub class with generate_additive_triple, square, generate_xor_triple, wrap_rng, and B2A_rng methods', 'review the generate_additive_triple method that generates multiplicative triples of given sizes', 'review the generate_xor_triple method that generates xor triples of a given size', 'review the wrap_rng method that generates random shared tensors and their wraps', 'create a subclass of TupleProvider that implements generate_additive_triple for MPC multiplicative triples', 'enable tracing on a TupleProvider instance to cache all tuple generation requests to disk', 'save the request and tuple cache to disk and later load it back into a TupleProvider', 'fill the tuple_cache by replaying cached requests from the request_cache list', 'create a TupleProvider subclass that implements generate_binary_triple for XOR triples in MPC', 'generate additive triples of given sizes using a torch operation and return ArithmeticSharedTensors', 'generate xor triples of given size and return BinarySharedTensors for MPC protocols', 'generate a square double of given size and return the value and its square as ArithmeticSharedTensors', 'generate a random shared tensor and its wrap count for arithmetic secret sharing across parties', 'generate a random bit tensor shared as both arithmetic and binary shared tensors for conversion', 'generate square doubles as arithmetic shared tensors via the TrustedThirdParty square method for MPC squaring', 'generate random shared tensors and their wrap counts using the TrustedThirdParty wrap_rng method for comparison protocols', 'generate random bit tensors as both arithmetic and binary shared tensors using the TrustedThirdParty B2A_rng method']
```

Usage

```
{'generate_additive_triple': 'generate additive secret sharing triples using the TrustedThirdParty provider for MPC multiplication protocols', 'generate_square_double': 'generate square doubles as arithmetic shared tensors via the TrustedThirdParty square method for MPC squaring', 'generate_binary_triple': 'generate binary secret sharing triples using the TrustedThirdParty provider for MPC bitwise AND protocols', 'generate_wrap_rng': 'generate random shared tensors and their wrap counts using the TrustedThirdParty wrap_rng method for comparison protocols', 'generate_B2A_rng': 'generate random bit tensors as both arithmetic and binary shared tensors using the TrustedThirdParty B2A_rng method'}
```

