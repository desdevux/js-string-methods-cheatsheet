# js-string-methods-cheatsheet
A cheat sheet for JavaScript string methods with examples, use cases and return types, right here in the README file for easy access. This project is primarily created for my personal use, but feel free to use it if you find it helpful!

## Example String
For the following examples, we are using this simple string:
```js
let exampleString = "This is an example text.";
```

### Cheatsheet

| **Method Name**  | **Code Example**  | **Result**  | **Return Data Type**  | **Use Case**  |
| ---------------- | ----------------- | ----------- | --------------------- | ------------- |
| concat() | ```exampleString.concat(" Another sentence.");``` | This is an example text. Another sentence. | string | Combine two or more strings together.|
| split() | ```exampleString.split(" ");``` | ["This", "is", "an", "example", "text."] | array | Split a string into an array of substrings based on a delimiter. Can be useful for processing multiple values from user input(like tags or keywords) from forms or search fields by splitting the string into an array.|
| toString() | ```let wordCount = 5; let num = wordCount.toString(); console.log(exampleString + " It has " + num + " words.");``` | This is an example text. It has 5 words. | string | Converts a number to a string for concatenation or display purposes. Can be useful if you need to display a number and a string as part of a message or UI element.|

> **Note:** Due to Markdown's limitations with multiline code in table cells, some code examples have been simplified and written in a single line for better formatting.

##### License

This cheatsheet is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License.

If you use or adapt this cheat sheet, please provide the following attribution:

"Original cheat sheet created by [desdevux](https://github.com/desdevux), available at [js-string-methods-cheatsheet](https://github.com/desdevux/js-string-methods-cheatsheet) on GitHub."
