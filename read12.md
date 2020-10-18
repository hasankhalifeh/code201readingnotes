# Animated charts

You can get the latest verision of CHart.js which uses HTML5's cancvase element to draw the graph onto the page.

## Setting up

After you download chart.js you can copy the chart.min.ks out of the unzipped folder into the directory. Then you can create an HTML page and import this script.
![charts](img/chart:html.png)

## Drawing a line chart

To draw  line chart the first thing we need to do is create an HTML inyou would use the follow:

 - < canvas id="buyers" width="600" height="400">< /canvas >
Then we need to write a script that will retrieve the contect of the canvas;

    < script >
    - var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
    < /script >

    Inside the same script tags we need to create the data, in this its an object that has labels for the base of you chat and datasets to describe the values.

## Drawing a pie chart

< canvas id="countries" width="600" height="400">< /canvas >
var countries= document.getElementById("countries").getContext("2d");
new Chart(countries).Pie(pieData, pieOptions);

## Drawing a bar chart

If you want to add a bar chart to our page you would use the following par chart:

    < canvas id="income" width="600" height="400" >< /canvas >
    var income = document.getElementById("income").getContext("2d");
    new Chart(income).Bar(barData);
    var barData = {
    labels : ["January","February","March","April","May","June"],
    datasets : [
    {
    fillColor : "#48A497",
    strokeColor : "#48A4D1",
    data : [456,479,324,569,702,600]
    },
    {
    fillColor : "rgba(73,188,170,0.4)",
    strokeColor : "rgba(72,174,209,0.4)",
    data : [364,504,605,400,345,320]
            }
    ]   
    }

### Applying styles & colors

fillStyle and strokeStyle are two important proerties to use in order to apply colors to shapes.

fillStyle = color (Sets the style used when filling shapes.)
strokeStyle = color (Sets the style for shapes' outlines.)

# Canvas Element

    - A first he <canvas> looks like and img element, with the only different is that it dosent hav ethe src and alt attributes. The canvas element has only two attributes the width and the height.
    - The Id attribute isnt specific to the canvas element but is a Global html attribute which is put in the HTML element. The canvas element can be styled with margin, border,background and can be styled like any other image.

### FallBack Content
    - The canvas element differs from an img tag its like the <video>,<audio>or <picture>. 
    - Providing fallback conent is very straightforward, you have to insert the alternate content 

## Rendering Context
    - The canvas elements create a fixed size drawing and exposes one or more rendering contexts. 
    - The canvas is initially blank, to display somthing a script first needs to access the rendering context and draw on it. 
    - The canvas element has a method called getContext. 

## The Grid
    - Before drawing you have to talk about canvas grid or coordinate space. 

## Drawing rectangles
    - The canvas only supports two primative shapes rectanges and paths. All other shapes must be created by using on or more paths. 
    - Here are three fuctions that draw rectangles: 
        -  fillRect(x, y, width, height)
            Draws a filled rectangle.
        -strokeRect(x, y, width, height)
          Draws a rectangular outline.
         - clearRect(x, y, width, height)
            Clears the specified rectangular area, making it fully transparent. 

## Drawing Paths:
    - A path is a list of points connected by segements of lines that can be different shapes. To make shapes using paths we use these extra stepS:
        1.First, you create the path.
        2.Then you use drawing commands to draw into the path.
        3.Once the path has been created, you can stroke or fill the path to render it.

# Apply styles and colors:

    -There are many ways to add color, If we want to use colors to a shape there are two properties we can use fillstyle and strokestyle. 
    - Color is a string representing a css color a gradient object or a pattern object.

### Transparency:
    In addition to drawing shapes to the canvas we can also draw semi transpert shapes. This is done by setting globalAlpha property or by assiging a transperant color. 

    - Gradients: we can fill stroke shapes using linear and radial graidents. We can assign the object to the fillyStyle or strokeStyle. 

### Patterns:
    - We can use a series of loops to create a pattern of images there is a much simpler method the createPattern() is the method.


# Drawing Text:
    - The canvas rendering context provides to different methods: 
        1. fillText(text, x, y [, maxWidth])
        2. strokeText(text, x, y [, maxWidth])
