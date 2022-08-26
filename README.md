# movie-library
Fasal (Wolkus Technology Solutions Private Limited) Movie library to add in public or private playlist


## Requirements

1.	The application must have user authentication ( Sign In/ Sign Up )
2.	After logging in users will be navigated to the home screen where they should see a search option where they can search movies and see details of those movies.
3.	They can create a list of movies by adding the movies to lists. ( Similar to youtube playlists ). On the home page, different movie lists created by that user will be displayed.
4.	These lists can be either public ( anyone with a link to the list can see this ) or private ( only the person who created can see this list )
5.	You can use OMDB API for the movie search option.
6.	The Search & List page should have a nice layout, take inspiration from other websites/applications.
7.	Include Steps to run ( Readme file ) in the project as well.
8.	You must host their projects online and provide working links of the application as well as code. ( e.g. Netlify, Vercel, Heroku, JSBin etc. )

## Getting Started

1. You must have `Python` installed on your system.
2. Visit `https://www.omdbapi.com/apikey.aspx` and get your API KEY
3. clone project using https://github.com/Akashmodi371/movie-library.git
4. Run `pip install -r requirements.txt` to download all the dependencies.
5. In your terminal, `cd` into the `fasal-movies-library-master` directory
6. Run `python manage.py makemigrations movies` to make migrations for the `movies` app.
7. Run `python manage.py migrate` to apply migrations to your database.
8. Navigate to movies->static->movies->index.js and on line 45 replace 'API_KEY' with your API KEY.
9. Run `python manage.py runserver` to start the Django web server.
10. Visit the website in your browser at local host.


## Heroku

Website: [Movie library](http://fasalmovielibrary.pythonanywhere.com/)





