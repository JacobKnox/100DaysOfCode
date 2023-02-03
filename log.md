# 100 Days Of Code
## Day 1 - February 1st, 2023
&emsp;&emsp;I coded for around 30 minutes from 11:45 AM to 12:15 PM EST and pushed changes to my Discord bot changing the !pnwraw and !pnwmanu resources to default to "all" which returns statistics about all raw/manu resources. [Commit](https://github.com/JacobKnox/Personal-Discord-Bot/commit/61af30bed1bdaee05734e8b51f82c3312b381bdf)

&emsp;&emsp;Spent roughly 20 minutes from 12:50 to 1:10 PM EST to make the !ban command functional and usable. Also fixed an issue where certain command errors would spam my DMs and a certain command error would be sent to my DMs when it didn't need to be. [Commit](https://github.com/JacobKnox/Personal-Discord-Bot/commit/2ddb76f854cffe7120d10b871ba2168fae70db5f)

&emsp;&emsp;Created a !kick command for the Discord bot around 2:20 PM EST (more or less a copy and paste of the ban command with minor changes). [Commit](https://github.com/JacobKnox/Personal-Discord-Bot/commit/e776f76fb978c003995cfdea70249132a1aa7bdf)

&emsp;&emsp;Started a !pnwmarket command to return information about the current buy and sell offers for a given resource. Worked on it for about 30 minutes from around 11:30 PM to 12:00 AM and made good progress, but currently running into a GraphQL error. [Commit](https://github.com/JacobKnox/Personal-Discord-Bot/commit/aea30fd2b8b4abfa7489c5d8a870f5fff88283f5)

## Day 2 - February 2nd, 2023
&emsp;&emsp;Ashamed to admit I just spent an hour trying to figure out the issue I was having with the !pnwmarket command from around 6:30 to 7:30 PM EST. Thank God [Village](https://github.com/mrvillage) realized I was using an outdated version of pnwkit-py and that resolved everything. [Commit](https://github.com/JacobKnox/Personal-Discord-Bot/commit/977d55768ed0365d1f11503588624763fd6775b8)

&emsp;&emsp;Spent the next roughly 20 minutes from 7:30 to 7:50 PM EST improving the !pnwmarket command. It now throws an error if the resource entered is invalid and defaults to "all" to get the market information of all resources. [Commit](https://github.com/JacobKnox/Personal-Discord-Bot/commit/d9b194c7af76b05b89681ff12227f2787a622649)