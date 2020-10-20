# TestSecuringBlazor
A recipe for securing your Blazor App

Securing a normal ASP.NET Core 3.1 web app is easy. You just AddAuthentication in your Startup.cs file, then add the [Authorize] attribute to whatever controller you want to secure. Everything is handled for you. Same with the AntiForgery token, just add an attribute. 

When you switch to a Blazor App, not so much. I created a blog post on how I managed to get it to work, and this is the code I used.
