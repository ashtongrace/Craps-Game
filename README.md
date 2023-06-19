# Craps-Game
The purpose of this project was to simulate a digital version of the gambling game Craps using both a graphical user interface, which was implemented using SceneBuilder, and the programming language Java. This project was developed in 2020 with two others, who will go unnamed as I have not asked whether they'd like to preserve anonymity, and myself.

The zip file has been included in this repository in order to ensure easy download.

Craps Rules

Player Goal: To bankrupt the CPU by taking all it's money.

How to play:

You take money from the CPU by betting money then winning the round.

1. You win a round on the first die roll by winning a 7 or 11, then rolling stops (move to part 3).
   You lose on the first dice roll by rolling a 2, 3, or 12, then rolling stops (move to part 3).
   If you roll anything else you roll again (move to part 2).

2. On other rolls you try to get the same value you rolled on the first roll.
   If you roll the value rolled on the first roll you win and rolling stops(move to part 3).
   If you roll a 7 you lose and rolling stops (move to part 3).
   If you roll anything else you roll again (part 2 again).

3. One you have won or lost, pay out gets calculated automatically.
   If you won, your money goes up and the CPU's money goes down by the betting amount.
   If you lost, your money goes down and the CPU's money goes up by the betting amount.
   
   PASS vs NO PASS
   - if you bet pass, you are betting you will the turn, and betting is normal
   - if you bet no pass, you are betting you will lose the turn, so you gain money by losing,
   and lose money by winning.

Step by Step:

Before Rolling - Bet money on the round (must not be negative or more money than you have)
Bet pass if you think you are going to win the round
Bet no pass if you thing you will lose

Roll 1 - Click roll
  If you get a 7 or 11, you win. You gain money if you bet pass.
  If you get a 2, 3, or 12, you lose. You lose money if you bet pass.
  Any other value goes to Roll 2+.

Roll 2+ - Click roll
  If you get the same value rolled in roll 1, you win. You gain money if you bet pass.
  If you get a 7, you lose. You lose money if you bet pass.
  If you get any other value, begin roll 2+ once more.


