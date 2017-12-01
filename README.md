# MSD Internship Task

MovieLens dataset:


26,000,000 ratings and 750,000 tag applications applied to 45,000 movies by 270,000 users. Includes tag genome data with 12 million relevance scores across 1,100 tags.

1.Read 1,000,000 lines of ratings csv file, in multiple threads each of which starts consuming from a random line, stop once 1million lines are read.

2.Parse the format and insert into a sqlite db using SQLAlchemy
