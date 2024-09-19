# Acropora palmata Field Transcriptomics
Transcriptomic analysis of 4 genets of Acropora palmata at 3 reef sites in the Florida Keys over a year period.

All raw reads are avaliable on the NCBI under project number PRJNA1081901

Folder **rscripts** has the following
- *Apal_outplant_rnaseq_full_pipeline.Rmd* = full bioinformatic pipeline
- *POR_seq_depth.Rmd* = script to work out alignment rates of the samples
- *differing_filt_thresholds.Rmd* = PCA analysis of the sample using different filtering thresholds as requested by reviewer 2. 

Folder **rdata_objects** has the objects needed to run entire pipeline.  
  
Folder **images** holds images for this readme.  
  
Folder **spreadsheets** has spreadsheets needed within the rscripts. 
  
  
![alt text](https://github.com/benyoung93/acropora_palmata_field_transcriptomics/blob/main/figs/filt_5countsgene_allsamples.png)

**Figure 1**: Using filtering criteria of 5 counts per gene in all samples retains the identified surrogate variable and genet being the main driver of the variance.   
  
  

![alt text](https://github.com/benyoung93/acropora_palmata_field_transcriptomics/blob/main/figs/filt_10countsgene_80percentsamples.png)

**Figure 2**: Using filtering criteria of 10 counts per gene in 80% of samples again retains the identified surrogate variable and genet being the main driver of the variance.