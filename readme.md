The project Structure is defined as follows:

|---- Readme.md			<- Top-Level Readme file for the project
|---- data				
|   |---- raw			<- The original data dump
|   |---- interim		<- Intermediate data after transformations
|   |---- processed	<- The final data sets used for modeling
|
|---- documents			<- Project documents explaining the steps and decisions made
|
|---- models         	<- Trained and serialized models, model predictions
|
|---- notebooks			<- Jupyter Notebooks. 
|						   Naming Convention: <int(for ordering)>_<initials(creators initials)>_<short `-` delimited description> 
|						   e.g. 1.0_av_initial-data-exploration
|
|---- reports			<- Generated analysis in HTML, PDF etc
|   |---- figures		<- Graphs and figures to be used in reports
|
|---- requirements.txt	<- pip freeze requirements. `pip freeze > requirements.txt
|
|---- src				<- Source Code for use in the project
|   |---- __init__.py	
|	|---- data_extraction.py
|	|---- data_preparation.py
|	|---- build_features.py
|	|---- train.py
|	|---- predict.py
|	|---- util
|	|  |---- _*.py		<- any helper functions for main python scripts
|	|
|	|---- tests			<- unit and integration tests to check the proper functionality of code