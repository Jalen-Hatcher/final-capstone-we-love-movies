# final-capstone-we-love-movies
Final Capstone for Thinkful's Backend Web Development Course. This is a backend, RESTful API for a hypothetical web application "We Love Movies", which provides movie, critic, and critical review details for various movies.
# Database Tables
movies - Consists of a primary key movie_id, title, runtime_in_minutes, rating, image_url, and a description for each movie.

critics - Consists of critic-related information including a critic_id, preferred_name, surname, and organization name.

theaters - Consists of various theaters showing movies within the movies table. Columns include: theater_id (primary key), name (name of theater), address_line_1, address_line_2, city, state, and zip.

movies_theaters - Conjoining table representing a many-to-many relationship between movies and theaters. Columns include movie_id (foreign key to movies), theater_id (foreign key to theaters), is_showing (tells whether or not amovie showing at a particular theater).

reviews - Represents the reviews of critics in the critics table (many-to-one) for certain movies. Contains a review_id (primary_key), content (content of the review), score (score as supplied by a review), movie_id  
(foreign key to movies), critic_id (foreign key to critics).  
Here is an ERD for the database schema:  
![image](https://github.com/Jalen-Hatcher/final-capstone-we-love-movies/assets/140201552/dc887c8e-32f8-4d97-bad5-5fd9b7f7e8dd)


# Routes
See docs.
# Links
Backend: https://we-love-movies-dg2h.onrender.com  
Frontend: https://we-love-movies-front-end-07d5.onrender.com

