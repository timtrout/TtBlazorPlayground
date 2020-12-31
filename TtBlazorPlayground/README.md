# Tim T's Blazor Playground
This a is dummy sample project to play around with various Blazor (Web Assembly) concepts 
and projects as wsell as to try out Github hosting and Azure hosting of 
the output.

## Learning Goals
* Blazor deployment strategies
* Github Pages hosting
* Azure Static Web Apps hosting
* Using Markdown for public documentation
* Continuous Integration and other automated deployment considerations (e.g. Github Actions)
* Usage and management of SSL/TLS certificates
* Security/authorization considerations
* Anything else that comes to mind

The first version fo this project will be Blazor WASM and not have an ASP.NET Core host so 
I can take advantage of static file deployment options on Github and Azure. Once I understand
those concepts better, I might consider adding a host and deploying to soemthing on Azure 
that supports running services (e.g. virtual machine, Azure funtions, etc.).  Whatever I do must
fit within free tier hsoting models and/or stay under monthly free credit allowances.

### Tutorial links:
* Github hosting: https://swimburger.net/blog/dotnet/how-to-deploy-aspnet-blazor-webassembly-to-github-pages
* Azure hosting: https://swimburger.net/blog/dotnet/how-to-deploy-aspnet-blazor-webassembly-to-azure-static-web-apps