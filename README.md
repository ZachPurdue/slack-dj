# slack.dj

A .dj plugin to allow slack users to create, control, and modify a plug.dj playlist from a dedicated slack channel.

================

Contributors

   - Zach Perry (ZachPurdue) (creator)

================

Goals/Vision

A) DJ SLACKBOT  
   - Slack users can create a dj channel within slack
   - channel creates a slackbot with dj commands 

B) Command List (Future/TBD)  
   - addSong(youtube link) adds song to queue
   		- remove(self) normal user, removes their next upcoming song
   		- remove(user) moderator, removes selected user's next upcoming song
   - skip() skips current song, moderator only
   - banUser(user, duration) moderator only
   		- prevents user from adding songs, user can still listen
   		- calls remove on users remaining songs until all songs gone
   - reportUser(user, reason) message mod with report
   - 

C) Command List (Current)  
   - 
   - 
   - 
   - 
   - 

================

# APIs Used

   - https://appi.slack.com
   - https://github.com/plugCubed/plugAPI
   - https://github.com/atomjack/plugbotapi

