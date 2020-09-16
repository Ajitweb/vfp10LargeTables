

Download the above zip file and unzip it
You will find the following files
imdb.dbc
imdb.dct
imdb.dcx
tbasics.dbf

Click on this link to view the license agreement and also the field names of each dataset
[](https://www.imdb.com/interfaces/)

Click on this link to view IMDb data files available for download.
https://datasets.imdbws.com/
Its in compressed format. When you uncompress it you will find the data in tsv format (tab seperated values)

Download the title.basics.tsv.gz  file and unzip it into the same location where you have put the tbasics.dbf file
You will get a data.tsv file

Start VFP10
set default to the directory that you have the dbc and tsv file
use tbasics
append from data.tsv delimited with tab









