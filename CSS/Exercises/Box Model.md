# **CSS Box Model**

**1. Set the width of the div element to "200px".**

```
<style>
    div {
        width:200px;
    }
</style>

<body>

    <div>
    Lorem ipsum dolor sit amet,
    consectetur adipiscing elit,
    sed do eiusmod tempor incididunt
    ut labore et dolore magna aliqua.
    </div>

</body>
```

**2. Add a 2px solid red border to the div element.**

```
<style>
    div {
        width:200px;
        border:2px solid red;
    }
</style>

<body>

    <div>
    Lorem ipsum dolor sit amet,
    consectetur adipiscing elit,
    sed do eiusmod tempor incididunt
    ut labore et dolore magna aliqua.
    </div>

</body>
```

**3. Add 25 pixels space between the div element's border and its content.**

```
<style>
    div {
        width:200px;
        border:2px solid red;
        padding:25px;
    }
</style>

<body>

    <div>
    Lorem ipsum dolor sit amet,
    consectetur adipiscing elit,
    sed do eiusmod tempor incididunt
    ut labore et dolore magna aliqua.
    </div>

</body>
```

**4. Add a 25 pixels space outside, to the left of the div element.**

```
<style>
    div {
        width:200px;
        border:2px solid red;
        padding:25px;
        margin-left:25px;
    }
</style>

<body>

    <div>
    Lorem ipsum dolor sit amet,
    consectetur adipiscing elit,
    sed do eiusmod tempor incididunt
    ut labore et dolore magna aliqua.
    </div>

</body>
```