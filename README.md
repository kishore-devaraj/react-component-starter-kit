# react-component-starter-kit
A starter kit for creating reusable react component which can be published in npm registry.

### Installation & Instructions
- Clone the repo
```
git clone https://github.com/kishore-devaraj/react-component-starter-kit
```

- Install the required packages
```
npm install
```

- Write your component under src directory and link it with root npm modules
```
npm link
```

- Link your modules in the test project
```
npm link <module_name>
```

### Import your module in your react code and start using it.


### Publishing it in npm registry
- Login into your npm account
```
npm login
```
- Change your version number in the package.json
```
npm version <major> | <minor> | <patch>
```

- Publish your package to npm repo
```
npm publish
```
