# Hostel10Euro

Statische Website aus der vorhandenen Vorschau. `index.html` ist die Startseite; `preview.html` bleibt unverändert erhalten. `.nojekyll` ist vorhanden. Kein Build erforderlich.

## Stripe

Die Startseite enthält im Menü, im Einstiegsbereich und im Abschnitt `#bezahlen` einen Zugang zur Stripe-Zahlung:
https://buy.stripe.com/28E14maa9ccdeaPbHB0RG00

10 EUR für genau ein Einzelbett für eine Nacht. Keine automatische Verfügbarkeitsprüfung, keine Datumsreservierung. Vor Zahlung ist eine Aufenthaltsbestätigung erforderlich; für mehrere Personen/Nächte einen passenden Zahlungslink bereitstellen. Die Website erfasst keine Kartendaten.

## Aktueller Domainstatus

IONOS leitet hostel10euro.de und www.hostel10euro.de derzeit direkt auf Stripe weiter. Das zeigt noch nicht die Hostel-Startseite. SSL Starter Wildcard wurde zur Einrichtung beauftragt. Die Weiterleitung erst ersetzen, wenn die Website veröffentlicht und getestet wurde.

## Website veröffentlichen

GitHub Repository → Settings → Pages → Build and deployment:
- Source: Deploy from a branch
- Branch: main
- Folder: / (root)
- Save

Danach Pages-Build und Projektadresse https://arshinfo-bot.github.io/hostel10euro/ prüfen.

## Noch erforderlich

- Rechtlichen Betreiber und ladungsfähige Betreiberanschrift bestätigen; Impressum vervollständigen.
- Datenschutzangaben für tatsächliches Hosting, Kontaktwege, Wikimedia und Stripe vervollständigen.
- Aufenthalts- und Stornierungsbedingungen bestätigen.
- Endfassung freigeben; Vorschauhinweise erst dann entfernen.
- Erst nach erfolgreicher Veröffentlichung die Domain von Stripe-Weiterleitung auf Website-Hosting umstellen, CNAME und DNS entsprechend konfigurieren und HTTPS sowie Zahlungsbutton testen.
