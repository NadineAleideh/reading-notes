# Readings:  MVC Forms

1. **4 Ways to Make a Form in .NET MVC:**
   In the .NET MVC (Model-View-Controller) framework, forms are a fundamental element for collecting and processing user input. There are several approaches to creating forms in .NET MVC:

   a. **HTML Forms:** You can use standard HTML `<form>` elements in your MVC views to create basic forms. These forms can be submitted to controller actions for processing.

   b. **Razor Helpers:** Razor is a view engine that simplifies the process of generating HTML. It offers helpers like `Html.BeginForm()` and `Html.BeginFormRoute()` that streamline form creation, handling URLs and HTTP methods automatically.

   c. **Ajax Forms:** To create forms that update parts of a page without a full page refresh, you can utilize Ajax-based form submission. Libraries like jQuery can be used to capture form data and send it to the server asynchronously.

   d. **Model Binding:** MVC supports model binding, allowing you to create forms that directly map to your model classes. When a form is submitted, MVC can automatically bind the form fields to the corresponding properties of the model.

2. **View Models:**
   In ASP.NET MVC (and other MVC-like frameworks), view models are specialized classes designed to cater to the needs of a particular view. They act as intermediaries between the controller and the view, providing a structured way to transfer data and maintain separation of concerns.

   View models are particularly useful when the data required by a view doesn't align directly with the structure of the domain model or when a view requires data from multiple sources. By creating a view model, you can consolidate and shape the necessary data into a format that suits the view's rendering needs.

   View models help prevent issues like under-fetching or over-fetching of data, which can occur when a view either lacks required data or receives more data than necessary. They also enhance maintainability by isolating the view-specific logic from the controller and the domain model, promoting cleaner and more focused code.

## Things I want to know more about

nothing for now.
