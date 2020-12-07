# react-fb-image-grid
An image library that's used to show the images in beautiful grids.

Below you will find some information on how to perform common tasks.<br>


## Table of Contents

- [What's new](#whats-new)
- [Installation](#installation)
- [Props](#props)
- [Pull Requests](#pr)
- [License](#license)


## What's new `v0.1.2`

Overlay Counts added for more than 5 images.


## Installation

Run the following
```
npm install react-fb-image-grid
```
or
```
yarn add react-fb-image-grid
```


## Props

Props | Type | Default | Example
:--- | :---: | :---: | :---
images | Array (String) | **required** | `{['https://some-url.com/image.jpg', importedImage]}` `//Local image should be imported first`
width | Number | auto | `{100}` `//Package consider this as percent`
countFrom | Number | 5 | `{2}`  `//Should be from 1 to 5`
hideOverlay | Boolean | false | `{true}`
renderOverlay | Function | `() => 'Preview Image'` | `{() => <button>Show Image</button>}`
overlayBackgroundColor | String | `#222222` | `'green'` or `'#000000'` or `'rgb(255, 26, 26)'`
onClickEach | Function | null | `{({src, index}) => {}}`


## Pull Requests

Feel free to make Pull Requests for your feature/fix.
To run the project, run
```
npm install
```
or
```
yarn
```
then
```
npm start
```


## License

[MIT](./LICENSE)