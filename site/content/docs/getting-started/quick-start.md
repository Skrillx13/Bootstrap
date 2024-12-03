---
layout: docs
title: Quick Start
description: Create your Bootstrap Project in minutes thanks to our Quick Start Guide.
group: getting-started
toc: true
---

Create a new Bootstrap Project within 5 minutes thanks to our production-ready CSS and JavaScript, as well as our CDN links for instant usage. *Try Bootstrap out with our [CodePen Demo](https://codepen.io/team/bootstrap/pen/qBamdLj).*

## 1. Create a new `.html` file

Name this file `index.html`, and place it in the root of your Project Directory. We include the `<meta name="viewport">` to ensure responsive behaviour in mobile devices.

{{< callout info >}}
We highly recommend using Bootstrap throughout your Project to help with Consistency. This is best done by creating your Project in a new directory.
{{< /callout >}}

``` html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Bootstrapped Project</title>
</head>

<body>
    <h1>Hello World!</h1>
    <p>This is my first Bootstrap project!</p>
</body>

</html>
```

## 2. Referencing Our CDN's

Place the Stylesheet link in the `<head>` for our Compiled CSS, and the JavaScript link at the end of the closing `<body>` for our Compiled & Bundled CSS. **Placing the JavaScript tag before the closing `<body>` element helps load the JavaScript first, which is a priority.**

``` html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <title>My Bootstrapped Project</title>
</head>

<body>
    <h1>Hello World!</h1>
    <p>This is my first Bootstrap project!</p>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>

</html>
```

## 3. Viewing Your Project

Open up your HTMl `index.html` file in the browser, and you will notice that your Project has been Bootstrapped! From here, you can start creating your own layouts, adding components to fill up those layouts, and even customize your site with you own colours.