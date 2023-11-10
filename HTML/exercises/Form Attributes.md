# **HTML Form Attributes**

**1. Add a submit button, and specify that the form should go to "/action_page.php".**

```
<form action="/action_page.php">
    Name: <input type="text" name="name">
    <input type="submit">
</form>
```

**2. Specify that the form is submitted using the "POST" method.**

```
<form action="/action_page.php" method="POST">
    Name: <input type="text" name="name">
    <input type="submit">
</form>
```