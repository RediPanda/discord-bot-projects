# Redi's Marriage System

> **Module Information:** 
Package Name: Redi's Marriage System

> Creation Date: 23/05/2019

> Last Updated: 19/06/2019

> Require: DBM Mods, Latest Modpack (as of 19/06/2019)

> If there's anything wrong with the package, please contact Redi Panda_#3657.

> **WARNING: NOT SYNCED AND CONNECTED WITH OTHER REDI'S SUB-MODULES**

*Redi's Redi's Marriage System provides you the ultimate control over the fantasies and families in your guild. From both the application manager's sides to the end-user, it is friendly to use and easy to edit.*

**The following package includes:**

  - *Marry other users!*
  - *Divorce other users!*
  - *Check marital status on other users!*
 

---
**Included in the package:**
- 
- Events: **N/A**
- Commands: **marry**, **divorce**, **marriage**


## What do these commands/events do?

`Command - [p]marry`
Initiates a DM to the Command Author with 3 (default) responses. The bot will await for the user to complete these responses in order to submit it to the corresponding guild. Timeout during the responses will cancel the operation. Applicants by default cannot re-apply to prevent filter flooding, unless the Application Manager approves or denies the application.
**If by any chance does a Application Manager accidently scrolled through the listing, removing the application's information; they can do [p]review <userid> to fetch the information and only then can they accept/deny that request.

`Command - [p]marriage`
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
