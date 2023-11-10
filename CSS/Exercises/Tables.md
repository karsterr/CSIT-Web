# **CSS Tables**

**1. Set the border to "2px solid green" for table, th and td elements.**

```
<style>
    table,td,th {
        border: 2px solid green;
    }
</style>

<body>
    <table>
        <tr>
            <th>Firstname</th>
            <th>Lastname</th>
        </tr>
        <tr>
            <td>Peter</td>
            <td>Griffin</td>
        </tr>
        <tr>
            <td>Lois</td>
            <td>Griffin</td>
        </tr>
    </table>
</body>
```

**2. Collapse the table borders into a single border.**

```
<style>
    table {
        border-collapse: collapse;
    }
</style>

<body>
    <table>
        <tr>
            <th>Firstname</th>
            <th>Lastname</th>
        </tr>
        <tr>
            <td>Peter</td>
            <td>Griffin</td>
        </tr>
        <tr>
            <td>Lois</td>
            <td>Griffin</td>
        </tr>
    </table>
</body>
```

**3. Use inline styles to set the width of the table to "100%".**

```
<table style="width:100%">
    <tr>
        <th>Firstname</th>
        <th>Lastname</th>
    </tr>
    <tr>
        <td>Peter</td>
        <td>Griffin</td>
    </tr>
    <tr>
        <td>Lois</td>
        <td>Griffin</td>
    </tr>
</table>
```

**4. Set the text alignment in td elements to "right".**

```
<style>
    table,td,th {
        border: 1px solid green;
    }

    td{
        text-align:right;
    }
</style>

<body>
    <table>
        <tr>
            <th>Firstname</th>
            <th>Lastname</th>
        </tr>
        <tr>
            <td>Peter</td>
            <td>Griffin</td>
        </tr>
        <tr>
            <td>Lois</td>
            <td>Griffin</td>
        </tr>
    </table>
</body>
```

**5. Set the padding in th elements to "15px".**

```
<style>
    table,td,th {
        border: 1px solid green;
    }

    th{
        padding:15px;
    }
</style>

<body>
    <table>
        <tr>
            <th>Firstname</th>
            <th>Lastname</th>
        </tr>
        <tr>
            <td>Peter</td>
            <td>Griffin</td>
        </tr>
        <tr>
            <td>Lois</td>
            <td>Griffin</td>
        </tr>
    </table>
</body>
```

**6. Set the background color of th elements to "lightblue".**

```
<style>
    table,td,th {
        border: 1px solid green;
    }

    th {
        background-color:lightblue;
    }
</style>

<body>
    <table>
        <tr>
            <th>Firstname</th>
            <th>Lastname</th>
        </tr>
        <tr>
            <td>Peter</td>
            <td>Griffin</td>
        </tr>
        <tr>
            <td>Lois</td>
            <td>Griffin</td>
        </tr>
    </table>
</body>
```