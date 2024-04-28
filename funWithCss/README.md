In this project, you will experiment and implement fun layout with HTML and CSS **ONLY**!

Yes, no JavaScript!

Enjoy!

Tasks
-----

### 0\. Sprite languages

#advanced

Score: 100.0% (Checks completed: 100.0%)

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 0- Sprite</title>

        <link href="0-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <ul>
            <li>HTML<span class="icon i-html"></span></li>
            <li>CSS<span class="icon i-css"></span></li>
            <li>JavaScript<span class="icon i-js"></span></li>
        </ul>
    </body>
</html>

```

And this image file: [0-sprite.png](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/d416199ca6ecdbd0f8a3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240428%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240428T144925Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=a1a289e12e007746920365f6b7211ae4404da7afeb73fcf0113edb7b30b1e942 "0-sprite.png")

Create `0-styles.css` and generate this layout:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/94aa60f76c412f40a87b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240428%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240428T144925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a3dc03bcecc83a7dbea943abc014cdb280c110d554c951f1f18f283fb65e0b97)

You are not allowed to change the image and the HTML - *sprite is cool!*

**Repo:**

-   GitHub repository: `alx-frontend-for-fun`
-   File: `0-styles.css`

 Done? QA Review

### 1\. Move the (under)line

#advanced

Score: 100.0% (Checks completed: 100.0%)

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 1- Underline</title>

        <link href="1-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <h2>
            Hello <a href="https://www.holbertonschool.com">Holberton!</a>
        </h2>
    </body>
</html>

```

Create `1-styles.css` and generate this layout where the underline is hidden by default and appeared slowly...:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/b791cfdbd11c0eefa5f7.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240428%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240428T144925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=bf149a23739941e4e2850ddeb35aefba88d14d640bebb03feba0bcad4c9d2d83)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository: `alx-frontend-for-fun`
-   File: `1-styles.css`

 Done? QA Review

### 2\. Toggle

#advanced

Score: 100.0% (Checks completed: 100.0%)

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link href="2-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <div class="toggle">
            <input type="checkbox" name="toggle" class="toggle-cb" id="toggle-0" checked>
            <label class="toggle-label" for="toggle-0">
                <div class="toggle-inner"></div>
                <div class="toggle-switch"></div>
            </label>
        </div>
    </body>
</html>

```

Create `2-styles.css` and generate this layout where the `<input>` is has this custom toggle layout:

**Checked:**

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/3848b025c8f25636bba5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240428%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240428T144925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=738f2edd8e23b475a3b70226c78c17ff7194fad32193893973e5cb033fba24d6)

**Unchecked:**

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/aeae59fdee93b17f360f.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240428%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240428T144925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=12940d5e863b82bc7209e17a9f688424467a77430299efbdd9bf8f89362dd0de)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository: `alx-frontend-for-fun`
-   File: `2-styles.css`

 Done? QA Review

### 3\. Menu

#advanced

Score: 100.0% (Checks completed: 100.0%)

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
        <link href="3-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>

        <nav class="menu">
            <input type="checkbox" href="#" class="menu-open" name="menu-open" id="menu-open"/>
            <label class="menu-open-button" for="menu-open">
                <span class="menu-line menu-line-1"></span>
                <span class="menu-line menu-line-2"></span>
                <span class="menu-line menu-line-3"></span>
            </label>

            <a href="#" class="menu-item"> <i class="fa fa-area-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-bar-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-line-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-pie-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-table"></i> </a>
        </nav>

    </body>
</html>

```

Create `3-styles.css` and generate this layout/animation:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/252a25667dc7c65fe0e9.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240428%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240428T144925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=375229bb40250e63626a56611dae91c97d923a3681d41ec461d4daf52ba4b63a)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository: `alx-frontend-for-fun`
-   File: `3-styles.css`

 Done? QA Review

Ready for a new peer review

Copyright © 2024 ALX, All rights reserved.