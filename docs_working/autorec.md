<div class="hts-doc-text">

The ‘Automatic Recorder’ is used to create rules that will trigger
automatic recording of events. You can use this to record you favorite
TV show(s), record all movies on a specific channel, etc.
It’s also possible to create a recording based on a query in the EPG.
For more information about that, please read the EPG chapter.

![](docresources/autorec.png)

The tags are listed / edited in a grid.

-   To edit a cell, double click on it. After a cell is changed it will
    flags one of its corner to red to indicated that it has been
    changed. To commit these changes back to Tvheadend press the ‘Save
    changes’ button. In order to change a Checkbox cell you only have to
    click once in it.
-   To add a new entry, press the ‘Add entry’ button. The new (empty)
    entry will be created on the server but will not be in its enabled
    state. You can now change all the cells to the desired values, check
    the ‘enable’ box and then press ‘Save changes’ to activate the new
    entry.
-   To delete one or more entries, select the lines (by clicking once on
    them), and press the ‘Delete selected’ button. A popup will ask you
    to confirm your request.

The columns have the following functions:

Enabled
If checked the rule is active. If unchecked the rule will not trig any
new recording sessions.
Title
Only matches events with the given title. The filter uses case
insensitive regular expression.
Channel
Only match events from the given channel.
Series Link
Checkbox indicates that a series link (using EPG provided info) is being
used, rather than a simple title match. The title field is still
populated, for clarity, with the title of the event used to create the
series link.
Channel tag
Only match events from the channels which are included in the given tag.
Tags are used for grouping channels and is configured by the
administrator.
Genre
Only match events belonging to the given content group.
Duration
Only match events that fall within the specified duration range.
Weekdays
Only record events if they occur on one of these days. By default all
days are marked as active.
Starting around
Only record events if they are scheduled +-15 minutes from this given
time.
Priority
The priority to give any recordings scheduled by this auto recording
rule.
DVR configuration
Select the DVR configuration profile to be used for scheduled
recordings.
Created by
Free text field, but will be copied to the recording session.
Comment
Free text field, not used for anything else.

</div>