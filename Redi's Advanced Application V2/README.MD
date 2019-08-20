# Redi's Advanced Application System

> **Module Information:** 
Package Name: Redi's Advanced Application System V2

> Creation Date: 18/08/2019

> Last Updated: 21/08/2019

> Require: DBM Mods, Latest Modpack (as of 18/08/2019)

> If there's anything wrong with the package, please contact Redi Panda_#3657.

> **WARNING: NOT SYNCED AND CONNECTED WITH OTHER REDI'S SUB-MODULES**

*Redi's Advanced Application System provides you the ultimate control over the applications in your guild. From both the application manager's sides to the end-user, it is friendly to use and easy to edit.*

**The following package includes:**

  - *Bot DM form submission.*
  - *Review all outstanding applications.*
  - *Enlist a finite number of staff to manage the applications.*
  - *AUTO LIST SAVING FEATURE*
  - *AUTO REMOVAL QUERY FEATURE*
  - *INTERFACE UPDATE!*
  - *BETTER LOGICS AND NEW DOCUMENTS*
 

---
**Included in the package:**
- 
- Events: **RediEvent-ApplicationInit**
- Commands: **Apply**, **Review**, **Accept**, **Deny**, **App-settings**
- Readme Docs on how to add more questions/remove questions and FAQ inqueries about Origin and V2.


## What do these commands/events do?
`Event - RediEvent-ApplicationInit`
Creates a new application listing if this is your first time using the module. It's intended purpose is to also refresh the listing since it cannot **retain the original listing after 2+ bot restarts.** *I cannot rectify this issue until further notice.*

`Command - [p]apply`
Initiates a DM to the Command Author with 3 (default) responses. The bot will await for the user to complete these responses in order to submit it to the corresponding guild. Timeout during the responses will cancel the operation. Applicants by default cannot re-apply to prevent filter flooding, unless the Application Manager approves or denies the application.
**If by any chance does a Application Manager accidently scrolled through the listing, removing the application's information; they can do [p]review <userid> to fetch the information and only then can they accept/deny that request.

`Command - [p]review`
Displays the listing of all awaiting applications. It displays the total applications awaiting for review and displays all the ID's in a good-looking embeded message.  

--`Subcommand - [p]review <id>`
Displays the specific application ID's information. This includes their account information; Display Tag, User ID, Account Creation Date, Account Join Guild Date and includes the responses provided. This command is also used to fetch previous staff information since this does not clear their internal data.

`Command - app-settings`
You can set/control app logging, locks and application roles using this command!

`Command - Accept`
Accepts the application and sends the applicant a DM in response to their application status.

`Command - Deny`
Denies the application and sends the applicant a DM in response to their application status.


## First time usage!

After installing all commands and events, please make sure to scroll through all of them to make sure you're not missing any mods!
If you are missing mods, you can fetch the latest `beta` mods [here](https://github.com/Discord-Bot-Maker-Mods/DBM-Mods/tree/beta)!

After the installation step, run [p]app-settings to setup a few options. These include: Application Control (Lock), Application Management (Role) and Application Logging (Logs Channel)
This will be useful for more control over your RD and you can enable/disable these options through this command.

After setting up everything, you can also run `[p]app-settings test <module(role/log/posts)>` to test out if your setup is running correctly as it should be.

That should be it! Your application system should now be able to process all the data and queries from users!

## FAQ from Origin and Beta!

`Why is there a V2??? Why can't you update the current origin package?`

I've made a separate package for several reasons. These include;
  - Better workflow/logic statement. It's a mess going back to old RD and I can't tell what happens half the time.
  - To archive old and new stuff. This is technically considered as a new package, so I'll leave it between old and new.

`Would all old application data carry over if I update to this package?`

Yes! All your old application data will be carried over to this new package! I made sure that everything is convinient for both DBM Users and
for users using the bot as well!

`Why do you use the data system if its in the deprecated section?`

Because I don't have the sufficient knowledge of using SQL and neither would the majority of DBM Users would. I made sure that the system works
flawlessly and easy for DBM Users to learn and obtain from using my RD. My RD is suppose to be a learning experience for both me and the users as
well as operate as it states.

Its only in the deprecated section due to the rate/chances of corruption. It is known to be corrupted every now and then so please, I recommend you
to backup all your "data" directory folders on a daily basis since this is good practice!

`How do I update from origin to V2?`

Just remove all your commands from the bot and add these new ones here! All your old data should stay the same, however most features from origin won't carry over. 
This may include locking systems since the new locking system runs off a different data branch.

`How can I add/remove more questions?`

You can modify the current template by following the instructions provided below this info content and inside the RAW DATA.

1. Make sure that you fully understand that if you fail to comply with the instruction, it may lead to irreversable damage to both the data and 
the RD itself.