# CourtCase_to_graph
pipeline for cross citation graph modeling.

pipelineVisualization.pdf is exactly what it sound like.

SeleniumSearchAndDownload.ipynb is the selenium script i used to automate search and downloading court rulings.

splitterIdMatcher.ipynb splits the cases to find who is the ruling judge and which other judges are mentioned in case (cited) and matches names, then returns grapgh edges by internal idNum in CSV .

edgesExampleOutput.csv is a short version to understand output,just internal ids in ID1;ID2 format to later use in graphing software/code. 

