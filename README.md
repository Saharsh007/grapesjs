# [GrapesJS](http://grapesjs.com)




<p align="center"><img src="img/img1.jpeg" alt="GrapesJS" width="500" align="center"/></p>


GrapesJS is a free and open source Web Builder Framework which helps building HTML templates, faster and easily, to be delivered in sites, newsletters or mobile apps. Mainly, GrapesJS was designed to be used inside a [CMS] to speed up the creation of dynamic templates. To better understand this concept check the image below

<br/>
<p align="center"><img src="img/img2.png" alt="GrapesJS - Style Manager" height="400" align="center"/></p>
<br/>

Generally any 'template system', that you'd find in various applications like CMS, is composed by the **structure** (HTML), **style** (CSS) and **variables**, which are then replaced with other templates and contents on server-side and rendered on client.

Official demo of GrapeJS: http://grapesjs.com/demo.html






## Table of contents

* [Features](#features)
* [Download](#download)
* [Development](#development)
* [Documentation](#documentation)
* [API](#api)
* [Plugins](#plugins)
* [Support](#support) 




## Features

| Blocks | Style Manager | Layer Manager |
|--|--|--|
|<img  src="img/img3.jpeg"  alt="GrapesJS - Block Manager"  height="400"  align="center"/>|<img  src="img/img4.jpeg"  alt="GrapesJS - Style Manager"  height="400"  align="center"/>|<img  src="img/img5.jpeg"  alt="GrapesJS - Layer Manager"  height="400"  align="center"/>|

| Code Viewer | Asset Manager |
|--|--|
|<img  src="img/img6.jpeg"  alt="GrapesJS - Code Viewer"  height="300"  align="center"/>|<img  src="img/img7.jpeg"  alt="GrapesJS - Asset Manager"  height="250"  align="center"/>|


<!-- * Default built-in commands (basically for creating and managing different components) -->





## Download
* GIT
  * `git clone https://github.com/Saharsh007/grapesjs.git`


## Development

GrapesJS uses [Webpack](https://github.com/webpack/webpack) as a module bundler and [Babel](https://github.com/babel/babel) as a compiler.

Clone the repository and install all the necessary dependencies

```sh
$ git clone https://github.com/Saharsh007/grapesjs.git
$ cd grapesjs
$ npm i
```

Start the dev server

```sh
$ npm start
```

Once the development server is started you should be able to reach the demo page (eg. `http://localhost:8080`)





## Documentation

Check the getting started guide here: [Documentation]

## API

API References could be found here: [API-Reference]

## Plugins

### Presets
* [grapesjs-preset-webpage](https://github.com/artf/grapesjs-preset-webpage) - Webpage Builder
* [grapesjs-preset-newsletter](https://github.com/artf/grapesjs-preset-newsletter) - Newsletter Builder
* [grapesjs-mjml](https://github.com/artf/grapesjs-mjml) - Newsletter Builder with MJML components
* [grapesjs-tui-image-editor](https://github.com/artf/grapesjs-tui-image-editor) - GrapesJS TOAST UI Image Editor
* [grapesjs-blocks-basic](https://github.com/artf/grapesjs-blocks-basic) - Basic set of blocks
* [grapesjs-plugin-forms](https://github.com/artf/grapesjs-plugin-forms) - Set of form components and blocks
* [grapesjs-navbar](https://github.com/artf/grapesjs-navbar) - Simple navbar component
* [grapesjs-component-countdown](https://github.com/artf/grapesjs-component-countdown) - Simple countdown component
* [grapesjs-style-gradient](https://github.com/artf/grapesjs-style-gradient) - Add `gradient` type input to the Style Manager
* [grapesjs-style-filter](https://github.com/artf/grapesjs-style-filter) - Add `filter` type input to the Style Manager
* [grapesjs-style-bg](https://github.com/artf/grapesjs-style-bg) - Full-stack background style property type, with the possibility to add images, colors, and gradients
* [grapesjs-blocks-flexbox](https://github.com/artf/grapesjs-blocks-flexbox) - Add the flexbox block
* [grapesjs-lory-slider](https://github.com/artf/grapesjs-lory-slider) - Slider component by using [lory](https://github.com/meandmax/lory)
* [grapesjs-tabs](https://github.com/artf/grapesjs-tabs) - Simple tabs component
* [grapesjs-tooltip](https://github.com/artf/grapesjs-tooltip) - Simple, CSS only, tooltip component for GrapesJS
* [grapesjs-custom-code](https://github.com/artf/grapesjs-custom-code) - Embed custom code

### Extensions
* [grapesjs-plugin-export](https://github.com/artf/grapesjs-plugin-export) - Export GrapesJS templates in a zip archive
* [grapesjs-plugin-filestack](https://github.com/artf/grapesjs-plugin-filestack) - Add Filestack uploader in Asset Manager
* [grapesjs-plugin-ckeditor](https://github.com/artf/grapesjs-plugin-ckeditor) - Replaces the built-in RTE with CKEditor
* [grapesjs-aviary](https://github.com/artf/grapesjs-aviary) - Add the Aviary Image Editor (dismissed, use the plugin below instead)
* [grapesjs-touch](https://github.com/artf/grapesjs-touch) - Enable touch support
* [grapesjs-indexeddb](https://github.com/artf/grapesjs-indexeddb) - Storage wrapper for IndexedDB
* [grapesjs-firestore](https://github.com/artf/grapesjs-firestore) - Storage wrapper for [Cloud Firestore](https://firebase.google.com/docs/firestore)
* [grapesjs-parser-postcss](https://github.com/artf/grapesjs-parser-postcss) - Custom CSS parser for GrapesJS by using [PostCSS](https://github.com/postcss/postcss)
* [grapesjs-typed](https://github.com/artf/grapesjs-typed) - Typed component made by wrapping Typed.js library



Find out more about plugins here: [Creating plugins](https://github.com/artf/grapesjs/wiki/Creating-plugins)





## License

BSD 3-clause


[Documentation]: <https://grapesjs.com/docs/>
[API-Reference]: <https://grapesjs.com/docs/api/>
[CMS]: <https://it.wikipedia.org/wiki/Content_management_system>
