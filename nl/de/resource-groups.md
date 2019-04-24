---

copyright:
  years: 2017, 2019
lastupdated: "2019-03-14"

keywords: access control, resource groups, resource group

subcollection: overview

---

{:shortdesc: .shortdesc}

# Ressourcen in Ressourcengruppen organisieren
{: #whatis-rgs}

Ressourcengruppen bieten Ihnen die Möglichkeit, Ihre Kontoressourcen in anpassbaren Gruppierungen zu organisieren, sodass Sie den Benutzern schnell Zugriff auf mehrere Ressourcen gleichzeitig zuordnen können. Jede Kontoressource, die mit der Zugriffssteuerung von {{site.data.keyword.Bluemix}} Identity and Access Management (IAM) verwaltet wird, gehört zu einer Ressourcengruppe innerhalb Ihres Kontos. Wenn Sie eine neue Ressource aus dem Katalog zu Ihrem Konto hinzufügen, können Sie die Ressource einer Ressourcengruppe zuweisen. Die einzige Ausnahme hiervon stellt Kubernetes dar, das Sie nicht zur Angabe einer Ressourcengruppenzuweisung auffordert. Der Zugriff auf den Service wird vielmehr durch die Verwendung von IAM-Rollen gesteuert.

Services, die mithilfe von {{site.data.keyword.Bluemix_notm}} IAM verwaltet werden und einer Ressourcengruppe angehören, haben meherere Vorteile. Zu diesen Vorteilen zählt unter anderem die Möglichkeit zur Herstellung von Verbindungen zu Apps und Services in einem beliebigen Cloud Foundry-Bereich. Auf diese Weise können Sie Verbindungen für Apps und Services herstellen, die sich an unterschiedlichen Standorten befinden. Da Ressourcengruppen nicht auf einen bestimmten Standort bezogen sind, können Sie Apps und Services an unterschiedlichen Standorten in derselben Ressourcengruppe bereitstellen. Außerdem können Sie die differenzierte Zugriffssteuerung bis hin zu jeder einzelnen Instanz innerhalb einer Ressourcengruppe verwenden.

Weitere Informationen zum Arbeiten mit Ressourcengruppen finden Sie unter [Ressourcengruppen verwalten](/docs/resources?topic=resources-rgs). 
