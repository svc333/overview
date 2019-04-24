---

copyright:

  years: 2015, 2019

lastupdated: "2019-04-05"

keywords: release notes, what's new, what is new, cloud updates

subcollection: overview

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Neuerungen in {{site.data.keyword.Bluemix_notm}}
{: #whatsnew}

Wenn Sie hinsichtlich neuer Features, die auf der {{site.data.keyword.Bluemix}}-Plattform verfügbar sind, stets auf dem aktuellen Stand bleiben, können Sie am meisten von {{site.data.keyword.Bluemix_notm}} profitieren. Aktualisierungen für die Services, die in {{site.data.keyword.Bluemix_notm}} verfügbar sind, finden Sie auf der Seite mit [{{site.data.keyword.Bluemix_notm}}-Ankündigungen ](https://www.ibm.com/cloud/blog/announcements){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") im Blog.
{:shortdesc}

## {{site.data.keyword.Bluemix_notm}}-Plattform
{: #platform_category}


### Nutzungsdaten mit zugehörigen Tags exportieren
Datum der Neuerung: 4. April 2019 

Benutzer können jetzt unsere neueste Tagging-Funktionalität verwenden, um Ressourcen, Nutzung und Kosten im exportierten Nutzungsbericht zu verwalten. Wenn Sie einer Ressource ein Tag hinzufügen, können Sie das Tag jetzt anzeigen, das der Ressource zugeordnet wurde. Rufen Sie **Verwalten**> **Abrechnung und Nutzung**> **Nutzung**> **CSV exportieren**>  **Instanzen** auf, um Ihren Nutzungsbericht herunterzuladen. Weitere Informationen zum Exportieren von Tags finden Sie im Blogbeitrag [Export tags within your usage data to help with cost allocation](https://www.ibm.com/blogs/bluemix/2019/04/export-your-tagged-usage-data-within-the-enhanced-ibm-cloud/).

### Zugriffsgruppe für die Aktivierung des öffentlichen Zugriffs auf Ressourcen
Datum der Neuerung: 25. März 2019

Sie können jetzt den öffentlichen Zugriff auf Objekte aktivieren, die sich in Ihren {{site.data.keyword.cos_full}}-Buckets befinden, indem Sie eine neue Zugriffsgruppe verwenden, die in Ihrem Konto für Sie bereitgestellt wird. Diese neue Zugriffsgruppe wird als Gruppe `Öffentlicher Zugriff` bezeichnet und alle Benutzer und Service-IDs werden dieser Gruppe standardmäßig hinzugefügt. Sie können die Richtlinien für die Zugriffsgruppe aktualisieren, um allen – auch nicht authentifizierten – Benutzern den Zugriff auf die Ressource zu ermöglichen, die Sie in der Richtlinie angeben. [Weitere Informationen zur Gruppe 'Öffentlicher Zugriff'](/docs/iam?topic=iam-public#public).

### Mehrfaktorauthentifizierung für Benutzer mit föderierten IDs
Datum der Neuerung: 12. März 2019
{: #mfa-federated}

Kontoeigner oder Benutzer, denen die Administratorrolle für den Abrechnungskontoverwaltungsservice zugewiesen wurde, können die Mehrfaktorauthentifizierung (MFA) für alle Benutzer in ihrem Konto aktivieren. Für föderierte Benutzer, die ihre unternehmensweite Single Sign-on-ID verwenden, kann es nun erforderlich sein, sich bei der Anmeldung bei {{site.data.keyword.Bluemix_notm}} anhand der MFA zu authentifizieren. Weiter Informationen zur funktionalen Erweiterung dieses Features und zur Aktivierung der MFA für Ihr Konto finden Sie in [Einführung der MFA für IBM Cloud-Benutzer mit einer föderierten ID ](https://www.ibm.com/blogs/bluemix/2019/03/introducing-mfa-for-ibm-cloud-users-with-federated-id/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Neues Unterstützungserlebnis für {{site.data.keyword.Bluemix_notm}}
Datum der Neuerung: 30. November 2018 
{: #support}

Mit dem Support Center können Sie alle Probleme im Zusammenhang mit {{site.data.keyword.Bluemix_notm}} lösen. Auf der Zielseite finden Sie häufig gestellte Fragen (FAQs), sodass Sie die Antwort auf Ihre Frage finden können, ohne sich dazu überhaupt mit {{site.data.keyword.Bluemix_notm}} in Verbindung setzen zu müssen. Sie können auch mit einem Live-Supportmitarbeiter chatten. Ihre Fälle können jetzt von einem einzigen Ort aus verwaltet werden. Rufen Sie **Support** &gt; **Fälle verwalten** auf, um Fälle zu erstellen, anzuzeigen, oder zu bearbeiten.

Sie können die [Statusseite](https://cloud.ibm.com/status){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") ebenfalls über das Support Center suchen. Die Seite wurde funktional so erweitert, dass sie alle ungeplanten Vorfälle, geplante Wartungsmaßnahmen, Ankündigungen und Sicherheitsbulletinbenachrichtigungen in Bezug auf bedeutende Ereignisse enthält, die die {{site.data.keyword.Bluemix_notm}}-Plattform, die Infrastruktur und die wichtigsten Services betreffen. Klicken Sie im Support Center auf **Cloudstatus anzeigen**. Um das neue Erlebnis kennenzulernen, melden Sie sich an und wechseln Sie zum [Support-Center](https://cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link"). 

### Einheitliche Anmeldung, API-Schlüssel sowie Benutzer-und Zugriffsverwaltung in {{site.data.keyword.Bluemix_notm}}
Datum der Neuerung: 30. November 2018
{: #useraccess}

Mit unseren neuesten Aktualisierungen können Sie die Vorteile einer vereinfachten sicheren Anmeldung nutzen, die allen Benutzern unabhängig von ihrem ID-Typ zur Verfügung ist. Unabhängig davon, ob Sie über eine IBMid oder eine SoftLayer-ID verfügen, können Sie sich von der funktional erweiterten Anmeldeseite schnell bei der {{site.data.keyword.Bluemix_notm}}-Konsole anmelden. Sie können auch sichere API-Aufrufe in {{site.data.keyword.Bluemix_notm}} tätigen und Ihre CLI-Anmeldung durch die Verwendung eines IAM-API-Schlüssels oder eines IAM-Zugriffstokens automatisieren. 

Nachdem Sie sich angemeldet haben, werden in der IAM-Benutzerschnittstelle (UI) auf der Seite 'Benutzer' jetzt alle Benutzer einschließlich der Benutzer der Plattform und der klassischen Infrastruktur angezeigt. Abhängig von Ihrem Zugriff für die Anzeige anderer Benutzer im Konto können Sie Ihre Ansicht rasch nach Kontobenutzern, Benutzern der klassischen Infrastruktur oder Cloud Foundry-Organisation filtern. Mit diesen Filtern können Sie Benutzer auch schnell nach Name, E-Mail-Adresse oder Status suchen.

Nachdem sich nun alle Ihre Benutzer in einer einzigen Konsole befinden, können Sie ihren Zugriff auf alle Typen von Ressourcen von demselben Ort aus verwalten. Der Zugriff beginnt beim Benutzer. Beginnen Sie also mit der Auswahl eines Benutzers aus Ihrer Liste. Abhängig von der Art der Ressource, der Sie Zugriff zuweisen wollen, können Sie zwischen IAM-Zugriffsrichtlinien, Cloud Foundry-Zugriff oder klassischen Infrastrukturberechtigungen auswählen. Wenn Sie einfach nur IAM-Zugriffsrichtlinien zuweisen möchten, erstellen Sie eine Zugriffsgruppe, um Ihren Zugriffsverwaltungsprozess zu optimieren, indem Sie alle Benutzer, denen dieselben Richtlinien zugewiesen werden müssen, zu derselben Zugriffsgruppe hinzufügen.

Weitere Details enthält der Blogbeitrag [Outstanding User Access Improvements Help Deliver a Unified {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/ibm-cloud-access-management){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link"). 

### Gesamte Dokumentation für das Plug-in der {{site.data.keyword.Bluemix_notm}}-CLI befindet sich jetzt an einem Ort
Datum der Neuerung: 30. November 2018
{: #cli}

Sie können jetzt an einem Ort auf die gesamte Dokumentation des Plug-ins für die {{site.data.keyword.Bluemix_notm}}-CLI zugreifen, wodurch es einfacher wird, einen beliebigen CLI-Befehl, den Sie suchen, auf der {{site.data.keyword.Bluemix_notm}}-Plattform zu finden. Lesen Sie hierzu in der [CLI-Dokumentation](/docs/cli?topic=cloud-cli-ibmcloud-cli) den Abschnitt 'Referenzen'.

### Sehen Sie sich das neue Dashboard und die neue Ressourcenliste an
Datum der Neuerung: 30. November 2018
{: #dash}

Mit der neuesten Aktualisierung können Sie jetzt alle Ihre Plattform- und Infrastrukturservices von einem zentralen Ort aus anzeigen. Wenn Sie sich anmelden, können Sie das neue Dashboard sofort genauer in Augenschein nehmen. Nachdem Sie Ressourcen aus dem Katalog zu Ihrem Konto hinzugefügt haben, können Sie anhand der Ressourcenliste eine vollständige Ansicht der Kontoressourcen abrufen :

* Das Dashboard wurde neu gestaltet, sodass Sie eine Zusammenfassung Ihrer Ressourcen, Ihrer Wartung, des Status, der Apps, des Supports, der Nutzung (Belegung) und der Benutzer anzeigen können.
* Weitere Details zu Ihren Ressourcen finden Sie in der Ressourcenliste. Sie können Ihre Ressourcen mit Tags kennzeichnen, um sie zu organisieren, oder Sie können sie auswählen, um auf der Detailseite Änderungen vorzunehmen.
* Da alle Ihre Ressourcen nun an einem Ort angezeigt werden, wurde eine globale Suche hinzugefügt, sodass Sie Ressourcen, die Sie erstellt haben und die auf der Seite 'Ressourcenliste' erwartungsgemäß angezeigt werden müssten, rasch ausfindig machen können. 
* Sie können auch nach Katalogergebnissen suchen, um rasch Ressourcen zu finden, die Sie zu Ihrem Konto hinzufügen können.  

Weitere Details enthält der Blogbeitrag [Manage All Your Cloud Resources on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/manage-all-your-cloud-resources-on-the-enhanced-ibm-cloud-platform/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Vereinheitlichte Konto-, Abrechnungs- und Benutzerprofilinformationen für Plattform- und Infrastrukturservices
Datum der Neuerung: 30. November 2018
{: #profile}

Ihre Konto-, Abrechnungs- und Profilinformationen wurden vereinfacht. Sie können die Kontoinformationen für alle Ihre Plattform- und Infrastrukturressourcen nun in einer einheitlichen Konsole anzeigen. 

* Ihr Profil- und Einstellungsbereich enthält Informationen zu Ihnen sowie Ihre Vorgaben für E-Mail-Benachrichtigungen für alle Ressourcentypen. 
* Ihr Kontoinformationsbereich enthält Informationen zu Ihrem Unternehmen oder Ihrer Organisation, Kontoeinstellungen und Schnellzugriff für das Arbeiten mit Ressourcengruppen und Cloud Foundry-Organisationen. Hier finden Sie sogar Leitfäden für den Schnelleinstieg, die Ihnen dabei helfen sollen, möglichst rasch durchzustarten.
* Der Abrechnungs- und Nutzungsbereich Ihres Kontos hilft Ihnen, Ihre Rechnung zu verstehen, Zahlungen vorzunehmen, Abonnements zu überwachen, Angebote einzuholen, Bestellungen zu verfolgen und Benachrichtigungen über Ausgaben festzulegen.

Weitere Details enthält der Blogbeitrag [Bringing It All Together: A Single Account and Billing Management Experience](https://www.ibm.com/blogs/bluemix/2018/11/ibm-cloud-account-management/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Organisieren von Ressourcen mit Tags
Datum der Neuerung: 30. November 2018
{: #tag}

Es stehen jetzt Tags zur Verfügung, die Sie zu Ihren Ressourcen hinzufügen können, wie z. B. Cloud Object Storage. Diese Tags helfen Ihnen bei der Verwaltung von Ressourcen und vereinfachen die Suche nach denjenigen, die für Sie die höchste Relevanz besitzen. Wenn Sie zum Beispiel über Hunderte von Ressourcen verfügen und zwischen einigen wenigen unterscheiden möchten, die auf dieselbe Weise bezahlt werden, könnten Sie sie mit `kostenstelle:standort01` kennzeichnen. Wenn ein Team wiederholt an bestimmten Ressourcen arbeitet, könnten Sie etwas wie `blaues-team` verwenden. Sie können Ihre Ressourcenliste auch nach Tags filtern, um die benötigten Ressourcen rasch zu organisieren und zu finden. Weitere Informationen finden Sie im Abschnitt [Mit Tags arbeiten](/docs/resources?topic=resources-tag) und im Blogbeitrag [Platform Tagging on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/platform-tagging-on-the-enhanced-ibm-cloud-platform/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link"). 

### Genaue monatliche Kosten mit dem Kostenschätzer suchen
Datum der Neuerung: 30. November 2018
{: #cost-estimator}

Um zu entscheiden und zu analysieren, welche Services Sie kaufen möchten, können Sie den Kostenschätzer verwenden. Sie können jetzt über die Konsole jeweils die Services auswählen, die Sie gerne nutzen würden, und alle Kosten in einem benutzerfreundlichen Tool hinzufügen. Es ist sogar möglich, projizierte Datennutzungen, Suchvorgänge pro Sekunde, Schreibvorgänge pro Sekunde und Abfragen pro Sekunde einzugeben, um eine genauere Schätzung Ihrer monatlichen Ausgaben zu erhalten. Sie können den Kostenschätzer mit jedem von Ihnen ausgewählten Katalogservice verwenden. Sie können aber auch in der Konsole auf das Symbol für den Kostenschätzer ![Symbol für Kostenschätzer](../../icons/Estimator.svg) klicken, um eine Zusammenfassung der geschätzten Kosten zu erhalten. Weitere Informationen enthält [Kosten schätzen](/docs/billing-usage?topic=billing-usage-cost).

### Aktualisierte globale Standortnamen für {{site.data.keyword.cloud_notm}}
Datum der Neuerung: 1. November 2018
{: #location-name-updates}

Im Zuge der weiteren Ausdehnung unserer globalen Verfügbarkeit durch {{site.data.keyword.cloud_notm}} aktualisieren wir unsere Standort-Benennungsstruktur, um eine verständliche, konsistente Hierarchie von Geografien, Regionen und Rechenzentren weltweit zu unterstützen. Wenn Sie mit unseren aktuellen globalen Regionen vertraut sind, werden Sie Namen wie "US South" und "Sydney" wiedererkennen. Wir richten diese Standortnamen an den Namen der Städte aus, in denen die Rechenzentren physisch existieren.

Die programmgesteuerten IDs ändern sich vorerst nicht, sodass es aus API-Perspektive keine Beeinträchtigungen gibt. Die folgende Tabelle enthält eine Zusammenfassung der bisherigen und der neuen Standortnamen. Weitere Informationen und eine umfassende Liste der Rechenzentren und Regionen finden Sie unter [Serviceverfügbarkeit](/docs/resources?topic=resources-services_region).

| Bisheriger angezeigter Standortname | Neuer angezeigter Standortname | Code |
|----------|---------|---------|
| Vereinigte Staaten (Süden) | Dallas | us-south | 
| Vereinigte Staaten (Osten) | Washington DC | us-east |
| Vereintes Königreich | London | eu-gb |
| Deutschland | Frankfurt | eu-de |
| Sydney | Sydney | au-syd |
| Asiatisch-pazifischer Raum (Norden) | Tokio | jp-tok |
{: caption="Tabelle 1. Neue Standortnamen" caption-side="top"}

### Zugriff auf Kontoverwaltung zuweisen
Datum der Neuerung: 30. Oktober 2018
{: #acct-mgmt-services}

Mit {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM) können Sie allgemeine Tasks, die Sie als Kontoadministrator auszuführen haben, an andere Benutzer in Ihrem Konto delegieren. Indem Sie eine Zugriffsrichtlinie für einen oder alle verfügbaren Kontoverwaltungsservices erstellen, können Sie ohne großen Aufwand Verantwortlichkeiten wie das Einladen und Entfernen von Benutzern, die Verwaltung von Zugriffsgruppen und von Service-IDs, die Pflege privater Katalogservices und auch die Überwachung von Abrechnungen und Aufzeichnung der Nutzung delegieren. Es gibt vier verschiedene Kontoverwaltungsservices sowie eine Option für alle Services, die Sie zum Festlegen von Zugriffsrichtlinien verwenden können:

* Benutzerverwaltung zum Einladen und Entfernen von Benutzern
* IAM-Zugriffsgruppen zum Erstellen, Bearbeiten, Löschen, Aktualisieren und Zuweisen des Zugriffs 
* IAM Identity Service zum Anzeigen, Erstellen, Löschen und Zuweisen des Zugriffs auf Service-IDs und zugeordnete API-Schlüssel im ganzen Konto
* Globaler Ressourcenkatalog zum Anzeigen von privaten Katalogangeboten und Aktualisieren der Metadaten und Sichtbarkeit für die Angebote
* Alle Kontoverwaltungsservices für den Zugriff auf die einzelnen Kontoverwaltungsserviceoptionen, je nach zugewiesener Rolle, sowie Zugriff auf die Abrechnungs- und Nutzungsverfolgung.

Weitere Informationen zu den Tasks, die ein Benutzer ausführen kann, je nachdem, für welchen Kontoverwaltungsservice er eine Richtlinie besitzt und welche Rolle ihm zugewiesen ist, finden Sie im Abschnitt [Beispiele zu Plattformmanagementrollen und Aktionen für Kontoverwaltungsservices](/docs/iam?topic=iam-userroles#platformrolestable2). Weitere Informationen zu diesem neuen Feature finden Sie unter dem Blogbeitrag [Introducing More Flexibility and Control for IBM Cloud Account Management Services Access](https://www.ibm.com/blogs/bluemix/2018/11/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link"). 

### Nach Ressourcen suchen
Datum der Neuerung: 17. Juli 2018
{: #forward-slash-key}

Sie können von der gesamten {{site.data.keyword.cloud_notm}}-Konsole aus nach Ressourcen suchen. Geben Sie den Namen einer Ressource in das Suchfeld in der Menüleiste der Konsole ein. Aktivieren Sie die Suche durch Drücken der Schrägstrichtaste (/).

### Föderierte Benutzer dynamisch zu Zugriffsgruppen hinzufügen
Datum der Neuerung: 12. Juli 2018
{: #add-fed-users}

Sie können dynamische Regeln erstellen, um föderierte Benutzer auf der Basis bestimmter Identitätsattribute automatisch zu Zugriffsgruppen hinzuzufügen. Wenn sich Benutzer mit einer föderierten IUD anmelden, werden die vom Identitätsprovider bereitgestellten Daten dazu verwendet, die Benutzer auf der Basis der von Ihnen festgelegten Regeln dynamisch einer Zugriffsgruppe zuzuordnen. Weitere Informationen finden Sie in [Dynamische Regeln für Zugriffsgruppe erstellen](/docs/iam?topic=iam-rules).

### Service-IDs und API-Schlüssel schützen
Datum der Neuerung: 01 Juni 2018
{: #protect-svcid-apikey}

Damit eine Situation vermieden werden kann, in der die Service-ID oder der API-Schlüssel gelöscht und so ein Ausfall oder eine Unterbrechung verursacht wird, können Sie Service-IDs und API-Schlüssel über die Benutzerschnittstelle (UI) oder die Befehlszeilenschnittstelle (CLI) sperren. Das Sperren einer Service-ID verhindert darüber hinaus, dass Zugriffsrichtlinien geändert, gelöscht oder zugewiesen werden und dass API-Schlüssel, die der Service-ID zugewiesen sind, erstellt oder gelöscht werden. Weitere Informationen finden Sie in [Service-ID sperren](/docs/iam?topic=iam-serviceidapikeys#lockkey) und [API-Schlüssel sperren](/docs/iam?topic=iam-userapikey).

### Upgrade für das Lite-Konto auf ein Abonnementkonto durchführen
Datum der Neuerung: 31. Mai 2018
{: #upgrade-lite}

Sie können nun direkt über die {{site.data.keyword.Bluemix_notm}}-Konsole ein Upgrade für Ihr Lite-Konto auf ein Abonnementkonto durchführen. Mit einem Abonnementkonto können Sie sowohl Plattform- als auch Infrastrukturangebote verwenden und Preisnachlässe nutzen, indem Sie eine monatliche Ausgabe- und Laufzeitverpflichtung vereinbaren. Darüber hinaus lassen sich durch festgelegte Abrechnungen im Rahmen eines monatlichen Zahlungsplans Überraschungen vermeiden, während Ihnen gleichzeitig die Flexibilität zur Verfügung steht, das Bestellvolumen nach Bedarf zu erhöhen oder zu reduzieren. Weitere Informationen finden Sie in [Häufig gestellte Fragen zu Abonnementkonten](/docs/billing-usage?topic=billing-usage-billusagefaqs#subs-order). 

### Neuer Markenname in der {{site.data.keyword.Bluemix_notm}}-Befehlszeilenschnittstelle
Datum der Neuerung: 15. Mai 2018
{: #cli-rebrand}

Die Befehle der {{site.data.keyword.Bluemix_notm}}-Befehlszeilenschnittstelle (CLI) wurden von **`bluemix`** und **`bx`** in **`ibmcloud`** geändert. Sie können die CLI-Befehle **`bluemix`** und **`bx`** jedoch weiterhin verwenden, bis sie zu einem späteren Zeitpunkt entfernt werden. Eine Abkürzung des neuen Befehls gibt es jetzt nicht. Daher muss der vollständige Name **`ibmcloud`** verwendet werden. 

### Mehrfaktorauthentifizierung für Ihr {{site.data.keyword.Bluemix_notm}}-Konto
Datum der Neuerung: 02. Mai 2018
{: #account-mfa}

Durch die Mehrfaktorauthentifizierung (MFA) wird eine zusätzliche Sicherheitsebene zu Ihrem Konto hinzugefügt, denn Benutzer müssen bei der Anmeldung neben ihrer Standard-IBMid und ihrem Kennwort zusätzlich einen zeitbasierten einmaligen Kenncode eingeben. Dies wird gängigerweise auch als Zwei-Faktor-Authentifizierung (2FA) bezeichnet. Mehrfaktorauthentifizierung wird pro Konto aktiviert und alle Benutzer in dem Konto müssen sich unter Verwendung der zusätzlichen Sicherheitsmaßnahme anmelden. Weitere Informationen finden Sie im Blogbeitrag [IBM Cloud Platform now adds support for Multi-Factor Authentication](https://www.ibm.com/blogs/bluemix/2018/05/ibm-cloud-platform-now-adds-support-multi-factor-authentication/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Mit Zugriffsgruppen schnellen Zugriff zuweisen
Datum der Neuerung: 03. April 2018
{: #access-groups}

Wollen Sie in der Lage sein, schnell Zugriff zuzuweisen, indem Sie die kleinstmögliche Anzahl an Richtlinien verwenden? Das ist nun mithilfe von Zugriffsgruppen möglich. Mit Zugriffsgruppen können Sie eine Gruppe von Benutzern und Service-IDs gruppieren und eine einzige Richtlinie zuweisen, die für alle Mitglieder der Gruppe gilt. Durch die Verwendung von Zugriffsgruppen können Sie den Zeitaufwand für die Verwaltung des Zugriffs auf die Benutzer und Service-IDs in Ihrem Konto begrenzen. Weitere Details finden Sie im Blogbeitrag [New feature: Access groups](https://www.ibm.com/blogs/bluemix/2018/04/access-groups/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### {{site.data.keyword.Bluemix_notm}} Foundry-Service jetzt für Region 'Vereinigte Staaten (Osten)' verfügbar
Datum der Neuerung: 15. Dezember 2017
{: #cf-useast}

In Washington, D.C. ist jetzt ein neues Rechenzentrum für die Region 'Vereinigte Staaten (Osten)' verfügbar. Diese neue Region ist über den Endpunkt `us-east.cloud.ibm.com` erreichbar. Details über die gebührenpflichtigen Services, die in dieser neuen Region angeboten werden, finden Sie unter [Services nach Region](/docs/resources?topic=resources-services_region).

### Unterstützung für Ressourcen in der Europäischen Union
Datum der Neuerung: 14. Dezember 2017
{: #eu-resources}

Falls sich Ihre Services und Rechenzentren in Europa befinden, bietet {{site.data.keyword.Bluemix_notm}} jetzt ein spezielles Leistungsspektrum für den Schutz Ihrer Daten in der Europäischen Union. Sie können anfordern, dass der Support für Sie von Kundenunterstützungsteams bereitgestellt wird, die sich in Europa befinden. Dieser Support ist täglich rund um die Uhr verfügbar. Weitere Informationen finden Sie in den Abschnitten [Option 'Unterstützung in der EU' aktivieren](/docs/account?topic=account-eu-hipaa-supported#bill_eusupported) und [Unterstützung für Ressourcen in der EU anfordern](/docs/get-support?topic=get-support-getting-customer-support#eusupported).

### Unterstützung für TLS 1.0 und 1.1 wird eingestellt
Datum der Neuerung: 28. Dezember 2017
{: #nosupport-tls}

{{site.data.keyword.Bluemix_notm}} stellt die Unterstützung für TLS 1.0 und TLS 1.1 bei vielen Cloud-Produkten und -Services am 1. März 2018 ein. Weitere Informationen zu den Auswirkungen dieser Änderung und zu den Maßnahmen, die Sie möglicherweise ergreifen müssen, finden Sie unter [Unterstützung für TLS 1.0 und 1.1 wird eingestellt](/docs/get-support?topic=get-support-tlssupportwithdraw).

### Neue Organisationsmöglichkeit für Ressourcen in Ihrem Konto
Datum der Neuerung: 16. November 2017
{: #usergs}

Ressourcengruppen sind eine neue Möglichkeit für Sie, anpassbare Gruppierungen von Kontoressourcen zu erstellen; der Zugriff auf die Gruppe und die darin enthaltenen Ressourcen wird mithilfe von Identity and Access Management (IAM) verwaltet. Für jeden Benutzer ist anfangs eine Standardressourcengruppe vorhanden. Diese Ressourcengruppe können Sie umbenennen und neue Serviceinstanzen zu ihr hinzufügen, wenn Sie diese aus dem Katalog erstellen.

Benutzer mit einem nutzungsabhängigen Konto oder einem Abonnementkonto können weitere Ressourcengruppen erstellen, um die Verwaltung von Kontingenten und die Anzeige von Abrechnung und Nutzung für ein Ressourcenset zu vereinfachen. Durch die Gruppierung von Ressourcen wird außerdem die gleichzeitige Zuweisung von Zugriffsberechtigungen für mehrere Services an die Benutzer erleichtert. Weitere Informationen zum Arbeiten mit Ressourcengruppen für Ihr Konto finden Sie unter [Ressourcengruppen verwalten](/docs/resources?topic=resources-rgs).

### Aktualisierungen für {{site.data.keyword.Bluemix_notm}} IAM
Datum der Neuerung: 16. November 2017
{: #iam-nov17}

Die Einführung von Ressourcengruppen in Ihrem {{site.data.keyword.Bluemix_notm}}-Konto bietet Ihnen ein neues Verfahren für die Zuordnung von Zugriffsberechtigungen. Benutzern und Service-IDs kann der Zugriff auf alle Services innerhalb einer Ressourcengruppe erteilt werden, wodurch Sie gleichzeitig schnell auf mehrere Ressourcen zugreifen können. Außerdem können Sie den Zugriff für jeden Benutzer oder jede Service-ID anpassen, indem Sie den Zugriff nur für einige Services in einer Ressourcengruppe ermöglichen oder indem Sie den Zugriff auf einzelne Ressourcen bis auf die Ebene der Serviceinstanz hinab festlegen. Weitere Informationen zu den Features, die Sie bei IAM nutzen können, enthält der Abschnitt [Welche Funktionen bietet IAM?](/docs/iam?topic=iam-iamoverview#features)

### Dashboardansicht anpassen
Datum der Neuerung: 16. November 2017
{: #custom-dash}

Sie können alle Ressourcen in Ihrem Konto im Dashboard der {{site.data.keyword.Bluemix_notm}}-Konsole anzeigen und verwalten. Außerdem können Sie künftig Filter festlegen, um die Ansicht anzupassen. Beispielsweise können Sie eine Filterung nach Ressourcengruppe vornehmen, um die speziellen Ressourcen in einer Ressourcengruppe anzuzeigen. Auch eine Filterung nach Region oder Cloud Foundry-Bereich ist möglich. Weitere Details finden Sie unter [Ressourcen im Dashboard verwalten](/docs/overview?topic=overview-ui#dashboardview).

### Support Center
Datum der Neuerung: 2. November 2017
{: #support-nov17}

Im neuen Support Center können Sie nach Informationen suchen, Fragen an die Entwickler-Community stellen und Tickets verwalten. Navigieren Sie in der Menüleiste der {{site.data.keyword.Bluemix_notm}}-Konsole zu **Support > Support Center**.

### Einführung von IBM Cloud
Datum der Neuerung: 31. Oktober 2017
{: #meet-ibmcloud}

Bluemix heißt jetzt IBM Cloud. Außer dem Namen ändert sich nichts. Sie können Ihre Apps und Services weiterhin wie gewohnt ohne großen Aufwand erstellen und ausführen. Weitere Details finden Sie im [IBM Cloud-Blog](https://www.ibm.com/blogs/bluemix/2017/10/bluemix-is-now-ibm-cloud/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Lite-Konto
Datum der Neuerung: 31. Oktober 2017
{: #new-liteacct}

Mit dem neuen Typ des Lite-Kontos können Sie ausgewählte Services kostenfrei und ohne Zeitbegrenzung ausprobieren. Dieses neue Konto umfasst darüber hinaus Nutzungsüberwachungs- und Effizienzfunktionen, die eine bessere Verwaltung Ihrer Ressourcen fördern. Mehr über die verfügbaren Funktionen finden Sie unter [Kontotypen](/docs/account?topic=account-accounts#liteaccount).

### Funktion 'Identity and Access Management' für Anwendungsauthentifizierung
Datum der Neuerung: 6. Oktober 2017
{: #app-authfeature}

Identity and Access Management (IAM) bietet jetzt die Möglichkeit der Erstellung einer Service-ID, die eine Art Identität darstellt, mit der sich Apps bei Ihren {{site.data.keyword.Bluemix_notm}}-Services authentifizieren können. Anstelle der Verwendung von einzelnen Benutzerberechtigungsnachweisen kann eine Service-ID mit einem zugeordneten API-Schlüssel und Zugriffsberechtigungen in Form einer Servicerichtlinie erstellt werden, die der Service-ID zugeordnet wird, damit Sie die Zugriffsebene für jede Anwendung steuern können, die sich mit dieser ID authentifiziert.

Weitere Informationen zu den Vorzügen dieser Funktion und zu ihrer Verwendung enthält der Blogbeitrag [Introducing IBM Cloud IAM Service IDs and API Keys](https://www.ibm.com/blogs/bluemix/2017/10/introducing-ibm-cloud-iam-service-ids-api-keys/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Globaler {{site.data.keyword.Bluemix_notm}}-Katalog
Datum der Neuerung: 27. Juli 2017
{: #gc}

Als Erweiterung der letzten Konsolenaktualisierung für die Verwaltung Ihrer öffentlichen Regionen an einer zentralen Stelle in der Konsole gibt es in {{site.data.keyword.Bluemix_notm}} jetzt einen globalen Katalog, der die Auswahl von Elementen im Katalog und ihre Bereitstellung optimiert. Ungeachtet der Region, die Sie in der Konsole ausgewählt haben, werden jetzt alle Services angezeigt, die in allen öffentlichen Regionen aus Ihrem Katalog verfügbar sind. Sobald Sie eine Kachel im Katalog auswählen, können Sie feststellen, in welchen Regionen der Service verfügbar ist, und auswählen, wo Sie den Service bereitstellen wollen. Weitere Informationen zu den neuesten Aktualisierungen des Katalogs enthält der Blogbeitrag [A global {{site.data.keyword.Bluemix_notm}} catalog makes building things easier](https://www.ibm.com/blogs/bluemix/2017/07/global-bluemix-catalog-makes-building-things-easier/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Aktualisierungen der {{site.data.keyword.Bluemix_notm}}-Konsole
Datum der Neuerung: 23. Mai 2017
{: #console-may17}

Sie können Ihre öffentlichen Regionen ab sofort an einer zentralen Stelle in der aktualisierten {{site.data.keyword.Bluemix_notm}}-Konsole verwalten. Der Regionsselektor ermöglicht Ihnen einen optimierten Zugriff auf Ihre Ressourcen; zu den weiteren Verbesserungen gehören eine höhere Verfügbarkeit und eine gesteigerte Leistung. Weitere Informationen enthält der Blogbeitrag [New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Identity and Access Management
Datum der Neuerung: 1. Mai 2017
{: #iam-may17}

Durch die neuesten Aktualisierungen und Verbesserungen können Eigner oder Administratoren von {{site.data.keyword.Bluemix_notm}}-Konten jetzt eine einheitliche Benutzerschnittstelle für die Zugriffssteuerung verwenden und hierdurch die folgende Funktionalität nutzen:
 * Differenzierten Benutzerzugriff auf Kubernetes-Services und andere Services verwalten, sobald diese die neuen Zugriffssteuerungsfunktionen annehmen
 * Servicerichtlinien und Cloud Foundry-Rollen zu Benutzern in ihren Organisationen zuordnen

Des Weiteren können Benutzer der {{site.data.keyword.Bluemix_notm}}-Plattform API-Schlüssel, die ihren Benutzer-IDs zugeordnet sind, erstellen, löschen und auflisten, sowie diese API-Schlüssel bei Verwendung von APIs oder CLIs zur Authentifizierung verwenden.

Zu guter Letzt wurde die einheitliche Benutzermanagementfunktion erweitert, damit bei einem verknüpften IaaS-PaaS-Konto die einheitliche Verwaltung von Benutzern möglich ist, ohne dass Benutzer separat im SoftLayer-Kundenportal oder der {{site.data.keyword.Bluemix_notm}}-Konsole hinzugefügt werden müssen.

Weitere Informationen können Sie dem Blogbeitrag [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") entnehmen.

### Geändertes Navigationsdesign für {{site.data.keyword.Bluemix_notm}}-Dokumente
Datum der Neuerung: 13. April 2017
{: #docnavupdates}

Diese aktualisierte Navigation verfolgt den Zweck, die Organisation des Inhalts in den Dokumenten besser verständlich zu machen und eine effizientere Suche nach relevantem Inhalt zu ermöglichen. Dank einer geringeren Verschachtelung der Inhaltsebenen müssen Sie nicht so tief nach den Informationen graben, die Sie für die erfolgreiche Nutzung von {{site.data.keyword.Bluemix_notm}} benötigen.


