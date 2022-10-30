# 👑 Dylan's Github



## My current favourite helloWorld program:
```js
let alphabet = [' ','a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']

let message = '';

function helloWorld() {
  for(i=0; i<12; i++){
    if(i===0) {
      message = message.concat(alphabet[8].toUpperCase());
    } else if(i===1) {
      message = message.concat(alphabet[5]);
    } else if(i===2) {
      message = message.concat(alphabet[12]);
    } else if(i===3) {
      message = message.concat(alphabet[12]);
    } else if(i===4) {
      message = message.concat(alphabet[15]);
    } else if(i===5) {
      message = message.concat(alphabet[0]);
    } else if(i===6) {
      message = message.concat(alphabet[23].toUpperCase());
    } else if(i===7) {
      message = message.concat(alphabet[15]);
    } else if(i===8) {
      message = message.concat(alphabet[18]);
    } else if(i===9) {
      message = message.concat(alphabet[12]);
    } else if(i===10) {
      message = message.concat(alphabet[4]);
    } else if(i===11) {
      message = message.concat('!');
    }
  }
}

helloWorld();
console.log(message);
```
