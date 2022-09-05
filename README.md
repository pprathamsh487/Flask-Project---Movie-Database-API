# Flask-Project---Movie-Database-API
APIs to fetch movie details from MySQL database


1) Executed the Installing IMDbPy.ipynb file to extract data from website and store it into the MySQL database.
2) Extracted using Beautiful_soup library and stored in MySQL.
3) Created the Flask app to define various functions like:
 a) index() : To search movie by exact name
 b) index2() : To Search movie by Keyword
 c) sort_by_name() : To sort the movies by movie names and display output in paginated format.
 d) sort_by_rating() : To Sort the movies in ascending order of ratings
 e) sort_by_release_date() : To sort movies on the basis of movie release dates
 f) sort_by_duration(): To sort by ascending order of duration

Routes :
http://127.0.0.1:5000/by_keyword  - To search by keyword
http://127.0.0.1:5000/search_by_movie_name - To search By name
http://127.0.0.1:5000/sort/by_name  - To sort By name with Paginated Output
http://127.0.0.1:5000/sort/by_rating -  Sort By rating
http://127.0.0.1:5000/sort/by_duration - Sort By Duration


Templates : 1) sort_temp.html : To provide the button for sorting the data
2) normal_table.html : To display data in normal table
3) table.html : To display table in paginated fashion.
4) index.html : To provide textarea for searching movies and keywords
