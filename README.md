<p align="center">
  <img src="icon-192.png" alt="Hausaufgaben-Puffer-Planer Logo" width="110" height="110">
</p>

<h1 align="center">Hausaufgaben-Puffer-Planer</h1>

<p align="center">
  <strong>Reizarme, 100 % lokale Offline-WebApp zur stressfreien Hausaufgaben-Planung, Zeitbudgetierung und Entlastung im Schulalltag</strong><br>
  Aktuelle Version: <strong>v1.6.0</strong> • Kostenlos • Werbefrei • Open Source (MIT)
</p>

---

## 🚀 Direkt starten oder herunterladen

| Aktion | Link | Hinweis |
| :--- | :--- | :--- |
| **🌐 WebApp direkt im Browser nutzen** | [**Hausaufgaben-Puffer-Planer öffnen ➔**](https://konzept23.github.io/hausaufgaben-planer/) | Sofort startklar auf Handy, Tablet & PC (GitHub Pages) |
| **📥 Offline-Paket herunterladen (.zip)** | [**Komplettpaket herunterladen (.zip)**](https://github.com/Konzept23/hausaufgaben-planer/archive/refs/heads/main.zip) | Enthält `index.html` + `icon-192.png` – entpacken & direkt öffnen |
| **📄 Einzelne HTML-Datei laden** | [**index.html (Direktlink)**](https://raw.githubusercontent.com/Konzept23/hausaufgaben-planer/main/index.html) | Rechtsklick → *„Ziel / Link speichern unter…“* als `index.html` |
| **🏷️ Versionen & Releases** | [**Alle Releases auf GitHub ansehen**](https://github.com/Konzept23/hausaufgaben-planer/releases) | Übersicht aller veröffentlichten Stände |

---

## 💡 Worum geht es?

Der **Hausaufgaben-Puffer-Planer** ist ein reizarmes, pädagogisches Werkzeug aus der Praxis der Schulbegleitung, Inklusion und individuellen Lernförderung. Statt endloser To-do-Listen rechnet die App automatisch aus dem Stundenplan (Woche A & B) aus, **was heute wirklich Pflicht ist** und **was entspannt geschoben werden darf** – abgestimmt auf ein festes, realistisches Nachmittags-Zeitbudget.

* **Reizarmes Design:** Klare Kontraste, gedämpfte Ampelfarben, null Animationen, umschaltbar zwischen **Light- und Dark-Mode**.
* **Keine Anmeldung, kein Konto, keine Cloud:** Alles läuft vollständig im Browser als einzelne HTML-Datei.

---

## ✨ Wichtigste Funktionen (v1.6.0)

### 🚦 Dynamischer Ampel-Plan & Zeitbudget
* **Automatische Priorisierung:**
  * **ROT:** Pflicht für heute (morgen ist das Fach dran oder der Puffer ist aufgebraucht).
  * **GELB:** Sinnvoller Puffer (passt noch entspannt ins heutige Nachmittags-Zeitbudget und verhindert Stau).
  * **GRÜN:** Kann ohne schlechtes Gewissen auf die nächsten Tage geschoben werden.
* **Zwei Live-Zeitbalken im Kopf:** Zeigen jederzeit das verplante Nachmittags-Pensum (inkl. reserviertem Klausur-Lernpuffer) sowie die verfügbare Kapazität in **Freistunden & Mittagspausen**.
* **Groß lesen & Teilen:** Jede Aufgabe und jede Klausur lässt sich im Vollbild-Lesefenster öffnen und mit einem Klick sauber formatiert für **SMS, WhatsApp oder Teams** kopieren (z. B. für kranke Mitschüler).

### 🎒 Abgabe- & Pack-Check (Erledigte Aufgaben & Schnellzugriff)
* **6. Navigations-Button `🎒 Pack-Check`:** Zeigt aus jedem Bereich der App per Fingertipp ein kompaktes Pop-up mit allen bereits erledigten Aufgaben, die **heute (Rot)** oder **morgen (Gelb)** im Unterricht gebraucht werden – inklusive Zähler direkt am Button.
* **Getrennte Erledigt-Ansicht:**
  * **Oben (immer sichtbar):** Aktive Abgabe-Ampel (**Rot** = heute inkl. Schulstunde, **Gelb** = morgen einpacken, **Grün** = später), normal lesbar und vollflächig antippbar.
  * **Unten (Archiv-Jalousie):** Bereits verstrichene Abgabetage wandern durchgestrichen in eine eingeklappte Archiv-Kachel.
  * **Geschütztes Aufräumen:** *„Archiv aufräumen“* löscht ausschließlich abgelaufene Archiv-Einträge – aktuelle Aufgaben in Rot, Gelb und Grün bleiben geschützt.
* **Optionale Wochenend-Brücke:** In den Einstellungen wählbar, ob Montags-Aufgaben streng nach Kalendertagen (ab Sonntag Gelb) oder bereits ab Freitag/Samstag Gelb markiert werden.

### 🎯 Klausur- & Test-Radar
* Ordnet Klassenarbeiten, Tests und Projekte nach Dringlichkeit (**Rot** ≤ 3 Tage, **Gelb** 4–7 Tage, **Grün** > 7 Tage).
* Reserviert ab 7 Tagen vorher automatisch tägliche Lernpuffer-Minuten im Nachmittags-Budget.
* **Doppeltag-Schutz:** Warnt automatisch, wenn am selben Kalendertag bereits eine andere Arbeit eingetragen ist.
* **Prüf-Markierung (`⚠️ Prüfen`):** Beim Import vorgemerkte Klausuren stehen ganz oben im Radar, bis Datum und Stoff bestätigt wurden.

### 📅 Stundenplan, Echtzeit-Schulglocke & Freistunden
* **Übersichtliche Jalousiekacheln:** Alle vier Bereiche (*Kurzfristiger Ausfall*, *Zeitraster*, *Zeitbudget*, *Basis-Stundenplan A/B*) lassen sich einzeln oder gesammelt auf- und zuklappen.
* **Echtzeit-Taktung:** Zeigt laufend die aktuelle Schulstunde, Pausen und verbleibende Minuten an.
* **Tagesaktueller Ausfall & Fächertausch:** Ausfälle werden automatisch als nutzbare Freistunde erkannt; abgelaufene Stunden von heute werden automatisch gesperrt und zurückgesetzt.
* **Halbjahres-Fächerfilter:** Nur die im aktuellen Halbjahr aktiven Fächer (plus eigene Fächer) erscheinen in den Auswahllisten.

### 📥 Sammel-Import per CSV & SB-Talker-Schnittstelle
* **CSV Schnell-Prüfliste:** Direkt im Tab **`+ Aufgabe`** (und in den Einstellungen) erreichbar. Liest CSV-Dateien im Format `Datum;Fach;Aufgabe;Notiz` (z. B. Export aus dem **SB-Talker / Schulbegleitungs-Tracker**) ein.
* Zeiten lassen sich pro Zeile per Ein-Klick-Chip (`10 | 15 | 30 | 45 Min.`) anpassen, unwichtige Einträge (z. B. Elterninfos) mit `×` vorab entfernen und erkannte Klausuren samt Datum im Text direkt ins **Klausur-Radar** umschalten.
* **Datensicherung:** Komplettes System-Backup als `.json` sowie kombinierter Export/Import von Hausaufgaben und Klausuren als `.csv` (Duplikat-Schutz, bestehende Daten werden nicht überschrieben).

---

## 📱 Nutzung als App auf dem Smartphone (PWA / Startbildschirm)

Die WebApp kann ohne App-Store wie eine normale App auf dem Startbildschirm abgelegt werden:

* **Android (Chrome / Edge / Firefox):**
  1. Öffne [https://konzept23.github.io/hausaufgaben-planer/](https://konzept23.github.io/hausaufgaben-planer/).
  2. Tippe oben rechts auf das Menü (**⋮**) und wähle **„Zum Startbildschirm hinzufügen“** bzw. **„App installieren“**.
* **iPhone / iPad (Safari):**
  1. Öffne [https://konzept23.github.io/hausaufgaben-planer/](https://konzept23.github.io/hausaufgaben-planer/) in Safari.
  2. Tippe unten auf das **Teilen-Symbol** und wähle **„Zum Home-Bildschirm“**.
* **Komplett offline am PC:**
  1. Lade das [ZIP-Paket](https://github.com/Konzept23/hausaufgaben-planer/archive/refs/heads/main.zip) herunter und entpacke es in einen Ordner.
  2. Öffne die Datei `index.html` per Doppelklick im Browser (Chrome, Firefox, Edge, Safari) – keine Internetverbindung nötig.

---

## 🛡️ Datenschutz & Sicherheit (DSGVO)

* **100 % lokal (`localStorage`):** Sämtliche Daten (Stundenplan, Hausaufgaben, Klausuren, Vokabeln, Einstellungen) verbleiben ausschließlich im Browser deines Endgeräts.
* **Keine Server, keine Tracker, keine Cookies, keine externen Schriftarten oder CDNs.**
* **Fehlklick-Schutz:** Alle kritischen Löschaktionen sind durch eine zweistufige Sicherheitsabfrage mit vertauschten Bestätigungs-Buttons abgesichert.
* **Hinweis zu GitHub Pages:** Beim Online-Aufruf über `konzept23.github.io` übermittelt der Browser technisch bedingt die IP-Adresse an GitHub, um die HTML-Datei auszuliefern. Alle danach in der App eingegebenen Planungsdaten bleiben ausschließlich lokal auf deinem Gerät.

---

## 📋 Änderungshistorie (Auszug)

* **v1.6.0:** Neuer 6. Navigations-Button `🎒 Pack-Check` mit Pop-up & Zähler, Stundenplan-Reiter als Jalousiekacheln, Trennung in sichtbare Abgabe-Ampel und einklappbare Archiv-Jalousie mit geschütztem Aufräumen, Android-Fix für lange CSV-Dateinamen, einheitliches Impressum mit MIT-Lizenz & Footer-Version.
* **v1.5.0:** Abgabe- & Pack-Check bei erledigten Aufgaben inkl. optionaler Wochenend-Brücke, CSV Schnell-Prüfliste (SB-Talker-Schnittstelle mit Klausur-Umschalter & Prüf-Markierung), eigenes 192×192-App-Icon (`icon-192.png`).
* **v1.4.x:** Ampel-System, A/B-Stundenplan im 8-Stunden-Raster, Echtzeit-Schulglocke, Freistunden- & Mittagspausen-Puffer, Klausur-Radar mit Kollisionswarnung, Vollbild-Lesen & Kopieren, Halbjahres-Fächerfilter, JSON- & CSV-Export/Import.

---

## ☕ Projekt freiwillig unterstützen

Der Hausaufgaben-Puffer-Planer ist und bleibt kostenlos, werbefrei und Open Source. Wenn dir das Werkzeug im Schulalltag hilft und Zeit spart, kannst du die Weiterentwicklung mit einem freiwilligen Dankeschön (virtueller Kaffee) unterstützen:

👉 [**Einen Kaffee ausgeben (Ko-fi)**](https://ko-fi.com/DEIN_KOFI_NAME)

---

## 📜 Lizenz & Entwickler

Diese Software steht unter der offenen **MIT-Lizenz** (Copyright © 2026 **Heiko Limbeck / Konzept23**). Sie darf kostenlos genutzt, weitergegeben und angepasst werden, sofern der Urheber- und Lizenzvermerk erhalten bleibt.

* **Entwicklung & Verantwortlich gem. § 5 DDG:** Heiko Limbeck (Projekt: Konzept23), Lindenstraße 61, 53945 Blankenheim, Deutschland
* **Web:** [www.konzept23.de](https://www.konzept23.de)
* **E-Mail:** [info@konzept23.de](mailto:info@konzept23.de)
* **Alle Projekte auf GitHub:** [github.com/Konzept23](https://github.com/Konzept23)