# up_down_gene_regulation
This code can be used to determine the up, down, and normally regulated genes for RNAseq data. The code will write a separate csv file for upregulated and down regulated genes. The csv file format for RNA seq data is shown below. The file contains information on expression of genes for control and treatment sample. As this is my initial code, I did not use pandas at that time. Hence, the user needs to have gene name in column 6, protein information in column 8, gene expression for control in column 9 and gene expression for treatment group in column 10. This can be used to analyze a large data (e.g the data I used for this code has > 2000 rows). Users need to provide information on file name to read and file name to write to store upregulated and downregulated genes as an input. As an output, files will be written and information on the number of up, down and normally regulated genes will be provided along with a pie chart. 

<img width="809" alt="csv file" src="https://github.com/Laxmi-Dhungel/up_down_gene_regulation/assets/154451345/4395b064-92e0-4741-9d4f-c337292cbfc7">

<img width="470" alt="file_input" src="https://github.com/Laxmi-Dhungel/up_down_gene_regulation/assets/154451345/25e8c5fe-81d5-4d47-bd0c-7cd17d982d00">

![pie_chart](https://github.com/Laxmi-Dhungel/up_down_gene_regulation/assets/154451345/6ddb3e97-6d41-41e0-bd63-35096e2acf04)
