# How I Automate User Unlocks

One of the most common requests I get is:  
_"User X is locked out, please unlock their account."_

Instead of doing this manually, I wrote a PowerShell script that:

- Checks AD lock status
- Unlocks the account
- Sends a Slack/Email confirmation to the requester

It takes 3 seconds. Multiply that by 20 tickets a day...

**Silent power.**
