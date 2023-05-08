# Redux DevTools Extension

|本期版本|上期版本
|:---:|:---:
`Mon Jun 13 09:56:18 CST 2022` | -

```bash
npm install --save @redux-devtools/extension
```

```javascript
import { composeWithDevTools } from '@redux-devtools/extension';
const store = createStore(
  reducer,
  composeWithDevTools(
    applyMiddleware(...middleware)
    // other store enhancers if any
  )
);
```


## Ref

* [Redux DevTools](https://github.com/reduxjs/redux-devtools)、 ~~[Redux DevTools Extension](https://github.com/zalmoxisus/redux-devtools-extension)~~
* [Redux DevTools - Chrome 应用商店](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd)
* [Redux DevTools 与 `replaceReducer` 冲突导致代码多次执行](https://github.com/dvajs/dva/issues/41)