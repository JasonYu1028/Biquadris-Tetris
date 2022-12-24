# Biquadris-Tetris-
The Game of Biquadris is a special variation of Tetris that is not real-time, giving players as much time as they need to choose where to place their blocks.

Two boards, each 11 columns wide and 15 "effective" rows high, make up a Biquadris game. The term "effective" refers to the three additional rows that have been set aside for the ease of rotating blocks but are not included as the effective rows used to arrange blocks for scoring. By entering certain commands that the command interpreter provides, players will take turns dropping blocks, one at a time, to play the game. When a player places a block on the board, his/her turn is over (except for special actions like the bonus for clearing two or more rows of blocks simultaneously, which will have an adverse effect on the opponent's game). The block that the opposing player will have to play following the player's turn is already at the top of the opposing player's board (and if it doesn't fit), then the opposing player loses.

The implementation of this project maximizes and structures around the benefits of object-oriented programming design. To separate and unite the numerous sorts of items in the game, classes have been introduced (i.e. level, categories of blocks, etc). More precisely, the observer software design pattern is created to see the boards of two players and model the changes taking place to them in order to accept and reflect changes in a clean and flexible fashion. Utilizing the factory software design pattern allows for the union of many types of building pieces, which provides subclasses with the responsibility of creating instances of object classes.

Due to policy 71 at the University of Waterloo, I'm not permitted to upload the whole codes in opence source, but you could find my design and documentation for an overview and check for details in words.

You may want to find a simple demo of playing this game here (there are more functionalities than what it shows):
https://drive.google.com/file/d/1nuSFI78-D6A9f41jYt0DZvNV72uDa-MD/view?usp=share_link
