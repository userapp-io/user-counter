# User Counter for UserApp
This is the screen that we used at our launch to show the number of users on our account. And since it works for all UserApp accounts we decided to make it available for everyone that might be interested.

![Screenshot of the User Counter](https://raw.github.com/userapp-io/user-counter/master/screenshot.png)

## Setup
All it requires is this stand-alone HTML file. No other dependencies (except UserApp of course).

1. [Get a UserApp account](https://app.userapp.io/#/sign-up/)
2. Download and open index.html in a text editor
3. Insert your App Id and an API token at line 60
4. Open index.html in your browser

The counter now updates every 5 seconds and will "animate" the counter to the new number.

## Sounds
If you want a sound to be played each time the counter increases, put your .wav files in a folder namned "sounds" and add the names of the sounds too the sounds array (line 64):

    var sounds = ["sound1", "sound2"];

## Warning
Do not expose index.html publicly while it contains your API token. It can be used to access your entire UserApp account.

# License

	DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE

	Copyright (C) 2013 Timothy E. Johansson <timothy.johansson@userapp.io>

	Everyone is permitted to copy and distribute verbatim or modified
	copies of this license document, and changing it is allowed as long
	as you get more users.

	DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
	TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

	0. You just DO WHAT THE FUCK YOU WANT TO.
