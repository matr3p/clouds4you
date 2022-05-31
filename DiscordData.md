## Table of Content
* Legality
* Different ways to pull data
* Requirements


## Legality
PLEASE READ
As this will be done on a live machine/system, please ensure you are either authorized or legally bound for the access.

## Different ways to pull data
* Discord Web
* Discord Application

## Requirements (Web)
* Discord Credentials
* Discord 2FA (whenever enabled)
* [https://dht.chylex.com/browser-only/build/viewer.html](#Discord Chat Viewer)
* Internet access Forensic Machine with the following installed as a browser addon;
* [https://violentmonkey.github.io/get-it/](#Violentmonkey (Chrome))
* [https://www.tampermonkey.net/](#Tampermoney (Firefox, Edge, Chrome, Opera)
* Please note: Due to browser bugs / limitations, DHT will not work in Firefox with Greasemonkey / Violentmonkey, and in Safari at all
* [https://dht.chylex.com/browser-only/build/track.user.js](#Userscipt)

## Requirements (Discord Application)
* Target laptop/desktop with Discord application AND/OR
* Target mobile device with Discord application
* Internet access for targets
* Discord application has to be logged in

## Web Method
1. Launch `https://discord.com/login` on forensic machine.
2. Login either via credentials or QR code.
![Discord Login](./img/blob/main/discord_login.PNG)
3. You may be present with 2FA
![Discord 2FA](./img/blob/main/discord 2FA.PNG?raw=true "Discord 2FA")
4. Upon logging in, navigate to Channels/DM that you want to export out. Notice that `DHT` is present on top right screen
![DHT](./img/blob/main/discord dm.png?raw=true "DMs")
5. Click on the `DHT`. The capture settings will appear and you may set accordingly to your preference
Make sure `Autoscroll` is checked
![DHT Settings](./img/blob/main/dht settings.PNG?raw=true "DHT Settings")
6. Click on `Start Tracking` to capture the data. Once done, it will autopopulate the messages and it's channel(s). Download the file.
![Download data](./img/blob/main/track %26 download.png?raw=true "Download data)
![Download data](./img/blob/main/track %26 download2.png?raw=true "Download data)
7. The downloaded file will be named `dht.txt`. Do note that this file is in JSON format
![DHT file](./img/blob/main/dht txt file?raw=true "DHT file")
8. Navigate to [https://dht.chylex.com/browser-only/build/viewer.html](#Discord Chat Viewer)
9. Load the `dht.txt` file
10. Congrats! You're able to view the data!
![View Data](./img/blob/main/view data.png?raw=true "View Data")
11. You may download the webpage or do a Save-As for offline copy, else the already downloaded JSON copy
12. Log out of account after use.

## Application Method
To DO
