<h1 align="center">Axios Notes</h1>

- [Introduction:](#introduction)
    - [Why Axios instead of fetch:](#why-axios-instead-of-fetch)
    - [Installing Axios:](#installing-axios)


# Introduction: 
Axios is a promise-based HTTP client for node.js used to communicate with servers (APIs). We can use it all HTTP methods like (GET, POST, PUT, PATCH, DELETE) and for Handle headers, auth, errors, interceptors, etc.

### Why Axios instead of fetch: 

| Feature                                     | Axios | fetch |
| ------------------------------------------- | ----- | ----- |
| Automatic JSON parsing (most used features) | ✅     | ❌     |
| Interceptors                                | ✅     | ❌     |
| Request timeout                             | ✅     | ❌     |
| Better error handling                       | ✅     | ❌     |
| Old browser support                         | ✅     | ❌     |

### Installing Axios:

```Bash
npm install axios
```

Note: CommonJS usage
In order to gain the TypeScript typings (for intellisense / autocomplete) while using CommonJS imports with require() use the following approach:

```js
const axios = require('axios').default;

// axios.<method> will now provide autocomplete and parameter typings
```
