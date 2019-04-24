---

copyright:

  years: 2018, 2019

lastupdated: "2019-01-02"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# Konto einrichten
{: #quickstart_acc_ad}

Diese Kurzanleitung soll Kontoadministratoren beim Einrichten ihrer {{site.data.keyword.Bluemix}}-Umgebung unterstützen. 
{:shortdesc}

1. Erstellen Sie Ressourcengruppen, die zum Organisieren der aus dem {{site.data.keyword.Bluemix_notm}}-Katalog erstellten Ressourcen verwendet werden sollen. Weitere Informationen finden Sie in [Bewährte Verfahren für die Organisation von Ressourcen in Ressourcengruppen](/docs/resources/bestpractice_rgs.html#bp_resourcegroups).

  Es ist wichtig, dies frühzeitig zu tun, denn wenn Sie einer Ressourcengruppe erst einmal eine Ressource zugewiesen haben, kann diese nicht mehr verschoben werden.
  {:tip}
  
2. Da nicht alle Services von {{site.data.keyword.Bluemix_notm}} verwaltet werden, müssen Sie Ihre Cloud Foundry-Organisation erstellen, um diese Services zu organisieren und ihnen Zugriff zu erteilen. Mit einem Lite-Konto erhalten Sie eine Cloud Foundry-Organisation an einem {{site.data.keyword.Bluemix_notm}}-Standort. Weitere Informationen finden Sie in [Organisationen und Bereiche hinzufügen](/docs/account/orgs_spaces.html#orgsspacesusers). 
3. Erstellen Sie Zugriffsgruppen, um Benutzer und Service-IDs in Gruppen zu organisieren, denen die dieselbe Zugriffsebene zugewiesen werden muss. Weitere Informationen finden Sie in [Zugriffsgruppen einrichten](/docs/iam/groups.html#groups).
4. Laden Sie Benutzer zum Konto ein und fügen Sie sie zu Zugriffsgruppen hinzu, um den erforderlichen Zugriff zu erteilen, den Ihre Kontobenutzer benötigen, um mit der Erstellung zu beginnen. Weitere Informationen enthält das [Lernprogramm 'Einführung' für IAM](/docs/iam/quickstart.html#getstarted).
5. Richten Sie Benachrichtigungen für Ereignisse und Kontoausgabenlimits ein. Weitere Informationen finden Sie in [E-Mail-Vorgaben festlegen](/docs/account/email.html) und [Ausgabebenachrichtigungen einstellen](/docs/billing-usage/notifications.html). 
6. Nutzen Sie den Kostenschätzer, um sich einen Eindruck davon zu verschaffen, wie viel Ihre Umgebung kosten könnte. Klicken Sie in der Menüleiste der Konsole auf das Symbol für den Kostenschätzer ![Symbol für Kostenschätzer](../icons/Estimator.svg). 
7. Nutzen Sie den Kostenschätzer, um sich einen Eindruck davon zu verschaffen, wie viel Ihre Infrastruktur kosten könnte. 
  
  a. Beginnen Sie mit der Auswahl eines Angebots aus dem [Katalog](https://cloud.ibm.com/catalog){: new_window} ![Symbol für externen Link](../icons/launch-glyph.svg). 
  
  b. Geben Sie die Konfigurationsdetails ein, wählen Sie Ihren Preisstrukturplan aus und klicken Sie auf **Zur Schätzung hinzufügen**.

## Nächste Schritte
{: #next-steps}

* Beginnen Sie mit der Erstellung von Services innerhalb des Kontos, damit Ihre Organisation und Ihre Entwickler die erforderlichen Lösungen erstellen können.  
* Erstellen Sie Tags und kennzeichnen Sie Ihre Ressourcen mit Tags, um die Art und Weise zu organisieren, wie Abrechnung und Nutzung angezeigt werden. Dies vereinfacht die Identifizierung von Rückbuchungen an unterschiedliche Organisationen. Weitere Informationen finden Sie in [Bewährte Verfahren zum Kennzeichnen von Ressourcen mit Tags](/docs/account/bp_account.html#tags). 
