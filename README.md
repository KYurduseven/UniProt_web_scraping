# UniProt_web_scraping

UniProt_web_scraping program is determining subcellular localizations (only membrane and secreted proteins) of the proteins.

This program has written within a Master's thesis and an article (DOI: 10.1089/omi.2022.0023). 

The algorithm accepts the Universal Protein Resource (UniProt, www.uniprot.org) IDs of proteins as input, then accesses the UniProt website, obtains the HTML files, and searches for the specific localization keywords in the resulting HTML data. 

Warning! Protein_List.csv , Desired_Proteins_with_keywords_Part.xlsx documents have to be in the same folder. 

The UniProt ID of each protein should be listed one after the other in a Protein_List.csv file. Example:
Q9Z0X1
Q9Z0X4
Q9Z103
Q9Z105
.
.
.
