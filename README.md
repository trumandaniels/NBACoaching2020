# NBA Analytics: Quantifying NBA Coaching Impact 

### Evaluating NBA coaches is hard. 

During the 2015-2016 season, GSW coach Steve Kerr was recovering from back surgery so assistant coach Luke Walton took over head coaching duties and lead the Warriors to a blazing 39-4 start.

The next year Walton took the head coaching job of the Lakers, leading the team to a record of 26-56. What happened? Walton's coaching didn't drasticly change. 

Obviously, what changed were the rosters. The Warriors had four likely Hall of Famers, and 3 of them in the conversation of the best shooters of all time. The Lakers on the other hand--a young, rebuilding team with a handful of past-their-prime veterans--didn't stand a chance vs most teams. 

Distinguishing the difference between is not easy. The only stats we track about coaches is how old they are and what their win-loss record is; the Luke Walton anecdote shows how misleading it can be to only look at wins and losses. Box scores don't keep track of how loud the coach is, or the timeliness of his or her time outs.  

Coaches do many things, some of which are intangible. They lead the locker room and keep the team happy and cohesive: basketball is a team sport after all. Coaches also help develop players' skills like ball handling and shooting. They also have more directly on-court impacts because they control things like substitutions, lineups, and matchups. They can use their power to keep players in check: substitutions give chuckers a consience and encourage scorers to hustle on defence. Coaches also design the gameplan, scheme, and plays that put players in the best possible positions to score.

#### This project is an attempt to quantify some aspects of scheme and compare coaches' ability to get players high-quality shots. 

There are two factors that determine which team wins and which team loses. These are:
1. the team with more possessions
2. the team that converts possessions into points more effectively

The former is difficult to parse. When a player turns the ball over, is that his fault or the coaches fault? When a player steals the ball is that because the coach created a brilliant defensive gameplan or because the player saw the play developing and jumped a passing lane? I want to look into this more, maybe by comparing the consistency of certain team statistics from year-to-year (and might . But for now I'm going to focus on deciphering the coaches impact on the latter. 

At least intuitively, coaches should have significant influence over shot selection, both by getting guys open with well designed plays and by keeping rogue shooters in check. If we remove individual player talent at converting posessions (making shots) and just look at the opportunities it is a way to measure coaching value. These same arguments also apply to the defensive side of coaching, good coaches prevent opposing teams from getting easy looks.

So what is a "good shot" exactly?

4 shot-quality factors there are statistics for:
1. Distance to nearest defender
2. Place on the floor (i.e. by the basket vs midrange vs corner 3 vs non corner 3s)
3. Catch-and-shoot vs off-the-dribble
4. Time left on the shot clock


#### Mike Dantoni and the Seven Seconds or Less Suns:

![](ShotClockvsScoringEfficency.png)
![](QuantifyingNBACoachingShotClockManagement.png)
