# React cheat sheet
- (Start)[]
## pre-Start
### create react app with redux template
```
npx create-react-app my-app --template redux
```
### Library
Router DOM
```
npm i react-router-dom
```
React-PDF
```
npm install @react-pdf/renderer
```

## Start
```
npm start
```
## App.js
### react-router-dom
```js
import { BrowserRouter, Routes, Route } from "react-router-dom";
```
```js
<BrowserRouter>
  <Routes>
    <Route index path="/home" element={<></>} />
    <Route path="/Make-certificate" element={<></>} />
  </Routes>
</BrowserRouter>
```

## Sass Style
install
```
npm i sass
```
file naming
```
nav.scss
```
use in react functional componant
```js
import "./nav.scss";
```
