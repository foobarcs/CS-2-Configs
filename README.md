![couter strike banner](https://i.ibb.co/8Yq6F8T/cs2-banner-for-faceit.jpg)


#### Official Counter-Strike Major Supplemental Rulebook
[Volvo Counter-Strike Major Rulebook](https://github.com/ValveSoftware/counter-strike/blob/main/major-supplemental-rulebook.md)

------

### Filepath for configs

##### CS-2 config filepath
C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg

------

### Token and authentication code
#### Game server login token for creating public/private Counter-Strike server
https://steamcommunity.com/dev/managegameservers

#### Authentication code for accessing Counter-Strike match history (Leetify for example)
https://help.steampowered.com/en/wizard/HelpWithGameIssue/?appid=730&issueid=128

------

### Miscellaneous commands
#### `bind` command to find which key bind to what command
example: `bind o` -> `"o" = "toggle volume 0.01 0.25"`

#### `find` command to locate a command related to specific keyword
example: `find money` ->  
`"mp_afterroundmoney" = "0" client replicated - amount of money awared to every player after each round  
"mp_economy_reset_rounds" = "0" client replicated - Reset all player money every N rounds (0 for never)`

#### bind a key to spawn to specific position for jump/utils practice
`getpos`  
`bind mouse5 "setpos 2055.492432 -132.761276 356.093811;setang -0.088000 -179.466614 0.000000"`

#### activate a c4 and extend c4 duration time in seconds
`ent_create planted_c4_training; ent_fire planted_c4_training ActivateSetTimerLength 1200`
