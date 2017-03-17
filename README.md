# react-scripts-sedona

Create React apps (with Typescript, SCSS and CSS-modules, with typings) with no build configuration.

Create React App works on macOS, Windows, and Linux.<br>
If something doesn’t work please [file an issue](https://github.com/facebookincubator/create-react-app/issues/new).

## tl;dr

```sh
npm install -g create-react-app@1.3.0
create-react-app my-app --scripts-version=react-scripts-sedona
cd my-app/
npm install --save-dev @types/node @types/react @types/react-dom @types/jest
npm start
```

We recommand to use yarn instead of npm.
To do so, [install yarn](https://yarnpkg.com/lang/en/docs/install/), and then :
```sh
yarn global add create-react-app@1.3.0
create-react-app my-app --scripts-version=react-scripts-sedona
cd my-app/
yarn add --dev install @types/node @types/react @types/react-dom @types/jest
yarn run start
```

### typings

Custom packages dependencies install doesn't seems to be available without modifying create-react-app itself. <br >
You'll therefore need to install them manually, as shown above.

For more informations about this issue, see [wmonk/create-react-app-typescript#10](https://github.com/wmonk/create-react-app-typescript/issues/10)

## last update from [create-react-app](https://github.com/facebookincubator/create-react-app)

* project's tag : [v0.9.5](https://github.com/facebookincubator/create-react-app/releases/tag/v0.9.5)
* create-react-app package version : 1.3.0

We recommand to use react-scripts-sedona with this exact create-react-app version **only**.

Credits
-------

React-scripts-sedona is created and maintained by Sedona
http://www.sedona.fr

We would like to thanks the authors of the different libraries and tools
used in this solution.

* [react-scripts-ts](https://github.com/wmonk/create-react-app-typescript), from wmonk
* [create-react-app](https://github.com/facebookincubator/create-react-app), from Facebook
* [typed css modules](https://github.com/Quramy/typed-css-modules), from Quramy