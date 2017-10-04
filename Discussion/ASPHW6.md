#ISTA-322
##Lesson-Plan 6
###Chetana Adhikari

1. Why do we want to validate user input on the client? Why do we want to validate user input on the server?
To give the user the opportunity to validate their input.
It is impotant to verify the user input through the server side validation.

2. In ASP.NET MVC, what data items are the focus of validation?
Model values are the focus of validation.

3. Where do data annotations live in the .NET framework?
The annotations live in System.ComponentModel.DataAnnotations in the .NET framework.

4. Can you stack multiple validation attributes with regard to actions? If so, how many can you stack?
Yes, and with no regard to actions.

5.Explain the syntax [remote] what does it do?


6. What is a server callback?
he client (typically a web service control) invokes requestMessage to initiate the web service's main process. When the main process is complete (that is, when the response is constructed) the onMessage callback method is invoked that sends the response back to the client.


7. What is a model builder and when does it run?
It takes the request parameters and puts it in the model. 


8. What is the model state? When is it created? How is it created? What does it contain?
ModelState is a property of a Controller, and can be accessed from those classes that inherit from System.Web.Mvc.Controller. The ModelState represents a collection of name and value pairs that were submitted to the server during a POST

9. What does the controller action method generally do if the model state is not valid?


10. What are the two options for custom validation? Explain your answer.
i) Packaging validation logic into a custom data annotation.
ii) Packaging validation logic into a model object itself.
