# AjaxMvcExample
An example on how to use Ajax.BeginForm() in ASP.NET MVC

Uses [Microsoft jQuery Unobtrusive Ajax](http://www.nuget.org/packages/Microsoft.jQuery.Unobtrusive.Ajax/).

### Where to look?
We're using the Ajax.BeginForm() inside the main view (`AjaxMvcExample/Views/Ajax/Index.cshtml`) that uses an AJAX request to GET a message from the `AjaxTest` action in the `AjaxMvcExample/Controllers/AjaxController.cs`. This is a simple action that takes a string and passes it as the model to its view (`AjaxMvcExample/Views/Ajax/AjaxTest.cshtml`) and returns it as a `PartialView`, which means without the default layout.
