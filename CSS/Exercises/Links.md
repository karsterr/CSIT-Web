# **CSS Links**

**1.Set the color of links to "red".**

```
<style>
    a {
        color: red;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <a href="http://w3schools.com">This is a link</a>
</body>
```

**2. Set the style when you mouse over a link (hover) to red.**

```
<style>
    a:hover {
        color: red;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <a href="http://w3schools.com">This is a link</a>
</body>
```

**3. Set the style for links to pages you have visited to red.**

```
<style>
    a:visited {
        color: red;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <a href="http://w3schools.com">This is a link</a>
</body>
```

**4. Remove the default underline style for links, but add a underline when you mouse over a link (hover).**

```
<style>
/* unvisited link */
    a:link{text-decoration: none;}

/* visited link */
    a:visited{text-decoration: none;}

/* mouse over link */
    a:hover{text-decoration: underline;}
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <a href="http://w3schools.com">This is a link</a>
</body>
```