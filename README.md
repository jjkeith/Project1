# Bright Lights, Big Kitty
#### [See the game here](http://jjkeith.github.io/Bright-Lights-Big-Kitty/)

**"Bright Lights, Big Kitty" is a cat-themed real estate card game. The goal of "Bright Lights, Big Kitty" is to collect establishment cards, which will earn the player rent money. Once enough cat coins(ξ) are collected in rent, players can invest in destinations that will increase their establishments' rent and get them closer to winning the title of Mayor Kitty.**

### Inspiration
The idea for "Bright Lights, Big Kitty" came from my then six-year-old daughter after playing "Machi Koro," a much more complicated Japanese card game that, sadly, has little to nothing to do with cats. She and I came up with a game that is simpler and is quicker to play... and also has 500% more cats. The original version of this game was made with paper cards, but her first-grade friends found keeping score too difficult, so I sought to make a Javascript-based version.

### Instructions

#### Cat Establishments
* Players may obtain up to two of each.
* Players can only buy the card that corresponds with their role.
* When a player obtains a property, the card changes to the player's color and the player begins making rent whenever the card's number is rolled.

1. The Veterinary Offices of Katz & Nuzzle - Costs 1ξ and earns 1ξ when a 1 is rolled.
2. Tuna 'R' Us — Costs 2ξ and earns 2ξ when a 2 is rolled
3. Purrfect Coif Groomer — Costs 3ξ and earns 3ξ when a 3 is rolled
4. Clawsitive Reinforcement Training Academy — Costs 4ξ and earns 4ξ when a 4 is rolled
5. Pawsplay Costume Rentals — Costs 5ξ and earns 5ξ when a 5 is rolled
6. Flea Strasburg Acting School — Costs 6ξ and earns 6ξ when a 6 is rolled

#### Cat Destinations
* Players may only have one of each.
* Cards must be bought in order.
* When a player obtains a destination, the card changes to the player's color, and the player is able to earn 1ξ per establishment owned of the corresponding number.

1. Catnip Dispensary - Costs 10ξ, earns 1ξ extra on The Veterinary Offices of Katz & Nuzzle
2. Tuna Cannery - Costs 15ξ, earns 1ξ extra on the Tuna 'R' Us
3. Catapult Magazine Headquarters - Costs 20ξ, earns 1ξ extra on Purrfect Coif Groomer
4. Paw-trait Studio - Costs 25ξ, earns 1ξ extra on Clawsitive Reinforcement Training Academy
5. CatCon Venue- Costs 30ξ, earns 1ξ extra on Pawsplay Costume Rentals
6. WCAT Television Station - Costs 35ξ

#### On Each Roll
1. Both players collect rent on any cards held.
2. The active player may choose to buy one property per turn.
3. Whoever buys the WCAT Television Studio first, wins!

### Screenshots
![](screenshot1.png)
The game at start.
![](screenshot2.png)
A modal from later in the game.

### Development
My original plan for laying out the screen was to put player info at the bottom of the page as below. However, I switched it around because I felt that having that information at the top was more intuitive.

![](Wireframe.png)

### Technology
"Bright Lights, Big Kitty" was created with HTML, CSS, Javascript, jQuery, and Bootstrap. The game board remains static, with colors changing when properties are purchased. Modals guide the player through starting the game and making decisions about purchasing properties.

### Known Issues
* Players can roll over and over again by escaping out of the modal.
* Some JS functions are not scalable. Some checker functions should be written recursively.
* The use of first() and last() limits the game to having only two establishment cards per roll.

### Credits
* Rules and theme: Beatrix Keith
* Inspiration: Machi Koro © IDW Games, 2015
* Color scheme: [Coolors] (https://coolors.co/app/4c9de0-e05353-e0bb28-3ab272-7768ad).

### Future Plans
* Starter cards that are dealt at random and change the occasions or properties upon which rent can be collected
* An option to play against the computer
* Key commands for the modals
* Four cards available for each establishment and raise the prices on the destinations
