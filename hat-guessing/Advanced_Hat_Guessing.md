# Advanced Hat-Guessing Conventions

This is an advanced version of [hat-guessing conventions](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/Hat_Guessing.md) invented by [IAMJEFF](https://github.com/iamwhoiamhahaha) in 2020.

<br />

## Introduction

* In regular hat-guessing conventions, players are not able to do a finesse by encoding an action on a one-way card while giving a clue. However, players are now able to do it with these advanced conventions.
* The convention is optimal for any variant with **high required efficiency** and **low starting pace**, e.g., a 3 suits 5-player game.

<br />

## General Conventions

* Most of the rules follow [the conventions](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/Hat_Guessing.md#other-conventions) in regular hat-guessing conventions.

### Priority Rules

* If a player has two or more playable cards (or one-away cards), the priority is as follows:
  1) Unique (e.g. black 1)
  2) Lowest rank
  3) Left-most
* Playable cards and one-away cards have same priority, no one is higher than the other. However, if the clue is ambiguous, playable cards takes priority over one-away cards.

### Finesse Rules

* If a one-away card is finessed, then the finessed component doesn't need to follow the _Priority Rules_.
* If two or more players have same copies of the finessed component, the finesse is on the last player who has it.

### Chop Move Rules

* The players are not allowed to chop move a card while that player has a playable card.
* The players are only allowed to chop move critical cards.

### Discard Rules

* Since _Good Touch Principle_ doesn’t apply to these conventions, players should always discard their right-most card, unless it is chop moved.

<br />

## Clue Interpretation Tables (4-player)

* You can play a No Variant game with any variant-specific table.

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
| 10(22)   | double chop move                 | 3 players away | number clue not touching the newest card
| 11(23)   | chop move                        | 3 players away | color clue not touching the newest card

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

<br />

## Clue Interpretation Tables (5-player)

* 3 Suits 5-player Conventions: [see here](https://github.com/Zamiell/hanabi-conventions/issues/168).
* You can play a No Variant game with any variant-specific table.

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
| 10(26)   | play a one-away card from slot 2 | 3 players away | number clue not touching the newest card
| 11(27)   | play a one-away card from slot 3 | 3 players away | color clue not touching the newest card
| 12(28)   | play a one-away card from slot 4 | 4 players away | number on newest card
| 13(29)   | triple chop move                 | 4 players away | color on newest card
| 14(30)   | double chop move                 | 4 players away | number clue not touching the newest card
| 15(31)   | chop move                        | 4 players away | color clue not touching the newest card

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
| 10(22)   | double chop move                 | 4 players away | color on newest card
| 11(23)   | chop move                        | 4 players away | any clue not touching the newest card

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
| 10(22)   | double chop move                 | 4 players away | number clue not touching the newest card
| 11(23)   | chop move                        | 4 players away | color clue not touching the newest card

<br />

### Omni / Rainbow & Pink / Rainbow & Omni / Pink & Omni (5-Player)

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

<br />

### Null / White & Brown / White & Null / Brown & Null (5-Player)

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

<br />

### Muddy Rainbow / Rainbow & Brown / Rainbow & Muddy Rainbow / Brown & Muddy Rainbow (5-Player)

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

<br />

### Light Pink / Pink & White / Pink & Light Pink / White & Light Pink (5-Player)

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

<br />
