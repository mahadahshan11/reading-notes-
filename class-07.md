# Domain Modeling

when a coder have many objects with the same properties and behaviour in his/her code repeated throghout the entire code having a model domain can help us to in understanding the given problem and communicate it better to other coders and developers. 

to create a domain model first, we have to define a constructor function using a function expression and give it its properties. when the values are assingned and stored inside the function, the objects then are stored inside the variables for late use. in this way when can easly acess any object from the ouside and make changes. and if we want to access the object's propreties from the inside of the object, we use `this` variable within the method. 


* **
# HTML book, Chapter 6: “Tables”:

**what is the table?**
it is a way of presenting information in a format consists of raws and colums.

**Basic Table Structure**

1) `<table>` : the element is used to creat a table in HTML and written raw by raw. 

2) `<tr>` : it indicate the start of each row using th opening `<tr>`. 

3) `<td>` : it represent each cell in the table. 

4) `<th>` : it represent the header of each colum. even if the cell is empty, the coder should use `<td>` or `<th>` to repressent that empty cell. 

**Spanning Columns**

 we use spannig colums when we want to stretch the entiries of the table across more than one colume. and we can use it for `<th> ` and `<td>` tags. 

 **Spanning Rows** 

 we use spanning row if we want to streach down across more than one row. we use it also with `<td>` and `<th>` elemrnts to indicate how many rows a cell should span down the table. 
 
 **Long Table**

  1) `<thead>` : a tag that represent the headings of the table. 

  2) `<tbody>` : a tag that represent the body of the table.

  3) `<tfoot>` : a tag that represent the footer. 

  * ** 

  # Js book, Chapter 3: “Functions, Methods, and Objects”

  **Creating an object: Constructor notation**: 

  to create an object constructor we must use the keyword `new` to add properties and methods to an object.
   

 **Updating an object**

To update an object we must update the value and properties inside the object. and to do so we use dot notation or square brackets  and give it a new value. and if the object dose not have the property you are trying to update, then you should add it to the object. you can also update the object without its method by using this method. 

`car ['color'] = 'red';` 

**Creating many objects: constructor notation**:

when we have many objects that represent similar things, the constuctor notation can use a function as a tamples or blue print for creating all the similar objects.  

![image](https://miro.medium.com/max/1764/1*f2GY7oXEjoGVD8fHOl5Ayg.png) 

if we want to creat several profiles to resucued animals in a rescue animal facility. and assigne each animal with image, and a name, and a age. we can use constructor function to avoid repeating each obeject with its method.

`let animal = new cat ('frankie' , '7', 'image');` 
 

 **Arrays are objects**
 Arrays are a type of object holding a related set of key/valuse in its index number. arrays have alot of helpful mehtods because arrays have a length property that telling how many items in the array.

 Arrays are very helpful beacuse they can store a series of objects. even the objects stored in the arrays also hold arrays. this is a form of complex data structure. 

