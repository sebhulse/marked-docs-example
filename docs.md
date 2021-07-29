## Code Quick Look

This is the fantastic JavaScript code for the fantastic docs, as seen in the fantastic article.

#### Code

```JavaScript
const docs = "docs.md"
async function run() {
  let file = await fetch(docs)
  let text = await file.text()
  document.getElementById('content').innerHTML =
    marked(text);
  hljs.highlightAll();
}
run()
```
