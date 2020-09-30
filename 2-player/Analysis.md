# Hanabi Analysis 

<br/>

## Table of Contents
1. [Introduction](#introduction)
2. [Prevent Locking Partner Analysis ](#prevent-locking-partner-analysis)
3. [Priority Of Which Cards Should Play](#priority-of-which-cards-should-play)
4. [Priority During End Game](#priority-during-end-game)

<br/>

## Introductuion
This document is to show the times I've analyzed hanabi over playing the game. 

<br/>

## Prevent Locking Partner Analysis 
![2020-09-28_20-31-10](https://github.com/Dr-Kakashi/hanabi/blob/master/images/2-player/2020-09-28_20-31-10.png)

* Taking a look at this game, Kakashi needs to decide what to do:
  1. Spend the last clue to directly clue and save the 5 on Kimbi's chop.
  2. Perform a skip discard cm to both cm the 5 on Kimbi's chop and gain 1 clue for the team.

### Skip Discard Option
Kakashi can actually calculate the chance he discards a critical card that effectively ends the game, since we're going for max score.
* His empathy shows that the card on slot 3 has negative pink & negative multi
* Thus, that card can be either B4 or 1 of the 3 5's left in the deck (He can see Y5 and Y4 in Kimbi's hand)
* Ignoring the card on his chop, since by context it is trash, there are effectively 25 cards (in the deck) + 3 cards (in his hand) = 28 cards
* Thus, he has a 4/28 chance or 14.3% chance of discarding a critical card.

### Directly Clue 5 Option
Kakashi can now calculate the chance Kimbi will draw a critical card that will **force** Kakashi to skip discard anyways.
* From Kakashi's perspective, Kimbi can draw Pink 2, Pink 3, Pink 5, Multi 4, Multi 5, Red 5, Green 5, Blue 5 = 8 cards
* There are 25 cards in the deck
* Thus, there is a 8/25 chance or 32% chance Kimbi will draw a Critical Card
* This basically means that there is a 32% chance that Kakashi will be forced to Skip Discard anyways.

Another thing to think about is, if Kakashi directly clue's the 5, Kimbi is forced to discard.  This in turn generates a clue for Kakashi, so something to take into account is what are the chances that Kimbi will draw a playable card.
* Cards that are playable are 2 Red 3's, 2 Yellow 2's, 2 Green 3's, 1 Blue 4, 1 Pink 1, 1 Multi 3 = 9 cards
* Thus, there is a 9/25 chance or 36% chance of drawing a playable card.  
* If Kimbi draws a playable card, she must play, putting Kakashi at 0 clues and again in the situation to be forced to skip discard, if Kimbi draws a critical/playable card.
* Thus, chances of drawing a critical/playable card are 8 + 8 = 16/24 = 66.6%
* We can then calculate the chances of this situation happening: 9/25 * 16/24 = 144/600 = 24%

Now we can just add these two numbers together
* 32% + 24% = 56% 
* This means that there is a 56% chance that Kakashi is **forced** to skip discard, if he directly clues the 5 as a 5 save.

### Pros & Cons
* Skip Discard Option
  * Pros
    * Team will be at 2 clues on Kimbi's turn
    * 5 in Kimbi's hand will be saved
    * Kakashi will be drawing cards instead of Kimbi, effectively drawing cards away from Kimbi (Better card distribution)
    * Kakashi has a 17/25 = 68% chance of drawing a playable or critical card
  * Cons
    * 14.3% chance of losing the game 
  
* Directly Clue 5 Option
  * Pros
    * Kimbi will now know about her 5
  * Cons
    * Kimbi is forced to discard, since she's now at 0 clues.
    * 56% chance that Kakashi will be forced to Skip Discard
    * Another way to look at it: Kimbi has a 56% chance to be in a situation to unlock herself with 1 clue

### Summary 
* Basically, it's better for Kakashi to take the 14.3% chance to effectively have a more smooth sailing game.  
* Where, if he did directly clue, the game would be a much tighter game. 
* With this Analysis we agree that you should perform a skip discard in this situation.
* Unfortunately, with this game the 14.3% chance happened where B4 was discarded, but we can agree that Kakashi did the correct move. 
* If you go into the replay and play out directly cluing the 5, you can see that Kakashi was forced to skip discard anyways.  

Take home points:
1. Do your best to avoid locking your partner in 2p.  Even to the point of taking the risk and skip discarding early.
2. If you are in the position of potentionally locking your partner, give them as much clues as possible to help them unlock themselves. 

<br/>

## Priority of which cards should play

![2020-09-30_08-14-15](https://github.com/Dr-Kakashi/hanabi/blob/master/images/2-player/2020-09-30_08-14-15.png)

* In this situation, which card should Kakashi get right now?  

## Priority during End Game

![2020-09-30_08-30-48](https://github.com/Dr-Kakashi/hanabi/blob/master/images/2-player/2020-09-30_08-30-48.png)

* In this situation, which card should Kimbi play now?

According to [Priority Exceptions #1](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#1-end-game): 
1) End-Game
   * Priority is generally "turned off" in the End-Game, because players often need to play specific cards.
   * With that said, Priority can still work if a player plays a card that would be really terrible for the team otherwise.

Basically, what we're asking here is would playing R5 be really terrible for the team or would playing i2 induce a priority on Kakashi to play i4 as i3? 

* If we look at the state of the board here, the only missing card is i3.  
* Currently, the team has 1 clue, so the team doesn't really need any more clues for the game
* If Kimbi plays the R5 and draws i3, she barely will be able to play the entire suit
* If Kimbi plays R5 and doesn't draw i3, then if Kakashi draws i3, the game is lost as i5 won't be able to play.
* Another way to look at it is, Kimbi needs to start end game because she holds the i5.  

* If Kimbi plays i2, then we can see that even though Kakashi draws i3, the max score can still be achieved, if i3 is not bottom decked.
* The reason for this is because the cards are now evenly distributed, Kimbi can take a turn off to clue Kakashi, and Kimbi will still initiate end game.  

* Thus, if we assume i3 is not bottom decked, the best chance to win is to have Kimbi play i2, which would not induce priority as playing R5 is terrible for the team.  
