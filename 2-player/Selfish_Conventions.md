# Selfish Conventions

* This is an instruction how you should respond to a *Selfish Color Clue* in a 2-player game.

<br/>

## Table of Contents

1. [Selfish Conventions](#selfish-conventions)
2. [Interpretations](#interpretations)

<br/>

## Selfish Conventions

### Selfish Chop Move

* If the player gives a *Selfish Color Clue* touching **only** one card and the card is not on chop (one-away or two-away from chop). It is a signal as a *Chop Move*, and the clue receiver should chop move their cards to the right of the clued card.
* The card which is touched by the *Selfish Color Clue* is promised to be a playable card through the player who gives the clue.
* For example:
  * Alice gives a blue clue touching a blue 1 on Bob's slot 3.
  * Instead of playing his blue 1, Bob gives a blue clue touching a blue 2 on Alice's slot 4 (which is one-away from chop).
  * This is quite strange, since Bob can just get the blue 2 after playing his blue 1. If the blue card is on chop, it is reasonable, for Alice is going to discard a playable card. However, it is not on chop.
  * Imagine the situation where Alice has a critical card on chop, and Bob sees Alice has nothing to do in her turn. If he saves the critical card on chop, the team might lose a playable card, which is quite bad. That's how this convention works.
  * Now, it's Alice's turn, she is surprised that Bob didn't play his blue 1 and gave a blue clue to her. It is not a Selfish Focus Inversion, since it only touches one blue card.
  * Then she realizes her blue card is exactly a blue 2 and also Chop Moves her slot 5 as a *Selfish Chop Move*.

### Selfish Bluff

* If the player gives a *Selfish Color Clue* touching **only** one card and the card is three or more away from chop. Since *Chop Moving* three or more cards is unlikely, in this situation, the clue receiver should blind-play their *Finessed Position* as a *Selfish Bluff*.
* The card which is touched by the *Selfish Color Clue* is promised to be a playable card through the player who gives the clue.

### Selfish Focus Inversion

* See [here](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#selfish-focus-inversion-sfi--sfi).

<br/>

## Interpretations

* Case A: The clue only touches one card.
* Case B: The clue touches multiple cards.

### Case A1: The clued card is on chop 

* Interpretation: ***Normal Play Clue***
* Explanation: Your teammate is going to discard the playable card.

### Case A2: The clued card is one-away-from-chop

* Interpretation: ***Selfish Chop Move***
* Explanation: Your teammate has a critical card on chop.
* Notes: Why do your teammate have a critical card on chop? The most common situation is you just discarded another copy of the card and made your teammate's chop become critical.

### Case A3: The clued card is two-away from chop
* Interpretation: ***Selfish (Double) Chop Move***
* Explanation: Your teammate has two critical cards on chop.

### Case A4: The clued card is three or more away from chop
* Interpretation: ***Selfish Bluff***
* Explanation: *Chop Moving* 3 cards in a row seems unlikely, even in hard variants.

### Case B1: One of the cards is on chop
* Interpretation: ***Normal Play Clue** (Chop Focus)*
* Explanation: Your teammate is going to discard the playable card.

### Case B2: None of the cards is on chop and one of the cards is one-away-from-chop 
* Interpretation: ***Normal Play Clue** (Focus on the leftmost)*
* Explanation: If you don't do it this turn, and if your teammate discards after you play the card, the team loses the focus.
* Example:
  * Alice has a known blue 1. Bob has a blue 2 on slot 2 and a blue 4 on slot 4.
  * If Alice doesn't give a blue clue to Bob this turn and play the blue 1, and if Bob has nothing to do and discards his chop.
  * Then, Alice is not able to give a 2-for-1 blue clue since it turns out to be a _Chop Focus_ clue and the focus is no longer on the blue 2.

### Case B3: None of the cards is on chop and none of the cards is one-away-from-chop 
* Interpretation: ***Selfish Focus Inversion***
* Explanation: It follows the current convention *Selfish Focus Inversion*.

<br/>
