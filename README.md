# MyBattleCats

An attempt to turn the Black Catculator to a website where I can check my Battle Cats progress. 
A lot of the inspiration comes from the current tracker I use, but it would be pretty cool to turn it into a website.

## Overview

### Main Features
- View All Cats
- Lifetime Statistics
- Stories of Legend Progress
- Loadouts?
- Favorite Cats
- Calendar?

### What is Battle Cats?
[Battle Cats](https://battlecats.club/en/series/battlecats/) is a tower defense game in which players deploy cat units to defend against waves of enemies and attack enemy bases. Players collect and upgrade cat units with unique abilities and attributes. It is available for free on the App Store and Google Play.

Note: Do not play if you have a gambling addiction... it's a gacha game

### Current Cat Tracker
I'm currently using [r/BattleCats's Black Catculator](https://docs.google.com/spreadsheets/d/1apSRNVAcpT4DRILXUASK691z7IlTxF7yw2ot_JVLO6E/edit#gid=894095787) to track my progress. I plan to utilize some of the main features of the spreadsheet in my website.

Here's a preview of what cats I have so far in the game:

<img src="https://github.com/Oohwo/battle-cats-progress/blob/main/wireframes/black%20catculator.png?raw=true" width=700>

### Next Steps
- [ ] Brainstorm / Create Wireframes
- [ ] Create more wireframes
- [ ] Export data from various sources ([Battle Cats Wikia](https://battle-cats.fandom.com/wiki/Battle_Cats_Wiki), [UDP Directory](https://thanksfeanor.pythonanywhere.com/UDP), [Black Catculator](https://thanksfeanor.pythonanywhere.com/black-catculator))
- [ ] Clean that data and make into a cool csv file ooh yeah
- [ ] Discord Bot for reading and writing to website?
- [ ] Create a Figma File for website
- [ ] Figure out how to create a website with the Figma file
- [ ] Create a Table / Gallery View for All Cats
- [ ] Host it somewhere lol

## Brainstorming:

Cat:
| Property | Type | Description |
| ----- | ----- | ----- |
| name | String | name of the cat |
| id | int | id of the cat |
| obtained | boolean | have i obtained this cat yet |
| rarity | String | basic, special, rare, super rare, uber rare, legend rare |
| level | int | current level of the cat (up to 30) |
| level_plus | int | extra levels using catseyes |
| icon | Dictionary | greyscale / colored icons |
| wiki_link | String | link to wikia |
| udp_link | String | link to UDP website |

Average Level for Cats:
| Rarity | LVL | + |
| ----- | ----- | ----- |
| Basic | int | int |
| Special | int | int |
| Rare | int | int |
| Super Rare | int | int |
| Uber Rare | int | int |
| Legends | int | int |
| Overall | int | int |

## Wireframes:
<img src="https://github.com/Oohwo/battle-cats-progress/blob/main/wireframes/possible_homepage.png?raw=true" width=200>
<img src="https://github.com/Oohwo/battle-cats-progress/blob/main/wireframes/cats%20and%20stats%20wireframe.png?raw=true" width=500>

## Credits / Various Links
- [Battle Cats](https://battlecats.club/en/series/battlecats/)
- [r/BattleCats](https://www.reddit.com/r/battlecats/)
- [UDP Directory](https://thanksfeanor.pythonanywhere.com/UDP)
- [Wikia](https://battle-cats.fandom.com/wiki/Battle_Cats_Wiki)
- [Official Battle Cats Calendar](https://ponos.s3.amazonaws.com/information/appli/battlecats/calendar/en/index.html)
- [Purdue Hackers Website inspo](https://purduehackers.com)
