# Chapter 2: “Text” 
*how to add both (structural and semantic markup) to a web page*

## Structural markup;

* HEADINGS `<H1><h2><h3><h4><h5><H6>`:

the heading tags are used to create a heading in the web page `<h1>` is used for the main heading and `<h2>` untile `<h6>` are used for the subheadings. they will display on the web page in different sizes. 

* PARAGRAPHS `<P>`:
 
 we use the paragraph tag to surround the words in case we need to show a paragraph. for example, 
 `<p>the text goes here</p>`

 * BOLD AND ITALIC `<B>/<I>`:

 we use bold represented with the tag `<b>` to distigush some sections or words inside a text. for example,
  `<p>this word is<b>bold</b></p>`.

we use the italic to make a certain character appears italic. for example, `<p>this word is <i>italic</i></p>`.

* SUPERSCRIPT & SUbSCRIPT `<sup>,<sub>`:

 the superscript tag `<sup>` used to contain characters that need to be superscripted like dates and mathmatical concepts.

 the subscript tag `<sub>` used to contain characters that need to be subscripted like chemical farmulas.
  
  ![image](https://media.geeksforgeeks.org/wp-content/uploads/Screen-Shot-2017-11-07-at-1.31.16-PM.png)
  
  * WHITE SPACE:
in order to make our cose easier to read we can add spaces between the charcters and they will not appear in the web page. 

  * LINE BREAKS & HORIZONAL RULES `<br /> <hr />`:
  the tag `<br />` is used to add a new line break iside a paragraph. 

  the tag `<hr />` it is used a visual horizonal line between a two texts in one paragraph so seperate between two different themes. 

  ## semantic markup;

  * STRONG AND EMPHASIS `<strong>/<em>`;

we use the tag `<strong>` to indicate that a certain word or a certain character have strong importance.we use the tag `<em>` to indicate an emphasis in a certain word that subtly chandes the meaning of the word and the overall meaning of the text.

* QUOTATION `<blockquote> <q>`;

the block quote tag `<blockquote>` is used to site a quote that would take an entair paragraph. while the quote tag `<q>` is ued to site a short quote within a line of the paragraph and it can be used inside the block quote. 

* ABBRIVATIONS & ACRONYMS `<abbr>`;

this tag is used to create an abbrivation to specifiy a full term. 
![image](https://studyopedia.com/wp-content/uploads/2018/02/HTML-abbr-tag.jpg)

* citations & definitions `<cite> <dfn>`;
we use the tag `<cite>` for reference. if we want to make a reference to a piece of work like a research paper or a book or a film. while the `<dfn>` tag is used to explain some new terminology. 

* AUTHOR DETAILS `<adress>`;

the adress tag is used to present a phone number or email adress. 
 * ** 
 # Chapter 10: “Introducing CSS”:

 *understanding the CSS*

 * first of all, CSS treats each HTML element as it appears in a box. and the role of CSS is to create rules to manage each and every box inside the HTML by controlling its boarders, changing hight and width, adding a background color, chanding the font and color of the text.

 * the CSS rules that associate the style with the HTML elements contains two parts; *(selector, declaration)*. 

![image](https://miro.medium.com/max/3840/1*naFDyXh9iGtmvNRhhFY-og.png)

**1- The selector**: indicate which element from the HTML is choosen and applied too the CSS style.

**1- The declaration** : the declaration indicate how the selected element in the selector should be styled, and it consists of two parts *(a property and a value)*.

*the property*; indicate the aspects of the elements you want to change. such as, the color, the font.

*the value*; represent the specific sitting you want to be displayed like which color(red/blue,...ect), or which font (Arial,...ect).

* we can either use internal CSS style, where the developer styles the elements of HTML within the same page and this method is called an inline method, where the developer style each element in the same line. or we can write CSS in seperate sheet and link it to the HTML file. to do that the developer need to select the element he/she want to style by *(tag name/ID/ or class)*.

* ** 

# Chapter 2: “Basic JavaScript Instructions” :

*How to read and write JavaScript*

 * STATMENTS
 statments is a series step by step instructions we give the computer that should follow. many statments gouped togather is called a block ot code. 

 ![image](https://1.bp.blogspot.com/-nh6ZkX6q_Dk/Xfc0S5zftiI/AAAAAAAAE24/y2brpWATADoxtCdeKt7Fv7nKaxx9dvTeQCLcBGAsYHQ/s1600/Screenshot%2B%2528463%2529.png)

 * COMMENTS

 comments are very useful because they mark the start and end of block code which make it easier for the developer to read and follow and understand the code.

 ![image](https://s3.amazonaws.com/webucator-how-tos/1127.png)

 * VARIABLES 

  *To understand the concept of the variable imagine this senario. for example in a shoping website the products are displayed in a list and each product has its own price.when the store offer a discount the price would be updated in every page of the website where the product appears according to right caculation written inside the variables*.

```//list of products```

```"sneaker price: 40$"```

```//sneaker detail page```

```"sneaker price: 40$```

```//combi products```

```"sneaker price:40$ product-B price: 20$"```

 * we can use variables to store a *(a number, a string, booleans)*.  

**RULES FOR NAMEING A VARIABLE:**

1- The must start with a name or ($) or (_). NOT A NUMBER.

2- No keywords or reserved words.

3- Should not use same variable name with different cases.

4- The name should describes the type of information stored inside the variable.

5- Since the name of the variable should not contain any spaces, each word should start with capital letter. for example, *fistName*.

**DATA TYPES: ARRAY**

It is a type of variable the displayes the same kind of data. for example, a list of friends on Facebook. other programming languages have thier own dtatype for an ARRAY. however, in Javascript we mix different types of data inside the ARRAY.


![image](https://cdn-media-1.freecodecamp.org/images/w3CWlvnWqG5VEy6qupnAYvTqECGhPdj3P9Wu)


# **Logical Operatores:**

![image](https://www.examtray.com/sites/default/files/2019-06/java-boolean-logical-operators-priotiry-table.jpg)


*A logical operator help you understand the result value of two operants. for example,*

 *  **&& (logical and );** called Logical AND. if both the operands are non-zero the the condition become true.
 * **||(logical or);**  called Logical OR operator. if the any of the two operands are non-zero, then the condition become true. 
* **! (logical not);** called Logical NOT operator. used to revered the logical state of its operand. it the condition is true then logical NOT operator will marke false. 


* **
# Chapter 4: “Decisions and Loops

**Decision**

* decisions are ysed to detrmine which line of code should the computer run. and to do so we use *if coditional statments*. desisions are made of two parts:

1- an expression that retuns a value.

2- a conditional statement to tell what to do in a givem situation. 

![image](https://www.homeandlearn.co.uk/java/images/con_logic/if_elseIF_statement.gif)

**Operators and Loops**


![image](https://cdn.educba.com/academy/wp-content/uploads/2020/02/Nested-Loop-in-Java.jpg)

*Comparison operators evaluating conditions*

* ```==``` checkes if the value of the two values are equal or not. for example, ```(A==B)``` is not true.

* ```!=``` checkes if the one value is not equal to the other value. for example, ```(A!=B)``` is true.

* ```===``` check if the datatype in both ends and the valuse are the same and equal. for example, ```'A'==='A'``` is true.

* ```!==``` checkes if the datatypes at both ends and valuess are not the same. for example, ```'A'!== A``` is true.

* ```>``` checkes it a number is greater than the other. for example, ```2 > 1``` is true.

* ```<``` checkes if the a number is lesser than the other. for example, ```3<4``` is true.
* ```>=``` checks if the number is greater than or equal than the other. for example, ```4>=3``` or ```4>=4``` is true.
* ```<=``` checkes if one number is lesser than or equal to the other number, for example, ```4<=5``` or ```4<=4``` is true.
* **




**Types of loops**

![image](https://media.geeksforgeeks.org/wp-content/uploads/20191108131134/For-Loop.jpg)

![image](https://media.geeksforgeeks.org/wp-content/uploads/20191118164726/While-Loop-GeeksforGeeks.jpg)


* (the for loops); we use the for loop when we have to repeat a task a certain number of times. it consists of three parts (variable declaration and condition and statment) for exampel, ```for (variable;condition; change){statement}``` 

* ( the while loops); the while loop is used to repeat a specific block of code an unkown number of times, untile a codition is met.  ```while(boolean-expression){statments}```
* **
 
