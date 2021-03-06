# creating-a-workflow-app-for-church

## This is a series on YouTube.We'll be exploring the in's and outs of some frameworks like 
- **React Native(react but with extra)**
-  **React**
-  Web(**html**,**css**,**js**)
- **Flutter**
> Note:Make sure you're using the latest stable version of the Flutter SDK(Standard Development Kit)


## Web
***
for web we're going to use [Material design](https://material.io) and [Materialize.css](https://materializecss.com).
Here are some code snippets:

***

### Material Design
`<link href="https://unpkg.com/material-components-web@latest/dist/material-components-web.min.css" rel="stylesheet">`
`<script src="https://unpkg.com/material-components-web@latest/dist/material-components-web.min.js"></script>`

***

### Materialize.css
`<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">`
`<script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>`

## Flutter
***
### lib/main.dart
for this,we're going to use material.dart in the flutter package,  
which gives us [Material Design](https://material.io) right out of the box   
`import 'package:flutter/material.dart';`

***
### pubspec.yaml
Cupertion_icons is a package in flutter
`cupertion_icons: ^0.1.3`

***

## React
***
for this,we're going to use [Material Design](https://material.io),[Materialize.css](https://materializecss.com/) (based around Material Design) and [Material-UI](https://material-ui.com) but we're going to put into our public/index.html file   

### public/index.html
Use this in development:  
`<script src="https://unpkg.com/@material-ui/core@latest/umd/material-ui.development.js"></script>`  

Use this in production:   
`<script src="https://unpkg.com/@material-ui/core@latest/umd/material-ui.production.js"></script>`


## React Native
***
for this,we're going to use [Material Design] but we're going to put into our public/index.html file

### public/index.html
   
   
Use this in development:
`<script src="https://unpkg.com/@material-ui/core@latest/umd/material-ui.development.js"></script>`  

Use this in production:
`<script src="https://unpkg.com/@material-ui/core@latest/umd/material-ui.production.js"></script>`  

## Requirements
***
- A code editor like [VsCode](https://code.visualstudio.com) or Flutter IDE like [Android Studio](https:///developer.android.com)
- [Flutter SDK](https://flutter.dev)
- [Node](https://nodejs.org)

## Coming soon
- [x] Make React Native Tutorial
- [x] Make React Tutorial
- [x] Make Web Tutorial
- [x] Make Flutter Tutorial
