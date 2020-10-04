# Text Chapter 2
    - Structural markup: elements that you can use to describe both headings and paragraphs.
    - Semantic markup: it provides extra information such as if emphasis is placed in a sentance 

    In HTML there are six types of headdings used starting from H1 to H6 and each one has a different size starting with H1 as the biggest. To create a paragraph in HTML you use the <p> tag. The <b> element makes the characters appear bold. 
    - Adding the <i> it adds it to becoming italic. 
    - <sup> is an element used to contain characters such as suffixes of dates.
    - <sub> it is an elemented used to contain character that should be subscript.
    
    ## Line breaks & Horizontal rules
        - <br / > If you want to add a break line in the middle of the paragrah you use that element.
        - <hr /> is used in between sections.

    ## Visual Editors & their code views
        - Visual editors, are created to make the website or page more appealing by adding headers, bold , italic and line break in between paragraphs.
        - Code Views, are created by the coder so you can manually change or edit the HTML website.

    ## Strong & Emphasis 
        -<strong> this element indicates that the content has strong importance.
        - <em> this element indicates that subtly changes the meaning of the sentence.
        - <blockquote> this element is used for longer quotes that take up an entire paragraph. 
        - <q> this element is ised for shorter quotes. 
        - <abbr> this is used as an abbreviation or acronym.

# Introducing CSS chapter 10

    - Css allows you to change the content of how the element. 
    - The key with understand what css is to imgagine there is an invisble box around the HTML. 
    - Css allows you to create rules and control the way the person uses the website or article. 
    - A css rule has to parts a selector and a declaration. Selectors indicate which element the rule is applied to. The declaration indicate how elements referred to in the selector should be styled. 
    - Css declarations are made up of two parts a property and a value. Properties indicate the aspects of of the lement you wanna change. Values specify the settings you want choosen. 

    ## Using External CSS
     - <link> element can be used in an HTML document to tell the browswer where the css is. 
     - Href specifies the path to the css file.
     - Type this attribute shows which document is being linked to.
     - rel specifies the relationship between the HTML and file it is linked to.
     - <style>  element should be used to indicate the styles that are put into css. 
     - There are different types of css selectors in css such as;
            1. universal sselector apples to all elements. 
            2. Types selector which matches the elements names.
            3. Class selector which matches an element whose call attribute has a vaule that matches the other one.
            4. Id Selector matches an element whose id attribute has a value that matches it. 
            5. Child seletor which matches an element that is a direct child of another. 
            6. Descendant selector matches ana element that is an decendent of another speicfied element.
            7. Adjacent sibling selector an element that is a sibling of another.

# Javascript
    Placing a script in your HTML can be placed anywhere but the best place to place your <script> is under the footer before the body. 

    ## How to use objects and methods
        - document.write('text input here'); the first part document object represents the entire webpage. The write method of the document allows new content to be written.

    ## Chapter 2 Basic javascript instructions
            - A script is a series of instructions for the computer to follow, each individual instruction is known as a statement. 
            - Comments explain what your code does. 
            - Variables are used to define certain things for example age > 18 will not be able to use the motoercycle.
            - How to declare a variable using the Var element, and whatever comes next is the variable name. 
            - Variables are used to storea a number or a string. 

    # Rules for naming variables
        - Here are six rules you must follow when giving a variable;
                1. The name has to behing with a letter, $ , or an underscore.
                2. The name can containt letters, numbers, $, and an underscore. Do not use - or . in a variable name. 
                3. Use keywords, they are special words that tell the reader to do somthing specific. 
                4. All variables are case sensitive. 
                5. Use a name that describes some information that varibles can store. For example firstname might be used to store someone first name. 
                6. If the variable name is made of up more than one word, use a capital letter for the ifrst word letter of the every word after the first word.

# Arrays   
    - An array is a special type of variable, it doesnt just store one value it stores a list of values. 
    - You should use array's when you are wokring with a list or a set of valued related to each other. 
    - Creating a array is used but inputting in java script this following command;    
            var colors;
            colors = ['white', 'black','custom']

            var el = document.getElementByID ('colors');
            el.textContent = colors[0];
    
# Values in arrayys
    - Values in an array are accessed as if they are in a numbered list.
        1. Numbering items in an array.
        2. Accessing items in an array.
        3. Number of items in an array.

    - Expression evalutes into a single value. There are two types of expressions:
        1. Expressions that just assign a value to a variable. In order for a variable to be usefull it needs a given value. 
        2. Expressions that use two or more values to return a single value.

    - Expressions rely on operators which allow programmers to create a single value from one or more valules. 

