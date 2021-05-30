## Getting Started with Web development

> #### HTML,CSS and JS


```html
//This is HTML and JS//

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JS Practice</title>
    <link rel="stylesheet" href="index.css">
    <!-- <script src="main.js"></script> -->
</head>
<body>
    <p>Player 1 : Chris</p>
<script>
    
    const para = document.querySelector('p');
  
    para.addEventListener('click', updateName);

    function updateName() {
        let name = prompt('Enter a new name');
        para.textContent = 'Player 1: ' + name;
    }

</script>
</body>
</html>
```
---

```css

//This is CSS part//

p {
    font-family: 'helvetica neue', helvetica, sans-serif;
    letter-spacing: 1px;
    text-transform: uppercase;
    text-align: center;
    border: 2px solid rgba(0,0,200,0.6);
    background: rgba(0,0,200,0.3);
    color: rgba(0,0,200,0.6);
    box-shadow: 1px 1px 2px rgba(0,0,200,0.4);
    border-radius: 10px;
    padding: 3px 10px;
    display: inline-block;
    cursor: pointer;
  }
```
---

This is the Output 
![Output](output_1.PNG)