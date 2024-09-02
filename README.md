# postman-reflection

## 1 - Introduction to APIs

### Squirtle

  ![Squirtle get](pokSquirtle.jpg)

  * Name: Squirtle
  * Request URL: https://pokeapi.co/api/v2/pokemon/squirtle
  * Request was successful and returned a code 200
  * Returned characteristics such as: abilities, base experience, height
  
  ### Pidgey

  ![pokPidgey get](pokPidgey.jpg)

  * Name: Pidgey
  * Request URL: https://pokeapi.co/api/v2/pokemon/pidgey
  * Request was successful and returned a code 200
  * Returned characteristics such as: abilities, base experience, height

  ### Kahuna

  ![pokKahuna get](pokKahuna.jpg)

  * Name: Kahuna
  * Request URL: https://pokeapi.co/api/v2/pokemon/kakuna
  * Request was successful and returned a code 200
  * Returned characteristics such as: abilities, base experience, height


## 2 - Exploring the Weather API

  * URL = https://api.weatherbit.io/v2.0/current/?city=New+Orleans&key={{APIVar}}
  * Parameters: City and Authorization key
  * Request was successful with expected weather related details.

    ![weatherapi New Orleans get](weatherNola.jpg)
    

Postman query parameters are specific to the API with strong adherence to syntax.

## 3 - Interacting with GitHub's API

### Get Repositories List

  * Create a new request
  * Select GET
  * Add URL ("https://api.github.com/user/repos")
  * No parameters necessary
  * Click Send

  ![GitHub API repo list get](getRepos.jpg)

  ### Create Repo

  * Create a new request
  * select POST
  * Add URL ("https://api.github.com/user/repos")
  * Select "Body" from options
  * Select "raw" from radio button options
  * Select JSON from dropdown menu
  * Add {"name":"anytexthere"} to initialize new repo
  * Click Send

  ![GitHub API new repo post](createRepo.jpg)