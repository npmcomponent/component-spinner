*This repository is a mirror of the [component](http://component.io) module [component/spinner](http://github.com/component/spinner). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-spinner`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# Spinner

  Flexible spinner using canvas, a fork of [godmodelabs/spinner](https://github.com/godmodelabs/spinner).

  ![js spinner component](http://i.cloudup.com/KPENz2xQbRnN7BZ.png)

  Check out the [demo](http://godmodelabs.github.com/spinner/)!

## Installation

```bash
$ component install component/spinner
```

## Example

```js
var Spinner = require('spinner');

var spinner = new Spinner;
document.body.appendChild(spinner.el);
```

## API

### Spinner#light()

  Change the spinner to the light theme.

### Spinner#font(family)

  Change the font to `family`.

### Spinner#fontSize(n)

  Change the font size to `n`.

### Spinner#size(n)

  Change the indicator diameter to `n`, defaults to 50.

### Spinner#speed(n)

  Change the speed to `n` rpm, defaults to 60.

### Spinner#stop()

  Stop the animation. This is important when removing
  the spinner, otherwise the requestAnimationFrame cycle
  will continue.

## License

  MIT
