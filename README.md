# My Basic Mac Mobile Developer Setup

This is my basic macOS setup for developing apps.

## Configuration:
- Setup global git config (user.name user.email)
- Install Felix Terminall (https://github.com/KrauseFx/what-terminal-is-felix-using)
- Setup SSH Kyes on GitHub and Bitbucket (https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/)

## Basic Developer Setup:
- Install Homebrew (https://brew.sh/index_pt-br.html)
- iTerm `brew install iterm2`
- Install GitFlow `brew install git-flow-avh`
- Fastlane `brew install fastlane`
- Install Visual Studio Code `brew install visual-studio-code`
- Install Postman - https://www.getpostman.com/downloads/
- Install Visual git client Fork - https://git-fork.com
- Install Gitmoji  `npm i -g gitmoji-cli`
- Install Pip `sudo -H python -m ensurepip`

### iOS:
- Install Xcode - https://apps.apple.com/br/app/xcode/id497799835?mt=12
- Install pod `sudo gem install cocoapods`
- Asset Catalog Creator - https://apps.apple.com/us/app/asset-catalog-creator-pro/id809625456?mt=12
- Install SimSim - https://github.com/dsmelov/simsim
- Instlal iOS Console app - https://lemonjar.com/iosconsole/ && libimobiledevice - `brew install --HEAD libimobiledevice`
- Install Dev Clenar (https://github.com/vashpan/xcode-dev-cleaner) - Clean a lot of space when you need it
- Install Realm Studio - https://realm.io/products/realm-studio
- If needed: Newer version of Xcode device support whitout upgrading Xcode - https://github.com/iGhibli/iOS-DeviceSupport
- Install Control room - https://github.com/twostraws/ControlRoom
- Install Poes - https://github.com/AvdLee/Poes

### Android:
- JDK `brew tap AdoptOpenJDK/openjdk; brew install adoptopenjdk8` || `brew install java`
- Install Android Studio - https://developer.android.com/studio/
- Setup Android Home (https://reactnative.dev/docs/environment-setup), after felix terminal
- Install Genymotion - https://www.genymotion.com/fun-zone/

## Flutter
- FVM - `brew tap dashixiong91/fvm && brew install fvm`
- Flutter without Metal (iOS) - https://github.com/acoutts/flutter-engines-no-metal

## React Native:
- Install Node Version Manager (brew install nvm)
- Make nvm default node with a soft link (Optional) - `ln -s $(which node) /usr/local/bin/node`
- Install Yarn Verson Manager `brew install yvm`
- Install Watchman `brew install watchman`
- Install React-native CLI - `npm install -g react-native-cli`
- Make lauchPackager.command run through iTerm instead of default Term
- Install Appcenter (mainly for codepush) -  `npm install -g appcenter-cli`
- Reactotron - https://github.com/infinitered/reactotron/releases

## Infrasctructure / Backend
- Install Heroku - `brew tap heroku/brew && brew install heroku`
- Install Sequel Pro (https://sequelpro.com/download)
- Install Firebase-hosting-cli `npm install -g firebase-tools`

## Others
- Install Google Chrome (https://www.google.com/chrome/browser/features.html)
- Install Slack (https://slack.com/downloads/) ou Franz
- Buy & Install Sip
- Quick Look Plugins (https://github.com/sindresorhus/quick-look-plugins) (qlimagesize, qlmarkdown, qlcolorcode)
- Install handbrake - https://handbrake.fr
- Sourcetree - `brew install sourcetree`
- Magnet - https://apps.apple.com/us/app/magnet/id441258766?mt=12
- Discord - https://discord.com/download
