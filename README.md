
1. Download the above 4 files 

2. Click on this link to view the license agreement and also the field names of each dataset  
[https://www.imdb.com/interfaces/](https://www.imdb.com/interfaces/)

3. Click on this link to view IMDb data files available for download.  
[https://datasets.imdbws.com/](https://datasets.imdbws.com/)    

Download the title.basics.tsv.gz  file and unzip it into the same location where you have put the tbasics.dbf file  
You will get a data.tsv file (tab separated value)

4. Start VFP10  
set default to the directory that you have the dbc and tsv file  
use tbasics  
append from data.tsv delimited with tab  

***







