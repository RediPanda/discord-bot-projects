DO NOT MODIFY THE EVENT TRIGGER IF YOU DON'T KNOW WHAT THE HECK YOU'RE DOING!<br />

# FAQ

Q. The second time I unreact, the bot doesn't register it!  
A. That seems to be a problem, however you can warm the listeners up by reaction/unreacting it.  

Q. Where do i put my actions when someone unreacts?!?  
A. Go to the `MessageReactionRemoved` event and you can add your own actions between the arrows indicated.  

# Lists of outputtable variables.

The following variables will be outputted:

 - Temp Variable  
	• `rediEvent.MemberID` 		- Returns the UserID of the person who unreacted.  
	• `rediEvent.Member` 		- Returns the Member Object. This variable can be used in the `Store Member Info` source variable.  
	• `rediEvent.ReactionObj`	- Returns the Reaction Object. This variable can be used in the `Store Reaction Info` source variable.
