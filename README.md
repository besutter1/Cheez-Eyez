# Cheez-Eyez
---

## A Top-Secret Project to Explore (some) National Cheeses

### What is the goal of this project ?
As interns at Cheez-Eyez, our goal is to artificially replicate cheese microbiomes of other national cheeses to flood the market with cheap imitations. For years spies around the world collected cheese samples. Finally, we as a secret union of soon-to-be pro computer scientist have the honorable opportunity to leak the secret of cheese and in the end eventually enabling the reverse engineering of the recipes. Yet scientist -us- don't know if this is feasible as possibly multiple factors influence the making of the highly classified national cheeses. Nevertheless, specific tasks need to be done in order to (maybe) achieve our goals. In this work we will try answer some questions with a focus on reaching our target. Two datasets with more than 300 samples were provided. Consisting of the sequences from the V4 region of 16S rRNA gene which were sequenced on an Illumina HiSeq machine. As well as a metadata table with information from each collected sample. The given datasets will be analyzed to answer the questions. Some of or research questions: 
1. Is possible to identify the “core microbiota” of different cheese variety. Furthermore, what taxa and individual ASVs can be found? What variety is more or less abundant? The cheese rind constitutes a complex ecosystem of microorganisms. Therefore samples of cheese rind of different type of cheese were collected and provided for the purpose of this project. 
2. What cheese type are most represented. Where are the samples coming from on a global scale. 
3. With results from these questions will then lead to the final question where factors will be compared to the results of the microbiota. Can there be factors found which influence the microbiota and then on a bigger scale the type of cheese? Or is there more which influences the different taste and type of cheese which cannot be determined with the data given?

### How did we proceed ?
We followed the content of the course and applied the new learnt code on our project. Depending on some of the outcomes we chose different statistical or abundance analysis to evaluate our data. 

### For usage of our code: How to Run the Project
As we used several branches to work on different topics we merged the branches into main at some point to have one main branch with every notebook needed to follow our doing step by step without having to switch branches. In the main branch we only then added some final touch (notes, some visualizations) to create a better understanding what we did at a certain point. 

We do hope everything is understandable and if not please contact one of the contributors to get insights. 
Have fun exploring !

Yours truly,
The secret cheese and bioinformatics lovers.

**Order of Notebooks and its Content: **

| Order   |      Notebook      |  Content/Goal |
|----------|:-------------:|------:|
| 1 | filedownload.ipynb |   downloading qza file with sequences and tsv file with metadata  |
| 2 |  metadata.ipynb | exploration of metadata nad generation of various visualizations |
| 3 |    denoising.ipynb   |    |
| 4 | taxonomy.ipynp |    taxonomic classification & phylogeny tree construction |
| 5 | taxonomy_full_length.ipynp |    usage of full length classifier instead of 515f/806r classifier (both greengenes) |
| 6 | diversity.ipynb |    diversity analysis (alpha and beta) |



| 8 | ancom.ipynp |    analysis of the differential abundance in our samples |
| 9 | metagenomics.ipynp |    analysis of functional pathways |
| 10 | core_microbiota.ipynp |   Identify "core" features |
| 7 | Interactive Map.ipynp |    geographic skew |