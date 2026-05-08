# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/tools/create_basis_compressed_glbs.py

Prompts

```
['run the CLI tool to convert all GLBs in a directory to basis compressed GLBs for reduced GPU memory', 'build an argparse parser with options for basis compression level, worker count, and unlit mesh conversion', 'convert a JPG or PNG image to a .basis compressed format using the magnum imageconverter tool', 'extract embedded images from a GLB file into a separate directory using the glb2gltf tool', 'finalize the compression pipeline by renaming basis meshes to .glb and originals to .glb.orig', 'run the npz2scn CLI tool to extract semantic scene data from a .npz file to a .scn JSON file', 'run the listify function to convert numpy ndarrays in a dictionary to Python lists for JSON serialization', 'extract object and room semantic scene information from a 3D Scene Graph .npz dataset file', 'convert a 3D Scene Graph .npz file containing objects and rooms into a JSON .scn output file', 'load a .npz file with pickle support and extract the output dictionary containing object and room data', 'run clang-tidy in parallel on all files in a compilation database using multiple threads', 'run clang-tidy with the -fix flag to automatically apply suggested fixes to source files', 'run clang-tidy and export suggested fixes to a YAML file for later review', 'run clang-tidy with a specific checks filter like llvm-header-guard on matched files', 'run clang-tidy with a header filter regex to only show diagnostics from matching headers']
```

Usage

```
{'run_basis_compression_cli': 'run the CLI tool to convert all GLBs in a directory to basis compressed GLBs for reduced GPU memory', 'build_parser_argparse': 'build an argparse parser with options for basis compression level, worker count, and unlit mesh conversion', 'convert_image_to_basis': 'convert a JPG or PNG image to a .basis compressed format using the magnum imageconverter tool', 'extract_images_from_glb': 'extract embedded images from a GLB file into a separate directory using the glb2gltf tool', 'finalize_rename_basis_meshes': 'finalize the compression pipeline by renaming basis meshes to .glb and originals to .glb.orig'}
```

## File: facebookresearch_habitat-sim/tools/npz2scn.py

Prompts

```
['run the CLI tool to convert all GLBs in a directory to basis compressed GLBs for reduced GPU memory', 'build an argparse parser with options for basis compression level, worker count, and unlit mesh conversion', 'convert a JPG or PNG image to a .basis compressed format using the magnum imageconverter tool', 'extract embedded images from a GLB file into a separate directory using the glb2gltf tool', 'finalize the compression pipeline by renaming basis meshes to .glb and originals to .glb.orig', 'run the npz2scn CLI tool to extract semantic scene data from a .npz file to a .scn JSON file', 'run the listify function to convert numpy ndarrays in a dictionary to Python lists for JSON serialization', 'extract object and room semantic scene information from a 3D Scene Graph .npz dataset file', 'convert a 3D Scene Graph .npz file containing objects and rooms into a JSON .scn output file', 'load a .npz file with pickle support and extract the output dictionary containing object and room data', 'run clang-tidy in parallel on all files in a compilation database using multiple threads', 'run clang-tidy with the -fix flag to automatically apply suggested fixes to source files', 'run clang-tidy and export suggested fixes to a YAML file for later review', 'run clang-tidy with a specific checks filter like llvm-header-guard on matched files', 'run clang-tidy with a header filter regex to only show diagnostics from matching headers']
```

Usage

```
{'run_npz2scn_cli': 'run the npz2scn CLI tool to extract semantic scene data from a .npz file to a .scn JSON file', 'run_listify_ndarrays': 'run the listify function to convert numpy ndarrays in a dictionary to Python lists for JSON serialization', 'extract_semantic_scene_data': 'extract object and room semantic scene information from a 3D Scene Graph .npz dataset file', 'convert_npz_to_json': 'convert a 3D Scene Graph .npz file containing objects and rooms into a JSON .scn output file', 'load_npz_with_pickle': 'load a .npz file with pickle support and extract the output dictionary containing object and room data'}
```

## File: facebookresearch_habitat-sim/tools/run-clang-tidy.py

Prompts

```
['run the CLI tool to convert all GLBs in a directory to basis compressed GLBs for reduced GPU memory', 'build an argparse parser with options for basis compression level, worker count, and unlit mesh conversion', 'convert a JPG or PNG image to a .basis compressed format using the magnum imageconverter tool', 'extract embedded images from a GLB file into a separate directory using the glb2gltf tool', 'finalize the compression pipeline by renaming basis meshes to .glb and originals to .glb.orig', 'run the npz2scn CLI tool to extract semantic scene data from a .npz file to a .scn JSON file', 'run the listify function to convert numpy ndarrays in a dictionary to Python lists for JSON serialization', 'extract object and room semantic scene information from a 3D Scene Graph .npz dataset file', 'convert a 3D Scene Graph .npz file containing objects and rooms into a JSON .scn output file', 'load a .npz file with pickle support and extract the output dictionary containing object and room data', 'run clang-tidy in parallel on all files in a compilation database using multiple threads', 'run clang-tidy with the -fix flag to automatically apply suggested fixes to source files', 'run clang-tidy and export suggested fixes to a YAML file for later review', 'run clang-tidy with a specific checks filter like llvm-header-guard on matched files', 'run clang-tidy with a header filter regex to only show diagnostics from matching headers']
```

Usage

```
{'run_clang_tidy_parallel': 'run clang-tidy in parallel on all files in a compilation database using multiple threads', 'run_clang_tidy_with_fixes': 'run clang-tidy with the -fix flag to automatically apply suggested fixes to source files', 'run_clang_tidy_export_fixes': 'run clang-tidy and export suggested fixes to a YAML file for later review', 'run_clang_tidy_specific_checks': 'run clang-tidy with a specific checks filter like llvm-header-guard on matched files', 'run_clang_tidy_with_header_filter': 'run clang-tidy with a header filter regex to only show diagnostics from matching headers'}
```

