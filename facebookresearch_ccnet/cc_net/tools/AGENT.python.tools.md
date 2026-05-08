# Agent Python Tools

- repo: facebookresearch/ccnet
- repo_uri: https://github.com/facebookresearch/cc_net

## File: facebookresearch_ccnet/cc_net/tools/dl_cc_100.py

Prompts

```
['download the CC100 corpus to an output directory using multiprocessing for parallel shard extraction', 'download a specific CC100 snapshot like 2018-51 with all 500 shards to a directory', 'download and split a single CC100 shard into per-language gzip text files', 'iterate over Paragraph named tuples with language, text, and language model score from a shard', 'split an iterator of paragraphs into per-language gzip files in an output directory', 'train a KenLM language model from a corpus file using n-gram order and vocabulary size settings', 'sample sentences from Common Crawl data based on perplexity scores relative to a trained language model', 'mine sentences from Common Crawl shards that are similar to a given corpus using perplexity threshold filtering', 'normalize a corpus text file by applying text normalization rules and writing output to a directory', 'extract unique sentences from documents and score them with a language model using perplexity', 'create a fastText training corpus from CC shard files using DMOZ category tags', 'download the DMOZ tagging RDF file from the web archive to a local path', 'parse a DMOZ RDF file and return a dictionary mapping URLs and domains to topic tags', 'add or intersect DMOZ topic tags for a given URL in the url2tags dictionary', 'review the make_corpus function that filters documents by DMOZ tags and writes fastText-labeled output']
```

Usage

```
{'download_cc100_corpus': 'download the CC100 corpus to an output directory using multiprocessing for parallel shard extraction', 'download_cc100_snapshot': 'download a specific CC100 snapshot like 2018-51 with all 500 shards to a directory', 'download_cc100_shard': 'download and split a single CC100 shard into per-language gzip text files', 'iterate_cc100_paragraphs': 'iterate over Paragraph named tuples with language, text, and language model score from a shard', 'split_paragraphs_by_language': 'split an iterator of paragraphs into per-language gzip files in an output directory'}
```

## File: facebookresearch_ccnet/cc_net/tools/expand_corpus.py

Prompts

```
['download the CC100 corpus to an output directory using multiprocessing for parallel shard extraction', 'download a specific CC100 snapshot like 2018-51 with all 500 shards to a directory', 'download and split a single CC100 shard into per-language gzip text files', 'iterate over Paragraph named tuples with language, text, and language model score from a shard', 'split an iterator of paragraphs into per-language gzip files in an output directory', 'train a KenLM language model from a corpus file using n-gram order and vocabulary size settings', 'sample sentences from Common Crawl data based on perplexity scores relative to a trained language model', 'mine sentences from Common Crawl shards that are similar to a given corpus using perplexity threshold filtering', 'normalize a corpus text file by applying text normalization rules and writing output to a directory', 'extract unique sentences from documents and score them with a language model using perplexity', 'create a fastText training corpus from CC shard files using DMOZ category tags', 'download the DMOZ tagging RDF file from the web archive to a local path', 'parse a DMOZ RDF file and return a dictionary mapping URLs and domains to topic tags', 'add or intersect DMOZ topic tags for a given URL in the url2tags dictionary', 'review the make_corpus function that filters documents by DMOZ tags and writes fastText-labeled output']
```

Usage

```
{'train_lm': 'train a KenLM language model from a corpus file using n-gram order and vocabulary size settings', 'sample': 'sample sentences from Common Crawl data based on perplexity scores relative to a trained language model', 'mine': 'mine sentences from Common Crawl shards that are similar to a given corpus using perplexity threshold filtering', 'normalize': 'normalize a corpus text file by applying text normalization rules and writing output to a directory', 'ExtractSentences': 'extract unique sentences from documents and score them with a language model using perplexity'}
```

## File: facebookresearch_ccnet/cc_net/tools/make_dmoz_corpus.py

Prompts

```
['download the CC100 corpus to an output directory using multiprocessing for parallel shard extraction', 'download a specific CC100 snapshot like 2018-51 with all 500 shards to a directory', 'download and split a single CC100 shard into per-language gzip text files', 'iterate over Paragraph named tuples with language, text, and language model score from a shard', 'split an iterator of paragraphs into per-language gzip files in an output directory', 'train a KenLM language model from a corpus file using n-gram order and vocabulary size settings', 'sample sentences from Common Crawl data based on perplexity scores relative to a trained language model', 'mine sentences from Common Crawl shards that are similar to a given corpus using perplexity threshold filtering', 'normalize a corpus text file by applying text normalization rules and writing output to a directory', 'extract unique sentences from documents and score them with a language model using perplexity', 'create a fastText training corpus from CC shard files using DMOZ category tags', 'download the DMOZ tagging RDF file from the web archive to a local path', 'parse a DMOZ RDF file and return a dictionary mapping URLs and domains to topic tags', 'add or intersect DMOZ topic tags for a given URL in the url2tags dictionary', 'review the make_corpus function that filters documents by DMOZ tags and writes fastText-labeled output']
```

Usage

```
{'build_fasttext_corpus': 'create a fastText training corpus from CC shard files using DMOZ category tags', 'download_dmoz_tags': 'download the DMOZ tagging RDF file from the web archive to a local path', 'load_dmoz_tags': 'parse a DMOZ RDF file and return a dictionary mapping URLs and domains to topic tags', 'add_tags_to_url': 'add or intersect DMOZ topic tags for a given URL in the url2tags dictionary', 'review_make_corpus': 'review the make_corpus function that filters documents by DMOZ tags and writes fastText-labeled output'}
```

