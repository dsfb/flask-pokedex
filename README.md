![Logo](https://fontmeme.com/permalink/200606/818570bc607f21d6e1c98e2e3fa6185b.png)





### How to run:

- Open **/flask-pokedex /pokedex**
- Install requirements
```python
 pip install -r requirements.txt
```
- Run the project :tada:
```python
 python app.py
```

###### Endpoint
- /pokemons

#
#

###### Why not bring more information about pokemons?


[PokéApi](https://pokeapi.co/) provides some endpoints. Reading the [docs](https://pokeapi.co/docs/v2) I realized that the endpoint **/pokedex** makes available the list of all pokemons at once but if I want specific information for each pokemon I would have to access the endpoint of each one. 

In **/pokedex** I would be able to render all pokemon with just one request. And to access the information of each pokemon I would need to make 151 requests in the API per access in the application being blocked by the API.