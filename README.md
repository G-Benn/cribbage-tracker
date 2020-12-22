# cribbage-tracker

## What is this?
This is intended to be a tool used to assist in the tracking of the results of games of [Cribbage](https://en.wikipedia.org/wiki/Cribbage).
- Tracks the hands played and scores via images
- Tracks cards played most/least often and the end results of the game
- Stores those results in an analysis-capable format
- Once enough results have been gathered, does analysis on the results
- Does all the above in a repeatable, scripted manner (though initial testing is done in jupyter)
- Uses containers / free AWS/Azure resources for any real-time components


## Technical pieces required
- [ ] Card image recognization. This will allow the program to determine the cards in the current hand.
- [ ] Hand-divider image recognization. This will allow the program to divide up each set of cards into the relevant hands (dealer, opponent, crib, starter).
- [ ] Hand scoring system that calculates the points that each hand gets.
- [ ] Rule selector. There are a number of variatians of Cribbage scoring systems, so the ability to add or remove rules is important. Possibilities include:
  - [ ] Max score
  - [ ] Skunking
  - [ ] Tournament match-based rules
  - [ ] Jack of same suite
  - [ ] dealer point advantages
  - [ ] etc
- [ ] Hand-based point tracking system, including winner notification
- [ ] Hand-based hand/card tracking system
- [ ] External factor tracking (dealer, etc)
- [ ] Pegging score / trick tracking.
- [ ] After-the-fact / batch scoring mechanism for a series of pictures 
- [ ] Real-time scoring / tracking system
- [ ] Match-based overall winner(s)
- [ ] Analysis of various factors:
  - [ ] Cards kept in-hand most/least often
  - [ ] Cards thrown out most often (and if they're differnet for dealer / crib owner)
  - [ ] Pegging score / trick analysis
  - [ ] Scores that show up most often (distribution by dealer)
  - [ ] Human-based analysis (how does person A differ from person B, etc)
  - [ ] Bot-based analysis (would require getting the system to work with cribbage bots online)
  - [ ] Etc
- [ ] License, publish, finalize etc
- [ ] Train Cribbage-playing bot?
