<h1>Twitch Authentication</h1>

The Twitch Authentication dialog box is shown below. The proceeding steps will walk you through configuring this section.

<img src="../img/auth_window_twitch.png" style="width: 400px;" />

## Bot Account
<h3>Set the Bot Name</h3>
On the Twitch Authentication dialog box, you'll need to specify the **name of the bot account**. Fill this in.

**Example:** If your bot account is named *CheeseBot* you'd enter that into this box.

<h3>Generate the OAuth Token</h3>
An OAuth Token is a secure method for allowing applications to access your account without providing the username or password. This protects your account as it is easily revoked and usually cannot modify your core account info (email, username, password, etc.).

To get your OAuth token, click the ***Generate Oauth-Token*** button at the bottom of the dialog. You will receive a message along these lines:  
<img src="../img/auth_window_twitch_oauth_bot_confirmation.png" style="width: 250px;" />

Clicking *Okay* will redirect you to the Twitch Authentication page in your web browser. Be sure you're authenticated with the right account  
<img src="../img/auth_window_twitch_oauth_bot_twitch.png" style="width: 75px;" />

Upon hitting "Authorize," you'll be redirected to the ScorpBot website (scorpware.ca) with your OAuth Token visible on the screen. Copy the token and paste it into the appropriate field in the Twitch Authentication dialog box.  
<img src="../img/auth_window_twitch_oauth_bot_token.png" style="width: 200px;" />

<h3>Set the channel in which it resides</h3>
Twitch's core chat technology is based off IRC, a very old and very reliable technology. Because of this, the chat channel the bot resides in must be indicated. Channels are based off usernames, preceded by a **#** sign.

So, if your username is **CheesyStreamer**, you'd put **#CheesyStreamer** in the Channel box.  
<img src="../img/auth_window_twitch_bot_complete.png" style="width: 400px;" />

## Streamer Account