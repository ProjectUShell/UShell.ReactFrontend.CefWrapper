# About the 'Project UShell'

This is the idea of building a 'universal' shell in the form of an SPA that can host any web application. The current paradigm of configurable application modules (keyword 'composite application') in combination with the "WebComponents" standard enables us to create a product which is put together from several decentrally hosted components. In addition, an interaction between these modules should be made possible. In addition, it should also be possible to define various standard use cases, such as processing a list of data records in the form of simple CRUD operations, purely configuratively. In the latter case, no frontend development is necessary at all - only a web service in the Backend...



# About this Repo

The 'React Frontent CEF Wrapper' is a .NET Windows Application (.exe) which is using the OpenSource project 'CefSharp' to execute a seamless Chromium-Browser. Here we have a Offline-Version of our 'React Frontend' inside. This Project is just to demonstrate, that our shell can be deployed as windows appliaction without the need of an Internet connection (*if there are no external webapps embedded...)