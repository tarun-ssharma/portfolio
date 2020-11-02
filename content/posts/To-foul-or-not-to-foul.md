---
title: "To Foul or Not to Foul"
date: 2020-10-01T18:03:59+05:30
draft: true
weight: 1
---
The NBA playoffs are going on. The bubble has given us many opportunities of witnessing close games.
The most recent one being the Game 2 of western conference finals. Lakers were trailing by one point, with 2.1 seconds left on the shot clock.
Anthony Davis gets an inbounds pass from Rondo, hits an unbelievable three, and the rest is history.
Since star players are bound to get the final shot more often than not, Rondo had a choice to make: pass to LeBron for a contested two or pass to Davis for an open three.
He fortunately saw AD was open and passed to him for the 3-point shot. After the game, Lebron James said “It’s not about making a shot. It’s about having a belief of just taking it and living with the result."
There are often situations like this, late in games, when a team is down by 1 or 2 points on the last possession, and they have a choice to make.
Either go for a two, or a three. When down by one, the obvious choice is to go for a two (Unless you are Damian Lillard).
So lets try to analyze the situation when a team is down by 2.
Here, the team A can either go for a 2 and hope to win in overtime, or look for a three pointer and hopefully a win.
Simultaneously, the opponent team has three choices: to defend the two, to defend the three, and to foul a player.
Rather simplistic representation for ease of analysis.

Displaying all the choices in a matrix form, we get:

|         | Defend 2 | Defend 3 | Foul |
|---------|----------|----------|------|
| Shoot 2 |          |          |      |
| Shoot 3 |          |          |      | 

Strategy for team A can be to shoot 2 with p%. In such a case, expected payoff for team B when defending a 2 is
p*. Also, payoff for defending a 3, it is. For fouling, it is 
Strategy for team B can be to defend 2 with p% and 3 with q%. In such a case, expected payoff for team A when going for a 2 is:
p*

Conclusion:

What's next:
https://fansided.com/2018/07/31/nylon-calculus-game-theory-deep-3/

weil: https://www.slideshare.net/sloansportsconf/the-importance-of-being-open-what-player-tracking-data-can-say-about-nba-field-goal-shooting








Inspired by: https://mindyourdecisions.com/blog/2012/06/19/game-theory-applied-to-basketball-by-shawn-ruminski/

