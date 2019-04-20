# Phrase object (with palindrome detector)

This is a sample module created for me (MrTrukiny) throw [*Learn Enough JavaScript to Be Dangerous*](https://www.learnenough.com/javascript-tutorial) writed by Michael Hartl.

The module can be used as follows:

```
$ npm install --global mrtrukiny-palindrome
$ vim test.js
let Phrase = require("mrtrukiny-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true
```

Regards.
