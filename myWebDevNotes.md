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

Use <br> to insert a blank line or to move content to the next line. This does not require the closing tag. The break tag <br> is a self-closing tag. Use the horizontal rule <hr> to draw an horizontal line. This is another self-closing tag. 

The head holds information about the web page and tells the browser how it should handle the page. The image tag is also self-closing. 

```
<img src=""> img -> HTML element | src="" -> HTML attribute.
```

Asides hosting pics on sites like FB/ LinkedIn, images can also be saved directly into the project folder. So, source will be something like:

> `<img src="seun.png" alt="seun's profile picture">`. If I had an images folder, then I would have to add a path like so: `"images/seun.png"`.

### Please review the docs for the image element: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img

### Also check out: The list element (and related elements ol, ul, menu) https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li

### 

> Side notes
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
Sample from my exercise: https://github.com/s-oshitade/html-personal-site/blob/main/contact.html `(Lines 16 - 24)`

Angela Yu on forms - 1: https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12287490#questions

Angela Yu on forms - 2: https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12287496#questions