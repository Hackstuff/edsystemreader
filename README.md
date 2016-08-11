# Elite Dangerous System Reader

## Summary

System Reader for Elite Dangerous. It is expected to become an app ecosystem.

## Technical information

- *creation date*: 2016-08-11
- *last update*: 2016-08-11
- *team*:
  - @painatalman
  - @bomany
  - @pleaseinsertyournamehere

## Objectives

- provide real-time info to [*Elite Dangerous*](https://www.elitedangerous.com/) users regarding their experiences with the game. The info provided by this family is mostly related to the player's current position in the game world, including:
  - dominant faction
  - population
  - number of planets
  - :heart:
- allow users to search for info regarding a specific system, also related to his/her current position (like distance from it to the requested system)
- record player data, like routes taken and planets/systems visited, for later research and statistics

## Phases

- get player location data
- get system-related info (via API)
- obter informação sobre um sistema definido pelo jogador
- renderizar a informação na aplicação

## Processo

### Informação de localização do jogador

- desenvolvimento de uma aplicação que monitorize o ficheiro que regista o paradeiro do jogador, em tempo real, e retorne ou o id ou o nome do sistema

### Informação sobre um sistema

- api que receba e processe informação de um sistema com base no nome ou id do mesmo ([eddb])

## API e 3rd party

- netlogmonitor
- [eddb](https://eddb.io/)

## Technologies used

- react
- nodejs
- react native

## Glossary

- Elite Dangerous
- system
- planet
- 

## Planos futuros

- processar informação sobre o utilizador e nave do mesmo
- desenvolvimento de uma base de dados própria, que seja atualizada todos os dias
- nota pessoal em cada sistema, possibilitar um registo

