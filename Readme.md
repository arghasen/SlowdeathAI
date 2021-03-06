# Beginning of the Slowdeath AI
From BearTheGreat tutorial
1. Defconst Rules.  Constants must be defined before they can be used in rules or else they will generate an error message, so they really need to be at the top of the file.
2. Starting Strategic Numbers.  Strategic numbers really can go anywhere in the file, but I tend to put the ones defined early in the game at this location in the list.
3. Market Rules.  Put them here so you can buy or sell items as needed for research items.
4. Economy Rules (i.e. - Gatherer Rules)  They could really go anywhere.  I just choose to put them here.
5. Research Rules.  I think it is very important to put these before the training rules so you don't end up with lots of un-upgraded units.
6. Escrow Rules - It is best to place these after the research rules because escrow is usually held for research items.  It is nice to know when it can be released.
7. Build Rules - I find it very necessary to build before training so that I will have the resources to build.
8. Training Rules.  I usually train civilian units first to keep the economy humming.
9. Taunting Rules. 
10. Resignation Rules.  These really could go anywhere in the file.
11. Town-Size Rules.  These could also go anywhere.
12. Defend Rules.  These could also go anywhere.
13. Counter-Attack Rules.  These could also go anywhere.
14. Attack Rules.  These could also go anywhere.

# Results

## v0.1
reached enough resources to feudal in 14 mins. Failed to advance due to not building 2 feudal age buildings
## v0.2
reached feudal in 11 and 21 mins respectively with 19 and 30 vills. AI1 never took wood and got housed at 20 pop to advance. AI2 waited till reaching 30 vills before advancing. Scores equal after 21 mins.
## v0.3
Can beat Easiest AI under 40 mins.
## v0.4
Beat Easiest AI in 35 minutes with Burmese in Castle Age(+2 attack long swordsman)
### Standard
Advanced Feudal with 28 vills in 15.58 sec(Malay 80% faster advance time). Scores equal at this time. 
Hunting far away in dark age after berries. Lost vill to wolf just reaching feudal.
72 pop(47 vil) castle age in 31 min. Could not attack walls. 44 min Imperial. Won in 1 hr after enemy chopped wood to give way to my army.
## v0.4.1
### Standard Original AI
25 vill with loom with Byzantines in 15.38s. 43 vill castle age in 32 min. Managed imperial click up as soon as buildings were done. Won in 33.38 min. 
### Standard HD AI
Lost heavily in 1 hour. 52 k/150 d. Reached imperial age but got destroyed by knights.
## v0.4.4
Lost heavily in 1 hour. 103k/ 158 d. Reached Imperial age in 41 mins. Got destroyed by crossbows.
## v0.4.5
No attack till well past imperial. Min 80 size attack with retreat. Won in 2hrs 25 mins.
## v0.4.7
Lost in 31 mins vs Franks against a Knight rush.
## v0.4.8
Lost in 38 mins vs Slavs against a Knight rush. Managed to defend initial rush but lost in 2nd wave.
## v0.5
Was losing after 31 mins vs Slavs as Saracens against Knight rush. Tested more trading to win in 1:12 min.

## v0.5.1
Won in 1 hour vs Slavs. Small Knight rush but no attack after that.
## v0.5.2 
Lost in 42 min to 2nd wave of knights
## v0.6.1
Lost in 50 min to 2nd wave of knights after trading help.
## v0.6.3 
Won in 1:03 min. Delayed 2nd rush of Knights.
## v0.7.1
Lost in 39 mins to 2nd wave after trading help.
## v0.7.3
Won in 1 hour 2 min. Normal 2nd wave
## v0.7.4
Won in 59.11 min. Normal 2nd wave.

# Update 27th Feb 2020

I was away from scripting AI for over an year and now look to improve this further. First a few games will be played for me to remember the state the AI was when I stopped.

The first 3 games were abandoned as the settings were incorrect.

Game 1:
Lost in 40 mins to Knight rush, AI ran into wood troubles and could never recover. It went to castle at 30 mins with 40 vills.

Game 2:
Lost in 45 mins to Long Swordman rush by Goths. AI did 27 min castle with 35 pop.

Game 3:
Lost in 51 mins to a late attack by Swordsmen and Crossbows. Managed to reach imperial age with 4 tc boom.

Game 4:
Lost in 1hr to 2nd wave of Knights, managed to reach Imp but was destryed by then.

Looks like the results in the few games before I stopped dev were an abberation, the AI is losing heavily to Standard HD AI.

## v0.8
Changed the build order in dark age

Lost in 1hr 35 mins to Japanese Arbalests and Trebuchets. There was no rush in this game.

## v0.8.1
reduce max vills in dark to 25, max in feudal to 30, change wheelborough research and add capped ram, seige ram research.

Lost heavily in 30 mins.

## v0.8.2
Start training military when advancing to castle, delay the barracks if already in feudal.

Lost in 50 mins, survived 1st wave of knights, lost to 2nd wave.

## v0.8.3 
change the order of researches a bit, make the boom more like a 3tc boom then a 4tc boom. Train upto 20 military in castle age.

Lost in 40 mins, had a bad wood lumbercamp at the start and never recovered in wood situation.

## v0.8.4
Build second barrack if under attack, build castle a bit earlier, delay tc, university and monastry when under attack.

Lost under 30 mins with bad lumbercamp again.

## v0.8.5
Fixed the lumber camp placement timings to be in seconds, I put them thinking in minutes and it was messing up

Game 1: Won in 1 hr 17 mins against a slightly delayed Knight rush.

Game 2: Lucky win in 1hr 24 mins as his archers ran into my castles.

## v0.9
Added skirmisher defense vs archers.

Game 1: Won in 1 hr 21 mins after defending an archer rush.

Game 2: Won in 1 hr 53 mins against flush archer rush. 

## v0.9.1
Small bugfix to research

Game 1: Won in 1 hr against archer rush.(Britons)

Game 2: Won in 1hr 15 mins. Not much attack from opponent(franks)

Game 3: **MODERATE Original AI** Won in 1 hr 31 mins. No attack by the AI


# Hard Original AI battles

We skipped looking to fight the Moderate AI as the timings of playing vs AI on any other difficulty other than Hard is incorrect. So we will go on to fight the Original AI in Hard in this section. We will also start structuring our AI a bit better.

Game 1: Lost vs Franks 1 hr 20 mins. 

Game 2: Lost vs Franks 1 hr 30 mins.(We made more vills in dark and feudal age)

## v0.9.2
Create One monk for relics, train skrimishers in imperial as well if archers are there. Research Wheelborrow a bit earlier.

Won in 1hr 40 mins. (Teutons mirror )

## v0.9.3

Work in Progress