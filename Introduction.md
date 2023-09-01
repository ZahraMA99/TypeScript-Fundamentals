## Introduction:earth_africa:
### What is TypeScript?
- TypeScript is an open source, typed syntactic superset of JavaScript.
- TypeScript is a strongly typed programming language that builds on JavaScript, giving you better tooling at any scale.
### Why developers want types
1. It allows you, as a code author, to leave more of your intent “on the page” => Types make the author’s intent more clear
```js
function add(a: number, b: number): number {
  return a + b
}
add(3, 4);
```
2. It has the potential to move some kinds of errors from runtime to compile time, *Examples:*
- Values that are potentially absent (null or undefined)<br/>
- Incomplete refactoring<br/>
- Breakage around internal code contracts (e.g., an argument becomes required)<br/>
3. It serves as the foundation for a great code authoring experience<br/>
