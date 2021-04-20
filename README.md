## Installation

```
npm i react-native-media-modal --save
```

### or

```
yarn add react-native-media-modal
```

## Props

| Prop             | Type     | Description                                              | Default                    |
| ---------------- | -------- | -------------------------------------------------------- | -------------------------- |
| title            | string   | Media Modal Content Title                                | ""                         |
| message          | string   | Media Modal message                                      | ""                         |
| showMedia        | boolean  | Display Media Block                                      | true                       |
| mediaImage       | boolean  | Load Image on Media Block or Webview                     | true                       |
| mediaURL         | string   | Url from Image or Video Embebed if you use Webview       | true                       |
| showCancel       | boolean  | Show a Cancel button                                     | true                       |
| showConfirm      | boolean  | Show a Confirm button                                    | true                       |
| textCancel       | string   | Text display on Cancel button                            | "No"                       |
| textConfirm      | string   | Text display on Confirm button                           | "Yes"                      |
| backdropClose    | boolean  | Close Media Modal when press on mask                     |
| useNativeDriver  | boolean  | Allowing native code to perform the animation            | false                      |
| customStyles     | object   | Custom style to AlertPro                                 | {}                         |
| onCancel         | function | Event on Cancel button                                   | null                       |
| onConfirm        | function | Event on Confirm button                                  | null                       |
| onClose          | function | Callback function when modal has closed                  | null                       |

### Available Custom Style

```jsx
customStyles: {
  BackgroundMask: {...}, // Backdrop mask 
  container: {...}, // Modal container 
  title: {...}, // Content title
  message: {...}, //Message text
  media: {...}, // Media 
  closeButton: {...}, // Close button
  closeButtonIcon: {...}, // Close button Icon
  buttonCancel: {...} // Cancel Button
  textButtonCancel: {...} // Cancel Button Text
  buttonConfirm: {...} // Confirm button
  textButtonConfirm: {...} // Confirm button's Text
}
```