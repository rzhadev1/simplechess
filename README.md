# simplechess.js 
Play against me [here!](https://rzhadev1.github.io/simplechess/)
# Description
A simple implementation of a minimax algorithm and basic static evaluation function, done in the browser and on discord that I wrote in 2019. Currently only supports a 3 move look ahead, which usually results in 15-20 second calculation time, depending on board state. Play against the bot as if it was bullet chess (or else it might be too easy).

# TODO 
- Because browser speed is limited and the algorithm is quite naive, the bot is not very good. Performance tradeoff between 3-4 move look ahead is too steep (4 move look ahead takes roughly 3 times as long as 3 move, thus I chose to stick with 3 moves). Could optimize the algorithm or implement short circuiting to cut off move calculation at 30 seconds and just use iterative deepening. 
- Improve GUI 
- Make the bot actually good (lots of ideas, monte carlo, neural nets etc..)
