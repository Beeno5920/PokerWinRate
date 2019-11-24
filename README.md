# PokerWinRate
This is the final project from the course "Introduction to programming in C" provided by Duke University

The programe takes a file, which contains the informations of the cards in each hand, as an input and calculates the win rate of each hand base on the ties of the hands (say "flush", "straight", "two pairs" ... etc). The win rate is calculated by simulating different possible outcomes in a game 10,000 times, count the numbers of games of each player won in 10,000 games then divide it by 10,000 to get the percentage.

Each card is represented as the format "(suit)(value)", for example 's1' is the ACE of SPADES.
Note that for suits, 's' means SPADE, 'h' means HEART, 'd' means DIAMONDS, 'c' means CLUB and '?' means unknown; for values, '0' means 10, 'j' means JACK, 'q' means QUEEN and 'k' means KING.

### Example
![example](https://github.com/Beeno5920/PokerWinRate/blob/master/example.png)
