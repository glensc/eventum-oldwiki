As the main page is not editable to add more contributions, add your contributions here:

Patches for Eventum 1.7.0
-------------------------

-   [Compact issue display](/Eventum:Compact_issue_display "wikilink") - **Implemented in 2.0** This patch removes line breaks between each subsection, moved "Back to top" link into header of each subsection.

-   [Associate new issues](/Eventum:Associate_new_issues "wikilink") - on the associate emails page, select only from open issues.

-   [Subject AND header based routing](/Eventum:Subject_AND_header_based_routing "wikilink") - fall back to header based routing if no issue \# found in subject

-   [Eventum:Hide_closed_issues_from_stats](/Eventum:Hide_closed_issues_from_stats "wikilink") - Pie charts only show issues with open status. <small>link may not be correct</small>

-   [Add a timeout for outgoing smtp connections 171](/Eventum:Add_a_timeout_for_outgoing_smtp_connections_171 "wikilink") - This adds an admin configurable timeout for smtp connections. It helps preventing the php script that processes the outgoing mail queue from getting stalled and never releasing its lock

-   [Defaulting Assigned Emails to Yes](/Eventum:Defaulting_Assigned_Emails_to_Yes "wikilink") - This fixes the fact users assigned to projects after being created do not get the proper defaults in reference to recieving emails when it is assigned to them

Patches for Eventum 2.0.1
-------------------------

-   [Hide Closed Issues on Stats (Main) Page](/Eventum:Hide_Closed_Issues_on_Stats_(Main)_Page "wikilink") - **Implemented in 2.1.X** This adds a "Hide Closed Issues" on the Stats / Main page and saves the preferences in user prefs and updates the local cookie. Designed to be included in Eventum Mainstream should the developers so choose.

-   [Add a timeout for outgoing smtp connections](/Eventum:Add_a_timeout_for_outgoing_smtp_connections "wikilink") - This adds an admin configurable timeout for smtp connections. It helps preventing the php script that processes the outgoing mail queue from getting stalled and never releasing its lock

-   [Open Source Project Mod](/Eventum:Open_Source_Project_Mod "wikilink") - Allows anonymous (non-registered) user access to tracker issues just like a regular user with configurable access.

-   [Custom reports from Tim Uckun](http://eventum.mysql.org/downloads/customreports.tgz) - Extra reports from Tim as described [here](http://lists.mysql.com/eventum-devel/611)

Patches for Eventum 2.1.1
-------------------------

-   [Eventum in Spanish](http://translate.unixlan.com.ar/es/eventum/eventum.po) - Eventum 100% translated into Spanish, thanks to the contributors of the [list](http://www.unixlan.com.ar/list/)
-   [Patch Reminder Repetition](/Eventum:Patch_Reminder_Repetition "wikilink") - This patch adds the possibility to specify a reminder repetition period. The reminder is repeated after the specified time.
-   [Limit Project Managers to Their Projects](/Eventum:Limit_Project_Managers_to_Only_Their_Projects "wikilink") - This mod will limit what a project manager can do in the Administration section.
    -   Managers can add / edit /update users only on the projects they manage.
    -   Managers can modify project parameters only on the projects they manage.
    -   Administrators can still do anything on any project.

Patches for Eventum 2.2
-----------------------

-   [Patch Reminder Repetition](/Eventum:Patch_Reminder_Repetition "wikilink") - This patch adds the possibility to specify a reminder repetition period. The reminder is repeated after the specified time.

Patches against Eventum daily build
-----------------------------------

-   [Enhanced FAQ part 1](/Eventum:Enhanced_FAQ_part_1 "wikilink") - Gives us two lists of FAQ-items in manage. One with not published FAQ-items, and one with published FAQ-items.

-   [Enhanced FAQ part 2](/Eventum:Enhanced_FAQ_part_2 "wikilink") - You MUST choose a project before editing FAQ-items. Remembers which project you choose.
