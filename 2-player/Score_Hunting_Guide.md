# Score Hunting Guide (2-Player)

* This is the guide for score hunting in 2-player games created by [IAMJEFF](https://github.com/iamwhoiamhahaha) in 2020.
* The goal of this document is to get the maximum score in any variant with the most efficient/minimum amount of attempts. Thus, they are designed to be quite aggressive.
* If you're looking for conservative way to play a 2-player game, please read [2-Player Conventions for the Hyphen-ated Framework](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md).

<br/>

## Table of Contents

1. [Introduction](#introduction)
2. [Conventions Changed](#conventions-changed)
3. [General Guide](#general-guide)
   * [First Turn Stall Guide](#first-turn-stall-guide)
   * [Chop Move Guide](#chop-move-guide)
   * [Self Color Bluff Guide](#self-color-bluff-guide)
4. [Variant-Specific Guide](#variant-specific-guide)
5. [Other Conventions](#other-conventions)
   * [About Play Clues](#about-play-clues)
   * [About Save Clues](#about-save-clues)
   * [Miscellaneous](#miscellaneous)
6. [Variant-Specific Conventions](#variant-specific-conventions)
7. [Convention Attribution](#convention-attribution-2-player)

<br/>

## Introduction

* Hello!  This document is for those players who want to explore what 2-player Hanabi has to offer.  From my experience, 2-player games are interesting and fun, where you are allowed to quickly gain experience and are still able to do special moves compared to 3-player+ games.  Self Color Bluffs, for example, they are illegal in 3 or more player games; however, they are one of the most common moves in 2-player games.
* Believe it or not, 2-player games are key to become a top Hanabi player. First, the gameplay is quite fast.  This allows you to accumulate a lot of experience to deal with troubles in various situations. Secondly, 2-player games are heavily contextual.  These games will help you cultivate your play style to train you to understand clues contextually in order to respond accordingly.
* As a player who has over 4000+ games in 2-player, I’ve found a lot of players tend to struggle. Thus, this is the main reason I wrote this document, in the hopes that everyone can enjoy 2-player games and be able to get the maximum scores for the variants that they wish to have. Happy hunting!
<br/>

## Conventions Changed

### 2p Conventions which are *turned on*

* ***[Tempo Change](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#tempo-change)***
* ***[Priority Change](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#priority-change)***
* ***[First Turn Stalls](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#first-turn-stalls)***
  * See the *[First Turn Stall Guide](#first-turn-stalls-guide)* below for more details.
* ***[Flush Clue](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#the-flush-clue-a-slot-1-color-clue)***
* ***[Self-Bluffs with Color Clues (Self Color Bluff)](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#self-bluffs-with-color-clues)***
  * See the *[Self Color Bluff Guide](#self-color-bluff-guide)* below for advanced usage.
* ***[Delayed Bluff](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#the-delayed-bluff)***
* ***[Scream Discard Modification](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#scream-discard-modification)***
  * Note that the players are allowed to perform a *Scream Discard Chop Move* in any clue.
* ***[Double Scream Blind-Play (Blind-Playing Chop)](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#the-double-scream-blind-play-blind-playing-chop)***
* ***[Skipped Discard Chop Move](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#the-skipped-discard-chop-move)***
* ***[Selfish Conventions](Selfish_Conventions.md)***
  * *[Selfish Chop Move](Selfish_Conventions.md#selfish-chop-move)*
  * *[Selfish Bluff](Selfish_Conventions.md#selfish-bluff)*
  * *[Selfish Focus Inversion](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#selfish-focus-inversion-sfi--sfi)*

### 2p Conventions which are *turned off*

* ***[One-Away Saves](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#one-away-saves)***
* ***[Second Turn Stalls](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#second-turn-stalls)***
* ***[5's Double Chop Move](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#the-5s-double-chop-move)***
* ***[Double Discard Save Stalls](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#double-discard-save-stalls)***
* ***[Scream Push (Anxiety with a Chop Move)](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#the-scream-push-anxiety-with-a-chop-move)***
* ***[Scream Blind-Play (Blind-Playing Chop)](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#the-scream-blind-play-blind-playing-chop)***
  * Blind-playing the *Chop* is always *Double Chop Move* (as a *Double Scream Blind-Play*).
  * If you want to *Chop Move* only one card while in no clues, use *Skipped Discard Chop Move*.
* ***[Double Skipped Discard Chop Move](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#the-double-skipped-discard-chop-move)***
  * It is treated as a *Positional Discard*.

### 2p Variant-Specific Conventions which are *turned on*
* ***[Flush Save](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#the-flush-save)***
* ***[Dark Chop Move](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#the-dark-chop-move)***
* ***[Implied Color Truth](https://github.com/Zamiell/hanabi-conventions/blob/master/misc/2-Player.md#implied-color-truth)***
  * Turn off if you want to apply *[Implied Saves](#implied-saves)* to rainbow cards.

### 3p+ Conventions which are *turned on*

* ***[3 Bluff](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#the-3-bluff)***
* ***[4 Double Bluff](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#the-4-double-bluff)***
* ***[5's Chop Move](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#the-5s-chop-move)***
* ***[5 Pull](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#the-5-pull)***
  * Note that the players are allowed to do a *5 Pull* at the start of the *Mid-Game*.
* ***[Anxiety Play](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#the-anxiety-play-forcing-a-locked-player-to-play)***

### 3p+ Conventions which are *turned off*

* ***[Double Discard Avoidance](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#double-discard-situations)***
* ***[Occupied Play Clue](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#the-occupied-play-clue--the-occupied-finesse-opc--opc)***
* ***[Loaded Play Clue](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#loaded-play-clues-in-hard-variants-part-1)***
  * The players can choose to turn *Loaded Play Clue* on. But from my experience, it is better to turn it off and enable [*Double Loaded Play Clue*](#double-loaded-play-clue) and [*Overloaded Play Clue*](#overloaded-play-clue).

<br/>

## General Guide

### First Turn Stall Guide

> #### First Turn Stalls
> * On the very first turn of the game, if a known-unplayable card is clued, then it should be treated as a *Save Clue* (instead of a *Self-Finesse*).
> * Note that players are allowed to use this ability even if there are other playable cards in the hand.

* First, look at your teammate's hand, is it able to give a *Save Clue* to "setup" a *Finesse*, a *Bluff* or even a *5 Pull*?
* Then you should note that if there are any critical cards on chop (or 2s) needed to be saved, and your teammate might discard on their turn? (e.g. you don't have playable cards)
* In this situation, you might have to think that whether you should to take a risk to setup the *Finesse*, or just simply give a *Save Clue* on their *Chop*.
* There is no correct answer, you have to balance the pros and cons depending on the situation yourself.
* For example, in a [*Light Pink (6 Suits)* game](https://hanabi.live/replay/160166):
  * Instead of giving a 1 clue, eevee opens with a 3 clue touching a light pink 4 on slot 1 and a purple 3 on slot 5.
  * Piper gives a 4 clue as a *4 Double Bluff*.
  * Eevee gives a 4 clue as another *4 Double Bluff*.
  ![First Turn Stall Example](https://github.com/iamwhoiamhahaha/hanabi/blob/master/images/2-player/first_turn_stall_guide.png)

### Game Flow Guide

* Never directly lock a player with a clue.  Use one of the chop moves in the [Chop Move Guide](https://github.com/Dr-Kakashi/hanabi/blob/master/2-player/Chop_Move_Guide.md#semi-emergency-chop-moves-without-wasting-a-clue)
  * The main reason for this is because it essentially burns a clue.  The locked player must give a clue, thus they have less clues to unlock themselves.  This is the main reason why one of the skip discard chop moves is preferred as it gains an extra clue for the player to unlock themselves.
  
* If in a 1 clue situation, where you spend the clue to save a card and your partner is 1 card away from being locked, it's best to skip discard chop move.
  * You want to try to draw cards away from them as they are about to be locked.
  * It gains a clue for the team.  The team will be in a 2 clue situation, instead of a 0 clue situation.
  * If you spend the clue to save them, they are forced to discard.  This means, if they draw a critical card, you're forced to skip discard anyways.   
  * Your teammate should do their best to not lock you.  

### Chop Move Guide

* *Chop Moves* are extremely important in 2-player games. Knowing how to perform a *Chop Move* in different circumstances is key to win maximum scores.
* Please read the guide [here](Chop_Move_Guide.md).

### Self Color Bluff Guide

> #### Self Color Bluff (SCB)
> * In non-2-player games, *Self-Bluffs* with color clues are explicitly illegal. However, in 2-player games, they are allowed.
> * In other words, if a color clue does not touch a brand-new card and the player who receives the clue knows that the cards touched are not playable, then they know it is a signal to blind-play their *Finessed Position*.
> * Thus, *Tempo Clues* take priority over *Self Color Bluff* by means of *Occam's Razor*.
> * Note that you are also allowed to perform a *Self Color Bluff* by touching a *Chop Moved* card.

* This is one of the most powerful move in 2-player, which not only provides more information on your teammate's clued card, but also get a free blind-card.
* Tip: Always give the clue by touching a one-away card, because it is more likely to be playable compared to two or more away card.
* If you want to play hanabi extremely aggressively, you can perform a *Self Color Bluff* by touching any card if it has full context that it is not playable, including a *Chop Moved* card or a brand-new card.
* Example 1, a *Brown & Light Pink (6 Suits)* game:
  * [154213, Turn 21](https://hanabi.live/replay/154213/21): Bluffing a pink 1 by touching a brand-new green 3 with a green clue.
  * [154213, Turn 33](https://hanabi.live/replay/154213/33): Bluffing a yellow 2 by touching a brand-new brown 4 with a brown clue. (*Telling my teammate they have a brown 4 so that we don't need to worry about brown blocking cards for the rest of the game.*)
* Example 2, a *Light Pink (6 Suits)* game:
  * [160146, Turn 21](https://hanabi.live/replay/160146/21): Bluffing a purple 1 by touching a brand-new red 5 on chop with a red clue. (***Typically, it is a 5CE!***)
  * [160146, Turn 43](https://hanabi.live/replay/160146/43): Bluffing a green 1 by touching a brand-new (critical) blue 4 with a blue clue. (*Pre-saving a critical card.*)
* Example 3, a *Pink-Ones & Brown* game:
  * [171723, Turn 43](https://hanabi.live/replay/171723/43): Bluffing by touching an unknown playable card
  * [171735, Turn 42](https://hanabi.live/replay/171735/42): Bluffing by touching a known playable card -> *Selfish Self Color Bluff*

<br/>

## Variant-Specific Guide

### Hard Suits
* *Brown*, *Muddy Rainbow*, and *Null* are hard suits.
* *[Double Loaded Play Clue](#double-loaded-play-clue)* and *[Overloaded Play Clue](#overloaded-play-clue)* are turned on in the variants with a hard suit.
* Note that *Occupied Play Clue* and *Loaded Play Clue* are turned off in 2-player.

### Brown

* If you receive *Play Clue* with a brown clue, and if you see your teammate has a brown card through your own hand. It is always better to give a *Play Clue* (or a *Tempo Clue*) focusing that brown card before playing your own card.

### Null

* *Self Color Bluffs* are turned off in favor of *Color Positional clues*.
* If a move looks like a *Trash Chop Move* then it is never a *Positional Clue*, unless you have enough context that it is not a *Trash Chop Move*.

<br/>

# Other Conventions

* [About Play Clues](#about-play-clues)
* [About Save Clues](#about-save-clues)
* [Miscellaneous](#miscellaneous)
* [Variant-Specific Conventions](#variant-specific-conventions)

<br/>

## About Play Clues

### 4 Single Bluff

* The players are allowed to perform a *4 Single Bluff* by touching a two-away 4 with a rank clue, if the 4 looks like a one-away card, and this move only gets one blind-card.
* The 4 that was used as a *4 Single Bluff* is not promised to be one-away. And the player who receives the clue should mark nothing on their card.

### Anxiety Play Shift

* This applies to situations where a player becomes locked but has a playable card or has a playable card through a partner's clued cards.
* Generally in an *Anxiety* situation, the player must play the card that is most likely playable. If there is more than one option, then they should know that the left-most is playable.
* However, what if that card isn't playable? A partner must continue to discard to generate clues to prevent an *Anxiety Play*. Thus, each discard can "shift" the *Anxiety Focus* over by 1 slot.
* For example:
  * All of the 1's are played on the stacks.
  * Alice is locked, she has three 5s with 5 clue on them and the other cards are *Chop Moved*. Her hand: g3, g5, r3, y5, b5 (from left to right).
  * There are only 1 clue in the bank, and it's Alice's turn.
  * Alice gives a red clue touching Bob's red 2 on slot 1. Now, it's 0 clues.
  * Bob knows he has a red 2 on slot 1. However, he cannot play it. If he does, Alice is going to bomb g3 as an *Anxiety Play*. Then he discards.
  * Alice gives a 5 clue as a *5 Stall*.
  * Bob plays the red 2.
  * Now, it's Alice's turn. She is in an *Anxiety* situation. By *Anxiety Play*, she is supposed to play her slot 1. However, if it is playable, then Bob won't discard last turn. Therefore, she knows that her slot 1 must not be playable.
  * Alice also knows *Anxiety Play Shift*, which means her playable card must be on slot 2. However, it is a 5, which is known not to be playable. Thus, her playable card must be on slot 3.
  * Alice blind-plays her red 3 from slot 3.

### Chop Overflowed Positional Clue

* If the player performs a *Double Chop Move* by discarding or misplaying while their teammate only has one card to *Chop Move*; or a *Triple Chop Move*, and their teammate only has one or two cards.
* In this situation, they are trying to perform a *Chop Move* (to all their cards) and a *Positional Clue* (corresponds to the slot they are discarding or misplaying) at the same time.
* For example:
  * Alice has a playable card. Her *Chop* is on slot 3.
  * Bob has an important card on his *Finessed Chop* (a term used to describe the situation where a player's *Chop* is also on their *Fienssed Position*).
  * If Alice discards slot 3, then it is just a *Scream Discard Chop Move*.
  * If Alice discards slot 2, then it is a *Double Chop Move* (*Scream Discard Chop Move* + *Skipped Discard Chop Move*). However, it doesn't make sense, since Bob only has one card to *Chop Move*. Therefore, it is a *Single Chop Move* on Bob and a *Positional Clue* on his slot 2.
  * Similarly, if Alice misplays slot 3, then it is a *Double Scream Blind-Play*. However, it doesn't make sense, since Bob only has one card to *Chop Move*. Therefore, it is a *Single Chop Move* on Bob and a *Positional Clue* on his slot 3.
  
### Chop Overflow Finesse

* If a player performs a Chop Overflow Positional clue, where the indicated slot is not playable, they are trying to perform a *Chop Move* (to all their cards) and a *Positional Clue* to their slot 1.  

<br/>

## About Save Clues

### Locked Hand Save Change

* In 2-player games, *Locked Hand Save* is always treated as an *8 Clue Save*, which means the player are allowed to save any off-chop card with either rank or color clue.
* However, *Flush Clue* takes priority over *Locked Hand Save*. In other words, any color clue fosusing a card on slot 1 is always a *Play Clue*.
* On the other hand, when a rank clue (except a 5 clue) is given focusing a card on slot 1 and if it requires the clue receiver to blind-play **one** or more card to fulfill the *Finesse/Bluff*, it is treated as a *Locked Hand Save*; otherwise, it is a *Play Clue*.

### Tempo Clue Chop Move Change (Jeff)

* Consider the following game-state:
  * Red and green 1 are played on the stacks.
  * Alice has a red 2. She knows rank, but not color.
  * Bob has a non-critical, unclued red 3 on chop.
  * There are no 3s in the discard.
* In this situation, Alice is unable to save Bob’s red 3. For this reason, we turn off *[Tempo Clue Chop Moves](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#the-tempo-clue-chop-move)* in 2-player. If Bob gives a *Tempo Clue* to Alice, she’ll be able to safely give a *Play Clue* to Bob’s red 3 and save it from being discarded.
* *Tempo clues* are therefore encouraged in 2-player, as they allow the team to save non-critical connecting cards.
* However, it would be wasteful to give a *Tempo Clue* which does not allow the team to save a non-critical connecting card. In this scenario, this would be a *Tempo Clue Chop Move*.
* For example, in a *[6 Suit](https://hanabi.live/replay/177641/42)* game:
  * The game-state are shown as the following screenshot. 
  * Kimbifille has a g3 (touched by a 3 clue) on slot 2, a g2 (touched by a green clue) on slot 4, and a b5 on slot 5.
  * Charmander gives a 2 clue touching the g2 as a *Tempo Clue*.
  * Kimbifille knows that *Tempo Clues* are encouraged in 2-player, but she would have saved g3, g4 and g5 anyway, since they're all critical. So this *Tempo Clue* offers no value to the team. It must be a *Tempo Clue Chop Move*.
![Tempo Clue Chop Move](https://github.com/iamwhoiamhahaha/hanabi/blob/master/images/2-player/tempo_clue_chop_move.png)
* Note that this convention is turned off when pace is low or when the player in a special *Stalling* situation.

### Advanced form of Tempo Clue Chop Move Change (Dr_Kakashi & Kimbifille)
![2020-09-27_07-13-33](https://github.com/Dr-Kakashi/hanabi/blob/master/images/2-player/2020-09-27_07-13-33.png)
![2020-09-27_07-25-03](https://github.com/Dr-Kakashi/hanabi/blob/master/images/2-player/2020-09-27_07-25-03.png)
* Following the logic of [Tempo Clue Chop Move Change](#tempo-clue-chop-move-change-jeff), we can take it 1 step further.
* In this situation, should Kakashi tempo the G4?  
  * If Kakashi does nothing, he can gain a lot of information by Kimbi's actions.
  * If Kimbi plays G4, then Kakashi will know that one of his 5's is G5.
  * If Kimbi discards, then it tells Kakashi that none of his 5's is G5.
* Furthermore, in the future, when Kakashi draws G5, Kimbi will immediately play G4.  This means that Kakashi will blind play G5 from slot 1.
* Thus, we can call this card "loaded." As when it does play, it induces a blind play.  
* It would be quite strange for Kakashi to directly clue the G4 for tempo.  Thus, it must have an extra meaning.
* Kakashi wants Kimbi to play now, which means her chop is important.  Thus, Kimbi should Chop Move.  
* [Tempo Clue Chop Move Change](#tempo-clue-chop-move-change-jeff) should be turned off to use this convention.

A card is said to be loaded if:
1. The rest of the suit is "critical."
2. The card will blind play by itself, if teammate draws the critical connecting card(s).
3. If the player who has the clued card, draws the connecting critical card, negative information will get them to play the whole suit.  
4. Its own suit doesn't block a direct tempo clue.  
   * This will prioritze tempoing cards that are easily blocked (Muddy rainbow cards, brown, pink, etc.)

If a card is indeed loaded and your teammate tempo's it, then the player who received the clue, should chop move.  

Situations for when this is turned off. I.e. Kakashi tempoing would not cm. 
1. Pace is 1 or less.
2. Player is Locked or is in a stall situation.

Kakashi should not blind play, if Kimbi is in a situation where she was forced to play.
For example, if she is in anxiety.  

### Sacrifice Discard Chop Move

* If the player is locked, and their teammate's *Chop* is on their *Finessed Position*, and the teammate draws a critical card. In this situation, the player who is locked can sacrifice one of their card to *Chop Move* their teammate as a *Sacrifice Discard Chop Move*.

### Crazy 3/4 Fake Saves

* If there are a 3 or 4 in the trash pile, and if the players don't know they have the other copy of that card (even it is in their hand), they are allowed to "fake save" a random 3 or 4 on chop. And the player who receives the clue shouldn't play into the finesse or bluff.
* Do not perform this move on a two-away 3 or 4. (Unless you think it is valuable.)

### Implied Saves

* If the player receives a *Play Clue* and they don't exactly know the identity of their card, and they see their teammate has a possible "matching" card on their chop (might not be true). Even though there are multiple possibilities for the card, in this situation if they know their teammate won't misplay or play into a *Finesse* or a *Bluff* from context, they can "protect" that card on chop by giving a clue directly.
* For example, in a 4 suits game:
  * Red 1 and blue 1 are played on the stacks.
  * Alice discarded last turn while Bob has a blue 3 on chop.
  * Bob gives a 2 clue touching a red 2 on Alice's slot 1.
  * Alice knows that the 2 could be either a red 2 or blue 2. If it is a blue 2 and Bob might discard the blue 3 if he has nothing to do. Alice gives a blue clue touching the blue 3 on Bob's chop.
  * Bob sees the only playable blue card is blue 2. However, if it is a blue 2, Alice will not disard last turn. He knows that Alice doesn't know the identity of her 2, if she has a blue 2, it is fair enough to protect the blue 3 on chop.
  * Bob marks his blue card as a 3 and discards

<br/>

## Miscellaneous

### Self Color Ejection

* Generally, if the player delays one turn to give a direct *Play Clue* then it should be interpreted as a *Self Color Bluff*.
* However, what if the player delays **two turns** to give a direct *Play Clue*? In this situation, if the clue giver does not make a mistake, and if the clue receiver didn't draw new cards in two turns, then it is a signal as an *Ejection*. The clue receiver should blind-play their *Second Finessed Position* as a *Self Color Ejection*.
* For example, in a [*Black & White (5 Suits)*](https://hanabi.live/replay/174021) game:
  * [Turn 25](https://hanabi.live/replay/174021/25): charmander discards since he has nothing to do.
  * [Turn 26](https://hanabi.live/replay/174021/26): piper gives a 3 clue as a *Play Clue*.
  * [Turn 27](https://hanabi.live/replay/174021/27): charmander gives a red clue (re)touching the red 5 on slot 4.
  * Piper knows that the red 5 is not playable; therefore, it is a signal as a *Self Color Bluff*. However, if his slot 1 was playable, charmander would do it last turn. Thus, piper knows that his playable card must be on slot 2.
  * [Turn 28](https://hanabi.live/replay/174021/28): piper blind-plays slot 2 as a *Self Color Ejection*, and a white 5 is successfully played.
* Actually, this is just a *Self Color Bluff* (with *Focus Slide*). But why not call it an *Ejection*? LOL.

### The BCannon Special

* If your username is **"bcannon"**, and if you are in *Locked Hand Situation*, you should always save a 4 as a *Locked Hand Save*.

<br/>

## Variant-Specific Conventions

### Double Loaded Play Clue

* This convention only apply to the variants with a hard suit.
* *Loaded action* is a situation where the player has `a playable card` or `a known trash`.
* If a clue is given to a chop card and the player has two or more *loaded actions*, then it is treated as a *Play Clue* on that card.
* Note that *Loaded Play Clues* are turned off in 2-player.

### Overloaded Play Clue

* This convention only apply to the variants with a hard suit.
* If a player is *Occupied* and they gives a clue touching a chop card while the clue receiver has a *loaded action*, then it is treated as a *Play Clue* on that card.
* Note that *Occupied Play Clues* and *Loaded Play Clues* are turned off in 2-player.

### Pink Crazy Bluff/Pull

* This convention only applies to variants with a pink suit.
* The players are allowed to use any pink card to do a *3 Bluff*, *4 Doulbe Bluff*, or *5 Pull*.
* *Pink Promise* doesn't apply to the card that is used for *Pink Crazy Bluff/Pull*.

### Pink Crazy 5's Chop Move

* This convention only applies to variants with a pink suit.
* For an emergancy, the players are allowed to break the *Pink Promise* to do a *5's Chop Move* by touching a non-5 pink card with a 5 clue.
* You can only do this with a `pink 2` or a `critical pink card`.

### Null Color Positional Clue Change

* This convention only applies to variants with a null suit.
* A *Color Positional Clue* corresponds to a slot number that is based on the order of the stacks. Stacks correspond to the slot numbers **from left to right**. *("from right to left" in a 3 or more player game)*
* *Color Positional Clues* always "wrap around" to the **newest** card. *("oldest" in a 3 or more player game)*

### Null Positional Double Bluff
* If the player who received a *Positional Clue* cannot find a null card after blind-playing 2 playable cards, they should stop digging for null card as a known *Positional Double Bluff*.

<br/>

## Convention Attribution (2-Player)

### Conventions for All Variants

| Convention Name                 | Inventor
| ------------------------------- | --------
| Tempo Change                    | *(Unknown)*
| Priority Change                 | *(Unknown)*
| First Turn Stalls               | *(Unknown)*
| Flush Clue                      | *(Unknown)*
| Scream Discard Modification     | *(Unknown)*
| Double Scream Blind-Play        | *(Unknown)*
| Skipped Discard Chop Move       | *(Unknown)*
| Self Color Bluff                | IAMJEFF
| Delayed Bluff                   | IAMJEFF & Fireheart
| Sacrifice Discard Chop Move     | IAMJEFF & Fireheart
| 4 Single Bluff                  | IAMJEFF
| Selfish Chop Move               | IAMJEFF
| Selfish Bluff                   | IAMJEFF
| Crazy 3/4 Fake Saves            | IAMJEFF
| Implied Saves                   | IAMJEFF
| Anxiety Play Shift              | IAMJEFF
| Self Color Ejection             | IAMJEFF
| Chop Overflowed Positional Clue | IAMJEFF
| Locked Hand Save Change         | IAMJEFF
| The BCannon Special             | bcannon
| Tempo Clue Chop Move Change     | IAMJEFF & piper
| Advanced form of Tempo Clue Chop Move Change | Dr_Kakashi & Kimbifille
| Reverse Misplay Chop Move       | Dr_Kakashi
| Risk of Duplication Chop Move   | Dr_Kakashi & Kimbifille
| Chop Overflow Finesse           | Dr_Kakashi & Kimbifille

<br/>

### Variant-Specific Conventions

| Convention Name                   | Inventor
| --------------------------------- | --------
| Flush Save                        | *(Unknown)*
| Implied Color Truth               | *(Unknown)*
| Null Color Positional Clue Change | IAMJEFF
| Null Positional Double Bluff      | IAMJEFF & Fireheart
| Dark Chop Move                    | IAMJEFF
| Pink Crazy Bluff/Pull             | IAMJEFF
| Pink Crazy 5's Chop Move          | IAMJEFF
| Double Loaded Play Clue           | IAMJEFF
| Overloaded Play Clue              | IAMJEFF

<br/>
