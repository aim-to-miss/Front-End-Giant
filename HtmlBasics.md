# Table of contents
1. [Basic Structure](#basicStructure)
2. [Elements](#elements)
    1.[Headings](#headings)
    2.[Paragraph](#paragraph)
    - [Sub](#sub)
    - [Sup](#sup)
    - [Strong](#strong)
    - [Emphasize](#emphasize)
    - [Bold](#bold)
    - [Italic](#italic)
    - [Underline](#underline)

    3.[Image](#image)
    4.[link](#link)



## 1. Basic HTML Page Structure <a name="basicStructure"></a>
```html
<!DOCTYPE html>
<html>
  <head>
    <title>
      Document Name
    </title>
    <meta >
    <link  />
  </head>
  <body>
    Page content
  </body>
</html>"
```
`!Docktype`: HTML Version

`Head` : Meta, Links, Title. Will not be visible after rendered.

## 2. Elements <a name="elements"></a>

### 2.1 Headlines <a name="headings"></a>
Used for adding heading where ever we need it.
```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```
#### Output:
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

### 2.2 Paragraph <a name="paragraph"></a>
`white space collapsing`: Will ignore all the extra white spaces. Html collapses white-spaces.\
`attribute`: describe the element.

```html
<p>One line paragraph</p>

<p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in<br /> reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</p>
```
#### 2.2.1 Sub <a name="sub"></a>
```html
<p>(A word)<sub>Below another word</sub></p>
```
<p>(A word)<sub>Below another word</sub></p>

#### 2.2.2 Sup <a name="sup"></a>
```html
<p>(A word)<sup>Over another word</sup></p>
```
<p>(A word)<sup>Over another word</sup></p>

#### 2.2.3 Strong <a name="strong"></a>
```html
<p>This is a <strong> Strong </strong> word</p>
```
<p>This is a <strong> Strong </strong> word</p>

#### 2.2.4 Emphasize <a name="emphasize"></a>
```html
<p>This word is <em>Emphisized</em></p>
```
<p>This word is <em>Emphisized</em></p>

#### 2.2.5 Bold <a name="bold"></a>
```html
<p>I am <b>Bold</b></p>
```
<p>I am <b>Bold</b></p>

#### 2.2.6 Italic <a name="italic"></a>
```html
<p>Pain starts with <i>Italic</i></p>
```
<p>Pain starts with <i>Italic</i></p>

#### 2.2.7 Underline <a name="underline"></a>
```html
<p>Sometimes you need to <u>Underline</u></p>
```
<p>Sometimes you need to <u>Underline</u></p>



### 2.3 Image <a name="Image"></a>
```html
<img src="" alt="">
```
`src` : Source of the image.\
`alt`: Alternative text for the image, if the image is not loaded.

### 2.4 Link <a name="Image"></a>
```html
<a href="#">Go Check It</a>
```
`href` : Redirect location\
We can have both internal link and external link.
```html
<a href="index.html"></a>
<a href="#paragraph"></a>
<a href="#"><img src="" /></a>
```
