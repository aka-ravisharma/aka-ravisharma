[![SpaceX](https://img.shields.io/badge/SpaceX-000000?style=for-the-badge&logo=spacex&logoColor=white)](https://spacex.com)
[![Black Hole](https://img.shields.io/badge/Black_Hole-000000?style=for-the-badge&logo=blackhole&logoColor=white&labelColor=FF00FF)](https://example.com)
[![Astronomy](https://img.shields.io/badge/Astronomy-6D3BFF?style=for-the-badge&logo=telescope&logoColor=white)](https://example.com)

```javascript
// Click the copy icon that appears on hover
const greet = () => console.log("Hello World!");
greet();
```

```js filename="greet.js"
// Filename appears above the block
function greet(name) {
  return `Hello ${name}!`;
}
```

```bash
# With dollar prefix indicating commands
$ npm install
$ node greet.js
```

```tree
project/
├── src/
│   ├── index.js
│   └── utils.js
└── package.json
```

```diff
// Changes are highlighted
- const oldCode = "deprecated";
+ const newCode = "shiny";
```

<div class="code-container">
  <button onclick="copyCode()">Copy</button>
  <pre><code id="code-block">
function copyExample() {
  return "This uses JavaScript to copy";
}</code></pre>
</div>

<script>
function copyCode() {
  const code = document.getElementById('code-block').innerText;
  navigator.clipboard.writeText(code);
}
</script>

[![Copy](https://img.shields.io/badge/-Copy%20Me!-brightgreen?style=flat-square)] `const copyThis = "value";`

<!-- Instruction comment -->

```js
// Click the copy button above →
const example = "This will be copied";
```
