# README for SCZ MPRA
created by sool_lee@unc.edu
08/08/2022

## BEFORE RUNNING SCRIPTS

0. Download files files from _GEO_ (...)
1. Git clone or download our files and scripts to your local/virtual environment.
2. Modify _config_scz.yml_ file within _files/_ folder (You only need to modify first three variables). 
    - Modify _script_dir:_ to identify where the scripts/ from github are stored.
    - Modify _scz_file_foldername:_ to identify where the files from GEO are stored. 
    - Modify _output_file_dir:_ to identify the location of the mpra result.

## RUNNING SCRIPTS

0. Generate MPRA results:
    - run _generate_mpra_result_from_count_fastq_ if you want to generate MPRA results from FASTQ files
    - run _generate_mpra_result_from_count_matrix_ if you want to generate MPRA results from DNA/DNA count files (these files are preprocessed, merged, and modified FASTQ files.
1. MPRA result will be created within the folder you specificied above (_output_file_dir:_).

## REFERENCE
Please cite this paper: Jessica C. McAfee, Sool Lee, Jiseok Lee, Jessica L. Bell, Oleh Krupa, Jessica Davis, Kimberly Insigne, Marielle L. Bond, Douglas H. Phanstiel, Michael I. Love, Jason L. Stein, Sriram Kosuri, Hyejung Won. Systematic investigation of allelic regulatory activity of schizophrenia-associated common variants
