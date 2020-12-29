1. Open the console 
2. Run the command "python create_tables.py"
3. Run the command "python etl.py"
4. open test.ipynb and run the cells to view the data
5. Schema design :
    Fact Table :
        1.songplay_table
    Dimension Tables :
        1.user_table
        2.song_table
        3.artist_table
        4.time_table
6. File Structure :
    1. sql_queries.py : Contains SQL to create and Insert Tables
    2. etl.py : Containes Business logic to extract the data and Store in the database.
    3. create_tables.py: contains logic to create and drop the tables
    4.test.ipynb : contains logic to verify the data in the tables