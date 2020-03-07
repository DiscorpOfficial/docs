# Colour Changing

As you have guessed by the title this code will make you background change from one colour to another!

First of all get a base html file...

```markup
<!DOCTYPE html>
<html>
<head>
</head>
<body>
</body>
</html>
```

Now we add our text and that..

```markup
<!DOCTYPE html>
<html>
<style> 
<head>
    <title>My Site</title>
</head>
<body>
    <h1>Jhon Doe</h1>
    <p>I like programming</p>
</body>
</html>
```

and finally our little code to change the colour...

```markup
<!DOCTYPE html>
<html>
<head>
  <title>My Site</title>
  <style> 
    body {
      background: red;
      animation: kns 8s infinite;
    }

    @keyframes kns {
      from {background-color: red;}
      to {background-color: blue;}
    }
  </style>
</head>
<body>
    <h1>Jhon Doe</h1>
    <p>I like programming</p>
</body>
</html>
```

![](../.gitbook/assets/screen-capture-1.webm)

