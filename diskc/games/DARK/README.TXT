DARKLANDS NOTES - version 483.07 - February 26, 1993
ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
INTRODUCTION

This version is a major upgrade. Numerous problems and difficulties 
have been solved, thanks both to the many contributions and notes 
from users, and our own continuing testing. This version allows 
save-games during certain big battles, and makes both loading and 
saving much more reliable.

Games saved using earlier versions should still work. However, some
fixes do not take effect unless you start a new game. These fixes
are minor; for example, in one, it's easier to leave Graz. However,
for the best possible version, start a new game.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
HARD DISK SPACE

Darklands requires about 17,500,000 bytes (17.5 MB) of hard disk 
space. This includes about 16 MB of files, plus approximately
1.5 MB of temporary storage, first for high speed installation, 
and then reused as temporary file storage during play, including 
a reasonable number of saved games. The exact amount of hard disk
space may increase on very large hard disks. On one 600MB hard disk
we've seen the game require 22 MB of space.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
MEMORY (RAM) REQUIREMENTS

Currently Darklands requires 595,000 bytes (581K) of main memory, 
plus 180,224 bytes (176K) of EMS memory. If you are uncertain of the 
memory in your machine use the DOS 5.0 command "MEM /C" to view the
entire memory configuration of your computer.

Darklands also requires FILES=20 (or more) in your CONFIG.SYS file.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
FAST LOADING COMMANDS

The "DARKLAND /Q" command mentioned in the technical supplement
disables ALL animation routines in the game, not just the initial
animation. This command is intended for hardware configurations 
that have problems with the animations, but which can run the rest 
of the game (see Extended Animation Sequences, below, for details).

To preserve the animations, but quickly bypass the opening sequence,
load normally with DARKLAND, then immediately tap the space bar. 
This bypasses the opening animation, while preserving the later 
defeat and victory animations.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
SAVING THE GAME

The best places to save Darklands are:
    (a) While staying at a city inn;
    (b) While camping in the countryside;
    (c) While on the travel map of Germany.
    (d) On certain battlefields, in certain cases.

Battlefields that allow save-games are indicated by a message
saying "Battlefield save rules are in effect". The main "save 
rule" is simple: there must be no living enemies on the current 
floor or level. In addition, you can save any time the game leaves
the battlefield for an interaction (i.e., a full-screen text/
picture/menu combination). In general, if you can use group 
movement mode, you can save (on appropriate battlefields).

The only battlefields that allow saves are the largest: the
various mines, the Templar's fortress monastery, and Baphomet's
Citadel of the Apocalypse. In fact, we recommend you save
frequently in these battles. This protects you from unexpected 
problems.

You can save the game at other times outside of battle. However,
when you restore, you may sometimes be "set back" a bit in time 
because a lot of complex logic has not yet changed all data in 
the "permanent" areas yet.

You can have up to 100 saved games. To scroll through the list, 
use the up and down arrow keys on the keyboard.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
FRANKFURT, FREIBURG and FREIBERG

Astute players will realize that some cities have similar names.
Within the game, "Frankfurt am Main" is abbreviated as 
"Frankfurt M", while "Frankfurt an der Oder" is "Frankfurt O".

Freiburg im Breisgau is misspelled "Freiberg im Breisgau" on the 
map. It is spelled correctly in the game, and abbreviated to
"Freiburg B" for greater clarity. The other Freiberg, in the Wettin
Lands, is spelled correctly and is just "Freiberg" in the game.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
CHARACTER COLORS

We very much regret that an extremely rare problem may cause a
battlefield character to suffer some color changes in battle.
However, you as a player won't notice the change until the next
battle. The bad part is that the change is stored in the saved
game file. You can fix up your characters by returning to an
old saved game. For example, in battle #3 you notice Gretch has 
green hair (yuck). If you return to a game saved prior to battle 
#2, Gretch will be fine again. We apologize for this work-around.
We've tried all sorts of tools and traps for this condition, and 
spent hundreds of hours testing for it. We'd be delighted to 
publicize the name of the first person who can tell us how to make 
it occur upon demand.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
SAVES\DEFAULT FILE

The SAVES subdirectory includes a file titled "DEFAULT." This file 
must be present in this subdirectory to permit character generation.
If you use DOS commands to copy, clean out, etc. the SAVES files, be
sure to not erase DEFAULT.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
LOADING SAVED GAMES

This version supports the ability to load saved games while in the
game, as described on page 18 of the manual. In addition, you can
scroll through the list of saved games using the keyboard arrow keys.
Loading is prohibited on certain information screens. Simply exit
the information screen and loading is re-enabled.

Beware that once you commit to loading a game while playing, you
MUST select a game to load. You cannot escape back to the game you
were playing. We apologize for this inconvenience.
 
ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
CHARACTERS LEAVING BATTLE by STAIRS or LADDERS

If a character uses a ladder or stairway (a "portal") to change 
floors, remember that the character is now inaccessible except 
through the appropriate number key (1 through 5) on the keyboard. 
Please review pages 35-36 of the manual if you're confused.

Also note that "Multiple Portals" is more flexible than the manual
suggests. If all survivors have left the original floor in different
directions, the view shifts to the character who departed last.
However, we still recommend that you rejoin the party immediately, 
since various functions (including group mode) may be confused
by a party split onto various floors.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
UNCERTAIN FATES & PRISONERS

Sometimes a character will suffer an uncertain fate. A series of 
"?" symbols appear in the blue character box. Such characters may be 
dead, may be a prisoner in a nearby city, or may have escaped their
fate and be waiting for you at some nearby city inn.

To rescue a prisoner, you must get into the dungeons of the city 
hall. If forced into a fight, you must kill ALL the guards. 
Accomplishing this will free your compatriot.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
QUICK EQUIPMENT TRANSFER

A number of players just use the mouse for transferring equipment
from one character to another. Although simple, this can be slow.
Note that there is a keyboard equivalent to the "drag and drop"
mouse action -- just tap a number key for the destination. See page
25 in the manual for details! Darklands has many keyboard shortcuts
that ease game play.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
RETIREMENT

Characters can temporarily retire at any city inn. You can later
return and invite them to rejoin the party once more. However, when
anyone joins an existing party, be they an old friend or someone
new, they come with NO equipment, just their knowledge. Therefore,
before retiring someone, cache their equipment at that inn.

There is no specific screen for retiring the entire party. To retire,
just save the game and erase all earlier saved games for that party.
You can take them "out of retirement" at any time by loading that
saved game.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
HALL OF FAME

The manual incorrectly states that Darklands has a Hall of Fame.
The game does not. However, for your information, we expect that 
moderately successful parties will achieve fame in the low hundreds, 
while very successful ones will reach the high hundreds.

Darklands has no specific ending -- you can play forever. However,
if you have defeated Raubritters, dragons, the three different kinds
of problems in mines, and ultimately Baphomet, you have encountered
all the major challenges. Good luck and good adventuring!

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
EXTENDED ANIMATION SEQUENCES

The opening sequence and two other animations during the game may
have problems with a few hard disk drive controllers. Generally, if
the opening animation runs without problem three or four times, you
should not have any difficulties.

If, however, you do have difficulties, we suggest you load with 
DARKLAND /Q. This will bypass all the animation sequences, thus 
avoiding any chance of trouble.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
SIMULTANEOUS ROLAND & SOUND BLASTER SUPPORT

It is possible to have both Roland MT-32/LAPC-1 sound and digital
speech in Darklands. However, it requires that you rename certain
files (described below) and then use INSTALL to set the game's sound 
to whatever NON-Roland board you are using. These boards include:
  Covox Sound Master II,  Sound Blaster,  Sound Blaster Pro,
  Pro Audio Spectrum (including + and 16 versions),
  Thunderboard,  ATI F/X

To rename the files to support both boards, go to MPS\DARKLAND
(or whatever subdirectory you installed the game into) and type
the following DOS commands:

COPY PSOUND.DLC PSOUND.DC
COPY PSOUND.DLB PSOUND.DB
COPY ASOUND.DLC ASOUND.DC
COPY ASOUND.DLB ASOUND.DB

COPY RSOUND.DLC PSOUND.DLC
COPY RSOUND.DLB PSOUND.DLB
COPY RSOUND.DLC ASOUND.DLC
COPY RSOUND.DLB ASOUND.DLB

Later, if you wish to restore the game to its normal configur-
ation, type the following DOS commands:

COPY PSOUND.DC PSOUND.DLC
COPY PSOUND.DB PSOUND.DLB
COPY ASOUND.DC ASOUND.DLC
COPY ASOUND.DB ASOUND.DLB

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
MICROPROSE HINTS BY PHONE

MicroProse has a telephone hint line service effective October 1,
1992. Information will be available on a range of games and cate-
gories, including recent MicroProse, MicroPlay, Evryware and 
Paragon titles for simulation, strategy, role-playing, graphic
adventure, and sports, as well as MicroProse's Nintendo video games.

The MicroProse telephone hint line is 1-900-933-PLAY. Charge is
$0.95 per minute, callers must be 18 years or older, a touch-tone
phone is required. Call 24 hours a day, 7 days a week.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
DARKLANDS CLUE BOOK

A clue book full of numerical data of all sorts, not to mention
outlines of the quests, hints and answers to puzzles, and much
more is available now from MicroProse. It is available either
with or without a special disk. The special disk contains a music
player, a picture viewer, and a character editor.

Call 1-800-879-PLAY to order your copy from MicroProse, or look
for it at your favorite software store.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
