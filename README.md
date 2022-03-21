<div align="center">
<h1>Mui-tel-input</h1>
  <p>A phone number input designed for the framework <a href="https://mui.com/">MUI</a> </p>
</div>

## Installation

This module is distributed via [npm][npm] which is bundled with [node][node] and
should be installed as one of your project's `dependencies`:

```
npm install --save mui-tel-input
```

## Usage

```jsx
import React from 'react'
import MuiTelInput from 'mui-tel-input'

const MyComponent = () => {
  const [value, setValue] = React.useState('')

  const handleChange = (newValue) => {
    setValue(newValue)
  }

  return <MuiTelInput value={value} onChange={handleChange} />
}
```

### 🐛 Bugs

Please file an issue for bugs, missing documentation, or unexpected behavior.

### 💡 Feature Requests

Please file an issue to suggest new features. Vote on feature requests by adding
a 👍. This helps maintainers prioritize what to work on.

## LICENSE

MIT
