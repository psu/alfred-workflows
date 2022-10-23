# Date & Time Snippets

[⤓ Download Workflow]()

## About

Adds a list of custom snippets with current date, time, relative dates, and more to Alfred.

## How it works

## Unix date command

- Start reading from the purple object executing the `date` command.
- `date` is provided with two arguments: `format` and `params`.
- Before the command is run, a `locale` is set to the environment.
- `format` specifies the output format. For exampel the order between day and month.
- `params` specifies what date to use. If it's not blank, todays date will be used.

### Workflow object colours

- Yellow "Snippets" defines a snippet in the "Primary locale".
- Yellow "Arg and Vars" sets variable `format` aligned to "Primary locale".
- Blue "Snippets" defines a snippet in the "Secondary locale".
- Blue "Arg and Vars" sets variable `format` aligned to "Secondary locale".
- Gray "Arg and Vars" sets variable `params` to define a date (used by all locales).
- Purple "Arg and Vars" sets variable `format` to a format used by all locales.
- Red objects are used to execute the command and output the result.

## Changelog

v2.0

- adapt to Alfred 5
- add Readme

v1.8

- add english snippets dates: today, yesterday, etc.
- add a new variables: locale, tolower
- restructure workflow components (reuse set vars)
- add default values for variables
- remove manual clipboard workaround
- add previous week snippet

v1.7

- added unix timestamp in seconds, "timestamp" (alias "ts")

v1.6

- replace shared suffix with suffix on each trigger, due to interference with other workflows

v1.5

- add 2 snippets for time: "time" (alias "t"), "now" (alias "n")

v1.4

- add pbpaste and delay to restore clipboard contents

v1.3

- add week
- add alias "dd"

v1.2

- add 7 snippets for upcoming weekdays

v1.1

- add var:params
- add snippet "yesterday"
- add snippet "90d"

v1.0

- improve command line to output localized and lower case
- add snippet "today"
- add snippet "date"

v0.1

- poc
- add snippet "d"
