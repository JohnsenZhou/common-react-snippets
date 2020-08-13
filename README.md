# common-react-snippets

Common React Snippets for VS Code.

## Features

These snippets were selected carefully from my own day-to-day React use. Not
everything in React is included here. This is a hand selected set of snippets
that work the way that you would expect, not just a copy of the documentation.

## Snippets

| Snippet | Renders                          |
| ------- | -------------------------------- |
| `imr`   | Import React                     |
| `imrc`  | Import React / Component         |
| `imrs`  | Import React / useState          |
| `imrse` | Import React / useState useEffect|
| `impc`  | Import React / PureComponent     |
| `imfc`  | Import React / FunctionComponent |
| `cc`    | Class Component                  |
| `pc`    | Pure Component                   |
| `ccc`   | Class Component With Constructor |
| `fc`    | Function Component With hooks    |
| `sfc`   | Stateless Function Component     |
| `cdm`   | componentDidMount                |
| `uef`   | useEffect Hook                   |
| `gds`   | getDerivedStateFromProps         |
| `scu`   | shouldComponentUpdate            |
| `cdu`   | componentDidUpdate               |
| `cwum`  | componentWillUnmount             |
| `cdc`   | componentDidCatch                |
| `gsbu`  | getSnapshotBeforeUpdate          |
| `ss`    | setState                         |
| `ssf`   | Functional setState              |
| `usf`   | Declare a new state variable using State Hook |
| `ren`   | render                           |
| `rprop` | Render Prop                      |
| `ima`   | Import antd                      |
| `imp`   | Import module                    |
| `imc`   | Import classnames                |
| `ims`   | Import style                     |
| `imms`  | Import module style              |
| `mobs`  | Mobx observable with comment     |
| `mact`  | Mobx action with comment         |
| `dwgc`  | Div with global class            |
| `mlg`   | My Log                           |

## Full Expansions

### imr - Import React

```javascript
import React from 'react'
```

### imrc - Import React, Component

```javascript
import React, { Component } from 'react'
```

### imrs - Import React, useState

```javascript
import React, { useState } from 'react'
```

### imrse - Import React, useState, useEffect

```javascript
import React, { useState, useEffect } from 'react'
```

### impt - Import PropTypes

```javascript
import PropTypes from 'prop-types'
```

### impc - Import PureComponent

```javascript
import React, { PureComponent } from 'react'
```

### cc - Class Component

```javascript
import React, { Component } from 'react'
interface |Props {
  
}
interface |State {
  
}
class | extends Component<|Props, |State> {
  state = { | },
  render() {
    return ( | )
  }
}

export default |
```

### pc - Pure Component

```javascript
import React, { PureComponent } from 'react'
interface |Props {
  
}
interface |State {
  
}
class | extends PureComponent<|Props, |State> {
  state = { | },
  render() {
    return ( | )
  }
}

export default |
```

### ccc - Class Component With Constructor

```javascript
import React, { Component } from 'react'
interface |Props {
  
}
interface |State {
  
}
class | extends Component<|Props, |State> {
  constructor(props: |Props) {
    super(props)
    this.state = { | }
  }
  render() {
    return ( | )
  }
}

export default |
```

### fc - Function Component With hooks

```javascript
import React, { useState, useEffect } from 'react'

interface |Props {
  
}
function | (props: |Props) {
  const {  } = props
  const [|, set|] = useState(|)
  useEffect(() => {

  }, [])
  return (
    <div></div>
  )
}

export default |
```

### sfc - Stateless Function Component

```javascript
import React from 'react'

interface |Props {
  
}
function | (props: |Props) {
  const {  } = props
  return (
    <div></div>
  )
}

export default |
```

### cdm - componentDidMount

```javascript
componentDidMount() {
  |
}
```

### uef - useEffect Hook
  
```javascript
useEffect(() => {
  |
}, [])
```

### gds - getDerivedStateFromProps

```javascript
static getDerivedStateFromProps(nextProps, prevState) {
  |
}
```

### scu - shouldComponentUpdate

```javascript
shouldComponentUpdate(nextProps, nextState) {
  |
}
```

### cdu - componentDidUpdate

```javascript
componentDidUpdate(prevProps, prevState) {
  |
}
```

### cwum - componentWillUnmount

```javascript
componentWillUnmount() {
  |
}
```

### cdc - componentDidCatch

```javascript
componentDidCatch(error, info) {
  |
}
```

### gsbu - getSnapshotBeforeUpdate

```javascript
getSnapshotBeforeUpdate(prevProps, prevState) {
  |
}
```

### ss - setState

```javascript
this.setState({ | : | })
```

### ssf - Functional setState

```javascript
this.setState(prevState => {
  return { | : prevState.| }
})
```

### usf - Declare a new state variable using State Hook

```javascript
const [|, set|] = useState()
```

> Hit Tab to apply CamelCase to function. e.g. [count, setCount]*

### ren - render

```javascript
render() {
  return (
    |
  )
}
```

### rprop - Render Prop

```javascript
class | extends Component {
  state = { | },
  render() {
    return this.props.render({
      |: this.state.|
    })
  }
}

export default |
```

### ima - Import antd

```javascript
import { | } from 'antd'
```

### imc - Import classnames

```javascript
import cls from 'classnames'
```

### ims - Import style

```javascript
import styles from './|.less'
```

### imms - Import module style

```javascript
import styles from './|.module.less'
```

### mobs - Mobx observable with comment

```javascript
/**  */
@observable | = |
```

### mact - Mobx action with comment

```javascript
/**  */
@action | = async () => {
  |
}
```

### dwc - Div with module class

```javascript
<div className={styles.|}>|</div>
```

### dwgc - Div with global class

```javascript
<div className='|'>|</div>
```

### mlg - My Log

```javascript
console.log('========start========')
console.log(|)
console.log('=========end=========')
```

## Commands

todo...
