## Quickstart Guide

### 1. Get phones
To start, obtain two phones with a minium version of Android 7. The gold phones should be able to run Android 7 for certain.
  - To find the version just use search in the settings
  - If the version is less than 7 try updating but it may be stuck at 7
  - I recommend just continuing to check the other phones until you can get two to 7, otherwise see this [Github Issue](https://github.com/FIRST-Tech-Challenge/FtcRobotController/issues/700)

### 2. Install the APK
Choose one phone to be the Robot Controller, and one to be the Driver Station. Labelling these is probably a good idea. Go to ```github.com/FIRST-Tech-Challenge/FtcRobotController/releases/tag/v9.0.1``` on the phone and download the corresponding apk for the two different phones. Once downloaded open the file and make sure to allow this apk to do whatever it has to do.

### 3. Prep the Phones
#### Phone Cleanup and Prep (DO FOR BOTH PHONES)

1. If needed, select ```Settings > Accounts > Google > select > 3 dots > Remove account > confirm```. Repeat for any other accounts. Additionally, remove any non-FIRST Tech Challenge apps/games that might run in the background or attempt updates.
2. Force quit (swipe away) all apps, including the FTC apps.
3. Go to ```Apps > Settings > Wi-Fi```. Manually select and Forget any saved Networks.
4. Still in the WiFi menu navigate to Wi-Fi Direct menu (via More Settings or Advanced) and do the following:
    - Select and forget/disconnect any connections with Peer Devices, including the current phone pairing. This may take a few tries; OK to give up if disconnect not acknowledged.
      - If the top item shows ‘Created Group’, Disconnect it.
      - If you inadvertently create an Invitation pop-up on the other phone, Decline on the other phone and Cancel on this phone. In rare cases, the Invite prompt is underneath any open windows on the RC phone.
      - Pairing will be done later in the apps see Pairing
    - Select and Forget all Remembered Groups, including ANY phone pairings. (This can also be done from Advanced RC Settings from either app.) Your goal after steps 4.1 and     - 4.2 is ‘Not visible’, no ‘Peer devices’, and no ‘Remembered groups’.
    - Rename/Configure phone now to legal name, e.g. TEAMNUMBER-A-RC or TEAMNUMBER-RC. (This can also be done from Settings in each app.) ***(Finn here: For now put whatever name you want and ask David about this)***
    - Optional for Moto phones only: Configure device/Limit to 2 devices, set ‘Inactivity timeout’ to Never, check box ‘Auto connect remembered groups’. ***(Note: timeout is not persistent, re-check occasionally.)***
    - Force quit to device home screen. Swipe down twice from top, do this in order:
      - Airplane Mode ON
      - Wi-Fi ON (usually toggles off when Airplane Mode is turned on), then Done
      - Bluetooth OFF
      - Location OFF, only for Android 7.x

#### Pairing
1. On RC phone: open the current season’s RC app. Check Self Inspect for any RC issues.
2. On DS phone: open the current season’s DS app. Check Self Inspect for any DS issues.
3. On DS phone: Menu (3 dots)/Settings. Confirm ‘Pairing Method’ is Wi-Fi Direct. Open ‘Pair with Robot Controller’. (Do not pair using phone/Android menu.)
4. Filter can remain on, be patient and wait for the app to find the matching device. Or turn off Filter to see all devices within a few seconds. Choose the corresponding RC phone, touch Back, and Back again to return to the DS home screen.
5. Look at RC phone, accept the Invitation there. In rare cases, the Invite prompt is underneath any open windows on the RC phone. Pairing will happen within seconds.

### 4. Connect Computer to Driver Station

