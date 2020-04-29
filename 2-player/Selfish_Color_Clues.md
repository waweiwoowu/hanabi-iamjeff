# Selfish Color Clues
* This is an instruction how you should respond to a _Selfish Color Clue_ while playing a 2-player game.

<br/>

## Conventions
* Here are some conventions related to _Selfish Color Clues_ you might use in the games:

### Selfish Focus Inversion
* See [here](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#selfish-focus-inversion-sfi--sfi).

### Selfish Chop Move
* If the player gives a _Selfish Color Clue_ touching **only** one card and the card is not on chop.
* It is a signal as a _Chop Move_, and the clue receiver should chop move their cards to the right of the clued card.
* For example:
  * Alice gives a blue clue touching a blue 1 on Bob's slot 3.
  * Instead of playing his blue 1, Bob gives a blue clue touching a blue 2 on Alice's slot 4 (which is one-away-from-chop).
  * This is quite strange, since Bob can just get the blue 2 after playing his blue 1. If the blue card is on chop, it is reasonable, for Alice is going to discard a playable card. However, it is not on chop.
  * Imagine the situation where Alice has a critical card on chop, and Bob sees Alice has nothing to do in her turn. If he saves the critical card on chop, the team might lose a playable card, which is quite bad. That's how this convention works.
  * Now, it's Alice's turn, she is surprised that Bob didn't play his blue 1 and gave a blue clue to her.
  * It is not a Selfish Focus Inversion, since it only touches one blue card. Then she realizes her blue card is exactly a blue 2 and also Chop Moves her slot 5 as a _Selfish Chop Move_.

<br/>

## Details

### Case A: The clue only touches one card.
* Case A1: The clued card is on chop → **_Normal Play Clue_**
* Case A2: The clued card is one-away-from-chop → **_Selfish Chop Move_**
* Case A3: The clued card is two-away-from-chop → **_Selfish (Double) Chop Move_**

### Case B: The clue touches multiple cards.
* Case B1: One of the cards is on chop  → _**Normal Play Clue** (Chop Focus)_
* Case B2: None of the cards is on chop and one of the cards is one-away-from-chop → _**Normal Play Clue** (Focus on the leftmost)_
* Case B3: None of the cards is on chop and none of the cards is one-away-from-chop → _**Selfish Focus Inversion**_

<br/>
