# Schwachstelle in Microsoft Teams entdeckt

Die Forscher **Max Corbridge** und **Tom Ellson** von **JUMPSEC's Red Team** haben eine Schwachstelle in **Microsoft Teams** gefunden, die möglicherweise das Einschleusen von Malware in Unternehmen ermöglicht, die die Plattform nutzen. Die Schwachstelle ermöglicht die Umgehung der client-seitigen Sicherheitskontrollen, so dass externe Benutzer Dateien, die möglicherweise Malware enthalten, an Mitarbeiter in Ihrem Unternehmen senden können. Dies ist aufgrund der Standardkonfiguration von Microsoft Teams möglich, die es Nutzern von außerhalb einer Organisation erlaubt, deren Mitarbeiter zu kontaktieren. Diese Schwachstelle umgeht im Wesentlichen moderne Anti-Phishing-Sicherheitsmaßnahmen und könnte sich daher auf alle Organisationen auswirken, die Microsoft Teams in der Standardkonfiguration verwenden.

## Stellungnahme von Microsoft

Microsoft wurde über die Schwachstelle informiert, gibt aber an, dass sie nicht sofort behoben werden muss. 

## Empfehlungen von JUMPSEC

**JUMPSEC** rät Unternehmen, zu überdenken, ob sie externen Benutzern wirklich erlauben müssen, ihren Mitarbeitern über Teams Nachrichten zu senden. Wenn dies nicht notwendig ist, sollten sie die Option deaktivieren, und wenn die Kommunikation mit externen Usern erforderlich ist, sollten sie sie auf Domänen beschränken, die auf der Erlaubnisliste stehen. Unternehmen, für die diese Optionen nicht in Frage kommen, wird empfohlen, ihre Mitarbeiter über potenzielle Social-Engineering-Kampagnen über Produktivitätsanwendungen wie Teams und Slack zu informieren. Während die Erkennungsoptionen derzeit begrenzt sind, hat JUMPSEC Microsoft gebeten, wichtige Protokolle zur Überwachung der Nutzung von Teams für Social Engineering-Zwecke hinzuzufügen.
