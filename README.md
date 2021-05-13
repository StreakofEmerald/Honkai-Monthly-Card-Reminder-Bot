# Honkai-Monthly-Card-Reminder-Bot
A bot that enables users to set their own reminders to login to the game Honkai Impact 3rd for their monthly card rewards, along with other useful features.
Commands are below:

[@Honkai Monthly Card Reminder]: Sends a message containing useful info on the bot, including who to contact for help and a link to this README.

$help: DMs the user with the aforementioned message.

$cardtime [00:00]: Allows the user to set a time to be reminded to login. 24 hr format. Reminder time determined by local timezone. The user with be @'ed daily.

$weeklytime [00:00]: Allows the user to set a time for their weekly reset. Functions similarly to $cardtime, but on a weekly basis.

$versionreset [00:00]: Allows the user to set a time for their version reset. Functions similarly to $cardtime and $weeklytime, but is one-time only.

$resetlookup [server]: Allows the user to lookup daily, weekly and version reset times for the specified server (NA, EU, JP, KR or CN). Times are in UTC +0. Version reset times are calculated from the expiration times of ingame version-exclusive event items (i.e. Bunny Cards for 4.7).
