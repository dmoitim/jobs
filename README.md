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

Instalar o VS Code, baixando o .deb do site e rodar o comando:
```sh
sudo apt install PACOTE.deb
```

Instalar o Chrome, baixando o .deb do site e rodar o comando:
```sh
sudo apt install PACOTE.deb
```

Instalar o NVM:
```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
```

Instalar a última versão LTS do node:
```sh
nvm install --lts
```

Indicar para o sistema utilizar essa versão:
```sh
nvm use --lts
```

Atualizar o NPM para a última versão estável:
```sh
npm install -g npm@latest
```

Instalar o JAVA 17 LTS:
```sh
sudo apt install openjdk-17-jdk
```

Instalar o Android Studio, baixado do site:
https://developer.android.com/studio

Descompacte o arquivo para a pasta do usuário, ficando:
```sh
/home/dmoitim/android-studio/
```

Execute o arquivo:
```sh
/home/dmoitim/android-studio/bin/studio.sh
```

Instale as SDKs sugeridas:
Next -> Next -> Finish

Ao término, clique em More Action -> SDK Manager, e na aba SDK Tools instale também:
- NDK (Side by Side)
- Android SDK Command-line Tools
- CMake

Abrir o arquivo:
```sh
vim.tiny ~/.bashrc
```

Incluir as linhas:
```sh
export ANDROID_HOME=/home/dmoitim/Android/Sdk
export PATH=${PATH}:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools
```