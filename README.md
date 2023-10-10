# Expo Router Example

Use [`expo-router`](https://expo.github.io/router) to build native navigation using files in the `app/` directory.

## 🚀 How to use

```sh
npx create-expo-app -e with-router
```

## 📚 Packages used
```sh
npm install expo-font axios react-native-dotenv
```

## 📚 After cloning the repository, run this command to install the packages locally
```sh
npm install
```

## 📚 Install eas to build
```sh
npm install --global eas-cli
```

## 📚 Install sharp-cli
```sh
npm install -g sharp-cli
```

## 📚 To build for android
```sh
npx eas build --platform android --local
```

## 📚 To upgrade packages
```sh
npx expo install --fix
```

Or to review and upgrade your dependencies

```sh
npx expo install --check
```

## 📚 Package used to run App on another wifi network
```sh
npm install -g expo-cli
```

## 🎆 Running App
```sh
expo-cli start --tunnel
```

## 📝 Notes

- [Expo Router: Docs](https://expo.github.io/router)
- [Expo Router: Repo](https://github.com/expo/router)

## Install
Fedora Linux 38
VS Code
NVM -> NodeJS LTS
Android Studio
-> Instalar a SDK, platform e cli

Javac:
sudo dnf install java-17-openjdk-devel.x86_64


Variáveis de ambiente:

nano ~/.bash_profile

Adiciona as linhas abaixo no final do arquivo:
export ANDROID_HOME=/home/dmoitim/Android/Sdk
export PATH=${PATH}:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools

source ~/.bash_profile

?? sdk.dir = /home/dmoitim/Android/Sdk