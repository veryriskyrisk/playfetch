# PlayFetch

## Description
This is an attempt to automate fetching of apps from Google Play app store.

## Prerequisites

* This needs to run either on an emulator or on a real device
* The device has to have Play Store already *setup* meaning that there has to be a user logged-in
* Some app vendors introduce country restrictions, in general central europe is blocked by many USA (or UK) vendors
* Even the websites (so the API endpoints) are blockd - use VPN
* Hint: best to get USA-based account but you'll need a friend with USA cell phone for that, last time I've checked
* `minSdk` is set to 29 for no good reason

## Installation & usage
Open the project in Android studio, it should build itself.
It's generally safe to update everything that Android Studio complains about, I'll try to keep up with dependencies if time will allow.

## Usage
Use examples liberally, and show the expected output if you can. It's helpful to have inline the smallest example of usage that you can demonstrate, while providing links to more sophisticated examples if they are too long to reasonably include in the README.

## Support
Tell people where they can go to for help. It can be any combination of an issue tracker, a chat room, an email address, etc.

## Roadmap
* 0.1.0 - initial version, 27 Oct 2023
* 0.2.0 - fetching first app from playstore
* 0.3.0 - fetching apps listed in a text/yaml/json/whatever file
* 0.4.0 - after successful fetch - script to copy files via adb to local filesystem?
* 0.5.0 - after successful fetch - script to copy files via adb to local filesystem?


## Contributing
Wanna join? Ping me!

## Authors and acknowledgment
Me, myself, and I

## License
GPLv3

## Project status
Not even a minimum viable at the moment.