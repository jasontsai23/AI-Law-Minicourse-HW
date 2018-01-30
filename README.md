# AI-Law-Minicourse-HW

step 1:

Importing the different functions we need (e.g., beautiful soup, panda, etc.).
Creating list of SCOTUS cases pulled from website ranging from 1760 to 2018.  Returns data in XML format.  

step 2:

Collect case details from URL and put into table and save.

step 3:

Processing the data by removing state names, case names, stopwords, people's names, day/month, non-words.
Lematizing means removing 'ing'.

step 4:

Trying different modelings methods such as LDA, LSA, and NMF.  

step 5:

Applying model to the data. 
	run the model against the data to collect topics.
	take model tand apply it back to data to assign most likely topics.
	make a dictionary of the components that make up each topic.
	use this dictionary to look up the topic components and apply to data. 
	gather data for presentation.    
