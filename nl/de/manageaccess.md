---

copyright:

  years: 2017, 2018

lastupdated: "2018-04-12"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# Zugriff in {{site.data.keyword.Bluemix_notm}} verwalten
{: #cloudaccess}

## Was ist Zugriffsmanagement?

Über das Zugriffsmanagement können Sie steuern, welche Benutzer Ressourcen in Ihrem Konto anzeigen, erstellen, verwenden und verwalten können. Um Zugriff zu erteilen, können Sie Rollen zuordnen, die den Benutzern auf verschiedenen Ebenen Zugriff für die Ausführung von Plattformverwaltungstasks und Zugriff auf Kontoressourcen ermöglichen.

Die Art und Weise, wie der Zugriff in {{site.data.keyword.Bluemix_notm}} verwaltet wird, hängt vom Typ der Ressource ab, für die Sie den Zugriff zuordnen möchten. {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) ist das Zugriffsmanagementsystem für die konsistente Verwaltung von Ressourcen über die gesamte {{site.data.keyword.Bluemix_notm}}-Plattform. {{site.data.keyword.Bluemix_notm}}-Infrastruktur- und Cloud Foundry-Ressourcen werden nicht mit Cloud IAM verwaltet. Diese Ressourcentypen verfügen über eigene Zugriffsmanagementsysteme. Wenn Sie eine Kombination verschiedener Ressourcentypen haben, verwalten Sie jeden Typ separat. Um den [Zugriff auf Ihre Infrastrukturressourcen zu ermöglichen](/docs/iam/infrastructureaccess.html#infrapermission), legen Sie Berechtigungen in Ihrem SoftLayer-Konto fest. Um den [Zugriff auf Cloud Foundry-Ressourcen zu ermöglichen](/docs/iam/cfaccess.html#cfaccess), verwenden Sie die Option "Anhand Cloud Foundry zuweisen" im Abschnitt "Identität und Zugriff" der Konsole.

## Wer ist für das Zugriffsmanagement berechtigt?

Als Kontoeigner können Sie den Zugriff auf alle Ressourcen in Ihrem Konto verwalten. Sie können die Task zum Verwalten des Zugriffs auf Plattformressourcen auch delegieren, indem Sie einem Benutzer in Ihrem Konto die Administratorrolle für alle Services zuordnen.

Wenn Sie über Cloud Foundry-Services in Ihrem Konto verfügen, können Sie einem anderen Benutzer die Rolle 'Organisationsmanager' oder 'Bereichsmanager' zuordnen, damit er Benutzer hinzufügen und Cloud Foundry-Benutzerrollen für den Zugriff auf Instanzen in der Organisation oder dem Bereich zuweisen kann, die/den sie verwalten.


## Wie beginne ich mit dem Zugriffsmanagement?

Wechseln Sie zu **Verwalten** &gt; **Sicherheit** &gt; **Identität und Zugriff** und wählen Sie dann  **Benutzer** aus, um die Verwaltung des Zugriffs für Benutzer in Ihrem Konto zu starten. Wählen Sie zunächst einen Benutzer aus der Liste aus. Sie sehen nur die Zugriffsmanagementoptionen, für die Sie eine Berechtigung haben. Wenn Sie z. B. nicht der Kontoeigner und kein Organisations- oder Bereichsmanager sind, wird die Option zum Verwalten des Cloud Foundry-Zugriffs nicht angezeigt.

Zugriffsrollen können auch Apps und Services zugeordnet werden, indem Service-IDs verwendet werden. Rufen Sie dazu die Seite **Service-IDs** auf. Weitere Informationen zum schnellen Einstieg in Cloud IAM finden Sie in den Schritten im [Lernprogramm 'Einführung'](/docs/iam/quickstart.html#getstarted).
