## About Me

Hi, my name is **Candra Dwi Cahyo**, I come from Indonesia and I was born in East Java, Malang.  I learned programming language in 2018 until now and I am a **front end web developer**.  What languages ​​have I studied?
* HTML
* CSS 
* JavaScript
* PHP

framework that I have used :
* Bootstrap
* Codeigniter

library that i have used :
* JQuery

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="./style.css">
  <title>Introduction</title>
</head>
<body>
  <input type="text" placeholder="enter your name...">
  <button type="button">Enter</button>
  <script src="./script.js"></script>
</body>
</html>
```
```CSS
* {
  margin: 0;
  padding: 0;
  font-family: sans-serif;
  box-sizing: border-box;
}

body { 
  background-color: royalblue; 
}
```
```javascript
window.addEventListener('load', () => {
  const input = document.querySelector('input');
  const button = document.querySelector('button');
  button.addEventListener('click', () => {
    if (!input.value) return alert('input is required');
    return alert(input.value);
  });
});
```
