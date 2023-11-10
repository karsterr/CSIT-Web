# **CSS Text**

**1. Change the text color of all p elements to "red".**

```
<style>
    p {
        color: red;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <p>This is a paragraph</p>
</body>
```

**2. Center align the p elements.**

```
<style>
    p {
        text-align:center;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <p>This is a paragraph</p>
</body>
```

**3. Remove the underline from the link.**

```
<style>
    a{
        text-decoration:none;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <a href="http://w3schools.com">This is a link</a>
</body>
```

**4. Style text in h1 to uppercase letters, and text in p to capitalized letters.**

```

<style>
    h1 {
        text-transform:uppercase;
    }

    p {
        text-decoration:lowercase;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
</body>
```

**1. Indent the first line of the p element with 20px.**

```
<style>
    p{
        text-indent:20px;
    }
</style>

<p>
Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.
</p>
```