How to play:

* Normal minesweeper: that's just normal minesweeper

* Independent binomial: instead of reporting the total number of mines in the eight adjacent squares,
each square takes eight samples its eight neighbours, with replacement, and reports the number
that are mines. This is pretty hard and difficult. 

* Global binomial: just like independent binomial, but all squares sample their neighbours in the
same way. For instance, each square might return 3x the number of mines to its left + 1x the number of 
mines to its bottom left + 1x the mines directly below + 2x the number of mines to its right + 1x the
number of mines to its top right. I prefer this to normal minesweeper, although there is a bit more 
luck involved. 

For a more verbose yarn about the game, see: https://posev.substack.com/p/binomial-minesweeper
The Python version is by me, the HTML version is translated by Claude
