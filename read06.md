# Understanding the problem domain is the hardest part of programming

    -  There are common ways to answer this questions: 
            1. Learning a new technology
            2. Naming things
            3. Testing your code
            4. Debugging
            5. Fixing bugs
            6. Making software maintainable

    - When creating a domain you will face alot of issues and alot of thinking stratgies but the best way to think about it is thinking about a puzzle how do you start solving it.
        1. You starting by figuiring which is the major components are 
        2. Sort all the pieces by color.
        3. Put together the border
        4. Put the rest of them that you have broken up. 

    - This is the same method to creating a problem domain together. 

    - To understand the problem domain is the hardest part of programmingyou want to make sure you make it easier by:
        1. Making sure the problem domain is easier.
        2. Get a better understanding the problem domain 

# Chapter 3 Object literals (Java)

    - When you call a function that has parameter you have to specifiy what the values are and they should be in parentheses and follows its name, the vaules are called arugments and can be provided either as values or variables.
    - Some functions return info to the code that called them. 
    - Functions can return more than one value using an array.
    - Expressions produce values. They can used where values are expected. 
    - Function declartion: creates a fucntion that you can call later in your code. You have to give the function a name and if you wanna call it would be nameoffunction(); at he bottom.
    - Function expression: if you put a function where the interprester would expect to see an expression. And a function with no name is called anonymous function. 
    - The loction where you decalre a variable will affect where it can be used without your code. This is known as a variable scope. 
    - Local variables: where variable is created inside a function using the keyword var. 
    - If you create a variable outside of a function then it can be used anywhere in the script which is called a global variable. 




# Chapter 5 Document Object Model (Java)

    - The document object model (dom) spefcies how browsers should createa model of an HTML. The Dom is neither part of html or javascript it is a seperate set of rule. 
    - When opening a website the browser loads it and creates a model of the page, the dom specifies the way in which the browser should struck this model using a dom tree. 
    - Accesing and updating the DOM tree involves two steps:     
        1. Locate the node that represents the element you want to work with. 
        2. Use its text content, child elements and attributes. 

    - Methodsthat find elemenents in the DOM tree are called dom queries. When you need to work with an element more than once you should use a variable to store the result. 
    - Dom queries may return one element, or they may return a nodelist which is a collection of nodes. 
    - If a method can return more than one node it will always return a Nodelist, which is a collection of nodes. 
    - Single element node return use getElementbyid('id)
    - Css selector syntax that would select one or more elements hse querySelector('css selector').
    - Selecting one or more element given the value of their class attribute uses getElementByClassName('class')
    - Selecting all elements on the page with the specifies tag name uses getElementByTagName('tagName')
    - Uses css selector syntax to select one or mroe elements and returns all of those that match you would use querySelectorAll('css selector')
    - There are two ways to select an element from a nodelist: 
        1. The item() method
        2. You can use the length property 
    - Array syntax is preferred over the item() because it is much faster. Example 
        var elements = document.getElementsByClassName('hot);
        if ( elements.length >=1){
            var firstItem = elements[0]
        }
    - Selecting elements using class attributes you would use getElementsByClassName()
    - Selecing elements by tag name would be done by getElementByTagName().
    - White space nodes, travering the dom can be diffecult because some browsers add a text node whenever they come across whitespace.

    - Text content property allows youto collect or update just the text that is in the containing element. \
    - Textcontent: is to collect the text from the <li> element. 
    - You could come across a property called innerText but should be avoided for the following reasons :
        1. Support: most browsers adopted the property but for for example firefox does not. 
        2. Obeys CSS: It will not show any content that has been hidden in CSS.
        3. Performance: It can be slower to retrieve the content than the textContent property. 

    - There are two very different ways for addming or removing html content. EIther through the DOM tree the innerHTML propety or the DOM manipulation.
        - The innerHTML property: There are secuirty risks using the innerHTML:
            1. Approach: The innerHTML can be used on any element node. It is used to both retreive and replace content.
            2. Adding content: Store new content as a string in a varibale. Select the element whose content you want to replace. 
            3. To remove all content from an element you set innerHTMLto an empty string.
    - DOM manipulation easily targets invidiual nodes in the dom tree, where as innerHTML is better suited to updating the enitre fragment.
        1. Approach: Dom maniplates refers to a set of Dom Methods that allow you to create element and text nodes. 
        2. Adding content: to add content you use the dom method to create new content one node at a time. 
        3. Removing content: You can remove an element from the DOM tree using a single method.

    - using the innerHTML property you can access and amend the contents of an element inclluding child elements. 

    - Dom Manipulation offers another technique to add a new content to page using :
        1. createElement() creates an element that can be added to the DOM tree
        2. createTextNode() allows you to creata new text node to attach to an element.
        3. appendChild()

    - Dom manipulation can be used to remove elements from the Dom Tree
    - To remove an elemtn from the Dom tree  using removeChild(). 
    - A validation is when visotrs have input of charcters they need to supply information. 
    - When using innerHTML you could have issues with attackers and have to be careful with what input you can give a certain user on HTML

