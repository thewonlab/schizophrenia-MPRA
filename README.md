# README for SCZ MPRA
created by sool_lee@unc.edu
08/08/2022

## BEFORE RUNNING SCRIPTS

0. Download FASTQ files and its respective _bcreads.txt file from GEO (...)
1. Either git clone or download our files and scripts to your local/virtual environment.
2. Modify config_scz.yml file within files/ folder (You only need to modify first two variables). 
  2-1. Modify script_dir: to identify where the scripts/ from github are stored.
  2-2. Modify scz_file_foldername: to identify where the files from GEO are stored. 
  2-3. Modify output_file_dir: to identify the location of the mpra result.
3. Depending on the option that you chose above either run:
  3-1. run generate_mpra_result_from_count_fastq
  3-2. run generate_mpra_result_from_count_matrix: You can also start from this step by download DNA/RNA count matrix file from GEO (...) 

## RUNNING SCRIPTS
- for option 1:
1. using generate_mpra_result_from_fastq, modify line 11 to identify the location of confiz_scz.yml file
- for option 2:
1. using generate_mpra_result_from_count_matrix, modify line 11 to identify the location of confiz_scz.yml file

## REFERENCE
Please cite this paper: Jessica C. McAfee, Sool Lee, Jiseok Lee, Jessica L. Bell, Oleh Krupa, Jessica Davis, Kimberly Insigne, Marielle L. Bond, Douglas H. Phanstiel, Michael I. Love, Jason L. Stein, Sriram Kosuri, Hyejung Won. Systematic investigation of allelic regulatory activity of schizophrenia-associated common variants
