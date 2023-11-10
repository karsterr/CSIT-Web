# **CSS Selectors**

**1. Set the text color to red, for all <p> elements.**

```
<style>
    p {
        color:red;
    }
</style>
```

**2. Set the text color to red, for the element with id="para1"**

```
<style>
    #para1{
        color:red;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p id="para1">This is a paragraph</p>
</body>
```

**3. Set the text color to red, for elements with class="colortext".**

```
<style>
    .colortext{
        color:red;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <p class="colortext">This is a paragraph</p>
    <p class="colortext">This is a paragraph</p>
</body>
```

**4. Set the text color to red, for all <p> and <h1> elements. Group the selectors to minimize code.**

```
<style>
    h1, p{
        color:red;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <h2>This is a smaller heading</h2>
    <p>This is a paragraph</p>
    <p>This is a paragraph</p>
</body>
```