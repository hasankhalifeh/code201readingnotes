# Domain Modeling
    - Domain modeling is the process of creating a conceptual model in code for a specfific problem.Object oreinted model is an entity that stores data in properties and encapsulates behaviors.

 # Chapter 6 Tables HTML 
    - There are several types of info that need to be displayed on a grid or table, when creating a grid or table you need to think how are they made up in rows and columns. A table represents information on a grid format.
    - Basic table structure:
           - <Table>element is used to create a table.
           - <tr> you indicate the start of each row using the opening.
           - <td> each cell of a table is represented.
    - Table headings:
        -<th> this element is used just like the <td>
    
    - Spanning colums:
        - Somtimes you need to stretch you would use the colspan attribute can be used on <th> or <td>.
    - Spanning rows:
        - Somtimes you need to streach down more than row you use use the rowspan attribute on the <th> or <td>.
    - Long tables, there are three elements that help distinguish between the main content of the table and the first and last rows. 
        -<Thead> the headings of the table should sit inside the thead.
        -<tbody> the body should sit inside the tbody element
        -<tfoot> the footer belongs inside the tfoot element.

### How memory and variables work

Each variable that is declared takes up memory. The more variables a browser has to remember, the more memory your script requires to run. Scripts that require a lot of memory can perform slower, which in turn makes your web page take longer to respond to the user.

Objects group together a set of variables and functions to create a model of something you would relate to with the real world.  In an object, variables and functions tak up new names. In an object:

- variables are known as properties (such as name, type of, number of and so on. )
- functions are known as methods (methods represent tasks that are associated with the object.)

### Creating an object (literal notation)

#### Literal Notation

Althought there are several ways to create opbjects, literal notation is the easiest and most common way.
var hotel = {
    name: 'FourSeason',
    rooms: 60,
    booked: 25,
    checkAvailability: function () {
        return this.rooms - this.booked;
    }
};
In this case, 'hotel' is the object, name, rooms and booked are properties and the last line is the method of what should be calculated (here the number of available rooms.)

#### Dot Notation

You can access the properties of an object by square brackets or like methods, by the dot notation.
var hotelName = hotel.name;
var roomsFree = hotel.checkAvailability();

#### Constructor Notation

You can first create a blank object, then add properties and methods to the object.
var hotel =  new Object();
*hotel.name = 'FourSeasons';*
*hotel.rooms = '60';*
*hotel.booked = '25';*
hotel.checkAvailability = function() {
    return this.room - this.booked;
};
In bold are the properties, and in italic is the method.

To update the value of properties, use dot notation or square brackets.
hote.name = 'Park';
To delete a property, use the *delete* keyword.
hotel['name'] = 'Park';

You can also create multiple objects, to represent similar things for example, by using a function as a template.
function Hotel (name, rooms, booked) {  
this.name = name;
this.rooms =rooms;
this.booked = booked;
this.checkAvailability = function() {
return this.rooms - this.booked;
};
}

### REFRESH/MEMORY Storing Data (Variables and Arrays)

In JavaScript, data is represented using name/value pairs.
To organize your data, you can use an array or object to group a set of related values. In arrays and objects the name is also known as a key.

So an object would go for
costs = {
    room1: 420,
    room2: 340,
    room3: 230,
}
But in an array, it would be like this
costs = [420, 340, 230];

Arrays in an object | Objects in an array
--------------------|---------------------
The property of any object can hold an array such as costs.room1.items[0]; | The value of any element in an array can be an object. costs[2].phone;

#### Built-in Objects

Browsers come with a set of built-in objects that represent things like the browser window and the current web page shown in that window. These built-in objects act like a toolkit for creating interactive web pages.



The Math object has properties and methods for mathematical constants and functions:

Property | Description
----------|-------------
Math.PI | Returns pi (to it's approximate)
Method | Description
-------|--------------
Math.round() | Rounds number to the nearest integer
Math.sqrt(n) | Returns square root of positive number,e.g.,Math.sqrt(9) returns 3
Math.ceil() | Rounds number up to the nearest integer
Math.floor() | Rounds number down to the nearest integer
Math.random() | Generates a random number between 0 (inclusive) and 1(not inclusive)

