You need to download **VoiceAttack** first from: [Here](https://voiceattack.com/)

Then import the **marbles-Profile.vap** and **database.sql** file into your database.

I recommend creating a local database using xampp: [Here](https://www.apachefriends.org/download.html)

Do not forget to edit code to match database to your info in both **mydb.php** and **index.js** files.
Import **database.sql** via PHPmyAdmin.

Create **.env** file and put this:
`export TWITCH_OAUTH_TOKEN='oauth:yourtoken'`

You can get the token from: [Here](https://twitchapps.com/tmi/)

Edit cooldown in **index.js** labeled as ``COOLDOWNINSECONDS``

I will be working on automatizing this process via installer soon and updates.

I also included PHP admin panel you can access with xampp [here](http://localhost).

You will need ClientID too from Twitch Developer console. [Here](https://dev.twitch.tv/console)

I will be working on a tutorial.

You start it using:

`node index.js`

in command prompt you run as administrator.

Run VoiceAttack as Admin too.

To clone this repo, run:

`gh repo clone aezrath96/MarbleBot`

You need Node.js installed: [Here](https://nodejs.org/en/download/)

Download from releases: [Here](https://github.com/SwyftPain/MarbleBot/releases/)

Note:

Admin panel is optional, database is not.
