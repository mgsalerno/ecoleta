# Ecoleta

>Application developed during the 1st Next Level Week, an event held by [RocketSeat](https://rocketseat.com.br/).

![](https://www.dropbox.com/s/o1bov5yxa2l0f9q/cover-ecoleta.png?raw=1)

The Ecoleta app works as a map, a marketplace and a connection between companies or entities that collect waste (organic and inorganic) and people who need to dispose of this waste.

## Installation

### JavaScript runtime environment Node.js

Linux (Ubuntu based distributions):
```sh
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install -y nodejs
```

Linux (Debian based distributions):
```sh
curl -sL https://deb.nodesource.com/setup_12.x | bash -
apt-get install -y nodejs
```

OS X (using [Homebrew](https://brew.sh/)):
```sh
brew install node@12
```

Windows (using [Chocolatey](https://chocolatey.org/)):
```sh
cinst nodejs-lts
```

To verify if the installation was successful, just type `node -v` to get the Node.js version and `npm -v` to get the npm version.

## Development setup

In the folders `server`, `web` and `mobile`, execute the following command to install all dependencies of the project:
```sh
npm install
```

To run the server, just execute `npm run dev` in the `server` folder.

To run the web client execute `npm start` in the `web` folder and a browser window will open with the web client running.

For the mobile app it's necessary to execute `npm start` in the `mobile` folder and read the QrCode that popped up in a browser window (it's also available at the terminal) with the Expo app in your phone and wait for the app to load. If you are using an Android emulator with Android Studio or an iOS emulator with XCode, you can click on the `Run on Android device/emulator` or `Run on iOS emulator` in the browser window and the app will start to load.

The Expo app is available for Android: 

```sh
play.google.com/store/apps/details?id=host.exp.exponent
```

and iOS:

```sh
apps.apple.com/app/expo-client/id982107779
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
