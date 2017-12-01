NEO: Ein dezentrales Netzwerk für die Smart Economy
================

NEO nutzt digitale Identität und Blockchain-Technologie zur Digitalisierung von Assets und nutzt Smart Contracts für autonom verwaltete digitale Assets, um eine "Smart Economy" innerhalb eines dezentralisierten Netzwerks zu schaffen.

Um mehr über NEO zu erfahren, lesen Sie bitte das [White Paper](http://docs.neo.org/de-de/index.html)|[Englische Version](http://docs.neo.org/en-us/index.html)|[白皮书](http://docs.neo.org/zh-cn/index.html).

Unterstützte Plattformen
--------

Wir unterstützen schon folgende Plattformen:

* CentOS 7
* Docker
* macOS 10 +
* Red Hat Enterprise Linux 7.0 +
* Ubuntu 14.04, Ubuntu 14.10, Ubuntu 15.04, Ubuntu 15.10, Ubuntu 16.04, Ubuntu 16.10
* Windows 7 SP1 +, Windows Server 2008 R2 +

In Zukunft werden wir auch folgende Plattformen unterstützen:

* Debian
* Fedora
* FreeBSD
* Linux Mint
* OpenSUSE
* Oracle Linux

Entwicklung
--------

Um Peer-Anwendungen für NEO unter Windows zu entwickeln, müssen Sie [Visual Studio 2017](https://www.visualstudio.com/products/visual-studio-community-vs) herunterladen und [.NET Core SDK](https://www.microsoft.com/net/core) installieren.

Wenn Sie auf Linux oder macOS entwickeln wollen, installieren Sie einfach [.NET Core SDK](https://www.microsoft.com/net/core).

Führen Sie den folgenden Befehl in der [Package Manager Console](https://docs.nuget.org/ndocs/tools/package-manager-console) aus, um Neo SDK in Ihrem Projekt zu installieren: 

```
PM> Install-Package Neo
```

Weitere Informationen zum Erstellen von DAPPs für NEO finden Sie in der [Dokumentation](http://docs.neo.org/de-de/sc/introduction.html)|[documentation](http://docs.neo.org/en-us/sc/introduction.html)|[文档](http://docs.neo.org/zh-cn/sc/introduction.html).

Wie Sie zum Projekt beitragen können
--------

Sie können zu NEO mit [Issues](https://github.com/neo-project/neo/issues) und [PRs](https://github.com/neo-project/neo/pulls) beitragen. Issues einfach einzutragen, ist ein guter Weg, um etwas beizutragen. Mit Implementierungen beizutragen wird sehr geschätzt.

Wir verwenden und empfehlen den folgenden Workflow:

1. Erstellen Sie ein Issue für Ihre Arbeit.
    * Für triviale Änderungen können Sie diesen Schritt überspringen
      * Verwenden Sie ein vorhandenes Issue zum Thema, falls vorhanden.
      * Geben Sie klar an, dass Sie die Implementierung übernehmen werden, wenn das der Fall ist. Sie können beantragen, dass das Issue Ihnen zugewiesen wird. Hinweis: Der Issue-Einreicher und der Implementierer müssen nicht dieselbe Person sein.
2. Erstellen Sie eine persönliche Fork der Repository auf GitHub (wenn Sie das nicht schon getan haben).
3. Erstellen Sie einen neuen Branch von Master (`git checkout -b mybranch`).
    * Benennen Sie den Branch so, dass er Ihre Absichten klar kommuniziert, z. B. issue-123 oder githubhandle-issue.
      * Branches sind nützlich, da sie Ihre Änderungen von eingehenden Änderungen von Upstream isolieren. Sie ermöglichen es Ihnen auch, mehrere PRs von derselben Fork zu erstellen.
      
4. Machen Sie Ihre Änderungen und Commits
5. Fügen Sie gegebenenfalls neue Tests zu Ihren Änderungen hinzu.
6. Erstellen Sie das Repository mit Ihren Änderungen.
    * Versichern Sie sich dass die Builds sauber sind.
      * Stellen Sie sicher, dass die Tests alle bestehen, einschließlich Ihrer neuen Tests.
7. Erstellen Sie eine Pull Request (PR) für den Master Branch des Upstream-Repositorys.
    * Pushen Sie Ihre Änderungen in Ihre Fork auf GitHub

Anmerkung: Es ist OK wenn Ihre PR eine grosse Anzahl an Commits enthält. Sobald Ihre Änderung akzeptiert wurde, werden Sie aufgefordert, Ihre Commits in eine oder eine entsprechend kleine Anzahl von Commits zu zerlegen, bevor Ihre PR zusammengeführt wird.

Lizenz
------

Das Neo Projekt ist unter der [MIT license](LICENSE) lizenziert.
