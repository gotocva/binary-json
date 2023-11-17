### Binary json


```js
npm i binary-json
```

```
const binaryJson = require('binary-json');
```

```
// Example data
const data = { name: 'Sivabharathy', age: 28, company: 'Sparkout Tech Solutions Pvt Ltd' };

// Serialize data using binary json
const buffer = binaryJson.encode(data);

console.log('MessagePack encoded:', buffer);

// Deserialize binary into data
const decodedData = binaryJson.decode(buffer);

console.log('MessagePack decoded:', decodedData);
```