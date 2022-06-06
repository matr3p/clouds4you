## Table of Content
* Legality
* Different ways to pull data
* Requirements


## Legality (PLEASE READ)
* As this will be done on a live machine/system, please ensure you are either authorized or legally bound for the access.

## Different ways to pull data
* Discord Web
* Discord Application

## Requirements (Web)
* Discord Credentials
* Discord 2FA (whenever enabled)
* [Discord Chat Viewer](https://dht.chylex.com/browser-only/build/viewer.html)
* Internet access Forensic Machine with the following installed as a browser addon;
  - [X] [Violentmonkey (Chrome)](https://violentmonkey.github.io/get-it/)
  - [X] [Tampermoney (Firefox, Edge, Chrome, Opera](https://www.tampermonkey.net/)
  - [X] Please note: Due to browser bugs / limitations, DHT will not work in Firefox with Greasemonkey / Violentmonkey, and in Safari at all
  - [X] [Userscipt](https://dht.chylex.com/browser-only/build/track.user.js)

## Requirements (Discord Application via Service Provider)
* Target laptop/desktop with Discord application AND/OR
* Target mobile device with Discord application
* Internet access for targets
* Discord application has to be logged in
- [X] Email account with its credentials that is linked to the Discord account

## Web Method
1. Launch `https://discord.com/login` on forensic machine.
2. Login either via credentials or QR code.
<br/><br/>
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_login.PNG" width="400" />](./img/discord_login.PNG)
3. You may be present with 2FA
<br/><br/>
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_2FA.PNG" width="400" />](./img/discord_2FA.PNG)
4. Upon logging in, navigate to Channels/DM that you want to export out. Notice that `DHT` is present on top right screen
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_dm.png" width="1000" />](./img/discord_dm.png)
5. Click on the `DHT`. The capture settings will appear and you may set accordingly to your preference
Make sure `Autoscroll` is checked
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/dht_settings.PNG" width="800" />](./img/dht_settings.PNG)
6. Click on `Start Tracking` to capture the data. Once done, it will autopopulate the messages and it's channel(s). Download the file.
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/track_download.png" width="800" />](./img/track_download.png)
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/track_download2.png" width="800" />](./img/track_download2.png)
7. The downloaded file will be named `dht.txt`. Do note that this file is in JSON format
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/dht_txt_file.PNG" width="400" />](./img/dht_txt_file.PNG)
8. Navigate to [Discord Chat Viewer](https://dht.chylex.com/browser-only/build/viewer.html)
9. Load the `dht.txt` file
10. Congrats! You're able to view the data!
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/view_data.PNG" width="1000" />](./img/view_data.PNG)
11. You may download the webpage or do a Save-As for offline copy, else the already downloaded JSON copy
12. Log out of account after use.

## Application Method (via Service Provider)
1. Launch Discord Application and login if necessary
2. Proceed with screen capture with tools of choice else you may do the alternative;
3. Navigate to user settings on the `bottom left screen`.
<br/><br/>
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/settings.png" width="400" />](./img/settings.png)
4. Navigate to `Privacy & Safety` under `User Settings` and scroll to the bottom to `Request all of my Data`
<br/><br/>
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/privacy_safety.png" width="400" />](./img/privacy_safety.png)
5. Click `Request Data`.
<br/><br/>
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/request_data.png" width="400" />](./img/request_data.png)
6. Data will be packaged and be available via email that is linked to the Discord account, once ready.
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/data_requested.PNG" width="400" />](./img/data_requested.PNG)
7. You may download the data via the linked email account

Same methodology can be applied on Discord mobile application
<br/>
8. Launch Discord Application and login if necessary
<br/>
9. Navigate to user settings on the `bottom right screen`
<br/>
10. Navigate to `Privacy & Safety` and scroll to the bottom to `Use data to make Discord work`
<br/>
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/mobile_discord_setting.png" width="200" />](./img/mobile_discord_setting.png)
<br/><br/>
11. Click `Request Data`.
<br/><br/>
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/mobile_discord_request_data.png" width="200" />](./img/mobile_discord_request_data.png)
<br/><br/>
12. Data will be packaged and be available via email that is linked to the Discord account, once ready.
<br/>
13. You may download the data via the linked email account
