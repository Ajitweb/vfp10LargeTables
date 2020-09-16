VFP10 breaks the barrier of 2GB limit and supports large table. If you want to experiment with large tables, then here are empty tables which can be populated with imdb data  

VFP Advanced (VFP version 10) is available at [http://www.baiyujia.com/vfpadvanced/f_vfpa_about.asp](http://www.baiyujia.com/vfpadvanced/f_vfpa_about.asp)  
Please note that you need to have the licensed version of Microsoft Visual Foxpro 9.0, installed in your PC, before installation of VFP10.

1. Download the 4 files into a directory  
   imdb.dbc   
   imdb.dct   
   imdb.dcx   
   tbasics.dbf   

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







