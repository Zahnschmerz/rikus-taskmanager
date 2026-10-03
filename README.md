# Rikus Taskmanager

**Quit programs in a calm list that stays put.**
Arrow keys choose, Delete asks, Delete again quits. Free.

➡️ **Website, download and free unlock code: https://taskmanager.rikus.info**

---

## What it does

Rikus Taskmanager shows your running programs and processes in a list that does **not**
jump around: new entries are added at the end, all others keep their place. You choose
with the arrow keys, Delete asks, Delete again quits the program. If a program does not
stop, one more Delete switches it off at once.

- **Restart** — a hanging program is closed and opened again right away, the way it would
  start from the menu. It asks first, because unsaved work can be lost.
- **Startup programs** — a second page lists everything that starts by itself when you log
  in, each with a switch to turn it off and on again. **Nothing is deleted**: the old state
  is saved before the first change and restored exactly when you switch back.
- Parts of the computer stay visible but cannot be switched off — sound, network, password
  prompts, screen lock.

Light and dark, German and English. Tested on Linux Mint 22.3.

## Install (apt)

Add the package repository once:

```sh
sudo apt update && sudo apt install -y curl && sudo install -d /etc/apt/keyrings && sudo curl -fsSL https://apt.rikus.info/rikus-apt.gpg -o /etc/apt/keyrings/rikus.gpg
echo "deb [signed-by=/etc/apt/keyrings/rikus.gpg] https://apt.rikus.info stable main" | sudo tee /etc/apt/sources.list.d/rikus.list
```

Then install:

```sh
sudo apt update && sudo apt install rikus-taskmanager
```

To remove the repository again (the program stays installed):

```sh
sudo rm /etc/apt/sources.list.d/rikus.list /etc/apt/keyrings/rikus.gpg && sudo apt update
```

The program asks once for a personal code. You get it free of charge on
**https://taskmanager.rikus.info** — enter name and e-mail, the code arrives by mail
straight away and is valid for all free Rikus programs.

## Questions and bugs

Please open an [issue](https://github.com/Zahnschmerz/rikus-taskmanager/issues) or write
via the website. This repository is the contact point for Rikus Taskmanager; the source
code is not published here.

All rights reserved.

---

# Rikus Taskmanager (Deutsch)

**Programme beenden in einer ruhigen Liste, die stehen bleibt.**
Pfeiltasten wählen, Entf fragt, ein zweites Entf beendet. Kostenlos.

➡️ **Seite, Herunterladen und kostenloser Freischaltcode: https://taskmanager.rikus.info**

## Was es tut

Rikus Taskmanager zeigt die laufenden Programme und Vorgänge in einer Liste, die **nicht**
springt: Neue Einträge kommen ans Ende, die anderen bleiben auf ihrem Platz. Du wählst mit
den Pfeiltasten, Entf fragt, ein zweites Entf beendet das Programm. Hört es nicht auf,
schaltet es ein weiteres Entf sofort aus.

- **Neu starten** — ein hängendes Programm wird geschlossen und gleich wieder geöffnet, so
  wie aus dem Startmenü. Vorher kommt eine Frage, denn Ungespeichertes kann verloren gehen.
- **Autostartprogramme** — eine zweite Seite zeigt alles, was beim Anmelden von selbst
  startet, jedes mit einem Schalter zum Ab- und Wiedereinschalten. **Gelöscht wird nichts**:
  Der alte Stand wird vor der ersten Änderung gesichert und beim Zurückschalten genau so
  wiederhergestellt.
- Was zum Rechner gehört, bleibt sichtbar, lässt sich aber nicht ausschalten — Ton, Netz,
  Passwortfragen, Bildschirmsperre.

Hell und dunkel, Deutsch und Englisch. Geprüft auf Linux Mint 22.3.

## Einspielen (apt)

Die Paketquelle einmal eintragen:

```sh
sudo apt update && sudo apt install -y curl && sudo install -d /etc/apt/keyrings && sudo curl -fsSL https://apt.rikus.info/rikus-apt.gpg -o /etc/apt/keyrings/rikus.gpg
echo "deb [signed-by=/etc/apt/keyrings/rikus.gpg] https://apt.rikus.info stable main" | sudo tee /etc/apt/sources.list.d/rikus.list
```

Dann einspielen:

```sh
sudo apt update && sudo apt install rikus-taskmanager
```

Beim ersten Start fragt das Programm einmal nach deinem persönlichen Code. Den bekommst du
kostenlos auf **https://taskmanager.rikus.info** — Name und E-Mail eintragen, der Code kommt
sofort per Mail und gilt für alle kostenlosen Rikus-Programme.

## Fragen und Fehler

Bitte ein [Issue](https://github.com/Zahnschmerz/rikus-taskmanager/issues) aufmachen oder
über die Seite schreiben. Diese Ablage ist die Anlaufstelle für Rikus Taskmanager; der
Quelltext liegt nicht hier.

Alle Rechte vorbehalten.
