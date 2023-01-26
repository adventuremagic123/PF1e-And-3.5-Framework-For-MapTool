# Introduction
This is a framework for running PF1e and OGL (3.5e) RPG games in MapTool 1.8.3 and above -- however, I only test in the latest MapTool version when I make changes.  I will typically be developing for the latest MapTool version because that's what my group will use -- and we've never had any problems doing that.

Note:  This code has been thoroughly tested in MapTool 1.8.3 for the initial release.

# Important Info For Hero Lab(R) Users

This framework supports importing data from Hero Lab(R) tokens dragged onto campaign maps via the Library window.  Read more about this in the documentation.

There's the following things you must be aware of when using Hero Lab(R):

A. Currently, MapTool 1.11.x and above has a problem where Hero Lab(R) tokens get messed up in the transition between starting and stopping the MapTool server.

1. In MapTool 1.12.x, you can develop your campaign without starting the MapTool server -- and you must save it before doing so.

2. You can load your campaign AFTER starting the server to play a game but likely BEFORE players connect.  Be sure to save your campaign before stopping the server.

3. MapTool 1.11.x will not allow Hero Lab(R) tokens to be dragged and dropped from the Library window -- but MapTool 1.12.x will.

4. MapTool 1.10.4 and below do not have any of these issues.

B. After dragging a Hero Lab(R) token to a map from a Hero Lab(R) file using the Library window, don't relocate the file it came from if you plan on resynchronizing the token due to updating the Hero Lab(R) file.

C. If you do relocate the file, my macros will prompt you for the new location -- and I think it works.  If you get prompted for the Hero Lab(R) file location, but have not changed the file, click the "Cancel" button and I think things will continue to work.

# 3.5e Is Not Currently Fully Supported, But Will Be Soon
If you want to run a 3.5e game, you'll have to ignore the PF1e part, i.e. Combat Maneuvers.  Also, Hero Lab(R) is only supported for PF1e characters, but I am hoping to add 3.5e support soon.

# Other RPG Game Systems Might Be Supported With This Framework
If you play 5e or PF2e, consider taking this framework and starting a project.  Most of the initial hard work has been done -- just please comply with my license agreement.  I put a lot of hours into this over a period of about a year and a half.

# Future Releases Of This Framework
Future releases of this framework will always be compatible with previous versions.  Previous versions will be automatically upgraded.  You generally won't have to do anying.

# Project Description

I apologize for the lightweight nature of my postings.

This project will be for managing a D&D 3.5 or Pathfinder 1e campaign in MapTool with features such as below, has been under nearly two years of development, and has been used by my group now for years since the beginning as it evolved:

- Party Treasure management
- Campaign management (view activity logs for each token so no more questions about how many spells or which spells were cast since last resting, how many arrows were used, how many charges were used, etc.)
- Campaign Time tracking (you'll now be able to deal with complex issues such as PCs crafting while the party moves on to further adventures)
- Automatic spell DC calculations
- Spell management (complete for both prepared and spontaneous spell casters)
- Easy to use interface
- Easy to understand macro layout
- Resource tracking (equipment, ranged attacks, spells, special abilities, money, etc.)
- New skills can be added by the GM (and they are automatically made available to all the tokens)
- Adjustments due to conditions or spells cast for abilities, size, movement, saving throws, energy resistance, AC, attacks, skills, light sources, etc. are automatically applied and can be enabled/disabled outright or based on whether their duration is rounds, minutes, or hours.
- Manage adjustments as reuseable templates for conditions, spells, and light sources.
- "Character Sheet" makes reviewing PCs and NPCs easy -- can be used in conjunction with WinMerge to do a text-based comparison for the old token's sheet versus the new token's sheet.
- "Player Token Editor.cmpgn" enables players to edit their tokens offline.
- Characters can give each other equipment items.
- Manage money.
- Resting automatically restores spells, hit points, daily use items and special abilities, expires adjustments with a temporary duration, etc.
- Import most PC and NPC details from Hero Lab(R) -- however, you can enter it all in manually without Hero Lab(R) if desired.
- And more ...

This framework has been used in regular game play by our group and enhanced periodically since December 2018 -- and might be easily modifiable to support other game systems such as PF2e, 5e, etc.

Hero Lab(R) is a registered trademark of Lone Wolf Development.
