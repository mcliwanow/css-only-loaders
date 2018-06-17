# css-only-loaders

This is a collection of single element loaders animated with CSS.

The aim of this little project was to play with css animations by creating a set of loaders consisting of single html element.

Each loader can be configured (size, color) and it can be displayed as:
* a standalone element (default)
* over a parent div (by adding `.on-element` class)
* over a full page (by adding `.full-page` class)

## Usage

To add a loader simply create an `html` element with class `.loader` and add an extra class for specific loader type.
For example to render loader bar you could write:
```
<div class="loader loader-bar"></div>
```

To display full page loader add `.full-page` class to the element. For example:
```
<div class="loader loader-default full-page"></div>
```

To cover relatively positioned parent with the loader add `.on-element` class to loader element. For example:
```
<div class="loader loader-default on-element"></div>
```

// TODO: how it looks - before and after

Possible loader types with their respective classes are shown before.

    
## Loader Types

| name | css class name | example usage | how it looks |
| --------------- | ---------------- | ---------------- | ---------------- |
| default | `loader-default` | `<div class="loader loader-default"></div>` | ![Default loader](images/default.gif) |
| bar | `loader-bar` | `<div class="loader loader-bar"></div>` | ![Bar loader](images/bar.gif) |
| dots | `loader-dots` | `<div class="loader loader-dots"></div>` | ![Dots loader](images/dots.gif) |
| spinner | `loader-spinner` | `<div class="loader loader-spinner"></div>` | ![Spinner loader](images/spinner.gif) |
| pulsate | `loader-pulsate` | `<div class="loader loader-pulsate"></div>` | ![Pulsate loader](images/pulsate.gif) |
| heartbeat | `loader-heartbeat` | `<div class="loader loader-heartbeat"></div>` | ![Heartbeat loader](images/heartbeat.gif) |
| circles | `loader-circles` | `<div class="loader loader-circles"></div>` | ![Circles loader](images/circles.gif) |
| progress | `loader-progress` | `<div class="loader loader-progress"></div>` | ![Progress loader](images/progress.gif) |
    
    
## Config and build
    - variables to change
    - how to build next version
    - how to build individual loaders 

## License
MIT License
