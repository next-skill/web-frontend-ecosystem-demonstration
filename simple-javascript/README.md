# simple-javascript

## javascript-on-console

```javascript
const textInput = document.getElementById('text-input')
const submitButton = document.getElementById('submit-button')

textInput.oninput = (event) => {
  const inputValue = event.target.value
  // 入力欄の値が空文字などの場合はボタンは disabled=true、その他の場合は disabled=false にする
  submitButton.disabled = !inputValue
}
```
