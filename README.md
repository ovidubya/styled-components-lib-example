# styled-components-lib-example

> Made with create-react-styled-library

[![NPM](https://img.shields.io/npm/v/styled-components-lib-example.svg)](https://www.npmjs.com/package/styled-components-lib-example) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install Peer Dependencies

```bash
npm install --save react styled-components
```

## Install

```bash
npm install --save styled-components-lib-example
```

## Usage

```tsx
import React from 'react'

import { ThemeProvider, Button } from 'styled-components-lib-example'

interface AppProps {}

const App: React.FC<AppProps> = () => {
  return (
    <ThemeProvider>
      <Button backgroundColor='primary' color='white'>
        Hello, I am a styled button
      </Button>
    </ThemeProvider>
  )
}
```

## Live Demo

For examples of the styled-components-lib-example in action, checkout the storybook <a href="https://ovidubya.github.io/styled-components-lib-example" target="_blank">here</a>.

## Develop

This will open a storybook dev server on `http://localhost:8080`

```bash
$ npm start # this will open storybook
```

## Build

This will output the cjs and es modules to the `dist` folder

```bash
$ npm run build
```

## Deploy github page

This will publish storybook as a Github page

```bash
$ npm run deploy-github-page
```

## Publish to npm

(you need to be logged in via npm for publishing)

```bash
$ npm publish
```

## Publish locally

To create a local TAR file to test before publishing, run

```
$ npm pack
```

This will create a file called `styled-components-lib-example-1.0.0.tgz`

You can use this file as a normal package dependency
by linking in your `npm install`

```sh
$ npm i path/to/styled-components-lib-example-1.0.0.tgz
```

## License

MIT © [ovidubya](https://github.com/ovidubya)
