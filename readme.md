# Library Catalog App

1. The Static IP address for this project is 54.200.117.233 and port 2200 is available for SSH
2. The website can be viewed at http://54.200.117.233.xip.io/
3. This is a Flask/SQLalchemy website written in Python 2. It is installed on a Ubuntu based server on Amazon's Lightrail Service. Ubuntu was configured by adding 2 additional root users; updating all packages; adding a firewall that only allows communication on ports 80, 123, and 2200; disabling root access; creation of a login key; and requiring said key for login. Creation of the web app was done with the following packages:
    - Apache2, as the Http server
    - PostgreSQL, for Database management
    - psycopg2, for communication between Python and PostgreSQL
    - Flask, as a web framework
    - SQLalchemy, to simplify database operations
    - Oauth2, to allow Google Authentication and Login
4. This project was made possible with assistance from Stack Overflow, Xip.io, w3 Schools, and  of course my Udacity Lessons


This website creates a PostgreSQL database and is able to hold information on Users, Genres, and Books. Users are able to login and create Genres and Books using their Google account

Instructions:

1. Visit the website by going to http://54.200.117.233.xip.io/ in your preferred browser
2. To view JSONs of the Database you can go to
        a. `http://54.200.117.233.xip.io/library/JSON`
            For a JSON of all Genres
        b. `http://54.200.117.233.xip.io/genre/<int:genre_id>/JSON`
            For the JSON of the genre with whichever genre_id you specify
        c. `http://54.200.117.233.xip.io/book/<int:book_id>/JSON`
            For the JSON of the book with whichever book_id you specify


