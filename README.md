# react-native-animated-switch

Lightweight switch implementation for Android and iOS.

## Demo

url: https://snack.expo.io/@zhangbao90s/animated-switch-v3

![React Native Animated Switch](https://raw.githubusercontent.com/baooab/react-native-animated-switch/main/animated-switch.gif)

## Install

Just copy `AnimatedSwitch.tsx`'s code from demo above to your project.

## Usage

```js
import AnimatedSwitch from './AnimatedSwitch';

<AnimatedSwitch value={false} onValueChange={(value) => console.log(value)} />;
```

## Props

| Prop          | Type     | Optional | Default value | Description                            |
| ------------- | -------- | -------- | ------------- | -------------------------------------- |
| value         | Boolean  | false    |               | Default state.                         |
| onValueChange | Function | false    |               | Trigger after switch state is changed. |
| width         | Number   | true     | 54            | Switch width.                          |
| height        | Number   | true     | 30            | Switch height.                         |
| onColor       | String   | true     | dodgerblue    | Active color.                          |
| offColor      | String   | true     | lightgray     | Inactive color.                        |

## License

MIT
