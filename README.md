# Demo ThreeJS from Udemy Course: ThreeJS and Typescript

## [Learn Threejs, TypeScript and NodeJS to create interactive 3D content on the web. by Sean Bradley](https://www.udemy.com/course/threejs-tutorials/)

- [Step-by-step - html version](https://sbcode.net/threejs/)

## Bootstrap project

```bash
npm init -y
npm i -D typescript
npx tsc -v
npx tsc --init
```

## Configure Typescript

```json
{ 
  "rootDir": "./src",
  "outDir": "./dist"
}
```

```json
  ...
  "scripts": {
    "watch": "tsc -w src/index.ts",
    "build": "tsc -p ."
  },
  ...
```
