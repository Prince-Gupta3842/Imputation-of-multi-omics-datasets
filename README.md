# Imputation-of-multi-omics-datasets
The medium through which a disease develops involves several events at various level of omics
such as transcriptomics, genomics and proteomics. However most of these omics data have been analyzed separately. The existing methods to integrate these omics data types are mostly based on conventional approaches like support vector machines and logistic regression. Advanced DL-based approaches are better suited for these types of data integration.

Multi-omics data included in our analysis:-

1.Transcriptomics : the complete set of RNA transcripts that are produced by the genome, under specific circumstances or in a specific cell
2. Proteomics : study of complete set of protein expressed by an organism.

DL models for multi-omics data analyses follows a common pipeline:

1.Data preprocessing
2.Feature selection or dimensionality reduction
3.Multi-omics variables are concatenated into a large dataset for data integration
4.Further feature selection or reduction techniques are applied
5.The integrated data are analyzed for classification, regression or clustering

Proteomic data were measured in blood plasma using a Slow Off-rate Modified Aptamer (SOMAmer)-based array called ‘SOMAscan’ (SomaLogic, Inc, Boulder, Colorado). Blood samples for the collection of gene expression data were taken at study baseline. Transcriptional profiling was performed in two batches using the Illumina HumanHT-12 v3 (batch one) and v4 (batch two) Expression BeadChip kits.

![image](https://user-images.githubusercontent.com/88485695/202242693-6e4dc9b5-7e7d-4349-bd6d-49760096d094.png)

Transcriptomics data:

![image](https://user-images.githubusercontent.com/88485695/202243032-e8393e82-ab9a-42fc-b693-9c4209c6b351.png)

Proteomics data:

![image](https://user-images.githubusercontent.com/88485695/202243112-174244c2-5459-45d9-aaac-efd69f359592.png)

Before Imputation:

![image](https://user-images.githubusercontent.com/88485695/202243290-b45ade47-db4a-4b6e-bac7-5cf501492953.png)

After Imputation:

![image](https://user-images.githubusercontent.com/88485695/202243338-06a4fd7e-31a3-48bd-a351-340fc9cd5f4b.png)

Average RMSE values obtained : 0.2874
