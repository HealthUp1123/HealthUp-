# HealthUp+ Website

Website für die App HealthUp+ (iPhone, iPhone Duo und Apple Watch), ausgeliefert über GitHub Pages aus dem Hauptordner dieses Repositorys:
https://healthup1123.github.io/HealthUp-/

Stand: 3. November 2026, App-Version 0.1.5. Dieses Repository ist die einzige Quelle der Website (früher `docs/site` im App-Projekt).

## Seiten

| Datei | Inhalt |
|---|---|
| `index.html` | Startseite (Bilder aus den App-Store-Screenshots: iPhone, iPhone Duo, Apple Watch) |
| `en/`, `fr/`, `pt-br/`, `tr/`, `ja/`, `ko/`, `zh-hans/`, `zh-hant/` | Startseite in den 8 weiteren App-Sprachen (Sprachwahl oben rechts auf jeder Seite). Die Rechtstexte gibt es auf Deutsch; die deutsche Fassung gilt. |
| `join.html` | Einladungsseite der Liga (`join.html?code=ABC123`); die App verlinkt sie in Einladungen |
| `datenschutzerklaerung.html` | Datenschutzerklärung |
| `impressum.html` | Impressum |
| `support.html` | Support und häufige Fragen |
| `nutzungsbedingungen.html` | Nutzungsbedingungen |
| `community-regeln.html` | Liga-Regeln, Melden, Sperren, Einspruch |
| `methodik.html` | Berechnungen mit Quellen, Eigenentwicklung oder literaturbasiert |
| `ki-transparenz.html` | KI-Bilder, KI-Foto, Berechnungen auf dem Gerät |
| `quellen-lizenzen.html` | Datenquellen und Lizenzen |
| `styles.css` | gemeinsame Gestaltung |
| `images/kopfzeile.mp4` | Kopfvideo der Startseite (aus `AppStore-Header_21x9_ProRes.mov`, H.264, 1920 px, ohne Ton); Standbild `kopfzeile.jpg` |
| `images/` | App-Symbol und Bildschirmfotos (JPEG, höchstens 1800 px) |

## Alte Adressen

Diese Dateien leiten weiter und dürfen nicht gelöscht werden, weil App Store und App sie verlinken:

* `HealthPlus-website.html` (Support- und Datenschutz-URL im App Store). Sprungmarken werden umgeleitet: `#datenschutz` zur Datenschutzerklärung, `#support` zu Support, `#impressum` zum Impressum, sonst zur Startseite.
* `Datenschutz.html` und `privacy.html` leiten zur Datenschutzerklärung.

Die neue Datenschutzseite heißt bewusst `datenschutzerklaerung.html` und nicht `datenschutz.html`, weil `Datenschutz.html` und `datenschutz.html` auf macOS denselben Dateinamen hätten.

## Regeln für Änderungen

* Keine Bilder als Base64 in HTML, Bilder gehören nach `images/`.
* Eine Änderung an der deutschen Startseite gehört in alle Sprachordner.
* Keine Skripte, Schriften oder Inhalte von fremden Servern.
* Jede Rechtsseite trägt ein Stand-Datum.
