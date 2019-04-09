**insert banner**

This post is part 2 of the series Intro to software development, click here if you will like to read the part 1


Web applications  are the software powering the websites we visits and the  backend for  most of the mobile applications we use.
When you visit a url eg facebook.com the  content the contents that get displayed , the friends suggestion etc are all powered by a web applications , same goes for all the websites we visit daily.
Therefore, Web application development is the development of apps that can be accessed via a url
(a web url is a web address assigned to a particular website, to make it accesible to other computers).In this post I will introduce the technologies and  languages used in building web applications and provide links to tutorials to get you started on your journey of becoming a web developer.

In the early days of the internet, web apps are buit using basic html and css.
**picture of old website**
.These days web apps have become very robust, handling lots of interaction with lots of featurers and capabilities like online payment, hotel booking, online exams and voting etc. Web apps have become the most popular kind of applications because its easy to access and platform or os independent.
**picture of new  website**

A lot of process goes into making a standard web applications from the planiing phase, to the design phase and the development phase. Web applications are split into 3 different categories :
1-web design,
2-front end (web) development 
3-backend (web) development

You  focus on working on one of these categories as a web designer, front end developer, backend developer.
Its good to have an understanding of the whole process though as it give you an advantage  and let you aware of what is possible or not when building large scale apps.

We will be going through these categories one after the other.


This  post  is structured into 
Intro To web design **add link**
 HTMl
 CSS
 Explain responsiveness
 Tutorial Links for Web design 

Intro to Design Framworks **add link**
 Tutorial links for Design Framworks

Intro to Frontend Development **add link**
 Javascript
 Tutorial for JS
FE framworks
 React explanation and tutorials link
 Angualar explanation and tutorials link
 Vue explanation and tutorials link

Into to Backend explanation **add link**
 Server explanation
 Database explanation
 HTTp request explanation



Web Design :

Web design deals with building and beutifying the content of the web pages  that gets displayed in the browser.It deals with the aesthetic of the web page.

Web page are built using HTML for structuring the blocks of content and CSS for placement and aesthetic. HTML and CSS are good entry points for anyone  looking to  get into web developmment as its easy to learn and building projects with it is fast once you understand how to use them both.

HTML:

Html (Hyper text markup language) is used to structure the webpage and add blocks of content like images, paragraph, video etc. These building blocks are called element. There are different element for different purpose, the <p>  element is used to insert a paragraph , <h1>is used to insert an header on the page, <img> is used to insert an image into the page. 
 Most of the element are made up of tags,  tags are  the code for starting an element and closing it. E.g To  insert a paragraph on a page, we add the <p> - opening tag, this tells the browser to start a paragh, we then insert the paragraph content  , then the closing tag</p>.
 **image shosing opening tag for <p> content and closing tag </p>. image should have arrow showing each section.

 This ensures the browser knows what content to display in an elemnt and where to stop.*

All html files have .html as thier extension



 Lets do a quick practical, so you can see how HTML is being used.
 Create a folder on your desktop called web_development, we will be creating all  projects file  in this folder.

**
If you have been following from part 1, we discuuseed about IDE, for developing apps
**show screen shot of part1 explainning what IDE is**
. We will be  downloading and using an  IDE now. head over to vscode.com, then download the version for you pc. When download get completed, click on the downloaded file to install it.

**

Open the newly installed VS Code app, by the top left side of the app page you will see open folder, click on this item, it will open a folder selector, navigate to your desktop and select the folder you just created "web_developemnt", the ide will open this folder and you can start working on the folder now.
**show screenshot of vscode open folder item**

**a small descriptuve image with arrow to point and  explain vscode views: navigation panel , editor.

 **if the welcome tab is opened close it.

 Under the 'web_deve..' folder click on the first plus button then enter index.html.This will create a file named index.html  in our folder. 
 We want to build this layout
 **insert image of intendend layout**(optional)
Copy the code below and paste into your opened editor, save the file by  pressing Ctrl and S on windows  or Command and S on mac.
Go back to the folder and double click on it, it will open in your default browser.
Congrats you have created your first web page Lets go through this code to understand how it works.



<!DOCTYPE html> 
 <html> is the parent element for all webpage.All html files must start with this.

The <head> tag is used to set information about the page and to set other data that are not meant for users.We will come back to this letter.

The <body> tag is where all of the content that get displayed on the webpage goes to. 

<h1> The h1 is used to insert an header on a page

<img> the img is used to insert an image
, the src attribute is used to tell the browser where to pick the image from, right here the image is fetched from a remote url, you can add an image to your folder and edit the source to refernce your local image.

<p> tag is used to insert a  paragraph into the page.

    *************

 The created page looks very basic and can be imporoved, we have used  HTML to structure the page, now we will be using CSS to style it and improve its aesthetic.


 CSS 
  Css (cascading style sheet) is used to style and desugn the web page.Its used in positioning element, styling the color and background color and overall page aesthetic.Both Html and  Css go hand in hand when designing a webpage.


Lets beutify our existing page using CSS, 
open the code editor, copy the code below and add it inside of the <head> tag.
**show with arrow, head tag and new style tag**
save and refresh the web page.
You should see a page with improved design, that looks more presentable


** Explain the styles and how it affects the page **

<!-->
As explained earlier to style a particular element we use an Id, 
and to style more than one element with the same rule we use a class or the elements tag.

This helps with ... so its easy to make changes to all attached element at once instead of applying it to them individually.

Styling methods:
 Inline : The style is added to the element directly. It added by addig a style attribute to the element and adding the style rules to it.

<style></style> tag, this placed at the header of the page, the elements are attached by id or class.
-->

This is a brief intro to show you how web pages are designed, the tutorial links below take you to tutorial that will guide you  through the full tutorial of building a professional web page.

Tutorials for Web design

 1 - Freecodecamp : They have an intercative page where you enter what you learn and test.Once you register you can start learning
(Highly recommende)

 2- W3c  html tutorial 

 3- Youtube Videos

Free Ebooks
 ... Add more



Design Frameworks : 
 Design framworks ....
 

 Examples of design framework are Bootstrap , Foundation , Material.

 Using design framworks doesnt mean you wont be writing css, it will only minimise the amount of code you write. 


Bootsrap is a styling framework that help you design web pages faster, it comes with lots of pre-styled classes ...
 
 
 Tutorials Links for Bootstrap:

- Youtube links

- W3c

- Bootstrap documentation



     ****************** *********





 
