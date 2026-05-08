# Agent Python Tools

- repo: facebookresearch/locate-3d
- repo_uri: https://github.com/facebookresearch/locate-3d

## File: facebookresearch_locate-3d/models/model_utils/serialization/default.py

Prompts

```
['encode 3D grid coordinates into Z-order space-filling curve codes with optional batch embedding', 'encode 3D grid coordinates into Hilbert space-filling curve codes with optional batch embedding', 'decode Z-order or Hilbert space-filling curve codes back into 3D grid coordinates and batch IDs', 'encode or decode 3D grid coordinates using Z-order curve for spatial indexing and serialization', 'encode or decode 3D grid coordinates using Hilbert curve for spatial indexing and serialization', 'encode hypercube locations into Hilbert curve integers using the encode function with num_dims and num_bits', 'decode Hilbert curve integers back into hypercube locations using the decode function with num_dims and num_bits', 'convert an array of binary values into Gray codes using the binary2gray function', 'convert an array of Gray codes back into binary values using the gray2binary function', 'right shift an array of binary values by k positions along a specified axis', 'encode x, y, z coordinate tensors into shuffled Z-order keys using pre-computed lookup tables', 'decode shuffled Z-order keys back into x, y, z coordinate tensors and batch index', 'encode x, y, z coordinates with a batch index into shuffled Z-order keys for batched octree operations', 'create or retrieve device-specific encoding lookup tables for fast Z-order key generation from coordinates', 'create or retrieve device-specific decoding lookup tables for fast coordinate extraction from Z-order keys']
```

Usage

```
{'encode_grid_coords_z_order': 'encode 3D grid coordinates into Z-order space-filling curve codes with optional batch embedding', 'encode_grid_coords_hilbert': 'encode 3D grid coordinates into Hilbert space-filling curve codes with optional batch embedding', 'decode_space_filling_codes': 'decode Z-order or Hilbert space-filling curve codes back into 3D grid coordinates and batch IDs', 'z_order_encode_decode': 'encode or decode 3D grid coordinates using Z-order curve for spatial indexing and serialization', 'hilbert_encode_decode': 'encode or decode 3D grid coordinates using Hilbert curve for spatial indexing and serialization'}
```

## File: facebookresearch_locate-3d/models/model_utils/serialization/hilbert.py

Prompts

```
['encode 3D grid coordinates into Z-order space-filling curve codes with optional batch embedding', 'encode 3D grid coordinates into Hilbert space-filling curve codes with optional batch embedding', 'decode Z-order or Hilbert space-filling curve codes back into 3D grid coordinates and batch IDs', 'encode or decode 3D grid coordinates using Z-order curve for spatial indexing and serialization', 'encode or decode 3D grid coordinates using Hilbert curve for spatial indexing and serialization', 'encode hypercube locations into Hilbert curve integers using the encode function with num_dims and num_bits', 'decode Hilbert curve integers back into hypercube locations using the decode function with num_dims and num_bits', 'convert an array of binary values into Gray codes using the binary2gray function', 'convert an array of Gray codes back into binary values using the gray2binary function', 'right shift an array of binary values by k positions along a specified axis', 'encode x, y, z coordinate tensors into shuffled Z-order keys using pre-computed lookup tables', 'decode shuffled Z-order keys back into x, y, z coordinate tensors and batch index', 'encode x, y, z coordinates with a batch index into shuffled Z-order keys for batched octree operations', 'create or retrieve device-specific encoding lookup tables for fast Z-order key generation from coordinates', 'create or retrieve device-specific decoding lookup tables for fast coordinate extraction from Z-order keys']
```

Usage

```
{'encode_hilbert_integer': 'encode hypercube locations into Hilbert curve integers using the encode function with num_dims and num_bits', 'decode_hilbert_integer': 'decode Hilbert curve integers back into hypercube locations using the decode function with num_dims and num_bits', 'convert_binary_to_gray': 'convert an array of binary values into Gray codes using the binary2gray function', 'convert_gray_to_binary': 'convert an array of Gray codes back into binary values using the gray2binary function', 'right_shift_binary': 'right shift an array of binary values by k positions along a specified axis'}
```

## File: facebookresearch_locate-3d/models/model_utils/serialization/z_order.py

Prompts

```
['encode 3D grid coordinates into Z-order space-filling curve codes with optional batch embedding', 'encode 3D grid coordinates into Hilbert space-filling curve codes with optional batch embedding', 'decode Z-order or Hilbert space-filling curve codes back into 3D grid coordinates and batch IDs', 'encode or decode 3D grid coordinates using Z-order curve for spatial indexing and serialization', 'encode or decode 3D grid coordinates using Hilbert curve for spatial indexing and serialization', 'encode hypercube locations into Hilbert curve integers using the encode function with num_dims and num_bits', 'decode Hilbert curve integers back into hypercube locations using the decode function with num_dims and num_bits', 'convert an array of binary values into Gray codes using the binary2gray function', 'convert an array of Gray codes back into binary values using the gray2binary function', 'right shift an array of binary values by k positions along a specified axis', 'encode x, y, z coordinate tensors into shuffled Z-order keys using pre-computed lookup tables', 'decode shuffled Z-order keys back into x, y, z coordinate tensors and batch index', 'encode x, y, z coordinates with a batch index into shuffled Z-order keys for batched octree operations', 'create or retrieve device-specific encoding lookup tables for fast Z-order key generation from coordinates', 'create or retrieve device-specific decoding lookup tables for fast coordinate extraction from Z-order keys']
```

Usage

```
{'encode_xyz_to_z_order_key': 'encode x, y, z coordinate tensors into shuffled Z-order keys using pre-computed lookup tables', 'decode_z_order_key_to_xyz': 'decode shuffled Z-order keys back into x, y, z coordinate tensors and batch index', 'encode_xyz_with_batch_index': 'encode x, y, z coordinates with a batch index into shuffled Z-order keys for batched octree operations', 'create_key_lut_encode_tables': 'create or retrieve device-specific encoding lookup tables for fast Z-order key generation from coordinates', 'create_key_lut_decode_tables': 'create or retrieve device-specific decoding lookup tables for fast coordinate extraction from Z-order keys'}
```

