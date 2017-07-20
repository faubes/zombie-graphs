# zombie-graphs

Some code relating to vertex pursuit games.  Uses the JUNG library to model the graphs

These efforts are inspired by the article A deterministic version of the game of zombies and survivors by S.L. Fitzpatrick a , J. Howell b , M.E. Messinger c, ∗ , D.A. Pike d, Discrete Applied Mathematics 213 (2016) 1-12.

As well as the book by Cops and Robbers on graphs by Bonato and Nowakowski.


Contents:

GraphGenerator contains a few methods to create graphs.

CopsAndRobbersBasic and ZombiesAndSurvivorsBasic allow you to play the games with a text interface. It's kind of hard to play these games using only their numerical representations but it works.

ZombiesAndSurvivorsGame is an attempt to add a GUI using JUNG's graph drawing capabilities. I decided it required refactoring and some sort oF MVC pattern to make it nice and so gave up on that. For now, it allows you to draw a given graph in a bare applet.

The ZombiesAndSurvivorsUtils class contains Floyd Warshall and other algorithms for trying to solve the game, and checking for valid moves.
