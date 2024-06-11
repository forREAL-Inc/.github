# Getting Started
### Download
1. VScode
    - Clone web repo: https://github.com/forREAL-Inc/web
    - Install PostgreSQL by VScode>Extensions and typing it in or using the following link: https://marketplace.visualstudio.com/items?itemName=ckolkman.vscode-postgres
2. pgAdmin 4
    - Direct Download Link: https://ftp.postgresql.org/pub/pgadmin/pgadmin4/v8.7/macos/pgadmin4-8.7-arm64.dmg 
    - If pgAdmin 4 does not open go to Finder>PostgreSQL16 and click “Get Info” on pgAdmin 4. Then select “Open Using Rosetta”
    - Select "Add New Server" 
        * Name: Database
        * Host name/address: forreal-development.postgres.database.azure.com 
        * Port: 5432
        * Database: postgres
        * Username: find in onboard channel
        * Password: find in onboard channel
3. Xcode
    - Make an Apple ID account in the settings using your-name@for-real-inc.com. 
    - Download from App Store. For the billing information select “None” for your credit card choice, enter an address, and then download.
    - Select iOS 17.5 Simulator and MacOS
    - Clone iOS repo: https://github.com/forREAL-Inc/ios
    - Run build phone
        - Connect your phone to your computer using a cable. 
        - In the search bar select your device. If there is any pairing error go to Window > Devices& Simulator for instructions.
        - On your phone: Click trust on any popups for pairing the device. Make sure developer mode is turned on. Go to Settings>Privacy & Security>Developer Mode and select “On”. Your phone will have to restart. Select “Trust Device” again. If the Xcode warning still is showing errors, try unpairing and pairing the device again. This can be done by right clicking your device from the “Connected” column and selecting “Unpair Device”.
        - Press the Play button in the top left corner to build the app on your device. Any errors will be displayed by pressing the warning sign that appears next to the search bar. 
            * Team: First-name Last-name (Personal Team)
            * Bundle Identifier: com.for-real-inc.your
        - Settings>General>VPN & Device Management select “Trust” Apple Development: your-name@for-real-inc.com
        - The app should now appear on your phone
    - Going forward your device can build if its on the same wifi as your Mac without needing to be connected
 
4. Homebrew
  ```
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

  # if /opt/homebrew/bin is not in your PATH.
  (echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/arielfuchs/.zprofile
  eval "$(/opt/homebrew/bin/brew shellenv)"

  # NPM
  brew install npm
  ```
5. Microsoft 365 and Teams (optional)

