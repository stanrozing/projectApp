# projectproposal

Stan Rozing 11268808

## Problem Statement
Er zijn erg veel voetballiefhebbers in de wereld en ook erg veel apps die iets met voetbal te maken hebben, zoals apps die bijvoorbeeld standen weergeven.
Ik kan echter geen app vinden die naast standen ook nog informatie over teams weergeeft, wat erg frustrerend kan zijn voor mensen die naast de stand ook iets over een team en zijn spelers te weten willen komen.

## Solution
An app which shows standings of big football competitions, but also info about teams and players in that competition.
The visual sketch of the app is in another file.

Main Features:
* Show standings of competitions
* Show info of a team
* Show info of a player

Those are the minimum things I want to implement, other things I want to do (but maybe more difficult) are:
* Show fixtures of competitions
* Show Live Scores of matches that are going on right now

## Prerequisities 
The Json api's (data sources) I intent to use are:
* https://apifootball.com/ for live scores
* http://api.football-data.org/documentation for standings, fixtures and info about playes/teams

External Components:
* None yet

Another app which displays football standings is called 'Football Standings' which gives a list of competions and when clicked on, you can see the standing of that competion, however, you can't do anything more than that, which is what I miss in that app.

The hardest parts will be combining both Json api's, maybe they won't work well together and I will need to fix this. Another hard thing might be making the app entirely crash free, like for example when the app is retrieving data and people start clicking on things.
