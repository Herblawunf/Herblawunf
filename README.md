# 👑 Dylan's Github

**`Just a guy learning to code`** <br />
I am currently following The Odin Project and learning full-stack web development 

## Projects
These are all pretty bad but I'm proud of them
* &#128216; **My first website**, the first website I built from scratch with the Odin Project.
  * [Live preview](https://herblawunf.github.io/TOP-Practice/)
  * Repository: [Github](https://github.com/Herblawunf/TOP-Practice)
* :scissors:; **Rock paper scissors**, my first use of DOM manipulation!.
  * [Live preview](https://herblawunf.github.io/Rock-Paper-Scissors-TOP/)
  * Repository: [Github](https://github.com/Herblawunf/Rock-Paper-Scissors-TOP)

## What I'm learning

###### Languages
<img align="left" width="30px" style="padding-right:10px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
<img align="left" width="30px" style="padding-right:10px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" />
<img align="left" width="30px" style="padding-right:10px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" /> <br />

###### Frameworks
*tumbleweed* <br />

###### Version Control
<img align="left" width="30px" style="padding-right:10px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
<img align="left" width="30px" style="padding-right:10px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" /> <br />

###### Environments
<img align="left" width="30px" style="padding-right:10px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" /> <br />

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
