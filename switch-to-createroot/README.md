# switch-to-createroot


|本期版本|上期版本
|:---:|:---:
`Fri Mar 31 16:32:05 CST 2023` | -

### React 18

```javascript
import React from 'react';
import ReactDOM from 'react-dom/client';

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
	<App />
)
```


### React 17

```javascript
import React from 'react';
import ReactDOM from 'react-dom';

ReactDOM.render(
	<App />,
	document.getElementById('root')
);
```

## Ref

* <https://reactjs.org/link/switch-to-createroot>
* [React 18 用 createRoot 替换 render](https://juejin.cn/post/6992435557456412709)