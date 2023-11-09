# Welcome on DNDocs!
## Free online documentation hosting platform for .NET projects

![image](https://github.com/NeuroXiq/DNDocs/assets/19374897/4a4f0d7b-4903-4b92-b82b-db6073d9ece4)

## Problem: Host .NET API Documentation 
There is not effortless way to create and host API documentation for .NET Core projects.
Current tools requires to integrate with build and publishing process to maintain docs up-to-date

## Solution: DNDocs

1. Open https://dndocs.com and signin with Github account
2. Create a project with Nuget Package Name
3. Click save button

Docfx API explorer is hosted online.

## When I should use DNDocs
You don't have any API Explorer for Your .NET project: * use https://dndocs.com *

## Motivation
Looking on github C# repositories lots of them did  not have any documentation online. To take a look on basic project structure
and what methods are exposed we needed to open open each .cs file just to simply look what functions and methods are there.
Also there was not any website that allows to just simply generate and host documentation for .NET Core project online.

## Share with URL
Url to documentation can be shared in any form, for example:
1. Put dndocs API Explorer URL to github project README 
2. Generate shields.io badge with Project API Explorer, for example: [![Static Badge](https://img.shields.io/badge/API%20Docs-DNDocs-190088?logo=readme&logoColor=white)](https://dndocs.com/d/arctium/api/Arctium.Standards.Connection.Tls.Tls13.API.Tls13ClientConfig.html) _(look below in this document for 'shields.io badge informations' to see how to generate exactly same badge)_
3. Or anything other

If You have a small or medium size .NET Core project - try DNdocs!\
DNdocs can be used as a *default project documentation* or *temporary documentation* for projects that does not have  any documentation yet.\
Only thing  needed is nuget package name.

---

Adventages of using DNDocs:
- DNDocs generates [sitemap.xml](https://dndocs.com/api/other/sitemaps/sitemap.xml)
- Very easy configuration - only nuget package needed
- No need to maintain code for documents generation and publishing
- Automatic rebuild MD docs from github
- Automatic rebuild Nuget Pakcages to latests
- No actions needed after creating docs - all upgrades are autmated
- Supports multiple Docfx templates (darkfx, discordfx, docfx-minimal-main, material, unit)
- Basic Versioning support

# Create Documentation from Pull Request
To host API explorer without registering on dndocs, please create a new pull request.
1. Edit 'projects.md' file and add a new row in the  table
2. In  commit  message please add following informations:

```
Project Name: project_name
DNDocs Url Prefix: url_prefix
Github Url: github_url
Description: description
Nuget Package Name: package_name (Install-Package 'package_name')
(if project does not have nuget package please add link to binary files like line below)
Dll Xml files: <url to .dll and .xml files)
```

For Example:

```
Project Name: Arctium Crypto Library
DNDocs Url Prefix: arctium
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
|GoogleSheetsWrapper|[DNDocs - GoogleSheetsWrapper](https://dndocs.com/d/googlesheetswrapper/api/index.html) | [Github](https://github.com/SteveWinward/GoogleSheetsWrapper) |
|RiotBlossom|[DNDocs - RiotBlossom](https://dndocs.com/d/riotblossom/api/index.html) | [Github](https://github.com/BlossomiShymae/RiotBlossom) |
|AAXClean|[DNDocs - AAXClean](https://dndocs.com/d/aaxclean/api/index.html) | [Github](https://github.com/Mbucari/AAXClean) |
|ZeroQL|[DNDocs - ZeroQL](https://dndocs.com/d/zeroql/api/index.html) | [Github](https://github.com/byme8/ZeroQL) |
|AsyncFlow|[DNDocs - AsyncFlow](https://dndocs.com/d/asyncflow/api/index.html) | [Github](https://github.com/TheFo2sh/AsyncFlow) |
|SQLite-DNA|[DNDocs - SQLite-DNA](https://dndocs.com/d/sqlite-dna/api/index.html) | [Github](https://github.com/SQLite-DNA/SqliteDna) |
|ArrayExtensions|[DNDocs - ArrayExtensions](https://dndocs.com/d/arrayextensions/api/index.html) | [Github](https://github.com/Tim-Maes/ArrayExtensions) |
|RepetierSharp|[DNDocs - RepetierSharp](https://dndocs.com/d/repetiersharp/api/index.html) | [Github](https://github.com/Z0rdak/RepetierSharp) |
|Mapster|[DNDocs - Mapster](https://dndocs.com/d/mapster/api/index.html) | [Github](https://github.com/MapsterMapper/Mapster) |
|EventFlow|[DNDocs - EventFlow](https://dndocs.com/d/eventflow/api/index.html) | [Github](https://github.com/eventflow/EventFlow) |
|Respawn|[DNDocs - Respawn](https://dndocs.com/d/respawn/api/index.html) | [Github](https://github.com/jbogard/Respawn) |
|Betalgo.OpenAI|[DNDocs - Betalgo.OpenAI](https://dndocs.com/d/betalgo-openai/api/index.html) | [Github](https://github.com/betalgo/openai) |
|NSubstitute|[DNDocs - NSubstitute](https://dndocs.com/d/nsubstitute/api/index.html) | [Github](https://github.com/nsubstitute/NSubstitute) |
|ZXing.Net|[DNDocs - ZXing.Net](https://dndocs.com/d/zxing-net/api/index.html) | [Github](https://github.com/micjahn/ZXing.Net) |
|Marten|[DNDocs - Marten](https://dndocs.com/d/marten/api/index.html) | [Github](https://github.com/JasperFx/marten) |
|Octokit|[DNDocs - Octokit](https://dndocs.com/d/octokit/api/index.html) | [Github](https://github.com/octokit/octokit.net) |
|FluentScheduler|[DNDocs - FluentScheduler](https://dndocs.com/d/fluentscheduler/api/index.html) | [Github](https://github.com/fluentscheduler/FluentScheduler) |
|EasyNetQ|[DNDocs - EasyNetQ](https://dndocs.com/d/easynetq/api/index.html) | [Github](https://github.com/EasyNetQ/EasyNetQ) |
|MiniProfiler|[DNDocs - MiniProfiler](https://dndocs.com/d/miniprofiler/api/index.html) | [Github](https://github.com/MiniProfiler/dotnet) |
|TMDbLib |[DNDocs - TMDbLib ](https://dndocs.com/d/tmdblib/api/index.html) | [Github](https://github.com/jellyfin/TMDbLib) |
|PdfSharpCore|[DNDocs - PdfSharpCore](https://dndocs.com/d/pdfsharpcore/api/index.html) | [Github](https://github.com/ststeiger/PdfSharpCore) |
|MediaToolkit|[DNDocs - MediaToolkit](https://dndocs.com/d/mediatoolkit/api/index.html) | [Github](https://github.com/AydinAdn/MediaToolkit) |
|DistributedLock|[DNDocs - DistributedLock](https://dndocs.com/d/distributedlock/api/index.html) | [Github](https://github.com/madelson/DistributedLock) |
|Websocket.Client|[DNDocs - Websocket.Client](https://dndocs.com/d/websocket-client/api/index.html) | [Github](https://github.com/Marfusios/websocket-client) |
|DotNetCorePlugins|[DNDocs - DotNetCorePlugins](https://dndocs.com/d/dotnetcoreplugins/api/index.html) | [Github](https://github.com/natemcmaster/DotNetCorePlugins) |
|NBitcoin|[DNDocs - NBitcoin](https://dndocs.com/d/nbitcoin/api/index.html) | [Github](https://github.com/MetacoSA/NBitcoin) |
|EasyHttp|[DNDocs - EasyHttp](https://dndocs.com/d/easyhttp/api/index.html) | [Github](https://github.com/EasyHttp/EasyHttp) |
|Arctium|[DNDocs - Arctium](https://dndocs.com/d/arctium/api/index.html) | [Github](https://github.com/NeuroXiq/Arctium) |
|CacheCow.Client|[DNDocs - CacheCow.Client](https://dndocs.com/d/cachecow-client/api/index.html) | [Github](https://github.com/aliostad/CacheCow) |
|XunitXml.TestLogger|[DNDocs - XunitXml.TestLogger](https://dndocs.com/d/xunitxml-testlogger/api/index.html) | [Github](https://github.com/spekt/xunit.testlogger) |
|Dapper.FastCrud|[DNDocs - Dapper.FastCrud](https://dndocs.com/d/dapper-fastcrud/api/index.html) | [Github](https://github.com/MoonStorm/FastCrud) |
|YoutubeExplode|[DNDocs - YoutubeExplode](https://dndocs.com/d/youtubeexplode/api/index.html) | [Github](https://github.com/Tyrrrz/YoutubeExplode) |
|Foundatio|[DNDocs - Foundatio](https://dndocs.com/d/foundatio/api/index.html) | [Github](https://github.com/FoundatioFx/Foundatio) |
|DynamicExpresso|[DNDocs - DynamicExpresso](https://dndocs.com/d/dynamicexpresso/api/index.html) | [Github](https://github.com/dynamicexpresso/DynamicExpresso) |
|CdekSdk|[DNDocs - CdekSdk](https://dndocs.com/d/cdeksdk/api/index.html) | [Github](https://github.com/restub/CdekSdk) |
|restub|[DNDocs - restub](https://dndocs.com/d/restub/api/index.html) | [Github](https://github.com/restub/) |
|FFMpegCore|[DNDocs - FFMpegCore](https://dndocs.com/d/ffmpegcore/api/index.html) | [Github](https://github.com/rosenbjerg/FFMpegCore) |
|SpotifyAPI-NET|[DNDocs - SpotifyAPI-NET](https://dndocs.com/d/spotifyapi-net/api/index.html) | [Github](https://github.com/JohnnyCrazy/SpotifyAPI-NET) |
|MemoryPack|[DNDocs - MemoryPack](https://dndocs.com/d/memorypack/api/index.html) | [Github](https://github.com/Cysharp/MemoryPack) |
|sharpcompress|[DNDocs - sharpcompress](https://dndocs.com/d/sharpcompress/api/index.html) | [Github](https://github.com/adamhathcock/sharpcompress) |
|Sprache|[DNDocs - Sprache](https://dndocs.com/d/sprache/api/index.html) | [Github](https://github.com/sprache/Sprache) |
|ComputeSharp|[DNDocs - ComputeSharp](https://dndocs.com/d/computesharp/api/index.html) | [Github](https://github.com/Sergio0694/ComputeSharp) |
|FluentFTP|[DNDocs - FluentFTP](https://dndocs.com/d/fluentftp/api/index.html) | [Github](https://github.com/robinrodricks/FluentFTP) |
|netmq|[DNDocs - netmq](https://dndocs.com/d/netmq/api/index.html) | [Github](https://github.com/zeromq/netmq) |
|querybuilder|[DNDocs - querybuilder](https://dndocs.com/d/querybuilder/api/index.html) | [Github](https://github.com/sqlkata/querybuilder) |
|MiniExcel|[DNDocs - MiniExcel](https://dndocs.com/d/miniexcel/api/index.html) | [Github](https://github.com/mini-software/MiniExcel) |
|Cocona|[DNDocs - Cocona](https://dndocs.com/d/cocona/api/index.html) | [Github](https://github.com/mayuki/Cocona) |
|Throw|[DNDocs - Throw](https://dndocs.com/d/throw/api/index.html) | [Github](https://github.com/amantinband/throw) |
|Fluxor|[DNDocs - Fluxor](https://dndocs.com/d/fluxor/api/index.html) | [Github](https://github.com/mrpmorris/Fluxor) |
|ZiggyCreatures.FusionCache|[DNDocs - ZiggyCreatures.FusionCache](https://dndocs.com/d/ziggycreatures-fusioncache/api/index.html) | [Github](https://github.com/ZiggyCreatures/FusionCache) |
|IPNetwork|[DNDocs - IPNetwork](https://dndocs.com/d/ipnetwork/api/index.html) | [Github](https://github.com/lduchosal/ipnetwork) |
|OpenAI|[DNDocs - OpenAI](https://dndocs.com/d/openai/api/index.html) | [Github](https://github.com/OkGoDoIt/OpenAI-API-dotnet) |
|NetDevPack.Security.Jwt|[DNDocs - NetDevPack.Security.Jwt](https://dndocs.com/d/netdevpack-security-jwt/api/index.html) | [Github](https://github.com/NetDevPack/Security.Jwt) |
|MagickNET|[DNDocs - MagickNET](https://dndocs.com/d/magicknet/api/index.html) | [Github](https://github.com/dlemstra/Magick.NET) |
|MediatR.Behaviors.Authorization|[DNDocs - MediatR.Behaviors.Authorization](https://dndocs.com/d/mediatr-behaviors-authorization/api/index.html) | [Github](https://github.com/AustinDavies/MediatR.Behaviors.Authorization) |
|Indice.AspNet|[DNDocs - Indice.AspNet](https://dndocs.com/d/indice-aspnet/api/index.html) | [Github](https://github.com/indice-co/Indice.AspNet) |
|JsonMasking|[DNDocs - JsonMasking](https://dndocs.com/d/jsonmasking/api/index.html) | [Github](https://github.com/ThiagoBarradas/jsonmasking) |
|DropNet|[DNDocs - DropNet](https://dndocs.com/d/dropnet/api/index.html) | [Github](https://github.com/DropNet/DropNet) |
|Typin|[DNDocs - Typin](https://dndocs.com/d/typin/api/index.html) | [Github](https://github.com/adambajguz/Typin) |
|WTelegramClient|[DNDocs - WTelegramClient](https://dndocs.com/d/wtelegramclient/api/index.html) | [Github](https://github.com/wiz0u/WTelegramClient) |
|SmtpServer|[DNDocs - SmtpServer](https://dndocs.com/d/smtpserver-/api/index.html) | [Github](https://github.com/cosullivan/SmtpServer) |
|CodingSeb.ExpressionEvaluator|[DNDocs - CodingSeb.ExpressionEvaluator](https://dndocs.com/d/codingseb-expressionevaluator/api/index.html) | [Github](https://github.com/codingseb/ExpressionEvaluator) |
|Mixbox|[DNDocs - Mixbox](https://dndocs.com/d/mixbox/api/index.html) | [Github](https://github.com/scrtwpns/mixbox) |
|RobiniaDocs|[DNDocs - RobiniaDocs](https://dndocs.com/d/robiniadocs/api/index.html) | [Github](https://github.com/NeuroXiq/RobiniaDocs) |
|Arctium.Standards|[DNDocs - Arctium.Standards](https://dndocs.com/d/arctium-standards/api/index.html) | [Github](https://github.com/NeuroXiq/Arctium) |
|Arctium.Cryptography|[DNDocs - Arctium.Cryptography](https://dndocs.com/d/arctium-cryptography/api/index.html) | [Github](https://github.com/NeuroXiq/Arctium) |
|Arctium.Shared|[DNDocs - Arctium.Shared](https://dndocs.com/d/arctium-shared/api/index.html) | [Github](https://github.com/NeuroXiq/Arctium) |
|FileHelpers |[DNDocs - FileHelpers ](https://dndocs.com/d/filehelper/api/index.html) | [Github](https://www.nuget.org/packages/FileHelpers/) |
|FsPickler |[DNDocs - FsPickler ](https://dndocs.com/d/fspickler/api/index.html) | [Github](https://github.com/mbraceproject/FsPickler) |
|ObjectDumper.NET|[DNDocs - ObjectDumper.NET](https://dndocs.com/d/objectdump/api/index.html) | [Github](https://github.com/thomasgalliker/ObjectDumper) |
|LiquidState |[DNDocs - LiquidState ](https://dndocs.com/d/liquidstat/api/index.html) | [Github](https://github.com/prasannavl/LiquidState) |
|Stateless |[DNDocs - Stateless ](https://dndocs.com/d/stateless/api/index.html) | [Github](https://github.com/dotnet-state-machine/stateless) |
|protobuf-net|[DNDocs - protobuf-net](https://dndocs.com/d/protobufn/api/index.html) | [Github](https://github.com/protobuf-net/protobuf-net) |
|Ceras |[DNDocs - Ceras ](https://dndocs.com/d/ceras/api/index.html) | [Github](https://github.com/rikimaru0345/Ceras) |
|SharpPcap |[DNDocs - SharpPcap ](https://dndocs.com/d/sharppcap/api/index.html) | [Github](https://github.com/dotpcap/sharppcap) |
|NetCoreServer|[DNDocs - NetCoreServer](https://dndocs.com/d/netcoreser/api/index.html) | [Github](https://github.com/chronoxor/NetCoreServer) |
|Colourful |[DNDocs - Colourful ](https://dndocs.com/d/colourful/api/index.html) | [Github](https://github.com/tompazourek/Colourful) |
|NGraphics |[DNDocs - NGraphics ](https://dndocs.com/d/ngraphics/api/index.html) | [Github](https://github.com/praeclarum/NGraphics) |
|RestEase |[DNDocs - RestEase ](https://dndocs.com/d/restease/api/index.html) | [Github](https://github.com/canton7/RestEase) |
|Refit |[DNDocs - Refit ](https://dndocs.com/d/refit/api/index.html) | [Github](https://github.com/reactiveui/refit) |
|RestSharp |[DNDocs - RestSharp ](https://dndocs.com/d/restsharp/api/index.html) | [Github](https://github.com/restsharp/RestSharp) |
|Http.fs|[DNDocs - Http.fs](https://dndocs.com/d/httpfs/api/index.html) | [Github](https://github.com/haf/Http.fs) |
|Tiny.RestClient|[DNDocs - Tiny.RestClient](https://dndocs.com/d/tinyrestc/api/index.html) | [Github](https://github.com/jgiacomini/Tiny.RestClient) |
|AgileObjects.AgileMapper|[DNDocs - AgileObjects.AgileMapper](https://dndocs.com/d/agileobjec/api/index.html) | [Github](https://github.com/agileobjects/AgileMapper) |
|TinyMapper |[DNDocs - TinyMapper ](https://dndocs.com/d/tinymapper/api/index.html) | [Github](https://github.com/TinyMapper/TinyMapper) |
|NAudio |[DNDocs - NAudio ](https://dndocs.com/d/naudio/api/index.html) | [Github](https://github.com/naudio/NAudio) |
|CSCore |[DNDocs - CSCore ](https://dndocs.com/d/cscore/api/index.html) | [Github](https://github.com/filoe/cscore) |
|Vim.Math3D |[DNDocs - Vim.Math3D ](https://dndocs.com/d/vimmathd/api/index.html) | [Github](https://github.com/vimaec/math3d) |
|Rationals|[DNDocs - Rationals](https://dndocs.com/d/rationals/api/index.html) | [Github](https://github.com/tompazourek/Rationals) |
|MimeKit |[DNDocs - MimeKit ](https://dndocs.com/d/mimekit/api/index.html) | [Github](https://github.com/jstedfast/MimeKit) |
|PreMailer.Net|[DNDocs - PreMailer.Net](https://dndocs.com/d/premailer/api/index.html) | [Github](https://github.com/milkshakesoftware/PreMailer.Net) |
|Markdig |[DNDocs - Markdig ](https://dndocs.com/d/markdig/api/index.html) | [Github](https://github.com/xoofx/markdig) |
|Stashbox |[DNDocs - Stashbox ](https://dndocs.com/d/stashbox/api/index.html) | [Github](https://github.com/z4kn4fein/stashbox) |
|LightInject |[DNDocs - LightInject ](https://dndocs.com/d/lightinjec/api/index.html) | [Github](https://github.com/seesharper/LightInject) |
|Spring.Core|[DNDocs - Spring.Core](https://dndocs.com/d/springcor/api/index.html) | [Github](https://github.com/spring-projects/spring-net) |
|Ninject|[DNDocs - Ninject](https://dndocs.com/d/ninject/api/index.html) | [Github](https://github.com/ninject/ninject) |
|StringDB|[DNDocs - StringDB](https://dndocs.com/d/stringdb/api/index.html) | [Github](https://github.com/SirJosh3917/StringDB) |
|SliccDB|[DNDocs - SliccDB](https://dndocs.com/d/sliccdb/api/index.html) | [Github](https://github.com/pmikstacki/SliccDB) |
|Akade.IndexedSet|[DNDocs - Akade.IndexedSet](https://dndocs.com/d/akadeinde/api/index.html) | [Github](https://github.com/akade/Akade.IndexedSet) |
|Towel |[DNDocs - Towel ](https://dndocs.com/d/towel/api/index.html) | [Github](https://github.com/ZacharyPatten/Towel) |
|Guard.Net|[DNDocs - Guard.Net](https://dndocs.com/d/guardnet/api/index.html) | [Github](Guard.Net) |
|Arctium - .NET Core crypto library|[dndocs - Arctium - .NET Core crypto library](https://www.dndocs.com/d/arctium/api/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|
|Arctium.Shared|[dndocs - Arctium.Shared](https://www.dndocs.com/d/arctium-shared/api/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|
|Arctium.Cryptography|[dndocs - Arctium.Cryptography](https://www.dndocs.com/d/arctium-cryptography/api/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|
|Arctium.Standards|[dndocs - Arctium.Standards](https://www.dndocs.com/d/arctium-standards/api/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|
