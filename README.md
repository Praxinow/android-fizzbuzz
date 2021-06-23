# fizzbuzz

Fizz buzz is a group word game for children to teach them about division. Players take turns to count incrementally, replacing any number divisible by three with the word "fizz", and any number divisible by five with the word "buzz". However, any number divisible by three is replaced by the word fizz and any number divisible by five by the word buzz. Numbers divisible by 15 become fizz buzz. A player who hesitates or makes a mistake is eliminated from the game.


# Requirement

In this app, there will be a screen where a random number will appear and player will have 10 seconds to determine whether it's fizz / buzz / fizzbuzz. If number is neither fizz, nor buzz, pass the number.
Screen will have:
1. 1 number which will keep changing.
2. 4 buttons namely fizz, buzz, fizzbuzz and pass
3. 1 10 sec timer.
4. A scoreboard.

score calculation:
fizz : 5 points
buzz : 5 points
fizzbuzz : 10 points
pass : 2 points

wrong answer score: what answer you'll give as wrong, it's positive score will be deducted from final score
for example:
if correct answer was fizz, but user answered as fizzbuzz, 10 points will be deducted.
similarly if correct answer is fizzbuzz and user pressed pass, 2 points will be deducted.

# UX

Feel free to do experiments

# Concepts to be learned

- MVVM
- Live Data
- Room DB
- Unit testing
- Fragment and Fragment Navigation

