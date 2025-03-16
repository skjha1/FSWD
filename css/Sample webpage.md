```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Attractive webpage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to our website</h1>
        <p>Your one-stop destination for amazing technical content.</p>
    </header>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <section class="main-content">
       <h2>About Us.</h2>
       <p>This is our website where you will fine interesting technical blogs on daily basis.</p>
    </section>

    <aside>
        <h3>Latest Posts</h3>
        <ul>
            <li><a href="#">Post 1</a></li>
            <li><a href="#">Post 2</a></li>
            <li><a href="#">Post 3</a></li>
        </ul>
    </aside>

    <footer>
        <p>&copy; 2025 Our website. All rights reserved</p>
    </footer>

</body>
</html>
```


```css
body {
    font-family: Arial, Helvetica, sans-serif;
    margin: 0;
    padding: 0;
}

header {
   background-color: #333; 
   color: #fff;
   padding: 20px;
   text-align: center;
}

.main-content {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #f0f0f0;
}

footer {
    background-color: #333; 
    color: #fff;
    padding: 10px;
    text-align: center;
 }

 nav {
    background-color: #333;
    padding: 10px 20px;
 }

 nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
 }

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li:last-child {
    margin-right: 0;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
    padding: 5px 10px;
    border-radius: 5px;
}

nav ul li a:hover {
    background-color: #555;
}

aside {
    background-color: #f4f4f4;
    padding: 20px;
}
aside h3 {
    color: #333;
    font-size: 18px;
    margin-bottom: 15px;
}
aside ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
}
aside ul li a {
    text-decoration: none;
    color: #666;
    font-weight: bold;
}

aside ul li a:hover{
    color: #333;
}



```
