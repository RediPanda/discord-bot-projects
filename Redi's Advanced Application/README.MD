# Redi's Advanced Application System

> **Module Information:** 
Package Name: Redi's Advanced Application System

> Creation Date: 12/06/2019

> Last Updated: 13/06/2019

> Require: DBM Mods, Latest Modpack (as of 12/06/2019)

> If there's anything wrong with the package, please contact Redi Panda_#3657.

**Big thanks to TheMonDon#1721 for fixing up some files and adding conditions check to some commands!**

> **WARNING: NOT SYNCED AND CONNECTED WITH OTHER REDI'S SUB-MODULES**

*Redi's Advanced Application System provides you the ultimate control over the applications in your guild. From both the application manager's sides to the end-user, it is friendly to use and easy to edit.*

**The following package includes:**

  - *Bot DM form submission.*
  - *Review all outstanding applications.*
  - *Enlist a finite number of staff to manage the applications.*
 

---
**Included in the package:**
- 
- Events: **ApplicationRefresh**
- Commands: **Apply**, **Review**, **Scroll**, **Accept**, **Deny**, **AddStaff**, **DelStaff**


## What do these commands/events do?
`Event - ApplicationRefresh`
Creates a new application listing if this is your first time using the module. It's intended purpose is to also refresh the listing since it cannot **retain the original listing after 2+ bot restarts.** *I cannot rectify this issue until further notice.*

`Command - [p]apply`
Initiates a DM to the Command Author with 3 (default) responses. The bot will await for the user to complete these responses in order to submit it to the corresponding guild. Timeout during the responses will cancel the operation. Applicants by default cannot re-apply to prevent filter flooding, unless the Application Manager approves or denies the application.
**If by any chance does a Application Manager accidently scrolled through the listing, removing the application's information; they can do [p]review <userid> to fetch the information and only then can they accept/deny that request.

`Command - [p]review`
Displays the listing of all awaiting applications. It displays the total applications awaiting for review and displays all the ID's in a good-looking embeded message.
-- --- -- ---`Subcommand - [p]review <id>`
Displays the specific application ID's information. This includes their account information; Display Tag, User ID, Account Creation Date, Account Join Guild Date and includes the responses provided. This command is also used to fetch previous staff information since this does not clear their internal data.

`Command - Scroll`
Scrolls up the review listing, removing the highest (oldest) ID to allow easier breathing space and management.

`Command - Accept`
Accepts the application and sends the applicant a DM in response to their application status.

`Command - Deny`
Denies the application and sends the applicant a DM in response to their application status.

`Command - AddStaff`
Grants the mentioned user the ability to use **review, accept, deny scroll**.

`Command - DelStaff`
Ungrants the mentioned user the ability to use **review, accept, deny scroll**.

#
