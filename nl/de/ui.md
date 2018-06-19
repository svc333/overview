---


copyright:
  years: 2016, 2018
lastupdated: "2018-05-23"

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}

# Funktionsweise der {{site.data.keyword.cloud_notm}}-Konsole
{: #ui}

Die {{site.data.keyword.cloud}}-Konsole ist eine Benutzerschnittstelle, mit der Sie alle Ihre {{site.data.keyword.cloud_notm}}-Ressourcen verwalten können. Wenn Sie auf die [-Konsole](https://console.bluemix.net){: new_window}  ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link") zugreifen, können Sie ein kostenloses Konto erstellen, sich anmelden, auf die Dokumentation und den Katalog zugreifen, Preisinformationen anzeigen, Unterstützung anfordern oder den Status aller {{site.data.keyword.cloud_notm}}-Komponenten überprüfen. Nachdem Sie sich angemeldet haben, enthält die Menüleiste ein Menüsymbol ![Menüsymbol](../icons/icon_hamburger.svg) und zusätzliche Links, abhängig von Ihrem Kontotyp.
{: shortdesc}

## Verwendung der Konsole
{: #consoleoptions}

Wenn Sie ein bereits bestehender Benutzer mit einem {{site.data.keyword.cloud_notm}}-Konto sind, können Sie das Menüsymbol ![Menüsymbol](../icons/icon_hamburger.svg) verwenden, um auf alle vorhandenen Ressourcen in Ihrem Dashboard zuzugreifen.
  * Verwenden Sie den Link **Katalog**, um neue Ressourcen zu erstellen.
  * Verwenden Sie den Link **Dokumente**, um auf hilfreiche Informationen über {{site.data.keyword.cloud_notm}} zuzugreifen.
  * Über das Menü **Support** können Sie auf Informationen zu den Neuerungen in {{site.data.keyword.cloud_notm}}, das Support Center, Optionen zum Hinzufügen und Anzeigen von Tickets und auf die Seite 'Status' zugreifen.
  * Über das Menü **Verwalten** können Sie auf Ihre Konto-, Abrechnungs- und Nutzungs- sowie Sicherheitsoptionen zugreifen.

Wenn Sie Ihre {{site.data.keyword.cloud_notm}}- und SoftLayer-Konten verknüpft haben, haben Sie dieselben Optionen, die auch ein Eigner von nicht verknüpften Konten hat. Außerdem können Sie zum Kundenportal navigieren, indem Sie die Option **Menüsymbol![Menüsymbol](../icons/icon_hamburger.svg) > Infrastruktur** auswählen. Von hier aus können Sie Ihre Kontozusammenfassung anzeigen, Speicher und Geräte bestellen und den Zugriff für Benutzer und Geräte verwalten, die nur VPN nutzen.

## Ressourcen im Dashboard verwalten
{: #dashboardview}

Sie können das Dashboard verwenden, um {{site.data.keyword.cloud_notm}}-Ressourcen und Cloud Foundry-Serviceinstanzen anzuzeigen und mit ihnen zu arbeiten. Weitere Informationen zu Ressourcen finden Sie in [Was ist eine Ressource?](/docs/resources/acct_resources.html#resource).

### Ressourcen anzeigen

Sie können alle Ressourcen in Ihrem Konto im Dashboard anzeigen. Verwenden Sie die folgenden Optionen, um Ihre Ansicht anzupassen:

  * Wenn Sie Ressourcen in einer bestimmten Ressourcengruppe anzeigen möchten, wählen Sie in der Liste **Ressourcengruppe** eine Ressourcengruppe aus.
  * Wenn Sie Ressourcen in einer bestimmten Cloud Foundry-Organisation anzeigen möchten, wählen Sie in der Liste **Cloud Foundry-Organisation** eine Organisation aus.

Anschließend können Sie basierend auf den von Ihnen ausgewählten Elementen nach den folgenden Optionen filtern:

  * Region
  * Cloud Foundry-Bereich

### Mit Ressourcen arbeiten

Sie können über das Dashboard auf unterschiedliche Art und Weise mit Ihren Ressourcen arbeiten:

  * Jede Ressource wird in einer eigenen Zeile angezeigt und am Ende der Zeile befindet sich ein Symbol 'Weitere Aktionen' ![Symbol 'Weitere Aktionen'](../icons/overflow-menu.svg). Klicken Sie auf das Symbol 'Weitere Aktionen', um eine Ressource zu starten, zu stoppen, umzubenennen oder zu löschen.
  * Wenn Sie Berechtigungsnachweise oder Verbindungen für eine Ressource konfigurieren möchten, klicken Sie auf den Namen der Ressource, um zur Seite mit den Ressourcendetails zu navigieren. Weitere Informationen finden Sie unter [Neuen Berechtigungsnachweis hinzufügen](/docs/resources/service_credentials.html) und [Verbindungen verwalten](/docs/resources/connecting_apps.html#connect_app).

## Im Katalog arbeiten
{: #catalogcreate}

Wenn Sie eine neue Ressource erstellen möchten, klicken Sie in Ihrem Dashboard auf **Ressource erstellen**. Sie werden dann zu dem Katalog geleitet. Wenn Sie eine Kachel im Katalog auswählen, sehen Sie, wo die Ressource verfügbar ist. Nicht jede im Katalog aufgelistete Ressource ist in jeder Region verfügbar.

Nachdem Sie auf die Kachel für die Ressource geklickt haben, die Sie erstellen möchten, können Sie die Position auswählen, an der die Bereitstellung erfolgen soll.

  * Bei Cloud Foundry-Ressourcen können Sie eine bestimmte Region auswählen und dann die Organisation und den Bereich für die Serviceinstanz auswählen, die zugeordnet werden soll.
  * Für Ressourcen, die von {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM) verwaltet werden, wählen Sie eine Position aus, an der die Bereitstellung durchgeführt werden soll. Anschließend wählen Sie eine Ressourcengruppe aus, der die Serviceinstanz zugeordnet werden soll.
