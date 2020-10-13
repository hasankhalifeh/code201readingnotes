# Chapter 7: Forms HTML 144/175
    - 'Form' has referred to a printed document that contains spaces for you to fill information.
    - There are several types of form controls that you can use to collect data from visitors here are some of teh following:
    ## Adding text:
        - text input: used for a single line of text like emails.
        - Password input : Is a single line text box where it masks the charcters.
        - Text area: for longer areas of texts.
    ## Making choices
        - Radio Buttons: For use when a suer must select a set options.
        - Checkboxes: when a user can select and unselect options.
        -  Drop-down boxes: when a user must pick one of the number of options.
    ## Submitting forms
        - Submit buttons: to submit data from your form to another web page.
        - Image buttons: similar to submit buttons but they allow you to use an image.
        - File upload: allows users to upload files to a website.
    
    - How do forms work, forms work when a user fill in a form and presses a button to submit, the information then is sent though a server with the user entries, then the server procees the information using a programming language.
    - Form structure:
         - <form> controls live inside a form element. 
         - action : Every form elemen has a action attribute. 
         - Method: forms can be sent using one of the two methods get or post. 
         - ID: the value is used to identify the form distinctly from other elements on the page. 
    - Text input:
        - <input> element is used to create several different form controls
        - type = 'text': when the type attribute has a value of text, which creates a single line text input. 
        - Name: when users enter info into theform, the server need to know which form to control to get the piece of data.
        - size: the size attribute should not be used on new forms. 
        - Maxlength: you can use this attribute to limit the number of characters a user may input. 
    - Password input
        - <input>
            - type='password': when they type the attribute has a value of password it creates a text box that acts just like a sing line text input.
            - name: the name attribute inddicates the name of the password input. 
            - size, maxlength: this carries the size and maxlength attrubites. 
        - Text Area:
            - <textarea>: this element is used to createa multiline text input
        - Radio Button: 
            - <input>: type='radio' << radio buttons allow users to pick just one of a number of options.
        - Checkbox:
            - <input>type='checkbox' << allow users to select one more options to answer the question.
        - Drop downlist box:
            - <select> a drop down list box allows users to slsect one option from the list . 
        - Multiple select boxes:
            - <select>: you can turn a drop down select into a box that shows more than one option. 
        - File Input box
            <input> if you want to allow users to upload a file, type = 'file'.
        - Labeling form controls:
            - <label>: each form of code was kept by keeping the purpose next to it, but each one should have its own label.
        - Grouping form elements:
            - <fieldset> you can keep related form controls together inside the element.



# Chapter 14: Lists HTML 330/357
    - There are several css propties that where created to work with elents such as lists, tables and forms. 
    - Bulletpoint styles:
        - The list style property allows you to control the shape where is known as a marker
    - Images for bullets:
        - You can specify the image to act as a bullet point using the list syle image property.
        - The property can be used on the rules that apply for <ul> and <li>.
    - Positioning the marker:
        - Lists are indented into the page by default and the list style position property indicates where the marker should appear inside or outsde the box. 
            - There are two properties tha can take one of the values :
                1. Outside: where the marker sits to the lft of the block text.
                2. Inside where the marker sits inside the box of text. 
    - List shorthand:
        - There is a property that acts as a shorthand for list styles called list-style.
    - Table properties:
        - Width is to set the width of the table.
        - Padding is to set space between the border of each table.
        - text-transform to conver the content of the table headers to uppercase. 
        - letter spacing and font size add additional styling to the content of the table headers. 
        - border top and bottom set border above and below the table headers. 
        - Text align to align the wrwiting left,right center. 
        - Background color is to change the color of the background. 
        - Hover is to set a table row when using a mouse over. 
    - Cursor styles:
        - The cursor property allos you to control the type of mouse cursor that should be displayed to users. Here some commonly used values for this property: auto,crosshair,default,pointer,move,text,wait,help. 
# Chapter 6: Events  Java 243/292
    - When you browse your browser registers different types of events. Scripts often respond to these events by updating the content of the webpage. 
    - When the user interacts with the html on a webpage there three steps involoved which are known as event handling:
        1. Select the element node you want to script on.
        2. Indicate which even on the selected node will trigger the response. 
        3. State the code you want to run when the event occurs. 

    - There are three ways to bind an even to an element, event handlers let you indicate which event you are waiting for.  
        1. HTML even handlers.
        2. Traditional Dom Event handlers
        3. Dom level 2 event listerns. 

    - Event flow, html elements nest inside the other elements, if you hover over or click on the link you will also be hovering on its parent elements. 
    - The flow of events only really matter when you code has an event handlers on an element and one of its ancestor or descendant elements. 
    - When an event occurs the object tell you information about thevent. 
    - Event delegation, creating even listeners for a lot of elements can slow a page down, but event flow allows you to listen for an event. 
    - The event object has methods that can change the default behavoir of an element and how ethe elements ancestors respond to the event. 
    - UI (user interface) events occur as a result of interaction with the browser window rather than the HTML.
    - The load event is commonly used to trigger scripts that access the content of the page. The setup)() function would not work before the page has loaded because it relies on finding the element whose id attribute has a value of the username. 
    - Binding is the process of stating which even you are waiting to happen and which element you are waiting for theven to happen upon.

    