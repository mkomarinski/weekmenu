# weekmenu

## Automating your weekly meal planning

Ever get bored trying to figure out what to eat?  Or realize it's almost dinner time and nothing is ready so you're stuck with whatever is quick and simple?  Like to have more complex foods on days when you have more time to prepare a meal?  Ever want to have a set of recipes you like and have them automatically added to a Google Calendar that you can share with others?

Well you're in the right place.

This is a fork of another program which I've modified for my purposes.  I'll keep adding a bit more and add in the documentation so it's easier to set up but once that's done it should be pretty self-sufficient.

## Prerequisites

You'll need the following to set it up. If you're smarter than me you can probably do something different, but that's on you if it breaks.

* A Google Cloud [account](https://console.cloud.google.com/)
* A Google Sheet - this can be from your personal account
* A Google Calendar - this can be from your personal account
* Python 3
  * numpy
  * pandas
  * google-api-python-client
  * google-auth-httplib2
  * google-auth-oauthlib
  
## High level install

(A placeholder until I get real docs in here)

* Configure new Google Cloud project
* Generate service account and key
* Add key to local directory
* Share Sheet and Calendar with service account, give write access
* Populate Sheet with recipes
* Create intial event in Calendar
* Change config.sample to config.py
  * update IDs for spreadsheet and calendar
  * add/change any recurring days
  * configure range for spreadsheet
  
`python3 ./generate_weekmenu.py`
