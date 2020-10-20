# The Hockey Game

[Home Assistant Core](https://home-assistant.io/) in [docker](https://www.docker.com/) on a  [Synology DiskStation DS918+](https://www.synology.com/products/DS918+). My use case is a [wall mounted](https://www.durable.eu/information-and-presentation/tablet-holder/wall-mounted-tablet-holder/tablet-holder-wall.html) tablet [[Samsung 10.1"](https://www.samsung.com/us/mobile/tablets/galaxy-tab-a/galaxy-tab-a-10-1-2019-32gb-black-wi-fi-sm-t510nzkaxar/)] displaying Home Assistant in [Fully Kiosk Browser](https://www.ozerov.de/fully-kiosk-browser/).

## Components

### Game Board

![screenshot](https://github.com/Tanner3644/the-hockey-game/blob/main/screenshots/Game%20Board.png)

* Monthly layout following the timeline of the NHL off-season, pre-season, regular season and playoffs
* Color coded card layout regions included on the board for quick setup
* Score matrix included on board to quickly calculate score based off of team overall and dice roll

### Player Cards

<img src="https://github.com/Tanner3644/the-hockey-game/blob/main/screenshots/1%20-%20Evans.png" width="200">  <img src="https://github.com/Tanner3644/the-hockey-game/blob/main/screenshots/5%20-%20Gill.png" width="200">  <img src="https://github.com/Tanner3644/the-hockey-game/blob/main/screenshots/2%20Willis.png" width="200">

<img src="https://github.com/Tanner3644/the-hockey-game/blob/main/screenshots/41%20-%20Vega.png" width="200">  <img src="https://github.com/Tanner3644/the-hockey-game/blob/main/screenshots/40%20-%20Walters.png" width="200">  <img src="https://github.com/Tanner3644/the-hockey-game/blob/main/screenshots/14%20-%20Doig.png" width="200">

* There are 54 player cards
* 18 player cards in each draft round (1-3, green-red)
* Each player card has an overall from 1-4 stars
* Each player has salary depending on there overall
  * 1-2$M for 1 Star player
  * 2-6$M for 2 Star player
  * 7-11$M for 3 Star player
  * 14$M for 4 Star player

The breakup of player cards can be seen in the tables below

#### The number of player cards for in per round and per overall
Player Overall | 1st Round | 2nd Round | 3rd Round | Total
--- | --- | --- | --- | ---
1 | 4 | 6 | 11 | 21
2 | 5 | 8 | 8 | 18
3 | 8 | 4 | 5 | 14
4 | 1 | 0 | 0 | 1
Total | 18 | 18 | 18 | 54 | 

#### The percentages of player cards per round and per overall
Player Overall | 1st Round | 2nd Round | 3rd Round
--- | --- | --- | ---
1 | 22.2% | 33.3% | 61.1%
2 | 27.8% | 44.4% | 27.8% 
3 | 44.4% | 22.2% | 11.1%
4 | 5.56% | 0.00% | 0.00%

### Manager Cards

<img src="https://github.com/Tanner3644/the-hockey-game/blob/main/screenshots/0%20-%20Manager%20Card.png" width="400">  <img src="https://github.com/Tanner3644/the-hockey-game/blob/main/screenshots/7%20-%20Manager%20Card.png" width="400">

* 16 total manager cards
* Can only effect the one who draws the card

### Trade Cards

<img src="https://github.com/Tanner3644/the-hockey-game/blob/main/screenshots/0%20-%20Trade%20Card.png" width="400">  <img src="https://github.com/Tanner3644/the-hockey-game/blob/main/screenshots/4%20-%20Trade%20Card.png" width="400">

* 16 total trade cards
* Can effect the one who draws the card or others

### Draft Pick Cards

<img src="https://github.com/Tanner3644/the-hockey-game/blob/main/screenshots/1st%20Round.png" width="100">  <img src="https://github.com/Tanner3644/the-hockey-game/blob/main/screenshots/2nd%20Round.png" width="100">  <img src="https://github.com/Tanner3644/the-hockey-game/blob/main/screenshots/3rd%20Round.png" width="100">

* Given out after drafting
* Which round of picks you get and how many of them depends on your team overall (This can be seen from the score matrix on the game board)

### Play Money

### Rule Book
