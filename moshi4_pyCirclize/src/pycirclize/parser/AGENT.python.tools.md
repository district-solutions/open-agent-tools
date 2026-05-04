# Agent Python Tools

- repo: moshi4/pyCirclize
- repo_uri: https://github.com/moshi4/pyCirclize

## File: moshi4_pyCirclize/src/pycirclize/parser/bed.py

Prompts

```
['create a BED file parser using the Bed class to load and access genomic interval records', 'parse a BED format file into a list of BedRecord objects with chromosome, start, end, name, and score fields', 'get a list of BedRecord objects from a parsed BED file via the Bed.records property', 'calculate the size of a BED record interval using the BedRecord.size property', 'build a BedRecord dataclass instance with chromosome, start, end, optional name, and optional score', 'create a Genbank parser instance from a genbank file path to access genome sequence and features', 'calculate the overall GC content percentage of a genbank genome sequence', 'calculate GC skew values across a genome sequence using sliding window analysis', 'calculate GC content percentages across a genome sequence using sliding window analysis', 'extract CDS or gene features from genbank records filtered by type and strand', 'parse a GFF file and extract records for a target seqid with automatic compression support', 'extract CDS features from a parsed GFF file filtered by strand and genomic range', 'extract exon structure features from mRNA and exon records using parent-child ID relations', 'filter GFF records by feature type, strand, and genomic range', 'create a Matrix from a CSV or TSV file path to parse chord diagram data', 'create a Matrix from a from-to table file or DataFrame with optional sorting order', 'build chord diagram links and sectors from a Matrix for plotting with Circos', 'sort a Matrix by ascending or descending node size or custom label order', 'convert a Matrix to a from-to table DataFrame for downstream processing', 'parse a CSV or TSV file into a pandas DataFrame using the Table class parser', 'build stacked bar chart data with row sums, bar heights, and bottom positions from a table', 'generate a column name to color mapping dict using a specified colormap for table visualization', 'calculate radius limits and label positions for horizontal bar plots on a circular track', 'create tooltip strings for a specific row in a radar table with column name and value pairs']
```

Usage

```
{'create_bed_parser': 'create a BED file parser using the Bed class to load and access genomic interval records', 'parse_bed_file': 'parse a BED format file into a list of BedRecord objects with chromosome, start, end, name, and score fields', 'get_bed_records': 'get a list of BedRecord objects from a parsed BED file via the Bed.records property', 'calculate_bed_record_size': 'calculate the size of a BED record interval using the BedRecord.size property', 'build_bed_record': 'build a BedRecord dataclass instance with chromosome, start, end, optional name, and optional score'}
```

## File: moshi4_pyCirclize/src/pycirclize/parser/genbank.py

Prompts

```
['create a BED file parser using the Bed class to load and access genomic interval records', 'parse a BED format file into a list of BedRecord objects with chromosome, start, end, name, and score fields', 'get a list of BedRecord objects from a parsed BED file via the Bed.records property', 'calculate the size of a BED record interval using the BedRecord.size property', 'build a BedRecord dataclass instance with chromosome, start, end, optional name, and optional score', 'create a Genbank parser instance from a genbank file path to access genome sequence and features', 'calculate the overall GC content percentage of a genbank genome sequence', 'calculate GC skew values across a genome sequence using sliding window analysis', 'calculate GC content percentages across a genome sequence using sliding window analysis', 'extract CDS or gene features from genbank records filtered by type and strand', 'parse a GFF file and extract records for a target seqid with automatic compression support', 'extract CDS features from a parsed GFF file filtered by strand and genomic range', 'extract exon structure features from mRNA and exon records using parent-child ID relations', 'filter GFF records by feature type, strand, and genomic range', 'create a Matrix from a CSV or TSV file path to parse chord diagram data', 'create a Matrix from a from-to table file or DataFrame with optional sorting order', 'build chord diagram links and sectors from a Matrix for plotting with Circos', 'sort a Matrix by ascending or descending node size or custom label order', 'convert a Matrix to a from-to table DataFrame for downstream processing', 'parse a CSV or TSV file into a pandas DataFrame using the Table class parser', 'build stacked bar chart data with row sums, bar heights, and bottom positions from a table', 'generate a column name to color mapping dict using a specified colormap for table visualization', 'calculate radius limits and label positions for horizontal bar plots on a circular track', 'create tooltip strings for a specific row in a radar table with column name and value pairs']
```

Usage

```
{'create_genbank_parser': 'create a Genbank parser instance from a genbank file path to access genome sequence and features', 'calc_genome_gc_content': 'calculate the overall GC content percentage of a genbank genome sequence', 'calc_gc_skew': 'calculate GC skew values across a genome sequence using sliding window analysis', 'calc_gc_content': 'calculate GC content percentages across a genome sequence using sliding window analysis', 'get_seqid2features': 'extract CDS or gene features from genbank records filtered by type and strand'}
```

## File: moshi4_pyCirclize/src/pycirclize/parser/gff.py

Prompts

```
['create a BED file parser using the Bed class to load and access genomic interval records', 'parse a BED format file into a list of BedRecord objects with chromosome, start, end, name, and score fields', 'get a list of BedRecord objects from a parsed BED file via the Bed.records property', 'calculate the size of a BED record interval using the BedRecord.size property', 'build a BedRecord dataclass instance with chromosome, start, end, optional name, and optional score', 'create a Genbank parser instance from a genbank file path to access genome sequence and features', 'calculate the overall GC content percentage of a genbank genome sequence', 'calculate GC skew values across a genome sequence using sliding window analysis', 'calculate GC content percentages across a genome sequence using sliding window analysis', 'extract CDS or gene features from genbank records filtered by type and strand', 'parse a GFF file and extract records for a target seqid with automatic compression support', 'extract CDS features from a parsed GFF file filtered by strand and genomic range', 'extract exon structure features from mRNA and exon records using parent-child ID relations', 'filter GFF records by feature type, strand, and genomic range', 'create a Matrix from a CSV or TSV file path to parse chord diagram data', 'create a Matrix from a from-to table file or DataFrame with optional sorting order', 'build chord diagram links and sectors from a Matrix for plotting with Circos', 'sort a Matrix by ascending or descending node size or custom label order', 'convert a Matrix to a from-to table DataFrame for downstream processing', 'parse a CSV or TSV file into a pandas DataFrame using the Table class parser', 'build stacked bar chart data with row sums, bar heights, and bottom positions from a table', 'generate a column name to color mapping dict using a specified colormap for table visualization', 'calculate radius limits and label positions for horizontal bar plots on a circular track', 'create tooltip strings for a specific row in a radar table with column name and value pairs']
```

Usage

```
{'parse_gff_file': 'parse a GFF file and extract records for a target seqid with automatic compression support', 'extract_cds_features': 'extract CDS features from a parsed GFF file filtered by strand and genomic range', 'extract_exon_features': 'extract exon structure features from mRNA and exon records using parent-child ID relations', 'get_seqid2features': 'get a dictionary mapping seqids to BioPython SeqFeature objects filtered by type and strand', 'filter_gff_records': 'filter GFF records by feature type, strand, and genomic range'}
```

## File: moshi4_pyCirclize/src/pycirclize/parser/matrix.py

Prompts

```
['create a BED file parser using the Bed class to load and access genomic interval records', 'parse a BED format file into a list of BedRecord objects with chromosome, start, end, name, and score fields', 'get a list of BedRecord objects from a parsed BED file via the Bed.records property', 'calculate the size of a BED record interval using the BedRecord.size property', 'build a BedRecord dataclass instance with chromosome, start, end, optional name, and optional score', 'create a Genbank parser instance from a genbank file path to access genome sequence and features', 'calculate the overall GC content percentage of a genbank genome sequence', 'calculate GC skew values across a genome sequence using sliding window analysis', 'calculate GC content percentages across a genome sequence using sliding window analysis', 'extract CDS or gene features from genbank records filtered by type and strand', 'parse a GFF file and extract records for a target seqid with automatic compression support', 'extract CDS features from a parsed GFF file filtered by strand and genomic range', 'extract exon structure features from mRNA and exon records using parent-child ID relations', 'filter GFF records by feature type, strand, and genomic range', 'create a Matrix from a CSV or TSV file path to parse chord diagram data', 'create a Matrix from a from-to table file or DataFrame with optional sorting order', 'build chord diagram links and sectors from a Matrix for plotting with Circos', 'sort a Matrix by ascending or descending node size or custom label order', 'convert a Matrix to a from-to table DataFrame for downstream processing', 'parse a CSV or TSV file into a pandas DataFrame using the Table class parser', 'build stacked bar chart data with row sums, bar heights, and bottom positions from a table', 'generate a column name to color mapping dict using a specified colormap for table visualization', 'calculate radius limits and label positions for horizontal bar plots on a circular track', 'create tooltip strings for a specific row in a radar table with column name and value pairs']
```

Usage

```
{'create_matrix_from_file': 'create a Matrix from a CSV or TSV file path to parse chord diagram data', 'create_matrix_from_fromto_table': 'create a Matrix from a from-to table file or DataFrame with optional sorting order', 'build_chord_diagram_links': 'build chord diagram links and sectors from a Matrix for plotting with Circos', 'sort_matrix_by_node_size': 'sort a Matrix by ascending or descending node size or custom label order', 'convert_matrix_to_fromto_table': 'convert a Matrix to a from-to table DataFrame for downstream processing'}
```

## File: moshi4_pyCirclize/src/pycirclize/parser/table.py

Prompts

```
['create a BED file parser using the Bed class to load and access genomic interval records', 'parse a BED format file into a list of BedRecord objects with chromosome, start, end, name, and score fields', 'get a list of BedRecord objects from a parsed BED file via the Bed.records property', 'calculate the size of a BED record interval using the BedRecord.size property', 'build a BedRecord dataclass instance with chromosome, start, end, optional name, and optional score', 'create a Genbank parser instance from a genbank file path to access genome sequence and features', 'calculate the overall GC content percentage of a genbank genome sequence', 'calculate GC skew values across a genome sequence using sliding window analysis', 'calculate GC content percentages across a genome sequence using sliding window analysis', 'extract CDS or gene features from genbank records filtered by type and strand', 'parse a GFF file and extract records for a target seqid with automatic compression support', 'extract CDS features from a parsed GFF file filtered by strand and genomic range', 'extract exon structure features from mRNA and exon records using parent-child ID relations', 'filter GFF records by feature type, strand, and genomic range', 'create a Matrix from a CSV or TSV file path to parse chord diagram data', 'create a Matrix from a from-to table file or DataFrame with optional sorting order', 'build chord diagram links and sectors from a Matrix for plotting with Circos', 'sort a Matrix by ascending or descending node size or custom label order', 'convert a Matrix to a from-to table DataFrame for downstream processing', 'parse a CSV or TSV file into a pandas DataFrame using the Table class parser', 'build stacked bar chart data with row sums, bar heights, and bottom positions from a table', 'generate a column name to color mapping dict using a specified colormap for table visualization', 'calculate radius limits and label positions for horizontal bar plots on a circular track', 'create tooltip strings for a specific row in a radar table with column name and value pairs']
```

Usage

```
{'parse_table_data': 'parse a CSV or TSV file into a pandas DataFrame using the Table class parser', 'build_stacked_bar_chart_data': 'build stacked bar chart data with row sums, bar heights, and bottom positions from a table', 'generate_color_mapping': 'generate a column name to color mapping dict using a specified colormap for table visualization', 'calculate_radar_chart_positions': 'calculate radius limits and label positions for horizontal bar plots on a circular track', 'create_radar_chart_tooltip': 'create tooltip strings for a specific row in a radar table with column name and value pairs'}
```

