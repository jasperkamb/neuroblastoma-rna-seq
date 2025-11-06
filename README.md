# neuroblastoma-rna-seq

# RNA-seq Analysis of Neuroblastoma Cell Lines
Analyzed RNA-seq data from 20 neuroblastoma samples (10 control, 10 treated) to evaluate transcriptional effects of an immunotherapy targeting the MYCN gene and associated transcription factors.

## Data & Methods
- Downloaded data from GEO (GSE164455) and processed on NYU Big Purple HPC  
- Workflow: FASTQC → TrimGalore → TopHat2/Kallisto → featureCounts → DESeq2  
- Differential expression, motif (MEME-ChIP), and pathway (GREAT, DAVID, IPA) analyses  
- Visualization using PCA, heatmaps, volcano plots, and IGV for genome exploration  

## Key Findings
Treatment modulated MYCN, PHOX2B, and ALK expression with varying effects across cell lines, uncovering transcriptional responses linked to tumor proliferation and immune regulation.  

## Tools & Skills
Bash, R, BioConductor, FASTQC, TrimGalore, TopHat2, Kallisto, DESeq2, MACS2, GREAT, IGV, DAVID, IPA
