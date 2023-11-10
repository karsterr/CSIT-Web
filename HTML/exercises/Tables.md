# **HTML Tables**

**1. Add a table row with two table headers. The two table headers should have the value "Name" and "Age".**

```
<table>
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>Jill Smith</td>
        <td>50</td>
    </tr>
</table>
```

**2. Use the correct CSS border values to create a solid black 3 pixels border on a table element.**

```
table, th, td {
  border: 3px solid black;
}
```

**3. Use CSS styles to make the table 300 pixels wide.**

```
<table style="width:300px;">
    <tr>
        <th>First Name</th>
        <th>Last Name</th>
        <th>Points</th>
    </tr>
    <tr>
        <td>Jill</td>
        <td>Smith</td>
        <td>50</td>
    </tr>
</table>
```

**4. Add a table caption that says "Names".**

```
<table>
    <caption>Names</caption>
    <tr>
        <th>First Name</th>
        <th>Last Name</th>
        <th>Points</th>
    </tr>
    <tr>
        <td>Jill</td>
        <td>Smith</td>
        <td>50</td>
    </tr>
</table>
```

**5. Use the correct CSS property to add 15 pixels of space between the cell border and cell content.**

```
.table td {
    padding:15px;
}
```

**6. Use the correct HTML attribute to make the second TH element span two rows.**

```
<table>
    <tr>
        <th>Name</th>
        <td>Jill Smith</td>
    </tr>
    <tr>
        <th rowspan="2">Phone</th>
        <td>555-77854</td>
    </tr>
    <tr>
        <td>555-77854</td>
    </tr>
</table>
```

**7. Use the correct HTML attribute to make the first TH element span two columns.**

```
<table>
    <tr>
        <th colspan="2">Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>Jill</td>
        <td>Smith</td>
        <td>50</td>
    </tr>
    <tr>
        <td>Eve</td>
        <td>Jackson</td>
        <td>94</td>
    </tr>
</table>
```

**8. Add a table row at the end of the table, with two table cells. The two table cells should have the value "Eve Jackson" and "94".**

```
<table>
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>Jill Smith</td>
        <td>50</td>
    </tr>
    <tr>
        <td>Eve Jackson</td>
        <td>94</td>
    </tr>
```