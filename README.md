# What do these scripts do?
Analyzing competing patents in order to come up with solutions to build supply chains or finding locations to expand.
These files will help you dealing with your patent data retrieved by the European Patent Office. It will wrangle your data and also creat geographic plots with simplified status of each patent (granted or not granted). Further information of the status of each patent can be discovered in the "Prepared_Data" folder.

# Why?
Patentdata are hard to handle if you don't have a Data Analyst or if you don't buy tools in order to handle them.

# How to use it?
Inside the "Capstone_Project" folder there are various files. First, use the "datapreparation" file in order to wrangle the raw data and to expand the data by additional information, which are retrieved by the European Patent Office in the "TranslationData" folder. The wrangled data will be saved as .xlsx and .csv. Second, Use either the datavisualization_assignee_filter or the datavisualisation_publication_number_filter file. You can either type inside the Script a company's name or a publication number which is available in the raw data. Then, plots will be automatically generated inside newly generated folders named by the company the patent belongs to.
