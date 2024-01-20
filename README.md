# rnhw
hello world react-native app launch able on our computers

## how I was able to init and launch react-native project:

basic guide:
https://reactnative.dev/docs/environment-setup?guide=native&platform=android

### system: MacOS
### platform: Android

### node & nvm: lts/* or lts*iron atm

`nvm use lts/*`


### watchman
`brew install watchman`

### init java
`brew tap homebrew/cask-versions
brew install --cask zulu17

# Get path to where cask was installed to double-click installer
brew info --cask zulu17

export JAVA_HOME=/Library/Java/JavaVirtualMachines/zulu-17.jdk/Contents/Home`

### Android SDK

install it with Android Studio and setup environment variables:

`export ANDROID_HOME=$HOME/Library/Android/sdk
export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/platform-tools`

### init project

`
npm uninstall -g react-native-cli @react-native-community/cli
npx react-native@latest init rnhw
`

### run project

cd into project dir and

`npm run start`

this instruction allows me to start default react-native project