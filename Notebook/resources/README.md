# Notebook Examples
## Here are the gsutil URI you need to get the input to the notebook
  - transcriptome annotation `.gtf` file (e.g. GENCODE v37)
    - gencode.v37.annotation.gtf
      - gs://mdl-data/mas-seq-paper-data/resources/gencode.v37.annotation.gtf
  - genome assembly reference `.fasta` file
    - Homo_sapiens.GRCh38.dna.primary_assembly.fa
      - gs://mdl-data/mas-seq-paper-data/resources/Homo_sapiens.GRCh38.dna.primary_assembly.fa
  - MAS-seq array elements `.bam` file
    - M132TS_MAS_15x_annotated_array_elements_for_quant_with_gene_names.corrected_umis.bam
      - gs://fc-96c9438d-e3aa-4474-afd4-7a63653b5d51/results/M132TS_MAS_15x.m64020e_210506_132139/20221107_205409_857743484/annotated_array_elements/M132TS_MAS_15x_annotated_array_elements_for_quant_with_gene_names.corrected_umis.bam
  - Gene symbol to Gene ID map
    - gencode.v37.annotation.gs_to_gid_map.pkl
      - gs://mdl-data/mas-seq-paper-data/resources/gencode.v37.annotation.gs_to_gid_map.pkl

# TO DO
Parse input files from cloud [directly](https://github.com/pysam-developers/pysam/issues/592). 
- This approach will save a lot of memory requirements. 