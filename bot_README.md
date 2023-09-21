
# BaksetBot Guide

## Help

If you ever forget the formatting for the query commands, try typing help after the command. 
Doing so will return the command format.

**Example**
```
$find_clip help

$find_clip [team] [Year-Month-Day] [Quarter] [Minutes:Seconds]
Alternatively, if the game was in the current season
$find_clip [team] [Month/Day] [Quarter] [Minutes:Seconds]
```

## Commands

_Deluxe Only_ means you can only use the command in the deluxe channel
- [$playmake](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#playmake)
- [$shotmap](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#shotmap)
- [$shotchange](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#shotchange)
- [$shotchange2](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#shotchange)
- [$shotdefense](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#shotchange)
- [$teamshots](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#shotchange)
- [$teamshotd](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#teamshotd)
- [$flow](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#flow)
- [$rotation](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#rotation)
- [$shift](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#shift)
- [$oldshift](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#oldshift)
- [$teamleader](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#teamleader)
- [$teamthrees](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#teamthrees)
- [$threepoint](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#threepoint)
- [$picks](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#picks)
- [$price](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#price)
- [$rim](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#rim)
- [$playleader](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#playleader)
- [$playtype](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#playtype)
- [$playstyle](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#playstyle)
- [$teambron](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#teambron)
- [$teambrond](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#teambrond)
- [$teamplay](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#teamplay)
- [$tracking](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#tracking)
- [$player_card](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#player_card)
- [$team_card](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#team_card)
- [$find_clip](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#find_clip)
- [$playerclips](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#playerclips)
- [$playerscreen](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#playerscreen)
- [$playerboard](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#playerboard)
- [$next_games](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#next_games)
- [$scoreboards](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#scoreboards)
- [$season](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#season)
- [$wowy](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#wowy)
- [$teamseason](https://github.com/gabriel1200/Bot_Guide/blob/main/bot_README.md#teamseason)
## $playmake
**What it does**

Visualizes a players performance in various creation/playmaking proxies compared to the rest of the league. Available for the regular season and postseason.

Span: 2014 - Present

**How to use it**

$playmake [firstname] [lastname] [season] 

or

$playmake firstname] [lastname] [start_season] [end_season]

or

$playmake [firstname] [lastname] [season] [ps]

**Example**
```
$playmake lebron james 2015 2017 ps

```
![playmake](https://media.discordapp.net/attachments/1132368217436864582/1145944467883442197/playmakelebron_james.jpg?width=1094&height=1094)

## $shotmap
**What it does**

Creates a Goldsberry style shotmap of a player season. 

Span: 1998 - Present


**How to use it**

$[firstname] [lastname] [season]

or

$[firstname] [lastname] [season] [endseason]

or

$firstname] [lastname] [season] ps

or

$[firstname] [lastname] [season] [endseason]
**Example**
```
$shotmap tracy mcgrady 2004

```
![ShotMap](https://media.discordapp.net/attachments/1088122768672948335/1108613133792186438/Tracy_McGrady_2003-04.png?width=1285&height=1104)

## $shotchange
**What it does**

Creates two Goldsberry style shotmaps. One for when the selected player is on the floor, and the other for when they are off it. 

Span: 1998 - Present


**How to use it**

$[firstname] [lastname] [season]

or

$firstname] [lastname] [season] ps

**Example**
```
$shotchange stephen curry 2021


```



![Shotmap](https://media.discordapp.net/attachments/1045134231707336764/1108450359543861288/Stephen_Curry_On__2020-21.png?width=1285&height=1104)


![Shotmap](https://media.discordapp.net/attachments/1045134231707336764/1108450359887806514/Stephen_Curry_Off__2020-21.png?width=1285&height=1104)

## $shotchange2
**What it does**

Creates two Goldsberry-style shot maps. One for when the selected player is on the floor, and the other for when they are off it. Unlike the base shotchange command, shots by the selected player are excluded

Span: 1998 - Present


**How to use it**

$[firstname] [lastname] [season]

or

$firstname] [lastname] [season] ps

**Example**
```
$shotchange2 stephen curry 2021


```



![Shotmap](https://media.discordapp.net/attachments/1042176198832308387/1129115408394362971/Stephen_Curry_On__2020-21_RS_Player_Excluded.png?width=1292&height=1145)


![Shotmap](https://media.discordapp.net/attachments/1042176198832308387/1129115408654405701/Stephen_Curry_Off__2020-21_RS.png?width=1334&height=1145)

## $shotdefense
**What it does**

Creates two Goldsberry style shotmaps. One showing the _opponents_ shotmap when the selected player is on the floor, and the other showing the opponents shooting when they're off the floor

Span: 1998 - Present


**How to use it**

$firstname lastname season

or

$firstname lastname season ps[optional]

**Example**
```
$shotdefense draymond green 2017 ps


```



![Shotmap](https://media.discordapp.net/attachments/1045134231707336764/1108477121174704308/Draymond_Green_On_Defense_2016-17.png?width=1285&height=1104)


![Shotmap](https://media.discordapp.net/attachments/1045134231707336764/1108477121757720626/Draymond_Green_Off_Defense_2016-17.png?width=1285&height=1104)


## $teamshots
**What it does**

Creates a Goldsberry style shotmap of a team season. 

Span: 1998 - Present


**How to use it**

$teamshots [firstname] [lastname] [season]

or

$teamshots [firstname] [lastname] [season] ps

**Example**
```
$teamshots den 2023

```


![Shotmap](https://media.discordapp.net/attachments/1045134231707336764/1106026282153680906/Denver_Nuggets_2022-23_RS.png?width=1333&height=1145)


## $teamshotd
**What it does**

Creates a Goldsberry style shotmap of shots _conceded_ by a team in a season.

Span: 1998 - Present


**How to use it**

$teamshotd [firstname] [lastname] [season]

or

$teamshotd [firstname] [lastname] [season] ps

**Example**
```
$teamshotd lal 2023 ps

```


![Shotmap](https://media.discordapp.net/attachments/617877313534558208/1110049157395263560/Los_Angeles_Lakers_2022-23_PS.png?width=1285&height=1104)
## $flow
**What it does**

Creates a network graphic that visualizes the frequency with which players made & received passes from teammates. 

Span: 2014 - Present


**How to use it**

$flow [team] [season] ps

**Example**
```
$flow dal 2023

```


![Flow](https://media.discordapp.net/attachments/1042176198832308387/1116166661028974592/chord.png?width=992&height=1072)

## $rotation
**What it does**

Visualizes a teams rotation pattern & plus minus for the selected game.


**How to use it**

$rotation team year-month-day

**Example**
```
$rotation mia 2023-06-01

```


![Rotation](https://media.discordapp.net/attachments/1045134231707336764/1114397859425566761/fig1.png?width=1715&height=1072)


## $shift

**What it does**

Shows a players output accross various dimensions with and without another player. [PBP stats.](http://www.pbpstats.com/wowy-combos/nba)
Users select two players on a team, and chose betwee regular season and post season data. Currently, this version does not work for players who were traded mid season. Use the oldshift command for such instances.

Span: 2001 - Present

**How to use it**

$shift player1_lastname player2_lastname season(s) ps-optional

**Examples**

```
$shift davis reaves 2023 ps

```
![Shift](https://media.discordapp.net/attachments/617877313534558208/1110319230596944012/fig1.png?width=1656&height=1104)

## $oldshift

**What it does**

Shows a players output with and without another player. [PBP stats.](http://www.pbpstats.com/wowy-combos/nba)

Shows a players output accross various dimensions with and without another player. [PBP stats.](http://www.pbpstats.com/wowy-combos/nba)
Users select two players, the season(s) they wish to include, and chose betwee regular season and post season data.  
Span: 2001 - Present

**How to use it**

$oldshift [team_acronym] firstname lastname first name lastname [season] ps-optional

**Examples**

```
$oldshift cle darius garland jarrett allen 2023

```
![OldShift](https://media.discordapp.net/attachments/1042176198832308387/1096940938523328612/fig1.png?width=1606&height=1070)
## $teamleader
**What it does**

Generates a scatterplot per synergy playtype for all teams. 
The xaxis showcases PPP for this action, the y axis showcases frequency. Can be used for the Regular Season & PostSeason.
The playtypes included are ['pr_ball','iso','tran','pr_roll','post','hand_off','oreb','cut','off_screen','spot'].

Span: 2014 - Present

**How to use it**

$teamleader playtype year ps[optional]

**Example**

```
$teamleader iso 2023

```
![TeamLeader](https://media.discordapp.net/attachments/617877313534558208/1104188454373445672/fig1.png?width=1784&height=1070)

## $threepoint
**What it does**

Shows a players three point shooting percentage and frequency on wide open, open, and tightly contested shots accross the selected seasons.
Available for the Regular Season & PostSeason.

Span: 2014 - Present

**How to use it**

$threepoint [firstname] [lastname] [season] 

or

$threepoint firstname] [lastname] [start_season] [end_season]

or

$threepoint [firstname] [lastname] [season] [ps]

**Example**
```
$threepoint chris paul 2022 2023

```
![threepoint](https://media.discordapp.net/attachments/617888289801895966/1152352109648412803/threes.jpg?width=1645&height=1096)

## $teamthrees
**What it does**
Visualizes teams shooting on wide-open, open, and tightly contested shots relative to the rest of the league using Second Spectrum data

* 'tight' combines the tight and very tight categories on Second Spectrum into one category.

Span: 2014 - Present


**How to use it**

$teamthrees [teamacronym] [year]

or

$teamshots [firstname] [lastname] [season] ps

**Example**
```
$teamthrees den 2023 ps

```


![teamthrees](https://media.discordapp.net/attachments/1132368217436864582/1145944920792772639/DEN20232023True.png?width=1094&height=1094)


## $picks
**What it does**

Scrapes Sportrac to visualize the draft picks owned and owed by the selected team.

Span: N/A

**How to use it**

$picks team

**Example**

```
$picks okc

```
![Future Firsts](https://media.discordapp.net/attachments/1045134231707336764/1121977636344836106/0page.png?width=2036&height=1145)
![Future Seconds](https://media.discordapp.net/attachments/1045134231707336764/1121977641835180083/1page.png?width=2036&height=1145)

## $price
**What it does**

Displays a LEBRON-based estimate of a player's wins above contract per team for the regular season.

Wins Above Contract(WAC) =  WAR  -(Player Salary/Average Cost of a Win)

Span: 2010 - Present

**How to use it**

$price team year

**Example**

```
$price tor 2019

```
![Price](https://media.discordapp.net/attachments/617877313534558208/1154505049909772360/tor2019price.png?width=1600&height=1066)

## $rim
**What it does**

Generates a graph comparing a team's opponent rim frequency and efficiency with their defensive anchors on the floor. (Using NBA defensive dashboard
to establish cutoffs for qualifying players.)

Span: 2014 - Present

**How to use it**

$rim year ps[optional]

**Example**

```
$rim 2023

```
![Rim](https://media.discordapp.net/attachments/1045134231707336764/1108451023950975046/fig1.png?width=1471&height=1104)

## $playleader
**What it does**

Generates a scatterplot per synergy playtype for all players averaging 2+ possesions of that playtype per game. 
The xaxis showcases PPP for this action, the y axis showcases frequency. Can be used for the Regular Season & PostSeason.
The playtypes included are ['pr_ball','iso','tran','pr_roll','post','hand_off','oreb','cut','off_screen','spot'].

Span: 2014 - Present

**How to use it**

$playleader playtype year ps[optional]

**Example**

```
$playleader iso 2023

```
![Playleader](https://media.discordapp.net/attachments/617877313534558208/1104049949160767590/fig1.png?width=1784&height=1070)

## $playtype
**What it does**

Shares the PPP & Frequencies of a players playtypes, according to Synergy classification. 
Available for the Regular Season & PostSeason.

Span: 2014 - Present

**How to use it**

$playtype [firstname] [lastname] [season] 

or

$playtype firstname] [lastname] [start_season] [end_season]

or

$playtype [firstname] [lastname] [season] [ps]

**Example**
```
$playtype james harden 2019

$playtype james harden 2019 ps

$playtype james harden 2019 2020 ps

$playtype james harden 2019 2020

```
![Playtypes](https://media.discordapp.net/attachments/1045134231707336764/1095817225820192948/playtype.jpg?width=1832&height=1145)

## $playstyle
**What it does**

Shares the average PPP & Frequencies of a players playtypes according to the following combined categories. 

On Ball: Iso + PR Ball Hanlder + Post

Play Finishing: PR Roll Man + Spot Up+ Putbacks + Cuts

Off Motion : Hand off + Off Screen 

Transition

Available for the Regular Season & PostSeason.

Span: 2014 - Present

**How to use it**

$playstyle [firstname] [lastname] [season] 

or

$playstyle firstname] [lastname] [start_season] [end_season]

or

$playstyle [firstname] [lastname] [season] [ps]

**Example**
```
$playstyle josh hart 2023

```
![Playstyle](https://media.discordapp.net/attachments/1045134231707336764/1106025686558310491/playtype.jpg?width=1832&height=1145)
## $teambron
**What it does**

Shows a breakdown of a team's offensive personnel, using O-LEBRON as the y index and Bball-Index's Offensive Categories as the x-axis.
Span: 2010 - Present


**How to use it**

$teambron [team] [year]

**Example**
```
$teambron ind 2014

```
![Team O-BRON](https://media.discordapp.net/attachments/1132368217436864582/1140463969975418890/obronIND2014.png?width=1566&height=1095)

## $teambrond
**What it does**

Shows a breakdown of a team's defensive personnel, using D-LEBRON as the y index and Bball-Index's Defensive Role as the x-axis.
Span: 2014 - Present


**How to use it**

$teambrond [team] [year] [minutecutoff-optional]

**Example**
```
$teambrond dal 2022 200

```
![Team D-BRON](https://media.discordapp.net/attachments/1132368217436864582/1140463809019003040/obronDAL2022.png?width=1566&height=1095)

## $teamplay
**What it does**

Shares the PPP & Frequency of a team's play types, according to Synergy classification. 
Available for the Regular Season & PostSeason.

Span: 2014 - Present

**How to use it**

$teamplay [firstname] [lastname] [season] 

or

$teamplay firstname] [lastname] [start_season] [end_season]

or

$teamplay [firstname] [lastname] [season] [ps]

**Example**
```
$teamplay gsw 2015


```
![Team Playtypes](https://media.discordapp.net/attachments/617877313534558208/1135937332416086178/team_playtype.jpg?width=1754&height=1096)
## $tracking
**What it does**

Shares a player's scoring efficiency and volume relative to other players according to various second-spectrum play classifications.
Available for the Regular Season & post-season.

Span: 2014 - Present

**How to use it**

$tracking [firstname] [lastname] [season] 

or

$tracking firstname] [lastname] [start_season] [end_season]

or

$tracking [firstname] [lastname] [season] [ps]

**Example**
```
$tracking stephen curry 2017 2018

$tracking stephen curry 2017 2019 ps


```
![Playtypes](https://media.discordapp.net/attachments/1132368217436864582/1137064883821756497/playtype.jpg?width=1480&height=1096)

## $player_card
**What it does**

Displays a players metrics over multi year periods in percentile form . 

Span: 1955 - 2022 (Corresponds to the Thinking Basketball Historical Database)

**How to use it**

$[firstname] [lastname] [end year] [span]

**Example**
```
$player_card joel embiid 2022 3
```
![Player Card ](https://media.discordapp.net/attachments/1045134231707336764/1095815927599202364/fig1.png?width=1145&height=1145)
## $team_card
**What it does**

Displays a teams performance metrics over multi year periods in percentile form. 

Span: 1980 - 2022

**How to use it**

$[team_acronym] [end_year] [span]

**Example**
```
$team_card mil 2022 4
```
![Team Card](https://media.discordapp.net/attachments/1045134231707336764/1095816188023554148/fig1.png?width=1145&height=1145)
## $find_clip
**What it does**

Returns the possesion video(s) closest to the time stamp.

Span: 2015 - Present

**How to use it**

$find_clip [team] [Year-Month-Day] [Quarter] [Minutes:Seconds]

OR

$find_clip [team] [Month/Day] [Quarter] [Minutes:Seconds]

**Examples**
```
$find_clip den 2023-1-24 4 0:07

$find_clip DEN 12/28 4 0:07
```
https://videos.nba.com/nba/pbp/media/2022/12/28/0022200522/656/25b2f99d-d815-c9b0-efc6-06b5f55cf9c7_960x540.mp4

## $playerclips
**What it does**

Returns a description and(if available) video for all plays a player was recorded as being involved in.

Span: 2015 - Present

**How to use it**

$playerclips [team] [Year-Month-Day] [Quarter] player_lastname

$playerclips [team] [Month/Day] [Quarter] player_lastname (for the current season)

**Examples**
```
$playerclips MIA 2023-5-21 2 williams
```

## $playerscreen

_Deluxe Only_

**What it does**

Provides customized snapshot of a players current season from thinkingbasketball.net

Span: Current Season

**How to use it**

$playerscreen [first_name] [last_name] 

**Example**
```
$player_screen Malcolm Brogdon
```
![Player Screen](https://media.discordapp.net/attachments/638116254720327680/1095773509621387264/player_snip.jpg?width=1386&height=966)
## $playerboard

_Deluxe Only_

**What it does**

Displays the top 10 _s by the selected team statistic(ortg,drtg,etc) for the current season, taken from the Thinking Basketball Daily Leaderboard.

For metrics with two terms in the name, replace the space with an underscore. (ie 'passer rating' should be entered as 'passer_rating') 

Span: Current Season

**How to use it**

$playerboard [stat]

**Example**
```
$playerboard passer_rating

┌──────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┐
│      Player         Tm    MP    GP   BPM    OBPM   ScoreVal   PlayVal   Load   Pts 75   rTS%    Box Creation   Passer Rating │
├──────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┤
│    Trae Young       ATL   351   10   2.2    3.6      -0.8       2.4     59.9    27.5    -6.5        14.7            9.5      │
│   Nikola Jokic      DEN   346   11   7.7    4.7      1.6        2.3     48.6    24.2    11.0        13.1            9.4      │
│    Ben Simmons      BKN   231   8    3.1    -1.4     -1.6       0.5     24.7    7.3     -11.8       2.5             9.3      │
│   James Harden      PHI   331   9    5.6    3.8      0.2        2.4     51.7    23.0     2.3        15.7            9.2      │
│   Ousmane Dieng     OKC   135   9    -0.2   -1.6     -1.2       0.7     20.0    8.2     -16.3       1.8             9.1      │
│    Luka Doncic      DAL   366   10   9.4    5.2      1.5        2.5     64.9    36.0     3.3        17.2            9.1      │
│    Chris Paul       PHX   302   10   3.8    1.4      -1.0       1.7     35.2    11.8    -6.3        8.3             9.0      │
│   Jrue Holiday      MIL   331   10   4.4    2.4      -0.6       1.6     46.7    21.2    -2.7        11.1            8.8      │
│ Tyrese Haliburton   IND   371   11   4.9    4.3      1.0        2.3     48.4    22.7     8.2        14.5            8.8      │
│  Andrew Nembhard    IND   200   10   0.7    0.6      -0.9       0.9     25.4    11.4    -3.6        3.7             8.7      │
└──────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┘
```
## $next_games

**What it does**

Shows the next 10 games the selected team has scheduled.

Span: Current Season

**How to use it**

$next_games [team_acronym]

**Example**
```
$next_games cle
┌────────────────────────────────────────────────────────────────────────────────────────────┐
│       away_team          away_tag         home_team         home_tag          date         │
├────────────────────────────────────────────────────────────────────────────────────────────┤
│  Cleveland Cavaliers       CLE       Los Angeles Lakers       LAL      2022-11-06 12:30:00 │
│  Cleveland Cavaliers       CLE           LA Clippers          LAC      2022-11-07 19:30:00 │
│  Cleveland Cavaliers       CLE        Sacramento Kings        SAC      2022-11-09 19:00:00 │
│  Cleveland Cavaliers       CLE      Golden State Warriors     GSW      2022-11-11 19:00:00 │
│ Minnesota Timberwolves     MIN       Cleveland Cavaliers      CLE      2022-11-13 18:00:00 │
│  Cleveland Cavaliers       CLE         Milwaukee Bucks        MIL      2022-11-16 19:00:00 │
│   Charlotte Hornets        CHA       Cleveland Cavaliers      CLE      2022-11-18 19:30:00 │
│       Miami Heat           MIA       Cleveland Cavaliers      CLE      2022-11-20 19:00:00 │
│     Atlanta Hawks          ATL       Cleveland Cavaliers      CLE      2022-11-21 19:00:00 │
│ Portland Trail Blazers     POR       Cleveland Cavaliers      CLE      2022-11-23 19:00:00 │
└────────────────────────────────────────────────────────────────────────────────────────────┘
```
## $scoreboards

**What it does**

Shows the planned time if a game is scheduled for later in the day, and shows the current score, remaining time and quarter if the game is ongoing.

Span: Current Season

**How to use it**

$scoreboards

**Example**
```
$scoreboards

Mavericks (2-3) vs. Magic (1-5)
9 - 13
Q1 8:3

Cavaliers (4-1) vs. Knicks (3-2)
80 - 87
Q3 1:25

Spurs (4-2) vs. Timberwolves (4-2)
35 - 31
Q2 8:39

Pistons (1-5) vs. Warriors (3-3)
89 - 79
Q3 4:11

Celtics (3-2) vs. Wizards (3-2)
87 - 68
Q3 0:0

Clippers (2-4) vs. Pelicans (4-2)
91 - 112
Q4 0:0

Suns (4-1) vs. Rockets (1-5)
9:00 pm ET

Lakers (0-5) vs. Nuggets (4-2)
9:30 pm ET
```
## $season


**What it does**

Shows various tb statistics(playval,scoreval, passer rating, box creation, bpm) and public statistics(LEBRON) for a player.
The user can select a single season or a multi season stretch, with the latter being determined using a weighted average by minutes played.

Span: 1955 - 2022 (Corresponds to the Thinking Basketball Historical Database)


**How to use it**

$season [firstname] [lastname] [start year] [end year *-optional*]

**Examples**
```
$season michael jordan 1992 1993
```
![Season](https://media.discordapp.net/attachments/1045134231707336764/1095821055802748979/fig1.png?width=1600&height=800)


## $wowy

**What it does**

Shows with and without you(wowy) player combinations taken from [PBP stats.](http://www.pbpstats.com/wowy-combos/nba)
Users can select any combination of players on a team, any combination of seasons within that timeframe, and chose between
regular season(rs), post season(ps) and total(all) wowy calculations. They can also chose whether to limit the calculation
to games including all of the selected players.

Span: 2001 - Present

**How to use it**

$wowy [team_acronym] [names] [years] [season type] [common*-optional*]

**Example**

```
$wowy lal kobe bryant pau gasol 2009 ps
```
![Wowy](https://media.discordapp.net/attachments/617888289801895966/1095555436339535892/fig1.png?width=1832&height=1145)

## $teamseason

**What it does**

Shows various team level metrics for the regular season(rDOtg,rORTG,SRS) and the playoffs if applicable(cORtg ,cDRtg ,cNET ).

Users can select a single season or a multi season stretch. Playoff metrics for the latter are determined via a weighted average by games played.

Span: 1980 - 2022

**How to use it**

$season [team_acronym] [start_year] [end year *-optional*] 

**Examples**

```
$teamseason hou 2018 2019

```

![Team Season](https://media.discordapp.net/attachments/1045134231707336764/1095821466597072906/fig1.png?width=1600&height=533)
