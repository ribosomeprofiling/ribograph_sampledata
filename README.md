# Sample Data Files for RiboGraph

This repository contains sample ribo and gzipped fasta files for the [RiboGraph](https://github.com/ribosomeprofiling/ribograph) browser.

Users can either clone this repository or download the individual files to use in RiboGraph.

----

## Sample Files

We provide ribo and gzipped fasta files. 

## Ribo Files

Ribo files come from published ribosome profiling data. They contain ribosome footprint coverage for a range of footprint lengths at nucleotide resolution. For details, see [the documentation](https://ribopy.readthedocs.io/en/latest/ribo_file_format.html).

Human: [GSM3323389.ribo](https://github.com/ribosomeprofiling/ribograph_sampledata/raw/main/human/GSM3323389.ribo), [GSM3323390.ribo](https://github.com/ribosomeprofiling/ribograph_sampledata/raw/main/human/GSM3323390.ribo), [GSE105175.ribo](https://github.com/ribosomeprofiling/ribograph_sampledata/raw/main/human/GSE105175.ribo) (contains 6 samples)

Mouse: [GSE102318.ribo](https://github.com/ribosomeprofiling/ribograph_sampledata/raw/main/mouse/GSE102318.ribo) (contains 2 samples), [GSE105147.ribo](https://github.com/ribosomeprofiling/ribograph_sampledata/raw/main/mouse/GSE105147.ribo) (contains 7 samples)

More detailed information about these samples can be found in GEO; 
[GSE118239](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE118239) and [GSE105175](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE105175) for human samples and [GSE102318](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE102318) and [GSE105147](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE105147) for mouse samples.

## Fasta Files

We provide two gzipped fasta files which contain transcriptome sequences for human and mouse. These files were used as transcriptome references for generating the ribo files.

Human Reference: [appris_human_v2_selected.fa.gz](https://github.com/ribosomeprofiling/ribograph_sampledata/raw/main/human/appris_human_v2_selected.fa.gz)


Mouse Reference: [appris_mouse_v2_selected.fa.gz](https://github.com/ribosomeprofiling/ribograph_sampledata/raw/main/mouse/appris_mouse_v2_selected.fa.gz)

## Notes

While ribo files are essential for ribograph, reference fasta files are not. Without the reference files, RiboGraph will still display the contents of ribo files. The only missing functionality will be transcript sequences in the coverage view.  