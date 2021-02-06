README FILE

PART-1

1.  2020-12-12scotusPreprocessingVisualizationPipelinesFinal.ipynb

A.  This file is a consolidation of multiple ipynb notebooks.

B.  The preceding notebooks were built on Anaconda Jupyter, Google Colab, and Azure DataBricks.

2.  To run the file from Google Colab:

	A.  Download the 512 MB original all_opinions.csv file from https://www.kaggle.com/gqfiddler/scotus-opinions

		1.  Unfortunately, I could not upload files of this size onto my github portal.

		2.  Parquet Output from the pipeline is currently locked in my Databricks account.  

	B.  Upload all_opinions.csv to the content folder

	C.  As of 12 December 2020, the pre-processing file runs without error upto Section D.  Prepare Data for Export, Save pyspark to Parquet
	
		1. As this step has worked on other platforms, there is no reason to believe that Google would eventually complete the task.

		2.  If attempted, expect the task to take many minutes, if not hours to complete on Google Colab.  

		3.  The csv transformation aslo is very slow.  After multiple attempts, lost patience with the task.  This step worked in the prototype pipeline.  

		3.  If successful, the new Parquet file is uploaded into a Pandas DataFrame for use in part III.

	D.  All visualization computations and code were implemented in DataBricks.  As such, this code has not yet been tested in Google Colab.

		1.  The DataBricks-derived output of matplotlib and plotly display in Google Colab.

	E.  The Machine Learning Code is a product of Durga Prasad.  His portion requires additional unlisted steps.

		
Thanks,

Ismael Rodriguez


PART-II

1. 2020-12-12_ScotusMachineLearningPipelinesFinal.ipynb

2. This Machine Learning code is done in the seperate ipynb notebook on the pre-processing output generated previosuly with PART-1 on sample datasset(n=1000)
	( Please note Final PART-1 processed Ouput is for complete dataset and is not used for modelling and code is not shown in part for generating pre-processed sample dataset output.)

A. Input file used for Machine learning part pysparkSCOTUSml.json is uploaded in the data folder along with project.

3. The ouput model Scotus_Final_Model.csv which is in data/output for visualization (Used for presentation puporse)

Thanks,
Durga Prasad Sarilla 




