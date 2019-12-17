# CacheQL

CacheQL is an open-source library for server-side caching GraphQL queries. This specific repository used Redis cache to test performance and fnuctionality, but can be incorporated with other caching mechanisms and databases.

## Installation

Use the package manager [npm](https://www.npmjs.com/) to install foobar.

```bash
npm install cacheql
```

## Usage

```javascript
const cacheQL = require('cacheql') 

// inside of resolvers
cacheql.checkify('word') # returns 'words'
cacheql.cachify('goose') # returns 'geese'
cacheql.singularize('phenomena') # returns 'phenomenon'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)