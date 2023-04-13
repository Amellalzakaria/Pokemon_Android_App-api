# Pokédex App
The Pokédex App is a useful tool for Pokémon enthusiasts who want to quickly access information about their favorite Pokémon. The app utilizes an API provided by the PokeAPI to display a list of Pokémon with their corresponding images, names, types, weaknesses, size, and weight information.

## The URL of the API that displays the list of PoKemons as images.
[API](https://pokeapi.co/api/v2/pokemon/) 

<img src="https://github.com/Amellalzakaria/Pokemon_Android_App-api/blob/master/pokes.jpeg" width=200>

The HttpURLConnection method is employed to fetch data from a remote URL that contains Pokemon-related information using the GET method.
The JSON content of the webpage is obtained, and subsequently transformed into a JSONObject using an InputStreamReader. 

To retrieve the data from the PokeAPI, the app employs the HttpURLConnection method to fetch the data from the API's URL using the GET method. The JSON content of the webpage is obtained, and then converted into a JSONObject using an InputStreamReader. The data is then stored in an ArrayList of Pokemon objects, which is utilized to populate a GridView using a custom adapter called "MyAdapter."

When the user selects a specific Pokémon from the GridView, the app initiates a detail activity (detailActivity) that displays more detailed information about the selected Pokémon. This detail activity retrieves data from the API based on the Pokémon's ID or name, which is included in the URL of the API.

## The API URL displays the details of a specific Pokemon based on its ID or name.
[API/{id or name}](https://pokeapi.co/api/v2/pokemon/)

<img src="https://github.com/Amellalzakaria/Pokemon_Android_App-api/blob/master/pokes2.jpeg" width=200>

Overall, the Pokédex App is a valuable resource for Pokémon enthusiasts who want to quickly access information about their favorite Pokémon. The app's use of the PokeAPI ensures that the data is up-to-date and accurate, making it a reliable source of information.
