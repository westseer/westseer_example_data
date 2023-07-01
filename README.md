# westseer_example_data
This repository proivdes a backup database for testing WESTSeer. The original data source is OpenAlex, but OpenAlex has rate limits in downloading speed, so collecting data directly from OpenAlex takes many hours. Thus, we have a backup in this repository to avoid repeating the slow collecting process. 

The backup database is a sqlite file. The file name before compression is database.sqlite. The file is compressed with 7Zip and segmented into 7 segments to be allowed submission to Github. 

To obtain the backup database file (i.e., database.sqlite), first download the seven segments, i.e., from database.zip.001 to database.zip.007, then decompress using 7Zip. 

To import the backup database file into WESTSeer, select "File" -> "Options" from menu and then set "Path of Database" in "General" to the path of the database file.
