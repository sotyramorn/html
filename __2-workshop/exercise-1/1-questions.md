# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false ] `<div><span>hello</div></span>`

b) [ false ]

```html
<ul>
<li>one</li>
</ol>
```

c) [ false ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

Screenreader is a tool for visually impaired to help understand what is displayed on the screen. For example, if the reader is reading an article and uses a text-to-speech function, it will read outloud `h1` as the title and `p` as the content of the article

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
```html
<img src="image" alt="" />
```

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
```html
<ul>
    <li><a href="Link to gallery">Gallery Name</a></li>
    <li><a href="Link to gallery">Gallery Name</a></li>
    <li><a href="Link to gallery">Gallery Name</a></li>
</ul>
```

c) You want to sell designer hats. You need to receive orders from the user.
```html
<form>
    <label>Name:</label><br>
    <input type="text"><br>
    <label>Message:</label><br>
    <input type="text"><br>
    <input type="submit" value="Submit">
</form>
```

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
No, a button cannot be a child of button. A button is responsible for one action and not multiple

## Q5 - What is the most generic tag you can use?
the div tag

## Q6 - What do the following achronyms stand for?

a) `a` anchor

b) `ol` ordered list

c) `ul` unordered list

d) `li` list item

e) `tr` table row

f) `th` table heading

g) `td` table data cell

## Q7 - Usually, `td` elements are children of what kind of elements?
the table row `tr`

## Q8 - What is the difference between td and th?
`th` is the name of the row. `td` is the data for that row

## Q9 - Which tag makes the text appear bigger: h1 or h3?
`h1`

## Q10 - In which situation can you use self closing tags?
images, br, hr, input

## Q11 - What is autofilling and why is it important?
autofill will predict what the user is typing while filling a form as well as save time

## Q12 - Which attributes are always present in an img element?
`src` and `alt` is required in an img element. `src` will indicate the image location and `alt` will describe the image

## Q13 - Which attribute is always present for an anchor tag?
`href` is require in order to click and send to the page