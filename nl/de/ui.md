---


copyright:
  years: 2015, 2018
lastupdated: "2018-11-28"

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}

# In der {{site.data.keyword.cloud_notm}}-Konsole navigieren 
{: #ui}

Die {{site.data.keyword.cloud}}-Konsole ist eine Benutzerschnittstelle, mit der Sie alle Ihre {{site.data.keyword.cloud_notm}}-Ressourcen verwalten können. Wenn Sie auf die [-Konsole](https://cloud.ibm.com){: new_window}  ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link") zugreifen, können Sie ein kostenfreies Konto erstellen, sich anmelden, auf die Dokumentation und den Katalog zugreifen, Preisinformationen anzeigen, Unterstützung anfordern oder den Status von {{site.data.keyword.cloud_notm}}-Komponenten überprüfen. Nachdem Sie sich angemeldet haben, enthält die Menüleiste ein Menüsymbol ![Menüsymbol](../icons/icon_hamburger.svg) und weitere Links.
{: shortdesc}


## Verwendung der Konsole
{: #consoleoptions}

Wenn Sie sich bei {{site.data.keyword.cloud_notm}} anmelden, kann als erste Seite das Dashboard angezeigt werden. Im Dashboard werden Widgets dargestellt, die den Status Ihres Kontos zusammenfassen. Als Nächstes können Sie Ihre Ressourcen verwalten. Rufen Sie das Menüsymbol ![Menüsymbol](../icons/icon_hamburger.svg) &gt; **Ressourcenliste** auf, um alle vorhandenen Ressourcen in Ihrem Konto anzuzeigen.

  * Verwenden Sie den Link **Katalog**, um neue Ressourcen zu erstellen.
  * Verwenden Sie den Link **Dokumente**, um auf hilfreiche Informationen über {{site.data.keyword.cloud_notm}} zuzugreifen.
  * Verwenden Sie den Link **Support**, unm auf das Support Center zuzugreifen.  
  * Über das Menü **Verwalten** können Sie auf Ihre Konto-, Abrechnungs- und Nutzungsoptionen sowie auf die Optionen für Identity and Access Management (IAM) zugreifen.
  * Klicken Sie auf das Symbol für den Kostenschätzer ![Symbol für Kostenschätzer](../icons/Estimator.svg), um den Kostenschätzer zu öffnen.
  * Klicken Sie auf das Benachrichtigungssymbol ![Symbol für Benachrichtigungen](../icons/Notification.svg), um auf Ankündigungen und geplante sowie ungeplante Ereignisse zuzugreifen.

## Nach Ressourcen suchen
{: #search}

Sie können von jeder beliebigen Position in der {{site.data.keyword.cloud_notm}}-Konsole nach Name oder nach Tag nach Ressourcen suchen, die Sie in der Ressourcenliste erwarten. Geben Sie den Namen einer Ressource oder einen Tag in das Suchfeld in der Menüleiste der Konsole ein. 

Weitere Informationen enthält [Nach Ressourcen suchen](/docs/resources/searching.html#searching-for-resources). 

## Ressourcen in der Ressourcenliste verwalten
{: #dashboardview}

Rufen Sie das Menüsymbol ![Menüsymbol](../icons/icon_hamburger.svg) &gt; **Ressourcenliste** auf, um auf Ihre Liste von Kontoressourcen zuzugreifen. Sie können die Ressourcenliste Dashboard verwenden, um {{site.data.keyword.cloud_notm}}-Ressourcen und Cloud Foundry-Serviceinstanzen anzuzeigen und mit ihnen zu arbeiten. Weitere Informationen zu den verschiedenen Typen von Ressourcen finden Sie in [Was ist eine Ressource?](/docs/resources/acct_resources.html#resource)

### Ressourcen anzeigen
Über die Ressourcenliste können Sie alle Ressourcen Ihres Kontos für alle Regionen anzeigen. Damti die Elemente angezeigt werden, die für Sie wichtig sind, filtern Sie Ihre Liste mit den Filtern für die einzelnen Spaltenüberschriften. Wenn Sie Ressourcen an einem bestimmten Standort anzeigen und mit diesen arbeiten möchten, erweitern Sie den Filter **Standort** und wählen Sie einen Standort aus der Liste aus.

### Mit Ressourcen arbeiten
Über die Ressourcenliste können Sie auf unterschiedliche Arten mit Ihren Ressourcen arbeiten:

  * Jede Ressource wird in einer eigenen Zeile angezeigt, an deren Ende sich ein Symbol 'Aktionen' ![Symbol 'Weitere Aktionen'](../icons/action-menu-icon.svg) befindet. Klicken Sie auf das Symbol 'Aktionen' ![Symbol 'Weitere Aktionen'](../icons/action-menu-icon.svg), um eine Ressource zu starten, zu stoppen, umzubenennen oder zu löschen.
  * Wenn Sie Berechtigungsnachweise oder Verbindungen für eine Ressource konfigurieren möchten, klicken Sie auf den Namen der Ressource, um zur Seite mit den Ressourcendetails zu navigieren. Wählen Sie dann **Serviceberechtigungsnachweise** oder **Verbindungen** aus. Weitere Informationen finden Sie unter [Berechtigungsnachweis hinzufügen](/docs/resources/service_credentials.html) und [Verbindungen verwalten](/docs/resources/connecting_apps.html#connect_app).


## Im Katalog arbeiten
{: #catalogcreate}

Wenn Sie eine Ressource erstellen möchten, klicken Sie in Ihrer Ressourcenliste auf **Erstellen**. Sie werden dann zu dem Katalog geleitet. Wenn Sie eine Kachel im Katalog auswählen, sehen Sie, wo die Ressource verfügbar ist. Nicht jede im Katalog aufgelistete Ressource ist in jeder Region verfügbar.

Nachdem Sie auf die Kachel für die Ressource geklickt haben, die Sie erstellen möchten, können Sie die Position auswählen, an der die Bereitstellung erfolgen soll.

  * Bei Cloud Foundry-Ressourcen können Sie eine bestimmte Region auswählen und dann die Organisation und den Bereich für die Serviceinstanz auswählen, die zugeordnet werden soll.
  * Für Ressourcen, die von {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM) verwaltet werden, wählen Sie eine Position aus, an der die Bereitstellung durchgeführt werden soll. Anschließend wählen Sie eine Ressourcengruppe aus, der die Serviceinstanz zugeordnet werden soll.
