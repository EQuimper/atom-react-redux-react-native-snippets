# react-redux-react-native-snippets-snippets package

Some snippets for React/React-Native and Redux for help you to be a faster developer. I try to make it really easy to remember.

Help for:
- React-Native-Router-Flux
- React-Router

More will coming soon.

# React

### `imr` Import React

```js
import React from 'react';
```

### `imrc` Import Component React

```js
import React, { Component } from 'react';
```

### `sl` Stateless Component

```js
const ${1} = () => (
  ${2}
);

export default ${1};
```

### `rrr` React-Router route

```js
<Route path="${1}" component={${2}} />
```

### `ed` Export Default

```js
export default ${1};
```

### `r` return

```js
return ${1};
```

### `rcc` class React component es6

```js
class ${1} extends Component {
  render() {
    return (
      ${2}
    );
  }
}

export default ${1};
```

---

## React Component Lifecycle

### `cwm` componentWillMount

```js
componentWillMount() {
  ${1}
}
```

### `cdm` componentDidMount

```js
componentDidMount() {
  ${1}
}
```

### `cwum` componentWillUnmount

```js
componentWillUnmount() {
  ${1}
}
```

### `cwu` componentWillUpdate

```js
componentWillUpdate() {
  ${1}
}
```

### `cdu` componentDidUpdate

```js
componentDidUpdate() {
  ${1}
}
```

---

# Redux

### 'ins' INITIAL_STATE

```js
const INITIAL_STATE = {
  ${1}
};
```

### `rrd` Redux Reducer

```js
export default (state = INITIAL_STATE, action) => {
  switch (action.type) {
    case ${1}:
    default:
      return state;
  }
};
```

### `rt` Redux Types

```js
export const ${1} = '${1}';
```

---

# React-Native

### `imrn` Import React-Native

```js
import { ${1} } from 'react-native';
```

### `rnvt` React-Native Text and View

```js
import {
  View,
  Text
} from 'react-native';
```

### `rnsc` React-Native scene

```js
<Scene
  key="${1}"
  title="${2}"
  component={${3}}
/>
```
