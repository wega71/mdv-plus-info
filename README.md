# MDV Plus – öffentliche Projektseite

Statische englische Projektseite und technisch auf den Stand 0.2.0 abgestimmte
Datenschutzerklärung. Kein Node-Build, kein Tracking-Skript und kein Backend.
Die Website ist noch nicht veröffentlicht.

## Auf GitHub Pages veröffentlichen

1. Ein neues öffentliches Repository namens `mdv-plus-info` auf GitHub anlegen.
   Der Erweiterungsquellcode muss dafür nicht hochgeladen werden.
2. Die **Inhalte** dieses Ordners in den Repository-Stamm hochladen:
   `index.html`, `privacy.html`, `style.css`, `.nojekyll`, `assets/` und diese README.
   Nicht einen weiteren übergeordneten Ordner ins Repository legen.
3. Unter **Settings → Pages → Build and deployment** die Quelle
   **Deploy from a branch**, Branch **main** und Ordner **/(root)** wählen.
4. Speichern und auf die erfolgreiche Bereitstellung warten. Die tatsächliche
   Adresse zeigt GitHub unter **Settings → Pages → Visit site**.
5. Die Homepage im Browser aufrufen, den Privacy-Link testen und sicherstellen,
   dass die Datenschutzerklärung ohne Anmeldung erreichbar ist.
6. Im Chrome-Web-Store eintragen:
   - Homepage: die von GitHub angezeigte Projektadresse.
   - Support: dieselbe Adresse mit `#support` am Ende.
   - Datenschutzerklärung: `privacy.html` relativ zur Projektadresse.

Die URL hat gewöhnlich das Schema
`https://DEIN-GITHUB-NAME.github.io/mdv-plus-info/privacy.html`.
Den Platzhalter nicht im Store eintragen; stattdessen die echte URL verwenden.

Anleitung: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Vor Veröffentlichung beachten

- Kontaktadresse `wegasolutions@googlemail.com` wird öffentlich angezeigt.
- GitHub-Accountname und Repository-Historie sind bei einem öffentlichen Repo
  sichtbar. Bei Git-Uploads vorab die Commit-E-Mail auf eine gewünschte öffentliche
  oder GitHub-noreply-Adresse einstellen. Keine privaten Schlüssel hochladen.
- Die Datenschutzerklärung beschreibt das geprüfte technische Verhalten und ist
  keine individuelle Rechtsberatung. Ob zusätzliche Anbieter-/Verantwortlichen-
  oder Impressumsangaben erforderlich sind, muss vor Veröffentlichung geklärt
  werden; eine Kontakt-E-Mail garantiert keine rechtlich zulässige Anonymität.
- Den Kontaktposteingang überwachen. Wenn Website oder Erweiterung geändert
  werden, die Datenschutzerklärung und Store-Angaben passend aktualisieren.
- Ein späterer Store-Link kann ergänzt werden, sobald die Erweiterung dort
  tatsächlich verfügbar ist. Aktuell behauptet die Website keine Verfügbarkeit.

## Herkunft

MDV Plus basiert auf Markdown Viewer von Simeon Velichkov (MIT-Lizenz).
Das Projektlogo und die Screenshots stammen aus MDV Plus. Der Link im Footer
kennzeichnet die Herkunft und ist kein Support-Link des ursprünglichen Autors.
