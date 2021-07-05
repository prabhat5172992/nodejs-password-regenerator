## Password Generator

### Commands
##### For generating password
```sh
node index.js or password-generator
```
##### For generating and saving it to a password.txt file
```sh
password-generator --save
```
##### For using only alphabets
```sh
password-generator -nn -ns
```
##### Using alpha numeric
```sh
password-generator -ns
```
##### Using alphabets and symbols
```sh
password-generator -nn
```

##### Packages used
```sh
commander
chalk
clipboardy
```
##### To create symlink
```sh
npm link and to unlink npm unlink

But to create symlink first go to package.json and add below configurations
"preferGlobal": true,
"bin": "./index.js",
```

### Refrence
```sh
https://youtu.be/3Xx83JAktXk
```