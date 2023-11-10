# **CSS Links**

**1. Set the list style for unordered lists to "square".**

```
<style>
    ul {
        list-style-type:square;
    }
</style>

<body>
    <ul>
        <li>Coffee</li>
        <li>Tea</li>
        <li>Coca Cola</li>
    </ul>
</body>
```

**2. Change the list's item marker to an image called 'bling.jpg':**

```
<style>
    ul {
        list-style-image:url(bling.jpg);
    }
</style>

<body>
    <ul>
        <li>Coffee</li>
        <li>Tea</li>
        <li>Coca Cola</li>
    </ul>
</body>
```

**3. Remove the bullets/markers from the list items.**

```
<style>
    ul {
        list-style-type:none;
    }
</style>

<body>
    <ul>
        <li>Coffee</li>
        <li>Tea</li>
        <li>Coca Cola</li>
    </ul>
</body>
```

**4. Set the list style to I, II, III, instead of 1, 2, 3 for ordered lists.**

```
<style>
    ol {
        list-style-type:upper-roman;
    }
</style>

<body>
    <ol>
        <li>Coffee</li>
        <li>Tea</li>
        <li>Coca Cola</li>
    </ol>
</body>
```