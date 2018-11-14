---

copyright:

  years: 2018

lastupdated: "2018-11-01"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:tip: .tip}

# Standorte für die Ressourcenbereitstellung 
{: #ov_intro_reg}

Sie können Apps und Serviceinstanzen an unterschiedlichen Standorten mit derselben {{site.data.keyword.cloud_notm}}-Infrastruktur für das Anwendungsmanagement und derselben Ansicht mit Nutzungsdetails zur Gebührenabrechnung erstellen. Sie können Ihre Apps an dem Standort bereitstellen, der Ihren Kunden am nächsten ist, um eine geringe Latenzzeit zu erreichen. 

Zum Beheben von Sicherheitsproblemen können Sie auch den Standort auswählen, in dem die Anwendungsdaten aufbewahrt werden sollen. Wenn Sie Apps an mehreren Standorten erstellen, werden die Apps an den anderen Standorten weiter ausgeführt, falls ein Standort nicht mehr verfügbar ist. Die verfügbaren Ressourcen sind für jeden verwendeten Standort gleich. Weitere Informationen zu den Plattformressourcen und den Standorten, an denen sie verfügbar sind, finden Sie unter [Serviceverfügbarkeit](/docs/resources/service_region.html).

Der globale Lastausgleich für die Konsole stellt sicher, dass bei einer Inaktivität Ihres nächsten geografischen Standorts die Konsole die Informationen für den nächstgelegenen Standort anzeigt. Auf diese Weise verfügen Sie stets über Zugriff auf die Konsole, ohne dass Aktionen erforderlich sind, um auf die benötigten Informationen zuzugreifen.

<!---This is a pre-pup topic. Post pup, the dashboard will have a Location status widget, which will show geographies as a summary. This paragraph will change and we need to add a paragraph to explain the continents are a summary in the widget.-->
Über das Dashboard können Sie standardmäßig alle Ressourcen an allen Standorten anzeigen. Wenn Sie Ressourcen an einem bestimmten Standort anzeigen und mit diesen arbeiten möchten, erweitern Sie das Menü **Standort** und wählen Sie einen Standort aus der Liste aus. 

Sie können auch die Befehlszeilenschnittstelle verwenden, um eine Verbindung zu dem {{site.data.keyword.cloud_notm}}-Standort herzustellen, mit dem Sie arbeiten möchten, indem Sie den Befehl `ibmcloud api` verwenden und den API-Endpunkt des Standorts angeben. Geben Sie beispielsweise den folgenden Befehl ein, um eine Verbindung zum {{site.data.keyword.cloud_notm}}-Standort London herzustellen:

```
ibmcloud api https://api.eu-gb.bluemix.net
```

Jedem Standort wird ein eindeutiges Präfix zugewiesen. {{site.data.keyword.cloud_notm}} stellt die folgenden Standorte und Standortpräfixe zur Verfügung.

| **Standort** | **API-Endpunkt** |
|-----------------|-------------------|
| Dallas | api.us-south.bluemix.net |
| Sydney | api.au-syd.bluemix.net |
| Frankfurt | api.eu-de.bluemix.net |
| London | api.eu-gb.bluemix.net |
| Washington DC | api.us-east.bluemix.net |
| Tokio | api.jp-tok.bluemix.net |
{: caption="Tabelle 1. Liste der {{site.data.keyword.cloud_notm}}-Standorte" caption-side="top"}

Wenn Sie Infrastrukturressourcen bereitstellen, haben Sie eine größere Auswahl an Orten, an denen sich Ihr Inhalt befinden soll. Sie können einen Standort auswählen oder ein Rechenzentrum aus der Liste in {{site.data.keyword.Bluemix_notm}} auswählen. Weitere Informationen finden Sie im Abschnitt [{{site.data.keyword.cloud_notm}}Rechenzentren](data-centers.html).
