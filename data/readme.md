####Folder Organization

`data/legacy` contains data that has been collected by MTC/ABAG staff. Some of the files may be duplicates. Metadata is not standardized, but there appears to be some text files and an `about` tab in some of the excel files.  

`data/geojson` contains geojson represenations of the shapefiles in `legacy` for inspection purposes.

Source that were unwieldy for git can be found below. These files represented housing across the entire US. We selected only observations from these data that were within the 9 counties of the Bay Area and put them in the 'data/geojson' folder in this repository.   

https://s3-us-west-2.amazonaws.com/deed-restricted-housing/HUD_LIHTCProjects.zip

https://s3-us-west-2.amazonaws.com/deed-restricted-housing/NHPD_Extract_03_14_2012.xls.zip

https://s3-us-west-2.amazonaws.com/deed-restricted-housing/PublicHousing.zip

