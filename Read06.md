# Read: 06 - Dynamic web pages with JavaScript

What is JavaScript? 

 >JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. -- mdn web docs_
 
It's programming language that can make your website more dynamic. **HTML** and **CSS** alone makes a website *static*; you do not interact with it. With **JavaScript**, you can now interact with it. The file extension for it is **.js**. In *HTML* the Javascript code is the **`<script>`** tag.

### Input Output in plain JavaScript

JavaScript (JS) enables a website to receive an input and return an output. The HTML example below shows how JS code looks inside of a `<body>` element. This code and Image from Code Maven website, will allow a user to *input* their first and last names and will produce an *output*;
a greeting followed by their name.

```
<body>
 
First name: <input id="first_name">
Last name: <input id="last_name">
<button id="say">Say hi!</button>
 
<hr>
<div id="result"></div>
 
<script>
function say_hi() {
    var fname = document.getElementById('first_name').value;
    var lname = document.getElementById('last_name').value;
 
    var html = 'Hello <b>' + fname + '</b> ' + lname;
 
    document.getElementById('result').innerHTML = html;
}
 
document.getElementById('say').addEventListener('click', say_hi);
</script>
 
</body>
```
![]("https://code-maven.com/img/input_form.png")

