# Harvard Odyssey management scripts

A collection of scripts for managing the Harvard Odyssey cluster, including quantifying usage, identifying files that can be compressed, and more.

See the head of each script for a brief description and usage instructions.

All scripts are quite basic and can be improved in various ways, but they should be useful.

`bed_compress` - 

`calc_genomics_files_sizes` - calculate the size of common, uncompressed genomics file formats (based on file extension) in a set of directories

`calc_last_use` - output a timestamp for the last manipulated file in a set of directories

`calc_usage` - calculate the amount of data storage of all files in a set of directories that counts against the lab quota

`calc_usage.jobscript` - calls the above `calc_usage` program in a formal Slurm job script

`check_fairshare` - summarize current cluster fairshare state for lab

`check_job_parameters` - summarizes the Slurm run parameters of queued or running jobs

`check_storage_quota` - summarize current cluster storge usage in the `scratchlfs` and `holylfs` locations

`compressMaker` - automated compression of raw MAKER outputs

`compressRepMod` - automated compression of raw RepeatModeler outputs

`compressSupernova` - automated compression of raw Supernova outputs

`compressTrinity` - automated compression of raw Trinity outputs

`doc_template.md` - template markdown file for creating documentation of programs or scripts

`fastq_compress` - Slurm job script for compressing all larger (>100 MB) FASTQ files in a directory using GZIP

`gff_compress` - Slurm job script for compressing all larger (>100 MB) GFF files in a directory using BGZIP/TABIX

`intrun` - start up an interactive session so commands are not run on login nodes

`jobscript_template` - write a job script template to the terminal for help creating a new job script

`sam_compress` - Slurm job script for compressing all larger (>100 MB) SAM files in a directory to BAM

`switch_partition_all` - switch the run partition of all queued jobs

`switch_partition_single` - switch the run partition of a single queued job

`switch_time_all` - change the time limit of all queued jobs

`switch_time_single` - change the time limit of a single queued job

`vcf_compress` - Slurm job script for compressing all larger (>100 MB) VCF files in a directory using BGZIP/TABIX
