I wanted to have my Wyze color strip update its colors, based on my Microsoft Teams status. 
...Why? 
Because I’m not the only human in my house during the summer, Christmas Break, snow days, random school days off, etc. and I am hoping to prevent awkward interruptions. So, I wanted the family to know if I am in a meeting(red) or available (green) by glancing at the colors of the lights around the door leading to my office. For me, this also serves the purpose of helping me know when I’ve accidentally left my status as “away” (yellow).
As of Feb 2022, I couldn’t find a readily available solution to get the data of my Teams' status from Teams, into Wyze. I've been enjoying this solution for a while now. Here's my no code solution!

# "Materials" needed
* PresenceLight
> https://presencelightapp.azurewebsites.net/
* IFTTT
> You'll need the low teir subscription if you want multiple color options and timely applets.
* Wyze account + Light Strip (Pro for my desk and standard strip for the door)

# Instructions
1. Download PresenceLight 
2. Login with the Microft Account you want to have changing your lights.
3. In IFTTT, link your Wyze account.
4. Next, create three <sarcasm> VERY complex </sarcasm> recipes:
* IF |receive a web request|
* THEN |Wyze| Change Color
* I reocmmend naming the web request events something useful like Teams_Red, Teams_Green, Teams_Yellow and set the Wyze light strip to the correlating color.
5. Find and gather your IFTTT URLs for the given action, you'll need them in the next step.
6. Go to PresenceLight, Configure Lights -> Configure a Custom API. Paste your links from IFTTT that "available" matches your green link, "busy" matches your read link, etc. This is a "POST" method to your IFTT URL.

# Summary
A change to your PresenceAPI will be picked up by PresenceLight, that status change will send to an IFTTT webhook, which then triggers a color change in your Wyze lights.
Have fun!

P.S. If you have Philips Hue, you can directly link your Philips Hue account with PresenceLight; no need for IFTTT.
