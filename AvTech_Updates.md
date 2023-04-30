# ***AvTech Support Update Version 0.0.6

### **Features**

- Rewrote ticket system to be more efficient and reliable

- New developer commands for making viewing system much more easier *Some Features yet to be finished*

- Archived Category is available and Option to users now 

- Improved performance for updating multiple data at once *No Idea why I didn't do it earlier*

- Updated Prompts for Ticket Buttons to be up-to-date

- Start Up Embed will show Bot resourecs usage 


### **Bugs and Typos**

- Patched Verification System from bugging out when time has ran out 

- Patched Updating Category not working using [ `/ticket update_settings` ]

- Patched Logging Embed not being sent when Ticket System is deleted


### ***Notices***

- I previously logs on what exactly was updated however because of my switching over to a different system, I permanenetly deleted the whole folder accidentally without transferring update log and got a fresh one. Because of this 0.0.6 update may look like it was a short update but I promise you, there was a lot of effort in this update.

-

------------------------------------------------------------------------
# ***AvTech Support Update Version 0.0.5[A]***

### **Bugs and Typos**

- Patched Bug where Certain Servers won't get the Developer Ping and Message if the Server Info has not been found

- Patched Server Images not being added when Changing Verification Settings [ `Credits to @Felix™#2763`]

-

------------------------------------------------------------------------
# ***AvTech Support Update Version 0.0.5***

### **Features**

- All the Settings should have Emojis that are more related to what they are 

- [ `/verification setup` ] new command to Setup Verification System for AvTech Support that will follow a setup concept similar to [ `/main setup` ]

- [ `/verification update_settings` ] new command that updates Verification System that follows a similar concept as [ `/main update_settings` ]

- [ `/verification status_change` ] are for Admins and Server Owners that will change Verification Status for the Server either disabling Users from verifying
or not 

-  [ `/bot info` ] now will be able to see if your Server is Configured to the Verification System
    > To use Verification System, you **must** configure your Server to AvTech Support using [ `/main setup` ]

- [ `/server_settings` ] will also display Verification System Settings if you have it Configured to your Server

- During User verifying, they'll receive message in their DMs and a similar message will be sent in the Logging Channel for logging activities along with the Correct Verification Answer 

- Custom Message Informtion for Verification Message as well which include either Embed or Text Message Choice

- Maximum of 10 minutes for 60 users to join the Server
    > To increase the User Limit and Time Limit, you'll need to have Server Premium which will be available within the coming updates

- Server Premium also includes where if the User inputs the Wrong Verification Code, they'll get timed out for 15 minutes   
    > Not customisable yet, but will be available in the coming updates

- Added back the Welcome Message when you join the Official Support Server

- More RAM optimisation have been made throughout with built in RAM handler 

- TOS has been updated

- [ `/bot permission` ] now includes Category Channels where it'll check the Permission of that as well 

- Buttons used for updating Settings using [ `/main update_settings` ] or configuring settings using [ `/main setup` ] now have increased timeout of 20 - 30 seconds

- Renamed [ `/delete_user_info` ] to [ `/delete_ticket_info` ] so that the functionality of the command makes sense 

- Custom Information for Ticket Embed Creator has been changed to where if you Enter in None for one of the Boxes, that field won't be shown on the Ticket Embed
    > If None is Entered in both of the boxes, the field won't show 

- New Activity Status has been added where the Number of Total Servers that the Bot is in and the Number of Servers Configured will be displayed

- Added in Loggings for when you change the Custom Ticket Information

- Added minimum of 5 characters to be included when creating a Ticket even if the Box is required to fill 

- Users with Administrator Permission can now use  [ `/main setup` ] | [ `/verification setup` ]

- Bot Status should include Number of Servers Configured to the Verification System

- [ `/delete_ticket_info` ] should be dynamic now [ *`Previously it was but now it is more stable`* ]
    > If the Ticket Channel is not found or the Bot doesn't have permission, the Ticket Information will be deleted anyway

    -

    > If the Bot has permission and Ticket Channel is present, it'll send in 2 Options where you can either create a transcript and delete the Ticket or delete the Ticket **only**

- Non Premium Servers have a default of 2 Retries for Verification Code in case they aren't able to guess it otherwise 3 Tries
    > Instead of Sending Messages that can't be Deleted, due to how the Feature now works, hidden | ephemeral messages will be sent when interacting with the Verification System

- Changed the Look of the Verification Embed sent in Users DM during the Verification Process for a more Polished Look

- When Updates arrive, it'll ping the Server owner in Every Server or when Important Announcement from the Bot needs to be Reached out

- Emojis have been changed for some of the Roles and Information

- Removed Fastforward Left and Right for Help Command, since there is a Page Button to input in, Middle Button *Gray Colour Button* to quickly go to the Page Destination

- [ `/help` ] command now has improvements in performance in being reliable to use

- [ `/help` ] Page Navigation Button now has improved Stablisation where it'll only take inputs from the Channel you ran the Command from

- [ `/help` ] has been Updated for the New Commands, Verification System that has been added in 

- [ `/help` ] will now show all the commands that can be used within that Category...
    > [ `/main update_settings` ] used by Admins, Server Owner and Administrator Perms and so on

- [ `/developer announcement` ] has been rewritten where it'll ping the Server Owner if the Option has been picked instead of pinging @everyone


### **Bugs and Typos**

- Fixed Typo in [ `/main setup` ] when giving UI to set a Logging Channel

- Patched an Important Bug where a check wouldn't be made when Updating Settings in [ `/main update_settings` ] which would possibly cause a crash

- Patched a Bug where UI won't be disabled after they have been selected when Updating Settings when updating Main Settings

- Patched a Bug where Bot Logging Channel won't update the New Channel set using [ `/main update_settings` ]

- Patched some Emojis that weren't loading due to them being Deleted, [ *They have been replaced by something better!* ]

- Patched Ticket Message breaking when it can't find any Message itself

- Patched where if the Data wasn't been able to send to TextChannel, it'd cause the whole thing to break

- Fixed the Typo on on the Suggestion Embed sent in the Suggestion Channel and the colour of the Embed

- Patched Issue where if the Bot Start Embed doesn't send, it'll break and not update the Bot Uptime and Restart it

- Fixed small typo on [ `/support server_info` ] for Support Team

- Patched Error Embeds when there's an invalid response to a command 

- Patched a bug that broke [ `/main setup` ] for Configuring Custom Ticket Information

- Fixed Ticket Information not deleting from the Database when it creates a transcript 

- Patched Bug where if the Verification was partially configured, It'll break 

- Fixed where User ID would be showed instead of User being mentioned *Most of what I could find*

- Patched a Bug where if you cancel the Verification System Configuration using [ `/verification setup` ], It'll continue from where it started and Error out

- Patched Error Message when using application commands not in a Server which wouldn't give a Response

- Patched where the [ `/help` ] buttons wouldn't get disabled when they have been Timed Out leading to **Invalid Interaction**

- Patched a Bug where  [ `/server_info` ] would show multiple times for some reason

- Patched an important bug where if a Role is not found within the Server, the system would break and not work

- Patched bugs where interaction failed while saving Server Settings for Verification and Main Configuration

- Patched bug where Warning Embed won't send if commands are used in the Bots DMs

- Patched  [ `/support server_info` ] showing unaccurate information about Server Perms


### ***Contributions To AvTech Support***

- @Felix™#2763 for Emoji Searches, Multiple Feature Request, Bug Reports and Importantly; helping out to test the Anti-Raid System multiple times 

- @DustinFoes#7729 for Various Feature Requests for Premium Features and such

- 

------------------------------------------------------------------------
# ***AvTech Support Update Version 0.0.4[A]***

### **Bugs and Typos**

- Patched [ `/bot info` ] not working for some servers 
    > If the issue comes again, kick the bot and invite it back again. It should work then 

- Patched Ticket Buttons not working for Server Owners and Admin Role configured to AvTech Support 

- 
------------------------------------------------------------------------
# ***AvTech Support Update Version 0.0.4***

### **Features**

- Rewrote [ `/server_settings` ] to fit with the new features

- Simplified work on [ `server_info` ] for AvTech Support Members

- Support module has been fully configured for Optimal Performance

- When User randomly leaves a Server, all information will be deleted which will cause Error when Deleting Tickets
    
- Embeds that are public will be logged in the Logging System itself

- Bringing a User in a ticket is easier now as UI will pop up which you're able to Enter in a User name and should pop up.

- Bringing a User Ticket Feature will now also be able to remove a User if they're in the Ticket Channel Permissions

- [ `/server_settings` ] should now display Server's Name, Profile picture or Default picture, and User that used the command profile picture / GIF

- Ticket Button Features have now gained bit more stability in case if Server Information was not found in the database which would have caused it to break
    
    > After the Server Owner re-configures the Server to AvTech Support, the Tickets should work normally unless further stated by the Developers *Data loss which is very unlikely but can happen*

- [ `/server_info` ] will display the latest information for a Server that is requested

- Reworked Embed Message that gets sent when it is invited to a Server

- Ticket Channel will now have a nice emoji next to them for aesthetic including Category Channel

- Renamed [ `/setup` ] --> [ `/main setup` ]

- Renamed [ `/update_settings` ] --> [ `/main update_settings` ]
    > Reasons for why this has changed is because of the New Verification System Setup which might confuse people. This should be a stable change, if not Please Open a Ticket and Explain in detail on how you got the issue 

- Improved Stability for Creating Tickets, with improved Data Collection from Discord itself

- Ticket Message Pins will now include the User's Avatar, Server Icon + Name, User Input Message for Faster Response time in aiding the User's issues 
    > This all depends on the Ticket Support Users if they understand the issue and able to assist or their activity. We cannot guarantee that the User will get a response in a timely manner

- [ `/error_help` ] new command which will provide more information in a pleasing manner

    > We're hoping to make Users be able to solve issues that are displayed by AvTech Support with better solutions depending on the Error and better aesthetics

- Renamed [ `/close` ] --> [ `/support close` ]

- Renamed [ `/server_info` ] --> [ `/support server_info` ]

- Renamed [  `/announce` ] --> [ `/developer announce` ]

- Renamed [ `/development` ] --> [ `/developer development` ]

- Renamed [ `/bot_info` ] --> [ `/bot info` ]

- [ `/bot permission` ] new command that will show AvTech Support's TextChannel Permission

- [ `/developer announce` ] now is able to not Log the Announcement to the Bot's Logging Channel configured to AvTech Support

- Welcome Message when AvTech Support joins a Server has been improved to be more aesthetically pleasing

- When getting Data about a User, Server, Channel or Category, it'll be able to find Data via fetching if Data is not cached

- Reworked how Error Embeds for the Support Team looked once again to fit the aesthetic theme that is currently being deployed within AvTech Support

- Ticket Embeds now has Icon and Server name for further information + to make it personal

- [ `/main setup` ] now follows the new Discord UI for configuring Channels to make it less clunky and fluid

- Renamed [ `/review_suggestion` ] --> [ `/developer review_suggestion` ]

- [ `/developer review_suggestion` ] now has another option to react to Features that has been finished


### **Bugs and Typos**

- Patched a Bug that didn't allow Admin Roles *Configured to AvTech Support* to manage tickets that they're supposed to manage

- Patched a Bug where the information about a Server will be sent privately for Developers on Users when not using a force to display information

- Patched Changing Status not showing Number of Tickets that are active


### **Notices**

- I'm absolutely aware that 0.0.4 is a very exciting update that is being released which will help in stablising operations, bringing improved features and easy to use. Every updates or so, the Error Solutions will be changed to keep up with the better solutions as we review the inputs if there's an Unknown Error displayed.

- Whilst this update will take a long time, this may last on a span for 2 months and the other updates will arrive very slowly as I'm being forced to focus on School Project that I need to give in my best. 

-
------------------------------------------------------------------------
# ***AvTech Support Update Version 0.0.3[C]***

### **Bugs and Typos**

- Patched a Bug where Ticket Buttons wouldn't work when Admins or Ticket Support members would handle a ticket *that are configured to AvTech Support*

-
------------------------------------------------------------------------
# ***AvTech Support Update Version 0.0.3[B]***

### **Features**

- Improved member count for Developers in [ `/development` ]


### **Bugs and Typos**

- Patched Unknown Error Message when Ticket Information has been deleted

- If AvTech Support doesn't have perms to delete a ticket channel, it won't disable the ticket buttons at all.
    > It should not error out because it deleted the data already


### **Notices**

- Verification Feature is close to finishing and will be given to few Members for testing. If you're interested in testing the Verification System before it's going out to public, Let me know!

-
------------------------------------------------------------------------
# ***AvTech Support Update Version 0.0.3[A]***

### **Features**

- AvTech Support status will also include the number of active tickets


### **Bugs and Typos**

- Patched [ `/server_settings` ], it should work life a charm now

- Patched [ `/server_info` ] for Support Team and it should also work now as it was affected by the patch above

- Patched [ `/user_info` ], forgot to revert a change in it :D

- Patched all Ticket Features from not being able to be used by Server Owner and Server Admins [ `That are configured to AvTech Support` ]

- Fixed typos in [ `/bot_info` ] on Version, Permissions, and System Version

- Patched important bug where it'd ping @everyone in Bot Logging Channel when not required

-
------------------------------------------------------------------------
# ***AvTech Support Update Version 0.0.3***

### **Features**

- Efficient information checking with little bit of improvemance

- Changed AvTech Support Status to Watching *Number of Servers* Servers

- Added in more information to why people would get timed-out due to an Alpha Feature.

- Detailed Error Message and possible solutions in why the Command didn't work

- Server Admin Role and Server Owners can manage anyone's ticket include their own without any issues [ `Credits to: Felix.#2763` ]  *[  `Feature Request` ]*

- Every Announcement made using [ `/announce` ] by Developer will be sent to every Server Bot Logging Channel

    > No one will be pinged unless for important announcement where **@everyone** will be Pinged in the Bot Logging Channel that you set it.

    ```yaml
    I suggest that you give AvTech Support @everyone @here Permission in case there's an important Announcement that needs to be made that needs to be alerted.
    ```

- Another update for Timing out Users that first join the Spiral Ash Bots Server, this time you'll be timed out for only 5 minutes, if you get the Verification Code wrong, you'll get timed out for 15 minutes. 

- [ `/help` ] when sent in a Drop Down Menu, other Discord Members can interact with it as the Help Embeds are being sent privately

- [ `/help` ] page number button where first it was disabled *you weren't able to click*, now you can navigate to any part of the page saving you a lot of hassle!

- Simplified some of the Error Embeds to being simple

- If you have an active ticket but you can't View it, it'll automatically delete the information, however you'll have to click the Button again to make a ticket

- Improved description [ `/help` ] to better reliable reading as it kind of mis-leads the user able to use commands


### **Bugs and Typos**

- Patched [ `/help` ] navigation left button not displaying emoji at all

- Fixed wrong alignment in [ `/bot_info` ] for AvTech Support's Permission Displaying

- Patched bug that occured in the Missing Permissions Error Handler

- Patched wrong uptime information after 1 week of constant running due to Discord Reconnecting and firing events

-
------------------------------------------------------------------------
# ***AvTech Support Update Version 0.0.2[A]***

### **Features**

- Changed [ `/setup` ] option from ticket -> ticket_message_channel

- Updated [ `/help` ] to use the latest changed settings, *Will be patching any other information that are not up to date* 

### **Bugs and Typos**

- Patched [ `/update_settings` ] not updating settings as required and rewrote the system to be efficient however using more RAM as a consequence

- Patched error when joining Server, it won't send in the Welcome Message

- Patched [ `/setup` ] being broken and updating settings

-
------------------------------------------------------------------------
# ***AvTech Support Update Version 0.0.2***

### **Features**

- Reworked most of the Embed which will include Server PFP as the Icon and Users PFP as the thumbnail giving more of a aesthetic taste

- AvTech Support's status will change every 10 seconds or so counting how many Server it serves

- Verification Button now can be enabled Globally. You can set as much Buttons as you want, however there's a limit of 2 Buttons per Server. `Soon there'll be an Option to get more via Premium`
    > For **Testing Reasons**, this is not available to everyone however only for Few Servers which you'll get Information sent by the Bot in the Bot Logging Channel that you have setup. If this does not exist, you won't be able to Test the New Feature

- [ `/bot_info` ] will now Display if your Server is registered with AvTech Support

- Support Team at Spiral Ash Bots can now request to View Information about a Certain Server and the User has to be an Admin of the Server or the Server Owner to request to view the Permission

    > Only Developer of AvTech Support can request to view **Any Server Information** without the User requesting having to fit the Criteria

- [ `server_info` ] - Support of Spiral Ash Bots can use to see the Permission of the Bot in other Servers.

    > AvTech Support will see if the User is the Server Owner or Server Admin before sending in Data

- Fixed where Reactions of Voting for a Suggestion was not being added to Embed Messages in the Required Server

- Fixed few errors in the Developer Commands that didn't displayed the Number of Cogs enabled 

- Detailed Information on how many Cogs are and are not loaded for Developers

- [ `/announce` ] **Command for Developers Only** now has the ability to publish the Announced Message in Announcement Channels

- Welcome Message when AvTech Support joins a Server has been udpated that it'll inform the Owner to join the Spiral Ash Bots to check if the Server is eligible for Premium Features due to the Role Checking directly from the Spiral Ash Bots

- Better Checks for Text Channels to send the message when the AvTech Support joins the Server with slight Performance Improvement 

- Added in an Option to Change Support Cateogory in [ `/update_settings` ] *Nearly forgot about this*

### **Bugs and Typos**

- Patched the Error when if you accidentally delete the Category, it won't create ticket at all
    > This'll instead create the ticket channel at the highest heirachy making it the first thing that is visible. `This can be changed as soon as you create a Cateogory and set it up with AvTech Support`

-
------------------------------------------------------------------------
# ***AvTech Support Update Version 0.0.1***

### **Features**

- [ `/help` ] displays all the commands that can be used by the user. Support Users from Spiral Ash Bot can use their commands in any Server AvTech Support is in

- [ `/setup` ] can only be used by the Server Owner once when AvTech Support joins the Server
    > This'll send a Welcome Message informing the Server Owner on what AvTech Support can do

- [ `/update_settings` ] can be used by the Owner Only. *This will change in the later updates that Admins will be able to do the same thing* and will update certain settings

- AvTech Support will send all the Logs that it does to [ `Bot_Logging_Channel` ] that the Server Owner has setup.

- [ `Tickets` ] have persistent buttons now and if AvTech Support goes offline for some reason; Once it comes back online, The Ticket Buttons will start working

- [ `/server_settings` ] can be used Only by Server Owners and Server Admins and can view Server Settings configured for AvTech Support 

- [ `/bot_info` ] will show information such as: Ping, Server Support, Updated TOS, Update Version etc, AvTech Support Permissions, etc...

- [ `/user_info` ] shows user of choice information: When they created a Discord Account, When they joined the Server & Roles...

- [ `/suggestion` ] - Users can suggest Features in which Developers or Support Team will have a look and review it. If it's a feature that won't come, It'll be explained and why if necessary

- [ `/review` ] - Users can review either AvTech Support or other Projects done by Spiral Ash and give feedbacks

- [ `/delete_user-info` ] can be used by Admins and Server Owner which is a check to see if the User has an active ticket and will force delete if it can't find one. *Using this is less likely but an option in case an issue occurs*

- [ `/close` ] can be used only by Support Team in Spiral Ash to close Forum Posts

- Users when joining Spiral Ash Bots will be timed-out for 15 minutes instead of 30 minutes, including when getting the Answers wrong

### **Bugs and Typos**

- Patched Permission issue with Ticket Creator not having access to the Ticket found by [ `Motion` ]

- Patched another issue with Audit Log displaying full Message ID instead of the Message itself

------------------------------------------------------------------------
