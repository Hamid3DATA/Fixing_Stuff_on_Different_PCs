## This is just me working on my projects from different PCs, trying to fix the issues i find along.

<br />

### BlackJack
#### [!NOTE]
BlackJack Problem 1 -*Fixed*-
#### Problem 1
When the dealer gets an Ace card, and his points are over 21 the Ace for some reason does not count as 1 point, instead it continues to count as 11 points, which does not make sense. Since it works perfectly fine when it's the same situation but with the player instead.

<br />

### Counting
#### Problem 1
I need to find a better solution for resizing font depending on the number that is being displayed. Due to the fact that right now i have to manually type what size the font has to be in different scenarios. I would like it to be automized. Say, the width(diameter) of the "display" is 1000px then as soon as the string's length/width exceedes that amount the font should shrink till it is less than 1000px in length/width so that it stays inside the so called "display".

<br />

### TicTacToe
#### Problem 1
You can put your X's as fast as you want. The animation of O's being put down is around 0.5s(i don't remember tbh) and its placement is random. Since X does not have to wait for the O's animation to finish it seems as if one can put down X's faster than the O's can. Which is not really true since the O is there instantly, it just doesn't appear due to the animation. I could turn off the "animation" for O's, but it would make it look weird while playing. The better option is to not allow the player to put down X's until the O's animation is done. I am not entirely sure as to how, but maybe by adding a delay or something.

#### Problem 2
Not really a problem per say. I started to make an "unfair" opponent in TicTacToe(app2.js), but stopped in the beginning. I should finish it. The premise(idea) was to counter all possible combinations that there is in TicTacToe, so that it would be impossible to win.
