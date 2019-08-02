<h1>mymenu.js</h1>
This file is to create expentable or collapsable menu using custom tag my-menu and my-menu-header based on javascript
<h2>Expand Menu</h2>
<img src="https://github.com/Jack5s/JavascriptMenu/blob/master/Image/expand.png"/>
<h2>Collapse Menu</h2>
<img src="https://github.com/Jack5s/JavascriptMenu/blob/master/Image/collapse.png"/>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
<my-menu expandState="expend">
    <my-menu-header>
        <div>Title</div>
    </my-menu-header>
    <p>It is a paragraph</p>
    <p>It is also a paragraph</p>
</my-menu>
<my-menu expandState="expend">
    <my-menu-header>
        <div>Title2</div>
    </my-menu-header>
    <p>It is a paragraph2</p>
    <p>It is also a paragraph2</p>
</my-menu>
<script src="https://raw.githack.com/Jack5s/JavascriptMenu/master/web/JS/jquery.js"></script>
<script src="https://raw.githack.com/Jack5s/JavascriptMenu/master/web/JS/MyJS/mymenu.js"></script>
</body>
</html>

<h2>HTML</h2> 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
<my-menu expandState="expend">
    <my-menu-header>
        <div>Title</div>
    </my-menu-header>
    <p>It is a paragraph</p>
    <p>It is also a paragraph</p>
</my-menu>
<my-menu expandState="expend">
    <my-menu-header>
        <div>Title2</div>
    </my-menu-header>
    <p>It is a paragraph2</p>
    <p>It is also a paragraph2</p>
</my-menu>
<script src="../JS/jquery.js"></script>
<script src="../JS/MyJS/mymenu.js"></script>
</body>
</html>
```
