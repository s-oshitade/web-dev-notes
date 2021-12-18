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

...Exploring css positioning in more detail. It's important to note that: even without css, our html has pre-defined rules for how it should be displayed on your webpage. We have to understand how things get positioned by default before we can go on to change it and bend it  to our rules without getting confused or stuck.


