# 3 Suits 5-Player Conventions

This is document of the conventions for 3 Suits 5-Player games using [advanced hat-guessing conventions](https://github.com/iamwhoiamhahaha/hanabi/blob/master/hat-guessing/Advanced_Hat_Guessing.md) invented by [IAMJEFF](https://github.com/iamwhoiamhahaha) in 2020.

<br />

## Table of Contents
1. [General Conventions](#general-conventions)
2. [Find Tables](#find-tables)
3. [Clue Interpretation Tables](#clue-interpretation-tables)

<br />

## General Conventions

### Clue Planning

* Give _**Action Clues**_ until getting **7** or more cards to play, including the cards which are loaded by the action clue.
  * Tips: While giving an action clue, you should always touch cards with higher rank (e.g. 4 or 5), since you would probably need those cards in last round.
* Then, every clue should be given as an _**Information Clue**_ _(see below)_.
* Notes: For the variants where the clue gives both positive number or positive color information, like No Variant, the team can choose to give normal _Play Clues_ (with [Hyphen-ated Conventions](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md)) instead of information clues. They have to decide this at the start of the game.

### Information Point
* Each card has an _Information Point_, with the priority as follows:
  1) Rank: 1 < 2 < 3 < 4 < 5
  2) Color: red (left-most color) < green < blue (right-most color)
* For example:
  * Green 3 < Green 4 < Green 5
  * Red 4 < Green 4 < Blue 4
  * Blue 3 < Green 4 < Red 5

### Information Clue Rules

* If a card has been assigned with an information clue, treat it as a known useful card.
* **Do not** count the known useful cards while giving an information clue.
* **Do not** count the card which has been assigned with an action clue.
* If the players have no useful cards (or all of their useful cards are known), assign them with `0`.
* If the players have only one known useful card (from previous information clues) and they play another playable card (from previous action clues):
  * If they draw a trash, assign them with `0`.
  * If they draw a useful card with higher rank, assign them with `1`.
  * If they draw the other copy of the known useful card, **reassign** their known useful card, i.e. with `2`, `3`, or `4`. (It gives more information to their known useful card.)
  * If they draw a useful card with lower rank, assign them with `5`.
* If the players who have two or more **unknown** useful cards and one of them is unique (e.g. a 5), and if everyone knows they can only play one card for the rest of the game, only count that unique card while giving an information clue.
* If a players have three or more **unknown** useful cards, only count the cards with highest and lowest points while giving a clue.

<br />

## Find Tables

### Standard
| Touched by         | No color clues                                                                          | Own color clue                                                            | All color clues                                                                                               |
| ------------------ | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| No rank clues      | [Null](#null--white--brown--white--null--brown--null) (Dark Null)                       | [Brown](#white--brown--up-or-down) (Dark Brown)                           | [Muddy Rainbow](#muddy-rainbow--rainbow--brown--rainbow--muddy-rainbow--brown--muddy-rainbow) (Cocoa Rainbow) |
| Own rank clue      | [White](#white--brown--up-or-down) (Gray)                                               | [No Variant](#no-variant--cow--pig) (Black)                               | [Rainbow](#rainbow--pink--ambiguous--very-ambiguous--dual-color) (Dark Rainbow)                               |
| All rank clues     | [Light Pink](#light-pink--pink--white--pink--light-pink--white--light-pink) (Gray Pink) | [Pink](#rainbow--pink--ambiguous--very-ambiguous--dual-color) (Dark Pink) | [Omni](#omni--rainbow--pink--rainbow--omni--pink--omni) (Dark Omni)                                           |


### Special
* [Ambiguous](#rainbow--pink--ambiguous--very-ambiguous--dual-color) / [Very Ambiguous](#rainbow--pink--ambiguous--very-ambiguous--dual-color) / [Extremely Ambiguous](#extremely-ambiguous) / [Dual-Color](#rainbow--pink--ambiguous--very-ambiguous--dual-color)
* [Color Blind](#color-blind) / [Number Blind](#number-blind) / [Totally Blind](#totally-blind) / [Color Mute](#color-mute--number-mute--alternating-clues--duck) / [Number Mute](#color-mute--number-mute--alternating-clues--duck)
* [Alternating Clues](#color-mute--number-mute--alternating-clues--duck)
* Clue Starved _(Currently Unavailable)_
* [Up or Down](#white--brown--up-or-down)
* [Cow & Pig](#no-variant--cow--pig) / [Duck](#color-mute--number-mute--alternating-clues--duck)
* Throw It in a Hole _(Currently Unavailable)_

<br />

## Clue Interpretation Tables

### General Tables 

| # mod 9 | action                                  | information                                             | person clued   | type of clue
| ------- | --------------------------------------- | ------------------------------------------------------- | -------------- | -------------
| 0 (9)   | give clue                               | no useful card                                          | 1 player away  | number clue
| 1 (10)  | play a card (from slot 1)               | a useful card (on slot 1)                               | 1 player away  | color clue
| 2 (11)  | play a card (from slot 2)               | a useful card (on slot 2)                               | 2 players away | number clue
| 3 (12)  | play a card (from slot 3)               | a useful card (on slot 3)                               | 2 players away | color clue
| 4 (13)  | play a card (from slot 4)               | a useful card (on slot 4)                               | 3 players away | number clue
| 5 (14)  | play a one-away card<br />(from slot 4) | two or more useful cards <br />(lowest-point on slot 1) | 3 players away | color clue
| 6 (15)  | play a one-away card<br />(from slot 3) | two or more useful cards <br />(lowest-point on slot 2) | 4 players away | number clue
| 7 (16)  | play a one-away card<br />(from slot 2) | two or more useful cards <br />(lowest-point on slot 3) | 4 players away | color clue
| 8 (17)  | play a one-away card<br />(from slot 1) | two or more useful cards <br />(lowest-point on slot 4) | any player     | any clue touching only newest card<br />any clue touching only oldest card

<br />

### No Variant / Cow & Pig

* If a player has three or more useful cards, only count the cards with highest and lowest points while giving a clue.

| # mod 16 | action                                  | information                                                                        | person clued   | type of clue
| -------- | --------------------------------------- | ---------------------------------------------------------------------------------- | -------------- | -------------
| 0 (16)   | give clue                               | no useful card                                                                     | 1 player away  | number on newest card
| 1 (17)   | play a card (from slot 1)               | a useful card (on slot 1)                                                          | 1 player away  | color on newest card
| 2 (18)   | play a card (from slot 2)               | a useful card (on slot 2)                                                          | 1 player away  | number not on newest card
| 3 (19)   | play a card (from slot 3)               | a useful card (on slot 3)                                                          | 1 player away  | color not on newest card
| 4 (20)   | play a card (from slot 4)               | a useful card (on slot 4)                                                          | 2 players away | number on newest card
| 5 (21)   | (N/A)                                   | two useful cards<br />(lowest-point on slot 1)<br /> (highest-point on slot 2)     | 2 players away | color on newest card
| 6 (22)   | (N/A)                                   | two useful cards<br />(lowest-point on slot 1)<br /> (highest-point on slot 3)     | 2 players away | number not on newest card
| 7 (23)   | (N/A)                                   | two useful cards<br />(lowest-point on slot 1)<br /> (highest-point on slot 4)     | 2 players away | color not on newest card
| 8 (24)   | (N/A)                                   | two useful cards<br />(lowest-point on slot 2)<br /> (highest-point on slot 3)     | 3 players away | number on newest card
| 9 (25)   | play a one-away card<br />(from slot 1) | two useful cards<br />(lowest-point on slot 2)<br /> (highest-point on slot 4)     | 3 players away | color on newest card
| 10 (26)  | play a one-away card<br />(from slot 2) | two useful cards<br />(lowest-point on slot 2)<br /> (highest-point on slot 1)     | 3 players away | number not on newest card
| 11 (27)  | play a one-away card<br />(from slot 3) | two useful cards<br />(lowest-point on slot 3)<br /> (highest-point on slot 4)     | 3 players away | color not on newest card
| 12 (28)  | play a one-away card<br />(from slot 4) | two useful cards<br />(lowest-point on slot 3)<br /> (highest-point on slot 1)     | 4 players away | number on newest card
| 13 (29)  | (N/A)                                   | two useful cards<br />(lowest-point on slot 3)<br /> (highest-point on slot 2)     | 4 players away | color on newest card
| 14 (30)  | (N/A)                                   | two useful cards<br />(lowest-point on slot 4)<br /> (highest-point on slot 1)     | 4 players away | number not on newest card
| 15 (31)  | (N/A)                                   | two useful cards<br />(lowest-point on slot 4)<br /> (highest-point not on slot 1) | 4 players away | color not on newest card

<br />

### Rainbow / Pink / Ambiguous / Very Ambiguous / Dual-Color

| # mod 12 | action                                  | information                                               | person clued   | type of clue
| -------- | --------------------------------------- | --------------------------------------------------------- | -------------- | -------------
| 0 (12)   | give clue                               | no useful card                                            | 1 player away  | number on newest card
| 1 (13)   | play a card (from slot 1)               | a useful card (on slot 1)                                 | 1 player away  | color on newest card
| 2 (14)   | play a card (from slot 2)               | a useful card (on slot 2)                                 | 1 player away  | any clue not on newest card
| 3 (15)   | play a card (from slot 3)               | a useful card (on slot 3)                                 | 2 players away | number on newest card
| 4 (16)   | play a card (from slot 4)               | a useful card (on slot 4)                                 | 2 players away | color on newest card
| 5 (17)   | play a one-away card<br />(from slot 1) | two useful cards <br />(lowest-point on slot 1)           | 2 players away | any clue not on newest card
| 6 (18)   | play a one-away card<br />(from slot 2) | two useful cards <br />(lowest-point on slot 2)           | 3 players away | number on newest card
| 7 (19)   | play a one-away card<br />(from slot 3) | two useful cards <br />(lowest-point on slot 3)           | 3 players away | color on newest card
| 8 (20)   | play a one-away card<br />(from slot 4) | *two or more useful cards <br />(lowest-point on slot 4)  | 3 players away | any clue not on newest card
| 9 (21)   | (N/A)                                   | three or more useful cards <br />(lowest-point on slot 3) | 4 players away | number on newest card
| 10 (22)  | (N/A)                                   | three or more useful cards <br />(lowest-point on slot 2) | 4 players away | color on newest card
| 11 (23)  | (N/A)                                   | three or more useful cards <br />(lowest-point on slot 1) | 4 players away | any clue not on newest card

<br />

### White / Brown / Up or Down

| # mod 12 | action                                  | information                                               | person clued   | type of clue
| -------- | --------------------------------------- | --------------------------------------------------------- | -------------- | -------------
| 0 (12)   | give clue                               | no useful card                                            | 1 player away  | any clue on newest card
| 1 (13)   | play a card (from slot 1)               | a useful card (on slot 1)                                 | 1 player away  | number clue not on newest card
| 2 (14)   | play a card (from slot 2)               | a useful card (on slot 2)                                 | 1 player away  | color clue not on newest card
| 3 (15)   | play a card (from slot 3)               | a useful card (on slot 3)                                 | 2 players away | any clue on newest card
| 4 (16)   | play a card (from slot 4)               | a useful card (on slot 4)                                 | 2 players away | number clue not on newest card
| 5 (17)   | play a one-away card<br />(from slot 1) | two useful cards <br />(lowest-point on slot 1)           | 2 players away | color clue not on newest card
| 6 (18)   | play a one-away card<br />(from slot 2) | two useful cards <br />(lowest-point on slot 2)           | 3 players away | any clue on newest card
| 7 (19)   | play a one-away card<br />(from slot 3) | two useful cards <br />(lowest-point on slot 3)           | 3 players away | number clue not on newest card
| 8 (20)   | play a one-away card<br />(from slot 4) | *two or more useful cards <br />(lowest-point on slot 4)  | 3 players away | color clue not on newest card
| 9 (21)   | (N/A)                                   | three or more useful cards <br />(lowest-point on slot 3) | 4 players away | any clue on newest card
| 10 (22)  | (N/A)                                   | three or more useful cards <br />(lowest-point on slot 2) | 4 players away | number clue not on newest card
| 11 (23)  | (N/A)                                   | three or more useful cards <br />(lowest-point on slot 1) | 4 players away | color clue not on newest card

<br />

### Omni / Rainbow & Pink / Rainbow & Omni / Pink & Omni

| # mod 9 | action                                  | information                                             | person clued   | type of clue
| ------- | --------------------------------------- | ------------------------------------------------------- | -------------- | -------------
| 0 (9)   | give clue                               | no useful card                                          | 1 player away  | number clue on newest card
| 1 (10)  | play a card (from slot 1)               | a useful card (on slot 1)                               | 1 player away  | color clue on newest card
| 2 (11)  | play a card (from slot 2)               | a useful card (on slot 2)                               | 2 players away | number clue on newest card
| 3 (12)  | play a card (from slot 3)               | a useful card (on slot 3)                               | 2 players away | color clue on newest card
| 4 (13)  | play a card (from slot 4)               | a useful card (on slot 4)                               | 3 players away | number clue on newest card
| 5 (14)  | play a one-away card<br />(from slot 1) | two or more useful cards <br />(lowest-point on slot 1) | 3 players away | color clue on newest card
| 6 (15)  | play a one-away card<br />(from slot 2) | two or more useful cards <br />(lowest-point on slot 2) | 4 players away | number clue on newest card
| 7 (16)  | play a one-away card<br />(from slot 3) | two or more useful cards <br />(lowest-point on slot 3) | 4 players away | color clue on newest card
| 8 (17)  | play a one-away card<br />(from slot 4) | two or more useful cards <br />(lowest-point on slot 4) | any player     | any clue not on newest card

<br />

### Null / White & Brown / White & Null / Brown & Null

| # mod 9 | action                                  | information                                             | person clued   | type of clue
| ------- | --------------------------------------- | ------------------------------------------------------- | -------------- | -------------
| 0 (9)   | give clue                               | no useful card                                          | 1 player away  | number clue not on newest card
| 1 (10)  | play a card (from slot 1)               | a useful card (on slot 1)                               | 1 player away  | color clue not on newest card
| 2 (11)  | play a card (from slot 2)               | a useful card (on slot 2)                               | 2 players away | number clue not on newest card
| 3 (12)  | play a card (from slot 3)               | a useful card (on slot 3)                               | 2 players away | color clue not on newest card
| 4 (13)  | play a card (from slot 4)               | a useful card (on slot 4)                               | 3 players away | number clue not on newest card
| 5 (14)  | play a one-away card<br />(from slot 1) | two or more useful cards <br />(lowest-point on slot 1) | 3 players away | color clue not on newest card
| 6 (15)  | play a one-away card<br />(from slot 2) | two or more useful cards <br />(lowest-point on slot 2) | 4 players away | number clue not on newest card
| 7 (16)  | play a one-away card<br />(from slot 3) | two or more useful cards <br />(lowest-point on slot 3) | 4 players away | color clue not on newest card
| 8 (17)  | play a one-away card<br />(from slot 4) | two or more useful cards <br />(lowest-point on slot 4) | any player     | any clue on newest card

<br />

### Muddy Rainbow / Rainbow & Brown / Rainbow & Muddy Rainbow / Brown & Muddy Rainbow

| # mod 9 | action                                  | information                                             | person clued   | type of clue
| ------- | --------------------------------------- | ------------------------------------------------------- | -------------- | -------------
| 0 (9)   | give clue                               | no useful card                                          | 1 player away  | number clue not on newest card
| 1 (10)  | play a card (from slot 1)               | a useful card (on slot 1)                               | 1 player away  | color clue on newest card
| 2 (11)  | play a card (from slot 2)               | a useful card (on slot 2)                               | 2 players away | number clue not on newest card
| 3 (12)  | play a card (from slot 3)               | a useful card (on slot 3)                               | 2 players away | color clue on newest card
| 4 (13)  | play a card (from slot 4)               | a useful card (on slot 4)                               | 3 players away | number clue not on newest card
| 5 (14)  | play a one-away card<br />(from slot 1) | two or more useful cards <br />(lowest-point on slot 1) | 3 players away | color clue on newest card
| 6 (15)  | play a one-away card<br />(from slot 2) | two or more useful cards <br />(lowest-point on slot 2) | 4 players away | number clue not on newest card
| 7 (16)  | play a one-away card<br />(from slot 3) | two or more useful cards <br />(lowest-point on slot 3) | 4 players away | color clue on newest card
| 8 (17)  | play a one-away card<br />(from slot 4) | two or more useful cards <br />(lowest-point on slot 4) | any player     | number clue on newest card<br />color clue not on newest card

<br />

### Light Pink / Pink & White / Pink & Light Pink / White & Light Pink

| # mod 9 | action                                  | information                                             | person clued   | type of clue
| ------- | --------------------------------------- | ------------------------------------------------------- | -------------- | -------------
| 0 (9)   | give clue                               | no useful card                                          | 1 player away  | number clue on newest card
| 1 (10)  | play a card (from slot 1)               | a useful card (on slot 1)                               | 1 player away  | color clue not on newest card
| 2 (11)  | play a card (from slot 2)               | a useful card (on slot 2)                               | 2 players away | number clue on newest card
| 3 (12)  | play a card (from slot 3)               | a useful card (on slot 3)                               | 2 players away | color clue not on newest card
| 4 (13)  | play a card (from slot 4)               | a useful card (on slot 4)                               | 3 players away | number clue on newest card
| 5 (14)  | play a one-away card<br />(from slot 1) | two or more useful cards <br />(lowest-point on slot 1) | 3 players away | color clue not on newest card
| 6 (15)  | play a one-away card<br />(from slot 2) | two or more useful cards <br />(lowest-point on slot 2) | 4 players away | number clue on newest card
| 7 (16)  | play a one-away card<br />(from slot 3) | two or more useful cards <br />(lowest-point on slot 3) | 4 players away | color clue not on newest card
| 8 (17)  | play a one-away card<br />(from slot 4) | two or more useful cards <br />(lowest-point on slot 4) | any player     | number clue not on newest card<br />color clue on newest card

<br />

### Extremely Ambiguous

| # mod 12 | action                                  | information                                              | person clued   | type of clue
| -------- | --------------------------------------- | -------------------------------------------------------- | -------------- | -------------
| 0 (12)   | give clue                               | no useful card                                           | 1 player away  | number clue on newest card
| 1 (13)   | play a card (from slot 1)               | a useful card (on slot 1)                                | 1 player away  | number clue not on newest card
| 2 (14)   | play a card (from slot 2)               | a useful card (on slot 2)                                | 1 player away  | color clue
| 3 (15)   | play a card (from slot 3)               | a useful card (on slot 3)                                | 2 players away | number clue on newest card
| 4 (16)   | play a card (from slot 4)               | a useful card (on slot 4)                                | 2 players away | number clue not on newest card
| 5 (17)   | play a one-away card<br />(from slot 1) | two useful cards<br />(lowest-point on slot 1)           | 2 players away | color clue
| 6 (18)   | play a one-away card<br />(from slot 2) | two useful cards<br />(lowest-point on slot 2)           | 3 players away | number clue on newest card
| 7 (19)   | play a one-away card<br />(from slot 3) | two useful cards<br />(lowest-point on slot 3)           | 3 players away | number clue not on newest card
| 8 (20)   | play a one-away card<br />(from slot 4) | *two or more useful cards<br />(lowest-point on slot 4)  | 3 players away | color clue
| 9 (21)   | (N/A)                                   | three or more useful cards<br />(lowest-point on slot 3) | 4 players away | number clue on newest card
| 10 (22)  | (N/A)                                   | three or more useful cards<br />(lowest-point on slot 2) | 4 players away | number clue not on newest card
| 11 (23)  | (N/A)                                   | three or more useful cards<br />(lowest-point on slot 1) | 4 players away | color clue

<br />

### Color Blind

* `play a 2nd-priorty card` means that player plays a playable card which has 2nd priorty.
* If a player has three or more useful cards, only count the cards with highest and lowest points while giving a clue.
* Information `5: a red card`, `6: a green card`, and `7: a blue card` is given to a known useful card (with lowest information point).

| # mod 20 | action                                     | information                                                                    | person clued   | type of clue
| -------- | ------------------------------------------ | ------------------------------------------------------------------------------ | -------------- | -------------
| 0 (20)   | give clue                                  | no useful card                                                                 | 1 player away  | number clue on newest card
| 1 (21)   | play a card (from slot 1)                  | a useful card (on slot 1)                                                      | 1 player away  | number clue not on newest card
| 2 (22)   | play a card (from slot 2)                  | a useful card (on slot 2)                                                      | 1 player away  | red clue
| 3 (23)   | play a card (from slot 3)                  | a useful card (on slot 3)                                                      | 1 player away  | grenn clue
| 4 (24)   | play a card (from slot 4)                  | a useful card (on slot 4)                                                      | 1 player away  | blue clue
| 5 (25)   | (N/A)                                      | a red card                                                                     | 2 players away | number clue on newest card
| 6 (26)   | (N/A)                                      | a green card                                                                   | 2 players away | number clue not on newest card
| 7 (27)   | (N/A)                                      | a blue card                                                                    | 2 players away | red clue
| 8 (28)   | (N/A)                                      | two useful cards<br />(lowest-point on slot 1)<br /> (highest-point on slot 2) | 2 players away | green clue
| 9 (29)   | play a one-away card<br />(from slot 1)    | two useful cards<br />(lowest-point on slot 1)<br /> (highest-point on slot 3) | 2 players away | blue clue
| 10 (30)  | play a one-away card<br />(from slot 2)    | two useful cards<br />(lowest-point on slot 1)<br /> (highest-point on slot 4) | 3 players away | number clue on newest card
| 11 (31)  | play a one-away card<br />(from slot 3)    | two useful cards<br />(lowest-point on slot 2)<br /> (highest-point on slot 3) | 3 players away | number clue not on newest card
| 12 (32)  | play a one-away card<br />(from slot 4)    | two useful cards<br />(lowest-point on slot 2)<br /> (highest-point on slot 4) | 3 players away | red clue
| 13 (33)  | (N/A)                                      | two useful cards<br />(lowest-point on slot 2)<br /> (highest-point on slot 1) | 3 players away | green clue
| 14 (34)  | (N/A)                                      | two useful cards<br />(lowest-point on slot 3)<br /> (highest-point on slot 4) | 3 players away | blue clue
| 15 (35)  | (N/A)                                      | two useful cards<br />(lowest-point on slot 3)<br /> (highest-point on slot 1) | 4 players away | number clue on newest card
| 16 (36)  | play a 2nd-priorty card<br />(from slot 4) | two useful cards<br />(lowest-point on slot 3)<br /> (highest-point on slot 2) | 4 players away | number clue not on newest card
| 17 (37)  | play a 2nd-priorty card<br />(from slot 3) | two useful cards<br />(lowest-point on slot 4)<br /> (highest-point on slot 1) | 4 players away | red clue
| 18 (38)  | play a 2nd-priorty card<br />(from slot 2) | two useful cards<br />(lowest-point on slot 4)<br /> (highest-point on slot 2) | 4 players away | green clue
| 19 (39)  | play a 2nd-priorty card<br />(from slot 1) | two useful cards<br />(lowest-point on slot 4)<br /> (highest-point on slot 3) | 4 players away | blue clue

<br />

### Number Blind

* `play a card (2nd-priorty)` means that player plays a playable card which has 2nd priorty.
* `play a one-away card (2nd-priorty)` means that player plays a one-away card which has 2nd priorty.
* If a player has three or more useful cards, only count the cards with highest and lowest points while giving a clue.

| # mod 28 | action                                              | information                                                             | person clued   | type of clue
| -------- | --------------------------------------------------- | ----------------------------------------------------------------------- | -------------- | -------------
| 0 (28)   | give clue                                           | no useful card                                                          | 1 player away  | color clue on newest card
| 1 (29)   | play a card (from slot 1)                           | a useful card (red on slot 1)                                           | 1 player away  | color clue not on newest card
| 2 (30)   | play a card (from slot 2)                           | a useful card (red on slot 2)                                           | 1 player away  | 1 clue
| 3 (31)   | play a card (from slot 3)                           | a useful card (red on slot 3)                                           | 1 player away  | 2 clue
| 4 (32)   | play a card (from slot 4)                           | a useful card (red on slot 4)                                           | 1 player away  | 3 clue
| 5 (33)   | (N/A)                                               | a useful card (green on slot 1)                                         | 1 player away  | 4 clue
| 6 (34)   | (N/A)                                               | a useful card (green on slot 2)                                         | 1 player away  | 5 clue
| 7 (35)   | (N/A)                                               | a useful card (green on slot 3)                                         | 2 players away | color clue on newest card
| 8 (36)   | (N/A)                                               | a useful card (green on slot 4)                                         | 2 players away | color clue not on newest card
| 9 (37)   | play a one-away card<br />(from slot 1)             | a useful card (blue on slot 1)                                          | 2 players away | 1 clue
| 10 (38)  | play a one-away card<br />(from slot 2)             | a useful card (blue on slot 2)                                          | 2 players away | 2 clue
| 11 (39)  | play a one-away card<br />(from slot 3)             | a useful card (blue on slot 3)                                          | 2 players away | 3 clue
| 12 (40)  | play a one-away card<br />(from slot 4)             | a useful card (blue on slot 4)                                          | 2 players away | 4 clue
| 13 (41)  | (N/A)                                               | two useful cards<br />(red on slot 1)<br />(the other on slot 2)        | 2 players away | 5 clue
| 14 (42)  | (N/A)                                               | two useful cards<br />(red on slot 1)<br />(the other on slot 3 or 4)   | 3 players away | color clue on newest card
| 15 (43)  | (N/A)                                               | two useful cards<br />(red on slot 2)                                   | 3 players away | color clue not on newest card
| 16 (44)  | (N/A)                                               | two useful cards<br />(red on slot 3)                                   | 3 players away | 1 clue
| 17 (45)  | play a one-away card<br />(2nd-priorty from slot 4) | two useful cards<br />(red on slot 4)                                   | 3 players away | 2 clue
| 18 (46)  | play a one-away card<br />(2nd-priorty from slot 3) | two useful cards<br />(green on slot 1)<br />(the other on slot 2)      | 3 players away | 3 clue
| 19 (47)  | play a one-away card<br />(2nd-priorty from slot 2) | two useful cards<br />(green on slot 1)<br />(the other on slot 3 or 4) | 3 players away | 4 clue
| 20 (48)  | play a one-away card<br />(2nd-priorty from slot 1) | two useful cards<br />(green on slot 2)                                 | 3 players away | 5 clue
| 21 (49)  | (N/A)                                               | two useful cards<br />(green on slot 3)                                 | 4 players away | color clue on newest card
| 22 (50)  | (N/A)                                               | two useful cards<br />(green on slot 4)                                 | 4 players away | color clue not on newest card
| 23 (51)  | (N/A)                                               | two useful cards<br />(blue on slot 1)<br />(the other on slot 2)       | 4 players away | 1 clue
| 24 (52)  | play a card<br />(2nd-priorty from slot 4)          | two useful cards<br />(blue on slot 1)<br />(the other on slot 3 or 4)  | 4 players away | 2 clue
| 25 (53)  | play a card<br />(2nd-priorty from slot 3)          | two useful cards<br />(blue on slot 2)                                  | 4 players away | 3 clue
| 26 (54)  | play a card<br />(2nd-priorty from slot 2)          | two useful cards<br />(blue on slot 3)                                  | 4 players away | 4 clue
| 27 (55)  | play a card<br />(2nd-priorty from slot 1)          | two useful cards<br />(blue on slot 4)                                  | 4 players away | 5 clue

<br />

### Totally Blind

* `play a card (2nd-priorty)` means that player plays a playable card which has 2nd priorty.
* `play a one-away card (2nd-priorty)` means that player plays a one-away card which has 2nd priorty.
* If a player has three or more useful cards, only count the cards with highest and lowest points while giving a clue.

| # mod 32 | action                                              | information                                                        | person clued   | type of clue
| -------- | --------------------------------------------------- | ------------------------------------------------------------------ | -------------- | -------------
| 0 (32)   | give clue                                           | no useful card                                                     | 1 player away  | red clue
| 1 (33)   | play a card<br />(1st-priorty from slot 1)          | a useful card (red on slot 1)                                      | 1 player away  | green clue
| 2 (34)   | play a card<br />(1st-priorty from slot 2)          | a useful card (red on slot 2)                                      | 1 player away  | blue clue
| 3 (35)   | play a card<br />(1st-priorty from slot 3)          | a useful card (red on slot 3)                                      | 1 player away  | 1 clue
| 4 (36)   | play a card<br />(1st-priorty from slot 4)          | a useful card (red on slot 4)                                      | 1 player away  | 2 clue
| 5 (37)   | (N/A)                                               | a useful card (green on slot 1)                                    | 1 player away  | 3 clue
| 6 (38)   | (N/A)                                               | a useful card (green on slot 2)                                    | 1 player away  | 4 clue
| 7 (39)   | (N/A)                                               | a useful card (green on slot 3)                                    | 1 player away  | 5 clue
| 8 (40)   | (N/A)                                               | a useful card (green on slot 4)                                    | 2 players away | red clue
| 9 (41)   | play a one-away card<br />(1st-priorty from slot 1) | a useful card (blue on slot 1)                                     | 2 players away | green clue
| 10 (42)  | play a one-away card<br />(1st-priorty from slot 2) | a useful card (blue on slot 2)                                     | 2 players away | blue clue
| 11 (43)  | play a one-away card<br />(1st-priorty from slot 3) | a useful card (blue on slot 3)                                     | 2 players away | 1 clue
| 12 (44)  | play a one-away card<br />(1st-priorty from slot 4) | a useful card (blue on slot 4)                                     | 2 players away | 2 clue
| 13 (45)  | (N/A)                                               | two useful cards<br />(red on slot 1)<br />(the other on slot 2)   | 2 players away | 3 clue
| 14 (46)  | (N/A)                                               | two useful cards<br />(red on slot 1)<br />(the other on slot 3)   | 2 players away | 4 clue
| 15 (47)  | (N/A)                                               | two useful cards<br />(red on slot 1)<br />(the other on slot 4)   | 2 players away | 5 clue
| 16 (48)  | (N/A)                                               | two useful cards<br />(red on slot 2)                              | 3 players away | red clue
| 17 (49)  | play a one-away card<br />(2nd-priorty from slot 4) | two useful cards<br />(red on slot 3)                              | 3 players away | green clue
| 18 (50)  | play a one-away card<br />(2nd-priorty from slot 3) | two useful cards<br />(red on slot 4)                              | 3 players away | blue clue
| 19 (51)  | play a one-away card<br />(2nd-priorty from slot 2) | two useful cards<br />(green on slot 1)<br />(the other on slot 2) | 3 players away | 1 clue
| 20 (52)  | play a one-away card<br />(2nd-priorty from slot 1) | two useful cards<br />(green on slot 1)<br />(the other on slot 3) | 3 players away | 2 clue
| 21 (53)  | (N/A)                                               | two useful cards<br />(green on slot 1)<br />(the other on slot 4) | 3 players away | 3 clue
| 22 (54)  | (N/A)                                               | two useful cards<br />(green on slot 2)                            | 3 players away | 4 clue
| 23 (55)  | (N/A)                                               | two useful cards<br />(green on slot 3)                            | 3 players away | 5 clue
| 24 (56)  | (N/A)                                               | two useful cards<br />(green on slot 4)                            | 4 players away | red clue
| 25 (57)  | (N/A)                                               | two useful cards<br />(blue on slot 1)<br />(the other on slot 2)  | 4 players away | green clue
| 26 (58)  | (N/A)                                               | two useful cards<br />(blue on slot 1)<br />(the other on slot 3)  | 4 players away | blue clue
| 27 (59)  | (N/A)                                               | two useful cards<br />(blue on slot 1)<br />(the other on slot 4)  | 4 players away | 1 clue
| 28 (60)  | play a card<br />(2nd-priorty from slot 4)          | two useful cards<br />(blue on slot 2)                             | 4 players away | 2 clue
| 29 (61)  | play a card<br />(2nd-priorty from slot 3)          | two useful cards<br />(blue on slot 3)                             | 4 players away | 3 clue
| 30 (62)  | play a card<br />(2nd-priorty from slot 2)          | two useful cards<br />(blue on slot 4)                             | 4 players away | 4 clue
| 31 (63)  | play a card<br />(2nd-priorty from slot 1)          | (N/A)                                                              | 4 players away | 5 clue

<br />

### Color Mute / Number Mute / Alternating Clues / Duck

| # mod 9 | action                                  | information                                             | person clued   | type of clue
| ------- | --------------------------------------- | ------------------------------------------------------- | -------------- | -------------
| 0 (9)   | give clue                               | no useful card                                          | 1 player away  | any clue on newest card
| 1 (10)  | play a card (from slot 1)               | a useful card (on slot 1)                               | 1 player away  | any clue not touching the newest card
| 2 (11)  | play a card (from slot 2)               | a useful card (on slot 2)                               | 2 players away | any clue on newest card
| 3 (12)  | play a card (from slot 3)               | a useful card (on slot 3)                               | 2 players away | any clue not touching the newest card
| 4 (13)  | play a card (from slot 4)               | a useful card (on slot 4)                               | 3 players away | any clue on newest card
| 5 (14)  | play a one-away card<br />(from slot 1) | two or more useful cards <br />(lowest-point on slot 1) | 3 players away | any clue not touching the newest card
| 6 (15)  | play a one-away card<br />(from slot 2) | two or more useful cards <br />(lowest-point on slot 2) | 4 players away | any clue on newest card
| 7 (16)  | play a one-away card<br />(from slot 3) | two or more useful cards <br />(lowest-point on slot 3) | 4 players away | any clue not touching the newest card
| 8 (17)  | play a one-away card<br />(from slot 4) | two or more useful cards <br />(lowest-point on slot 4) | any player     | any clue touching only oldest card

<br />
