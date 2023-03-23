# TicTacToe API

REST API для игры в крестики-нолики. 

## Endpoints:

* GET api/games: Получить список всех игр.
* GET api/games/{id}: Получить информацию о конкретной игре по ее id.
* POST api/games: Создать новую игру.
* PUT api/games/{id}: Сделать ход в игре по ее id.
* GET api/games/{gameId}/Moves/{id}: Получить конкретный ход в конкретной игре по id игры и id хода.
* GET api/games/{gameId}/Moves: Получить все ходы в конкретной игре по ее id.

## Requirements

* ASP.NET Core 6.0 SDK
* Visual Studio 2022
* SQL Server 2022
* SQL Server Management Studio 2019