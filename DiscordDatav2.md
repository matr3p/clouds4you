## Table of Content
* Legality
* Different ways to pull data
* Requirements


## Legality (PLEASE READ)
* As this will be done on a live machine/system, please ensure you are either authorized or legally bound for the access.

## Pre-Requisite
* Discord stores data in cloud, thus you'll have to extract the data to local so as not to tamper with live data.
* Discord doesn't have history limit, the only limit is your scrolling ability.

## Different ways to pull data
* 3rd Party Application (Discord History Tracker)
* Discord Application

## Requirements (3rd Party Application)
* Discord Credentials
* Discord 2FA (whenever enabled)
* Internet access Forensic Machine with the following application installed;
  - [X] [Discord History Tracker](https://dht.chylex.com/)

## Requirements (Discord Application via Service Provider)
* Target laptop/desktop with Discord application AND/OR
* Target mobile device with Discord application
* Internet access for targets
* Discord application has to be logged in
  - [X] Email account with its credentials that is linked to the Discord account

## Discord History Tracker
1. Download and Install `Discord History Tracker`.
2. Once installed, can create (individual) database for the case
<br/><br/>
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_history_tracker.PNG" width="800" />](./img/discord_history_tracker.PNG)
<br/><br/>
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_history_tracker_newDB.PNG" width="800" />](./img/discord_history_tracker_newDB.PNG)
<br/><br/>
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_history_tracker_application.PNG" width="800" />](./img/discord_history_tracker_application.PNG)
3. Launch `https://discord.com/login` on forensic machine.
4. Login either via credentials or QR code.
<br/><br/>
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_login.PNG" width="400" />](./img/discord_login.PNG)
5. You may be present with 2FA
<br/><br/>
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_2FA.PNG" width="400" />](./img/discord_2FA.PNG)
6. Upon logging in, navigate to Channels/DM that you want to export out.
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_dm.png" width="1000" />](./img/discord_dm.png)
7. In the `Discord History Tracker`, navigate to `Tracking` and click `Copy Tracking Script`.
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_history_tracking_script.PNG" width="800" />](./img/discord_history_tracking_script.PNG)
8. Open your browser console via `CTRL + SHIFT + I`, paste the script and press `Enter` to run it. A pop up will appear at the bottom of the browser.
<br/><br/>
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_history_tracker_setting.PNG" width="800" />](./img/discord_history_tracker_setting.PNG)
9. Click on the `Settings`. The capture settings will appear and you may set accordingly to your preference. Make sure `Autoscroll` is checked
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/dht_settings.PNG" width="800" />](./img/dht_settings.PNG)
10. Click on `Start Tracking` to capture the data. Once done, it will autopopulate the messages and it's channel(s) in the `Discord History Tracker` application.
  - [X] Note 1: Your discord has to be the active window for the tracking to happen.
  - [X] Note 2: If the channel has a lot of messages, be patient.
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_history_tracker_reach_end.PNG" width="800" />](./img/discord_history_tracker_reach_end.PNG)
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_history_tracker_total.PNG" width="800" />](./img/discord_history_tracker_total.PNG)
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_history_tracker_total2.PNG" width="800" />](./img/discord_history_tracker_total2.PNG)
11. Navigate to `Viewer` on `Discord History Tracker` application to view the data.
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_history_tracker_viewer.PNG" width="1000" />](./img/discord_history_tracker_viewer.PNG)
[<img src="https://github.com/matr3p/clouds4you/blob/main/img/discord_history_tracker_data.PNG" width="1000" />](./img/discord_history_tracker_data.PNG)
11. The 1st entry is the 1st message of the channel/DM.
  - [X] Note 1: You are able to filter by date/channel/user on the application.
  - [X] Note 2: You are able to view the total number of attachments downloaded and size, reattempt if failed and limit the attachment size.
  - [X] Note 3: Call/Video/Pinned Messages metadata are not captured. (Issue raised to developer)
  - [X] Note 4: All links/images/screenshots are dynamic, not static (need internet access to view).
  - [X] Note 5: Deleted messages/links/images/screenshots cannot be retrieved/captured.
  - [X] Note 5a: If messages/links/images/screenshots was captured before deletion, data will retain.
  - [X] Note 6: The application uses SQLite. You can use SQL to query or manipulate the database file.
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
