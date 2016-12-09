alfred-reminders
================

This creates a new reminder in Reminders.app

Download the latest version, for Alfred v3 and macOS

More information at [Alfred Forums](http://www.alfredforum.com/topic/917-reminders/)

## Usage
To use, just type `r <some text>` into Alfred.

For example, `r check out some of Alfred's other workflows` will create a new reminder called "check out some of Alfred's other workflows". 

You can also include times and dates in the text and have Alfred set a reminder for that particular time.

`r this` will capture the current application and turn it into a reminder.

### Dates
To be reminded at a specific date/time, simply type a date into the command, for example:

- `r today release the hamsters into the wild`
- `r tomorrow bring about financial ruin upon my enemies`
- `r in 5 minutes drop everything`
- `r in 2 hours laugh out loud`
- `r on 24/12/13 forget everything I know about things in movies`
- `r on 12 June 15 come up with some interesting ideas`
- `r on 31-12-99 23:22 panic about the millennium bug`
- `r at 2pm to wait for nothing in particular`
- `r next thursday at 15.30 ask some difficult questions`

### Priority

To set the priority of the reminder, either use exclamation marks right at the start or end of the command (`!` for low priority, `!!` for medium priority, `!!!` for high priority), or type the priority right at the end of the command (these can also be abbreviated, for example `mp` or `p lo`). For example:

- `r !!! in 2 weeks an important meeting`
- `r thursday have a banana medium priority`
- `r decide what to have for lunch !lo`
- `r make a turkey sandwich p3`

### Apps
Get reminded about the app you're using, for example the selected file in Finder, or the current tab in Chrome or Safari.

To create a reminder about the active app, simply type `r this`. Or keep typing to set a date, priority or a custom title, for example `r this drop some sick beats on Friday !!!`.

The following apps are currently supported:

- Adobe Acrobat (Pro/DX)
- Chromium
- Contacts
- Finder
- FoldingText
- Google Chrome
- Google Chrome Canary
- Mail
- Microsoft PowerPoint
- Microsoft Word
- Safari
- TextEdit
- TextMate
- Vienna
- WebKit

Apps can be added on request. Just [raise an issue](https://github.com/surrealroad/alfred-reminders/issues/new) with the app you use. As long as it's freely available and has AppleScript support, it can be added.

### Getting help

`r help` will display the above examples

All sorts of combinations are possible!

### Configuration
If you want to change the default reminder list, edit the variables component at the top of the workflow, otherwise it will just use the first one (unless you use "in Y list" at the end).

### Building from source
In Alfred create a new Blank Workflow, then right-click and choose Open In Finder. Then replace all the files with this source.

## Acknowlegdements
Date parsing is done via [chrono.js](https://github.com/wanasit/chrono)

Uses icons from the Flurry collection by David Lanham / The Icon Factory
