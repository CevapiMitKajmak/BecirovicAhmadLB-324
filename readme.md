# LB 324

## Aufgabe 2
LB 324 - Aufgabe 2: Installation von pre-commit

Um pre-commit zu installieren, stehen Ihnen zwei verschiedene Methoden zur Verfügung. Folgen Sie diesen Schritten, um pre-commit erfolgreich auf Ihrem System zu installieren.

Schritt 1: Voraussetzungen überprüfen

Stellen Sie sicher, dass Sie Python und Pip auf Ihrem System installiert haben. Falls Sie Pip noch nicht installiert haben, können Sie es unter folgendem Link herunterladen und installieren: https://pip.pypa.io/en/stable/installation/

 Installation über Visual Studio Code

Öffnen Sie Visual Studio Code, Ihre Entwicklungsumgebung.

  Öffnen Sie ein neues Terminalfenster in Visual Studio Code.

  Geben Sie den folgenden Befehl ein und drücken Sie Enter:

  bash
  
    pip install -r requirements.txt

Stellen Sie sicher, dass Sie bereits ein requirements.txt-Datei in Ihrem Projekt haben und sicherstellen, dass pre-commit darin aufgeführt ist. Sie können pre-commit zur requirements.txt hinzufügen, indem Sie folgende Zeile einfügen:

bash

    pre-commit

Nachdem Sie einen der oben genannten Schritte ausgeführt haben, ist pre-commit auf Ihrem System installiert und einsatzbereit.

Sie können nun pre-commit verwenden, um automatisierte Codeüberprüfungen und -formatierungen in Ihrem Projekt durchzuführen. Vergessen Sie nicht, Ihre .pre-commit-config.yaml-Datei entsprechend Ihren Anforderungen zu konfigurieren, um die gewünschten Überprüfungen und Formatierungen festzulegen.

Mit pre-commit können Sie sicherstellen, dass Ihr Code stets den definierten Standards entspricht und somit die Qualität Ihrer Softwareprojekte verbessern.

## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.
