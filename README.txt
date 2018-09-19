# Library Catalog App

1. The Static IP address for this project is 54.200.117.233 and port 2200 is available for SSH
2. The website can be viewed at http://54.200.117.233.xip.io/
3. A summary of software you installed and configuration changes made. This is a Flask/SQLalchemy website written in Python 2. It is installed on a Ubuntu based server using the following packages
        * Apache2
        * PostgreSQL
        * psycopg2
        * Flask
        * SQLalchemy
        * Oauth2
4. This project was made possible with assistance from Stack Overflow, Xip.io, w3 Schools, and  of course my Udacity Lessons


This website creates a PostgreSQL database and is able to hold information on Users, Genres, and Books. Users are able to login and create Genres and Books using their Google account

Instructions:

1. Visit the website by going to http://54.200.117.233.xip.io/ in your preferred browser
2. To view JSONs of the Database you can go to
        a. http://54.200.117.233.xip.io/library/JSON
            For a JSON of all Genres
        b. http://54.200.117.233.xip.io/genre/<int:genre_id>/JSON
            For the JSON of the genre with whichever genre_id you specify
        c. http://54.200.117.233.xip.io/book/<int:book_id>/JSON
            For the JSON of the book with whichever book_id you specify


