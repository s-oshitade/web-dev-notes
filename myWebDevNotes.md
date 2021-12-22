# SECTION 1: PREAMBLES

> Note: Links to most of the resources in this web development course can be found here: https://www.appbrewery.co/p/web-development-course-resources


## Section 1(4) - 12 Rules to learn code
1. Trick your brain with the 20 minute rule
2. Code for a purpose
3. There is no perfect programming language 
4. Understand what you're writing
5. It's OK to not know 
6. Be a copy cat
7. Be accountable
8. Keep learning
9. Play Foosball
10. Get a mentor
11. Get into the habit of chunking
12. Break someone else's code

_Credit: Angela Yu, Lead Instructor at the App Brewery_

## Section 1(7) - How to get the most out of this course
- Don't code along. Instead, watch the video and then reflect on your understanding of the content. Query why a code is written and preempt the result you expect to see. 
- Take notes after those 10 minutes of watch for understanding. These notes will become valuable to you in your journey.
- Then get on your code editor and try to replicate what you have just watched, without looking at the code from the video. Iterate if necessary.
- Review your notes and pick out questions and keywords that you want to research on later. You can also include memory hints for yourself. 
- Change the playback speed to fit your requirements.
- Try not to skip any lessons. You can playback at a higher speed if you find some content too easy.
- Rewatch videos that you find difficult. If you still don't understand some aspects after rewatching, bookmark it and take some time to research around the topic. If you come back to the same video after a couple of days of researching, it will become much easier to understand.
- Practice and perseverance leads to mastery.
> Embrace situations where you struggle or get stuck. Use tools like Google and stackoverflow to get unstuck. Enjoy that feeling that comes when you finally solve a problem. `Consistent practice leads to mastery!`
```
Will you quit when you get stuck? Remember that good programmers just stare at the screen more than half of the time! You will be hired to solve problems, so get used to the stuck-unstuck cycle. Enjoy it!
```
***
## MY BACKLOG

* https://eslint.org/

* https://www.frontendmentor.io/challenges/space-tourism-multipage-website-gRWj1URZ3
* Practice wire framing with https://balsamiq.cloud/sio79i5/projects.

***

# SECTION 2: INTRODUCTION TO HTML 

https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf
https://docs.emmet.io/cheat-sheet/ 

Use `<br>` to insert a blank line or to move content to the next line. This does not require the closing tag. The break tag `<br>` is a self-closing tag. Use the horizontal rule `<hr>` to draw an horizontal line. This is another self-closing tag. 

The head holds information about the web page and tells the browser how it should handle the page. The image tag is also self-closing. 

```
<img src=""> img -> HTML element | src="" -> HTML attribute.
```

Asides hosting pics on sites like FB/ LinkedIn, images can also be saved directly into the project folder. So, source will be something like:

> `<img src="seun.png" alt="seun's profile picture">`. If I had an images folder, then I would have to add a path like so: `"images/seun.png"`.

### Please review the docs for the image element: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img

### Also check out: The list element (and related elements ol, ul, menu) https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li

### 

> Side notes:
Regular review of documentation is very vital to your journey. Make it a daily habit if possible. Some good sources include https://developer.mozilla.org/en-US/ , https://devdocs.io/ , https://www.w3schools.com/.

Go and master the shourcuts on emmet https://docs.emmet.io/cheat-sheet/ and your choice code editor https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf.

You can upload your images to https://photobucket.com/explore . To quickly get circular cuts of images, you can use https://crop-circle.imageonline.co/ .

## HTML Links and Anchor Tags
The HT (hypertext) in HTML is executed with "a" tags. Anchor tags are extremely important in web development. The href is the hyperlink reference.

> `<a href="https://...">Hello</a>
<a> -> HTML element | href -> HTML attribute | https://... -> Link destination | Hello -> Link Text. `

You can use a tags to create satellite pages that link back to your index.html such that you have a website rather than just a web page.

> `<><a href="mailto:seun.oshitade@gmail.com">Email Me </a><p>`

>`<><a href="tel:77777777">Telephone</a><p>`

### You should definitely review the entire a- tag documentation on MDN. It's worth it. Afterall, HTML is all about links, right?  https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a

### Complete the goal-setting framework that has been provided.

# My favorite shortcuts
### Collect favorite shortcuts here. The ones that I actually use all the time!

## VS Code
1. Copy or cut entire line without highlighting. cmd+c and cmd + x respectively
2. cmd + direction to move to the very end of row or page.
3. Command palette - Instead of cmd + shift + p, just hit F1!

## My Mac
1. Emoji Keyboard: cmd + ctr + space. Or better still, just type the function key (based on my set preferences)!
2. Page down on Mac: fn + down-arrow.

## Emmet
1. For all elements, just start typing the element name and hit enter
2. If you want 6 divs, type div*6 + enter. Applies to any other element

# SECTION 3 
## HTML TABLES 

### Docs - https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table ; https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form

While the main job of tables is to display structured data, it can be used to affect the layout of various HTML elements on a web page. Alot of styling attributes of tables are better handled with CSS. They are therefore mostly deprecated. Tables have three main components: <thead>, <tbody> and <tfoot>. In practice, only the first two are often used. Each component consists of rows <tr> and cells to hold the data - <th> and <td> in the <thead> and <tbody> elements respectively.

`Note that table cells are wrapped in <tr> elements. No columns.`

Here's an example of what a table layout might look like:
```javaScript
<table>
  <thead>
    <tr>
      <th>Insert info here</th>
      <th>Insert info here</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Insert info here</th>
      <th>Insert info here</th>
    </tr>
  </tbody>
  <tfoot>
  </tfoot>
</table>
```
Using tables for layouts is not a great idea. There are more powerful tools. Note that you can easily introduce padding in your tables by using the cellspacing property, e.g. `<table cellspacing="20">`.

`The various sub-elements for tables are valuable when styling with CSS. Tables can also be used for layouts including images, texts, and so on.` The code used in my basic html-based exercise site illustrates the use of tables (and forms). https://github.com/s-oshitade/html-personal-site.

## HTML FORMS

### Official docs - https://devdocs.io/html/element/form . To be reviewed!
MDN refere for HTML: https://developer.mozilla.org/en-US/docs/Web/HTML/Reference 

Sample from my exercise: https://github.com/s-oshitade/html-personal-site/blob/main/contact.html `(Lines 16 - 24)`

Angela Yu on forms - 1: https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12287490#questions

Angela Yu on forms - 2: https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12287496#questions

# SECTION 4 - INTRODUCTION TO CSS 

### Docs - https://developer.mozilla.org/en-US/docs/Web/CSS/Reference. Check out the article on background color. https://developer.mozilla.org/en-US/docs/Web/CSS/background-color 
CSS broder-style: https://developer.mozilla.org/en-US/docs/Web/CSS/border-style

Checkout the stanford css cheat sheet here: https://web.stanford.edu/group/csp/cs21/csscheatsheet.pdf

`You must make a habit of looking up stuff for yourself on google. There's no other way to survive as developer!`

Look up named colors here https://developer.mozilla.org/en-US/docs/Web/CSS/color_value. Highly recommended for bookmark! You will also find the corresponding HEX values.

CSS's only purpose is to style mark-up language such as HTML, XML. 

There are 3 ways to use CSS: inline, internal CSS and external CSS links. The latter is the recommended approach.
### A tool for finding beautiful colors and color palattes is called https://colorhunt.co/.

Examples:
1. Inline: `<body style="background-color:blue;">`

2. Internal: In the `<head>` element:

`<style>
 body {
   background-color: #EAF6F6;
 }
</style>`

Note that there are some default CSS styles applied by your browser. You can use Google to look this up. WS3 has a good section on this.On the chrome devtool -> Inspect -> Styles, you will find this as "user agent stylesheet".

> One of the most important concepts in learning CSS is realizing that pretty much everything that exists on the web page are essentially just boxes. Use the pesticide chrome extension to see those boxes on your browser.

You can use percentages to represent size.

3. External
`<link rel="stylesheet" href="css/styles.css">`

> Very important CSS lessons can be found in the debugging exercise here: https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12287560?start=165#questions

Arrange css rules in alphabetical order, especially when the list gets long. It makes debugging easier.

There are so many properties on CSS. Don't try to memorise them. Just use the index [here](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference) . 

This site is great for emojis - https://emojipedia.org/.

border-radius: 100% -> circular

## CSS Selectors
css selectors: tags, classes, ids. -> Increasing selectivity. 

To target tags, just use the tag name directly. To target classes and ids, use `.` and `#` respectively.

## Classes vs. Ids

When there are conflicting rules, ids overrule classes and classes overrule tag selectors. You can see these using the chrome dev-tool: Over-ridden rules are striked out.

>You can only have a single instance of one particular id name inside a single page. Ids must be unique. Use ids to apply a specific style to a single element on a page. Whereas you can use a given class multiple times on a page. So you can use classes to group related elements that should follow the same css rule(s). 

The analogy of name and passport number is apt. Many people can have a particular name, but your passport number should be unique to you.

You can't have more than one id for a particular element. `<h1 id="heading big"> wil not work`. But any HTML element can have more than one class. While tag and class selectors are widely used, id selectors are used more sparingly.

`Another interesting feature regarding css selectors is something called a pseudo-class.`


>If you have a look at some of the properties in the css refereence [here](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference), you will find that some them start with a colon, such as `:active`. These are called pseudo classes. And this is because HTML elements can have different states.

For instance, you can get a css element to change based on whether you're hovering over a piece of text or an image or not. These are two different states: `hovering over` or `not hovering over`.

The pseuo-element that you will most commonly find is the hover element. Read the documentation on [click](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover).

```javascript
/* Selects any <a> element when "hovered" */
a:hover {
  color: orange;
}
```
# INTERMEDIATE CSS
The previous personal website won't get us hired! It looks more like a computer scince professor's CV website.😃

Let's make something that is inspired by [Sean Halpin's personal website](https://web.archive.org/web/20180819202235js_/http://seanhalpin.io/).

You can link a css stylesheet like so:
`<link rel="stylesheet" href="css/styles.css" type="text/css">`

The type="text/css" is optional but you must make accurate reference to the location of the css file, i.e. href (hypetext reference).
## FAVICONS
To create a favicon (favorite icon), go to https://www.favicon.cc/.

Link your favicon like so:
 ` <link rel="icon" href="favicon.ico">`

Using `Pesticide`, hold down control and hover on the boxes. You will see some information at the foot of the page, about the element that you're hovering on.
## HTML DIVS
You can use divs to structure your html elements into separate `container`s or boxes that can be styled separately. 

`div` stands for Content Division Element. The div can have a height based on the css rule that you apply to it. But when it has content, a div is also able to assume a height that is just sufficient to `CONTAIN` the elements within it.

You can use the chrome dev tools -> inspect -> Elements -> styles to experiment and test out the changes that need to be made. What you see is what you get. ONce you're satisfied with what you can see, you can then head over to your css and implement it.

## THE BOX MODEL OF WEBSITE STYLING!💪
Every single element on screen is treated as a box by CSS. By styling that box - it's height, padding, margin, etc - that's how we can the determine how the elements can be laid out and how they will show up on a screen. This concept is known as The Box Model.

When a div container has no content, then it will have no dimension unless you specify css rules, e.g. height and/or width.

Padding makes the element 'look' different in size, but margin does not. That's because the padding takes the background color of the element, so it pads the content. While the margin does not take the color of the element, it pushes away other elements and creates a space between elements.
### The border
The [border](https://developer.mozilla.org/en-US/docs/Web/CSS/border) is a very important aspect of a box. The border shorthand CSS property sets an element's border. It sets the values of [border-width](https://developer.mozilla.org/en-US/docs/Web/CSS/border-width), [border-style](https://developer.mozilla.org/en-US/docs/Web/CSS/border-style), and [border-color](https://developer.mozilla.org/en-US/docs/Web/CSS/border-color). Please read each of the linked docs - border, border-width, border-style, border-color. Also review the reference for margin and padding. With these, you will be able to handle the CSS box/container well.

Here's a lecture on [The Box Model](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12287726#questions/8856680). Please re-watch!

## THE CSS DISPLAY PROPERTY
The display property has four different values.
1. `Block` elements such as `<p>`, `<h1 - h6>`, `ul, ol, <hr, article, section, div`
2. `Inline`, such as span, img, `<a>`
A major issue with the inline elements is that you can't set the width to a particular value. It won't respond. On the other hand, block elements allow you to set the width but it won't allow multiple elements to sit on the same line.
3. If you change the display to `inline-block`, then you get the best of both worlds. Images are typically handled as inline block elements.
4. `display: none`. This removes such element from the website.
Quite similar to display: none, there's a property called visibility. When the property `visibility` is set to a value of hidden, The element disappears but its original position is kept.

## CSS STATIC AND RELATIVE POSITIONING

...Exploring css positioning in more detail. It's important to note that: even without css, our html has pre-defined rules for how it should be displayed on your webpage. 

`We have to understand how things get positioned by default before we can go on to change it and bend it  to our rules without getting confused or stuck.`

- Rule #1: Content is everything. Inline elements only take as much width and as much height as the content. So if you have a span that contains a long word, then you will have a short width. And if you have a span that contains a loong word, then you will have a long width. With block elements, even though they take a 100% of the width, the height is still determined by the content. So your content is the first thing that determines how large things gets displayed and what the height and width will be. And this is despite any CSS.
- Rule #2: The order of your elements on-screen comes from your HTML code.
- Rule #3: Children sit on top of top parents. So if you image that you have X, Y, Z dimensions, with the z dimension reprenting closeness to the user relative to the screen. A paragraph that is nested in a div would be closer to the user than the div.
These 3 rules determine the placement of objects on the screen, just based on HTML.

`POSITION: With CSS, you can POSITION elements on the screen the way that you want. Most times, you would need to do this as a developer.`

There are multiple ways to change the Position property of elements with CSS. They include (among others):
1. Static - Default.
2. Relative - Position relative to where the element shoud lhave been by default.
3. Absolute - Position relative to parent. Absolute positioning takes element out of the flow of HTML, unlike relative positioning that leave the 'ghost' of the element behind.
4. Fixed: A fixed element stays in its position even when you  scroll through a web page. For instance, it can be implemented like so:

```javascript
.className {
  position: fixed;
  top: 0;
}
```

The position property uses four coordinates - top, right, bottom, left. Think of these coordinates as special margins. 

`You can use containers (e.g. divs) to fine-tune the position of elements on screeen by using a combination of relative and absolte positioning.`

## THE DARK ART OF CENTERING ELEMENTS
The easiest way of centering elements is by tapping into a property called `text-align`.This property has to be set inside of a parent container, such as the body.
```javascript
body {
  text-align: center;
}
```
This works as long as we've got inline block elements sucha as images, or if we've got full-width block elements like h1 or p tag.

When you set a width property for a child element of the body in the example above, then the text-align rule would not apply to such child element.
In such a case, you can still center to the child element by using `margin-auto`.

As an example further to the one above:
```javascript
h1 {
  width: 10%; // this takes our h1 element out of the influence of the text-align above
  margin: 0 auto; //sets the element to be horizontally centered on display.
}

```

With reference to the css-site example, our bottom cloud has an absolute position. In order to position it relative to something, then one of the parents has to have its position set to relative, and if we don't, then it will be relative to the body.

## FONT STYLING

There are two very important decisions that you have to make in web development:
1. A color palatte, and
2. A font scheme

There are 5 major font families listed on our code editor - Serif, Sans-serif, monospace, cursive and fantasy. monospace is good for reprensting code.  For most browsers, the default serif is the times font, and the default sans-serif is Arial.

Use https://www.cssfontstack.com to check out the usage of fonts.You can easily copy font families and ``stack of fallbacks` here. Use a font stack to influence how you're site is rendered when a user doesn't have your primary font installed on their machine. 

`To ensure that EVERYBODY has the same experience on your website, then use something called  FONT EMBEDDING.` Refer to https://fonts.google.com/. After selecting preferred fonts, copy and paste the `<link>` to your html. This will take users that don't have the fonts installed, to the ref site. And then copy/paste the css rules accordingly, to specify how your selected fonts should be applied to the body and/or specific elements on your site.

`Aside` - Use lorem ipsum to set up your websites when you haven't gotten content for the txt yet. Just type lorem on your code editor and enter. You can also use the * operator to speicify how much of lorem content you need before you hit enter. You will find the following sites useful: https://loremipsum.io/ , lorem-ipsum.perbang.dk . For images, check google or got to https://www.flaticon.com. There are more than half a million icons. Download as png.You can also right-click and copy the image address to your src. For animated GIFs, head over to giphy.com. If you select the sticker tages, then your background colors will go all around it. 

## CSS Sizing
* Percentages can be used for sizing. This is one way of achieving dynamic sizing.

  `100% === 16px`
* Another way to size dynemaically is the use of `em`. This should not be confused with the em tage in HTML which is used for emphasis/ italics. Historically, the `em` was the width of the capital letter `M`. This is no longer true. What is true though is that 

  `1em === 16px`

`Aside`: Make a habit of inspecting the sites of great companies like Uber, TechCrunch, Airbnb, Netflix, etc. Use your dev tools to check out their code and tinker around with it. You stand to learn alot!

With zoom, it doesn't matter if your website is statically or dynamically sized because the zoom will scale your entire content accordingly.

> `An important consideration:` When you're using em or percentages, that value is inherited. So if the parent (e.g. body) specifies a font size of 2em, and the child indicates 5em, then the font displayed will factor in the sizes mentioed in the parent and child elements. This can distort our content. This `rem` solves this by ignoring the parent size. `rem` is relative to the root, not the parent/ enclosing container. `1rem is always === 16px`. So `rem` dos not get affected by upstrem size changes.

```javascript
//rem is recommended as the most adaptable and least error-prone unit for dynamic sizing.
```

## My top dozen css properties
```javascript
/*
Here's a list of my top dozen css properties. I will take the time to review the full documentation for these properties [here](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference).

  - margin
  - border
  - padding
  - display
  - position
  - font-weight
  - line-height
  - font-family
  - flex
  - box-sizing
  - width, height
  - z-index

  OTHERS:
  - Text decoration
  - color
  - hover
*/
```

## CSS FLOAT AND CLEAR
Use the float property to wrap texts around an image. You also get to decide where the image should float relative to the texts. So the values for the `float` property can be float: left; right; or none. [Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/float).

"The float CSS property places an element on the left or right side of its container, allowing text and inline elements to wrap around it. The element is removed from the normal flow of the page, though still remaining a part of the flow (in contrast to absolute positioning)".

To prevent the text from wrapping around the image, then use the `clear` property. Think of the clear as the anti-float.

"The clear CSS property sets whether an element must be moved below (cleared) floating elements that precede it. The clear property applies to floating and non-floating elements."

`Float is often abused. Don't use it for positioning. This will save you from headaches that could result from the side-effects of the Float property.`

The float lecture is worth re-watching on [click](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12287672#overview).

`Aside` - The [CSS button generator](https://css3buttongenerator.com/) is amazing and should be used regularly.

## GET MORE PRACTICE! SEE NOTE BELOW FROM ANGELA.

> Hey,

In our in-person bootcamps, I often encourage students to practice the skills they've acquired. Because after all, it's practice that turns a beginner into a master.

So why not try your hand at some of these optional front-end challenges and get more practice with HTML and CSS?

https://www.frontendmentor.io/challenges/space-tourism-multipage-website-gRWj1URZ3

Angela

Tip from Angela on [click](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/17966538#questions).
***
# SECTION 6 - INTRODUCTION TO BOOTSTRAP
## WHAT IS BOOTSTRAP?
Bootstrap is a frontend library. It's a bunch of code that can make website design much easier. 

![](bootstrap.jpeg)

Originally developed by Twitter, it is now free and open source. It's one of the most-starred repos on Github. It is THE most popular frontend framework/ library.

It enables you to make your site responsive. Will bootstrap, you will be able to change your layout depending on the size of the device/ view port. It also goves you access to a bunch of pre-styled elements that you can easily drop into your code/ site.

`Unlike codepen`, [codeply](https://www.codeply.com/) `is a playground that allows you to include frameworks like react, bootstrap, vue, Tailwind, etc.`

## INSTALLAING BOOTSTRAP

https://getbootstrap.com/docs/5.1/getting-started/introduction/#quick-start

The simplest way to use Bootstrap is to copy the bootstrap cdn and paste it as a linked css stylesheet. CDN means content delivery network. The CDN cuts down on latency or how long it would take to load the website. Because of the popularity of bootstrap, your customers probably already have the files cached on their browsers.

Another way is to copy and paste the `Starter Template`. Note that the starter template usese some JS and jQuery.

The third way to use B is to download the CSS and JS source code and include them as relative files in your project. Caching does not occur in this scenario.

In the remainder of this course, we will use option 1. For your projects in the future, option 2 is recommended. The starter code ensures tha you have everything you need to maximally leverage Bootstrap.
Installation video available on [click](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12287996#questions).

## WIREFRAMING
A wireframe is a low fidelity representation of your proposed website. It enables iteration and buy-in on the design before implementing the website/app.

A mock-up is a HIGH fidelity representation. What you see is what you get.

Workflow
* Check out UI patterns at ui-patterns.com. Look at other people's websites.
* Wireframe
* Mock-up. If you want to go the extra mile, you can even create an animated prototype. A really good resource for getting inspiration on all these is https://dribbble.com/.
`dribbble.com is a fantastic place to get inspiration for your site!`

* Pencil and paper is a great way to do your wireframing. Use sneakpeekit.com to print out accurate view ports for your device of interest.
* For more advanced wireframing, https://balsamic.cloud is the indiustry standard. It's quick and collaborative.

***
# SECTION 9 - INTRODUCTION TO JAVASCRIPT ES6.
`Caveat - My JS notes will be very lean as I have learned alot of JS already`.

# SECTION 11 - THE DOCUMENT OBJECT MODEL

## ADDING JAVASCRIPT TO WEBSITES
There's no point writing javaScript codes if we don't know how to incorporate it into our websites, right? Recall the 3 ways to incorporate CSS into websites? Well javascript works very similarly -> 
1. Inline
2. Internal
3. External

We can add inline js by simply adding an attribute to html element. For example:

```javascript
<body onload="alert('Hello');"> 
  <h1>Hello!</h1>
</body>
// note the careful use of double and single quotation marks.

```
This means that whenever the body element gets loaded up, then whatever javascript code that exists between the double quotation marks gets carried out. This is not good practice. It's not modular and very difficult to debug.

The internal approach involves the use of a script tag, like so:

```js
<script type="text/javascript">
  alert("Hello");
</script>
```

This is done in the body of the html.

Lastly, we can incorporate JS into html by using linking to an external source as shown below. This is usually inserted on the line just before body closing tag.

```js
<body>

 //Insert other lines of code here.

  <script src="index.js" charset="utf-8"></script>
</body>

/*index.js
  alert("Hello");
*/

```

`The position where introduce the js script matters a huge deal.`

Interesting: From index.js, you can change the content of the innerHTML from Hello to Goodbye. Learn more about selcting and manipulating HTML content in the next couple of sections.

## INTRODUCTION TO THE DOCUMENT OBJECT MODEL
With HTML and CSS, you can build a static website. But you need your website to be interactive. This is the problem that the DOM solves. It basically cataloues the webpage (HTML) into individual objects that we can select and manipulate.

![](2021-12-22-03-23-22.png)

The task of converting the html into  the DOM is done by the web browser when you load your web page.

![](2021-12-22-03-26-35.png)

What it does is that it turns each of the html elements into and their associated data into a tree structire with a bunch of objects which you can select and manipulate. The reationship between the html elements is mapped out in the tree diagram.

Everything that is contained inside your html is contained in an object called the "document".

Our objects inside the DOM can have properties and actions. You can use the dot notation to select objects in the DOM and manipulate their properties and/or methods.

> On the DOM, we can:
* GET properties 
* SET properties by using the `=` to assign a desired value
* CALL a method on a selected object 

![](2021-12-22-04-26-07.png)

`The key takeaway here is that we can access the properties and methods by using the dot notation, and by so doing we can manipluate the object.`

Angela's introduction to DOM manipulation is worth rewatching!...on [click](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12374120#questions/11415058).

Useful sidenotes - Some other syntax to access the nth child of an object.

![](2021-12-22-04-55-06.png)

## SELECTING HTML ELEMENTS WITH JAVASCRIPT

The use of querySelector to access DOM objects was introduced in the last [section](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12374120#questions/11415058). Other ways include:

1. document.getElementsByTagName("li")[n]
2. document.getElementsByClassName("btn")[n]

Note  that in "1" and "2" above, "Elements" is in `plural` form, and the result is an `array`. Hence you have to use the bracket notation to access the array element of interest using the bracket notation. This must be done even if there is only one element in the array, in which you will access it at index 0.

3. document.getElementById("title")
This is sigular and a single item is returned, not an array. Therefore, this would work fine: 

// document.getElementById("title").innerHTML = "Good Bye";

4. document.querySelector("")
The query selector approach is a much more approach as you can combine (for instance) a tag with a class to reach a specific element, and so on. Unlike 1 - 3, you can use the 4th approach to select an element, a class or an id. The selector should follow the exact format that you use for selection in CSS. You can combine to selectors to achieve higher specificity like so:
document.querySelector("li a"); 
When selecting a list item that is also inside a class "item" on the same level, you can select like so:
document.querySelector("li.item). Note that there's no space between li and item. This applies to the following example: 
`<li class="item"><a href="https://www.google.com">Google</a></li>`.

When you're not specific enough with the querySelector, it returns only the first item that matches. If you want to return ALL the matching items, then you will have y=to use `querySelectorAll` instead. To get specific using this array from `querySelectorAll`, you can use the bracket notation.

```js
You can use querySelector and querySelectorAll to achieve most of selection needs when working on the DOM.
 
```

## MANIPULATING AND CHANGING STYLES OF HTML ELEMENTS WITH JAVASCRIPT

When you're trying to change the property names of your html using javascript, you will find that the names are sometimes different from what you see in CSS. For instance, `font-size` will appear as `fontSize`. Notice the camel casing. Use this [link](https://www.w3schools.com/jsref/dom_obj_style.asp) as a guide for writing property names in js.

Also notice that the ALL the values have to be specified as strings. Even numbers.

## THE SEPARATION OF CONCERNS
In practice, we have to stay conscious of the following with respect to our :
1. HTML is for content
2. CSS is for style
3. JS is for behaviour

We've obviously not been following this rule closely because we have been changing styles of elements using JS.

The thing is we have make some style chnages on the fly to make our site interactive. There's a way to achieve this while maintaining separation of concerns!🤫 😉

```js
//Use the following code snippet for the explanations of DOM concepts:
//

```
![](2021-12-22-08-16-47.png)

1. Manipulating styles with ClassList: 

This is a property of every DOM object.

For example:

![](2021-12-22-08-11-45.png)

We can .add, .remove or. toggle specified classes.

For example, you can create styles for class .huge on the styles.css sheet, then manipulate the DOM as provided below:

`document.querySelector("h1").classList.add("huge");`

This way, our style is still in our style sheet and our behanviour is still in our JS.

2. Manipluating Text.

We already know about innerHTML. There's something called `.textContent`. The innerHTML will literally return the html, including the tag if it is nested. But .textContent will only return the text, even if nested.

![](2021-12-22-08-33-16.png)

3. Manipulating Attributes of html elements.

You can: 
* view attributes: `.attributes`,
* get specified attributes: `.getAttribute("insert attribute name")`, and 
* set attributes to preferred values: `.setAttributes("which attribite do you want to change, what do you want to change it to")`

![](2021-12-22-08-41-33.png)

`Angela's tip - Trick your brain with the 20-minute rule. Overcome the inertia to starting and leverage the intertia to stop!`