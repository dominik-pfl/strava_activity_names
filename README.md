# strava_activity_names
I want to build a tool which automatically renames activities when they are uploaded. Maybe with AI?


It works :) You can deploy it yourself, if you create a strava app wut the correct scope (write,activity:read_all) and use your credentials with .env_sample and change the document to "env"

### Target user story:
As a user I want the activty to be automagically and creativelly renamed when it is uploaded.

### Next steps: 
1. Build some sort of event listener, which triggers the renaming as soon as it is uploaded
2. Feed the activity information to a genAI API and ask for a creative name for this activity
