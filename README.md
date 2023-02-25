# sciter-bulma
Bulma CSS for Sciter

## Requirement
- SciterJS SDK (5.0.2.5 or higher)

- [sciter fontawesome](https://github.com/8ctopus/sciter-fontawesome) (Optional)

## Usage

1. Copy file `sciter-bulma.css` in `dist` to your project.

2. Include it in your html file like this: `<link rel="stylesheet" href="../../dist/sciter-bulma.css" />`

3. If you want to use FontAwesome 6 in SciterJS, copy folder `sciter-fontawesome` in `vendors` to your project. 

    Then include it like this: `<link rel="stylesheet" href="../../vendors/sciter-fontawesome/fontawesome.css" />`

*** Please see demo files if you need more samples. ***

## Demos

You can use `usciter.exe` to load demo files. All the demos are from [Bulma Documentation](https://bulma.io/documentation/) with same or little changes.

## Known Issues
The effects in SciterJS is as consistent as possible with it's in Chrome, but they still have a little differences in some cases.

## How to compile from source files

* Compile `sciter-bulma.sass` with sass tools to generate  `sciter-bulma.css` when make changes.

* In `sciter-bulma.css` :
    - replace `"*;"` with `*;`
    - replace `"1*;"` with `1*;` 
    - replace `"5*;"` with `5*;`

## Reference & Acknowledgment

[Sciter](https://gitlab.com/sciter-engine/sciter-js-sdk) - Build cross platform desktop applications with HTML, CSS and javascript.

[Bulma](https://github.com/jgthms/bulma) - Bulma is a modern CSS framework based on Flexbox.

[sciter fontawesome](https://github.com/8ctopus/sciter-fontawesome) - Fontawesome 6 support for sciter.js.