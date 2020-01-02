# GroupTinder

![GroupTinder](/images/login.png)

## What is GroupTinder?
GroupTinder allows you to outsource messaging your matches for whatever reason. You can add your friends to a match, and they can message on your behalf. The match on the other side will think the messages are coming from you.

Please use responsibly.

Home page | Chat
:--------:|:-------:
![Home Page](/images/home_page_blurred.png) | ![Chat](/images/matt_blurred.png)


## How does it work?
You login with your Facebook or Google accounts. Upon logging in, you'll be presented with the option to connect your Tinder account through SMS verification. This step is optional, but you'll only be able to see your own Tinder matches if you connect your Tinder.

![Connecting Tinder](/images/sms_verif.png)

After logging in, you will be taken to the home page. At first, this page will be empty, but as your friends add you to their matches, these matches will show up here. If you connect Tinder, your matches from the last 4 weeks will appear.

Initial home page | Home page
:--------:|:-------:
![Initial Home Page](/images/initial_home_page_2.png) | ![Home Page](/images/home_page_blurred.png)

You can now start messaging people and viewing their profiles!

![Sample conversation](/images/matt_blurred.png)

You can then add your friends to conversations on a match-by-match basis using the '+ Wyng' button on their profiles. This will bring up a prompt.

Match profile | Adding friends
:--------:|:-------:
![Match Profile](/images/match_profile_final.png) | ![Add friends](/images/add_friends_blurred.png)


Due to the nature of Tinder's access tokens, as well as security reasons, you must reconnect your Tinder via SMS authentication every 24 hours in order to be able to send messages from your Tinder account.

Happy Tindering!

# FAQ

### How does this work?
The app uses [fbessez's unofficial Tinder API](https://github.com/fbessez/Tinder), so huge shoutout to him! Grouptinder is built as a MERN (MongoDB, Express, React, Node) web-app.

### Does my match know who sent the message?
No, your match will see all messages as having been sent by you.

### Can I add people to matches that are not mine?
No.

### Why can I see everyone on the app when adding participants?
We originally intended to show only your Facebook friends, but this would require us to submit and pass an app review by Facebook, which is a lengthy process.

### Is there any way to make my token last more than 24 hours?
Not as of now, but in the future we might implement a way to make it last 60 days instead.

### This is unethical?
We hope people use this app respectfully and responsibly!


## Brought to you by:
n/a
