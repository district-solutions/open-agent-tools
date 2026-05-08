# Agent Python Tools

- repo: facebookresearch/libri-light
- repo_uri: https://github.com/facebookresearch/libri-light

## File: facebookresearch_libri-light/data_preparation/text_retrieval/archive_org.py

Prompts

```
['download all .txt files for a given Archive.org item ID into a specified output directory', 'extract the Archive.org item ID from a details URL string', 'download and concatenate all text files from an Archive.org URL into a single string', 'check whether a given URL points to an Archive.org details or stream page', 'run the module to fetch and print full text from an Archive.org URL', 'fetch and parse full text from a bartleby.com URL including all paginated chapters', 'check if a given URL points to a bartleby.com domain', 'parse bartleby HTML pages to extract chapter titles and body text using an HTMLParser subclass', 'get cleaned text from a BarthelebyParser instance with escaped characters unescaped', 'parse a bartleby HTML page to extract the document title from the title tag', 'check if a given URL is a valid Project Gutenberg URL', 'fetch the raw text content of a Project Gutenberg book by its URL', 'refactor is_guttenberg_url to use a regex or URL parsing library instead of string find', 'test get_guttenberg_data with a known Gutenberg book URL to verify text retrieval', 'summarize the guttenberg module functions for URL validation and text fetching from Project Gutenberg', 'load the full text of a HathiTrust book given a catalog or Babel URL', 'load the full text of a HathiTrust book given its book ID string', 'parse a HathiTrust plaintext page HTML to extract page text and next page URL', 'parse a HathiTrust catalog page HTML to extract candidate book handle IDs', 'check if a given URL string is a HathiTrust URL by searching for hathitrust.org', 'scrape all chapter text from a mainlesson.com URL by parsing the table of contents and each chapter page', 'extract a specific query parameter value from a display.php URL by tag name', 'build a gatewaytotheclassics.com display URL from author, book, and chapter parameters', 'parse an HTML table of contents page to extract chapter story IDs from lhlink div links', 'parse an HTML chapter page to extract the centered title and body text from the content']
```

Usage

```
{'download_text_data_from_archive_org': 'download all .txt files for a given Archive.org item ID into a specified output directory', 'extract_archive_id_from_url': 'extract the Archive.org item ID from a details URL string', 'retrieve_full_text_from_archive_org': 'download and concatenate all text files from an Archive.org URL into a single string', 'check_if_archive_org_url': 'check whether a given URL points to an Archive.org details or stream page', 'run_archive_org_text_retrieval': 'run the module to fetch and print full text from an Archive.org URL'}
```

## File: facebookresearch_libri-light/data_preparation/text_retrieval/bartleby.py

Prompts

```
['download all .txt files for a given Archive.org item ID into a specified output directory', 'extract the Archive.org item ID from a details URL string', 'download and concatenate all text files from an Archive.org URL into a single string', 'check whether a given URL points to an Archive.org details or stream page', 'run the module to fetch and print full text from an Archive.org URL', 'fetch and parse full text from a bartleby.com URL including all paginated chapters', 'check if a given URL points to a bartleby.com domain', 'parse bartleby HTML pages to extract chapter titles and body text using an HTMLParser subclass', 'get cleaned text from a BarthelebyParser instance with escaped characters unescaped', 'parse a bartleby HTML page to extract the document title from the title tag', 'check if a given URL is a valid Project Gutenberg URL', 'fetch the raw text content of a Project Gutenberg book by its URL', 'refactor is_guttenberg_url to use a regex or URL parsing library instead of string find', 'test get_guttenberg_data with a known Gutenberg book URL to verify text retrieval', 'summarize the guttenberg module functions for URL validation and text fetching from Project Gutenberg', 'load the full text of a HathiTrust book given a catalog or Babel URL', 'load the full text of a HathiTrust book given its book ID string', 'parse a HathiTrust plaintext page HTML to extract page text and next page URL', 'parse a HathiTrust catalog page HTML to extract candidate book handle IDs', 'check if a given URL string is a HathiTrust URL by searching for hathitrust.org', 'scrape all chapter text from a mainlesson.com URL by parsing the table of contents and each chapter page', 'extract a specific query parameter value from a display.php URL by tag name', 'build a gatewaytotheclassics.com display URL from author, book, and chapter parameters', 'parse an HTML table of contents page to extract chapter story IDs from lhlink div links', 'parse an HTML chapter page to extract the centered title and body text from the content']
```

Usage

```
{'get_bartheleby_data': 'fetch and parse full text from a bartleby.com URL including all paginated chapters', 'is_bartheleby_url': 'check if a given URL points to a bartleby.com domain', 'BarthelebyParser': 'parse bartleby HTML pages to extract chapter titles and body text using an HTMLParser subclass', 'BarthelebyParser_getCleanText': 'get cleaned text from a BarthelebyParser instance with escaped characters unescaped', 'BarthelebyTitleParser': 'parse a bartleby HTML page to extract the document title from the title tag'}
```

## File: facebookresearch_libri-light/data_preparation/text_retrieval/guttenberg.py

Prompts

```
['download all .txt files for a given Archive.org item ID into a specified output directory', 'extract the Archive.org item ID from a details URL string', 'download and concatenate all text files from an Archive.org URL into a single string', 'check whether a given URL points to an Archive.org details or stream page', 'run the module to fetch and print full text from an Archive.org URL', 'fetch and parse full text from a bartleby.com URL including all paginated chapters', 'check if a given URL points to a bartleby.com domain', 'parse bartleby HTML pages to extract chapter titles and body text using an HTMLParser subclass', 'get cleaned text from a BarthelebyParser instance with escaped characters unescaped', 'parse a bartleby HTML page to extract the document title from the title tag', 'check if a given URL is a valid Project Gutenberg URL', 'fetch the raw text content of a Project Gutenberg book by its URL', 'refactor is_guttenberg_url to use a regex or URL parsing library instead of string find', 'test get_guttenberg_data with a known Gutenberg book URL to verify text retrieval', 'summarize the guttenberg module functions for URL validation and text fetching from Project Gutenberg', 'load the full text of a HathiTrust book given a catalog or Babel URL', 'load the full text of a HathiTrust book given its book ID string', 'parse a HathiTrust plaintext page HTML to extract page text and next page URL', 'parse a HathiTrust catalog page HTML to extract candidate book handle IDs', 'check if a given URL string is a HathiTrust URL by searching for hathitrust.org', 'scrape all chapter text from a mainlesson.com URL by parsing the table of contents and each chapter page', 'extract a specific query parameter value from a display.php URL by tag name', 'build a gatewaytotheclassics.com display URL from author, book, and chapter parameters', 'parse an HTML table of contents page to extract chapter story IDs from lhlink div links', 'parse an HTML chapter page to extract the centered title and body text from the content']
```

Usage

```
{'check_is_guttenberg_url': 'check if a given URL is a valid Project Gutenberg URL', 'get_guttenberg_data': 'fetch the raw text content of a Project Gutenberg book by its URL', 'refactor_is_guttenberg_url': 'refactor is_guttenberg_url to use a regex or URL parsing library instead of string find', 'test_get_guttenberg_data': 'test get_guttenberg_data with a known Gutenberg book URL to verify text retrieval', 'summarize_guttenberg_module': 'summarize the guttenberg module functions for URL validation and text fetching from Project Gutenberg'}
```

## File: facebookresearch_libri-light/data_preparation/text_retrieval/hathitrust.py

Prompts

```
['download all .txt files for a given Archive.org item ID into a specified output directory', 'extract the Archive.org item ID from a details URL string', 'download and concatenate all text files from an Archive.org URL into a single string', 'check whether a given URL points to an Archive.org details or stream page', 'run the module to fetch and print full text from an Archive.org URL', 'fetch and parse full text from a bartleby.com URL including all paginated chapters', 'check if a given URL points to a bartleby.com domain', 'parse bartleby HTML pages to extract chapter titles and body text using an HTMLParser subclass', 'get cleaned text from a BarthelebyParser instance with escaped characters unescaped', 'parse a bartleby HTML page to extract the document title from the title tag', 'check if a given URL is a valid Project Gutenberg URL', 'fetch the raw text content of a Project Gutenberg book by its URL', 'refactor is_guttenberg_url to use a regex or URL parsing library instead of string find', 'test get_guttenberg_data with a known Gutenberg book URL to verify text retrieval', 'summarize the guttenberg module functions for URL validation and text fetching from Project Gutenberg', 'load the full text of a HathiTrust book given a catalog or Babel URL', 'load the full text of a HathiTrust book given its book ID string', 'parse a HathiTrust plaintext page HTML to extract page text and next page URL', 'parse a HathiTrust catalog page HTML to extract candidate book handle IDs', 'check if a given URL string is a HathiTrust URL by searching for hathitrust.org', 'scrape all chapter text from a mainlesson.com URL by parsing the table of contents and each chapter page', 'extract a specific query parameter value from a display.php URL by tag name', 'build a gatewaytotheclassics.com display URL from author, book, and chapter parameters', 'parse an HTML table of contents page to extract chapter story IDs from lhlink div links', 'parse an HTML chapter page to extract the centered title and body text from the content']
```

Usage

```
{'load_hathitrust_book_from_url': 'load the full text of a HathiTrust book given a catalog or Babel URL', 'load_whole_book_by_id': 'load the full text of a HathiTrust book given its book ID string', 'parse_hathitrust_page_with_HathitrustParser': 'parse a HathiTrust plaintext page HTML to extract page text and next page URL', 'parse_catalog_with_CatalogParser': 'parse a HathiTrust catalog page HTML to extract candidate book handle IDs', 'check_is_hathitrust_url': 'check if a given URL string is a HathiTrust URL by searching for hathitrust.org'}
```

## File: facebookresearch_libri-light/data_preparation/text_retrieval/main_lesson.py

Prompts

```
['download all .txt files for a given Archive.org item ID into a specified output directory', 'extract the Archive.org item ID from a details URL string', 'download and concatenate all text files from an Archive.org URL into a single string', 'check whether a given URL points to an Archive.org details or stream page', 'run the module to fetch and print full text from an Archive.org URL', 'fetch and parse full text from a bartleby.com URL including all paginated chapters', 'check if a given URL points to a bartleby.com domain', 'parse bartleby HTML pages to extract chapter titles and body text using an HTMLParser subclass', 'get cleaned text from a BarthelebyParser instance with escaped characters unescaped', 'parse a bartleby HTML page to extract the document title from the title tag', 'check if a given URL is a valid Project Gutenberg URL', 'fetch the raw text content of a Project Gutenberg book by its URL', 'refactor is_guttenberg_url to use a regex or URL parsing library instead of string find', 'test get_guttenberg_data with a known Gutenberg book URL to verify text retrieval', 'summarize the guttenberg module functions for URL validation and text fetching from Project Gutenberg', 'load the full text of a HathiTrust book given a catalog or Babel URL', 'load the full text of a HathiTrust book given its book ID string', 'parse a HathiTrust plaintext page HTML to extract page text and next page URL', 'parse a HathiTrust catalog page HTML to extract candidate book handle IDs', 'check if a given URL string is a HathiTrust URL by searching for hathitrust.org', 'scrape all chapter text from a mainlesson.com URL by parsing the table of contents and each chapter page', 'extract a specific query parameter value from a display.php URL by tag name', 'build a gatewaytotheclassics.com display URL from author, book, and chapter parameters', 'parse an HTML table of contents page to extract chapter story IDs from lhlink div links', 'parse an HTML chapter page to extract the centered title and body text from the content']
```

Usage

```
{'get_all_text_from_main_lesson': 'scrape all chapter text from a mainlesson.com URL by parsing the table of contents and each chapter page', 'get_tag_value_in_url': 'extract a specific query parameter value from a display.php URL by tag name', 'get_full_url': 'build a gatewaytotheclassics.com display URL from author, book, and chapter parameters', 'ToCParser': 'parse an HTML table of contents page to extract chapter story IDs from lhlink div links', 'ChapterParser': 'parse an HTML chapter page to extract the centered title and body text from the content'}
```

