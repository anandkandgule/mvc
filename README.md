
The ASP.NET MVC framework includes several action filters − OutputCache − Caches the output of a controller action for a specified amount of time.
HandleError − Handles errors raised when a controller action is executed. Authorize − Enables you to restrict access to a particular user or role.
Types of Filters The ASP.NET MVC framework supports four different types of filters − Authorization Filters − Implements
the IAuthorizationFilter attribute. Action Filters − Implements the IActionFilter attribute. Result Filters − Implements the IResultFilter attribute.
Exception Filters − Implements the IExceptionFilter attribute.
Filters are executed in the order listed above.
For example, authorization filters are always executed before action filters and exception filters are always executed after every other type of filter.

 A collection is a set of similar types of objects that are grouped together.
 System.Collections namespace contains specialized classes for storing and accessing the data. 
 Each collection class defined in .NET has a unique feature.
Types of collections:
Arrays: Array class is defined in System namespace. Arrays can store any type of data but only one type at a time.
The size of the array has to be specified at compilation time.
Insertion and deletion reduce performance.
Advanced Collections Many times we can’t give number elements in the list and we need to perform different operations like inserting, 
deleting, sorting, searching, comparing, and so on. To perform these operations efficiently, 
the data needs to be organized in a specific way. This gives rise to advanced collections. Advanced collections are found in System.Collections namespace. 

