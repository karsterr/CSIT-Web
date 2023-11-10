# **CSS Display/Visibility**

**1. Hide the h1 element. It should still take up the same space as before.**

```
<style>
    h1 {
        visibility: hidden;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <p>This is a paragraph</p>
</body>
```

**2. Hide the h1 element. It should NOT take up any space.**

```
<style>
    h1 {
        display:none;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <p>This is a paragraph</p>
</body>
```

**3. Display the list items as inline elements.**

```
<style>
    li {
        display: inline;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <p>This is a paragraph</p>
</body>
```

**4.Display the strong elements as block elements.**

```
<style>
    strong {
        display:block;
    }
</style>

<body>
    <h1>This is a heading</h1>
    <p>This is a <strong>paragraph</strong></p>
</body>
```