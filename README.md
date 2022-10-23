# Date & Time Snippets

## About

Custom snippets with current time, relative dates and more

## How it works

## Unix date command

- Start reading from the purple object executing the `date` command.
- `date` is provided with a format argument and a params argument.
- Before the command is run, a locale is set to the environment

### Workflow object colours

- Yellow "Snippet" is in the "Primary locale"
- Yellow "Arg and Vars" adds a format in "Primary locale"
- Blue "Snippet" is in the "Secondary locale"
- Blue "Arg and Vars" adds a format in "Secondary locale" (default en_US)

### asdf

- The mindset is "localized", english is the sencond locale

## Changelog

v2

- Adapt to Alfred 5
- Add Readme

v1.8

- add english snippets dates: today, yesterday, etc.
- add a new variables: locale, tolower
- restructure workflow components (reuse set vars)
- add default values for variables
- remove manual clipboard workaround
- add previous week snippet

v1.7
added unix timestamp in seconds, "timestamp" (alias "ts")

v1.6
replace shared suffix with suffix on each trigger, due to interference with other workflows

v1.5
add 2 snippets for time: "time" (alias "t"), "now" (alias "n")

v1.4
add pbpaste and delay to restore clipboard contents

v1.3
add week
add alias "dd"

v1.2
add 7 snippets for upcoming weekdays

v1.1
add var:params
add snippet "igår"
add snippet "om90"
add external log

v1.0
imporve command line to output Swedish and lower case
add snippet "idag"
add snippet "datum"

v0.1
poc
add snippet "d"
