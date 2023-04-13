# Pokédex App
It is an application that allows us to consume information about all the PoKemons from an API to display a list of Pokémon with their images, names, types, weaknesses and size and weight information.

## The URL of the API that displays the list of PoKemons as images:
[API](https://pokeapi.co/api/v2/pokemon/) 

<img src="https://github.com/Amellalzakaria/Pokemon_Android_App-api/blob/master/pokes.jpeg" width=200>

HttpURLConnection est utilisé pour récupérer des données depuis une URL distante qui contient les informations sur les Pokemons en utilisant la méthode GET. 
On récupère le contenu JSON de la page qui est ensuite converti en objet JSONObject en utilisant InputStreamReader. 

Une fois que les données sont récupérées, elles sont stockées dans une ArrayList de Pokémons et utilisées pour créer un adaptateur personnalisé (MyAdapter) qui est ensuite utilisé pour remplir la GridView. Lorsque l'utilisateur clique sur un élément de la GridView, une activité de détail (detailActivity) est lancée pour afficher des informations détaillées sur le Pokémon sélectionné.
## L'URL de l'API qui affiche les détails du PoKémon selon son {id ou nom}: 
[API/{id ou nom}](https://pokeapi.co/api/v2/pokemon/) - ajouter l'id ou le nom aprés le /

<img src="https://user-images.githubusercontent.com/81178741/230798573-a3d5969f-037c-45d5-a347-2f5ea5089a6b.jpeg" width=200>
