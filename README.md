# shopping-app
## Getting Started
Run ```npm install``` and ```expo start```
## If Getting 'TypeError: interpolate is not a function' in React-Native
* Reference: https://stackoverflow.com/questions/67840220/getting-typeerror-interpolate-is-not-a-function-in-react-native
1. Open the Drawer.js file found in /node_modules/react-navigation-drawer/lib/module/views/ folder
2. You will find interpolate in two places, replace the interpolate with interpolateNode in those two places.
3. Rebuild code
## Demo
https://user-images.githubusercontent.com/78141594/149455585-ef84cc2d-31f0-4984-9ae2-da428648bfd8.mp4
