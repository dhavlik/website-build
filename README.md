# Website Eigenbaukombinat.de

## Anleitungen

Grundsätzlich braucht es um die Webseite zu bearbeiten mindestens einen [Github](https://github.com) Account.

Im Folgenden entstehen kurze Anleitungen um mit möglichst einfachen Mitteln und wenigen Vorkenntnissen die Webseite bearbeiten zu können.

Mit dem VSCode Editor könnt ihr auf der Github Webseite ohne Vorkenntnisse mit git arbeiten.

Den Editor könnt ihr mit dem Druck auf die Punkt-Taste[.] oder über den [Link](https://github.dev/Eigenbaukombinat/website-build) öffnen.

### Einen neuen Blog-Artikel erstellen oder ändern

1. neuen Fork des Repositorys erstellen
1. Erstelle dort eine neue Datei mit dem "Explorer"
    1. Öffne den Ordner `content` -> `posts`
    1. erstelle eine neue Datei mit dem vorangestellten Datum zB. `2023-02-02-Mein-erster-Blogpost.markdown`
2. Schreiben des Blogposts
    1. Die neu erstellte Datei muss am anfang der Datei folgenden Inhalt haben.
        1. Beispiel:
            ```
            ---
            author: Markus
            date: 2022-11-25 09:00:00+00:00
            draft: false
            title: 'Der Titel meines ersten Blogposts'
            type: post
            url: /mein-erster-blogpost/
            categories:
            - Veranstaltungen
            - Verein
            tags:
            - Verein
            - Veranstaltung
            - games
            - spieleabend
            ---
            ```
    1. Dahinter kommt [Markdown](https://de.wikipedia.org/wiki/Markdown) Format dein Text.
    1. Als Hilfe um den Text zu verfassen kannst du auch https://pads.eigenbaukombinat.de benutzen und ihn hier rein kopieren.
    1. Speichern
        1. QuellcodeVerwaltung öffnen
        1. die Geänderte Datei mit dem Plus[+] hinzufügen
        1. Als Nachricht in wenigen worten schreiben was zu getan hast
        1. `Commit und Push` klicken
    
    Solltest du noch nicht zufrieden sein kannst du jederzeit Änderungen machen und nochmal speichern.
    
    Aktuell musst du dann noch jemanden bescheid sagen damit es auch auf der Webseite erscheint.
