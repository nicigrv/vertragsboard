# Vertragsboard
---

**Ein Produkt von <https://greylo.de>**

**Weitere Informationen unter <https://greylo.de/vertragsboard.php>**

---

Windows-Desktop-Anwendung zur Verwaltung von Einstellungs- und
Vertragsprozessen. Mehrere Personen arbeiten gleichzeitig – entweder
gemeinsam über einen PHP-/MariaDB-Server oder lokal via OneDrive.

---

## Download

**Aktuelle Version (empfohlen):**

- Web-Installer (Empfohlen):
  https://github.com/nicigrv/vertragsboard/releases/latest/download/Vertragsboard-Installer.zip
- Portable EXE:
  https://github.com/nicigrv/vertragsboard/releases/latest/download/Vertragsboard.exe
- Voller Offline-Installer:
  https://github.com/nicigrv/vertragsboard/releases/latest/download/Vertragsboard-Setup.exe

Alle Releases im Überblick: <https://github.com/nicigrv/vertragsboard/releases>

## Betriebsmodi

| Modus | Wann sinnvoll |
|---|---|
| **Standard-Server** | Zugang zu einer gehosteten Instanz vorhanden. Mehrere Nutzer gleichzeitig live. |
| **Eigener Server**  | Man betreibt das PHP-/MariaDB-Backend selbst (Standard-Webhosting reicht). Anleitung im Release-Asset `Vertragsboard-PHP-Backend.zip`. |
| **Lokal / OneDrive**| Ein-Personen-Betrieb oder wechselnder Zugriff mehrerer PCs ueber OneDrive-Sync. |

Beim ersten Start fuehrt ein Setup-Wizard durch die Auswahl.

## Rollen

- **admin** – volle Rechte, Admin-Dashboard, Nutzerverwaltung, Konfiguration
- **user** – Vorgaenge anlegen, bearbeiten, loeschen
- **readonly** – nur lesen

## Konfigurierbarkeit

Alle Prozessschritte, Vertragsarten, Einheiten (z. B. Kitas) und der
Organisationsname werden im **Admin-Dashboard** gepflegt – nichts ist
mehr hart im Code hinterlegt.

Zwei Presets bei der Erstinstallation:

- **Bonifatius-Standard** – 9 Prozessschritte, 8 Vertragsarten, 2 Kitas (trifft auf die meißten Katholischen KITAS im Bistum Limburg zu)
- **Leer** – man richtet alles selbst ein

## Voraussetzungen

- Windows 11
- Fuer den Server-Modus: Zugang zu einer Instanz (Basis-URL + Login)
- Fuer den Lokal-Modus: OneDrive installiert und eingerichtet

## Support

Bugs / Feedback bitte als Issue:
<https://github.com/nicigrv/vertragsboard/issues>
