# node-readline
node-readline

## more info 

```
https://nodejs.org/api/readline.html
```

## initial code

```
const readline = require('readline');

const rl = readline.createInterface({
  input: process.stdin,
  output: process.stdout
});

rl.on('line', (input) => {
  console.log(`Received: ${input}`);
});
```

