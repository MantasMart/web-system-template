# WEB system
- [ ] Meal recipe search system

## Description
- [ ] The web system is for helping people find meal recipies based on specified category or ingredient.

## Entity definition
Meal Recipe:
   
      ID - number  

      Meal – string (length - 40)

      Category - string (length - 20)

      Instructions – string 

      Ingredient(s) - string[] (length - 20)

      Ingredient measure(s) – string[]  (length - 20)

      Tags - string (length - 20)


## API definition
GET full meal details by id - https://www.themealdb.com/api/json/v1/1/lookup.php?i={id}

GET meal by name - https://www.themealdb.com/api/json/v1/1/search.php?s={name}

GET list all ingredients - https://www.themealdb.com/api/json/v1/1/list.php?i=list

GET meal by ingredient - https://www.themealdb.com/api/json/v1/1/filter.php?i={ingredient}

GET list of all categories - https://www.themealdb.com/api/json/v1/1/list.php?c=list

GET meal by category - https://www.themealdb.com/api/json/v1/1/filter.php?c={category}


## UI definition
https://wireframe.cc/1Cn8Iz

https://wireframe.cc/FUdmoG
