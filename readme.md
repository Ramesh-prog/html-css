readme.md - it is used for taking notes. this file will not be executed because its a markdown file. 

HTML :- 

- html stands for Hyper text markup language. 
- It is used for building a structure of a web page. 
- we called html as a markup language because its contain the skeleton structure of a web page. 
- all HTML elements works on the basis of tag name. 
- all content of the HTML page are wrapped with 1 starting tag and ending tag. 

Ex. <html> - starting Tag, </html> - ending Tag

Head tag :- 

- head tag is wrapped on our HTML tag. 
- head tag contain title, meta elements & outer stylish sheet link. 

Body tag :- 

- Body tag also wrapped with our HTML element.
- Body tag contain whole body structure of a web page. 

Heading :- 

- Heading is the most important tag of a website because it contain heading of a web page. 
- it is denoted by h
- in html heading are of 6 types depends upon their size. 
- ex. h1, h2, h3, h4, h5, h6

paragraph :- 

- paragraph play a very imp. role in html because it holds actuall content of a web page.
- paragraph is denoted by p.

Break :- 

- we use break tag for break the line. 
- it is a single tag and its denoted by <br>.

Horizontal line :- 

- when we want to separate the field or text we can add a horizontal line in that place. 
- horizontal line is denoted by <hr>.

image tag :- 

- when we want to add a image in our website then we use <img /> tag in that place. 
- it is a single tag and it contain some attributes. 
- attributes means its a element that help our tag for their present. 
ex. height , width, src, alt is the attributes of <img /> tag. 

Anchor tag :- 

- when we open any other sites or links in our webpage , we need anchor tag to store and open it. 
- Anchor tag is denoted by <a></a>
- in that anchor tag we get some attributes like href, target. 
- HREF for hyper reference (reference a  a element into a another element)
- in target attribute we have 2 value
    1. _self - it is used for open the specific link into our own website
    2. _blank - it is used for open the specific link into a new website. 

HTML Formating :- 

- we used html formating for structuring our text in a right direction. 
- there are 10 HTML formating are there.. 

1. <b> - bold the text
2. <i> - Italic the text
3. <em> - Emphasized the text
4. <strong> - strong the text size
5. <mark> - Marked or Highlighted the text
6. <del> - Deleted the text
7. <ins> - inserted the text
8. <sub> - subscript the text
9. <sup> - superscript the text
10. <small> - smaller the text

HTML Table :- 

- in our day to day life we need a table structure for storing our data in perfect manner so html provide us a table structure where we can draw row and column according to our need. 

- <table> tag is our main tag for HTML Table. 
- in that <table> tag we have our table row <tr> , table data <td> & table Heading <th>.
- <th> -> we use Table heading for store our table headings. 
- <td> -> we use table data for store our data in side table
- <tr> -> we use table row for structuring our table in row wise. 

Table List :- 

- when we visit market in the evening we need to buy some fruits in our home then our mama give a list of fruits that we can buy from market so in that way HTML provide a list that we can store some data in side that list. 
- list are of 2 types.
1. ordered list.

- in ordered list we can store data by ordering structure like 1,2,3... 
- for creating ordered list we need 2 tag like <ol> - order list, <li> - list item

2. unordered list. 

- in unoredred list we can store data in unstructured way. 
- for creating unordered list we need 2 tag like <ul> - unordered list, <li> - list item. 

Homework :- 

- create a portfolio website where you can give your
1. name
2. image
3. proper description (about YOU)
4. educational details starting from KG1 (table format)
5. add a list where you can give your strength (ordered list), weekness (unordered list).
6. add your social link 
- upload the code on github and share the link in the official group (falcon 8.0) by 10am tomorrow.

HTML Forms :- 

- HTML forms are the forms like structure where we can do our login form or signup , signin form etc.. 
- The <form> is the main tag of HTML Form.
- there are multiple of HTML input tags are there like ..
1. <input type="radio">
2. <input type="submit">
3. <input type="checkbox">
4. <input type="text">
5. <input type="email">
6. <input type="color">
7. <input type="date">
8. <input type="file">
9. <input type="hidden">
10. <input type="password">
11. <input type="image"> .... 25...

HTML Block Level Element :- 

- Those tag who created a block structure in your designing. 
- there are mostly 2 types of block level element are present.
- ex. <div>, <p>

CSS (cascadding Styles sheet):- 

- CSS is used for styling or designing our web pages. 
- Normally CSS are the most important aspects of a web page. 
- basically CSS are of 3 types. 
- syntax of css :- 
h1{
    color: red;
    Text-align: center;
}

- in that above syntax h1 is our selector, color & text-align is our property , red & center is our value. 

1. inline css :- 

- inline css is a type of css which we have write in the same tag on HTML element. 
- inline css are basically used in a small code base websites. 
ex. 
<p style="color:red">today is tuesday and today we have strated css</p>

2. internal css :- 

- internal css is a type of css which we have writen in a style tag inside head section of HTML. 
- Internal CSS are mostlly used in many places. 
ex. 
<html>
    <head>
        <style>
            h1{
                color: red;
            }
        </style>
    </head>
    <body>
        <h1>today is a great day</h1>
    </body>
</html>

3. external css :- 

- external css is a type of css where we can write code outside the html page and linking the page in our html page through <link> tag inside head section. 
- external css are the most commenly used style element. 

Selector In CSS :- 

- selectors are those element whose select a item for the designing aspecific structure of web page. 
- There are 5 types of selectors are there in HTML 

1. ID selector :- 

- ID selector is basically used for designing a specific task or program. 
- ID selector is denoted by "#" symbol.

2. Class Selector :- 

- class selector is used to design more than one specific element.
- class selector is denoted by "." symbol.

3. Group Selector :- 

- group selector we used to design multiple element in a group.

4. Universal Selector :- 

- universal selector is used for designing same style on whole body part.
- it is denoted by "*" symbol.

5. Element Selector :- 

- element selector is used to select specific element for designing.

practice questions :- 

1. create a simple div with an id "box". Add some text content inside the div. set its background color to blue.
2. create 3 headings with h1, h2,h3. give them all a class "heading" & set color of "heading" to red.
3. create a button & set its background color to :
    - green using css stylesheet
    - blue using <style> tag
    - red using inline style.

text- properties in CSS :- 

1. text-allign: left/right/center -> align the text in proper place
2. text-decoration : underline/overline/line-through -> put a line on a text
3. font-weight : normal/bold/bolder/lighter -> specify the font weight
4. font-family : arial ... etc -> styling our font in differnt fonts. 
5. line-height : 2px/3/normal -> distance between 2 lines.
6. text-transform : uppercase/lowercase/capitalize/none -> chenge the text style


practice task :- (10 min)

1. create a heading centered on the page with all of its text capitalized by default.
2. set the font family of all the content in the document to "times new roman".
3. create one div inside another div. 
    - set id & text "outer" for the first one & "inner" for the second one.
    - set the outer div font size to 25px & inner div font size to 10px.

Display Property :- 

- it means display the elements in a right direction. 
- there are 4 types of display element are present.

1. inline :- Takes only the space required by the element.
2. block :- takes full space avalable on width.
3. inline-block :- similar to inline element
4. none :- to remove element from document flow. 

Box-Model in CSS :- 

- we need to identify the box model for properly placed all the things in a web page and create all the things inside a box. 

- there are 5 types of box-model element are there like :- 

1. Height :- by default, it sets the content area height of the element
2. Weight :- by default it sets the content area width of the elememt.
3. Border :- used to set an element border.
4. Padding :- padding is used for the distance between content to box.
- padding-left
- padding-right
- padding-top
- padding-buttom
5. Margin

practice question :- 

1. create a div with height & width of 100px.
    set its background color to green & the border radius to 50%.

Units in CSS :- 

- we use units for mostlly handle of our responsive issue in css. 
- there are many units are there like.. 
1. px - pixel - it is fixed as per the size

2. % - percentage - it depends on parents element

3. VH & VW - viewport height & viewport width - it works on viewport i.e depends om total screen size , wheather it is laptop screen or tablet or phone.

4. vmax & vmin - viewport maximum & viewport minimum - it works basically your perfect responsiveness, when your laptop width is min to your phone height then it stop shrinking and it break the wording. 
- laptop width < phone height = break the line

5. em - basically em depends on parent element 
ex. when parent element is 20 px then our 1 em is 20 px like wise when we increase our em to 2em then we consider 2em = 40px.

6. rem - it is also a fixed unit. (1rem = 16px).










