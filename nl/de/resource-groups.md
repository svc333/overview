---

copyright:
  years: 2017, 2018
lastupdated: "2018-10-11"

---

{:shortdesc: .shortdesc}

# Ressourcen in Ressourcengruppen organisieren
{: #whatis}

Ressourcengruppen bieten Ihnen die Möglichkeit, Ihre [Kontoressourcen](/docs/resources/acct_resources.html#resource) in anpassbaren Gruppierungen zu organisieren, sodass Sie den Benutzern schnell Zugriff auf mehrere Ressourcen gleichzeitig zuordnen können. Jede Kontoressource, die mit der Zugriffssteuerung von {{site.data.keyword.Bluemix}} Identity and Access Management (IAM) verwaltet wird, gehört zu einer Ressourcengruppe innerhalb Ihres Kontos. Wenn Sie Ihrem Konto aus dem Katalog eine neue Ressource hinzufügen, können Sie die Ressource einer Ressourcengruppe zuordnen. Die einzige Ausnahme ist Kubernetes, das Sie nicht zur Angabe einer Ressourcengruppenzuweisung auffordert. Der Zugriff auf den Service wird jedoch durch die Verwendung von IAM-Rollen gesteuert.

Services, die mit {{site.data.keyword.Bluemix}} IAM verwaltet werden und zu einer Ressourcengruppe gehören, haben mehrere Vorteile, einschließlich der Möglichkeit, eine Verbindung zu Apps und Services in einem beliebigen Cloud Foundry-Bereich herzustellen, sodass Sie Apps und Services an unterschiedlichen Standorten miteinander verbinden können. Da Ressourcengruppen nicht auf einen bestimmten Standort bezogen sind, können Sie Apps und Services an unterschiedlichen Standorten in derselben Ressourcengruppe bereitstellen. Sie haben auch die Möglichkeit, eine bis zur einzelnen Instanz differenzierte Zugriffssteuerung in einer Ressourcengruppe zu verwenden.

Weitere Informationen zum Arbeiten mit Ressourcengruppen finden Sie unter [Ressourcengruppen verwalten](/docs/resources/resourcegroups.html). Wenn Sie noch nicht über Erfahrung mit der Verwendung von Ressourcengruppen verfügen, lesen Sie die Informationen in [Bewährte Verfahren für die Organisation von Ressourcen in Ressourcengruppen](/docs/resources/bestpractice_rgs.html#bp_resourcegroups).
