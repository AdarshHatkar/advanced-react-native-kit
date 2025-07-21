# advanced-react-native-kit

React Native wrapper for advanced-js-kit - Modern TypeScript utility library with tree-shaking support for React Native applications.

## Installation

```bash
npm install advanced-react-native-kit
```

## Usage

### ESM/TypeScript Import
```typescript
import { testFun } from 'advanced-react-native-kit';

const result = testFun();
console.log(result); // "testFun result"
```

### CommonJS Import
```javascript
const { testFun } = require('advanced-react-native-kit');

const result = testFun();
console.log(result); // "testFun result"
```

## React Native Usage

This package is specifically designed for React Native applications and should work seamlessly with:
- Metro bundler
- React Native CLI projects
- Expo projects
- Both TypeScript and JavaScript projects

## API

### testFun()
- **Type**: `() => string`
- **Description**: A test function that logs a message and returns a test result
- **Returns**: `"testFun result"`