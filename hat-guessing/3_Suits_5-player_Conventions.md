# 3 Suits 5-player Conventions

This is document of the conventions for 3 Suits 5-player games using [advanced hat-guessing conventions](https://github.com/iamwhoiamhahaha/hanabi/blob/master/hat-guessing/Advanced_Hat_Guessing.md) invented by [IAMJEFF](https://github.com/iamwhoiamhahaha) in 2020.

<br />

## General Conventions

* Use first 3 clues with hat-guessing clues getting as many cards as possible with these 3 clues.
  * (Exception) Or 4 clues if there are more than 3 cards left in the deck after 3 clues.
  * Tips: While giving a hat-guessing clue, you should always touch cards with high rank (e.g. 4 or 5), since you would probably need those cards in last round.
* Starting from the 4th clue (or 5th), every clue should be given as a normal play clue.
* Each player can decide to draw the last card to initiate the end game.

<br />

## Find Tables

### Standard
| Touched by         | No color clues | Own color clue | All color clues |
| ------------------ | -------------- | -------------- | --------------- |
| No rank clues      | [Null](#null--white--brown--white--null--brown--null) (Dark Null) | [Brown](#white--brown--up-or-down) (Dark Brown) | [Muddy Rainbow](#muddy-rainbow--rainbow--brown--rainbow--muddy-rainbow--brown--muddy-rainbow) (Cocoa Rainbow) |
| Own rank clue      | [White](#white--brown--up-or-down) (Gray) | [No Variant]() (Black) | [Rainbow](#rainbow--pink--ambiguous--very-ambiguous--dual-color) (Dark Rainbow) |
| All rank clues     | [Light Pink](#light-pink--pink--white--pink--light-pink--white--light-pink) (Gray Pink) | [Pink](#rainbow--pink--ambiguous--very-ambiguous--dual-color) (Dark Pink) | [Omni](#omni--rainbow--pink--rainbow--omni--pink--omni) (Dark Omni) |

### Special
* [Ambiguous](#rainbow--pink--ambiguous--very-ambiguous--dual-color) / [Very Ambiguous](#rainbow--pink--ambiguous--very-ambiguous--dual-color) / [Extremely Ambiguous]() / [Dual-Color](#rainbow--pink--ambiguous--very-ambiguous--dual-color)
* [Color Blind]() / [Number Blind]() / [Totally Blind]() / [Color Mute]() / [Number Mute]()
* [Alternating Clues]()
* Clue Starved (Currently unavailable)
* [Up or Down](#white--brown--up-or-down)
* [Cow & Pig]() / [Duck]()
* Throw It in a Hole (Currently unavailable)

<br />

## Clue Interpretation Tables

### No Variant / Cow & Pig

* Use any table below.

<br />

### Rainbow / Pink / Ambiguous / Very Ambiguous / Dual-Color

| # mod 12 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (12)   | give clue                        | 1 player away  | number on newest card
| 1 (13)   | play a card from slot 1          | 1 player away  | color on newest card
| 2 (14)   | play a card from slot 2          | 1 player away  | any clue not touching the newest card
| 3 (15)   | play a card from slot 3          | 2 players away | number on newest card
| 4 (16)   | play a card from slot 4          | 2 players away | color on newest card
| 5 (17)   | (N/A)                            | 2 players away | any clue not touching the newest cardd
| 6 (18)   | (N/A)                            | 3 players away | number on newest card
| 7 (19)   | (N/A)                            | 3 players away | color on newest card
| 8 (20)   | play a one-away card from slot 4 | 3 players away | any clue not touching the newest card
| 9 (21)   | play a one-away card from slot 3 | 4 players away | number on newest card
| 10(22)   | play a one-away card from slot 2 | 4 players away | color on newest card
| 11(23)   | play a one-away card from slot 1 | 4 players away | any clue not touching the newest card

<br />

### White / Brown / Up or Down

| # mod 12 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (12)   | give clue / discard              | 1 player away  | any clue on newest card
| 1 (13)   | play a card from slot 1          | 1 player away  | number clue not touching the newest card
| 2 (14)   | play a card from slot 2          | 1 player away  | color clue not touching the newest card
| 3 (15)   | play a card from slot 3          | 2 players away | any clue on newest card
| 4 (16)   | play a card from slot 4          | 2 players away | number clue not touching the newest card
| 5 (17)   | (N/A)                            | 2 players away | color clue not touching the newest card
| 6 (18)   | (N/A)                            | 3 players away | any clue on newest card
| 7 (19)   | (N/A)                            | 3 players away | number clue not touching the newest card
| 8 (20)   | play a one-away card from slot 4 | 3 players away | color clue not touching the newest card
| 9 (21)   | play a one-away card from slot 3 | 4 players away | any clue on newest card
| 10 (22)  | play a one-away card from slot 2 | 4 players away | number clue not touching the newest card
| 11 (23)  | play a one-away card from slot 1 | 4 players away | color clue not touching the newest card

<br />

### Omni / Rainbow & Pink / Rainbow & Omni / Pink & Omni

| # mod 9 | action                           | person clued   | type of clue
| ------- | -------------------------------- | -------------- | -------------
| 0 (9)   | give clue / discard              | 1 player away  | number clue on newest card
| 1 (10)  | play a card from slot 1          | 1 player away  | color clue on newest card
| 2 (11)  | play a card from slot 2          | 2 players away | number clue on newest card
| 3 (12)  | play a card from slot 3          | 2 players away | color clue on newest card
| 4 (13)  | play a card from slot 4          | 3 players away | number clue on newest card
| 5 (14)  | play a one-away card from slot 4 | 3 players away | color clue on newest card
| 6 (15)  | play a one-away card from slot 3 | 4 players away | number clue on newest card
| 7 (16)  | play a one-away card from slot 2 | 4 players away | color clue on newest card
| 8 (17)  | play a one-away card from slot 1 | any player     | any clue not touching the newest card

<br />

### Null / White & Brown / White & Null / Brown & Null

| # mod 9 | action                           | person clued   | type of clue
| ------- | -------------------------------- | -------------- | -------------
| 0 (9)   | give clue / discard              | 1 player away  | number clue not touching the newest card
| 1 (10)  | play a card from slot 1          | 1 player away  | color clue not touching the newest card
| 2 (11)  | play a card from slot 2          | 2 players away | number clue not touching the newest card
| 3 (12)  | play a card from slot 3          | 2 players away | color clue not touching the newest card
| 4 (13)  | play a card from slot 4          | 3 players away | number clue not touching the newest card
| 5 (14)  | play a one-away card from slot 4 | 3 players away | color clue not touching the newest card
| 6 (15)  | play a one-away card from slot 3 | 4 players away | number clue not touching the newest card
| 7 (16)  | play a one-away card from slot 2 | 4 players away | color clue not touching the newest card
| 8 (17)  | play a one-away card from slot 1 | any player     | any clue on newest card

<br />

### Muddy Rainbow / Rainbow & Brown / Rainbow & Muddy Rainbow / Brown & Muddy Rainbow

| # mod 9 | action                           | person clued   | type of clue
| ------- | -------------------------------- | -------------- | -------------
| 0 (9)   | give clue / discard              | 1 player away  | number clue not touching the newest card
| 1 (10)  | play a card from slot 1          | 1 player away  | color clue on newest card
| 2 (11)  | play a card from slot 2          | 2 players away | number clue not touching the newest card
| 3 (12)  | play a card from slot 3          | 2 players away | color clue on newest card
| 4 (13)  | play a card from slot 4          | 3 players away | number clue not touching the newest card
| 5 (14)  | play a one-away card from slot 4 | 3 players away | color clue on newest card
| 6 (15)  | play a one-away card from slot 3 | 4 players away | number clue not touching the newest card
| 7 (16)  | play a one-away card from slot 2 | 4 players away | color clue on newest card
| 8 (17)  | play a one-away card from slot 1 | any player     | number clue on newest card<br />color clue not touching the newest card

<br />

### Light Pink / Pink & White / Pink & Light Pink / White & Light Pink

| # mod 9 | action                           | person clued   | type of clue
| ------- | -------------------------------- | -------------- | -------------
| 0 (9)   | give clue / discard              | 1 player away  | number clue on newest card
| 1 (10)  | play a card from slot 1          | 1 player away  | color clue not touching the newest card
| 2 (11)  | play a card from slot 2          | 2 players away | number clue on newest card
| 3 (12)  | play a card from slot 3          | 2 players away | color clue not touching the newest card
| 4 (13)  | play a card from slot 4          | 3 players away | number clue on newest card
| 5 (14)  | play a one-away card from slot 4 | 3 players away | color clue not touching the newest card
| 6 (15)  | play a one-away card from slot 3 | 4 players away | number clue on newest card
| 7 (16)  | play a one-away card from slot 2 | 4 players away | color clue not touching the newest card
| 8 (17)  | play a one-away card from slot 1 | any player     | number clue not touching the newest card<br />color clue on newest card

<br />
