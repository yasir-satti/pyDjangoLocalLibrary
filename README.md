Local library app

Website that will be used to manage the catalog for a local library.

Content:

[2 - Create a skeleton website and application](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/skeleton_website)

  - [Creating the project](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/skeleton_website#creating_the_project)
  - [Creating the catalog application](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/skeleton_website#creating_the_catalog_application)
  - [Registering the catalog application](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/skeleton_website#registering_the_catalog_application)
  - [Specifying the database](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/skeleton_website#specifying_the_database)
  - [Other project settings](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/skeleton_website#other_project_settings)
  - [Hooking up the URL mapper](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/skeleton_website#hooking_up_the_url_mapper)
  - [Testing the website framework](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/skeleton_website#testing_the_website_framework)
  - [Running the website](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/skeleton_website#running_the_website)



[3 - Create models to represent your application's data](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models)

  - [Designing the LocalLibrary models](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models#designing_the_locallibrary_models)
  - [Model definition](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models#model_primer)
  - [Defining the LocalLibrary Models](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models#defining_the_locallibrary_models)
    - [Genre model](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models#genre_model)
    - [Book model](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models#book_model)
    - [BookInstance model](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models#bookinstance_model)
    - [Author model](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models#author_model)
  - [Re-run the database migrations](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models#re-run_the_database_migrations) 


[4 - Use the Django admin site to populate your site's data](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site)
  - [Registering models](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site#registering_models)
  - [Creating a superuser](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site#creating_a_superuser)
  - [Logging in and using the site](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site#logging_in_and_using_the_site)
  - [Advanced configuration](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site#advanced_configuration)
     - [Register a ModelAdmin class](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site#register_a_modeladmin_class)
     - [Configure list views](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site#configure_list_views)
     - [Add list filters](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site#add_list_filters)
     - [Organize detail view layout](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site#organize_detail_view_layout)
     


5 - [Create home page](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Home_page): Create views to retrieve specific data in response to different requests, and templates to render the data as HTML to be displayed in the browser.
  - [Defining the resource URLs](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Home_page#defining_the_resource_urls)
    - [Creating the index page](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Home_page#creating_the_index_page)
    - [URL mapping](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Home_page#url_mapping)
    - [View (function-based)](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Home_page#view_function-based)
    - [Template](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Home_page#template)

6 - [Generic list and detail views](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Generic_views): To understand where and how to use generic class-based views, and how to extract patterns from URLs and pass the information to views.
  - [Overview](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Generic_views#overview): Add to the website list and detail pages for books and authors.
  - [Book list page](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Generic_views#book_list_page):display a list of all the available book records in the page.
  - [Creating the List View template](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Generic_views#creating_the_list_view_template): Create the HTML file , the default template file expected by the generic class-based list view.
  - [Book detail page](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Generic_views#book_detail_page)
  - [Pagination](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Generic_views#pagination): add pagination to your list views, reducing the number of items displayed on each page.


7 - Add user authorization and sessions to control site behavior and access.
Work with forms.


8 - Write test code for your app.


9 - Use Django's security effectively.


10 - Deploy your application to production.