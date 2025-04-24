Barrierefreiheit-Widget - Hosting-Information

Diese Dateien bilden den vollständigen React-Build des Barrierefreiheit-Widgets.

Verzeichnisstruktur:
- index.html: Die Hauptdatei des Widgets
- assets/: Enthält alle JavaScript- und CSS-Dateien

WICHTIGE HINWEISE:
1. Hosten Sie alle Dateien zusammen auf demselben Server/im selben Verzeichnis
2. Die Pfade zu den Assets in index.html sind relativ (./assets/...)
3. Wenn Sie das Widget in einem Unterverzeichnis hosten, stellen Sie sicher, dass das Assets-Verzeichnis korrekt erreichbar ist

Sobald die Dateien gehostet sind, aktualisieren Sie Ihr Integrations-Script (react-integration-final.js) 
mit dem Pfad zu dieser index.html.

Beispiel:
Wenn Ihre Hosting-URL lautet: https://example.com/widgets/accessibility/
Dann sollte in react-integration-final.js stehen:

const widgetBaseUrl = 'https://example.com/widgets/accessibility/';

Beachten Sie: Die URL muss mit einem Schrägstrich (/) enden!

Weitere detaillierte Informationen finden Sie in der README-DEPLOY.md Datei.