# Harvard Odyssey management scripts

A collection of scripts for managing the Harvard Odyssey cluster, including quantifying usage, identifying files that can be compressed, and more.

See the head of each script for a brief description and usage instructions.

All scripts are quite basic and can be improved in various ways, but they should be useful.

`calc_genomics_files_sizes` - calculate the size of common, uncompressed genomics file formats (based on file extension) in a set of directories

`calc_last_use` - output a timestamp for the last manipulated file in a set of directories

`calc_usage` - calculate the amount of data storage of all files in a set of directories that counts against the lab quota

`check_fairshare` - summarize current cluster fairshare state for lab

`check_storage_quota` - summarize current cluster storge usage in the `scratchlfs` and `holylfs` locations

`compressMaker` - automated compression of raw MAKER outputs

`compressRepMod` - automated compression of raw RepeatModeler outputs

`compressSupernova` - automated compression of raw Supernova outputs

`compressTrinity` - automated compression of raw Trinity outputs

`fastq_compress` - Slurm job script for compressing all larger (>100 MB) FASTQ files in a directory using GZIP

`intrun` - start up an interactive session so commands are not run on login nodes

`jobscript_template` - write a job script template to the terminal for help creating a new job script

`sam_compress` - Slurm job script for compressing all larger (>100 MB) SAM files in a directory to BAM

`switch_partition_all` - switch the run partition of all queued jobs

`switch_partition_single` - switch the run partition of a single queued job

`switch_time_all` - change the time limit of all queued jobs

`switch_time_single` - change the time limit of a single queued job
