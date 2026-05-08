# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/architects/router/build_router.py

Prompts

```
['build a node or flask router server by copying source files into the build directory', 'build the NPM router by installing node_modules and returning the node server source root path', 'build the flask router by returning the pre-built flask server source root path', 'install npm packages for the node router by running npm install in the node source directory', 'validate whether the build directory is properly formatted for building the router server']
```

Usage

```
{'build_router': 'build a node or flask router server by copying source files into the build directory', 'build_node_router': 'build the NPM router by installing node_modules and returning the node server source root path', 'build_flask_router': 'build the flask router by returning the pre-built flask server source root path', 'install_router_files': 'install npm packages for the node router by running npm install in the node source directory', 'can_build': 'validate whether the build directory is properly formatted for building the router server'}
```

