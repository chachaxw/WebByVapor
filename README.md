# Vapor Framework

A basic vapor template for starting a new Vapor web application. If you're using vapor toolbox, you can use: `vapor new --template=basic`

## Screen Shot
![Screen Shot](http://7xqacx.com1.z0.glb.clouddn.com/vapor_screenshot.png)

![Vapor Structure](http://7xqacx.com1.z0.glb.clouddn.com/vapor_structure.png)

## 📖 Documentation

Visit the Vapor web framework's [documentation](http://docs.vapor.codes) for instructions on how to use this package.

## 💧 Community

Join the welcoming community of fellow Vapor developers in [slack](http://vapor.team).

## 🔧 Compatibility

This package has been tested on macOS and Ubuntu.

## 🐶 Folder Structure

#### Minimum Folder Structure
```
.
├── App
│   └── main.swift
├── Public
└── Package.swift
```
#### Models
```
.
├── App
.   └── Models
.       └── User.swift
```
#### Controllers
```
.
├── App
.   └── Controllers
.       └── UserController.swift
```
#### Views
```
.
├── App
└── Resources
    └── Views
         └── user.html
```
#### Config
```
.
├── App
└── Config
  └── app.json         // default app.json
    └── development
         └── app.json  // overrides app.json when in development environment
    └── production
         └── app.json  // overrides app.json when in production environment
    └── secrets
         └── app.json  // overrides app.json in all environments, ignored by git
```
