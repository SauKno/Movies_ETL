## Movies_ETL
# Purpose
The project included extracting a large data set from Kaggle, then transforming the data into a usable dataset for a "hacking competition." Once the data was transformed and narrowed in scope for the hack-a-thon, the DataFrames were loaded into PostgresSQL.

# Extracting
Wikipedia Movies JSON file, starting with 193 Columns:
<img width="1107" alt="Screen Shot 2022-03-28 at 5 52 40 PM" src="https://user-images.githubusercontent.com/94129215/160493456-4bbb4365-3421-43a8-88f1-312c5151a3aa.png">

Kaggle Movie Metadata, 24 columns:
<img width="747" alt="Screen Shot 2022-03-28 at 5 53 27 PM" src="https://user-images.githubusercontent.com/94129215/160493544-7a859450-6ae9-4014-8b50-b892ffefb0d6.png">

Kaggle Ratings data, 2602489 rows by 4 columns

<img width="449" alt="Screen Shot 2022-03-28 at 5 55 59 PM" src="https://user-images.githubusercontent.com/94129215/160493871-bff6301f-db62-4b9c-abf1-99fd406e0458.png">

# Transforming
Wikipedia Movies transformed, 22 columns

<img width="739" alt="Screen Shot 2022-03-28 at 5 57 03 PM" src="https://user-images.githubusercontent.com/94129215/160494070-41ed8845-8cd5-4f08-8fa2-c7d94a2d2c7a.png">

Wikipedia Movies, making the column names more succinct and uniform, 7033 rows of data

<img width="763" alt="Screen Shot 2022-03-28 at 5 57 54 PM" src="https://user-images.githubusercontent.com/94129215/160494162-25f887b4-f9b1-4037-a0ed-356ac7767257.png">

Kaggle Data
Wikipedia Movies merged with Kaggle Movies data, all column names and row counts, 6052 rows. 

<img width="654" alt="Screen Shot 2022-03-28 at 6 00 23 PM" src="https://user-images.githubusercontent.com/94129215/160494453-82582b28-cbfb-4f45-a8b1-395d9925c8e5.png">

Merged Movies with Kaggle ratings, all of the column names and row counts, 6052 rows.

<img width="654" alt="Screen Shot 2022-03-28 at 6 00 23 PM" src="https://user-images.githubusercontent.com/94129215/160503297-9c2cb7d9-8b99-410d-b7e6-497e33db6987.png">

