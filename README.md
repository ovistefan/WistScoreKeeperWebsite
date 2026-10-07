# Automatic Scoreboard for card game Whist.

Simply read the rules, input names and play. Saves time, paper, and cheating accusations!

## Features:

* 3 to 6 player support with dynamic round scheme depending on player count.
* Quick and easy score calculation.
* No login, install, or backend to run.
* Rules built in.
* Hosted on GitHub

## Getting Started:

[**Live Webiste**](https://ovistefan.github.io/WistScoreKeeperWebsite/)

## Rules

Romanian whist is a game for 3 to 6 players (best for 4). Each player plays alone. From a standard deck use 8 cards for every player (24 for 3 players, 32 for 4 players and so on, to 48 for 6 players).

The cards rank as follows: A, K, Q, J, 10, 9, and so on. They have no value because it is a plain trick game.

## Deal

The first dealer is chosen at random. The dealer deals the cards and the first player to go is to the left of the dealer. Then the turn to deal rotates clockwise after each hand. The number of cards dealt to each player varies during the game, starting at one, going up to eight and then back down again. The rounds of one card and eight cards are played as many times as there are players. The website will tell you how many cards to deal each round.

Example round scheme: With 4 players the whole game would consist of 24 deals, and the number of cards dealt each time would be as follows:
1, 1, 1, 1, 2, 3, 4, 5, 6, 7, 8, 8, 8, 8, 7, 6, 5, 4, 3, 2, 1, 1, 1, 1.

## Bidding

Each player in order, beginning with the player to dealer's left, bids how many tricks they think they will take. All bids are final and cannot be changed afterwards.

To ensure that not everyone will succeed in their bid, the sum of all tricks bid must not be the same as the number of cards dealt to each player. (Example: game with six cards, three players: The first player bids "3", the next "1". The last player cannot bid "2", as this would make the sum of the tricks equal to 6. in this case, the last bidder must bid 0, 1, 3, 4, 5 or 6).

This rule puts the last bidder (the dealer) at a disadvantage, especially in the one-card hands. To counter this disadvantage, a series of one-card hands equal to the number of players is played at the beginning and end of each game.

## Play

The player to dealer's left plays the first card. The other players must play a card of the same suit if possible. Any player who has no card of the suit led must play a trump if they can. A player who has no cards of the suit led and no trumps can play any card. The trick is won by whoever played the highest trump, or if no trump was played, by whoever played the highest card of the leading suit, or the first suit put down. The winner of the trick starts the next.

The objective is to win exactly the number of tricks you said you would win.

## Scoring

The hand ends when all cards are played. Scoring is as follows:

Players who made their contract (exactly) get 5 points plus 1 point for each trick made.
Players who took fewer tricks than their bid lose one point for each undertrick.
Players who took more tricks than their bid lose one point for each overtrick.

Examples: Suppose you bid 3 tricks. If you take exactly 3 you will win 8 points (5+3). If you take only two tricks you lose 1 point; the same if you take 4 tricks. If you take 1 or 5 tricks (two off from your bid) you will lose 2 points; if you take no tricks or 6 tricks you will lose 3. This is the part which the website takes care of, all players must do is submit their bets, play a round, and then submit their take.



Rules adapted from [Wikipedia](https://en.wikipedia.org/wiki/Romanian_whist).



