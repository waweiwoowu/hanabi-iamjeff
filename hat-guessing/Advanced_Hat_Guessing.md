# Advanced Hat-Guessing Conventions

This is an advanced version of [hat-guessing conventions](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/Hat_Guessing.md) invented by [IAMJEFF](https://github.com/iamwhoiamhahaha) in April 2020.

If you are looking for 3 Suits 5-Player Conventions. See [here](https://github.com/iamwhoiamhahaha/hanabi/blob/master/hat-guessing/5-Player_3_Suits_Conventions.md).

<br />

## Table of Contents
1. [Introduction](#introduction)
2. [General Conventions](#general-conventions)
3. [Other Conventions](#other-conventions)
4. [Variant-Specific Conventions](#variant-specific-conventions)
5. [Find Tables](#find-tables)
6. [Clue Interpretation Tables (4-player)](#clue-interpretation-tables-4-player)
7. [Clue Interpretation Tables (5-player)](#clue-interpretation-tables-5-player)
8. [Clue Interpretation Tables (6-player)](#clue-interpretation-tables-6-player)

<br />

## Introduction
* In regular hat-guessing conventions, players are not able to do a finesse by encoding an action on a one-way card while giving a clue. However, players are now able to do it with these advanced conventions.
* The convention is optimal for any variant with **high required efficiency** and **low starting pace**, e.g., a 3 suits 5-player game.

<br />

## General Conventions
* Most of the rules follow [the conventions](https://github.com/hanabi/hanabi.github.io/blob/main/misc/hat-guessing.md) in regular hat-guessing conventions.

### Priority Rules
* If a player has two or more playable cards (or one-away cards), the priority is as follows:
  1) Unique (e.g. black 1)
  2) Lowest rank
  3) Left-most
* Playable cards and one-away cards have same priority, no one is higher than the other. However, if the clue is ambiguous, playable cards takes priority over one-away cards.
* Players are allowed to break the priority if the action has only one interpretation to each player and no one would misplay.

### Finesse Rules
* If a one-away card is finessed, then the finessed component doesn't need to follow the _Priority Rules_.
* If two or more players have same copies of the finessed component, the finesse is on the last player who has it.
* If the player sees their next player has both playable cards and one-away cards, and if the action is ambiguous and they don't know whether the finesse is on them or on their next player, they should assume it is on next player.

### Chop Move Rules
* The players are not allowed to chop move a card while that player has a playable card.
* The players are only allowed to chop move critical cards.

### Discard Rules
* **Do not** discard the useful card which has both positive number information and positive color information. (e.g. a green 4 touched by both green clue and a 4 clue)
* **Do not** discard the globilly known critical card. (e.g. a 5 touched by a 5 clue)
* Players should always discard their right-most card, unless it was chop moved. (Since _Good Touch Principle_ doesn’t apply)
* Players should always discard their right-most card, even they have enough (locally) information on their card, unless they are 100% sure it is critical.

<br />

## Other Conventions

### Useful Choice Principle
* Always touch the cards which is useful while giving a clue. For example, high rank (e.g. 4 or 5) or unique (e.g. black 3).
* This is because the team might have another chance to give enough information on those cards, and the team doesn't need to chop move them later.

<br />

## Variant-Specific Conventions

### Up or Down

#### (Unnamed)

* In Up or Down, if a suit hasn't determined to be "going up" or "going down", the players are not allowed to assign action with "playing a 1-away card" for that suit.
* For example, in an Up or Down (5 Suits) game:
  * If `yellow 1`, `green 5`, and `blue Start` have been played on the stacks, the only one-away cards that can be assigned with actions are: `yellow 3` and `green 3`.

<br />


## Find Tables

| 4 Player                                                                              | 5 Player                                                                                    | 6 Player                                                                              |
| ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| [No Variant (4-Player)](#no-variant--clue-starved--cow--pig-4-player)                 | [No Variant (5-Player)](#no-variant--clue-starved--cow--pig-5-player)                       | [No Variant (6-Player)](#no-variant--clue-starved--cow--pig-6-player)                 |
| [Rainbow (4-Player)](#rainbow--ambiguous--very-ambiguous--dual-color-4-player)        | [Rainbow (5-Player)](#rainbow--pink--ambiguous--very-ambiguous--dual-color-5-player)        | [Rainbow (6-Player)](#rainbow--ambiguous--very-ambiguous--dual-color-6-player)        |
| [Pink (4-Player)](#pink-4-player)                                                     | [Pink (5-Player)](#rainbow--pink--ambiguous--very-ambiguous--dual-color-5-player)           | [Pink (6-Player)](#pink-6-player)                                                     |
| [White (4-Player)](#white-4-player)                                                   | [White (5-Player)](#white--brown--up-or-down-5-player)                                      | [White (6-Player)](#white-6-player)                                                   |
| [Brown (4-Player)](#brown--up-or-down-4-player)                                       | [Brown (5-Player)](#white--brown--up-or-down-5-player)                                      | [Brown (6-Player)](#brown--up-or-down-6-player)                                       |
| [Omni (4-Player)](#omni-4-player)                                                     | [Omni (5-Player)](#omni-5-player)                                                           | [Omni (6-Player)](#omni-6-player)                                                     |
| [Null (4-Player)](#null-4-player)                                                     | [Null (5-Player)](#null-5-player)                                                           | [Null (6-Player)](#null-6-player)                                                     |
| [Muddy Rainbow (4-Player)](#muddy-rainbow-4-player)                                   | [Muddy Rainbow (5-Player)](#muddy-rainbow-5-player)                                         | [Muddy Rainbow (6-Player)](#muddy-rainbow-6-player)                                   |
| [Light Pink (4-Player)](#light-pink-4-player)                                         | [Light Pink (5-Player)](#light-pink-5-player)                                               | [Light Pink (6-Player)](#light-pink-6-player)                                         |
| [Ambiguous (4-Player)](#rainbow--ambiguous--very-ambiguous--dual-color-4-player)      | [Ambiguous (5-Player)](#rainbow--pink--ambiguous--very-ambiguous--dual-color-5-player)      | [Ambiguous (6-Player)](#rainbow--ambiguous--very-ambiguous--dual-color-6-player)      |
| [Very Ambiguous (4-Player)](#rainbow--ambiguous--very-ambiguous--dual-color-4-player) | [Very Ambiguous (5-Player)](#rainbow--pink--ambiguous--very-ambiguous--dual-color-5-player) | [Very Ambiguous (6-Player)](#rainbow--ambiguous--very-ambiguous--dual-color-6-player) |
| [Extremely Ambiguous (4-Player)](#extremely-ambiguous-4-player)                       | [Extremely Ambiguous (5-Player)](#extremely-ambiguous-5-player)                             | [Extremely Ambiguous (6-Player)](#general-table-6-player)                             |
| [Dual-Color (4-Player)](#rainbow--ambiguous--very-ambiguous--dual-color-4-player)     | [Dual-Color (5-Player)](#rainbow--pink--ambiguous--very-ambiguous--dual-color-5-player)     | [Dual-Color (6-Player)](#rainbow--ambiguous--very-ambiguous--dual-color-6-player)     |
| Color Mute (4-Player)                                                                 | [Color Mute (5-Player)](#color-mute--number-mute--alternating-clues-5-player)               | Color Mute (6-Player)                                                                 |
| Number Mute (4-Player)                                                                | [Number Mute (5-Player)](#color-mute--number-mute--alternating-clues-5-player)              | Number Mute (6-Player)                                                                |
| Alternating Clues (4-Player)                                                          | [Alternating Clues (5-Player)](#color-mute--number-mute--alternating-clues-5-player)        | Alternating Clues (6-Player)                                                          |
| [Clue Starved (4-Player)](#no-variant--clue-starved--cow--pig-4-player)               | [Clue Starved (5-Player)](#no-variant--clue-starved--cow--pig-5-player)                     | [Clue Starved (6-Player)](#no-variant--clue-starved--cow--pig-6-player)               |
| [Up or Down (4-Player)](#brown--up-or-down-4-player)                                  | [Up or Down (5-Player)](#white--brown--up-or-down-5-player)                                 | [Up or Down (6-Player)](#brown--up-or-down-6-player)                                  |
| [Cow & Pig (4-Player)](#no-variant--clue-starved--cow--pig-4-player)                  | [Cow & Pig (5-Player)](#no-variant--clue-starved--cow--pig-5-player)                        | [Cow & Pig (6-Player)](#no-variant--clue-starved--cow--pig-6-player)                  |
| Duck (4-Player)                                                                       | [Duck (5-Player)](#duck-5-player)                                                           | Duck (6-Player)                                                                       |
| Throw It in a Hole (4-Player)                                                         | Throw It in a Hole (5-Player)                                                               | Throw It in a Hole (6-Player)                                                         |

### Empty Clues
* [Color Blind](https://github.com/iamwhoiamhahaha/hanabi/blob/master/hat-guessing/Empty_Clues.md#color-blind-tables)
* [Number Blind](https://github.com/iamwhoiamhahaha/hanabi/blob/master/hat-guessing/Empty_Clues.md#number-blind-tables)
* [Totally Blind](https://github.com/iamwhoiamhahaha/hanabi/blob/master/hat-guessing/Empty_Clues.md#totally-blind-tables)

### Other Variants
* [General Table (5 Player)](#general-table-5-player)
* [General Table (6 Player)](#general-table-6-player)

### Use Same Tables
* No Variant = Clue Starved = Cow & Pig
* Rainbow = Ambiguous = Very Ambiguous = Dual-Color
* Brown = Up or Down
* Omni = Rainbow & Pink = Rainbow & Omni = Pink & Omni
* Null = White & Brown = White & Null = Brown & Null
* Muddy Rainbow = Rainbow & Brown = Rainbow & Muddy Rainbow = Brown & Muddy Rainbow
* Light Pink = Pink & White = Pink & Light Pink = White & Light Pink
* Special Suit = Special-Ones = Special-Fives (e.g. Rainbow = Rainbow-Ones = Rainbow-Fives, and so on.)
* Special Suit = Dark Special Suit (e.g. Light Pink = Gray Pink)

<br />

## Clue Interpretation Tables (4-player)

### No Variant / Clue Starved / Cow & Pig (4-Player)

| # mod 12 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (12)   | give clue / discard              | 1 player away  | number on newest card
| 1 (13)   | play a card from slot 1          | 1 player away  | color on newest card
| 2 (14)   | play a card from slot 2          | 1 player away  | number clue not touching the newest card
| 3 (15)   | play a card from slot 3          | 1 player away  | color clue not touching the newest card
| 4 (16)   | play a card from slot 4          | 2 players away | number on newest card
| 5 (17)   | play a one-away card from slot 1 | 2 players away | color on newest card
| 6 (18)   | play a one-away card from slot 2 | 2 players away | number clue not touching the newest card
| 7 (19)   | play a one-away card from slot 3 | 2 players away | color clue not touching the newest card
| 8 (20)   | play a one-away card from slot 4 | 3 players away | number on newest card
| 9 (21)   | triple chop move                 | 3 players away | color on newest card
| 10 (22)  | double chop move                 | 3 players away | number clue not touching the newest card
| 11 (23)  | chop move                        | 3 players away | color clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### Rainbow / Ambiguous / Very Ambiguous / Dual-Color (4-Player)

| # mod 10 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (10)   | give clue / discard              | 1 player away  | number on newest card
| 1 (11)   | play a card from slot 1          | 1 player away  | color on newest card
| 2 (12)   | play a card from slot 2          | 1 player away  | number clue not touching the newest card
| 3 (13)   | play a card from slot 3          | 2 players away | number on newest card
| 4 (14)   | play a card from slot 4          | 2 players away | color on newest card
| 5 (15)   | play a one-away card from slot 1 | 2 players away | number clue not touching the newest card
| 6 (16)   | play a one-away card from slot 2 | 3 players away | number on newest card
| 7 (17)   | play a one-away card from slot 3 | 3 players away | color on newest card
| 8 (18)   | play a one-away card from slot 4 | 3 players away | number clue not touching the newest card
| 9 (19)   | chop move                        | any player     | color clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### Pink (4-Player)

| # mod 10 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (10)   | give clue / discard              | 1 player away  | number on newest card
| 1 (11)   | play a card from slot 1          | 1 player away  | color on newest card
| 2 (12)   | play a card from slot 2          | 1 player away  | color clue not touching the newest card
| 3 (13)   | play a card from slot 3          | 2 players away | number on newest card
| 4 (14)   | play a card from slot 4          | 2 players away | color on newest card
| 5 (15)   | play a one-away card from slot 1 | 2 players away | color clue not touching the newest card
| 6 (16)   | play a one-away card from slot 2 | 3 players away | number on newest card
| 7 (17)   | play a one-away card from slot 3 | 3 players away | color on newest card
| 8 (18)   | play a one-away card from slot 4 | 3 players away | color clue not touching the newest card
| 9 (19)   | chop move                        | any player     | number clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### White (4-Player)

| # mod 10 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (10)   | give clue / discard              | 1 player away  | number on newest card
| 1 (11)   | play a card from slot 1          | 1 player away  | number clue not touching the newest card
| 2 (12)   | play a card from slot 2          | 1 player away  | color clue not touching the newest card
| 3 (13)   | play a card from slot 3          | 2 players away | number on newest card
| 4 (14)   | play a card from slot 4          | 2 players away | number clue not touching the newest card
| 5 (15)   | play a one-away card from slot 1 | 2 players away | color clue not touching the newest card
| 6 (16)   | play a one-away card from slot 2 | 3 players away | number on newest card
| 7 (17)   | play a one-away card from slot 3 | 3 players away | number clue not touching the newest card
| 8 (18)   | play a one-away card from slot 4 | 3 players away | color clue not touching the newest card
| 9 (19)   | chop move                        | any player     | color clue on newest card

[(Find Tables)](#find-tables)

<br />

### Brown / Up or Down (4-Player)

| # mod 10 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (10)   | give clue / discard              | 1 player away  | color on newest card
| 1 (11)   | play a card from slot 1          | 1 player away  | number clue not touching the newest card
| 2 (12)   | play a card from slot 2          | 1 player away  | color clue not touching the newest card
| 3 (13)   | play a card from slot 3          | 2 players away | color on newest card
| 4 (14)   | play a card from slot 4          | 2 players away | number clue not touching the newest card
| 5 (15)   | play a one-away card from slot 1 | 2 players away | color clue not touching the newest card
| 6 (16)   | play a one-away card from slot 2 | 3 players away | color on newest card
| 7 (17)   | play a one-away card from slot 3 | 3 players away | number clue not touching the newest card
| 8 (18)   | play a one-away card from slot 4 | 3 players away | color clue not touching the newest card
| 9 (19)   | chop move                        | any player     | number clue on newest card

[(Find Tables)](#find-tables)

<br />

### Omni (4-Player)

| # mod 8 | action                           | person clued   | type of clue
| ------- | -------------------------------- | -------------- | -------------
| 0 (8)   | give clue / discard              | 1 player away  | number clue on newest card
| 1 (9)   | play a card from slot 1          | 1 player away  | color clue on newest card
| 2 (10)  | play a card from slot 2          | 2 players away | number clue on newest card
| 3 (11)  | play a card from slot 3          | 2 players away | color clue on newest card
| 4 (12)  | play a card from slot 4          | 3 players away | number clue on newest card
| 5 (13)  | play a one-away card from slot 1 | 3 players away | color clue on newest card
| 6 (14)  | play a one-away card from chop   | any player     | number clue not touching the newest card
| 7 (15)  | chop move                        | any player     | color clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### Null (4-Player)

| # mod 8 | action                           | person clued   | type of clue
| ------- | -------------------------------- | -------------- | -------------
| 0 (8)   | give clue / discard              | 1 player away  | number clue not touching the newest card
| 1 (9)   | play a card from slot 1          | 1 player away  | color clue not touching the newest card
| 2 (10)  | play a card from slot 2          | 2 players away | number clue not touching the newest card
| 3 (11)  | play a card from slot 3          | 2 players away | color clue not touching the newest card
| 4 (12)  | play a card from slot 4          | 3 players away | number clue not touching the newest card
| 5 (13)  | play a one-away card from slot 1 | 3 players away | color clue not touching the newest card
| 6 (14)  | play a one-away card from chop   | any player     | number clue on newest card
| 7 (15)  | chop move                        | any player     | color clue on newest card

[(Find Tables)](#find-tables)

<br />

### Muddy Rainbow (4-Player)

| # mod 8 | action                           | person clued   | type of clue
| ------- | -------------------------------- | -------------- | -------------
| 0 (8)   | give clue / discard              | 1 player away  | number clue not touching the newest card
| 1 (9)   | play a card from slot 1          | 1 player away  | color clue on newest card
| 2 (10)  | play a card from slot 2          | 2 players away | number clue not touching the newest card
| 3 (11)  | play a card from slot 3          | 2 players away | color clue on newest card
| 4 (12)  | play a card from slot 4          | 3 players away | number clue not touching the newest card
| 5 (13)  | play a one-away card from slot 1 | 3 players away | color clue on newest card
| 6 (14)  | play a one-away card from chop   | any player     | number clue on newest card
| 7 (15)  | chop move                        | any player     | color clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### Light Pink (4-Player)

| # mod 8 | action                           | person clued   | type of clue
| ------- | -------------------------------- | -------------- | -------------
| 0 (8)   | give clue / discard              | 1 player away  | number clue on newest card
| 1 (9)   | play a card from slot 1          | 1 player away  | color clue not touching the newest card
| 2 (10)  | play a card from slot 2          | 2 players away | number clue on newest card
| 3 (11)  | play a card from slot 3          | 2 players away | color clue not touching the newest card
| 4 (12)  | play a card from slot 4          | 3 players away | number clue on newest card
| 5 (13)  | play a one-away card from slot 1 | 3 players away | color clue not touching the newest card
| 6 (14)  | play a one-away card from chop   | any player     | number clue not touching the newest card
| 7 (15)  | chop move                        | any player     | color clue on newest card

[(Find Tables)](#find-tables)

<br />

### Extremely Ambiguous (4-player)

| # mod 9 | action                           | person clued   | type of clue
| ------- | -------------------------------- | -------------- | -------------
| 0 (9)   | give clue / discard              | 1 player away  | number clue on newest card
| 1 (10)  | play a card from slot 1          | 1 player away  | number clue not touching the newest card
| 2 (11)  | play a card from slot 2          | 1 player away  | color clue
| 3 (12)  | play a card from slot 3          | 2 players away | number clue on newest card
| 4 (13)  | play a card from slot 4          | 2 players away | number clue not touching the newest card
| 5 (14)  | play a one-away card from slot 1 | 2 players away | color clue
| 6 (15)  | play a one-away card from slot 2 | 3 players away | number clue on newest card
| 7 (16)  | play a one-away card from chop   | 3 players away | number clue not touching the newest card
| 8 (17)  | chop move                        | 3 players away | color clue

[(Find Tables)](#find-tables)

<br />

## Clue Interpretation Tables (5-player)

* 3 Suits 5-Player Conventions: [See here](https://github.com/iamwhoiamhahaha/hanabi/blob/master/hat-guessing/3_Suits_5-Player_Conventions.md).

### General Table (5-player)

| # mod 8 | action                           | person clued   | type of clue
| ------- | -------------------------------- | -------------- | -------------
| 0 (8)   | give clue / discard              | 1 player away  | number clue
| 1 (9)   | play a card from slot 1          | 1 player away  | color clue
| 2 (10)  | play a card from slot 2          | 2 players away | number clue
| 3 (11)  | play a card from slot 3          | 2 players away | color clue
| 4 (12)  | play a card from slot 4          | 3 players away | number clue
| 5 (13)  | play a one-away card from slot 1 | 3 players away | color clue
| 6 (14)  | play a one-away card from chop   | 4 players away | number clue
| 7 (15)  | chop move                        | 4 players away | color clue

[(Find Tables)](#find-tables)

<br />

### No Variant / Clue Starved / Cow & Pig (5-Player)

| # mod 16 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (16)   | give clue / discard              | 1 player away  | number on newest card
| 1 (17)   | play a card from slot 1          | 1 player away  | color on newest card
| 2 (18)   | play a card from slot 2          | 1 player away  | number clue not touching the newest card
| 3 (19)   | play a card from slot 3          | 1 player away  | color clue not touching the newest card
| 4 (20)   | play a card from slot 4          | 2 players away | number on newest card
| 5 (21)   | (N/A)                            | 2 players away | color on newest card
| 6 (22)   | (N/A)                            | 2 players away | number clue not touching the newest card
| 7 (23)   | (N/A)                            | 2 players away | color clue not touching the newest card
| 8 (24)   | (N/A)                            | 3 players away | number on newest card
| 9 (25)   | play a one-away card from slot 1 | 3 players away | color on newest card
| 10 (26)  | play a one-away card from slot 2 | 3 players away | number clue not touching the newest card
| 11 (27)  | play a one-away card from slot 3 | 3 players away | color clue not touching the newest card
| 12 (28)  | play a one-away card from slot 4 | 4 players away | number on newest card
| 13 (29)  | triple chop move                 | 4 players away | color on newest card
| 14 (30)  | double chop move                 | 4 players away | number clue not touching the newest card
| 15 (31)  | chop move                        | 4 players away | color clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### Rainbow / Pink / Ambiguous / Very Ambiguous / Dual-Color (5-Player)

| # mod 12 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (12)   | give clue / discard              | 1 player away  | number on newest card
| 1 (13)   | play a card from slot 1          | 1 player away  | color on newest card
| 2 (14)   | play a card from slot 2          | 1 player away  | any clue not touching the newest card
| 3 (15)   | play a card from slot 3          | 2 players away | number on newest card
| 4 (16)   | play a card from slot 4          | 2 players away | color on newest card
| 5 (17)   | play a one-away card from slot 1 | 2 players away | any clue not touching the newest cardd
| 6 (18)   | play a one-away card from slot 2 | 3 players away | number on newest card
| 7 (19)   | play a one-away card from slot 3 | 3 players away | color on newest card
| 8 (20)   | play a one-away card from slot 4 | 3 players away | any clue not touching the newest card
| 9 (21)   | triple chop move                 | 4 players away | number on newest card
| 10 (22)  | double chop move                 | 4 players away | color on newest card
| 11 (23)  | chop move                        | 4 players away | any clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### White / Brown / Up or Down (5-Player)

| # mod 12 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (12)   | give clue / discard              | 1 player away  | any clue on newest card
| 1 (13)   | play a card from slot 1          | 1 player away  | number clue not touching the newest card
| 2 (14)   | play a card from slot 2          | 1 player away  | color clue not touching the newest card
| 3 (15)   | play a card from slot 3          | 2 players away | any clue on newest card
| 4 (16)   | play a card from slot 4          | 2 players away | number clue not touching the newest card
| 5 (17)   | play a one-away card from slot 1 | 2 players away | color clue not touching the newest card
| 6 (18)   | play a one-away card from slot 2 | 3 players away | any clue on newest card
| 7 (19)   | play a one-away card from slot 3 | 3 players away | number clue not touching the newest card
| 8 (20)   | play a one-away card from slot 4 | 3 players away | color clue not touching the newest card
| 9 (21)   | triple chop move                 | 4 players away | any clue on newest card
| 10 (22)  | double chop move                 | 4 players away | number clue not touching the newest card
| 11 (23)  | chop move                        | 4 players away | color clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### Omni (5-Player)

| # mod 10 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (10)   | give clue / discard              | 1 player away  | number clue on newest card
| 1 (11)   | play a card from slot 1          | 1 player away  | color clue on newest card
| 2 (12)   | play a card from slot 2          | 2 players away | number clue on newest card
| 3 (13)   | play a card from slot 3          | 2 players away | color clue on newest card
| 4 (14)   | play a card from slot 4          | 3 players away | number clue on newest card
| 5 (15)   | play a one-away card from slot 1 | 3 players away | color clue on newest card
| 6 (16)   | play a one-away card from slot 2 | 4 players away | number clue on newest card
| 7 (17)   | play a one-away card from slot 3 | 4 players away | color clue on newest card
| 8 (18)   | play a one-away card from slot 4 | any player     | number clue not touching the newest card
| 9 (19)   | chop move                        | any player     | color clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### Null (5-Player)

| # mod 10 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (10)   | give clue / discard              | 1 player away  | number clue not touching the newest card
| 1 (11)   | play a card from slot 1          | 1 player away  | color clue not touching the newest card
| 2 (12)   | play a card from slot 2          | 2 players away | number clue not touching the newest card
| 3 (13)   | play a card from slot 3          | 2 players away | color clue not touching the newest card
| 4 (14)   | play a card from slot 4          | 3 players away | number clue not touching the newest card
| 5 (15)   | play a one-away card from slot 1 | 3 players away | color clue not touching the newest card
| 6 (16)   | play a one-away card from slot 2 | 4 players away | number clue not touching the newest card
| 7 (17)   | play a one-away card from slot 3 | 4 players away | color clue not touching the newest card
| 8 (18)   | play a one-away card from slot 4 | any player     | number clue on newest card
| 9 (19)   | chop move                        | any player     | color clue on newest card

[(Find Tables)](#find-tables)

<br />

### Muddy Rainbow (5-Player)

| # mod 10 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (10)   | give clue / discard              | 1 player away  | number clue not touching the newest card
| 1 (11)   | play a card from slot 1          | 1 player away  | color clue on newest card
| 2 (12)   | play a card from slot 2          | 2 players away | number clue not touching the newest card
| 3 (13)   | play a card from slot 3          | 2 players away | color clue on newest card
| 4 (14)   | play a card from slot 4          | 3 players away | number clue not touching the newest card
| 5 (15)   | play a one-away card from slot 1 | 3 players away | color clue on newest card
| 6 (16)   | play a one-away card from slot 2 | 4 players away | number clue not touching the newest card
| 7 (17)   | play a one-away card from slot 3 | 4 players away | color clue on newest card
| 8 (18)   | play a one-away card from slot 4 | any player     | number clue on newest card
| 9 (19)   | chop move                        | any player     | color clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### Light Pink (5-Player)

| # mod 10 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (10)   | give clue / discard              | 1 player away  | number clue on newest card
| 1 (11)   | play a card from slot 1          | 1 player away  | color clue not touching the newest card
| 2 (12)   | play a card from slot 2          | 2 players away | number clue on newest card
| 3 (13)   | play a card from slot 3          | 2 players away | color clue not touching the newest card
| 4 (14)   | play a card from slot 4          | 3 players away | number clue on newest card
| 5 (15)   | play a one-away card from slot 1 | 3 players away | color clue not touching the newest card
| 6 (16)   | play a one-away card from slot 2 | 4 players away | number clue on newest card
| 7 (17)   | play a one-away card from slot 3 | 4 players away | color clue not touching the newest card
| 8 (18)   | play a one-away card from slot 4 | any player     | number clue not touching the newest card
| 9 (19)   | chop move                        | any player     | color clue on newest card

[(Find Tables)](#find-tables)

<br />

### Extremely Ambiguous (5-player)

| # mod 12 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (12)   | give clue / discard              | 1 player away  | number clue on newest card
| 1 (13)   | play a card from slot 1          | 1 player away  | number clue not touching the newest card
| 2 (14)   | play a card from slot 2          | 1 player away  | color clue
| 3 (15)   | play a card from slot 3          | 2 players away | number clue on newest card
| 4 (16)   | play a card from slot 4          | 2 players away | number clue not touching the newest card
| 5 (17)   | play a one-away card from slot 1 | 2 players away | color clue
| 6 (18)   | play a one-away card from slot 2 | 3 players away | number clue on newest card
| 7 (19)   | play a one-away card from slot 3 | 3 players away | number clue not touching the newest card
| 8 (20)   | play a one-away card from slot 4 | 3 players away | color clue
| 9 (21)   | triple chop move                 | 4 players away | number clue on newest card
| 10 (22)  | double chop move                 | 4 players away | number clue not touching the newest card
| 11 (23)  | chop move                        | 4 players away | color clue

[(Find Tables)](#find-tables)

<br />

### Color Mute / Number Mute / Alternating Clues (5-player)

| # mod 8 | action                           | person clued   | type of clue
| ------- | -------------------------------- | -------------- | -------------
| 0 (8)   | give clue / discard              | 1 player away  | any clue on newest card
| 1 (9)   | play a card from slot 1          | 1 player away  | any clue not touching the newest card
| 2 (10)  | play a card from slot 2          | 2 players away | any clue on newest card
| 3 (11)  | play a card from slot 3          | 2 players away | any clue not touching the newest card
| 4 (12)  | play a card from slot 4          | 3 players away | any clue on newest card
| 5 (13)  | play a one-away card from slot 1 | 3 players away | any clue not touching the newest card
| 6 (14)  | play a one-away card from chop   | 4 players away | any clue on newest card
| 7 (15)  | chop move                        | 4 players away | any clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### Duck (5-player)

| # mod 9 | action                           | person clued   | type of clue
| ------- | -------------------------------- | -------------- | -------------
| 0 (9)   | give clue / discard              | 1 player away  | any clue on newest card
| 1 (10)  | play a card from slot 1          | 1 player away  | any clue not touching the newest card
| 2 (11)  | play a card from slot 2          | 2 players away | any clue on newest card
| 3 (12)  | play a card from slot 3          | 2 players away | any clue not touching the newest card
| 4 (13)  | play a card from slot 4          | 3 players away | any clue on newest card
| 5 (14)  | play a one-away card from slot 1 | 3 players away | any clue not touching the newest card
| 6 (15)  | play a one-away card from slot 2 | 4 players away | any clue on newest card
| 7 (16)  | play a one-away card from chop   | 4 players away | any clue not touching the newest card
| 8 (17)  | chop move                        | any player     | any clue touching only oldest card

[(Find Tables)](#find-tables)

<br />

## Clue Interpretation Tables (6-player)

### General Table (6-Player)

| # mod 10 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (10)   | give clue / discard              | 1 player away  | number clue
| 1 (11)   | play a card from slot 1          | 1 player away  | color clue
| 2 (12)   | play a card from slot 2          | 2 players away | number clue
| 3 (13)   | play a card from slot 3          | 2 players away | color clue
| 4 (14)   | play a card from slot 4          | 3 players away | number clue
| 5 (15)   | play a one-away card from slot 1 | 3 players away | color clue
| 6 (16)   | play a one-away card from slot 2 | 4 players away | number clue
| 7 (17)   | play a one-away card from slot 3 | 4 players away | color clue
| 8 (18)   | play a one-away card from slot 4 | 5 players away | number clue
| 9 (19)   | chop move                        | 5 players away | color clue

[(Find Tables)](#find-tables)

<br />

### No Variant / Clue Starved / Cow & Pig (6-Player)

| # mod 15 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (15)   | give clue / discard              | 1 player away  | number on newest card
| 1 (16)   | play a card from slot 1          | 1 player away  | color on newest card
| 2 (17)   | play a card from slot 2          | 1 player away  | any clue not touching the newest card
| 3 (18)   | play a card from slot 3          | 2 players away | number on newest card
| 4 (19)   | play a card from slot 4          | 2 players away | color on newest card
| 5 (20)   | (N/A)                            | 2 players away | any clue not touching the newest card
| 6 (21)   | (N/A)                            | 3 players away | number on newest card
| 7 (22)   | (N/A)                            | 3 players away | color on newest card
| 8 (23)   | (N/A)                            | 3 players away | any clue not touching the newest card
| 9 (24)   | play a one-away card from slot 1 | 4 players away | number on newest card
| 10 (25)  | play a one-away card from slot 2 | 4 players away | color on newest card
| 11 (26)  | play a one-away card from slot 3 | 4 players away | any clue not touching the newest card
| 12 (27)  | play a one-away card from slot 4 | 5 players away | number on newest card
| 13 (28)  | double chop move                 | 5 players away | color on newest card
| 14 (29)  | chop move                        | 5 players away | any clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### Rainbow / Ambiguous / Very Ambiguous / Dual-Color (6-Player)

| # mod 11 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (11)   | give clue / discard              | 1 player away  | number on newest card
| 1 (12)   | play a card from slot 1          | 1 player away  | color on newest card
| 2 (13)   | play a card from slot 2          | 2 players away | number on newest card
| 3 (14)   | play a card from slot 3          | 2 players away | color on newest card
| 4 (15)   | play a card from slot 4          | 3 players away | number on newest card
| 5 (16)   | play a one-away card from slot 1 | 3 players away | color on newest card
| 6 (17)   | play a one-away card from slot 2 | 4 players away | number on newest card
| 7 (18)   | play a one-away card from slot 3 | 4 players away | color on newest card
| 8 (19)   | play a one-away card from slot 4 | 5 players away | number on newest card
| 9 (20)   | double chop move                 | 5 players away | color on newest card
| 10 (21)  | chop move                        | any player     | number clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### Pink (6-Player)

| # mod 11 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (11)   | give clue / discard              | 1 player away  | number on newest card
| 1 (12)   | play a card from slot 1          | 1 player away  | color on newest card
| 2 (13)   | play a card from slot 2          | 2 players away | number on newest card
| 3 (14)   | play a card from slot 3          | 2 players away | color on newest card
| 4 (15)   | play a card from slot 4          | 3 players away | number on newest card
| 5 (16)   | play a one-away card from slot 1 | 3 players away | color on newest card
| 6 (17)   | play a one-away card from slot 2 | 4 players away | number on newest card
| 7 (18)   | play a one-away card from slot 3 | 4 players away | color on newest card
| 8 (19)   | play a one-away card from slot 4 | 5 players away | number on newest card
| 9 (20)   | double chop move                 | 5 players away | color on newest card
| 10 (21)  | chop move                        | any player     | color clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### White (6-Player)

| # mod 11 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (11)   | give clue / discard              | 1 player away  | number on newest card
| 1 (12)   | play a card from slot 1          | 1 player away  | color clue not touching the newest card
| 2 (13)   | play a card from slot 2          | 2 players away | number on newest card
| 3 (14)   | play a card from slot 3          | 2 players away | color clue not touching the newest card
| 4 (15)   | play a card from slot 4          | 3 players away | number on newest card
| 5 (16)   | play a one-away card from slot 1 | 3 players away | color clue not touching the newest card
| 6 (17)   | play a one-away card from slot 2 | 4 players away | number on newest card
| 7 (18)   | play a one-away card from slot 3 | 4 players away | color clue not touching the newest card
| 8 (19)   | play a one-away card from slot 4 | 5 players away | number on newest card
| 9 (20)   | double chop move                 | 5 players away | color clue not touching the newest newest card
| 10 (21)  | chop move                        | any player     | number clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### Brown / Up or Down (6-Player)

| # mod 11 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (11)   | give clue / discard              | 1 player away  | number clue not touching the newest card
| 1 (12)   | play a card from slot 1          | 1 player away  | color on newest card
| 2 (13)   | play a card from slot 2          | 2 players away | number clue not touching the newest card
| 3 (14)   | play a card from slot 3          | 2 players away | color on newest card
| 4 (15)   | play a card from slot 4          | 3 players away | number clue not touching the newest card
| 5 (16)   | play a one-away card from slot 1 | 3 players away | color on newest card
| 6 (17)   | play a one-away card from slot 2 | 4 players away | number clue not touching the newest card
| 7 (18)   | play a one-away card from slot 3 | 4 players away | color on newest card
| 8 (19)   | play a one-away card from slot 4 | 5 players away | number clue not touching the newest card
| 9 (20)   | double chop move                 | 5 players away | color on newest card
| 10 (21)  | chop move                        | any player     | color clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### Omni (6-Player)

| # mod 10 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (10)   | give clue / discard              | 1 player away  | number on newest card
| 1 (11)   | play a card from slot 1          | 1 player away  | color on newest card
| 2 (12)   | play a card from slot 2          | 2 players away | number on newest card
| 3 (13)   | play a card from slot 3          | 2 players away | color on newest card
| 4 (14)   | play a card from slot 4          | 3 players away | number on newest card
| 5 (15)   | play a one-away card from slot 1 | 3 players away | color on newest card
| 6 (16)   | play a one-away card from slot 2 | 4 players away | number on newest card
| 7 (17)   | play a one-away card from slot 3 | 4 players away | color on newest card
| 8 (18)   | play a one-away card from slot 4 | 5 players away | number on newest card
| 9 (19)   | chop move                        | 5 players away | color on newest card

[(Find Tables)](#find-tables)

<br />

### Null (6-Player)

| # mod 10 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (10)   | give clue / discard              | 1 player away  | number clue not touching the newest card
| 1 (11)   | play a card from slot 1          | 1 player away  | color clue not touching the newest card
| 2 (12)   | play a card from slot 2          | 2 players away | number clue not touching the newest card
| 3 (13)   | play a card from slot 3          | 2 players away | color clue not touching the newest card
| 4 (14)   | play a card from slot 4          | 3 players away | number clue not touching the newest card
| 5 (15)   | play a one-away card from slot 1 | 3 players away | color clue not touching the newest card
| 6 (16)   | play a one-away card from slot 2 | 4 players away | number clue not touching the newest card
| 7 (17)   | play a one-away card from slot 3 | 4 players away | color clue not touching the newest card
| 8 (18)   | play a one-away card from slot 4 | 5 players away | number clue not touching the newest card
| 9 (19)   | chop move                        | 5 players away | color clue not touching the newest card

[(Find Tables)](#find-tables)

<br />

### Muddy Rainbow (6-Player)

| # mod 10 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (10)   | give clue / discard              | 1 player away  | number clue not touching the newest card
| 1 (11)   | play a card from slot 1          | 1 player away  | color on newest card
| 2 (12)   | play a card from slot 2          | 2 players away | number clue not touching the newest card
| 3 (13)   | play a card from slot 3          | 2 players away | color on newest card
| 4 (14)   | play a card from slot 4          | 3 players away | number clue not touching the newest card
| 5 (15)   | play a one-away card from slot 1 | 3 players away | color on newest card
| 6 (16)   | play a one-away card from slot 2 | 4 players away | number clue not touching the newest card
| 7 (17)   | play a one-away card from slot 3 | 4 players away | color on newest card
| 8 (18)   | play a one-away card from slot 4 | 5 players away | number clue not touching the newest card
| 9 (19)   | chop move                        | 5 players away | color on newest card

[(Find Tables)](#find-tables)

<br />

### Light Pink (6-Player)

| # mod 10 | action                           | person clued   | type of clue
| -------- | -------------------------------- | -------------- | -------------
| 0 (10)   | give clue / discard              | 1 player away  | number on newest card
| 1 (11)   | play a card from slot 1          | 1 player away  | color clue not touching the newest card
| 2 (12)   | play a card from slot 2          | 2 players away | number on newest card
| 3 (13)   | play a card from slot 3          | 2 players away | color clue not touching the newest card
| 4 (14)   | play a card from slot 4          | 3 players away | number on newest card
| 5 (15)   | play a one-away card from slot 1 | 3 players away | color clue not touching the newest card
| 6 (16)   | play a one-away card from slot 2 | 4 players away | number on newest card
| 7 (17)   | play a one-away card from slot 3 | 4 players away | color clue not touching the newest card
| 8 (18)   | play a one-away card from slot 4 | 5 players away | number on newest card
| 9 (19)   | chop move                        | 5 players away | color clue not touching the newest card

[(Find Tables)](#find-tables)

<br />
