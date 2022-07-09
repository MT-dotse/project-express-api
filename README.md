# Express API Project 🎥

I created my first **RESTful** API using Express in Node. This API have series of endpoints which returns both a collection of data and single results. In order to create the different endpoints I used methods such as: **find(), filter(), and slice()**. To show the the API in use, I created a simple frontend. Overall a great learning experience to have built both the backend and frontend.

## Documentation

### Collection of results using query params

<b>GET/shows </b>
This endpoint returns all the Netflix showes.<br>

<b>GET/shows?type= </b>
This endpoint returns data by the given type e.g 'movie' and 'tv show'.<br>

<b>GET/shows?country= </b>
This endpoint returns data by the given country. <br>

<b>GET/shows?release= </b>
This endpoint returns data by the given release year.<br>

<b>GET/shows?cast= </b>
This endpoint returns data by the given actress/actor e.g. 'Halle Berry', and 'Bruce Willis'.<br>

<b>GET/shows?genre= </b>
This endpoint returns data by the given genre e.g. 'drama', 'action' and 'comedy'.<br>

<b>GET/shows?director= </b>
This endpoint returns data by the given director name e.g. 'Martin, Scorsese' and 'Steven Spielberg'.<br>

### Single results using path params

<b>GET/id/:id </b>
This endpoint return a title based on the unique id e.g '70172928' to get the title 'War Horse'.<br>

<b>GET/title/:title </b>
This endpoint return a title based the given title e.g 'War Horse'.<br>

## View it live

You can view my app live here: https://mt-dotse-netflix-titles.netlify.app/

Repo for the Backend API: https://github.com/MT-dotse/project-express-api

API is live in Heroku here: https://mtdose-netflix-shows.herokuapp.com/
