# Chapter 5 Images
    - There are many reasons one would put an image on their website. But there are serveral things you have to consider before selecting your images
        1. you need to include an image in your webpage using html.
        2. Need to pick which image format to use.
        3. Show an image the corrrect size.
        4. Optimize an image for the use on the web pages to make them load faster. 
    - If you are making a website from scartch it is good to create a folder for all the images, keeping them in sepearte folders could help you undertsand how the website is stored, which is called images. To add an image you use <img> tag and the src tells the broswer where to find the image, alt provides a description to the image.

    - When you add a new image to your website you will also need to specifiy the height and width of the images. When placing the links to the images you usually would put them before a paragraph or inside the paragraph or middle. 

    - You can use the aligh attribute to indicate how the other parts of a page should flow around the image. You can use left or right allowing text to flow around it. You can also allign text vertically by using the top, middle and bottom methods. 

# Chapter 11 Color
    - Colors can make your website very colorful and attractive for the readers or clients. 

### There are two types of colors 
    - Foreground color allows you to specify the color inside the text, you can specify using these three elements:
        1. RGB Values
        2. Hex Codes
        3. Color Names

    - Background color you can specifiy colors in the same three ways mentioned above.

## Understanding color
    - Every color on the computer is created by the RBG which is red blue green to create colors. 
            1.RBG Values which are values of red green and blue and are experssed as numbers.
            2. Hex Codes represent values of red green and blue. 
            3. Color names which is known from the title.
            4. Hue which is a colloquial idea of colors. 
            5. Saturation refers to the amount of gray in the color.
            6. Brightness refers to how much black is in the color. 
    
    - There are many way to check if the colors you are using are correct using simple tools such as contrast, opacity, HSL colors, HSL & HSLA. Using such tools would make your website more attractive for the user. 

# Chapter 12 Text
    - There are two groups of properties for text:
        1. Those that directly affect the font and appeareance.
        2. Those that would have the same effect on text no matter what font ur using.

    ## Typeface terminology
        - Serif fonts have extra details on the end of the main strokes of the letter.
        - Sans-serif fonds have straight ends to letters.
        - Monospace every letter of the font is the same width. 

        - There several ways to use font other than the ones listed on the page. But these are subject to copyright so the techniques are limited that you can choose from.
            1. Font family: the users computer needs the typeface installed, which is specified from CSS
            2. Font face: CSS specifies where a font can be downloaded from.
            3. Service based font face: commerical services give users access to a wider range of fonts

        - But if you are desgning on a mac it is important also to check what type of typefaces look like. 
        - The font family property allows you to specify the typeface that should be used for any text inside the elements.
        - There are ways to enable you to specify the font size and the most common are:
            - Pixels which are commonly used as the give us precise control.
            - Percentages 
            - EMS which equivalent to the width of a letter m.

        - @font face allows you to use a font even if it is not installed on the computer. by allowing you to specify a path to a copy of the font which will be downloadd if it is not he users machine.
        - The src will specify the path to the font.
    
    ## Understand font formats
        - Each browser supports a different format for fonts so you will need to give all the browsers several varations. 

        -  Bold font weight is a property that allows you to create bolt text. 
        - Italic font style where  it allows you to create italic text. 
        - The text decoration property allows you to specify the following values:
            1. None which removes any decor already applied to the text. 
            2. Underline that adds a line under the text.
            3. Overline that adds a line over the text.
            4. Line-through which adds lines though the text.
            5. Blink which animates the text to make it flash on and off.
        
        - Leading line-height is a term that typographers use for the vertical space between the lines of a text. THe bottom line is called a descender and the top of the like is called ascender.
        - Kerning is a term that typographers use for the space between each letter. 
        - Aligining is very beneficial for your website, you can align text middle, left, right and justify.
        