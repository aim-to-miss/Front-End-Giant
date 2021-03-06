# Table of contents

1. [Basic Structure](#basicStructure)
2. [Elements](#elements) 1.[Headings](#headings) 2.[Paragraph](#paragraph)

   - [Sub](#sub)
   - [Sup](#sup)
   - [Strong](#strong)
   - [Emphasize](#emphasize)
   - [Bold](#bold)
   - [Italic](#italic)
   - [Underline](#underline)

     3.[Image](#image) 4.[link](#link)

## 1. Basic HTML Page Structure <a name="basicStructure"></a>

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Document Name</title>
    <meta />
    <link />
  </head>
  <body>
    Page content
  </body>
</html>
"
```

`!Docktype`: HTML Version

`Head` : Meta, Links, Title. Will not be visible after rendered.

`link`: Link element specifies the relationship betewwn the current documewnt
and the external resource.

```html
<link
  rel="...."
  href="...."
  sizes="...X..."
  type=""
  media=""
  as=""
  crossorigin=""
/>
```

1. `as`: Specific class of content.(Used when `preload` or `pre-fetched` is
   used.) \
2. `crossorigin`: Weather the resource should be fetched with a CORS
   request.(`anonymous`: A cross-origin performed without
   cred,`use-credentials`;)\
3. `type`: Refers to the MIME type.
4. `href`: Refers to the path of the resource.\
5. `rel` : is for relationship.\
6. `disabled`: for `rel=stylesheet`, if disabled is specified in the HTML when
   it is loaded, the stylesheet will not be loaded during page load.

There are different type of links:\

- `alternate`: Alternate stylesheet.\
- `author`: Hyperlink to a page describing the author.\
- `canonical`: Points to duplicate page, for crawler.\
- `dns-prefetch`:Hints to the browser that that a resource is needed, allowing
  the browser to do a DNS lookup and protocol handshaking before a user clicks
  the link.\
- `help`: HyperLink giving further help about the whole page.\
- `icon`: Defines the resource for representation in user interface.\
- `import`: Html imports.\
- `license`: Hyperlink for lisence related resource. alternative `copyright`-
  but should be avoided.\
- `manifest`: Indicates that the linked file is Web App Manifest.\
- `modulepreload`: Initiates earlt loading of modules. \
- `preconnect`: Open a connection to the linked website in advance without
  disclosing any private information.\
- `prefetch`: Suggest the browser to fetch the resource in advance.\
- `preload`: Tells the browser to download a resource in advance.\
- `search`: Hyper link refereed is specially designed for searching this
  document. \
- `stylesheet`: Defines external resource to be used as stylesheet.\
- `tag`: Indicates that the hyperlink refers to a document describing a tag that
  applies to this document.

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

`white space collapsing`: Will ignore all the extra white spaces. Html collapses
white-spaces.\
`attribute`: describe the element.

```html
<p>One line paragraph</p>

<p>
  Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
  tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
  quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
  consequat. Duis aute irure dolor in<br />
  reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
  Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia
  deserunt mollit anim id est laborum.
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

NB: Some content may look same with different tag. But all device does not read
html as the same. So we need to be careful about that.\

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
  Let's add a Copywite Character: &copy; We can also use code for the
  specialCharacters: &#169;
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
<address>otherTags</address>
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
<article>Other Content</article>
```

The `article` tag specifies independent, self-contained content. Potential
sources for the `article` element:

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

#### 2.2.12 Direction <a name="direction"></a>

Basic syntax:

```html
<bdo dir="...direction..."> ...Text need to change direction... </bdo>
```

`bdo` element is used to specify the direction of the text inside the element.
the direction goes inside `dir` attribute. Possible values are, `rtl`, `ltr`
Example:

```html
<bdo dir="rtl"> Go Right </bdo> <bdo dir="ltr"> Go Left </bdo>
```

<bdo dir="rtl">
    Go Right
</bdo>
<bdo dir="ltr">
    Go Left
</bdo>

#### 2.2.13 Blockquote <a name="blockquote"></a>

Basic syntax:

```html
<blockquote cite="http://">...block content...</blockquote>
```

`blockquote` elements indicate that the containing text is quoted from another
resource. The text is idented to the right by default. `cite` attribute for the
`blockquote` is used for the reference of the quote. Example:

```html
<blockquote cite="http://">
  <p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
    consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
    cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
    non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
  </p>
</blockquote>
```

<blockquote cite="http://">
    <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
    </p>
</blockquote>

#### 2.2.14 Cite <a name="cite"></a>

Basic syntax:

```html
<cite>...Text...</cite>
```

Example:

```html
<cite>Most valuable text</cite>
```

<cite>Most valuable text</cite>

#### 2.2.15 Abbreviation <a name="abbreviation"></a>

Basic syntax:

```html
<code>...code...</code>
```

Example:

```html
<code>code here. The font is browser default</code>
```

<code>code here. The font is browser default</code>

#### 2.2.16 Delete <a name="del"></a>

Basic syntax:

```html
<del>...Text..</del>
```

Example:

```html
<del>...Text..</del>
```

<del>...Text..</del> Represent a deleted text.

#### 2.2.17 Insertion <a name="ins"></a>

Basic syntax:

```html
<ins>...Text..</ins>
```

Example:

```html
<ins>...Text..</ins>
```

<ins>...Text..</ins> Represent newly inserted text.

`cite` : Defines the URI of a resource that describes the change.\
`datetime`: Indicate the date and time of the change.

#### 2.2.18 Definition <a name="definition"></a>

Basic syntax:

```html
<dfn>Term</dfn>
```

Example:

```html
<p><dfn>Unable:</dfn>A state where you are not able.</p>
```

<p><dfn>Unable:</dfn>A state where you are not able.</p>

#### 2.2.19 Dialog <a name="dialog"></a>

Basic syntax:

```html
<dialog>...Inside Content of the dialog...</dialog>
```

`dialog` element have an attribute `open` that represent the visibility of the
dialog box. Example:

```html
<dialog open>Text inside the dialog box</dialog>
```

<dialog open>
    Text inside the dialog box
</dialog>

#### 2.2.20 Content Division <a name="div"></a>

`div` is a content container that contains the content. It has no effect on the
content or layout until styled in some way using CSS Basic syntax:

```html
<div></div>
```

Example:

```html
<div><p>Text</p></div>
```

#### 2.2.21 Embed <a name="embed"></a>

Basic syntax:

```html
<embed attributes />
```

`embed` element is used to embed external content in the document. It has
different attribute for control. `src`: URL of the content.\
`type`: Type of the content.\
`width`: Width of the content.\
`height`: Height of the content in pixels. Example:

```html
<embed
  type="video/mp4"
  src="./assets/video/video.mp4"
  width="300"
  height="300"
/>
```

#### 2.2.22 Figure <a name="figure"></a>

`figure` element represents self-contained content. `figcaption` is a optional
element that adds caption to the figure. Basic syntax:

```html
<figure>
  ...Content of the figure...
  <figcaption>Figure Caption</figcaption>
</figure>
```

Example:

```html
<figure>
  <img
    src="https://developer.mozilla.org/static/img/favicon144.png"
    alt="The beautiful MDN logo."
    onContextMenu="return false;"
  />
  <figcaption>MDN Logo</figcaption>
</figure>
```

<figure>
  <img
      src="https://developer.mozilla.org/static/img/favicon144.png"
  alt="The beautiful MDN logo.">
  <figcaption>MDN Logo</figcaption>
</figure>

#### 2.2.23 Header Element <a name="header"></a>

`header` element represent the introductory of content.\
`main` element represent the dominant content of the `body` element.The `main` element
should be unique in the document. Basic syntax:

```html
<header>
  <h1>...</h1>
  . . .
  <img src="" alt="" />
</header>
<main></main>
```

Example:

```html
<header>
  <h1>Simple header of the documnet</h1>
  <img src="" alt="" />
</header>
<main></main>
```

#### 2.2.24 Mark <a name="mark"></a>

Basic syntax:

```html
<mark> .... </mark>
```

Represent marked or highlighted text. Example:

```html
<mark> Marked Text</mark>
```

<mark> Marked Text</mark>

#### 2.2.25 Output <a name="output"></a>

Basic syntax:

```html
<output name="result" for=" ... "> ... </output>
```

`output` is a container element into which a site or app can inject the result
of a calculation or the outcome of a user action.

- `name`: Elements name.\
- `for`: Space separated list of other element `id`s indicating that those
  elements contribute in the value.\
- `form`: Id of the associate owner form element. If the value is not set then
  is consider itself as the child of ancestor form element. Example:

```html
<form oninput="result.value=parseInt(a.value)+parseInt(b.value)">
  <input type="number" id="a" value="20" /> +
  <input type="number" id="b" value="40" /> : Result =
  <output name="result" for="a b">60</output>
</form>
```

#### 2.2.26 Preserve <a name="pre"></a>

Basic syntax:

```html
<pre> ... </pre>
```

Represent formatted text which will be represented exactly as written in the
html file. Example:

```html
<pre>I am Pre-formated        And space in between will be kept</pre>
```

#### 2.2.27 Quote <a name="q"></a>

Basic syntax:

```html
<q cite="...."> .... </q>
```

Indicates that the text is a short inline quotation.

- `cite`: A Url that designates a source for the reference for the quote.
  Example:

```html
<p>
  This is the quatation that I am making for the nation:
  <q cite=""
    >Never try to be a hero on social media. You Are Product. Not Consumer</q
  >
</p>
```

#### 2.2.28 Sample output <a name="samp"></a>

Basic syntax:

```html
<samp> ... </samp>
```

Enclouse inline text which represent sample output from a computer program.
Example:

```html
<p>To revoke the last local commit, type:</p>
<samp>git reset --hard HEAD~1</samp>
```

#### 2.2.29 Section <a name="section"></a>

`section` element represent a `generic` standalone section of a Document.
Sections should always have a heading, with very few exceptions. A rule of thumb
is that a <section> should logically appear in the outline of a document.

```html
<section>
  <h2>Heading</h2>
  <p>Bunch of awesome content</p>
</section>
```

Sections with no headings do not appear in the document outline. If you did want
force the inclusion of such an HTML block inside the document outline but not
affect the visual output in any way, you could include a heading but hide it.\

```html
<section>
  <h2 class="hidden">Controls</h2>
  <button class="reply">Reply</button>
  <button class="reply-all">Reply to all</button>
  <button class="fwd">Forward</button>
  <button class="del">Delete</button>
</section>
```

#### 2.2.30 Span <a name="span"></a>

`span` is a generic inline container for phrasing content which does not
inherently represent anything.(It have no meaning by itself but just a
container). It group elements for:

- Styling Purpose (`id`,`class`).
- Share attributes values (`lang`). The main difference between the `div` and
  `span` is, `div` is block level element but `span` is inline element.

```html
<p>...<span class="...">...</span>, <span class="..."> ... </span> ...</p>
```

#### 2.2.31 Small <a name="small"></a>

Basic syntax:

```html
<small> ... </small>
```

Render the text within it one font-size smaller.

#### 2.2.32 Small <a name="small"></a>

Basic syntax:

```html
<var> ... </var>
```

Represents the name of a variable. It's typically presented using an italicized
version of the current typeface.

#### 2.2.33 Footer <a name="footer"></a>

Basic syntax:

```html
<footer></footer>
```

defines the footer section. Example:

```html
<footer>Content of the footer section</footer>
```

### 2.3 Image <a name="Image"></a>

```html
<img src="" alt="" />
```

`src` : Source of the image.\
`alt`: Alternative text for the image, if the image is not loaded.

There are `map` and `area` element that can be used for mapping clickable area
in an image. But to do so the `img` element must have to have an attrubute
`usemap` assigning the name of the map. Basic syntax:

```html
<img src="" alt="" usemap="#id" />
<map name="workmap">
  <area shape coords alt href />
  ...
</map>
```

The `map` map is used to define an image map. An image map is an image with
click able areas. The `area` tag defines an area inside an image map.\
`sahpe`: Represent the shape of the area. i.e: `rect`,`circle`.\
`coords`: Represent the co-ordinates of the shape. Number of value depends on
the shape.\
`alt`: Alternative text.\
`href`: Hyper link that will be redirected after clicking the area.

Example:

```html
<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="#" />
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="#" />
</map>
```

### 2.4 Hyper Link <a name="Image"></a>

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

#### 2.5.4 Definition List <a name="definitionList"></a>

Basic syntax:

```html
<dl>
  <dt>Defination Term</dt>
  <dd>Definition</dd>
</dl>
```

Example:

```html
<dl>
  <dt>Code</dt>
  <dd>Feature that works.</dd>
  <dt>Bug</dt>
  <dd>Feature taht will not work.</dd>
</dl>
```

<dl>
    <dt>Code</dt>
    <dd>Feature that works.</dd>
    <dt>Bug</dt>
    <dd>Feature taht will not work.</dd>
</dl>

### 2.6 Table <a name="table"></a>

Basic Syntax:

```html
<table>
  <caption></caption>
  <colgroup>
    ...
  </colgroup>
  <thead>
    <tr>
      <th>...</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>...</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <th>...</th>
      <td>...</td>
    </tr>
  </tfoot>
  ...
</table>
```

`caption` element is used for adding table caption. `colgroup` element is used
to modify specified colums in a table. Modification is defined with the `col`
element. `col` element have different attributes. `span`: Defines the number of
column under consideration.\
`align`: For alignment of the text.\
`valign`: For the vertical alignment of the text.\
`bgcolor`: Specifies the background color.\
`charoff`: Specifies the number of characters to cutoff for exceeding.\
`class`: If any custom class needed.\
`style`: If any styling needed.\
`thead`,`tbody`,`tfoot` represent the table header, table body and table body section.\
Example:

```html
<table>
    <caption>Learning Table</caption>
    <colgroup>
        <col span="1" class="" style="background-color:red;">
        <col span="2" class="" style="background-color:yellow;">
    </colgroup>
    <thead>
        <tr>
            <th>Column 01</th>
            <th>Column 02</th>
            <th>Column 03</th>
        </tr>
    </thead>
    <tbody>
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
    </tbody>
    <tfoot>
        <tr>
            <th>Item 11</td>
            <th>Item 12</td>
            <th>Item 13</td>
        </tr>
    </tfoot>
</table>
```

<table>
    <colgroup>
        <col span="1" class="" style="background-color:red;">
        <col span="2" class="" style="background-color:yellow;">
    </colgroup>
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
  <fieldset>
    <legend>Caption of fieldset</legend>
    <label for="">...</label>
    <input type="" name="" value="" id="" />
    <input type="" name="" placeholder="" />
    <input type="text" name="" value="" />
    <input type="submit" name="" value="" />
  </fieldset>

  <button type="button" name="button">From Submit</button>
</form>
```

`form`: Every from element must be wrapped with the from tag.\
`fieldset`element is used to group several controls as well as labels.\
`legend` adds caption for a field set.\
`label`: Element is used to label a form field. We also use other element ie. `p`
for labeling. But `label` element gives a flexibility. It the `label text` is clicked
the targeted field becomes highlighted. `for` attribute of the form takes the `id`
of the specified `input` element. In other world we need to give the `id` to the
`input` element, and put that `id` value in the `for` attribute of the `label` element.\
`name`: Name attribute of the `input` element is required for further
operations.\
`placeholder`: placeholder attributes `input` is use to describe the expected to
the user.\
`value`: Value attribute of `input` field is used to provide some default value
to the input field. The difference between the value and the placeholder
attribute is that placeholder value get vanished as soon as the user start to
type anything in the field, but for `value` it just concatenate after the
default value.\
`submit`: Input type submit can be used to submit a from.\
`button`: Button element can also be used for from submission.\

Attributes of the fieldset:\
`disabled`: All descended form controls will be disabled, form can not be submited.
And they won't receive any browser events. elements inside `legend` will be disabled.\
`form`: Takes the `id` value of the from.\
`name`.

Example:

```html
<form class="" action="index.html" method="post">
  <fieldset>
    <legend>My be all possible input field examples</legend>
    <ul>
      <li>
        <label for="labeledField">Label for input field, related with ID</label
        ><br />
        <input type="text" name="" value="" id="labeledField" />
      </li>
      <li>
        <p>Label without label Element</p>
        <input
          type="text"
          name="withoutLabel"
          placeholder="Wtrite what you expect"
        />
      </li>
      <li><input type="text" value="preDefinedValue" /></li>
      <li><input type="submit" value="Button Text - Go" /></li>
      <li><input type="checkbox" /> Check if you understand</li>
      <li><input type="color" /> Select your color</li>
      <li>Pick Up your required date: <input type="date" /></li>
      <li>
        Pick Up your required date with time: <input type="datetime-local" />
      </li>
      <li>Enter email: <input type="email" /></li>
      <li><input type="file" /> Select file to upload</li>
      <li>There is a field, But you can not see it. <input type="hidden" /></li>
      <li><input type="image" /> Upload your image</li>
      <li>Just pick up the month of a year: <input type="month" /></li>
      <li>Dial Your Numbr: <input type="number" /></li>
      <li>
        <input type="password" placeholder="Password" /> Password please!!!
      </li>
      <li>
        <input type="radio" /> Item to check 01 <br />
        <input type="radio" /> Item to check 02
      </li>
      <li><input type="range" /> How much angry are you?</li>
      <li><input type="reset" /> Reset all the value.</li>
      <li>
        <input type="search" /> Search Anything. But you will get nothing.
      </li>
      <li>
        May be you cal call your Parents: <input type="tel" name="" value="" />
      </li>
      <li>Tell me when you get up: <input type="time" /></li>
      <li><input type="url" /> : Make me Frieds</li>
      <li>Take any week of a year for vacation: <input type="week" /></li>
    </ul>
  </fieldset>
  <button type="button" name="button">From Submit</button>
</form>
```

NB: All other input type of the form can be found in Appendix - 2

#### 2.7.2 Text Area <a name="textArea"></a>

`textarea` is used for taking bulk of input. We can specify the number of
columns and number of rows with the `cols` and `rows` attribute.

```html
<textarea name="name" rows="8" cols="80"></textarea>
```

#### 2.7.3 Dropdown (select) <a name="dropdown"></a>

We can make a simple dropdown using the `select` element. Simple Syntax:

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
##### 2.7.3.1 OptGroup (select) <a name="optgroup"></a>
`optgroup` creates a grouping of options within a `select` element.
Simple Syntax:
```html
<select>
    <optgroup label="....">
        <option> ... </option>
        .
        .
        .
        <option> ... </option>
    </optgroup>
    .
    .
    .
    <optgroup label="....">
    </optgroup>
</select>
```
Example:
```html
<label for="groupSelector">Choose something you need</label>
<select id="groupSelector">
    <optgroup label="SolidOptions">
        <option value="cerial">Cerials</option>
        <option value="rice">Rice</option>
        <option value="bakery">Bakery</option>
    </optgroup>
    <optgroup label="LiquidOptions">
        <option value="water">Water</option>
        <option value="tea">Tea</option>
        <option value="coffie">Coffie</option>
    </optgroup>
</select>
```
#### 2.7.4 Datalist (select) <a name="datalist"></a>
`datalist` is used show a dropdown related to an input element. The `input` element have an attribute `list` which takes the id of the datalist.
Basic Syntax:
```html
<input list="idOfTheDataList">
<datalist id="">
    <option value="...">...</option>
    <option value="...">...</option>
</datalist>
```
Example:
```html
<input list="dataList">
<datalist id="dataList">
    <option value="item01">Item 01</option>
    <option value="item02">Item 02</option>
</datalist>
```
<input list="dataList">
<datalist id="dataList">
    <option value="item01">Item 01</option>
    <option value="item02">Item 02</option>
</datalist>

The main difference between `select` and `datalist` is that the `select`
requires users to choose from the indicated options. The `datalist` allows users
to either choose from the specified answers, or to type in their original ones.

### 2.8 Iframe <a name="iframe"></a>

The HTML **Inline Frame element** (`<iframe>`) represents a nested browsing
context. Usually embedding another HTML page into the current one. Each embedded
browsing context has its own `session history` and `document`. The browsing
context that embeds the others is called the `parent browsing context`. Using
iframe consumes more memory. Basic Syntax:

```html
<iframe
  id="..."
  title="..."
  width="..."
  height="..."
  src="...externalContextlink"
>
</iframe>
```

There are several Attributes for iframe:

- `allow`:Specifies a feature policy for the iframe.

  > `Feature Policy` Ferature policy allowes web developer to selewctively
  > enable, disable and modify the behaviour of certain feature and APIs in the
  > browser. It is Similer to Content Securtity policy but controls feature
  > instade of security behaviour. For More information regarding to Feature
  > Policy and Content security Policy Look at the Appendix.

- `allowfullscreen`: `true` can activate fullscreen mode. Alternative:
  `allow:"fullscreen"`.
- `allowpaymentrequest`: `true` if a cross origin `<iframe>` should be allowed
  to invoke payment request API. Alternative: `allow="payment"`.
- `csp`: Content security policy.
- `height`: Height of the frame in px.
- `loading`: Indicate how the browser shopuld load the iframe;

  > `eager` : Load the iframe imidiately; `lazy`: Defer loading of the iframe.

- `name`: A targetable attribute.
- `refererpolicy`: Indicate which referrer to be sent when fatching the iframe
  resource.

  > `no-referer`: Referer header will not be sent;\
  > `no-referer-when-downgrade`; `origin`: Origin of the referring page (scheme,
  > host,port); `origin-when-cross-origin`: Origin sent to the other origin. `strict-origin`:
  > Sent when `HTTPS` -> `HTTPS` `strict-origin-when-cross-origin` `unsafe-url`:
  > Origin + path will be sent.

- `sandbox`: Applies extra restrictions to the content in the iframe. The value
  of the attribute can either be empty to apply all restrictions, or
  space-seperated tokens to lift particular restrictions.

  > `allow-downlolads-without-user-activations`: Allow a donload to occure
  > without a gesture from the user.\
  > 'allow-downloads': Allow download tro occure with a gesture from the user.\
  > `allow-forms`: Allow the resource to submit froms.\
  > `allow-modals`;\
  > `allow-orientation-lock`;\
  > `allow-pointer-lock`;\
  > `allow-popups`: `windows.open()` , `target = "_blank"`;\
  > `allow-popups-to-escape-sandbox`;\
  > `allow-presentation`;\
  > `allow-same-origin`;\
  > `allow-scripts`: Let's resource run scripts.

- `src`: The url of the page to embed. `about:blank` to embed an empty page
- `srcdoc`: Override `src` if the browser supports.
- `width`: Width of the frames in px.

Scripting: All `iframes` are included in `window.frames` pseudo-array. Windo
object of `ifame` is `contentWindow`. THe `contentDocument` property refers to
`document` inside the `iframe`

### 2.9 Object <a name="object"></a>

`object` element represent an external resource, which can be treated as image,
a nasted browsing context or a resource to be handled by a plugin. Basic Syntax:

```html
<object
  type="..."
  data="..."
  width="..."
  height="..."
  form="..."
  name="..."
  usemap="#..."
></object>
```

- `type`: The content type of the resource by data.
- `data`: The address of the resource as a valid url.
- `width`: The width of the display resource in px.
- `height`: The height of the dispaly resource in px.
- `form`: The form element (Owner): if any.
- `name`: Name fro the control.
- `usemap`: A hash named reference to `map` element.

#### 2.9.1 Parameter of Object <a name="param"></a>

`param` element is used to define the value of an object.

```Html
<object type="application/pdf" data="......pdf">
    <param name="attribute1" value="value1">
    <param name="attribute2" value="value2">
</object>
```

### 2.10 NoScript <a name="noscript"></a>

`noscript` element is a section in the html page which will be inserted if the
script type of the page is unsupported or if currently turned off in the
browser. Basic Syntax:

```html
<noscript> ..... </noscript>
```

Example:

```Html
<noscript>
    <h1>This section is been shown because the script is not working for this browser</h1>
</noscript>
<p>It will be always shown to the user. I am Script Indepemdent</p>
```

<noscript>
    <h1>This section is been shown because the script is not working for this browser</h1>
</noscript>
<p>It will be always shown to the user. I am Script Indepemdent</p>

## 3. Header Area <a name="headerArea"></a>

### 3.1 Meta <a name="meta"></a>

`meta` actually is the **Data of the Data**. Different type of attribute of meta
is being used. Some of them are:

1. `cahrset` : Character set used.
2. `description`: Description of the web page.
3. `keywords`: Define keywords for the search engine.
4. `author`: Define the author of the page.
5. `http-equiv`: Refresh the page after some defined seconds.
6. `viewport`: Setting the viewport for all the devices.

```html
<meta charset="UTF-8" />
<meta name="description" content="Free Web tutorials" />
<meta name="keywords" content="HTML, CSS, JavaScript" />
<meta name="author" content="John Doe" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

### 3.2 Base <a name="base"></a>

`base` element is used to specify a base url and targets for all resources
links.Base element have `href` and `target` attributes that performs same as
they does in Hyperlink.There can be only base element in the document and it
needed to be added in the hear section. Simple Syntax:

```html
<base href="https://www.w3schools.com/" target="_blank" />
```

## 4. Multimedia <a name="multimedia"></a>

### 4.1 Audio <a name="audio"></a>

Basic syntax:

```html
<audio ...attributes... preload="auto/metadata/none" onplay="invokeFunction()">
  <source src="..." type="audio/...fileType..." />
  <source src="..." type="audio/...fileType..." />
  Text that will be shown when error.
</audio>
```

`audio` element is used embed the audio in the page. `source` element is used to
specify the source of the audio. `src` attribute is used to specify the source
of the audio `type` attribute a specifies the file type.We can have multiple
`source` element. The valid one will play first. `audio` element have `preload`
attribute to preload the audio before paly. Any text between the tag element
will be only shown if there is error in playing the audio.\
`audio` element have other different attributes for audio controls.\
`controls`: Enables the audio control, browser default.\
`autoplay`: Autoplayes the audio after load.\
`loop`: Loop the audio.\
`muted`: Mute the audio by default.\

Example:

```html
<audio controls loop>
  <source src="./assets/audio/bensound-ukulele.mp3" type="audio/mp3" />
</audio>
```

### 4.2 Video <a name="video"></a>

Basic syntax:

```html
<video ...attributes...>
  <source src="..." type="video/...fileType..." />
  <source src="..." type="video/...fileType..." />
  Text that will be shown when error.
</video>
```

`video` element is used embed the video in the page. `source` element is used to
specify the source of the audio. `src` attribute is used to specify the source
of the audio `type` attribute a specifies the file type. Attributes for video
elements are:\
`autoplay`: **Values:** autoplay - Specifies that the video will play automatically.\
`controls`: **Values:** controls - Specifies that the video controls gets
displayed.\
`loop`: **Values:** loop - Specifies that the video will start again every time after
finish.\
`height`: **Values:** pixels - Specifies the height.\
`weight`: **Values:** pixels - Specifies the width.\
`muted`:**Values:** muted - Specifies that the audio should be muted.\
`poster`: **Values:** URL - Specifies the image to be shown while the video is downloading.\
`preload`: **Values:** auto, metadat, none - Specifies what author thinks will
lead to user experience at its best. `src`: **Values:** URL - Specifies the URL.

Example:

```html
<video controls loop poster="./assets/images/alone.jpg">
  <source src="./assets/video/video.mp4" type="video/mp4" />
</video>
```

#### 4.2.1 Track <a name="track"></a>

`track` element is used as a child of the media elements `audio` and
`video`element. It specify **timed text tracks** (or time-based data) for
example to automatically handle subtitles.

```html
<video controls src="...">
  <track default kind="..." srclang=".." src="..." />
</video>
```

- `default`: Indicates that the track should be enabled, unless user's
  preference indicate that another track is suitable.
- `kind`: How the text track is meant to be used.
  - `subtitles`
  - `captions`: Closed captions provide a transcription and possibly a
    translation of audio.It may include important non-verbal information such as
    music cues or sound effects.
  - `descriptions`: Textual description of the video content.Suitable for users
    who are blind or where the video cannot be seen.
  - `chapters`: Chapter titles are intended to be used when the user is
    navigating the media resource.
  - `metadata`: Tracks used by scripts. Not visible to the user. Default value
    is `subtitle`.
- `label`:A user-readable title of the text track which is used by the browser
  when listing available text tracks.
- `src`: Address of the track. (`.vtt`) file. URL value must have the same
  origin as the document.
- `srclang`:Language of the track text data. Must be defined for `subtitle`
  track. A `media` element cannot have more than one track with the same `kind`,
  `srclang`, and `label`.

```html
<video controls poster="/images/sample.gif">
  <source src="sample.mp4" type="video/mp4" />
  <track kind="captions" src="sampleCaptions.vtt" srclang="en" />
  <track kind="descriptions" src="sampleDescriptions.vtt" srclang="en" />
  <track kind="chapters" src="sampleChapters.vtt" srclang="en" />
  <track kind="subtitles" src="sampleSubtitles_de.vtt" srclang="de" />
  <track kind="subtitles" src="sampleSubtitles_en.vtt" srclang="en" />
  <track kind="metadata" src="keyStage1.vtt" srclang="en" label="Key Stage 1" />
  <track kind="metadata" src="keyStage2.vtt" srclang="en" />
  ...
</video>
```

### 4.3 Meter <a name="meter"></a>

Basic syntax:

```html
<meter ...attributes...></meter>
```

Meter represents either a scalar value within a known range or fractional value.

- `id`:Distinguishable id for query in label of form or others.\
- `value`: Current numeric value. Must be in between `min` and `max`. Other wise
  it will be `0`.
- `min`: Lower numeric bound. Default value `0`.\
- `max`: Upper numeric bound. Default value `1`.\
- `high`: The lower numeric bound of the high end measured range. Default value
  `max`.\
- `low`: The upper numeric bound of the low end measured range. Default value
  `min`.\
- `optimum`: Optimal numeric value.
- `form`: Distinguishable id for query in label of form or others.

<meter id="fuel" value="40" min="0" max="100" low="20" high="80" optimum="70"></meter>

### 4.4 Progress <a name="progress"></a>

Basic syntax:

```html
<progress for="...." value=".." max="...">...</progress>
```

Displays an indicator showing the completion of progress of a task.

- `for`: Unique indicator for the `progress`.
- `value`: Current numeric value. Must be in between `0` and `max`. Other wise
  it will be `0`.
- `max`: Upper numeric bound. Default value `1`.\
  There is no minimum bound in `progress`. The minimum value is always `0`. If the
  `value` attribute is undefined it indicates that an activity is going on of no
  indication of how long it is expected to take.

Example:

```HTML
<label for="prgressbar1">Progress bar with value: </label>
<progress for="progressbar1" value="30" max="100">0%</progress>
<label for="progressbar2">Progress bar without value attribute: </label>
<progress max="100">0%</progress>
```

### 4.5 Navigation <a name="nav"></a>

Basic syntax:

```html
<nav class="navigation">
  <ol>
    <li><a href="#"> Option 1</a></li>
    <li><a href="#"> Option 2</a></li>
    <li><a href="#">Selected Tab</a></li>
  </ol>
</nav>
```

`nav` represent a section of a page, whose purpose is to provide navigation
link. (Menus, Table of Contents, Indexes).\

### 4.6 Picture <a name="picture"></a>

`picture` element contains zero or more `source` element and one `img` element
to offer alternative version of an image for different display/device. Browser
will consider each `source` element and will consider the best among them. If no
source matches or the browser does not support the picture element, the url of
`img` element `src` will be selected. Properties of image like `object-fit`
should be used in `img` element, not in `picture` element. Basic syntax:

```html
<picture>
  <source srcset=" ... w, ..., ....x, ..." media="(...)" />
  . . .
  <source />
  <img src="..." alt="..." />
</picture>
```

- `media`: Specifies a media condition.
- `srcset`: Define multiple size of the same image, allowing the browser to
  select the appropriate image source. It is composed of a comma-separated list
  of image descriptions.
  - `URL` + `width`**w**
  - `URL` + `density`**x**
- `type`: MIME type.

Example:

```html
<picture>
  <source srcset="/assets/images/alone.jpg" media="(min-width:600px)" />
  <source
    srcset="/assets/images/alone.jpg 200w, /assets/images/alone.jpg .5x"
    type="image/jpg"
  />
  <img src="/assets/images/alone.jpg" alt="testimage" />
</picture>
```

### 4.7 Script <a name="script"></a>

`script` used to embed executable code/data/refer to code.

- `async`: The script will be fetched in parallel to parsing and fetched as soon
  as possible. It allows the elimination of **parser-blocking JavaScript**.
- `crossorigin`: Allow error logging for sites which use a separate domain for
  static media. (Though CORS check fails).
- `defer`: Indicate that the script meant to be executed after the document have
  been parsed, before calling the Event `DOMContentLoaded`. Scripts with the
  `defer` attribute will prevent the `DOMContentLoaded` event from firing until
  the script has loaded and finished evaluating. It do not have any effect on
  `module` script but `src` script.
- `integrity`: This attribute contains inline metadata that a user agent can use
  to verify that a fetched resource has been delivered free of unexpected
  manipulation.

```Html
<script src="https://example.com/example-framework.js"
        integrity="sha384-oqVuAfXRKap7fdgcCY5uykM6+R9GqQ8K/uxy9rx7HNQlGYl1kPzQho1wx4JwY8wC"
        crossorigin="anonymous"></script>
```

- `nomodule`: Indicate that the script should not be executed in browsers that
  support ES2015 modules.
- `nonce`: Whitelist scripts in a **script-src Content-Security-Policy**.

```html
Content-Security-Policy: script-src 'nonce-2726c7f26c'
```

```html
<script nonce="2726c7f26c">
  var inline = 1;
</script>
```

- `refererpolicy`: Which referrer to send when fetching the script, or resource
  fetched by Script.
  - `no-referrer`
  - `no-referrer-when-downgrade`: (Default) The Referrer header will not be sent
    to origins without `https`.
  - `origin`: Origin of the refereeing page. (`scheme`+`host`+`port`).
  - `origin-when-cross-origin`: Referrer sent to other origins will be limited.
    (`scheme`+`host`+`port`).
  - `same-origin`: Referrer will be sent to same origin.
  - `strict-origin`: Only send the origin of the document as the referrer when
    the protocol security level stays the same (e.g. `HTTPS` → `HTTPS`).
  - `strict-origin-when-cross-origin`: Send a full URL when performing a
    same-origin request, but only send the origin when the protocol security
    level stays the same (e.g.`HTTPS` → `HTTPS`), and send no header to a less
    secure destination (e.g. `HTTPS` → `HTTP`).
- `src`:URI of an external script.
- `type`:
  - `Omitted or a JavaScript MIME type(text/javascript)`: Should be kept
    omitted/blank to represent JavaScript.
  - `module`: Represent JavaScript module.
  - `Any other value`: Won't be processed by the browser.

`parser-blocking JavaScript` is where the browser would have to load and
evaluate scripts before continuing to parse.

```html
<script src="javascript.js"></script>
```

```html
<script>
  alert("Hello World!");
</script>
```

```html
<script type="module" src="main.js"></script>
<script nomodule src="fallback.js"></script>
```

```html
<!-- Generated by the server -->
<script id="data" type="application/json">
  {
    "userId": 1234,
    "userName": "John Doe",
    "memberSince": "2000-01-01T00:00:00.000Z"
  }
</script>

<!-- Static -->
<script>
  const userInfo = JSON.parse(document.getElementById("data").text);
  console.log("User information: %o", userInfo);
</script>
```

### 4.8 Style <a name="style"></a>

`style` contains style information for a document, or part of a document.It
contains CSS, which is applied to the contents of the document containing the
`style` element. It mus be included in the `head` section of the document. For
multiple style document, make sure you include them in correct order.

```html
<head>
  <style>
    p {
      color: red;
    }
  </style>
</head>
```

- `media`: Apply style for certain media type.

```html
<style media="print">
  p {
    color: blue;
    background-color: yellow;
  }
</style>
```

- `nonce`: A cryptographic nonce (number used once) used to whitelist inline
  styles in a style-src Content-Security-Policy.
- `title`: Specifies alternative style sheet sets.

### 4.9 Details and Summery <a name="details"></a>

`details` Creates a disclosure widget in which information is visible only when
the widget is toggled into an "open" state.A summary or label must be provided
using the `summary` element. It have boolen `open` attribute and support
`toggle` event. Basic Syntax:

```html
<details>
  <summary>...</summary>
  <!-- Some Content -->
</details>
```

- `open`: Indicates that whether or not the details should be expand.

### 4.10 Time <a name="time"></a>

`time` represent a specific period of time. it use `datetime` attribute for
translation of time to machine-readable formate.

- A `time` on `24hr` clock.
- A precise date in the `Gregorian calendar` with time zone information.
- A valid time duration. Basic Syntax:

```html
<time datetime="..."> Time Text </time>
```

Example:

```html
<time datetime="2018-07-07">July 7</time>
<time datetime="20:00">20:00</time>
<time datetime="PT2H30M">2h 30m</time>
```

`datetime` indicates tine and/or date of the element. It should always follow
the valid formate. Valid formates are:

- `2011` : valid **Year**.
- `2011-11`: valid **Month**.
- `2011-11-10`: valid **date**.
- `11-10`: valid **Yeasless Date**.
- `2021-W47`: valid **week**.
- `14:56`: valid **Time**.
- `14:56:58`: valid **Time**
- `14:56:58.349`: valid **Time**
- `2011-11-18T14:54:39.929`: valid **Local Time and Date**.
- `2011-11-18 14:54:39.929`: valid **Local Time and Date**.
- `2011-11-18T14:54:39.929Z`, `2011-11-18T14:54:39.929-0400`,
  `2011-11-18T14:54:39.929-04:00`,
  `2011-11-18 14:54:39.929Z`,`2011-11-18 14:54:39.929-0400`,
  `2011-11-18 14:54:39.929-04:00`.
- `PT4H18M3S`: Valid **Duration**

### Appendix -1

All Special Characters list and Code.\

| Character | Character Code | Character name | Description                       |
| --------- | -------------- | -------------- | --------------------------------- |
| Space     | 160            | nbsp           | non-breaking space                |
| ¡         | 161;           | iexcl;         | inverted exclamation mark         |
| ¢         | 162            | cent;          | cent                              |
| £         | 163;           | pound;         | pound                             |
| ¤         | 164;           | curren;        | currency                          |
| ¥         | 165;           | yen;           | yen                               |
| ¦         | 166;           | brvbar;        | broken vertical bar               |
| §         | 167;           | sect;          | section                           |
| ¨         | 168;           | uml;           | spacing diaeresis                 |
| ©         | 169;           | copy;          | copyright                         |
| ª         | 170;           | ordf;          | feminine ordinal indicator        |
| «         | 171;           | laquo;         | angle quotation mark (left)       |
| ¬         | 172;           | not;           | negation                          |
| ­         | 173;           | shy;           | soft hyphen                       |
| ®         | 174;           | reg;           | registered trademark              |
| ¯         | 175;           | macr;          | spacing macron                    |
| °         | 176;           | deg;           | degree                            |
| ±         | 177;           | plusmn;        | plus-or-minus                     |
| ²         | 178;           | sup2;          | superscript 2                     |
| ³         | 179;           | sup3;          | superscript 3                     |
| ´         | 180;           | acute;         | spacing acute                     |
| µ         | 181;           | micro;         | micro                             |
| ¶         | 182;           | para;          | paragraph                         |
| ·         | 183;           | middot;        | middle dot                        |
| ¸         | 184;           | cedil;         | spacing cedilla                   |
| ¹         | 185;           | sup1;          | superscript 1                     |
| º         | 186;           | ordm;          | masculine ordinal indicator       |
| »         | 187;           | raquo;         | angle quotation mark (right)      |
| ¼         | 188;           | frac14;        | fraction 1/4                      |
| ½         | 189;           | frac12;        | fraction 1/2                      |
| ¾         | 190;           | frac34;        | fraction 3/4                      |
| ¿         | 191;           | iquest;        | inverted question mark            |
| ×         | 215;           | times;         | multiplication                    |
| ÷         | 247;           | divide;        | division                          |
| "         | 34;            | quot;          | quotation mark                    |
| '         | 39;            | apos;          | apostrophe                        |
|           | 38;            | amp;           | ampersand                         |
| <         | 60;            | lt;            | less-than                         |
| >         | 62;            | gt;            | greater-than                      |
| Œ         | 338;           | OElig;         | capital ligature OE               |
| œ         | 339;           | oelig;         | small ligature oe                 |
| Š         | 352;           | Scaron;        | capital S with caron              |
| š         | 353;           | scaron;        | small S with caron                |
| Ÿ         | 376;           | Yuml;          | capital Y with diaeres            |
| ƒ         | 402;           | fnof;          | f with hook                       |
| ˆ         | 710;           | circ;          | modifier letter circumflex accent |
| ˜         | 732;           | tilde;         | small tilde                       |
|           | 8194;          | ensp;          | en space                          |
|           | 8195;          | emsp;          | em space                          |
|           | 8201;          | thinsp;        | thin space                        |
| ‌         | 8204;          | zwnj;          | zero width non-joiner             |
| ‍         | 8205;          | zwj;           | zero width joiner                 |
| ‎         | 8206;          | lrm;           | left-to-right mark                |
|           | ‏              | 820 rlm;       | right-to-left mark                |
| –         | 8211;          | ndash;         | en dash                           |
| —         | 8212;          | mdash;         | em dash                           |
| ‘         | 8216;          | lsquo;         | left single quotation mark        |
| ’         | 8217;          | rsquo;         | right single quotation mark       |
| ‚         | 8218;          | sbquo;         | single low-9 quotation mark       |
| “         | 8220;          | ldquo;         | left double quotation mark        |
| ”         | 8221;          | rdquo;         | right double quotation mark       |
| „         | 8222;          | bdquo;         | double low-9 quotation mark       |
| †         | 8224;          | dagger;        | dagger                            |
| ‡         | 8225;          | Dagger;        | double dagger                     |
| •         | 8226;          | bull;          | bullet                            |
| …         | 8230;          | hellip;        | horizontal ellipsis               |
| ‰         | 8240;          | permil;        | per mille                         |
| ′         | 8242;          | prime;         | minutes                           |
| ″         | 8243;          | Prime;         | seconds                           |
| ‹         | 8249;          | lsaquo;        | single left angle quotation       |
| ›         | 8250;          | rsaquo;        | single right angle quotation      |
| ‾         | 8254;          | oline;         | overline                          |
| €         | 8364;          | euro;          | euro                              |
| ™         | 8482;          | trade;         | trademark                         |
| ←         | 8592;          | larr;          | left arrow                        |
| ↑         | 8593;          | uarr;          | up arrow                          |
| →         | 8594;          | rarr;          | right arrow                       |
| ↓         | 8595;          | darr;          | down arrow                        |
| ↔         | 8596;          | harr;          | left right arrow                  |
| ↵         | 8629;          | crarr;         | carriage return arrow             |
| ⌈         | 8968;          | lceil;         | left ceiling                      |
| ⌉         | 8969;          | rceil;         | right ceiling                     |
| ⌊         | 8970;          | lfloor;        | left floor                        |
| ⌋         | 8971;          | rfloor;        | right floor                       |
| ◊         | 9674;          | loz;           | lozenge                           |
| ♠         | 9824;          | spades;        | spade                             |
| ♣         | 9827;          | clubs;         | club                              |
| ♥         | 9829;          | hearts;        | heart                             |
| ♦         | 9830;          | diams;         | diamond                           |
| ∀         | 8704;          | forall;        | for all                           |
| ∂         | 8706;          | part;          | part                              |
| ∃         | 8707;          | exist;         | exists                            |
| ∅         | 8709;          | empty;         | empty                             |
| ∇         | 8711;          | nabla;         | nabla                             |
| ∈         | 8712;          | isin;          | isin                              |
| ∉         | 8713;          | notin;         | notin                             |
| ∋         | 8715;          | ni;            | ni                                |
| ∏         | 8719;          | prod;          | prod                              |
| ∑         | 8721;          | sum;           | sum                               |
| −         | 8722;          | minus;         | minus                             |
| ∗         | 8727;          | lowast;        | lowast                            |
| √         | 8730;          | radic;         | square root                       |
| ∝         | 8733;          | prop;          | proportional to                   |
| ∞         | 8734;          | infin;         | infinity                          |
| ∠         | 8736;          | ang;           | angle                             |
| ∧         | 8743;          | and;           | and                               |
| ∨         | 8744;          | or;            | or                                |
| ∩         | 8745;          | cap;           | cap                               |
| ∪         | 8746;          | cup;           | cup                               |
| ∫         | 8747;          | int;           | integral                          |
| ∴         | 8756;          | there4;        | therefore                         |
| ∼         | 8764;          | sim;           | similar to                        |
| ≅         | 8773;          | cong;          | congruent to                      |
| ≈         | 8776;          | asymp;         | almost equal                      |
| ≠         | 8800;          | ne;            | not equal                         |
| ≡         | 8801;          | equiv;         | equivalent                        |
| ≤         | 8804;          | le;            | less or equal                     |
| ≥         | 8805;          | ge;            | greater or equal                  |
| ⊂         | 8834;          | sub;           | subset of                         |
| ⊃         | 8835;          | sup;           | superset of                       |
| ⊄         | 8836;          | nsub;          | not subset of                     |
| ⊆         | 8838;          | sube;          | subset or equal                   |
| ⊇         | 8839;          | supe;          | superset or equal                 |
| ⊕         | 8853;          | oplus;         | circled plus                      |
| ⊗         | 8855;          | otimes;        | circled times                     |
| ⊥         | 8869;          | perp;          | perpendicular                     |
| ⋅         | 8901;          | sdot;          | dot operator                      |
| À         | 192;           | Agrave;        | capital a, grave accent           |
| Á         | 193;           | Aacute;        | capital a, acute accent           |
| Â         | 194;           | Acirc;         | capital a, circumflex accent      |
| Ã         | 195;           | Atilde;        | capital a, tilde                  |
| Ä         | 196;           | Auml;          | capital a, umlaut mark            |
| Å         | 197;           | Aring;         | capital a, ring                   |
| Æ         | 198;           | AElig;         | capital ae                        |
| Ç         | 199;           | Ccedil;        | capital c, cedilla                |
| È         | 200;           | Egrave;        | capital e, grave accent           |
| É         | 201;           | Eacute;        | capital e, acute accent           |
| Ê         | 202;           | Ecirc;         | capital e, circumflex accent      |
| Ë         | 203;           | Euml;          | capital e, umlaut mark            |
| Ì         | 204;           | Igrave;        | capital i, grave accent           |
| Í         | 205;           | Iacute;        | capital i, acute accent           |
| Î         | 206;           | Icirc;         | capital i, circumflex accent      |
| Ï         | 207;           | Iuml;          | capital i, umlaut mark            |
| Ð         | 208;           | ETH;           | capital eth, Icelandic            |
| Ñ         | 209;           | Ntilde;        | capital n, tilde                  |
| Ò         | 210;           | Ograve;        | capital o, grave accent           |
| Ó         | 211;           | Oacute;        | capital o, acute accent           |
| Ô         | 212;           | Ocirc;         | capital o, circumflex accent      |
| Õ         | 213;           | Otilde;        | capital o, tilde                  |
| Ö         | 214;           | Ouml;          | capital o, umlaut mark            |
| Ø         | 216;           | Oslash;        | capital o, slash                  |
| Ù         | 217;           | Ugrave;        | capital u, grave accent           |
| Ú         | 218;           | Uacute;        | capital u, acute accent           |
| Û         | 219;           | Ucirc;         | capital u, circumflex accent      |
| Ü         | 220;           | Uuml;          | capital u, umlaut mark            |
| Ý         | 221;           | Yacute;        | capital y, acute accent           |
| Þ         | 222;           | THORN;         | capital THORN, Icelandic          |
| ß         | 223;           | szlig;         | small sharp s, German             |
| à         | 224;           | agrave;        | small a, grave accent             |
| á         | 225;           | aacute;        | small a, acute accent             |
| â         | 226;           | acirc;         | small a, circumflex accent        |
| ã         | 227;           | atilde;        | small a, tilde                    |
| ä         | 228;           | auml;          | small a, umlaut mark              |
| å         | 229;           | aring;         | small a, ring                     |
| æ         | 230;           | aelig;         | small ae                          |
| ç         | 231;           | ccedil;        | small c, cedilla                  |
| è         | 232;           | egrave;        | small e, grave accent             |
| é         | 233;           | eacute;        | small e, acute accent             |
| ê         | 234;           | ecirc;         | small e, circumflex accent        |
| ë         | 235;           | euml;          | small e, umlaut mark              |
| ì         | 236;           | igrave;        | small i, grave accent             |
| í         | 237;           | iacute;        | small i, acute accent             |
| î         | 238;           | icirc;         | small i, circumflex accent        |
| ï         | 239;           | iuml;          | small i, umlaut mark              |
| ð         | 240;           | eth;           | small eth, Icelandic              |
| ñ         | 241;           | ntilde;        | small n, tilde                    |
| ò         | 242;           | ograve;        | small o, grave accent             |
| ó         | 243;           | oacute;        | small o, acute accent             |
| ô         | 244;           | ocirc;         | small o, circumflex accent        |
| õ         | 245;           | otilde;        | small o, tilde                    |
| ö         | 246;           | ouml;          | small o, umlaut mark              |
| ø         | 248;           | oslash;        | small o, slash                    |
| ù         | 249;           | ugrave;        | small u, grave accent             |
| ú         | 250;           | uacute;        | small u, acute accent             |
| û         | 251;           | ucirc;         | small u, circumflex accent        |
| ü         | 252;           | uuml;          | small u, umlaut mark              |
| ý         | 253;           | yacute;        | small y, acute accent             |
| þ         | 254;           | thorn;         | small thorn, Icelandic            |
| ÿ         | 255;           | yuml;          | small y, umlaut mark              |

### Appendix -2:

All input types for form:\

| Type             | Description                                                                     |
| ---------------- | ------------------------------------------------------------------------------- |
| `button`         | Defines a clickable button (mostly used with a JavaScript to activate a script) |
| `checkbox`       | Defines a checkbox                                                              |
| `color`          | Defines a color picker                                                          |
| `date`           | Defines a date control (year, month, day (no time))                             |
| `datetime-local` | Defines a date and time control (year, month, day, time (no timezone)           |
| `email`          | Defines a field for an e-mail address                                           |
| `file`           | Defines a file-select field and a "Browse" button (for file uploads)            |
| `hidden`         | Defines a hidden input field                                                    |
| `image`          | Defines an image as the submit button                                           |
| `month`          | Defines a month and year control (no timezone)                                  |
| `number`         | Defines a field for entering a number                                           |
| `password`       | Defines a password field                                                        |
| `radio`          | Defines a radio button                                                          |
| `range`          | Defines a range control (like a slider control)                                 |
| `reset`          | Defines a reset button                                                          |
| `search`         | Defines a text field for entering a search string                               |
| `submit`         | Defines a submit button                                                         |
| `tel`            | Defines a field for entering a telephone number                                 |
| `text`           | Default. Defines a single-line text field                                       |
| `time`           | Defines a control for entering a time (no timezone)                             |
| `url`            | Defines a field for entering a URL                                              |
| `week`           | Defines a week and year control (no timezone)                                   |

#### Appendix - 3:

All Tags in one place:

| Tag            | Description                                                                                 |
| -------------- | ------------------------------------------------------------------------------------------- |
| `<!-- ..-->`   | Comment                                                                                     |
| `<!DOCTYPE>`   | Defines the document type                                                                   |
| `<a>`          | Defines a Hyper link                                                                        |
| `<abbr>`       | Defines an abbreviation or an acronym                                                       |
| `<address>`    | Defines a contract information for the author of the document                               |
| `<area>`       | Defines an area inside an image map                                                         |
| `<article>`    | Defines an article                                                                          |
| `<aside>`      | Defines content aside from the page content                                                 |
| `<audio>`      | Defines embedded sound content                                                              |
| `<b>`          | Defines bold text                                                                           |
| `<base>`       | Defines specifies the base url in document                                                  |
| `<bdi>`        | Isolate a part of the text that might be formatted in a different direction from other text |
| `<bdo>`        | Override the current text direction                                                         |
| `<blockquote>` | Defines a section that is quoted from another source                                        |
| `<body>`       | Defines the document's body                                                                 |
| `<br>`         | Defines the single line break                                                               |
| `<button>`     | Defines a click able button                                                                 |
| `<canvas>`     | Used to draw graphics                                                                       |
| `<caption>`    | Defines a table captions                                                                    |
| `<cite>`       | Defines the title of a work                                                                 |
| `<code>`       | Defines a piece of computer code                                                            |
| `<col>`        | Specifies column properties for each column within a `<colgroup>` element                   |
| `<colgroup>`   | Specifies a group of one or more columns in a table fro formatting                          |
| `<data>`       | Adds a machine-readable translation of a given content                                      |
| `<datalist>`   | Specifies a list of pre-defined options for input controls                                  |
| `<dd>`         | Defines a description/value of a term in a description list                                 |
| `<del>`        | Defines a text that has been deleted from a document                                        |
| `<details>`    | Defines additional details that the user can view or hide                                   |
| `<dfn>`        | Specifies a term that is going to be defined within the content                             |
| `<dialog>`     | Defines a dialog box or window                                                              |
| `<div>`        | Defines a section in a document                                                             |
| `<dl>`         | Defines a description list                                                                  |
| `<dt>`         | Defines a term/name in a description list                                                   |
| `<em>`         | Defines emphasized text                                                                     |
| `<embed>`      | Defines a container for an external application                                             |
| `<fieldset>`   | Groups related elements in a from                                                           |
| `<figcaption>` | Defines caption for a figure element                                                        |
| `<figure>`     | Specifies self-contained content                                                            |
| `<footer>`     | Defines a footer for a document                                                             |
| `<form>`       | Defines HTML froms for user input                                                           |
| `<h1> to <h6>` | Defines HTML headlines                                                                      |
| `<head>`       | Contains metadata for the document                                                          |
| `<header>`     | Defines a header for a document                                                             |
| `<hr>`         | Defines a thematic change in the content                                                    |
| `<html>`       | Defines the root of an HTML document                                                        |
| `<i>`          | Defines a part of the text in an alternate voice or mood                                    |
| `<iframe>`     | Defines an inline iframe                                                                    |
| `<img>`        | Defines an image                                                                            |
| `<input>`      | Defines an input control                                                                    |
| `<ins>`        | Defines a text that has been inserted into a document                                       |
| `<kbd>`        | Defines keyboard input                                                                      |
| `<label>`      | Defines a label for an input element                                                        |
| `<legend>`     | Defines a caption for a `<fieldset>` element                                                |
| `<li>`         | Defines alist item                                                                          |
| `<link>`       | Defines the relationship between a document and an external resource                        |
| `<main>`       | Specifies the main content of a document                                                    |
| `<map>`        | Defines an image map                                                                        |
| `<mark>`       | Defines mark or highlighted text                                                            |
| `<meta>`       | Defines meta about an HTML document                                                         |
| `<meter>`      | Defines a scalar measurement within a known range                                           |
| `<nav>`        | Defines a navigation link                                                                   |
| `<noscript>`   | Defines an alternative content for user that do not support client-side scripts             |
| `<object>`     | Defines a container for an external application                                             |
| `<ol>`         | Defines an ordered list                                                                     |
| `<optgroup>`   | Defines a group of related options in a drop-down list                                      |
| `<option>`     | Defines an option in a drop-down list                                                       |
| `<output>`     | Defines the result of a calculation                                                         |
| `<p>`          | Defines a paragraph                                                                         |
| `<param>`      | Defines a parameter for an object                                                           |
| `<picture>`    | Defines a container for multiple image resources                                            |
| `<pre>`        | Defines preformed text                                                                      |
| `<progress>`   | Represents the progress of a task                                                           |
| `<q>`          | Defines a short quotation                                                                   |
| `<rp>`         | Defines what to show in browsers that do not support ruby annotations                       |
| `<ruby>`       | Defines an explanation of characters                                                        |
| `<s>`          | Defines text that is no longer correct                                                      |
| `<samp>`       | Defines sample output from a computer program                                               |
| `<script>`     | Defines a client-side script                                                                |
| `<section>`    | Defines a section in a document                                                             |
| `<select>`     | Defines a drop-down list                                                                    |
| `<samll>`      | Defines smaller text                                                                        |
| `<source>`     | Defines multiple media resources fro media element                                          |
| `<span>`       | Defines a section in a document                                                             |
| `<strong>`     | Defines important text                                                                      |
| `<style>`      | Defines style information for a document                                                    |
| `<sub>`        | Defines subscription text                                                                   |
| `<summary>`    | Defines a visible heading for a `<details>` element                                         |
| `<sup>`        | Defines superscripted text                                                                  |
| `<svg>`        | Defines a container for SVG graphics                                                        |
| `<table>`      | Defines a table                                                                             |
| `<tbody>`      | Groups the body content in a table                                                          |
| `<td>`         | Defines a cell in the table                                                                 |
| `<template>`   | Defines a container for content that should be hidden when the page loads                   |
| `<textarea>`   | Defines a multi line input control                                                          |
| `<tfoot>`      | Groups the footer content in a table                                                        |
| `<th>`         | Defines a header cell in a table                                                            |
| `<thead>`      | Groups the header content in a table                                                        |
| `<time>`       | Defines a specific time                                                                     |
| `<title>`      | Defines a title for the document                                                            |
| `<tr>`         | Defines a row in a table                                                                    |
| `<track>`      | Defines text tracks for media elements                                                      |
| `<u>`          | Defines some text that is unarticulated and styled differently from normal text             |
| `<ul>`         | Defines an unordered list                                                                   |
| `<var>`        | Defines a variable                                                                          |
| `<video>`      | Defines embedded video content                                                              |
| `<wbr>`        | Defines a possible line-break                                                               |

#### Appendix - 4:

Feature Policy: Feature policy allows a web developer to enable, disable and
modify behavior of certain features and APIs.

> The `Feature Policy` header is now renamed to 'Permission Policy'

It is a mechanism to explicitly declare what functionality is used or not used
throughout your website. You can opt-in set of policies for the browsers on
specific feature used throughout the website. It's like: you have different
feature in you hand but you want to use a specific one for always. Toy can tell
it to your browser by `Feature Policy`. like:

1. Change default autoplay behavior of Video.
2. Restrict a site from using sensitive APIs like camera or microphone.
3. Modify iframe behavior.
4. Ensure images are sized properly and so on.

It can control which `origin` will use which `feature`. Essentially you write a
policy, which is an allowed list of origins for each freature. If every features
are controlled by Feature pilicy than the feature is only enabled to the current
document or frame if its origin matches in the allowed origin list
(`allowlist`). If no pilicy list is created, the browser use a deafult
allowlist.\

Policy = &sum; Policy Directives\
Policy Directive = &sum;(featureName + &sum;allowlist)

Feature policy is used in:

1. `Feature Policy` in header.
2. `allow` in iframes.

Scripts can access feature policy object by: `Document.featurePolicy` or
`HTMLIFrameElement.featurePolicy`.\

`Allowlist` - `allowlist` is a list of origins that takes one or more of the
following values, seperated by space.\

1. `*` : Feature will be allowed in this document and nested context of any
   origin.
2. `self` : Feature will be allowed in this document and nested context in the
   same origin.
3. `src` (`iframe`): Feature will be allowed in this iframe, as long as the
   document loaded in to it comes from the same origin of `src`.
4. `none`: Feature isdiscable at the top level.

Feature pilicy in `HTTPHeader`:

`Feature-Policy: <feature name> <allowlist of origins>` Several Policy can be
send, seperated with `;` or seperate `Feature Policy`

Feature Policy in `iframe`:\

```Html
<iframe src="..." allo="camera 'none'; microphone 'none'">
```

All iframe inherit the policy of their parent page. if iframe has an `allow`
attributes, the policies of the parent page and the `allowed` attribute are
combained.

#### Appendix - 5:

# Content Security Policy:

#### Appendix - 6:

# Global Attribute

Attributes that are common to all element are considered as `global attribute`.
Some elemetns amy not be effected by them.\

1. `accesskey`: Specifies a shortcutkey to focus/activate an element.

```html
<a href="#" accesskey="h">HTML</a><br />
<a href="3" accesskey="c">CSS</a>
```

`alt` + `accesskey` will activate the hyperlink.\

2. `class`: Space-seperated list of the case sensative words. They are usert to
   allow `CSS` and `JavaScript` to select and access the specific element by
   class selector function or DOM Method.
3. `contenteditable`: Indicate if the element should be editable by the user. It
   takes `true` and `false` as value. By default an Element is editable if the
   `parent` element is editable.
4. `data-*` : Custom Data Attribute, allow proprietary information to be
   exchanged between `html` and `DOM` representation by script.
   ```html
   <li data-id="1234">List value</li>
   ```
   `HTMLElement.dataset` property gives access to these data attribute value.
   `*` means any name. Point to remember that the `name` must not contain any
   capital letters.\
   `data-test-value` will be accessable via `HTMLElement.dataset.testValue` or `HTMLElement.dataset["testValue"]`.
   Dash is replesed by Capitalizing the `nextLetter`.
5. `dir` : Represents the directionalityofthe element Text
   ```html
   <p dir="rtl"></p>
   <p dir="ltr"></p>
   <p dir="auto"></p>
   ```
   This properties can be overwridden by css `direction` and `unicode-bidi`
6. `draggable` : Indicates wheather an element can be dragged.
   ```html
   <img draggable="false" />
   ```
   The value can be either `true` or `false`. As default `text`, `image`, `link`
   are draggable.We can always modify event `ondragstart` for specifing draging
   oprtation of all elements.
7. `enterkeyhint` : Defines the operation of the enter key in virtual keyboard
   (Mibile Keyboard) for `textarea` or `input` element or element with
   `contenteditable` attribute.
   ```html
   <input enterkeyhint="go" />
   <p contenteditable enterkeyhint="go"></p>
   ```
   Accepted values are:\
   `enter` --> Insert a newline.\
   `done` --> Nothing to input, and input method well be closed.\
   `go` --> Take the user to the target text they typed.\
   `next` --> Take user to the next field that accept text.\
   `previous` --> Take user to the previous field.\
   `search` --> takes the user to the reasult of searching the text.\
   `send` --> Deliver the text to it's target.
8. `hidden` : Boolean attribute indicate that the element is not relevent, and
   will not show.
9. `id` : Identifier which must be unique in the whole document. No white space
   is allowed. Element can have one single ID value.
10. `lang` : Defines the `language` of an element.
11. `nonce` : Identifier allows `script` element to perform security operations.
12. `spellcheck` : Defies weather an element should be checked for spelling
    errors. Possible values are `true` and `false`.
13. `style` : Add stlying declaration for an element.
14. `tabindex` : Allow to navigate through key board `tab`.\
    `-1` --> Means not reachable through sequential tab.\
    `0` --> Means focusable in sequential navigation.\
    `1-32767` --> Navigation moves to assending order. but `0` comes last.
15. `translate` : Tells if an element should be allowed to be translated or
    not.Possible values are `true` and `false`.
