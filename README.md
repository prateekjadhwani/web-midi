# Web-Midi Element

With the help of `<web-midi>` element, you can view the midi devices connnected to a computer and see the keys pressed in a browser.

## Installation

You can install the `<web-midi>` element with the help of `bower`. 

`bower install --save web-midi`

This will install the `<web-midi>` element in your components directory.

## How to use

Simply import the `web-midi.html` file in your elements file. After that you can simply use `<web-midi></web-midi>` html tag to use it. 

You can use the `value` attribute of `web-midi` element to get the value of the key pressed.

The element also emits a `change` event when the value changes.Please refer the `demo.html` file for how you can listen to it.

## Attributes

| attribute | description | type | example value |
|-----------|-------------|------|---------------|
| value | The value of the key pressed on a midi device | String | `92 24 7f ` |