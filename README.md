# RankSentinel

RankSentinel watches the combat log and detects when group members (and now their pets!) accidentally use a low-rank ability and sends them a private message so they can fix the issue. It's inspired by the legacy add-on [RankWatch](https://www.curseforge.com/wow/addons/rankwatch).

We built this tool to help your raid group make small improvements so they can avoid those 1%-wipe situations. In testing it detected so many guildies, friends, and PUGs who had just forgotten to update their action bars or macros after training. Everyone has at least one ability they forgot to update. Everyone.

- Legitimate low-rank Abilities have been excluded; including all heals, Frostbolt (Rank 1), Earth Shock (Rank 1), Blizzard (Rank 1), etc.
- Ability data comes from [Gogo's revised ability list](https://docs.google.com/spreadsheets/d/1jtx1WyfChzACzh0WBWANtrqkRtS3D-zPWqs3eOnyVvY/edit?usp=sharing), please leave a comment for any ability data changes you have in mind.
- A large focus has been on delivering the most optimized code possible, memory usage is significantly less than Questie, your favorite damage meter, or inventory management add-on.
- RankSentinel's [GitHub issues](https://github.com/valkyrnstudios/RankSentinel/issues) and [CurseForge comments](https://www.curseforge.com/wow/addons/ranksentinel) are great locations to report any issues you find.
- RankSentinel is a [spiritual successor](https://github.com/valkyrnstudios/RankSentinel/issues/5) to the now-defunct GogoWatch and SpellSnob add-ons.

## Commands

Use `/ranksentinel` to get the latest commands.

- `/ranksentinel enable`: toggles combat log parsing
- `/ranksentinel whisper`: toggles whispers to players
- `/ranksentinel combat`: toggles whispers to players during combat
- `/ranksentinel reset`: resets profile to defaults
- `/ranksentinel count`: prints current statistics
- `/ranksentinel debug`: toggles debug output for testing
- `/ranksentinel clear`: clears local ability caches
- `/ranksentinel lead`: sets yourself as lead
- `/ranksentinel ignore`: adds current target to addon ignore list, will not report rank errors

## Contributors

- Gogo - for continued addon collaboration and data curation
- Aevala and Fathom - ability data feedback, exclusions
- Splendiferus - for continued testing and feedback
