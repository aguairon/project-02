# General Assembly Project 2 : React Hackathon
### Timeframe
2 days. Collaborative project with 2 people.
## Technologies used
* React
* Bulma
* Node.js
* Express
* Request-promise with two public APIs (OMDB and movieglu)

## Hackathon: Movies website
<img width="1440" alt="Screenshot 2019-03-20 at 13 31 46" src="https://user-images.githubusercontent.com/9445433/54687883-8e47a580-4b14-11e9-9ef6-cc9267d9caa6.png">
A live version of this site can be found on Heroku ----> https://hackathon-movie-api.herokuapp.com/

### Website overview
Movies website is a simple website that allows users to search for their favourite movies, view their details and find cinemas near them.

In the homepage there is a selection of movies with the word Star in their title. But if the user wants to find other movies they have a search bar they can use. Once something has been typed, OMDB api will requested for new results every second.

<img width="1440" alt="Screenshot 2019-03-20 at 15 24 53" src="https://user-images.githubusercontent.com/9445433/54696786-5b0d1280-4b24-11e9-9dae-caffebbf81f1.png">

Or with a message indicating that no movie was found with that word.

<img width="1439" alt="Screenshot 2019-03-20 at 15 40 39" src="https://user-images.githubusercontent.com/9445433/54698194-cce65b80-4b26-11e9-8a7c-1cebe118910f.png">

Once the user finds a movie they wanted they can view the movie details. In this page they will have not only the metascore for the film, actors and plot for the selected movie but also the runtime, language and genre.

<img width="1437" alt="Screenshot 2019-03-20 at 15 31 16" src="https://user-images.githubusercontent.com/9445433/54697305-3a918800-4b25-11e9-9aa4-9ede3de402a1.png">

The user can also find cinemas near them on the Cinema Near Me tab where there is a button to find the user's location. Once the location is found the map will update to show the location and it will show markers with available cinemas.

<img width="1440" alt="Screenshot 2019-03-20 at 15 36 14" src="https://user-images.githubusercontent.com/9445433/54697702-ec30b900-4b25-11e9-9237-8c090da3ff67.png">

