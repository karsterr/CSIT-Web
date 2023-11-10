# **CSS Background**

**1. Set the background color of the h1 element to "lightblue".**

```
<style>
    h1 {
        background-color: lightblue;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <p>This is a paragraph</p>
</body>
```

**2. Set "paper.gif" as the background image of the page.**

```
<style>
    body {
        background-image:url("paper.gif");
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <p>This is a paragraph</p>
</body>
```

**3. Make the background image repeat only vertically.**

```
<style>
    body {
        background-image: url("img_tree.png");
        background-repeat: repeat-y;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <p>This is a paragraph</p>
</body>
```

**4. Specify that the background image should be shown once, in the top right corner.**

```
<style>
    body {
        background-image: url("img_tree.png");
        background-repeat: no-repeat;
        background-position: top right;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <p>This is a paragraph</p>
</body>
```

**5. Use the correct background property to make the background image NOT scroll with the rest of the page.**

```
<style>
    body {
        background-image: url("img_tree.png");
        background-attachment: fixed;
    }
</style>
```