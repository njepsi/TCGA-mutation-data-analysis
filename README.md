# TCGA-mutation-data-analysis

Instructions
Create an HTML report (Rmarkdown) which shows requested and relevant code and visualizations.

Data: TCGA mutation data Clinical data Linking mutation data and clinical data:

Clinical data column: “bcr_patient_barcode”

Mutation data: first 12 characters of “Tumor_Sample_Barcode”

Using mutation data from TCGA (filtered for genes in COSMIC) and the associated clinical data:

Create a plot which shows the frequency of KRAS mutations (column “Hugo_Symbol”) by cancer type sorted from most frequently mutated to least.
X-axis: cancer type (column “type” in clinical data), Y-axis: frequency of mutations
Create the same plot from (1) but filter out Silent mutations (column “Variant_Classification”)
Create a plot which shows the number of amino acid changes within KRAS (column “HGVSp_Short”).
X-axis: amino acid change, Y-axis: frequency of mutations
Which cancer type has the most frequent G12D KRAS mutations?
Raw numbers
Percent (the clinical data sheet for TCGA can be used as the manifest for this code test)
Is there any association between age and KRAS mutation status (mutated or WT in pancreatic cancer (type==”PAAD”)?
