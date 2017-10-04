#ISTA 320
##Lesson Plan 4
###Chetana Adhikari

1.What is scaffolding?
ASP.NET Scaffolding is a code generation framework for ASP.NET Web applications

2.What is a navigational property? What is a foreign key property?
A navigational property can be used to navigate to the object using the dot operator. A foreign key property is a property that allows an object to be referenced from multiple database tables.

3.What is a virtual property? Why does the book use virtual properties?
Virtual methods are used for Lazy Loading in Entities Framework.

4.Explain eagar loading. Explain lazy loading. What is the difference between the two?
Eager loading is the process whereby a query for one type of entity also loads related entities as part of the query. Eager loading is achieved by use of the Include method.
Lazy loading is a design pattern commonly used in computer programming to defer initialization of an object until the point at which it is needed.

5.What is meant by seeding a database? Explain.
Database seeding is the initial seeding of a database with data. This is often an automated process that is executed upon the initial setup of an application.

6.What is meant by the happy path? What is meant by the sad path? Give examples of each that are not in the book.
It is the code you execute when the model is in a valid state and you can save the object in the database. 

8.What is implicit model binding? Explain.
Model binding implicitly goes to work when there is an action parameter through which bind attribute can be used to restrict the binding behavior.

9. What is explicit model binding? Explain.
We can also explicitly invoke model binding using the UpdateModel and TryUpdateModel methods in controller.UpdateModel will throw an exception if something goes wrong during model binding and the model is invalid.TryUpdateModel also invokes model binding, but doesn't throw an exception. TryUpdateModel does return a bool - a value of true if model binding succeeded and the model is valid, and a value of false if something went wrong.

Source: http://www.itorian.com/2013/06/what-are-default-model-binding-and.html