# Webgrid example in ASP.NET MVC

This blog shows how to use Webgrid in ASP.NET MVC. It displays model data in WebGrid in PartialView on selection change of Listbox value.

For this tutorial you will create a view with ListBox. Listbox will have a list of categories from Northwind database. On selection of category, products under selected category will be shown in Webgrid. It loads partialview using jQuery to display Webgrid.


## Files

1. **[HTML View](https://github.com/geeksarray/webgrid-example-in-asp-net-mvc/blob/master/MvcWebGridExample/Views/Home/ShowProducts.cshtml)** - with WebGrid HTML and jQuery functions.

1. **[Home Controller](https://github.com/geeksarray/webgrid-example-in-asp-net-mvc/blob/master/MvcWebGridExample/Controllers/HomeController.cs)** - with action method to return 
   product list from database.
   
After you implement code from this repo, you will see the WebGrid rendered like

![ASP.NET MVC WebGrid](https://geeksarray.com/images/blog/asp-net-mvc-web-grid-example.png)

For more details visit - [ASP.NET MVC](https://geeksarray.com/blog/webgrid-example-in-asp-net-mvc)
 

