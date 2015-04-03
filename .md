![Welcome Screen](Eventum-Profile.jpg "fig:Welcome Screen") Eventum is a user-friendly and flexible issue tracking system that can be used by a support department to track incoming technical support requests, or by a software development team to quickly organize tasks and bugs.

* * * * *

The Eventum project is hosted on [Launchpad](https://launchpad.net/eventum/).

The source code is available through the [GPL license](Eventum:License "wikilink").

Browse the [Eventum source](https://code.launchpad.net/~eventum-developers/eventum/trunk)

You can download the dev source directly from [Launchpad](https://launchpad.net/eventum) using [Bazaar](http://bazaar-vcs.org).


`bzr clone lp:eventum`

* * * * *

Documentation
-------------

-   Installation
    -   Before you start, check the [prerequisites](Eventum:Prerequisites "wikilink") for Eventum.
        -   [System Requirements](Eventum:Prerequisites#System_Requirements "wikilink")
            -   [Checking PHP Requirements](Eventum:Prerequisites#Checking_PHP_Requirements "wikilink")
                -   [Via the Command Line](Eventum:Prerequisites#Via_the_Command_Line "wikilink")
                -   [Via the Web](Eventum:Prerequisites#Via_the_Web "wikilink")
    -   [Download](http://dev.mysql.com/downloads/other/eventum/)
    -   **[Doing a fresh install](Eventum:Doing a fresh install "wikilink")**
        -   [Installation Process](Eventum:Doing_a_fresh_install#Installation_Process "wikilink")
        -   [Scheduled Tasks](Eventum:Doing_a_fresh_install#Scheduled_Tasks "wikilink")
            -   [Mail Queue Process (crons/process_mail_queue.php)](Eventum:Doing_a_fresh_install#Mail_Queue_Process_.28misc.2Fprocess_mail_queue.php.29 "wikilink")
            -   [Email Download (crons/download_emails.php)](Eventum:Doing_a_fresh_install#Email_Download_.28misc.2Fdownload_emails.php.29 "wikilink")
            -   [Reminder System (crons/check_reminders.php)](Eventum:Doing_a_fresh_install#Reminder_System_.28misc.2Fcheck_reminders.php.29 "wikilink")
            -   [Heartbeat Monitor (crons/monitor.php)](Eventum:Doing_a_fresh_install#Heartbeat_Monitor_.28misc.2Fmonitor.php.29 "wikilink")
        -   [Other Features Requiring System Setup](Eventum:Doing_a_fresh_install#Other_Features_Requiring_System_Setup "wikilink")
            -   [Email Routing Script (crons/route_emails.php)](Eventum:Doing_a_fresh_install#Email_Routing_Script_.28misc.2Froute_emails.php.29 "wikilink")
            -   [Note Routing Script (misc/route_notes.php)](Eventum:Doing_a_fresh_install#Note_Routing_Script_.28misc.2Froute_notes.php.29 "wikilink")
            -   [IRC Notification Bot (misc/irc/bot.php)](Eventum:Doing_a_fresh_install#IRC_Notification_Bot_.28misc.2Firc.2Fbot.php.29 "wikilink")
            -   [Command Line Interface (misc/cli/eventum)](Eventum:Doing_a_fresh_install#Command_Line_Interface_.28misc.2Fcli.2Feventum.29 "wikilink")
        -   [Installing on SSL (https)](Eventum:Doing_a_fresh_install#Installing_on_SSL_.28https.29 "wikilink")
        -   [Installing with PHP on FastCGI](Eventum:Doing_a_fresh_install#Installing_with_PHP_on_FastCGI "wikilink")
    -   [Upgrading](Eventum:Upgrading "wikilink")
    -   Installation Notes
        -   [Linux based systems](Eventum:Installation notes for Linux based Systems "wikilink")
            -   [Slackware 12.0](Eventum:Installation_notes_for_Linux_based_Systems#Slackware_12.0 "wikilink")
            -   [Ubuntu 5.10](Eventum:Installation_notes_for_Linux_based_Systems#Ubuntu_5.10 "wikilink")
            -   [Fedora_Core 4](Eventum:Installation_notes_for_Linux_based_Systems#Fedora_Core_4 "wikilink")
            -   [Debian Linux](Eventum:Installation_notes_for_Linux_based_Systems#Debian_Linux "wikilink")
            -   [gettext and Translation](Eventum:Installation_notes_for_Linux_based_Systems#gettext_and_Translation "wikilink")
        -   [PLD Linux](Eventum:Installation notes for PLD Linux "wikilink")
        -   [FreeBSD](Eventum:Installation notes for FreeBSD 4.x "wikilink")
        -   [Windows](Eventum:Installation notes for Windows "wikilink")
            -   [Allowing file uploads](Eventum:Installation_notes_for_Windows#Allowing_file_uploads "wikilink")
            -   [Setting up Windows Task Scheduler (for sending email queue or downloading new emails)](Eventum:Installation_notes_for_Windows#Setting_up_Windows_Task_Scheduler_.28for_sending_email_queue_or_downloading_new_emails.29 "wikilink")
            -   [Solving 'CGI Timeout'](Eventum:Installation_notes_for_Windows#Solving_.27CGI_Timeout.27 "wikilink")
            -   [Solving 'pages do not refresh'](Eventum:Installation_notes_for_Windows#Solving_.27pages_do_not_refresh.27 "wikilink")
        -   [NetWare](Eventum:Installation notes for NetWare "wikilink")
        -   [Shared Hosting](Eventum:Installation notes for shared hosts "wikilink")
-   [FAQ](Eventum:FAQ "wikilink")
    -   [Troubleshooting](Eventum:FAQ#Troubleshooting "wikilink")
    -   [Setup](Eventum:FAQ#Setup "wikilink")
    -   [General Usage](Eventum:FAQ#General_Usage "wikilink")
-   Usage
    -   [How issues are handled in Eventum](Eventum:How issues are handled in Eventum "wikilink")
    -   [Creating Issues](Eventum:Creating Issues "wikilink")
    -   [Working with Issues](Eventum:Working with Issues "wikilink")
    -   [Listing Issues](Eventum:Listing Issues "wikilink")
    -   [Editing Preferences](Eventum:Editing Preferences "wikilink")
-   Features
    -   [Projects](Eventum:Projects "wikilink")
    -   [Users](Eventum:Users "wikilink")
        -   [Import Users](Eventum:Import Users "wikilink")
    -   [Email integration](Eventum:Email integration "wikilink")
    -   Administration
        -   [General Setup](Eventum:General Setup "wikilink")
            -   [Tool Caption](Eventum:General_Setup#Tool_Caption "wikilink")
            -   [SMTP (Outgoing Email) Settings](Eventum:General_Setup#SMTP_.28Outgoing_Email.29_Settings "wikilink")
            -   [Open Account Signup](Eventum:General_Setup#Open_Account_Signup "wikilink")
            -   [Subject Based Routing](Eventum:General_Setup#Subject_Based_Routing "wikilink")
            -   [Email Recipient Type Flag](Eventum:General_Setup#Email_Recipient_Type_Flag "wikilink")
            -   [Email Routing Interface](Eventum:General_Setup#Email_Routing_Interface "wikilink")
            -   [Note Recipient Type Flag](Eventum:General_Setup#Note_Recipient_Type_Flag "wikilink")
            -   [Internal Note Routing Interface](Eventum:General_Setup#Internal_Note_Routing_Interface "wikilink")
            -   [Email Draft Interface](Eventum:General_Setup#Email_Draft_Interface "wikilink")
            -   [SCM Integration](Eventum:General_Setup#SCM_Integration "wikilink")
            -   [Email Integration Feature](Eventum:General_Setup#Email_Integration_Feature "wikilink")
            -   [Daily Tips](Eventum:General_Setup#Daily_Tips "wikilink")
            -   [Email Spell Checker](Eventum:General_Setup#Email_Spell_Checker "wikilink")
            -   IRC Notifications
            -   [Allow Un-Assigned Issues?](Eventum:General_Setup#Allow_Un-Assigned_Issues.3F "wikilink")
            -   [Options for Notifications](Eventum:General_Setup#Default_Options_for_Notifications "wikilink")
            -   [Email Reminder System Status Information](Eventum:General_Setup#Email_Reminder_System_Status_Information "wikilink")
            -   [Email Error Logging System](Eventum:General_Setup#Email_Error_Logging_System "wikilink")
        -   [Manage Link Filters](Eventum:Manage Link Filters "wikilink")
        -   [Become Super-Administrator](Eventum:Become Super-Administrator "wikilink")
        -   [Creating and Managing Projects](Eventum:Creating and Managing Projects "wikilink")
    -   Email Routing Interface
        -   [Setting up email routing with Sendmail](Eventum:Setting up email routing with Sendmail "wikilink")
        -   [Setting up email routing with qmail](Eventum:Setting up email routing with qmail "wikilink")
        -   [Setting up email routing with postfix](Eventum:Setting up email routing with postfix "wikilink")
        -   [Setting up email routing with exim](Eventum:Setting up email routing with exim "wikilink")
        -   [Setting up email routing with 1 email account for multiple projects](Eventum:Setting up email routing with 1 email account for multiple projects "wikilink")
    -   [Reporting System](Eventum:Reporting System "wikilink")
    -   [RSS feeds](Eventum:RSS feeds "wikilink")
    -   Configuration
        -   [Setting up fulltext searching](Eventum:Setting up fulltext searching "wikilink")
        -   [Extending and Integrating Eventum](Eventum:Extending and Integrating Eventum "wikilink")
        -   [Adding a cron entry](Eventum:Adding a cron entry "wikilink")
    -   Miscellaneous
        -   [Using the IRC bot](Eventum:Using the IRC bot "wikilink")
        -   [Deleting Issues](Eventum:Deleting Issues "wikilink")
        -   [Fulltext Search](Eventum:Fulltext Search "wikilink")
-   Development Related
    -   [Changelog](Eventum:Changelog "wikilink")
    -   [Roadmap](Eventum:Roadmap "wikilink")
    -   [Localization](Eventum:Localization "wikilink")
    -   [Workflow API](Eventum:WorkflowDocumentation "wikilink")
        -   [Workflow Examples](Eventum:WorkflowExamples "wikilink")
    -   [Custom Fields](Eventum:Custom Fields "wikilink")
        -   [Custom Field API](Eventum:CustomFieldAPI "wikilink")
        -   [Dynamic Custom Field Example](Eventum:DynamicCustomFieldExample "wikilink")
    -   [Pending Contributions](Eventum:Pending_Contributions "wikilink") (not yet merged into Eventum)
    -   [How to Contribute to the Project](Eventum:HowToContribute "wikilink")
    -   [Article on setting up LDAP Authentication in Eventum](http://www.bieberlabs.com/wordpress/archives/2007/10/20/ldap-enabling-the-eventum-defect-tracking-system/)
-   Debugging Problems
    -   [Displaying PHP errors](Eventum:Displaying PHP errors "wikilink")
-   Presentations
    -   [Houston PHP / MySQL Meetup (June 3 2005)](http://eventum.mysql.org/meetup_presentation.ppt) - Eventum presentation

Asking Questions
----------------

To ask questions or get more information please join/mail our mailing list: <http://lists.mysql.org/#eventum>