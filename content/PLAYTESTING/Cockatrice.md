![[cockatrice_logo.png]]

Cockatrice is a computer program used for playing tabletop card games, specifically [[MtG|Magic: the Gathering]]. Its homepage can be found at https://cockatrice.github.io/

The program is customizable enough that we can import representations of the Mondo Megabits cards and interact with them via sorting, deckbuilding, and gameplay. 

### Upsides to Using Cockatrice

While not a perfect fit given our use case, it is currently the ideal solution for playtesting my Mondo Megabits ruleset for these reasons:

 > [!success] Available on Windows, MacOS, and Linux distros
 
> [!success] Free to download, free to play online
 
> [!success] The cardlist I maintain of Mondo Megabits cards is free too. Players have all the cards they need to make any possible deck

> [!success]  I can implement changes quickly and improve card text and rules with ease

### Downsides to using Cockatrice:

> [!warning] It was designed very clearly for Magic cards, and most of the User Interface has references to that game. Playtesters will need to look past these Magic terms or translate them over to Mondo Megabits terms in their head to get the most out of functionality.

> [!warning] The Cockatrice client has a text chat feature, but proper communication during games will need to be done over Discord voice chat.

> [!danger] It is very, very, VERY barebones in visuals. If you played [[Tabletop Simulator]] and thought those graphics were too dull, you will struggle to finish a game here. It is literally flat images of cards on a background that we can move around and point at. It's basically the computer version of sitting down at a table to play cards with someone. No more bells and whistles. Good for playtesting, but not if you need something flashy in front of you.

## Cockatrice Screenshot

![[cockatrice-screen.png]]

In this screenshot you can see several elements of the Cockatrice client:

- The obviously very basic visuals
- The ability to import custom card images (Mondo card back coming later)
- The ability to tap cards, apply counters, point arrows, and play cards face down
- Various counters on the left that can be used if needed
- [[Game Zones]] as follows: Green = [[Look Hand]], Purple below line = Think Tank (with 4 face-down cards in the [[Stowed Hand]]), Purple above line = [[Active Zone]], Red = [[Location]] (plus maybe other uses)
- The counter right next to 'Player 1' is normally used for life points in Magic games, but is a perfect match for [[Funding]] since it starts at 20 by default
