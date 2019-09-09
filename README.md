# PokeApp
SPA to test Angular


**Please follow the instructions below, once you have finished send an email to HR and make a pull request to review your work.**

Install packages:
`npm install`

Run:
`ng serve`

Run tests:
`ng test`


**Objective**
A company wants to build a Pokemon SPA demo using Angular as base framework to give the ability to any gamer to find and list any pokemon.
The company is worried about the user experience so you need to consider the followings constraints in your app:

    - Include a Form (input text and submit button) where the user could find an specific Pokemon by name.
    - List and present all the pokemon below the form (see [Get all](http://pokeapi.co/api/v2/pokemon)) with his own name and image (to get the image you should call [Get by name](http://pokeapi.co/api/v2/pokemon/bulbasaur/) for each pokemon previously listed).

    - If the user enters a pokemon name the app should filter the list by name.
    - If the input value is empty then the app should to present all the pokemon list.

If you want to consider to handle loading elements or pagination to increase the performance, it would give you some extra points.

**Evaluation metrics**
    - Readability
    - Solution
    - Maintainable
    - Performance

**Nice to have**
    - Unit Tests


## API
URL http://pokeapi.salestock.net/docsv2/


**Get all Pokemons**
URL: http://pokeapi.co/api/v2/pokemon
TYPE: GET 

**Get an specific pokemon by name**
URL: http://pokeapi.co/api/v2/pokemon/bulbasaur/
TYPE: GET 


