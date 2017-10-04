#ISTA-322
##Lesson Plan-3
###Chetana Adhikari

1. What is a view?
The view proves the user interface (UI) to the user. After the controller has executed the appropriate logic for the requested URL, it delegates the display to the view. 

2.What is the similarity between view names and controller names? What is the difference between the two?
View names correspond to the method names in a controller. The root view for each controller is usually the index.cshtml. Controller base names are always 
combined with the word "Controller". 

3.Where in the directory structure of an ASP.NET MVC application do views live?
In the Views folder. 

4.What is a ViewBag object? What does it do?

5.What does the at symbol (@) do? Can you escape it? If so, how?
It is used to transition from markup to code and sometimes also to transition back. 
 
7.What is an ActionResult object? How do these objects interact with views?
An ActionResult object is an instance of the ActionResult class and have the information that the view converts into HTML to send to the browser.

8.What are strongly typed views?
The view which bind with any model is called as strogly typed view.

9.How does Razor combine HTML and C# code?
Razor allows you to insert C# code into HTML using the @ sign. 

10.Where do layouts live in the directory structure of an ASP.NET MVC application?
They lived in the Shared subfolder of the Views folder.

11. What are the differences between a partial view and a "full view?"
The partial view itself looks much like a normal view, except it doesn't specify a layout.