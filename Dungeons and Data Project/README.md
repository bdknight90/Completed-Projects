
## Dungeons and Data
#### Benjamin David Knight

### Dataset and Source:

>For my final project at Udacity I wanted to work with a dataset I could not only enjoy sinking my teeth into, but could provide me some practical real world data. I play the fantasy roleplaying game Dungeons and Dragons (D&D) often, to the point where I'm doing content creation for a homebrew based podcast. I thought it would be great to see what, if any, trends exist in character creation and if they would shed any insight into how to approach my work.

>To that end I was able to find a dataset using information taken from the "5th Edition Character Creator" (5th Edition is the current edition of D&D) phone app, an app I myself have used! The link to the data can be found here: https://github.com/oganm/dndstats/blob/master/README.md

### Main and Secondary Findings:

>In the exploration, I found that there was a strong relationship between the race and class chosen, with modifying effects from the stats. There is a loose correlation between stats within certain classes. I found a somewhat surprising result initially when I saw that a Human Fighter was the most popular choice despite being mechanically simple and relatively mundane. However, there is likely a mechanical reason for this outcome. Humans have a racial feat to add one point to every stat at first level or, alternatively, to take fewer points and gain a feat (the only race to allow for a first-level feat.) This versitility and feat-granting make Humans well suited to fit almost any situation. The rest of the data made sense: the core races are the most commonly played while the later introduced, rarer, and more complex races show up much less often.

>Outside of the main discoveries on character creation trends I did find that the most common alignment in character was Chaotic Neutral, which surprised me a bit. In fact Lawful characters took a back seat to every other alignment in their morality save for Lawful and Chaotic Evil. I also found that most players create their characters at lower levels as opposed to higher as I might have expected at first blush.

### Presentation Breakdown:

>For the presentation, I focus on mostly just the just the relationships between Stats, Race, and Class and leave out all of the Alignment information. I start by looking at the level groups, followed by an overview of stat distributions with violin plots, and race bar counts, then a matrix scatter plot of the stats of only Barbarians. Finally I see what the overall likelihood was of all the race/class combinations using a heat map. For the purposes of clean data I ignored any instances of multi-classing and homebrewing since it's not as common (only 14% of entries) and made the graphs difficult to read.
