# ![title](app/assets/images/titlemd.png)

<h3 align="center">   Crew Members   </h3>
<h4 align="center"> ⭐️ Quinn Miller ⭐️ </h4>
<h4 align="center"> ⭐️ Christopher Cahill ⭐️ </h4>
<h4 align="center"> ⭐️ Daniel Burbach ⭐️ </h4>
<h4 align="center"> ⭐️ Robert Lee ⭐️ </h4>
<h4 align="center"> ⭐️ Ngan Nguyen ⭐️ </h4>

## Description

_This is a simple game of battleship where two players try to sink one another's ships._

## Table of content

- [Installation](#installation)
- [Deploy and Play Game](#play)
- [Technology](#technology)
- [License](#license)

## Installation

1. Go to terminal and clone this repository:
```
$ git clone https://github.com/quinnrobepicodus/battle-ships.git
```
2. Change into the project directory and install Gems
```
$ bundle
```
3. Create the Database:
```
$ rails db:create
```
```
$ rails db:migrate
```
4. To run the program:
```
$ rails s
```
6. Go to local host:
```
http://localhost:3000/games
```
## Play
* Click on New Game button to start game.
* To select placement for your ship, click on the board.
* Once all player's ship are placed, click on Update Game button.
* The game is now in session.
* Click a on the board where you think the opponent's ships might be.
* The computer or player 2 will immediately fire back.
* Repeat until someone wins.

## Technology
* Ruby 2.5.1
* Rails 5
* HTML
* CSS
* PostgreSQL
* Bycrpt

## License
* This project is licensed under the MIT License - see the LICENSE.md file for details
