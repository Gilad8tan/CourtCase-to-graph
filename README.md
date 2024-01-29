# CourtCase_to_graph
pipeline for cross citation graph modeling.

SeleniumSearchAndDownload.ipynb is the selenium script i used to automate search and downloading court rulings.

splitterIdMatcher.ipynb splits the cases to find who is the ruling judge and which other judges are mentioned in case (cited) and matches names, then returns grapgh edges by internal idNum in CSV .

