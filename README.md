# @hstover/react-use-the-things

> a package that gives you custom react things

[![NPM](https://img.shields.io/npm/v/@hstover/react-use-the-things.svg)](https://www.npmjs.com/package/@hstover/react-use-the-things) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save @hstover/react-use-the-things
```

## Usage

```jsx
import React, { Component } from 'react'

import { useMyHook } from '@hstover/react-use-the-things'

const Example = () => {
  const example = useMyHook()
  return (
    <div>{example}</div>
  )
}
```

## License

MIT © [HannahStover](https://github.com/HannahStover)

---

This hook is created using [create-react-hook](https://github.com/hermanya/create-react-hook).
