# Authentication-and-authorization-for-SPAs



08/05/2019

ASP.NET Core 3.0 or later offers authentication in Single Page Apps (SPAs) using the support for API authorization. ASP.NET Core Identity for authenticating and storing users is combined with IdentityServer for implementing Open ID Connect.

An authentication parameter was added to the Angular and React project templates that is similar to the authentication parameter in the Web Application (Model-View-Controller) (MVC) and Web Application (Razor Pages) project templates. The allowed parameter values are None and Individual. The React.js and Redux project template doesn't support the authentication parameter at this time.
Create an app with API authorization support

User authentication and authorization can be used with both Angular and React SPAs. Open a command shell, and run the following command:

Angular:
>dotnet new angular -o <output_directory_name> -au Individual

React:
>dotnet new react -o <output_directory_name> -au Individual

The preceding command creates an ASP.NET Core app with a ClientApp directory containing the SPA.
