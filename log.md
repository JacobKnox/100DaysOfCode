# 100 Days Of Code

Break Days (mainly so I know how many to add to the end): 1

## Day 1 - February 1st, 2023
&emsp;&emsp;I coded for around 30 minutes from 11:45 AM to 12:15 PM EST and pushed changes to my Discord bot changing the !pnwraw and !pnwmanu resources to default to "all" which returns statistics about all raw/manu resources. [Commit](https://github.com/JacobKnox/Personal-Discord-Bot/commit/61af30bed1bdaee05734e8b51f82c3312b381bdf)

&emsp;&emsp;Spent roughly 20 minutes from 12:50 to 1:10 PM EST to make the !ban command functional and usable. Also fixed an issue where certain command errors would spam my DMs and a certain command error would be sent to my DMs when it didn't need to be. [Commit](https://github.com/JacobKnox/Personal-Discord-Bot/commit/2ddb76f854cffe7120d10b871ba2168fae70db5f)

&emsp;&emsp;Created a !kick command for the Discord bot around 2:20 PM EST (more or less a copy and paste of the ban command with minor changes). [Commit](https://github.com/JacobKnox/Personal-Discord-Bot/commit/e776f76fb978c003995cfdea70249132a1aa7bdf)

&emsp;&emsp;Started a !pnwmarket command to return information about the current buy and sell offers for a given resource. Worked on it for about 30 minutes from around 11:30 PM to 12:00 AM and made good progress, but currently running into a GraphQL error. [Commit](https://github.com/JacobKnox/Personal-Discord-Bot/commit/aea30fd2b8b4abfa7489c5d8a870f5fff88283f5)

## Day 2 - February 2nd, 2023
&emsp;&emsp;Ashamed to admit I just spent an hour trying to figure out the issue I was having with the !pnwmarket command from around 6:30 to 7:30 PM EST. Thank God [Village](https://github.com/mrvillage) realized I was using an outdated version of pnwkit-py and that resolved everything. [Commit](https://github.com/JacobKnox/Personal-Discord-Bot/commit/977d55768ed0365d1f11503588624763fd6775b8)

&emsp;&emsp;Spent the next roughly 20 minutes from 7:30 to 7:50 PM EST improving the !pnwmarket command. It now throws an error if the resource entered is invalid and defaults to "all" to get the market information of all resources. [Commit](https://github.com/JacobKnox/Personal-Discord-Bot/commit/d9b194c7af76b05b89681ff12227f2787a622649)

&emsp;&emsp;Spent the past roughly 20 minutes from 8:20 to 8:40 PM EST adding the !mute and !unmute commands. The !mute command, in its current state, creates a Muted role if one does not exist and adds it to the pinged members. The !unmute command, in its current state, removes this role from the pinged members. The bot sends messages alerting in the following cases: the Muted role does not exist and the user attempted to use the !unmute command, a pinged member is already muted and the user attempted to use the !mute command, and a pinged member is not muted and the user attempted to use the !unmute command. [Commit](https://github.com/JacobKnox/Personal-Discord-Bot/commit/4e14932d79127acac37391a4c16f0d7cab59839c)

## Day 3 - February 3rd, 2023
&emsp;&emsp;Spent about an 1 hour and 30 minutes today from around 3:00 to 4:00 PM EST and then from around 9:30 to 10:00 PM EST finishing up the GraphQL docs update for the PnW v3 API.

## Day 4 - February 4th, 2023
&emsp;&emsp;Today ended up being more of a physically productive and mental health day rather than mentally productive, so I didn't do any coding. Because of this, per the rules of the challenge, I cannot take another "break" until Day 15 and I must add a day to the end of this challenge.

## Day 5 - February 5th, 2023
&emsp;&emsp;Spent about 2 hours working on Aurora's Java implementation of the Aurora Space Puppy bot. First, I helped Toxic figure out how to work better with the JSONObject. Then, I added all the fields for a Nation model (going to start trying to parse JSON responses to the models soonish). Finally, I spent a good chunk of time fighting with Maven and Visual Studio Code to get the code to run locally.

## Day 6 - February 6th, 2023
&emsp;&emsp;Spent an untold amount of time, though a decent amount, working on adding two filters to the Politics and War v3 API. Mainly because one of them proved to be more complicated than I initially thought and I still haven't gotten it to work.

## Day 7 - February 7th, 2023
&emsp;&emsp;Spent around two hours today finishing up the API filters and getting them ready to be merged into the master branch. The past few days have been a bit slow for me, so I'm hoping I can pick the pace up more in the coming days.

## Day 8 - February 8th, 2023
&emsp;&emsp;Another day and even more time spent agonizing over the filters. Why must Laravel be the way that it is? I will conquer it. I must.

## Day 9 - February 9th, 2023
&emsp;&emsp;Today I got the code for PokeTCG Card Manager to run again (since the last time I ran it was on a different computer) and documented how I did it for future reference. I also spent time in class coding agglomerative clustering as part of class and later improved on it by adding the ability to choose what type of clustering to do and with which distance metric.