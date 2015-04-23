# xplatformhttprequests
Cross Platform HTTP request libraries - see readme and wiki for more details

This project aims to provide a collection of HTTP request libraries that offer (roughly) the same API across different languages and platforms. Think of it like the ActiveX or Component Object Model (COM) API from Microsoft and similar interfaces, where the module/library can be consumed by different languages but the API is nearly the same, save for some language specific deviations in syntax and data type interactions.

This project probably is useless to people who prefer using their language's native HTTP library's API, work with a specific or few languages, or don't mind learning the different APIs of each HTTP library for each language platform they work with.

But for those of us who like to have code reuse (across languages/platforms), or not have to remember different APIs for different languages for doing the same task (e.g. duplicating or porting code/functionality as an example), or are using a language that doesn't offer a nice wrapper for making HTTP requests (e.g. have to write boiler plate code or make your own wrapper library), then this might come in handy.

The intent is to offer a single API model for making HTTP requests that applies across the available languages for which an implementation is created for. See this project's wiki page(s), for details on the API model. I welcome contributions for additional languages/platforms that I've not implemented for as well as improvements, suggestions, and bug fixes for existing implementations.

This will be a work in progress project as I add more implementations, one by one.

Currently targeted languages for implementation include: Java, .NET/C#, PHP, Python, Perl, Ruby, Javascript (node.js, browser client side javascript, Microsoft JScript for WSH/ASP), Adobe ExtendScript, VBScript (for WSH, ASP, HTA apps)
