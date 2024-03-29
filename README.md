# "Evolution Game" for NAO robot [v.1.2]
*Attention: this project is only available in German!*


### How the Game works

This game serves to loosen up the lesson a bit. It can be done with any number of students. 
The students spread out loosely in the room. The robot NAO then briefly explains the game.
After that, the exercise starts.
The aim is to win 3 times and thus reach the highest level. Whoever has achieved this 
sits down and waits until the others have also finished
Meanwhile, NAO stands in front of the class waiting for someone to play with him.
To do this, tap one of NAO's sensors. Then he asks the player to choose one of the three cards infront of him.<br>
On each card is a NAO-mark. These stand for rock, paper or scissors.
The player shows the chosen card to the robot. 
Internally, NAO has also chosen one of the three variants.
It tells the player who has won. Then the robot waits for the next player.

### What do you need?

In addition to this program on your Nao, you also need 3 cards.
They must show your chosen NAO-marks and what the card represents (rock, paper or scissors).
If you don't want to create this yourself, you can use the "cards" image in the files and print it out.

### Plans of further development:

Sometime in the future, it is planned that Nao will recognize the player's hand position
with his camera in real time, making the gameplay more natural.

### Choregraphe screenshot:
![evolution_game_logic](https://user-images.githubusercontent.com/68842909/223420713-a3903347-ed9e-489d-8cf7-23e6fdb67b7b.PNG)

---

### Changelog

v.1.2 <br>
add: new animation (3) - animations for "rock" , "paper" and "scissors"
fixed: bug in logic - you will win now, when Nao picked scissors against rock

v.1.1 <br>
Fix: the "hand animation" - animation causes an error and crashes the programm
