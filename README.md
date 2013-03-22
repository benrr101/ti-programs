# TI-85 Programs
## Overview
This is a repository for the all the progams I wrote on my TI-85 back when I was in high school. These were written before I had even learned to code, so they are incredibly inefficient -- even for such a low-performance architecture.

## Notes on the Code
* There was a bug/feature that made closing parenthesis (when not ambiguous `Outpt(1,1,"qqq"` vs `Outpt(X(1,2),2,"qqq"`) totally optional. This may have increased the compile time, but it was a trade off to trim a few bytes off the application. Since I used this technique in my code, the files don't have closing parenthesis (unless it was required)
* There are no comments in the code. I forget if there was a way to write comments, but it would've bloated the code.
* I don't think that indentation is valid, but I added it just to make it slightly more readable and so I could see if I had actually closed off all the Ifs/Fors/Repeats
* This code is specific to the TI-85. It's old. It's better. Deal with it. 

## BATTSHP
This is a battleship game. It stores four HUGE matricies that take up a ton of memory. It's a good idea to delete these after the game is finished. The game is two player, not single player.

## BLKJK
This is a black jack game. It was the first successful game I ever wrote. Looking back, I realize it's probably the worst code I've ever written, and honestly, I don't know how it even ran. The `goto`s and the horrendous inefficiency in picking the cards. Really, you shouldn't look at this code.