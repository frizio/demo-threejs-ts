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

## Install Three.js -> 0.138.3 [ al 04 / Marzo / 2022 ]

```bash
npm i -D three @types/three
```

## Run in development mode

```bash
npm run dev
```

## Run in production mode

```bash
npm i -g http-server
npm run build
http-server ./dist/client
```

## Deploy on GitHub pages

```bash
npm i -g gh-pages
gh-pages -d dist/client
or
npm run deploy-ghp
```

### [Link](https://frizio.github.io/demo-threejs-ts/index.html)
