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

NB: Some content may look same with different tag. But all device does not read html as the same. So we need to be careful about that.\

#### 2.2.8 Special Characters <a name="specialCharacters"></a>
Basic syntax:
```html
 nameofCharacter;
```
We can also use the code number of the Special characters.
```html
 CodeNumber;
```
Example:
```html
<p>
    Let's add a Copywite Character:  &copy;
    We can also use code for the specialCharacters:  &#169;
</p>
```
<p>
    Let's add a Copywite Character:  &copy;<br/>
    We can also use code for the specialCharacters:  &#169;
</p>

#### 2.2.9 Abbreviation <a name="abbreviation"></a>
Basic syntax:
```html
<abbr title="...fullform...">Short Form</abbr>
```
Example:
```html
<abbr title="Bachelor of Science">BSc</abbr>
```
<abbr title="Bachelor of Science">BSc</abbr>

#### 2.2.10 Address <a name="address"></a>
Basic syntax:
```html
<address>
    otherTags
</address>
```
Example:
```html
<address>
  Written by Author <br />
  Visit us at:<br />
  Example.com<br />
  Box 564, Disneyland<br />
  USA
</address>
```
<address>
  Written by Author <br />
  Visit us at:<br />
  Example.com<br />
  Box 564, Disneyland<br />
  USA
</address>


#### 2.2.11 Abbreviation <a name="abbreviation"></a>
Basic syntax:
```html
<article>
    Other Content
</article>
```
The `article` tag specifies independent, self-contained content. Potential sources for the `article` element:
1. Forum post
2. Blog post
3. News story

Example:
```html
<article>
<h2>Joke 01</h2>
<p>Programming is fun.</p>
</article>
```
<article>
<h2>Joke 01</h2>
<p>Programming is fun.</p>
</article>

#### 2.2.9 Abbreviation <a name="abbreviation"></a>
Basic syntax:
```html

```
Example:
```html
```


#### 2.2.9 Abbreviation <a name="abbreviation"></a>
Basic syntax:
```html

```
Example:
```html
```


#### 2.2.9 Abbreviation <a name="abbreviation"></a>
Basic syntax:
```html

```
Example:
```html
```


#### 2.2.9 Abbreviation <a name="abbreviation"></a>
Basic syntax:
```html

```
Example:
```html
```


#### 2.2.9 Abbreviation <a name="abbreviation"></a>
Basic syntax:
```html

```
Example:
```html
```


#### 2.2.9 Abbreviation <a name="abbreviation"></a>
Basic syntax:
```html

```
Example:
```html
```


#### 2.2.9 Abbreviation <a name="abbreviation"></a>
Basic syntax:
```html

```
Example:
```html
```


#### 2.2.9 Abbreviation <a name="abbreviation"></a>
Basic syntax:
```html

```
Example:
```html
```



#### 2.2.9 Abbreviation <a name="abbreviation"></a>
Basic syntax:
```html

```
Example:
```html
```

#### 2.2.9 Abbreviation <a name="abbreviation"></a>
Basic syntax:
```html

```
Example:
```html
```


#### 2.2.9 Abbreviation <a name="abbreviation"></a>
Basic syntax:
```html

```
Example:
```html
```


#### 2.2.9 Abbreviation <a name="abbreviation"></a>
Basic syntax:
```html

```
Example:
```html
```




### 2.3 Image <a name="Image"></a>
```html
<img src="" alt="">
```
`src` : Source of the image.\
`alt`: Alternative text for the image, if the image is not loaded.

There are `map` and `area` element that can be used for mapping clickable area in an image. But to do so the `img` element must have to have an attrubute `usemap` assigning the name of the map.
Basic syntax:
```html
<img src="" alt=""  usemap="#id"/>
<map name="workmap">
  <area
    shape
    coords
    alt
    href
  />
  ...
</map>
```
The `map` map is used to define an image map. An image map is an image with click able areas. The `area` tag defines an area inside an image map.\
`sahpe`: Represent the shape of the area. i.e: `rect`,`circle`.\
`coords`: Represent the co-ordinates of the shape. Number of value depends on the shape.\
`alt`: Alternative text.\
`href`: Hyper link that will be redirected after clicking the area.

Example:
```html
<map name="workmap">
  <area
    shape="rect"
    coords="34,44,270,350"
    alt="Computer"
    href="#"
  />
  <area
    shape="rect"
    coords="290,172,333,250"
    alt="Phone"
    href="#"
  />
</map>
```

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

### 2.5 List <a name="list"></a>
#### 2.5.1 Unordered List <a name="unorderedList"></a>
Basic syntax:
```html
<ui>
    <li>...</li>
</ui>
```

Example:
```html
<ui>
    <li>Item 01</li>
    <li>Item 02</li>
    <li>Item 03</li>
</ui>
```
<ui>
    <li>Item 01</li>
    <li>Item 02</li>
    <li>Item 03</li>
</ui>

#### 2.5.2 Ordered List <a name="orderedList"></a>
Basic syntax:
```html
<ol>
    <li>...</li>
</ol>
```

Example:
```html
<ol>
    <li>Item 01</li>
    <li>Item 02</li>
    <li>Item 03</li>
</ol>
```
<ol>
    <li>Item 01</li>
    <li>Item 02</li>
    <li>Item 03</li>
</ol>

#### 2.5.3 Nasted List <a name="nastedList"></a>
Example:
```html
<ul>
    <li>Item01</li>
    <li>
        Item02
        <ol>
            <li>SubItem01</li>
            <li>SubItem02</li>
        </ol>
    </li>
    <li>Item03</li>
</ul>
```
<ul>
    <li>Item01</li>
    <li>
        Item02
        <ol>
            <li>SubItem01</li>
            <li>SubItem02</li>
        </ol>
    </li>
    <li>Item03</li>
</ul>

### 2.6 Table <a name="table"></a>
Basic Syntax:
```html
<table>
    <tr>
        <th>...</th>
    </tr>
    <tr>
        <td>...</td>
    </tr>
    ...
</table>
```
Example:
```html
<table>
    <tr>
        <th>Column 01</th>
        <th>Column 02</th>
        <th>Column 03</th>
    </tr>
    <tr>
        <td>Item 01</td>
        <td>Item 02</td>
        <td>Item 03</td>
    </tr>
    <tr>
        <td>Item 11</td>
        <td>Item 12</td>
        <td>Item 13</td>
    </tr>
</table>
```
<table>
    <tr>
        <th>Column 01</th>
        <th>Column 02</th>
        <th>Column 03</th>
    </tr>
    <tr>
        <td>Item 01</td>
        <td>Item 02</td>
        <td>Item 03</td>
    </tr>
    <tr>
        <td>Item 11</td>
        <td>Item 12</td>
        <td>Item 13</td>
    </tr>
</table>


### 2.7 Form <a name="form"></a>
Basic Syntax:
```html
<form class="" action="" method="">
    <label for="">...</label>
    <input type="" name="" value="" id="">
    <input type="" name="" placeholder="">
    <input type="text" name="" value="">
    <input type="submit" name="" value="">
    <button type="button" name="button">From Submit</button>
</form>
```
`form`: Every from element must be wrapped with the from tag.\
`label`: Element is used to label a form field. We also use other element ie. `p` for labeling. But `label` element gives a flexibility. It the `label text` is clicked the targeted field becomes highlighted. `for` attribute of the form takes the `id` of the specified `input` element. In other world we need to give the `id` to the `input` element, and put that `id` value in the `for` attribute of the `label` element.\
`name`: Name attribute of the `input` element is required for further operations.\
`placeholder`: placeholder attributes `input` is use to describe the expected to the user.\
`value`: Value attribute of `input` field is used to provide some default value to the input field. The difference between the value and the placeholder attribute is that placeholder value get vanished as soon as the user start to type anything in the field, but for `value` it just concatenate after the default value.\
`submit`: Input type submit can be used to submit a from.\
`button`: Button element can also be used for from submission.\

Example:
```html
<form class="" action="index.html" method="post">
    <ul>
        <li>
            <label for="labeledField">Label for input field, related with ID</label><br>
            <input type="text" name="" value="" id="labeledField">
        </li>
        <li>
            <p>Label without label Element</p>
            <input type="text" name="withoutLabel" placeholder="Wtrite what you expect">
        </li>
        <li><input type="text"  value="preDefinedValue"></li>
        <li><input type="submit"  value="Button Text - Go"></li>
        <li><input type="checkbox" > Check if you understand</li>
        <li><input type="color"> Select your color</li>
        <li>Pick Up your required date: <input type="date"></li>
        <li>Pick Up your required date with time: <input type="datetime-local"></li>
        <li>Enter email: <input type="email"></li>
        <li><input type="file"> Select file to upload</li>
        <li>There is a field, But you can not see it. <input type="hidden"></li>
        <li><input type="image"> Upload your image</li>
        <li>Just pick up the month of a year: <input type="month"></li>
        <li>Dial Your Numbr: <input type="number"></li>
        <li><input type="password" placeholder="Password"> Password please!!!</li>
        <li>
            <input type="radio"> Item to check 01 <br>
            <input type="radio"> Item to check 02
        </li>
        <li><input type="range"> How much angry are you?</li>
        <li><input type="reset"> Reset all the value.</li>
        <li><input type="search"> Search Anything. But you will get nothing.</li>
        <li>May be you cal call your Parents: <input type="tel" name="" value=""></li>
        <li>Tell me when you get up: <input type="time"></li>
        <li><input type="url"> : Make me Frieds</li>
        <li>Take any week of a year for vacation: <input type="week"></li>
    </ul>
    <button type="button" name="button">From Submit</button>
</form>
```
NB: All other input type of the form can be found in Appendix - 2

#### 2.7.2 Text Area <a name="textArea"></a>
`textarea` is used for taking bulk of input. We can specify the number of columns and number of rows with the `cols` and `rows` attribute.

```html
<textarea name="name" rows="8" cols="80"></textarea>
```
#### 2.7.3 Dropdown (select) <a name="dropdown"></a>
We can make a simple dropdown using the `select` element.
Simple Syntax:
```html
<select class="" name="">
    <option value="...">...</option>
    ...
</select>
```
Example:
```html
<select class="" name="">
    <option value="item01">Item01</option>
    <option value="item02">Item02</option>
    <option value="item03">Item03</option>
</select>
```
<select class="" name="">
    <option value="item01">Item01</option>
    <option value="item02">Item02</option>
    <option value="item03">Item03</option>
</select>

## 3. Header Area <a name="headerArea"></a>
### 3.1 Meta <a name="meta"></a>
`meta` actually is the **Data of the Data**. Different type of attribute of meta is being used. Some of them are:
1. `cahrset` : Character set used.
2. `description`: Description of the web page.
3. `keywords`: Define keywords for the search engine.
4. `author`: Define the author of the page.
5. `http-equiv`: Refresh the page after some defined seconds.
6. `viewport`: Setting the viewport for all the devices.

```html
<meta charset="UTF-8">
<meta name="description" content="Free Web tutorials">
<meta name="keywords" content="HTML, CSS, JavaScript">
<meta name="author" content="John Doe">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
## 4. Multimedia <a name="multimedia"></a>
### 4.1 Audio <a name="audio"></a>
Basic syntax:
```html
<audio
    ...attributes...
    preload="auto/metadata/none"
    onplay="invokeFunction()"
    >
    <source src="..." type="audio/...fileType...">
    <source src="..." type="audio/...fileType...">
    Text that will be shown when error.
</audio>
```
`audio` element is used embed the audio in the page. `source` element is used to specify the source of the audio. `src` attribute is used to specify the source of the audio `type` attribute a specifies the file type.We can have multiple `source` element. The valid one will play first. `audio` element have `preload` attribute to preload the audio before paly. Any text between the tag element will be only shown if there is error in playing the audio.\
`audio` element have other different attributes for audio controls.\
`controls`: Enables the audio control, browser default.\
`autoplay`: Autoplayes the audio after load.\
`loop`: Loop the audio.\
`muted`: Mute the audio by default.\

Example:
```html
<audio controls autoplay loop>
    <source src="./assets/audio/bensound-ukulele.mp3" type="audio/mp3">
</audio>
```
<audio controls autoplay loop>
    <source src="./assets/audio/bensound-ukulele.mp3" type="audio/mp3">
</audio>

### 4.2 Video <a name="video"></a>
Basic syntax:
```html
<video
    ...attributes...
    >
    <source src="..." type="video/...fileType...">
    <source src="..." type="video/...fileType...">
    Text that will be shown when error.
</video>
```
`video` element is used embed the video in the page. `source` element is used to specify the source of the audio. `src` attribute is used to specify the source of the audio `type` attribute a specifies the file type. Attributes for video elements are:\
`autoplay`: **Values:** autoplay - Specifies that the video will play automatically.\
`controls`: **Values:** controls - Specifies that the video controls gets displayed.\
`loop`: **Values:** loop - Specifies that the video will start again every time after finish.\
`height`: **Values:** pixels - Specifies the height.\
`weight`: **Values:** pixels - Specifies the width.\
`muted`:**Values:** muted - Specifies that the audio should be muted.\
`poster`: **Values:** URL - Specifies the image to be shown while the video is downloading.\
`preload`: **Values:** auto, metadat, none - Specifies what author thinks will lead to user experience at its best.
`src`: **Values:** URL - Specifies the URL.


### Appendix -1
All Special Characters list and Code.\

| Character | Character Code | Character name | Description                       |
|-----------|----------------|----------------|-----------------------------------|
|Space      | 160            | nbsp           | non-breaking space                |
|¡          | 161;           |  iexcl;        | inverted exclamation mark         |
|¢          | 162            |  cent;         | cent                              |
|£          |  163;          |  pound;        | pound                             |
| ¤         |  164;          |  curren;       | currency                          |
| ¥         |  165;          |  yen;          | yen                               |
| ¦         |  166;          |  brvbar;       | broken vertical bar               |
| §         |  167;          |  sect;         | section                           |
| ¨         |  168;          |  uml;          | spacing diaeresis                 |
| ©         |  169;          |  copy;         | copyright                         |
| ª         |  170;          |  ordf;         | feminine ordinal indicator        |
| «         |  171;          |  laquo;        | angle quotation mark (left)       |
| ¬         |  172;          |  not;          | negation                          |
| ­          |  173;          |  shy;          | soft hyphen                       |
| ®         |  174;          |  reg;          | registered trademark              |
| ¯         |  175;          |  macr;         | spacing macron                    |
| °         |  176;          |  deg;          | degree                            |
| ±         |  177;          |  plusmn;       | plus-or-minus                     |
| ²         |  178;          |  sup2;         | superscript 2                     |
| ³         |  179;          |  sup3;         | superscript 3                     |
| ´         |  180;          |  acute;        | spacing acute                     |
| µ         |  181;          |  micro;        | micro                             |
| ¶         |  182;          |  para;         | paragraph                         |
| ·         |  183;          |  middot;       | middle dot                        |
| ¸         |  184;          |  cedil;        | spacing cedilla                   |
| ¹         |  185;          |  sup1;         | superscript 1                     |
| º         |  186;          |  ordm;         | masculine ordinal indicator       |
| »         |  187;          |  raquo;        | angle quotation mark (right)      |
| ¼         |  188;          |  frac14;       | fraction 1/4                      |
| ½         |  189;          |  frac12;       | fraction 1/2                      |
| ¾         |  190;          |  frac34;       | fraction 3/4                      |
| ¿         |  191;          |  iquest;       | inverted question mark            |
| ×         |  215;          |  times;        | multiplication                    |
| ÷         |  247;          |  divide;       | division                          |
| "         |  34;           |  quot;         | quotation mark                    |
| '         |  39;           |  apos;         | apostrophe                        |
|           |  38;           |  amp;          | ampersand                         |
| <         |  60;           |  lt;           | less-than                         |
| >         |  62;           |  gt;           | greater-than                      |
| Œ         |  338;          |  OElig;        | capital ligature OE               |
| œ         |  339;          |  oelig;        | small ligature oe                 |
| Š         |  352;          |  Scaron;       | capital S with caron              |
| š         |  353;          |  scaron;       | small S with caron                |
| Ÿ         |  376;          |  Yuml;         | capital Y with diaeres            |
| ƒ         |  402;          |  fnof;         | f with hook                       |
| ˆ         |  710;          |  circ;         | modifier letter circumflex accent |
| ˜         |  732;          |  tilde;        | small tilde                       |
|           |  8194;         |  ensp;         | en space                          |
|          |  8195;         |  emsp;         | em space                          |
|           |  8201;         |  thinsp;       | thin space                        |
| ‌          |  8204;         |  zwnj;         | zero width non-joiner             |
| ‍          |  8205;         |  zwj;          | zero width joiner                 |
| ‎          |  8206;         |  lrm;          | left-to-right mark                |
|           |  ‏          |           820  rlm;| right-to-left mark                |  
| –         |  8211;         |  ndash;        | en dash                           |
| —         |  8212;         |  mdash;        | em dash                           |
| ‘         |  8216;         |  lsquo;        | left single quotation mark        |
| ’         |  8217;        |  rsquo;        | right single quotation mark       |
| ‚         |  8218;        |  sbquo;        | single low-9 quotation mark       |
| “         |  8220;        |  ldquo;        | left double quotation mark        |
| ”         |  8221;        |  rdquo;        | right double quotation mark       |
| „         |  8222;        |  bdquo;        | double low-9 quotation mark       |
| †         |  8224;        |  dagger;       | dagger                            |
| ‡         |  8225;        |  Dagger;       | double dagger                     |
| •         |  8226;        |  bull;         | bullet                            |
| …         |  8230;        |  hellip;       | horizontal ellipsis               |
| ‰         |  8240;        |  permil;       | per mille                         |
| ′         |  8242;        |  prime;        | minutes                           |
| ″         |  8243;        |  Prime;        | seconds                           |
| ‹         |  8249;        |  lsaquo;       | single left angle quotation       |
| ›         |  8250;        |  rsaquo;       | single right angle quotation      |
| ‾         |  8254;        |  oline;        | overline                          |
| €         |  8364;        |  euro;         | euro                              |
| ™         |  8482;        |  trade;        | trademark                         |
| ←         |  8592;        |  larr;         | left arrow                        |
| ↑         |  8593;        |  uarr;         | up arrow                          |
| →         |  8594;        |  rarr;         | right arrow                       |
| ↓         |  8595;        |  darr;         | down arrow                        |
| ↔         |  8596;        |  harr;         | left right arrow                  |
| ↵        |  8629;        |  crarr;        | carriage return arrow             |
| ⌈         |  8968;        |  lceil;        | left ceiling                      |
| ⌉         |  8969;        |  rceil;        | right ceiling                     |
| ⌊         |  8970;        |  lfloor;       | left floor                        |
| ⌋         |  8971;        |  rfloor;       | right floor                       |
| ◊         |  9674;        |  loz;          | lozenge                           |
| ♠         |  9824;        |  spades;       | spade                             |
| ♣         |  9827;        |  clubs;        | club                              |
| ♥         |  9829;        |  hearts;       | heart                             |
| ♦         |  9830;        |  diams;        | diamond                           |
| ∀         |  8704;        |  forall;       | for all                           |
| ∂         |  8706;        |  part;         | part                              |
| ∃         |  8707;        |  exist;        | exists                            |
| ∅         |  8709;        |  empty;        | empty                             |
| ∇        |  8711;        |  nabla;        | nabla                             |
| ∈         |  8712;        |  isin;         | isin                              |
| ∉        |  8713;        |  notin;        | notin                             |
| ∋        |  8715;        |  ni;           | ni                                |
| ∏         |  8719;        |  prod;         | prod                              |
| ∑         |  8721;        |  sum;          | sum                               |
| −         |  8722;        |  minus;        | minus                             |
| ∗         |  8727;        |  lowast;       | lowast                            |
| √         |  8730;        |  radic;        | square root                       |
| ∝        |  8733;        |  prop;         | proportional to                   |
| ∞         |  8734;        |  infin;        | infinity                          |
| ∠        |  8736;        |  ang;          | angle                             |
| ∧        |  8743;        |  and;          | and                               |
| ∨        |  8744;        |  or;           | or                                |
| ∩         |  8745;        |  cap;          | cap                               |
| ∪         |  8746;        |  cup;          | cup                               |
| ∫         |  8747;        |  int;          | integral                          |
| ∴        |  8756;        |  there4;       | therefore                         |
| ∼        |  8764;        |  sim;          | similar to                        |
| ≅        |  8773;        |  cong;         | congruent to                      |
| ≈         |  8776;        |  asymp;        | almost equal                      |
| ≠         |  8800;        |  ne;           | not equal                         |
| ≡         |  8801;        |  equiv;        | equivalent                        |
| ≤         |  8804;        |  le;           | less or equal                     |
| ≥         |  8805;        |  ge;           | greater or equal                  |
| ⊂        |  8834;        |  sub;          | subset of                         |
| ⊃        |  8835;        |  sup;          | superset of                       |
| ⊄        |  8836;        |  nsub;         | not subset of                     |
| ⊆        |  8838;        |  sube;         | subset or equal                   |
| ⊇        |  8839;        |  supe;         | superset or equal                 |
| ⊕         |  8853;        |  oplus;        | circled plus                      |
| ⊗        |  8855;        |  otimes;       | circled times                     |
| ⊥        |  8869;        |  perp;         | perpendicular                     |
| ⋅         |  8901;        |  sdot;         | dot operator                      |
| À         |  192;         |  Agrave;       | capital a, grave accent           |
| Á         |  193;         |  Aacute;       | capital a, acute accent           |
| Â         |  194;         |  Acirc;        | capital a, circumflex accent      |
| Ã         |  195;         |  Atilde;       | capital a, tilde                  |
| Ä         |  196;         |  Auml;         | capital a, umlaut mark            |
| Å         |  197;         |  Aring;        | capital a, ring                   |
| Æ         |  198;         |  AElig;        | capital ae                        |
| Ç         |  199;         |  Ccedil;       | capital c, cedilla                |
| È         |  200;         |  Egrave;       | capital e, grave accent           |
| É         |  201;         |  Eacute;       | capital e, acute accent           |
| Ê         |  202;         |  Ecirc;        | capital e, circumflex accent      |
| Ë         |  203;         |  Euml;         | capital e, umlaut mark            |
| Ì         |  204;         |  Igrave;       | capital i, grave accent           |
| Í         |  205;         |  Iacute;       | capital i, acute accent           |
| Î         |  206;         |  Icirc;        | capital i, circumflex accent      |
| Ï         |  207;         |  Iuml;         | capital i, umlaut mark            |
| Ð         |  208;         |  ETH;          | capital eth, Icelandic            |
| Ñ         |  209;         |  Ntilde;       | capital n, tilde                  |
| Ò         |  210;         |  Ograve;       | capital o, grave accent           |
| Ó         |  211;         |  Oacute;       | capital o, acute accent           |
| Ô         |  212;         |  Ocirc;        | capital o, circumflex accent      |
| Õ         |  213;         |  Otilde;       | capital o, tilde                  |
| Ö         |  214;         |  Ouml;         | capital o, umlaut mark            |
| Ø         |  216;         |  Oslash;       | capital o, slash                  |
| Ù         |  217;         |  Ugrave;       | capital u, grave accent           |
| Ú         |  218;         |  Uacute;       | capital u, acute accent           |
| Û         |  219;         |  Ucirc;        | capital u, circumflex accent      |
| Ü         |  220;         |  Uuml;         | capital u, umlaut mark            |
| Ý         |  221;         |  Yacute;       | capital y, acute accent           |
| Þ         |  222;         |  THORN;        | capital THORN, Icelandic          |
| ß         |  223;         |  szlig;        | small sharp s, German             |
| à         |  224;         |  agrave;       | small a, grave accent             |
| á         |  225;         |  aacute;       | small a, acute accent             |
| â         |  226;         |  acirc;        | small a, circumflex accent        |
| ã         |  227;         |  atilde;       | small a, tilde                    |
| ä         |  228;         |  auml;         | small a, umlaut mark              |
| å         |  229;         |  aring;        | small a, ring                     |
| æ         |  230;         |  aelig;        | small ae                          |
| ç         |  231;         |  ccedil;       | small c, cedilla                  |
| è         |  232;         |  egrave;       | small e, grave accent             |
| é         |  233;         |  eacute;       | small e, acute accent             |
| ê         |  234;         |  ecirc;        | small e, circumflex accent        |
| ë         |  235;         |  euml;         | small e, umlaut mark              |
| ì         |  236;         |  igrave;       | small i, grave accent             |
| í         |  237;         |  iacute;       | small i, acute accent             |
| î         |  238;         |  icirc;        | small i, circumflex accent        |
| ï         |  239;         |  iuml;         | small i, umlaut mark              |
| ð         |  240;         |  eth;          | small eth, Icelandic              |
| ñ         |  241;         |  ntilde;       | small n, tilde                    |
| ò         |  242;         |  ograve;       | small o, grave accent             |
| ó         |  243;         |  oacute;       | small o, acute accent             |
| ô         |  244;         |  ocirc;        | small o, circumflex accent        |
| õ         |  245;         |  otilde;       | small o, tilde                    |
| ö         |  246;         |  ouml;         | small o, umlaut mark              |
| ø         |  248;         |  oslash;       | small o, slash                    |
| ù         |  249;         |  ugrave;       | small u, grave accent             |
| ú         |  250;         |  uacute;       | small u, acute accent             |
| û         |  251;         |  ucirc;        | small u, circumflex accent        |
| ü         |  252;         |  uuml;         | small u, umlaut mark              |
| ý         |  253;         |  yacute;       | small y, acute accent             |
| þ         |  254;         |  thorn;        | small thorn, Icelandic            |
| ÿ         |  255;         |  yuml;         | small y, umlaut mark              |

### Appendix -2:
All input types for form:\

Type  | Description
------------- | -------------
`button` | Defines a clickable button (mostly used with a JavaScript to activate a script)
`checkbox` | Defines a checkbox
`color` |Defines a color picker
`date` |	Defines a date control (year, month, day (no time))
`datetime-local` |	Defines a date and time control (year, month, day, time (no timezone)
`email` |	Defines a field for an e-mail address
`file` |	Defines a file-select field and a "Browse" button (for file uploads)
`hidden` |	Defines a hidden input field
`image` | Defines an image as the submit button
`month`	| Defines a month and year control (no timezone)
`number` |	Defines a field for entering a number
`password` |	Defines a password field
`radio`	| Defines a radio button
`range`	| Defines a range control (like a slider control)
`reset`	| Defines a reset button
`search` |	Defines a text field for entering a search string
`submit` |	Defines a submit button
`tel`	| Defines a field for entering a telephone number
`text`	| Default. Defines a single-line text field
`time`	| Defines a control for entering a time (no timezone)
`url`	| Defines a field for entering a URL
`week`	| Defines a week and year control (no timezone)

#### Appendix - 3:
All Tags in one place:

|Tag|Description|
|---|-----------|
|`<!-- ..-->`|Comment|
|`<!DOCTYPE>`|Defines the document type|
|`<a>`|Defines a Hyper link|
|`<abbr>`|Defines an abbreviation or an acronym|
|`<address>`|Defines a contract information for the author of the document|
|`<area>`|Defines an area inside an image map |
|`<article>`|Defines an article |
|`<aside>`|Defines content aside from the page content|
|`<audio>`|Defines embedded sound content|
|`<b>`|Defines bold text|
|`<base>`|Defines specifies the base url in document|
|`<bdi>`|Isolate a part of the text that might be formatted in a different direction from other text|
|`<bdo>`| Override the current text direction|
|`<blockquote>`|Defines a section that is quoted from another source|
|`<body>`|Defines the document's body|
|`<br>`|Defines the single line break|
|`<button>`|Defines a click able button |
|`<canvas>`|Used to draw graphics|
|`<caption>`|Defines a table captions |
|`<cite>`|Defines the title of a work|
|`<code>`|Defines a piece of computer code |
|`<col>`| Specifies column properties for each column within  a `<colgroup>` element|
|`<colgroup>`|Specifies a group of one or more columns in a table fro formatting|
|`<data>`|Adds a machine-readable translation of a given content |
|`<datalist>`|Specifies a list of pre-defined options for input controls |
|`<dd>`|Defines a description/value of a term in a description list|
|`<del>`|Defines a text that has been deleted from a document|
|`<details>`|Defines additional details that the user can view or hide|
|`<dfn>`|Specifies a term that is going to be defined within the content|
|`<dialog>`|Defines a dialog box or window|
|`<div>`|Defines a section in a document|
|`<dl>`|Defines a description list|
|`<dt>`|Defines a term/name in a description list|
|`<em>`|Defines emphasized text |
|`<embed>`|Defines a container for an external application|
|`<fieldset>`|Groups related elements in a from|
|`<figcaption>`|Defines caption for a figure element |
|`<figure>`|Specifies self-contained content|
|`<footer>`|Defines a footer for a document|
|`<form>`|Defines HTML froms for user input |
|`<h1> to <h6>`|Defines HTML headlines|
|`<head>`|Contains metadata for the document |
|`<header>`|Defines a header for a document|
|`<hr>`|Defines a thematic change in the content |
|`<html>`|Defines the root of an HTML document|
|`<i>`|Defines a part of the text in an alternate voice or mood|
|`<iframe>`|Defines an inline iframe|
|`<img>`|Defines an image|
|`<input>`|Defines an input control|
|`<ins>`|Defines a text that has been inserted into a document|
|`<kbd>`|Defines keyboard input|
|`<label>`|Defines a label for an input element |
|`<legend>`|Defines a caption for a `<fieldset>` element |
|`<li>`|Defines alist item |
|`<link>`|Defines the relationship between a document and an external resource |
|`<main>`|Specifies the main content of a document |
|`<map>`|Defines an image map|
|`<mark>`|Defines mark or highlighted text|
|`<meta>`|Defines meta about an HTML document|
|`<meter>`|Defines a scalar measurement within a known range|
|`<nav>`|Defines a navigation link |
|`<noscript>`|Defines an alternative content for user that do not support client-side scripts|
|`<object>`|Defines a container for an external application |
|`<ol>`|Defines an ordered list|
|`<optgroup>`|Defines a group of related options in a drop-down list|
|`<option>`|Defines an option in a drop-down list|
|`<output>`|Defines the result of a calculation|
|`<p>`|Defines a paragraph|
|`<param>`|Defines a parameter for an object|
|`<picture>`|Defines a container for multiple image resources|
|`<pre>`|Defines preformed text|
|`<progress>`|Represents the progress of a task|
|`<q>`|Defines a short quotation|
|`<rp>`|Defines what to show in browsers that do not support ruby annotations|
|`<ruby>`|Defines an explanation of characters|
|`<s>`|Defines text that is no longer correct|
|`<samp>`|Defines sample output from a computer program|
|`<script>`|Defines a client-side script|
|`<section>`|Defines a section in a document|
|`<select>`|Defines a drop-down list |
|`<samll>`|Defines smaller text|
|`<source>`|Defines  multiple media resources fro media element|
|`<span>`|Defines a section in a document|
|`<strong>`|Defines important text |
|`<style>`|Defines style information for a document |
|`<sub>`|Defines subscription text |
|`<summary>`|Defines a visible heading for a `<details>` element |
|`<sup>`|Defines superscripted text |
|`<svg>`|Defines a container for SVG graphics |
|`<table>`|Defines a table|
|`<tbody>`|Groups the body content in a table|
|`<td>`|Defines a cell in the table|
|`<template>`|Defines a container for content that should be hidden when the page loads|
|`<textarea>`|Defines a multi line input control|
|`<tfoot>`|Groups the footer content in a table|
|`<th>`|Defines a header cell in a table|
|`<thead>`|Groups the header content in a table|
|`<time>`|Defines a specific time|
|`<title>`|Defines a title for the document|
|`<tr>`|Defines a row in a table|
|`<track>`|Defines text tracks for media elements|
|`<u>`|Defines some text that is unarticulated and styled differently from normal text|
|`<ul>`|Defines an unordered list|
|`<var>`|Defines a variable |
|`<video>`|Defines embedded video content|
|`<wbr>`|Defines a possible line-break|
