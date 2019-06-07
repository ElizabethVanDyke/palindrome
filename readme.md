This simple NPM module was created in the process of going through the 
<a href="https://www.learnenough.com/javascript-tutorial" rel="nofollow">
<em>Learn Enough JavaScript to Be Dangerous</em></a>. The module can be used as follows:

```
$ npm install --global mhartl-palindrome
$ vim test.js
let Phrase = require("mhartl-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true

```