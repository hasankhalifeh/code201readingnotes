# Chapter 4 HTML LINKS

    - Links are the defining feature of the web, because they let you move from one page to another. You usually use links for the following:
        1. links one website to another.
        2. Links a page to another on the say website.
        3. Links from one part of a webpage to another part.
        4. Links that open a new browser.
        5. Links that start up ur email and send new mail to someone. 

    - How to write a link, you write a link there the <a> elemnt. Anthing in between the <a> tag is a clickable tag, you specify the link using the href attribute.
    - When making larger websites it is always better way to organize your code by placing different sections of the site into new folders.
    - The top level folder is known as the root folder.
    - THe mainhompage of an GTML file is called index.html

    ## Relative URLS
    - Relative urls are used when linking pages withing your own website. When linking a page to your own website you dont need to specify a domain because of the relative urls. 
    - Email links can be created also with the <a> take here is an example of it; <a> href = "mailto.jon@example.org">Email Jon</a>.
    - If you want a link to open in a new window you can use the target attribute on the opening of the <a> tag. For exampe:<a href="http://www.imdb.com" target="_blank">.
    - Linking to a pecific part of the same page is by linking the element that is using the id selector you use the <a> tag but the href attribute starts with #symbol which then is followed by the id attribute. 
    - Linking to a specifc part of another page you can use the same way as mentioned above but as long as the page you are linking to has id attributed that identify specific parts of the page.

# Chapter 15 HTML Layout

    ## Key concepts in positioning elements.

    - There are two types of building blocks block level and inline box, and css treats each element in HTML as if it is in its own box. The block level box start on a new line and act as the main block of any layout for example <h1>, <p>,<ul>,<li> while inline boxes flow between the surronding text for example <img>,<b> and <i>.
    - If a block level elements sits inside another block level element the outer box is know as containing or parent element. 
    - Css has the following positioning schemes
        1. Normal flow, where each block element appears ona new line which causes each item to appear lower down the page then the other.
        2. Relative positioning this moves an element from the postion it would be in normal flow, either shifting top, right , bottom or left.
        3. Absolute positioning which positions the lemein in relation to the containing element. WHich is taken out of the normal flow.
    - Using box off set properties indicate where the position of the box is. Box set properties tell the browser how far from the top or bottom or right or left it should be put.
        1. Fixed positioning is a form of absolute positioning that positions the element in relation toe the browser window.
        2. Floating element is an element which allows you to take it out of the normal flow and position it to either the far left or right of a box.
    -Normal flow each block level element sits on the top of the netx one. 
    - Relative positioning moves an element in relation to where it would have been in normal flow .
    - Absolute postioning the position property is given a value of absolute it is taken out of the normal box flow and no longer affects the positions of other elements. 
    - Fixed positioning is a type of absolute positioning that requires the position property. 
    - Overlapping elements is when you used a relative or fixed or absolute positioning they can overlap. If the boxes over lap the lements could later appear in the HTML code sit on on top of the others. If you want to control the element that sits on top you can use the z-element.
    - Floating elements allows your to take an element in normal flow and place it to hte left or right. 
    - Using float to place elements side by side, there are many boxes that are next to each other. TO create a float you can either put it on the left side ,right side and both. 
    - Many web pages use multiple columsin their design this is done by using the <div> element.The three properties that are used for positionning colums in css are width, float and margin 
    - Fixed width layout desgins dont change the size of the users brwoser. Measurments tend to be gien in pixels. 
    - Liquid layout desgins stretch and contract as the user increases or decreased the size of the browser. 
    - To create a fixed width layout they width on the main boxes will be specified. Here can use use the <div> element with li or ol elemtns for a list. 
    - A liquid layout used a percentage to specify the width of each box. 
    - Layout grids when creating a website there are ways and arragement for the webpage so it is more appealing to the user. 
    - CSS frameworks aim to make ur life easier by giving us the code for common taks. 
    - Some web pages split up their css styles rules into different style sheets. You can take add two ways,
        1.Your html page can link one style sheet and that sheet can use the @import function.
        2. In the HTML you can use a different link elemnt for each style sheet.
    
# Java
    - The basic structure of the an html element will look like this;
    <!DOCTYPE html>
    <HTML>
    <head>
    <title><title>
    </head>
    <body>
    <main></main>
    <header></header>
    <footer></footer>
    </body>

    - Script is made up of a series of statements.
    - Scripts contaiin a very prcesie instructions.
    - Variables are used to temporarily sotre informatuon
    - Arrays are special types of veriables that store more than one piece.

# 6 Reasons of Pair Programming

    - Pair programming involves two roles the driver and navigator. The driver is the programmer you types the code and only person doing it. The navigator uses their words to guide the driver but does not directly input into the computer. 
    - Why do people pair program, its because there are many languages out there and having two people that know these languages make it easier.
        1. Its much more efficient for two people to do the same code. It could be easier catching mistakes. 
        2. When two people are working on the same code it could be way more engaging and harder to procrastinate or track off when somone is beside you. 
        3. You could also learn from each other, each person could come from a different coding background and help each other get to a better point.
        4. Ofcourse this helps your social skills, and social skills is important because communication is the key to any business not just coding.
        5. A common step of job interviews are pair programming between the employee and applicant and they can code together where the employee can grade the applicants skill.
        6. WHen working in groups it helps you get ready for work enviroments as there is alot of social acitives and could help you gain more informaion from others.
        



