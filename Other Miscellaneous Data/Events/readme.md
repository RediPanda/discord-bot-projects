DO NOT MODIFY THE EVENT TRIGGER IF YOU DON'T KNOW WHAT THE HECK YOU'RE DOING!  

# Information about the folowing files.

`codeToBeRun.JSON` - This raw data will handle all your actions when the event boots.  
`remoteEvent.JSON` - This raw data will listen to the events. This event SHOULD NOT BE MODIFIED!  

# Lists of outputtable variables.

The following variables will be outputted:

 - Temp Variable  
	• `rediEvent.MemberID` 		- Returns the UserID of the person who unreacted.  
	• `rediEvent.Member` 		- Returns the Member Object. This variable can be used in the `Store Member Info` source variable.  
	• `rediEvent.ReactionObj`	- Returns the Reaction Object. This variable can be used in the `Store Reaction Info` source variable.
