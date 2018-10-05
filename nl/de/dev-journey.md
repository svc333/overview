---

copyright:
  years: 2016, 2017, 2018
lastupdated: "2018-09-12"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}

# Developer Journey in {{site.data.keyword.cloud_notm}} erkunden
{: #dev-journey}

Für Entwickler bietet {{site.data.keyword.cloud}} eine Reihe von Funktionalitäten, mit denen Apps in wenigen Minuten erstellt werden können. In unseren Entwicklerdashboards können Sie Folgendes tun:

* Starter-Kits auswählen, die anwendungsfallspezifisch sind, und einsatzbereite Starter-Apps in einer Vielzahl von Programmiersprachen und Architekturmustern erzeugen.
* Ressourcen anzeigen und verwalten, die automatisch von Ihrem Starter-Kit bereitgestellt wurden bzw. die Sie Ihrer App manuell hinzugefügt haben.
* Portierbaren App-Code abrufen, mit dem Sie in verschiedenen Cloudumgebungen bereitstellen können.
* In wenigen Klicks eine [DevOps-Toolchain](../services/ContinuousDelivery/index.html#cd_getting_started) erstellen.
* Eine [Befehlszeilenschnittstelle](/docs/cli/idt/index.html) für die lokale Entwicklung verwenden.

Um zu verstehen, wie die {{site.data.keyword.cloud_notm}}-Entwicklungsumgebung Ihnen helfen kann, schnell qualitativ hochwertige, einsatzbereite Apps zu erstellen, gehen wir auf diese Elemente im Detail ein.

## Entwicklerdashboards
{: #dev-dashboards}

{{site.data.keyword.cloud_notm}} verfügt über Entwicklerdashboards für verschiedene Interessensbereiche (wie Watson, Sicherheit, oder Finanzen) bzw. digitale Kanäle (wie Mobile oder Web-Apps). Sie können auf diese Dashboards über das **Menüsymbol** ![Menüsymbol](../icons/icon_hamburger.svg) zugreifen.

Jedes Entwicklerdashboard stellt Starter-Kits mit Bezug auf den Schwerpunktbereich des Dashboards bereit und bietet einen konsistenten, intuitiven Workflow, mit dem Sie in wenigen Minuten eine funktionstüchtige, einsatzbereite App erstellen können.

## Apps
{: #app-projects}

Eine App umfasst Code, Daten, Services und Toolchains. Beispielsweise enthält die {{site.data.keyword.cloud_notm}} Mobile-App Gerätecode und Back-End-Logik, Datenspeicher, Analyse- und Sicherheitsservices und ist für Continuous Delivery konzipiert.

![Wiederverwenden](images/garage_reuse2.png "Die Entwicklungsumgebung lässt Sie Elemente wiederverwenden und Sie müssen das Rad nicht jedes mal neu erfinden.")

Sie können eine App mithilfe eines beliebigen {{site.data.keyword.cloud_notm}}-Entwicklerdashboards oder der {{site.data.keyword.dev_cli_notm}} erstellen und verwalten.

## Starter-Kits
{: #starter-kits}

Mithilfe von Starter-Kits erstellt {{site.data.keyword.cloud_notm}} das Gerüst einer Produktions-App in der Sprache Ihrer Wahl, das in der Cloud bereitgestellt werden kann. Jedes Starter-Kit umfasst eine Sprache, ein Framework und ein Muster für einen bestimmten Anwendungsfall und ermöglicht Ihnen, Code wiederzuverwenden.

### Inwiefern unterscheiden sich Starter-Kits von normalen Beispielen?
Starter-Kits sind sofort einsatzbereit und veranschaulichen in erster Linie die grundlegende Musterimplementierung mithilfe einer Laufzeit (z. B. Node.js und Express). In manchen Fällen bieten Starter-Kits eine einfache Benutzererfahrung, um die Integration des Service hervorzuheben. In anderen Fällen stellen Starter-Kits eine anpassbare Implementierung eines ausgereiften Anwendungsfalls dar.

* Ein **Snippet** sind wenige Zeilen Code, die oft in einer IDE vorhanden sind. Snippets unterstützen einen Entwickler bei der Integration einer Programmiersprachensyntax oder einer definierten API.
* Eine **Demonstration** ist üblicherweise qualitativ hochwertig und inhaltstreu und verwendet eine Reihe von Services und Integrationspunkten. Sie erfordert oft eine gewisse Rüstzeit und wird eingesetzt, um ein Geschäftsproblem zur veranschaulichen oder ein Plattformfeature vorzuführen. Sie wird verwendet, um Phasen der Cloudeinführung zu evaluieren. Manchmal ist der Code in Produktionscode eingeschlossen.
* Ein **Beispiel** ist ein kompakte Veranschaulichung eines bestimmtes Features, einer bestimmten Funktion, eines bestimmten Service oder einer bestimmten User Journey. Ein Beispiel kann wiederverwendet werden oder in einer Produktionsanwendung enthalten sein. Es wird typischerweise verwendet, um technische Funktionen zu veranschaulichen und mögliche Lösungswege für ein technisches Problem aufzuzeigen.
* Ein **Starter-Kit** ist ein einsatzbereites Muster, das in einen Satz Services integriert werden kann, um ein einsatzbereites Asset zu generieren, das direkt in einer DevOps-Pipeline und einem Kubernetes-Cluster bereitgestellt werden kann. Ein Starter-Kit enthält beschreibende Metadaten, die dem Benutzer ausreichend Informationen über den Aufbau und die Funktionalität des Kits liefern. Es enthält außerdem Anweisungen, was {{site.data.keyword.cloud_notm}} erzeugen soll. Die Ausgabe ist direkt einsatzbereit und kann für weitere Verbesserungen iteriert werden, auf der Basis von IBM Best Practices. Der Inhalt eines Starter-Kits ist nicht so komplex wie eine Demonstration und nicht so einfach strukturiert wie ein Snippet oder ein Beispiel. Starter-Kits werden abhängig von den Anforderungen eines Entwicklers dynamisch erstellt.

## Automatisch bereitgestellte Ressourcen
{: #auto-provision}

Falls ein Starter-Kit erforderliche Ressourcen angibt, erstellt {{site.data.keyword.cloud_notm}} automatisch Instanzen dieser Ressourcen, wenn Sie Ihre App erstellen. Denken Sie daran, dass Sie auch manuell Ressourcen bereitstellen oder vorhandene Ressourceninstanzen auswählen können, die Ihrer App hinzugefügt werden, nachdem sie erstellt wurde. In der Ansicht 'App-Details' können Sie eine Liste von Serviceinstanzen anzeigen, die Ihrer App zugeordnet sind, zusammen mit den ggf. erforderlichen Berechtigungsnachweisen.

## Portierbarer Code
{: #portable-code}

Beim Erstellen einer App aus einem Starter-Kit wird automatisch Code für Sie erstellt, der ein konsistentes Format hat und laufzeitunabhängig ist. Sie können den Code in der Umgebung Ihrer Wahl bereitstellen, z. B. Kubernetes oder Cloud Foundry, ohne Änderungen daran vorzunehmen.

### Welcher Code wird erstellt?
Der aus einem {{site.data.keyword.cloud_notm}}-Starter-Kit erstellte Code hat vier grundlegende Komponenten: Anwendungsfalllogik, Sprachkomponenten, Serviceaktivierung und Cloudaktivierung. Das Generieren dieser Komponenten spart Ihnen wertvolle Zeit und stellt sicher, dass Sie mit der leistungsfähigsten Architektur arbeiten.

* **Anwendungsfalllogik** bietet Funktionen für den zentralen Zweck eines Anwendungsfalls. Beispiele sind unter anderem Code für einen Watson Conversation-Chat-Bot oder Code für eine mobile App für visuelle Erkennung.
* **Sprachkomponenten** sind Codekomponenten und Dateien, die spezifisch sind für die Programmiersprache, die Sie für Ihr Starter-Kit ausgewählt haben. Beispielsweise benötigen Node.js-Programmierer eine 'package.json'-Datei für das Abhängigkeitsmanagement und diese Datei wird automatisch erstellt.
* **Serviceaktivierung** ist Code, der Ihrer App ermöglicht, die Services, die Sie hinzufügen, zu verbinden und zu verwenden. Verwaltung von Berechtigungsnachweisen, Initialisierungscode und servicespezifische SDKs sind Beispiele für Serviceaktivierungskomponenten.
* **Cloudaktivierung** ist Code, der Ihre App befähigt, unter {{site.data.keyword.cloud_notm}} ausgeführt zu werden. Beispielsweise Helm-Diagramme, die Ihre App befähigen, in einem {{site.data.keyword.cloud_notm}}-Kubernetes-Cluster ausgeführt zu werden.

Wenn Sie eine App auf der Grundlage eines {{site.data.keyword.cloud_notm}}-Starter-Kits erstellen, baut diese App auf bewährter Architektur auf, die außerdem die bewährten Verfahren (Best Practices) für die von Ihnen ausgewählte Sprache widerspiegelt.

Jede App enthält eine Readme-Datei mit den technischen Details des Projekts und erläutert, welche Schritte ausgeführt werden müssen, wenn Ihre App nicht sofort einsatzbereit ist.
{: tip}

## DevOps-Toolchain
{: #devops}

DevOps umfasst Prozeduren und Tools für den Zugriff, die Entwicklung, die Bereitstellung und den Betrieb Ihrer App. Eine DevOps-Toolchain ist ein Satz verknüpfter Services zur Automatisierung Ihrer DevOps-Tasks. Es ist möglich, DevOps mithilfe von sehr einfachen Apps manuell auszuführen, aber der Bedarf an Automatisierung nimmt mit der Komplexität von Apps schnell zu und die Toolchain-Automatisierung ist ein Must-Have für eine Continuous Delivery.

Die zentrale Komponente einer DevOps-Toolchain ist ein Repository für die Steuerung von Codeversionen wie GitHub. Zusätzliche Tools können ein Rückstandtracking, eine Delivery Pipeline, eine IDE und einen Überwachungsservice wie [{{site.data.keyword.cloud_notm}}DevOps Insights](../services/DevOpsInsights/index.html#gettingstarted) enthalten.

Wenn Sie eine App mithilfe eines Starter-Kits erstellt haben, können Sie eine neue Toolchain erstellen und Ihre App einfach durch Klicken auf **In Cloud bereitstellen** in der Ansicht 'App-Details' bereitstellen. Es wird eine Toolchain mit einem Coderepository, einer Delivery Pipeline und einer Web-IDE erstellt.

Sie können auf der Grundlage dieser Toolchain weiter entwickeln, um mehrere Teams und die Bereitstellung in separaten Umgebungen für Entwicklung, Tests und Produktion zu ermöglichen und so ein auf Unternehmen abgestimmtes Modell für bereichsübergreifende Continuous Delivery für Ihre App erstellen.  

![Continuous Delivery](images/garage_continuous_delivery2.png "Die Entwicklungsumgebung richtet Continuous Delivery in Ihrem Entwicklungszweig ein.")

Sie können auch einen schnellen Blick auf Ihren App-Code werfen, indem Sie auf der App-Übersichtsseite des Entwicklerdashboards auf die Schaltfläche **Download** klicken. Ihr Code wird in Form einer `.zip`-Datei heruntergeladen, die die vollständige App-Codestruktur enthält. Sie können die Datei einfach erstellen und den Code lokal mithilfe der {{site.data.keyword.dev_cli_notm}} ausführen oder Sie können ihn zu Ihrem Code-Management-Repository hinzufügen.

## Befehlszeilenschnittstelle
Mit {{site.data.keyword.dev_cli_notm}} können Sie Ihre App lokal codieren, erstellen und ausführen.  Eine gängige Vorgehensweise besteht darin, Ihre App mithilfe eines Entwicklerdashboards zu erstellen, in {{site.data.keyword.dev_cli_notm}} lokal zu entwickeln und dann die Aktualisierungen per Push-Operation in Ihr Repository zu übertragen und dort zusammenzuführen, um Ihre Toolchain für Bereitstellung zu starten.

## Garage Method-Entwicklung
{: #developer_concepts}

Informieren Sie sich über die [Garage Method](https://www.ibm.com/cloud/garage/), um zu erfahren, wie IBM Sie beim Entwickeln von Apps in Ihrer Organisation unterstützen kann.  

![Übersicht über die Garage Method-Phasen](images/garage_phases_overview2.png "Übersicht über die Garage Method-Phasen")*Übersicht über die Garage Method-Phasen*

{{site.data.keyword.cloud_notm}} hilft Ihnen dabei, auf Unternehmen abgestimmte Produktions-Apps mithilfe der Garage Method oder einer beliebigen anderen Methode zu erzeugen. Um besser zu verstehen, was {{site.data.keyword.cloud_notm}} Entwicklern bieten kann, werfen wir einen kurzen Blick auf die Fähigkeiten, die erforderlich sind, um eine moderne App zu erstellen.

## Entwickler-Know-how
{: #skills}

Heute erwarten Benutzer mehr von ihren Anwendungen als je zuvor. Sie erwarten, dass Apps aussagekräftige Informationen aus gespeicherten und Echtzeitdaten ziehen, immer verfügbar sind und ihre individuellen Bedürfnisse möglichst optimal abbilden. Um diese Erwartungen erfüllen zu können, müssen App-Entwickler ein breites Repertoire an Know-how mitbringen. Eine ausgereifte kognitive Anwendung kann Beiträge von digitalen Entwicklern, cloudnativen Entwicklern, Stream-Entwicklern, Data-Scientists und DevOps-Spezialisten erforderlich machen.

 ![Entwicklertypen](images/developer_skills.png "Beziehungen zwischen Entwicklern")

* **Digitale Entwickler** erstellen einen digitalen Kanal wie mobiles Web, Sprachsteuerung und Chat. Digitale Entwickler konzentrieren sich typischerweise auf Anwendungsfälle und die direkte Erfüllung von Benutzeranforderungen.
* **Cloudnative Entwickler** spezialisieren sich darauf, Cloudkomponenten zu erstellen und miteinander zu verbinden. Dazu zählen beispielsweise Verfasser von Mikroservices und Back-End-for-Front-End-Verfasser.
* **Stream-Entwickler** konzentrieren sich auf die Verarbeitung von Datenströmen und den entsprechenden Erkenntnisgewinn. Ein Stream-Entwickler kann beispielsweise Aktionen für eingehende Text-, Sprache- oder Videodatenströme analysieren und initiieren.
* **Data-Scientists** setzen Analysen und maschinelles Lernen ein, um Vorhersagemodelle zu erstellen. Diese Modelle werden in Geschäftsmetriken verwendet und liefern aussagekräftige Informationen für Anwendungsbenutzer.
* **DevOps-Spezialisten** sind Experten im Beheben von Bereitstellungs- und Toolchain-Problemen. Bei einfachen Apps sind dedizierte Spezialisten üblicherweise nicht erforderlich, da DevOps im Team verwaltet werden. Aber bei komplexen Unternehmensanwendungen mit vielen Abhängigkeiten sind DevOps-Spezialisten unerlässlich, um Ihre Produktions-App reibungslos ausführen zu können.

Die Entwicklerfunktionalitäten, die in {{site.data.keyword.cloud_notm}} integriert sind, sind an diesem Know-how ausgerichtet und ermöglichen Ihrem Team, eine einzige Plattform zum Erzeugen, Bereitstellen, Ausführen und Verwalten Ihrer App zu verwenden. Beispielsweise kann ein digitaler Entwickler, der eine mobile App erstellt, das {{site.data.keyword.cloud_notm}} [Mobile-Entwicklerdashboard](https://console.bluemix.net/developer/mobile/dashboard) verwenden, während ein Entwickler von kognitiven Apps das [Watson-Entwicklerdashboard](https://console.bluemix.net/developer/watson/dashboard) zusammen mit [Watson Studio](https://console.bluemix.net/catalog/services/watson-studio) nutzt. Ein Streams-Entwickler kann [IBM Real-Time Analytics](../services/StreamingAnalytics/index.html#gettingstarted) verwenden und der [Continuous Delivery-Service von {{site.data.keyword.cloud_notm}}](../services/ContinuousDelivery/index.html#cd_getting_started) vereinfacht den Job eines DevOps-Spezialisten.

Bereit, loszulegen? [Klicken Sie hier](../apps/index.html), um jetzt eine App in {{site.data.keyword.cloud_notm}} zu erstellen.
