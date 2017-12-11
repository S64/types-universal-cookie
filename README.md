# @types/universal-cookie

TypeScript definitions for [`universal-cookie`](https://github.com/reactivestack/cookies/tree/master/packages/universal-cookie).

## Installation

```javascript
{
  "dependencies": {
    "universal-cookie": "^2.1.2"
  },
  "devDependencies": {
    "@types/react-cookie": "git+ssh://git@github.com:S64/types-universal-cookie.git#v2.1.2-1"
  }
}
```

## Example

```typescript
import Cookies from 'universal-cookie';

const cookies: Cookies = new Cookies(req.headers.cookie);
```
