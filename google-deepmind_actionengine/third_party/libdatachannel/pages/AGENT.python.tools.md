# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/third_party/libdatachannel/pages/tasks.py

Prompts

```
['build a local version of the pelican static site using the base settings configuration', 'serve the pelican site on localhost:8000 using a custom TCP server with address reuse', 'remove all generated files in the pelican output directory and recreate the folder', 'build the production pelican site and deploy it to a remote server via rsync over ssh', 'build the production pelican site and publish it to GitHub Pages using ghp-import']
```

Usage

```
{'build_pelican_site': 'build a local version of the pelican static site using the base settings configuration', 'serve_pelican_site': 'serve the pelican site on localhost:8000 using a custom TCP server with address reuse', 'clean_pelican_output': 'remove all generated files in the pelican output directory and recreate the folder', 'publish_pelican_rsync': 'build the production pelican site and deploy it to a remote server via rsync over ssh', 'deploy_pelican_ghpages': 'build the production pelican site and publish it to GitHub Pages using ghp-import'}
```

