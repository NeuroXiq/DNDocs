# DNDocs

![image](https://github.com/NeuroXiq/DNDocs/assets/19374897/4a4f0d7b-4903-4b92-b82b-db6073d9ece4)

![238906680-f8fbe700-3ef6-4110-b19d-ce9a07248e01](https://github.com/NeuroXiq/DNDocs/assets/19374897/929c263c-3737-48a1-a223-09426aedb579)

## DNDocs - Create API Explorer in one minute

1. Open dndocs.com and signin with Github account
2. Create a project with Nuget Package Name
3. Rebuild Project

Docfx API explorer is hosted online.

## Motivation
Looking on github C# repositories lots of them did  not have any documentation online. To take a look on basic project structure
and what methods are exposed I needed to open a code and open each .cs file just to simply look what functions and methods are there.
Also there was not any website that allows me to just simply generate and host documentation for my .NET Core project online.

Url to documentation can be shared in any form, for example:
1. Put dndocs API Explorer URL to github project README 
2. Generate shields.io badge with Project API Explorer, for example: [![Static Badge](https://img.shields.io/badge/API%20Docs-DNDocs-190088?logo=readme&logoColor=white)](https://dndocs.com/d/arctium/api/Arctium.Standards.Connection.Tls.Tls13.API.Tls13ClientConfig.html) _(look below in this document for 'shields.io badge informations' to see how to generate exactly same badge)_
3. Or anything other

If You have a small or medium size .NET Core project - try DNdocs!\
DNdocs can be used as a *default project documentation* or *temporary documentation* for projects that does not have  any documentation yet.\
Only thing  needed is nuget package name.

---

Adventages of using Robinia:
- Robinia generates [sitemap.xml](https://dndocs.com/api/other/sitemaps/sitemap.xml)
- Very easy configuration - only nuget package needed
- No need to maintain code for documents generation and publishing
- Automatic rebuild MD docs from github
- Automatic rebuild Nuget Pakcages to latests
- No actions needed after creating docs - all upgrades are autmated
- Supports multiple Docfx templates (darkfx, discordfx, docfx-minimal-main, material, unit)

# Create Documentation from Pull Request
To host API explorer without registering on dndocs, please create a new pull request.
1. Edit 'projects.md' file and add a new row in the  table
2. In  commit  message please add following informations:

```
Project Name: project_name
Robinia Url Prefix: url_prefix
Github Url: github_url
Description: description
Nuget Package Name: package_name (Install-Package 'package_name')
(if project does not have nuget package please add link to binary files like line below)
Dll Xml files: <url to .dll and .xml files)
```

For Example:

```
Project Name: Arctium Crypto Library
Robinia Url Prefix: arctium
Github Url: https://github.com/NeuroXiq/Arctium
Description: Arctium is a simple crypto library. It provides various cryptographic functions, ciphers, connection protocols
Nuget Package Name: Arctium.Shared
```

---
> shields.io badge informations:\
> Badge on shields.io can be generated with any parameters\
> but as an example above I generated badge with following parameters:\
> badgeContent: API Docs-DNDocs-190088\
> logo: readme\
> logoColor: white\
> Ready to copy-paste markdown badge (only replace 'WWWdndocsCOM/API_EXPLORER_LINK' with valid url):

```
[![Static Badge](https://img.shields.io/badge/API%20Docs-DNDocs-190088?logo=readme&logoColor=white)](WWWdndocsCOM/API_EXPLORER_LINK)
```

---
### Projects list:

|Name|Robinia Url|Github|
|-|-|-|
|Guard.Net|[dndocs - Guard.Net](https://www.dndocs.com/d/guardnet/api/index.html)| [Github](Guard.Net)|
|Algorithmia|[dndocs - Algorithmia](https://www.dndocs.com/d/algorithmi/api/index.html)| [Github](https://github.com/SolutionsDesign/Algorithmia)|
|Towel |[dndocs - Towel ](https://www.dndocs.com/d/towel/api/index.html)| [Github](https://github.com/ZacharyPatten/Towel)|
|Akade.IndexedSet|[dndocs - Akade.IndexedSet](https://www.dndocs.com/d/akadeinde/api/index.html)| [Github](https://github.com/akade/Akade.IndexedSet)|
|SliccDB|[dndocs - SliccDB](https://www.dndocs.com/d/sliccdb/api/index.html)| [Github](https://github.com/pmikstacki/SliccDB)|
|StringDB|[dndocs - StringDB](https://www.dndocs.com/d/stringdb/api/index.html)| [Github](https://github.com/SirJosh3917/StringDB)|
|Ninject|[dndocs - Ninject](https://www.dndocs.com/d/ninject/api/index.html)| [Github](https://github.com/ninject/ninject)|
|Spring.Core|[dndocs - Spring.Core](https://www.dndocs.com/d/springcor/api/index.html)| [Github](https://github.com/spring-projects/spring-net)|
|LightInject |[dndocs - LightInject ](https://www.dndocs.com/d/lightinjec/api/index.html)| [Github](https://github.com/seesharper/LightInject)|
|Stashbox |[dndocs - Stashbox ](https://www.dndocs.com/d/stashbox/api/index.html)| [Github](https://github.com/z4kn4fein/stashbox)|
|Markdig |[dndocs - Markdig ](https://www.dndocs.com/d/markdig/api/index.html)| [Github](https://github.com/xoofx/markdig)|
|PreMailer.Net|[dndocs - PreMailer.Net](https://www.dndocs.com/d/premailer/api/index.html)| [Github](https://github.com/milkshakesoftware/PreMailer.Net)|
|MimeKit |[dndocs - MimeKit ](https://www.dndocs.com/d/mimekit/api/index.html)| [Github](https://github.com/jstedfast/MimeKit)|
|StrongGrid |[dndocs - StrongGrid ](https://www.dndocs.com/d/stronggrid/api/index.html)| [Github](https://github.com/Jericho/StrongGrid)|
|Rationals|[dndocs - Rationals](https://www.dndocs.com/d/rationals/api/index.html)| [Github](https://github.com/tompazourek/Rationals)|
|Vim.Math3D |[dndocs - Vim.Math3D ](https://www.dndocs.com/d/vimmathd/api/index.html)| [Github](https://github.com/vimaec/math3d)|
|NAudio |[dndocs - NAudio ](https://www.dndocs.com/d/naudio/api/index.html)| [Github](https://github.com/naudio/NAudio)|
|TinyMapper |[dndocs - TinyMapper ](https://www.dndocs.com/d/tinymapper/api/index.html)| [Github](https://github.com/TinyMapper/TinyMapper)|
|AgileObjects.AgileMapper|[dndocs - AgileObjects.AgileMapper](https://www.dndocs.com/d/agileobjec/api/index.html)| [Github](https://github.com/agileobjects/AgileMapper)|
|DateTimeExtensions|[dndocs - DateTimeExtensions](https://www.dndocs.com/d/datetimeex/api/index.html)| [Github](https://github.com/joaomatossilva/DateTimeExtensions)|
|Exceptionless.DateTimeExtensions|[dndocs - Exceptionless.DateTimeExtensions](https://www.dndocs.com/d/exceptionl/api/index.html)| [Github](https://github.com/exceptionless/Exceptionless.DateTimeExtensions)|
|Tiny.RestClient|[dndocs - Tiny.RestClient](https://www.dndocs.com/d/tinyrestc/api/index.html)| [Github](https://github.com/jgiacomini/Tiny.RestClient)|
|Http.fs|[dndocs - Http.fs](https://www.dndocs.com/d/httpfs/api/index.html)| [Github](https://github.com/haf/Http.fs)|
|RestSharp |[dndocs - RestSharp ](https://www.dndocs.com/d/restsharp/api/index.html)| [Github](https://github.com/restsharp/RestSharp)|
|Refit |[dndocs - Refit ](https://www.dndocs.com/d/refit/api/index.html)| [Github](https://github.com/reactiveui/refit)|
|RestEase |[dndocs - RestEase ](https://www.dndocs.com/d/restease/api/index.html)| [Github](https://github.com/canton7/RestEase)|
|PhotoSauce.MagicScaler|[dndocs - PhotoSauce.MagicScaler](https://www.dndocs.com/d/photosauce/api/index.html)| [Github](https://github.com/saucecontrol/PhotoSauce)|
|Magick.NET|[dndocs - Magick.NET](https://www.dndocs.com/d/magicknet/api/index.html)| [Github](https://github.com/dlemstra/Magick.NET)|
|Colourful |[dndocs - Colourful ](https://www.dndocs.com/d/colourful/api/index.html)| [Github](https://github.com/tompazourek/Colourful)|
|SharpPcap |[dndocs - SharpPcap ](https://www.dndocs.com/d/sharppcap/api/index.html)| [Github](https://github.com/dotpcap/sharppcap)|
|Ceras |[dndocs - Ceras ](https://www.dndocs.com/d/ceras/api/index.html)| [Github](https://github.com/rikimaru0345/Ceras)|
|protobuf-net|[dndocs - protobuf-net](https://www.dndocs.com/d/protobufn/api/index.html)| [Github](https://github.com/protobuf-net/protobuf-net)|
|Stateless |[dndocs - Stateless ](https://www.dndocs.com/d/stateless/api/index.html)| [Github](https://github.com/dotnet-state-machine/stateless)|
|Downloader |[dndocs - Downloader ](https://www.dndocs.com/d/downloader/api/index.html)| [Github](https://github.com/bezzad/Downloader)|
|FluentSerializer.Json|[dndocs - FluentSerializer.Json](https://www.dndocs.com/d/fluentseri/api/index.html)| [Github](https://github.com/Marvin-Brouwer/FluentSerializer#readme)|
|ObjectDumper.NET|[dndocs - ObjectDumper.NET](https://www.dndocs.com/d/objectdump/api/index.html)| [Github](https://github.com/thomasgalliker/ObjectDumper)|
|FsPickler |[dndocs - FsPickler ](https://www.dndocs.com/d/fspickler/api/index.html)| [Github](https://github.com/mbraceproject/FsPickler)|
|FileHelpers |[dndocs - FileHelpers ](https://www.dndocs.com/d/filehelper/api/index.html)| [Github](https://www.nuget.org/packages/FileHelpers/)|
|dfghdfgh|[dndocs - dfghdfgh](https://www.dndocs.com/d/dfghdfgh/api/index.html)| [Github](dfgh)|
|Arctium - .NET Core crypto library|[dndocs - Arctium - .NET Core crypto library](https://www.dndocs.com/d/arctium/api/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|
|Arctium.Shared|[dndocs - Arctium.Shared](https://www.dndocs.com/d/arctium-shared/api/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|
|Arctium.Cryptography|[dndocs - Arctium.Cryptography](https://www.dndocs.com/d/arctium-cryptography/api/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|
|Arctium.Standards|[dndocs - Arctium.Standards](https://www.dndocs.com/d/arctium-standards/api/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|
