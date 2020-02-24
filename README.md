# react-easy-back-to-top

## Description

An easy to use back to top component with React

## Installation

`npm install --save react-easy-back-to-top`

## Run the example locally

1. npm install
2. npm start

## Demo

[Demo](https://codesandbox.io/s/laughing-architecture-kzqi6)

## Usage

```
import React from "react";
import BackToTop from 'react-easy-back-to-top';

export default function Example() {
  return (
    <BackToTop
      backgroundColor="green"
      position={{ right: "5%", bottom: "10%" }}
      hover={{ backgroundColor: "black", color: "gray" }}
      transition="all 0.5s"
      showOnDistance={0}
      borderRadius={16}
      opacity="1"
      color="white"
      fontSize="24px"
      // Other Props...
    />
  );
}

```

## Props

| Props           | Types  | Defaults                                                     | Descriptions                                                                                                                                                                                                                                                                                                                                                                                  |
| --------------- | :----- | ------------------------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| icon            | string |                                                              | You can use any icon library after you import it to index.html via cdn etc. and these icons has to be applied with classnames. For example (Font awesome icons): `icon="fas fa-arrow-up"`                                                                                                                                                                                                     |
| position        | object | `{ bottom: "0%", right: "0%"}`                               | Position of the button. You can specify top, right, bottom, left positions with 'px' or '%'                                                                                                                                                                                                                                                                                                   |
| color           | string | `white`                                                      | Color of text or icon inside of the button                                                                                                                                                                                                                                                                                                                                                    |
| backgroundColor | string | `black`                                                      | Background of the button                                                                                                                                                                                                                                                                                                                                                                      |
| hover           | object | `{color: 'white', backgroundColor: 'black', opacity: '0.9'}` | If the button hovered, these styles gonna be applied to button                                                                                                                                                                                                                                                                                                                                |
| borderRadius    | number | `48`                                                         | Border radius of the button                                                                                                                                                                                                                                                                                                                                                                   |
| margin          | string | `12px`                                                       | Margin of the button                                                                                                                                                                                                                                                                                                                                                                          |
| fontSize        | string | `18px`                                                       | Font size of the icon or text                                                                                                                                                                                                                                                                                                                                                                 |
| padding         | string | `16px`                                                       | Padding of the button                                                                                                                                                                                                                                                                                                                                                                         |
| opacity         | string | `1`                                                          | Opacity of the button                                                                                                                                                                                                                                                                                                                                                                         |
| border          | string | `none`                                                       | Border of the button                                                                                                                                                                                                                                                                                                                                                                          |
| text            | string |                                                              | The text inside of the button                                                                                                                                                                                                                                                                                                                                                                 |
| cursor          | string | `pointer`                                                    | Cursor style of the button                                                                                                                                                                                                                                                                                                                                                                    |
| outline         | string | `none`                                                       | Outline style of the button                                                                                                                                                                                                                                                                                                                                                                   |
| scrollBehavior  | string | `smooth`                                                     | Scroll behavior of the button. You can use any scroll behavior property. [More](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-behavior)                                                                                                                                                                                                                                             |
| transition      | string | `none`                                                       | Transition property of the button [More](https://developer.mozilla.org/en-US/docs/Web/CSS/transition)                                                                                                                                                                                                                                                                                         |
| showOnDistance  | number | `300`                                                        | The read-only scrollY property of the Window interface returns the number of pixels that the document is currently scrolled vertically. For example when you set it to showOnDistance={1000}, the button will appear when the user's scrollY greater than 1000 pixels. If you set it to 0, it will be always visible. [More](https://developer.mozilla.org/en-US/docs/Web/API/Window/scrollY) |
| zIndex          | number | `999`                                                        | z-index property for the button                                                                                                                                                                                                                                                                                                                                                               |
