------------------------------------------------------------------------
# ***AvTech Support Update Version 0.0.3[C]***

### **Bugs and Typos**

- Patched a Bug where Ticket Buttons wouldn't work when Admins or Ticket Support members would handle a ticket *that are configured to AvTech Support*

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


------------------------------------------------------------------------
# ***AvTech Support Update Version 0.0.2[A]***

### **Features**

- Changed [ `/setup` ] option from ticket -> ticket_message_channel

- Updated [ `/help` ] to use the latest changed settings, *Will be patching any other information that are not up to date* 

### **Bugs and Typos**

- Patched [ `/update_settings` ] not updating settings as required and rewrote the system to be efficient however using more RAM as a consequence

- Patched error when joining Server, it won't send in the Welcome Message

- Patched [ `/setup` ] being broken and updating settings

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
