# ideas

People tend to come up with - mostly useless - ideas. Instead of letting these ideas occupy a mind of mine, I scribe them in this repository.

## Rock-paper-scissors

* mobile
* multiplayer (both online and offline)
* rankings, tournaments
* statistics
* possibility of playing many games at the same time

## DelayFS

* provides files with a configurable (including random) delay
* might be useful for testing (e.g. testing responsiveness of user interface)
* possible usage: `delayfs /tmp/files /tmp/delayed_files`

## TodoFS

* tasks as directories
* mark done tasks using a starting dot in the name of a directory (`rm` would rename in this case)
* not-directories are regular files which are attachments to the task
* related idea: filesystem for Wunderlist or similar todo service

## Linkbin

* one-user web application to store URLs
* title + (URL xor text)
* use Google Authenticator or similar one-time password system

## Reading assistant

* keep a list of known words (by a user)
* find new words in a given text and let a user mark them as known or unknown (or use a scale: "I know a definition", "I intuitively understand", "I've seen this word", "It's completely new")
* generate flashcards with new words for a given text

## Tinder for food

* keep a list of ingredients in a house
* compare available dishes with a recipes database
* show possible dishes (sorted by calories or overall "quality" of a dish)

## Videos queue manager

Rationale: I follow some YouTube channels; I watch some TV series. I use tools to download them automatically. What I need is an app which could provide separated queues of videos to watch.

* possibility of sorting by date/length/popularity/custom function
* grouping multiple sources into one queue (possible queue names: "algorithms", "funny cats", "new music in the feed")
* find video with video length ≤ X (and search only in the first positions of the queues)
    * rationale: I often have got X minutes of free time and want to watch full video
* related to previous two points: mark a queue as with important order or not
* optionally: in case of TV series or movies, provide IMDb link (or event a description/rating in the UI!)

## Quick file uploader

* small tool to upload given file (or screenshot, or clipboard) to a server
* on success it prints (or copies to clipbaord) direct access URL

## Taskwarrior notifications

* notifies about (almost) overdue tasks
* generate PDF with tasks for a given day
