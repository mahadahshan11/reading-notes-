# HTML Notes 

* **

# **HTML Chapter 1: Structure**

 *how HTML describes the structure of a web page*

 the srtucture of documents in webpages are very similar to the structure of documents in real life such as newspaper and insurance. however in HTML we add a code to the different texts and sections that we want to appear in the webpage. these codes have a meaning and are represented between angled brackets and are consisted of two elements, open and close tags.

 ![image](https://mason.gmu.edu/~kshiffl4/375/HTML_Tags.jpg)
 * **
  # **HTML Chapter 8: “Extra Markup”**
  * *specifying different versions of HTML:*
  
after the release of XML language, HTML4 was reformulated to follow the rules of XML.

1- every element need a closing tag. ```<p> </p>```

2- the attributes, which used in elements to give us more information about the element itself, consist of two parts *name*: has to be in a lowercase to while the *value* has to placed between double quotes, example ```<imag class="logo">...</img>```.

3- every element opened inside a bigger element should be closed inside that bigger elemnt as well. ```<section> <p></p> </section>```.



* *identifying and grouping elements*

**1- comments in HTML:**

when we have such a complicated and long code, it is useful to add comments to tell us the start and end of each section of our code. and it will not appear to the user. to add a comment 
```<!--comment goes here-->```

**2- ID Attributes:**

when ID attributes are added to the element it help to distigushed that certain element from the other elements in your code. the valuse should start with a letter or an underscore. for example ```<p id="content">text gose her</p>```.

using ID attributes is very useful becuase they help us to distinguish certain elements when styling using CSS or make the code interactive using JAVA.

**3-Class Attributes**

the class attribute help us specfiye one or more than one class name for a single element. for exmaple,

 ` 
     <title>
        <div class="hello" hello world></div>
        <div class="hello" hello world></div>
        <div class="hello" hello world></div>
        </title>`

and like the ID attributes, the class attributes used to point out the elements to style sheet using CSS or to give instructions using Java. 

**4-Block elements**

![image](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/06/Block-level-Inline-elements-in-html-df.jpg)
Examples for block elements; ```<h1>, <p>, <ul>, <il>```

Examples for inline block elements ```<a>, <b>, <em>, <img>```

**5-Grouping texts or elements in a block**

the HTML ```<div>...</div>``` allows us to group larg sections of HTML in a blok-level box. the `<div>` element is very often used together with CSS, to layout a web page. 

the HTML `<span>` tag allow us to group elements in an inline block box. when used in a text, it allows us to differeniate a certain item from the surrounding text. 

**6-Iframes**

![image](https://addons.cdn.mozilla.net/user-media/previews/full/203/203354.png?modified=1543521066)

iframe allows you to embed another document inside your current HTML page. and it has few attributes (src, hight width, scrolling, frameborder, seamless)

* **
# **HTML Chapter 17: "HTML5 layout"**
![image](https://mobile.htmlgoodies.com/imagesvr_ce/8525/html5_doc_sections.gif)


*the new HTML layout elements helps describe the structure of the page and also help developers to ignore the header and the footer and go stright to the content. 

1- The header and the footer `<header> <footer>`; the header contains the site name and the main `<nav>` bar while the footer contains copy rights information and links to social media websites. 

2- The navigation `<nav>`; used to represent a section that contain nevigation links either withing the current document or other document.

3- Articles `<article>`; represent an independent unite of content which means the information contained in the article can be distributed independently from the rest of the site or it appears in. 

4- section `<section>`; it is an element that used to group together ralated elements. 

* *The image below represent the difference between a section and an article in HTML*
![image](https://notesformsc.org/wp-content/uploads/2019/09/HTML5-Layout.png)

5- Asides `<aside>`; the aside element have two different purposes depending whether it was placed inside or outside of `<article>`. if it was placed inside an article then it contian information that related to article. however, if it was placed outside the article then it acts like a container that is related to the rest of the web page. 

5- Heading groups `<hgroup>`; the purpose of the `<hgroup>` is to gather a set of one or more `<h1>`and treated as one single heading. 
![image](https://www.newhorizonsmn.com/Portals/36/EasyDNNNews/157067/600600p224537EDNmain157067html-5-hgroup.jpg)

6- Figures `<figure>`; this element represent self-contained information that is not particularly essential to the article. it is used with images, video, graphs ect. Example;

 `<figure><img scr ................alt <figurecaption> fly high in the sky </figurecaption> </figure>`.  

![image](https://www.w3spoint.com/wp-content/uploads/2019/10/word-image-109.png)

* **

# **HTML Chapter 18: “Process & Design**

before any developer start building the his/her web site they need to understand who their target audience are and who will be visting thier page. information about the potential audience should be gathered first. like where they live, what is the level of thier education, what is thier marital statues is, whether they live in urban or rural areas and so on. after that the developer should ask him/her self why people would visit this website. and to answer this questio, there are two basic categories. 1- underlying the key motivation (whether the site will be for entertainment or to achieve a certain goal), 2- examins the specific goals. after examining the specific goals of the site, the developer need to identify the key information the visitors need. and then update the gathered information according to the visitors needs. 

**1-Site maps**

after you gather the necessary information about your site decided what information should appear on your web page. now you need to organized them and group them into a digram, this process called site map. 

![image](https://i.pinimg.com/originals/1c/c5/f4/1cc5f4ec000969f11eedf4dbe0f8c9d8.png)

**2-Wireframe**

it is a simple illustration of the key information the needed to appear in each page of the web site that showes the hierarchy of information. from the most important information to the least important one. 

![image](https://miro.medium.com/max/4096/1*57RPr8H0u9-S9j_TjgEGzA@2x.png) 


* **

# **JS Chapter 1: “The ABC of Programming”**


*A: what is a script and how do i create one?*

first of all the script is a series of instructions that we can give to a computer to achieve a certain goals and we can compare it to a recipe or a hand book.
in order to make the computer achieve that goal we need give it a specific detailed tasks descripting each step. 

1- define the goal; you need to identify the task that you want the computer to achieve.

2-design the script; this step includes breaking down the goal into a smaller instructions or tasks so that the computer would run them. for example; here a design for (while loop script), which is a sricpt used to get an input from the user and it will keep looping untile the correct input is received from the user.
![image](https://beginnersbook.com/wp-content/uploads/2017/09/while_loop_C.jpg)

3- code each step; after we designed the script we begin to write a code for every small task inside it. 


*B: How do computers fit in the world around them*


for computer every this is presented as an object and each object has its own **(properties, events and methods)**.

*properties*; is the characterstics of each object and each property has a **name** and a **valuse**.


*Events*; each object identified by the computer has its own functionality that coded by the programmers. for example, when a message pops put to the user welcoming him/her for visting the website. this is considered an event. 

*Methods*; is how the user would interact with website. it contains a lot of tasks that the computer have to achieve according to the user input. 

*C: How do I write a script for a web page?* 

to create a web page we use three programming languages (HTML, CSS Java). HTML represent the content of the web page and every information. so it acts like a skeltone of your web page. CSS, is the styling language and it represent how the content of the page would appear (the bachground color, the font,the dimensions). and Java, enable the user to interact with the web page and decide how the web page should behave.
  
to start wirting bacic javascrip code. first you should create a separate file in your visual code and link java file to your HTML code by creating a js extension `<script src="web.js">`. javaScript will not make any changes to HTML content. 
if you want to make a welcoming message the can pop out to the web page visitor you can use this code 

`alert('welcom to my page');` 

