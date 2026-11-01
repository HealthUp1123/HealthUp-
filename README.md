# HealthUp+ Website

Website für die App HealthUp+ (iPhone und Apple Watch), ausgeliefert über GitHub Pages aus dem Hauptordner dieses Repositorys:
https://healthup1123.github.io/HealthUp-/

Stand: 1. November 2026, App-Version 0.1.5. Dieses Repository ist die einzige Quelle der Website (früher `docs/site` im App-Projekt).

## Seiten

| Datei | Inhalt |
|---|---|
| `index.html` | Startseite |
| `datenschutzerklaerung.html` | Datenschutzerklärung |
| `impressum.html` | Impressum |
| `support.html` | Support und häufige Fragen |
| `nutzungsbedingungen.html` | Nutzungsbedingungen |
| `community-regeln.html` | Liga-Regeln, Melden, Sperren, Einspruch |
| `methodik.html` | Berechnungen mit Quellen, Eigenentwicklung oder literaturbasiert |
| `ki-transparenz.html` | KI-Bilder, KI-Foto, Berechnungen auf dem Gerät |
| `quellen-lizenzen.html` | Datenquellen und Lizenzen |
| `styles.css` | gemeinsame Gestaltung |
| `images/` | Logo und Bildschirmfotos |

## Alte Adressen

Diese Dateien leiten weiter und dürfen nicht gelöscht werden, weil App Store und App sie verlinken:

* `HealthPlus-website.html` (Support- und Datenschutz-URL im App Store). Sprungmarken werden umgeleitet: `#datenschutz` zur Datenschutzerklärung, `#support` zu Support, `#impressum` zum Impressum, sonst zur Startseite.
* `Datenschutz.html` und `privacy.html` leiten zur Datenschutzerklärung.

Die neue Datenschutzseite heißt bewusst `datenschutzerklaerung.html` und nicht `datenschutz.html`, weil `Datenschutz.html` und `datenschutz.html` auf macOS denselben Dateinamen hätten.

## Regeln für Änderungen

* Keine Bilder als Base64 in HTML, Bilder gehören nach `images/`.
* Keine Skripte, Schriften oder Inhalte von fremden Servern.
* Jede Rechtsseite trägt ein Stand-Datum.
