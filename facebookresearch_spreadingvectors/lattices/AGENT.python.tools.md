# Agent Python Tools

- repo: facebookresearch/spreadingvectors
- repo_uri: https://github.com/facebookresearch/spreadingvectors

## File: facebookresearch_spreadingvectors/lattices/Zn_lattice.py

Prompts

```
['create a ZnCodec instance with dimension d and squared radius r2 for Zn sphere quantization', 'quantize an array of float vectors to the nearest Zn lattice centroids using ZnCodec.quantize', 'encode quantized vectors into compact uint64 codes using ZnCodec.encode for storage or transmission', 'decode uint64 codes back into float vectors using ZnCodec.decode to reconstruct quantized data', 'find the nearest lattice code for query vectors using ZnCodec.find_nn to get ids and dot products', 'test the ZnCodec class to quantize, encode, and decode random vectors in a Z^n lattice', 'test the ZnCodecPy pure Python codec to quantize random vectors and compare with C implementation', 'test the ZnSphereCodec to search for nearest lattice points and encode them into codes', 'test the ZnSphereCodecRec recursive codec to encode centroids and verify round-trip decoding', 'test the Repeats class to encode and decode vectors with repeated values using SWIG bindings']
```

Usage

```
{'create_ZnCodec': 'create a ZnCodec instance with dimension d and squared radius r2 for Zn sphere quantization', 'quantize_vectors': 'quantize an array of float vectors to the nearest Zn lattice centroids using ZnCodec.quantize', 'encode_quantized_vectors': 'encode quantized vectors into compact uint64 codes using ZnCodec.encode for storage or transmission', 'decode_codes': 'decode uint64 codes back into float vectors using ZnCodec.decode to reconstruct quantized data', 'find_nearest_neighbor': 'find the nearest lattice code for query vectors using ZnCodec.find_nn to get ids and dot products'}
```

## File: facebookresearch_spreadingvectors/lattices/test_Zn.py

Prompts

```
['create a ZnCodec instance with dimension d and squared radius r2 for Zn sphere quantization', 'quantize an array of float vectors to the nearest Zn lattice centroids using ZnCodec.quantize', 'encode quantized vectors into compact uint64 codes using ZnCodec.encode for storage or transmission', 'decode uint64 codes back into float vectors using ZnCodec.decode to reconstruct quantized data', 'find the nearest lattice code for query vectors using ZnCodec.find_nn to get ids and dot products', 'test the ZnCodec class to quantize, encode, and decode random vectors in a Z^n lattice', 'test the ZnCodecPy pure Python codec to quantize random vectors and compare with C implementation', 'test the ZnSphereCodec to search for nearest lattice points and encode them into codes', 'test the ZnSphereCodecRec recursive codec to encode centroids and verify round-trip decoding', 'test the Repeats class to encode and decode vectors with repeated values using SWIG bindings']
```

Usage

```
{'test_ZnCodec_quantize_encode_decode': 'test the ZnCodec class to quantize, encode, and decode random vectors in a Z^n lattice', 'test_ZnCodecPy_quantize': 'test the ZnCodecPy pure Python codec to quantize random vectors and compare with C implementation', 'test_ZnSphereCodec_search_and_encode': 'test the ZnSphereCodec to search for nearest lattice points and encode them into codes', 'test_ZnSphereCodecRec_encode_centroid': 'test the ZnSphereCodecRec recursive codec to encode centroids and verify round-trip decoding', 'test_Repeats_encode_decode': 'test the Repeats class to encode and decode vectors with repeated values using SWIG bindings'}
```

