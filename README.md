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

## BLKJK2
This is the second iteration of my black jack game. This was written in my junior year of high school mostly during study halls. By the time I finished it, I was quite proud of myself for having written much more concise code for the game. In particular, I revised the logic for generating cards to eliminate the god-awful If-Then chains. All in all, I reduced the size of the game from 3218 bytes in the first version to 1739 bytes in the second version. Looking back, I still see places where I could have improved the code, but it was pretty good having never formally learned coding. I also added comments to this file so it would be more understandable.

One other note: neither BLKJK or BLKJK2 implement actual card decks. Cards are generated at random and are not selected from a real deck. It is, therefore, impossible to card count and cheat these games. It is also, possible to have more than 52 cards in your hand. This leads to hilarious situations where you bust by 800 points.