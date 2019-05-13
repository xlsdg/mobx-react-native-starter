# Step

初始化项目：

```bash
react-native init MobxReactNativeStarter
```

修改 `package.json`：

```json
{
  "scripts": {
    "android": "react-native run-android",
    "android:log": "react-native log-android",
    "android:release": "react-native run-android --variant release",
    "ios": "react-native run-ios",
    "ios:device": "react-native run-ios --device",
    "ios:log": "react-native log-ios",
    "ios:release": "react-native run-ios --configuration Release",
    "lint": "eslint --ext .js src",
    "lint:fix": "eslint --fix --ext .js src",
    "prettier": "prettier --write './src/**/*.{js,jsx,ts,tsx,less,scss,css}'",
    "start": "react-native start --reset-cache",
    "test": "jest"
  }
}
```

添加导航：

```bash
yarn add react-navigation react-native-gesture-handler
react-native link react-native-gesture-handler
```

修改 `android/app/src/main/java/com/dvareactnativestarter/MainActivity.java` 文件：

参考：https://reactnavigation.org/docs/en/getting-started.html 或 https://kmagiera.github.io/react-native-gesture-handler/docs/getting-started.html

添加 `Mobx.js`：

```bash
yarn add mobx mobx-react mobx-state-tree
```
