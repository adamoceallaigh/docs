# Documentation: JS

## Resources

`Vanilla JS`

[Obtain last element of an array](https://flexiple.com/javascript/get-last-array-element-javascript/#section12)

[Formatting and styling console methods](https://www.youtube.com/watch?v=UUoZ_U2_4tA)

[parseInt()](https://www.w3schools.com/jsref/jsref_parseint.asp)

[Array.find()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find)

[Sets in Javascript](https://www.geeksforgeeks.org/sets-in-javascript/)

[Mutation observer](https://www.youtube.com/watch?v=Mi4EF9K87aM)

[Javascript tilde](https://wsvincent.com/javascript-tilde/#:~:text=In%20JavaScript%2C%20the%20tilde%20~%20Bitwise,a%20String%20object%20passed%20in.)

[Implement linked lists w/ test driven development](https://www.youtube.com/watch?v=gJjPWA8wpQg)

[Identifying through includes array of objects contains value](https://stackoverflow.com/questions/49187940/javascript-using-includes-to-find-if-an-array-of-objects-contains-a-specific)

[Using Array.some to find object in array of objects contains value](https://stackoverflow.com/a/8217584)

[Looping through or enumerating a JS object](https://stackoverflow.com/questions/684672/how-do-i-loop-through-or-enumerate-a-javascript-object)

```javascript
eg.

const p = {
    "p1": "value1",
    "p2": "value2",
    "p3": "value3"
};

for (const [key, value] of Object.entries(p)) {
  console.log(`${key}: ${value}`);
}

```

[Destructuring object property and also object itself](https://stackoverflow.com/questions/65354700/destructure-object-property-and-whole-object-itself)

[Array.every() documentation](https://www.w3schools.com/jsref/jsref_every.asp)

[Sorting array based on another array](https://stackoverflow.com/questions/13304543/javascript-sort-array-based-on-another-array)

```javascript
const coreMarkets = [
  { iso2: 'at', name: 'Austria' },
  { iso2: 'ch', name: 'Switzerland' },
  { iso2: 'de', name: 'Germany' },
  { iso2: 'es', name: 'Spain' },
  { iso2: 'fi', name: 'Finland' },
  { iso2: 'gb', name: 'Great Britain' },
  { iso2: 'it', name: 'Italy' }
]
const marketFocus = ['de', 'es', 'it', 'gb', 'ch', 'fi', 'at']

const sortMarkets = (array, sortArray) => {
  return [...array].sort(
    (a, b) => sortArray.indexOf(a.iso2) - sortArray.indexOf(b.iso2)
  )
}

sortMarkets(coreMarkets, marketFocus)
// [
//   { "iso2": "de", "name": "Germany" },
//   { "iso2": "es", "name": "Spain" },
//   { "iso2": "it", "name": "Italy" },
//   . . .
// ]
```
> Note: copy array [...array].sort() or you might mutate the original array. You can also use array.slice().sort() for that.

[Math.random()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)

[Divide a string into n equal parts](https://www.youtube.com/watch?v=O7GdshOYljE)

[Clone object without certain keys](https://stackoverflow.com/questions/34698905/how-can-i-clone-a-javascript-object-except-for-one-key)

[Sorting object array based on date property](https://stackoverflow.com/questions/10123953/how-to-sort-an-object-array-by-date-property)

[Finding the sum of an array of numbers](https://stackoverflow.com/questions/1230233/how-to-find-the-sum-of-an-array-of-numbers)

[Selecting elements w/ data attributes in JS for functionality](https://stackoverflow.com/questions/2487747/selecting-element-by-data-attribute-with-jquery)

[Parsing string to date](https://stackoverflow.com/questions/5619202/parsing-a-string-to-a-date-in-javascript)

[Difference between script rendering and downloading w/ async and defer](https://stackoverflow.com/questions/10808109/script-tag-async-defer)

[String.replace()](https://www.w3schools.com/jsref/jsref_replace.asp)

[Array.slice() Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice)

[Array.splice() Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice)

[Array.splice() YT - Florin Pop](https://www.youtube.com/watch?v=FFas8cMHVwg)

[Array.splice() YT - Free Code Camp](https://www.youtube.com/watch?v=-8L4B5X-BFA)

[Enums w/ symbols](https://www.sohamkamani.com/javascript/enums/?utm_content=cmp-true)

[Symbols docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol)

[Why does implicit Symbol to String conversion' lead to TypeError in JavaScript?](https://stackoverflow.com/questions/40944470/why-does-implicit-symbol-to-string-conversion-lead-to-typeerror-in-javascript)

[Colt Steele: The Complete Guide to JS Symbols ES6](https://www.youtube.com/watch?v=4J5hnOCj69w)

[Change element positions in array and shift elements in between](https://stackoverflow.com/questions/44932502/change-elements-positions-in-an-array-and-shift-elements-in-between)

[update highlighted nav link upon scroll](http://jsfiddle.net/Ty_Yang/80t9p3n4/)

[How can I detect the scrollTop of an element using Vanilla Javascript?](https://stackoverflow.com/a/50432070)

[Array.findIndex(): Get index of object inside array matching condition](https://stackoverflow.com/questions/15997879/get-the-index-of-the-object-inside-an-array-matching-a-condition)

[Medium.com: JS function chaining](https://medium.com/technofunnel/javascript-function-chaining-8b2fbef76f7f)

[Zipping two arrays of objects](https://stackoverflow.com/questions/71422566/how-to-zip-two-arrays-object-in-javascript)

[Converting an array of key-value tuples into an object](https://stackoverflow.com/questions/32002176/how-to-convert-an-array-of-key-value-tuples-into-an-object)

[Hexlet.io: explicit and implicit fn parameters](https://hexlet.io/blog/posts/code-complete-explicit-and-implicit-function-parameters)

[Zip arrays](https://stackoverflow.com/questions/22015684/zip-arrays-in-javascript)

[YT: Implicit Parameters, whether to use or not?](https://www.youtube.com/watch?v=fwu3lLpgZsg)

[W3Schools: array.findIndex fn](https://www.w3schools.com/jsref/jsref_findindex.asp)

[How to get function parameter names/values dynamically?](https://stackoverflow.com/questions/1007981/how-to-get-function-parameter-names-values-dynamically)

[How to console log the name of a variable/function?](https://stackoverflow.com/a/48087922)

[Removing specific item from array](https://sentry.io/answers/remove-specific-item-from-array/)

[WDS: Why i write my numbers like this - 1_000_000](https://www.youtube.com/shorts/bFNxVXXlDEQ)

<br>

Stack Overflow: Convert array to object
- [Convert array to object](https://stackoverflow.com/questions/4215737/convert-array-to-object)
- [Best way to implement conversion of array to object](https://stackoverflow.com/questions/41827019/javascript-whats-the-best-way-convert-array-into-object)

<br>

Stack Overflow: JavaScript function chaining
- [JS method chaining and the this object](https://stackoverflow.com/questions/25205030/javascript-method-chaining-and-the-this-object)
- [Can method chaining be implemented the way built in functions in javascript are](https://stackoverflow.com/questions/69595934/can-method-chaining-be-implemented-the-way-built-in-functions-in-javascript-are)
- [Method chaining using javascript not working](https://stackoverflow.com/questions/28097633/method-chaining-using-javascript-not-working)
- [How to chain an anonymous function in jquery](https://stackoverflow.com/questions/4393019/how-to-chain-an-anonymous-function-in-jquery)
- [Async function chaining](https://stackoverflow.com/questions/39028882/chaining-async-method-calls-javascript)


[IIFE Docs: JS github docs](https://github.com/airbnb/javascript/blob/master/README.md#functions--iife)

[Anonymous function reasoning](https://stackoverflow.com/questions/2421911/what-is-the-purpose-of-wrapping-whole-javascript-files-in-anonymous-functions-li?rq=2)

[Destructuring overview in Javascript - Javascript.info](https://javascript.info/destructuring-assignment)

[Destructuring arrays in Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)

[Conditional attribute component addition](https://stackoverflow.com/questions/31163693/how-do-i-conditionally-add-attributes-to-react-components)

[V8 internals of JS engine for developers](https://www.youtube.com/watch?v=m9cTaYI95Zc&t=1500s)

<br>

Stack Overflow: Console methods
- [Console.log | util.inspect for nested object/array](https://stackoverflow.com/questions/21524415/node-console-log-util-inspect-for-nested-object-array)
- [Duplicate of above](https://stackoverflow.com/questions/10729276/how-can-i-get-the-full-object-in-node-jss-console-log-rather-than-object)
- [Wrapper fn for console.log with correct line numbers](https://stackoverflow.com/questions/13815640/a-proper-wrapper-for-console-log-with-correct-line-number)

<br>

Array Constructor: Predefined length
- [new Array(?), ? is array length](https://stackoverflow.com/questions/43256119/how-does-new-array5-map-work)
- [Creating and filling arrays of arbitrary lengths](https://2ality.com/2018/12/creating-arrays.html#:~:text=One%20common%20way%20of%20creating,has%20holes%20in%20it%20assert.)
- []()
- []()

<br>

`React`

[Dispatch in React](https://www.youtube.com/results?search_query=dispatch+react)

[UseReducer in React](https://www.youtube.com/watch?v=kK_Wqx3RnHk)

[3 beginner React mistakes that can ruin your app](https://www.youtube.com/watch?v=oc_TNtCe2sY)

[Learn React error boundaries in 7 minutes](https://www.youtube.com/watch?v=_FuDMEgIy7I)

[Junior vs senior React folder structure - how to organize React projects](https://www.youtube.com/watch?v=UUga4-z7b6s)

[rendering "[object object]" if placed next to a concatenated text](https://react.dev/reference/react/Fragment)




