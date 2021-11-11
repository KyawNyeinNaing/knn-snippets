# knn-snippets README

## Supported languages (file extensions)

- JavaScript (.js)
- JavaScript React (.jsx)

## installation

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

```
  ext install knn.knn-snippets
```

**Snippets are found below.**

→ Denotes the `TAB` key.

### Basic Method

|    Prefix | Method                                              |
| --------: | --------------------------------------------------- |
| `_syimd→` | `import { destructuredModule } from 'module'`       |
| `_syime→` | `import * as alias from 'module'`                   |
| `_syima→` | `import { originalName as aliasName} from 'module'` |
|  `_sydo→` | `const { propName } = objectToDescruct`             |
|  `_syda→` | `const [ propName ] = arrayToDescruct`              |
| `_systo→` | `setTimeout(() => { }, delayTime`                   |
| `_sycmb→` | `Comment Big Block`                                 |

### React

|      Prefix | Method                                                                                     |
| ----------: | ------------------------------------------------------------------------------------------ |
|   `_syimr→` | `import React from 'react'`                                                                |
|  `_syimrc→` | `import React, { Component } from 'react'`                                                 |
| `_syimrcp→` | `import React, { Component } from 'react' & import PropTypes from 'prop-types'`            |
|  `_syimrs→` | `import React, { useState } from 'react'`                                                  |
|  `_syimre→` | `import React, { useEffect } from 'react'`                                                 |
| `_syimrse→` | `import React, { useState, useEffect } from 'react'`                                       |
|  `_syimrr→` | `import { BrowserRouter as Router, Route, Switch, Link, NavLink } from 'react-router-dom'` |
|   `_syrct→` | `const ${1:contextName} = React.createContext()`                                           |
|  `_syfref→` | `const ${1:refName}Ref = React.createRef()t`                                               |

### Redux

|             Prefix | Method                                                                                           |
| -----------------: | ------------------------------------------------------------------------------------------------ |
|         `_syrfcx→` | `Creates a React functional component with connected redux and ES7 module system`                |
|        `_syrfcxp→` | `Creates a React functional component with PropTypes with connected redux and ES7 module system` |
|      `_syrxtypes→` | `Create redux types`                                                            |
| `_syrxtypehandle→` | `Create redux type handle`                                                            |
|     `_syrxaction→` | `Create a redux action`                                                                          |
|   `_syrxactionget` | `Create a redux action API Reference`                                                            |
|    `_syrxreducer→` | `Create a redux reducer`                                                                         |
| `_syrxreducerapi→` | `Create a redux reducer API Reference`                                                           |
| `_syrxmiddleware→` | `applyMiddleware(...middleware)`                                                                 |
|    `_syrxcombine→` | `Combine reducers`                                                                               |
|          `_syrct→` | `Create React context`                                                                           |

### `_syrfc`

```javascript
import React from "react";

export default function $1() {
  return <>$0</>;
}
```

### `_syrfce`

```javascript
import React from "react";

function $1() {
  return <>$0</>;
}

export default $1;
```

### `_syrafcp`

```javascript
import React from "react";
import PropTypes from "prop-types";

const $1 = (props) => {
  return <>$0</>;
};

$1.propTypes = {};

export default $1;
```

### `_syrafce`

```javascript
import React from "react";

const $1 = () => {
  return <>$0</>;
};

export default $1;
```

### `_syrafc`

```javascript
import React from "react";

export const $1 = () => {
  return <>$0</>;
};
```

### `_syrafcp`

```javascript
import React from "react";
import PropTypes from "prop-types";

const $1 = (props) => {
  return <>$0</>;
};

$1.propTypes = {};

export default $1;
```

### `_syrmcp`

```javascript
import React, { memo } from "react";
import PropTypes from "prop-types";

const $1 = memo(function $1(props) {
  return <>$0</>;
});

$1.propTypes = {};

export default $1;
```

## Release Notes

## [1.1.1]

- Change `_syrxactionApi` to `_syrxactionget`
- Add `_syrxtypes` redux types for snippets
- Add `_syrxtypehandle` redux type handle for snippets

## [1.1.0]

Minor changes

### 1.0.0

Initial release of

- Redux snippets
- React components snippets
- Import and functions snippets
- PropTypes snippets
