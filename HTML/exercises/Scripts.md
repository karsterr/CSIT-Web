# **HTML Scripts**

**1. Use JavaScript to change the HTML content of the <p> element to "Hello World!".**

```
<body>
    
    <p id="demo">Hi.</p>

    <script>
        document.getElementById("demo").innerHTML = "Hello World!";
    </script>

</body>
```

**2. Use JavaScript to change the text size of the <p> element to 40 pixels.**

```
<body>
    
    <p id="demo">Hi.</p>
    
    <script>
        document.getElementById("demo").style.fontSize = 40px;
    </script>

</body>
```

**3.Use JavaScript to set the color of the <p> element to "red".**

```
<body>
    
    <p id="demo">Hi.</p>
    
    <script>
        document.getElementById("demo").style.color = red;
    </script>

</body>
```

**4. Use JavaScript to change the image source from "scream.png" to "smiley.gif".**

```
<body>
    
    <p id="demo">Hi.</p>
    
    <script>
        document.getElementById("demo").src = smiley.gif;
    </script>

</body>
```