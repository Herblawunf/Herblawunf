# 👑 Dylan's Github
```Just a guy learning to code```
---

## What do I know

###### Languages
<img align="left" width="30px" style="padding-right:10px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
<img align="left" width="30px" style="padding-right:10px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" />
<img align="left" width="30px" style="padding-right:10px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" />

###### Frameworks
*tumbleweed*

###### Version Control
<img align="left" width="30px" style="padding-right:10px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
<img align="left" width="30px" style="padding-right:10px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />

###### Environments
<img align="left" width="30px" style="padding-right:10px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" />

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
