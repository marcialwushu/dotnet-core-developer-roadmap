Language: 
[RO](/README-RO.md) | 
[ES](/README.md)

# Roadmap-ul  dezvoltatorului .NET Core

>  Roadmap-ul pentru a deveni un Dezvoltator .NET

Un ghid pentru dezvoltator cu toate instrumentele și principiile necesare în timpul dezvoltării.

> Scopul acestui roadmap este să ofere o idee despre peisaj.  Roadmap-ul vă va ghida dacă sunteți confuz cu privire la ce să învățați în continuare, în loc să vă încurajeze să alegeți ce este modern și în tendințe. Ar trebui să înțelegeți mai bine de ce unele instrumente ar fi mai potrivite pentru anumite cazuri decât altele și să vă amintiți că "modern" nu înseamnă întotdeauna cel mai potrivit pentru sarcină.

ASP.NET Core este noul framework web dezvoltat de Microsoft. ASP.NET Core este un framework open-source și cross-platform pentru construirea de aplicații web moderne bazate pe cloud, compatibile cu Windows, macOS sau Linux.

> Mai jos puteți găsi un grafic care prezintă căile pe care le puteți urma și bibliotecile pe care doriți să le învățați pentru a deveni un dezvoltator ASP.NET Core. Am creat acest grafic ca un sfat pentru toți cei care mă întreabă: "Ce ar trebui să învăț în continuare ca dezvoltator ASP.NET Core?"

## Dă o stea! ⭐

Dacă vă place sau folosiți acest proiect pentru a învăța sau a începe o soluție, acordați-i o stea. Vă mulțumesc!

##  Roadmap

![](images/aspnetcore-developer-roadmap-printable.png)

## Caracteristici .NET Core:

- Suport cross-platform și pentru containere.
- Performanță ridicată.
- Asincron prin async/await.
- Framework-uri unificate MVC & Web API.
- Medii multiple și mod de dezvoltare.
- Injecție de dependențe.
- WebSockets și SignalR.

## Resurse

1. Învață cerințele preliminare

   - [C#](https://www.pluralsight.com/paths/csharp)
   - [.NET 5](https://devblogs.microsoft.com/dotnet/introducing-net-5)
   - [Entity Framework](https://www.pluralsight.com/search?q=entity%20framework%20core)
   - [Dapper](https://github.com/StackExchange/Dapper)
   - [NHibernate](https://github.com/nhibernate/nhibernate-core)
   - [ASP.NET Core](https://www.pluralsight.com/search?q=asp.net%20core)
   - Fundamentele SQL

2. Abilități de dezvoltare generale

   - Învață GIT, creează câteva depozite pe GitHub și împărtășește-ți codul cu alții.
   - Cunoașteți protocolul HTTP (S), metodele de cerere (GET, POST, PUT, PATCH, DELETE, OPTIONS).
   - Nu vă fie teamă să utilizați Google, [Căutări puternice cu Google](http://www.powersearchingwithgoogle.com).
   - Învață [dotnet CLI](https://docs.microsoft.com/dotnet/core/tools).
   - Citește câteva cărți despre algoritmi și structuri de date.

3. SOLID

    - [Principiul Responsabilității Unice (SRP)](https://www.dotnetcurry.com/software-gardening/1148/solid-single-responsibility-principle)
    - [Principiul Deschis/Închis (OCP)](https://www.dotnetcurry.com/software-gardening/1176/solid-open-closed-principle)
    - [Principiul Substiției Liskov (LSP)](https://www.dotnetcurry.com/software-gardening/1235/liskov-substitution-principle-lsp-solid-patterns)
    - [Principiul Segregării Interfețelor (ISP)](https://www.dotnetcurry.com/software-gardening/1257/interface-segregation-principle-isp-solid-principle)
    - [Principiul Inversiunii Dependințelor (DIP)](https://www.dotnetcurry.com/software-gardening/1284/dependency-injection-solid-principles)

4. Injecție de dependențe

   1. Containere DI
      - [Microsoft.Extensions.DependencyInjection](https://docs.microsoft.com/aspnet/core/fundamentals/dependency-injection)
      - [AutoFac](https://autofaccn.readthedocs.io/en/latest/integration/aspnetcore.html)
      - [Ninject](http://www.ninject.org)
      - [Castle Windsor](https://github.com/castleproject/Windsor)
      - [Simple Injector](https://github.com/simpleinjector/SimpleInjector)
   2. [Ciclurile de viață](https://docs.microsoft.com/aspnet/core/fundamentals/dependency-injection#service-lifetimes)
   3. [Scrutor](https://github.com/khellang/Scrutor)

5. Baze de date

   1. Relaționale
      1. [SQL Server](https://www.microsoft.com/sql-server/sql-server-2019)
      2. [PostgreSQL](https://www.postgresql.org)
      3. [MariaDB](https://mariadb.org)
      4. [MySQL](https://www.mysql.com)
   2. Baze de date în cloud
      - [CosmosDB](https://docs.microsoft.com/azure/cosmos-db)
      - [DynamoDB](https://aws.amazon.com/dynamodb)
   3. Motoare de căutare
      - [ElasticSearch](https://www.elastic.co)
      - [Solr](http://lucene.apache.org/solr)
      - [Sphinx](http://sphinxsearch.com)
   4. Baze de date NoSQL
      - [Redis](https://redis.io)
      - [MongoDB](https://docs.microsoft.com/aspnet/core/tutorials/first-mongo-app)
      - [Apache Cassandra](http://cassandra.apache.org)
      - [LiteDB](https://github.com/mbdavid/LiteDB)
      - [RavenDB](https://github.com/ravendb/ravendb)
      - [CouchDB](http://couchdb.apache.org)

6. Cache

   1. [Memory Cache](https://docs.microsoft.com/aspnet/core/performance/caching/memory)
   2. [Distributed Cache](https://docs.microsoft.com/aspnet/core/performance/caching/distributed)
      1. [Redis](https://redis.io/)
         1. [StackExchange.Redis](https://stackexchange.github.io/StackExchange.Redis)
         2. [EasyCaching](https://github.com/dotnetcore/EasyCaching)
      2. [Memcached](https://memcached.org)
   3. Cache de nivel 2 pentru Entity Framework
      1. [EFCoreSecondLevelCacheInterceptor](https://github.com/VahidN/EFCoreSecondLevelCacheInterceptor)
      2. [EntityFrameworkCore.Cacheable](https://github.com/SteffenMangold/EntityFrameworkCore.Cacheable)

7. Jurnale

   1. Framework-uri de jurnalizare
      - [Serilog](https://github.com/serilog/serilog)
      - [NLog](https://github.com/NLog/NLog)
   2. Sisteme de management al jurnalului
      - [ELK Stack](https://www.elastic.co/what-is/elk-stack)
      - [Sentry.io](http://sentry.io)
      - [Loggly.com](https://loggly.com)
      - [Elmah.io](http://elmah.io)
      
8. Clienți API și comunicări

    1. REST
       - [OData](https://devblogs.microsoft.com/odata/experimenting-with-odata-in-asp-net-core-3-1)
       - [Sieve](https://github.com/Biarity/Sieve)
    2. [gRPC](https://docs.microsoft.com/en-us/aspnet/core/grpc)
    3. GraphQL
       - [HotChocolate](https://github.com/ChilliCream/hotchocolate)
       - [GraphQL-dotnet](https://github.com/graphql-dotnet/graphql-dotnet)

9. Comunicare în timp real

   - [SignalR](https://docs.microsoft.com/aspnet/core/signalr)
   - [WebSockets](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/websockets)
   
10. Mapping de obiecte

   - [AutoMapper](https://github.com/AutoMapper/AutoMapper)
   - [Mapster](https://github.com/MapsterMapper/Mapster)
   - [ExpressMapper](http://expressmapper.org/)
   - [AgileMapper](https://github.com/agileobjects/AgileMapper)
   
11. Planificarea sarcinilor

    - [Coravel](https://github.com/jamesmh/coravel)
    - [HangFire](https://github.com/HangfireIO/Hangfire)
    - [Background Service](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/hosted-services)
    - [Fluent Scheduler](https://github.com/fluentscheduler/FluentScheduler)
    
12. Testare

    1. Testare unitară
       1. Framework-uri
          - [xUnit](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-dotnet-test)
          - [NUnit](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-nunit)
          - [MSTest](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-mstest)
       2. Mocking
          - [Moq](https://github.com/moq/moq4)
          - [NSubstitute](https://github.com/nsubstitute/NSubstitute)
          - [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy)
       3. Assertion
          - [FluentAssertion](https://github.com/fluentassertions/fluentassertions)
          - [Shouldly](https://github.com/shouldly/shouldly)
    2. Testare de integrare
       - [WebApplicationFactory](https://docs.microsoft.com/aspnet/core/test/integration-tests)
       - [TestServer](https://koukia.ca/integration-testing-in-asp-net-core-2-0-51d14ede3968)
    3. Testare comportamentală BDD
       - [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore)
       - [BDDfy](https://github.com/TestStack/TestStack.BDDfy)
       - [LightBDD](https://github.com/LightBDD/LightBDD)
    4. Testare E2E
       - [Selenium](https://www.hanselman.com/blog/real-browser-integration-testing-with-selenium-standalone-chrome-and-aspnet-core-21)
       - [Puppeteer-Sharp](https://github.com/kblok/puppeteer-sharp)

13. Microservicii

    1. Broker de mesaje
       - [RabbitMQ](https://www.rabbitmq.com/tutorials/tutorial-one-dotnet.html)
       - [Apache Kafka](https://github.com/confluentinc/confluent-kafka-dotnet)
       - [ActiveMQ](https://github.com/apache/activemq)
       - [Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview)
       - [NetMQ](https://github.com/zeromq/netmq)
    2. Bus de mesaje
       - [MassTransit](https://github.com/MassTransit/MassTransit)
       - [NServiceBus](https://github.com/Particular/NServiceBus)
       - [EasyNetQ](https://github.com/EasyNetQ/EasyNetQ)
       - [CAP](https://github.com/dotnetcore/CAP)
    3. API Gateway
       - [Ocelot](https://github.com/ThreeMammals/Ocelot)
    4. Containerizare
       - [Docker](https://www.docker.com)
    5. Orchestare
       - [Kubernetes](https://kubernetes.io)
       - [Docker Swarm](https://docs.docker.com/engine/swarm)
    6. Proxy invers
       - [YARP](https://github.com/microsoft/reverse-proxy)
    7. Altele
       - [Orleans](https://github.com/dotnet/orleans)
       - [Steeltoe](https://steeltoe.io)
       - [Dapr](https://github.com/dapr/dapr)
       - [Tye](https://github.com/dotnet/tye)

14. Integrare și livrare continuă
    - [Acțiuni GitHub](https://github.com/features/actions)
    - [Pipelines Azure](https://azure.microsoft.com/en-us/services/devops/pipelines)
    - [Travis CI](https://travis-ci.org)
    - [Jenkins](https://www.jenkins.io)
    - [Circle CI](https://circleci.com)
    - [TeamCity](

https://www.jetbrains.com/teamcity)

15. Design Patterns

    - [CQRS](https://docs.microsoft.com/azure/architecture/patterns/cqrs)
    - [Decorator](https://www.dofactory.com/net/decorator-design-pattern)
    - [Strategy](https://www.dofactory.com/net/strategy-design-pattern)
    - [Builder](https://www.dofactory.com/net/builder-design-pattern)
    - [Singleton](https://www.dofactory.com/net/singleton-design-pattern)
    - [Facade](https://www.dofactory.com/net/facade-design-pattern)

16. Biblioteci client-side
    - [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)

17. Motoare de șabloane

   - [Razor](https://docs.microsoft.com/aspnet/core/mvc/views/razor)
   - [DotLiquid](https://github.com/dotliquid/dotliquid)
   - [Scriban](https://github.com/lunet-io/scriban)
   - [Fluid](https://github.com/sebastienros/fluid)

18. Bine de știut

    - [MediatR](https://github.com/jbogard/MediatR)
    - [Fluent Validation](https://github.com/JeremySkinner/FluentValidation)
    - [Polly](https://github.com/App-vNext/Polly)    
    - [Benchmark.NET](https://github.com/dotnet/BenchmarkDotNet)
    - [NodaTime](https://github.com/nodatime/nodatime)
    - [GenFu](https://github.com/MisterJames/GenFu)
    - [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)

## Concluzie

Dacă credeți că roadmap-ul poate fi îmbunătățită, deschideți un PR cu toate actualizările și trimiteți orice probleme. De asemenea, voi continua să îmbunătățesc acest proiect, deci poate doriți să marcați acest repositoriu cu o stea pentru a reveni asupra lui.

Inspirație din: [ASP.NET Core Developer Roadmap [Engleză]](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap)

## Contribuții

Doriți să contribuiți? Încurajăm comentariile și contribuțiile comunității. Urmați ghidurile noastre de contribuție.

## REFERINȚE 

- https://github.com/MoienTajik/AspNetCore-Developer-Roadmap
- https://medium.com/developers-cafe/net-core-developer-roadmap-270bba855f82
