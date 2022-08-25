# T2D

T2D is a knowledge graph of food and nutrition for the management of type 2 diabetes.

The Food knowledge graph was constructed via GrapgDB RDF mappings toolkit. The resulting Food_onto2.ttl is the merged ontology of both the NEVO and FDC datasets. 

The food_data_central1 and NEVO2021_details were used to construct the food knowledge graph. The full data of bothe datasets can be found in the All data folder.

The **T2D_python jupyter notebook** contains the integration code implemented for merging both the food KG with the Diabetes guideline that is manually extracted.
As well as additional data visualization and sparql queries are done in the jupyter notebook. 

The Final_onotlogy_2.ttl is the merged Food and Diabetes guideline and can be loaded to a SPARQL endpoint for querying. 

The competency_questions.txt file contains the competency questions used to scope the ontology as well as the RDF mappings of both the NEVO and FDC datasets.

The results csv contains the output of running the competency questions query into the Final_onotlogy_2.ttl file and the results are saved in csv format. We have 
constructed 12 CQ to test the ontology. 
