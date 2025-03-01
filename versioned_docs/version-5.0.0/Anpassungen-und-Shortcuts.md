---
id: adaption
title: 'Navigation, Shortcuts, Settings und co.'
tags:
  - keyboard
  - shortcuts
  - grundwissen
lektorat:
    - Lektorat: 24.4.2022 @MirUnauffaellig
    - Schlusskorrektur: 6.7.2022 @MirUnauffaellig
---

<!-- @todo: Gif loops nur bei Bedarf starten (Gif verändern) -->

![customizing-banner](https://raw.githubusercontent.com/Ultraschall/ultraschall-manual/main/assets/images/Anpassungen-und-Shortcuts/0-banner-custom.png)

## Einleitung

Um deine Aufnahme- und Schnittarbeit zu beschleunigen, gibt es in Ultraschall zahlreiche Tastenkombinationen, die dir die Arbeit vereinfachen. In diesem Kapitel lernst du, wie du die bereits mitgelieferten Shortcuts benutzt – und wie du beliebige eigene Tastenkombinationen einrichtest. Ferner wird gezeigt, wie man einige Eigenschaften von Ultraschall an die eigenen Bedürfnisse anpassen kann.

## Ultraschall Shortcuts

:::info Info
**Anmerkung für Ultraschall-Veteranen:** Anders als in den vergangenen Versionen sind etliche Tastatur-Shortcuts nun global verfügbar. Wo Tastenkürzel früher davon abhingen, welcher Programmbereich gerade den Fokus hatte, sind seit Version 5 viele Shortcuts so eingestellt, dass sie immer funktionieren. Das sollte typische Probleme lösen – wie etwa, dass nach einem Druck auf <kbd>M</kbd> kein Marker gesetzt wird, weil du zuletzt etwas im Soundboard angeklickt hattest.
:::

**Übersicht über sämtliche Shortcuts:** Im neuen Menüpunkt `Podcast`>`Help and Documentation` ist eine automatisch generierte, sortierte Liste sämtlicher aktiver Shortcuts und Maus-Modifier zu finden.

**Aktualisierte Tastaturschablone:** Alle relevanten Shortcuts sind in [diesem praktischen PDF](http://url.ultraschall-podcast.de/keymap5) zu finden:
[![Keymap](https://raw.githubusercontent.com/Ultraschall/ultraschall-manual/main/assets/images/Anpassungen-und-Shortcuts/keymap.jpg)](http://url.ultraschall-podcast.de/keymap5)

**Aktuellen Projekttab schließen:** Auf dem Mac schließt du den Reiter des aktuell geöffneten Projekts nun standardmäßig mit <kbd>Cmd</kbd> + <kbd>W</kbd>.

**Dynamic Split Items:** Die Funktion `Dynamic Split Items` ist nun wieder direkt über das Tastenkürzel <kbd>Cmd</kbd>/<kbd>Strg</kbd> + <kbd>Shift</kbd> + <kbd>D</kbd> zu erreichen

**Normalisierung:** Per <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>N</kbd> normalisierst du alle selektierten Items auf -23 LUFS. Mit <kbd>Cmd</kbd>/<kbd>Strg</kbd> + <kbd>Shift</kbd> + <kbd>N</kbd> hebst du jegliche Normalisierung wieder auf.

## Navigation

**Trackpad-/Mausradfunktionen:** Trackpads und das Mausrad kommen sich leider in den Belegungen ab und an in die Quere. Das Mausrad hat nun folgende Belegungen, die so auch in nahezu allen anderen Schnittprogrammen zu finden sind:

- **Scrollen**: vertikales Scrollen im [Timeline-Arbeitsbereichs [25]](GUI-overview#bereich-arbeitsfläche)
- **Scrollen** bei gehaltener <kbd>Shift</kbd>-Taste: horizontales Scrollen des [Timeline-Arbeitsbereichs [25]](GUI-overview#bereich-arbeitsfläche)
- **Scrollen** bei gehaltener <kbd>Opt</kbd>/<kbd>Alt</kbd>-Taste: horizontaler Zoom
- **Scrollen** bei gehaltener <kbd>Cmd</kbd>/<kbd>Strg</kbd>-Taste – vertikaler Zoom
- **Klicken**: setzt den Edit-Cursor ohne Auswahl von Spuren oder Items
- **Klicken** und **Ziehen (Drag)**: freies Verschieben des [Timeline-Arbeitsbereichs [25]](GUI-overview#bereich-arbeitsfläche) <!-- [ ] ToDo: prüfen und gegebenenfalls korrigieren -->

**Schnitte prüfen:** Die Shortcuts <kbd>Alt</kbd> + <kbd>Cmd</kbd>/<kbd>Strg</kbd> + <kbd>←</kbd> und <kbd>Alt</kbd> + <kbd>Cmd</kbd>/<kbd>Strg</kbd> + <kbd>→</kbd> setzen den Abspiel-Cursor auf die nächste Item-Kante (bei ausgewählten Tracks nur auf ebendiesem); der Cursor springt anschließend noch um den in den Ultraschall-Settings angegebenen Wert für Previews zurück und startet den Abspielvorgang – perfekt, um alle Schnitte in einem Projekt schnell zu kontrollieren.

**Zoom auf Auswahl und zurück:** Das Kürzel <kbd>Shift</kbd> + <kbd>Z</kbd> zoomt die Ansicht auf eine Zeitauswahl oder auf die selektierten Items. Die Auswahl wird anschließend aufgehoben. Bei nochmaligem Drücken springt die Ansicht zurück in die ursprüngliche Zoomstufe.

**Zoom auf Edit-Cursor:** Mit <kbd>Cmd</kbd>/<kbd>Strg</kbd> + **Pinchen** auf dem Trackpad wird nicht an die Position des Mauszeigers gezoomt, sondern an die des Edit-Cursors.

## Eigene Shortcuts verwenden

Um an das Menü für die Shortcuts zu gelangen, öffnest du den `Actions`-Dialog aus dem Menü `Actions`>`Show action list`. Hier kannst du die Shortcuts individualisieren, falls die Ultraschall-Standardeinstellungen für dich aus irgendeinem Grund nicht passen.

### Globale Shortcuts

In diesem Beispiel erstellen wir den neuen Shortcut <kbd>Alt</kbd> + <kbd>Eingabe</kbd>, der die Project-Einstellungen öffnen soll. Such hierfür die entsprechende Action – im Beispiel `Project Settings` – und klick die Schaltfläche `Add…` an, um den Dialog `Keyboard/MIDI/OSC Input` fürs Festlegen eines Tastenkürzels aufzurufen. Tipp hier zuerst das Kürzel ein, das du künftig verwenden möchtest, und wähl dann in der `Scope`-Dropdown-Liste die Einstellung `Global` aus. Nach einer Bestätigung mit `OK` ist dein neuer Shortcut überall in Ultraschall verfügbar. (Du erkennst, dass er global ist, wenn unten in der Liste das Schlagwort "(global)" hinter dem Shortcut steht.)

![Shortcuts Global](https://raw.githubusercontent.com/Ultraschall/ultraschall-manual/main/assets/images/Anpassungen-und-Shortcuts/globale_shortcuts.gif)

:::note Hinweis
Wichtig ist, hierbei darauf zu achten, dass du in der Scope-Auswahlliste NICHT `Global + text fields` auswählst, sonst wird dein Shortcut auch dann ausgelöst, wenn du irgendwo einen Text eintippst (zum Beispiel bei der Benennung von Kapitelmarken). Und das willst du in der Regel nicht.
:::

### Eigene Shortcuts anlegen und benutzen

In diesem Beispiel ändern wir den eben gesetzten Shortcut <kbd>Alt</kbd> + <kbd>Eingabe</kbd> so ab, dass er nicht global gesetzt ist, sondern nur dann funktioniert, wenn der Tastaturfokus auf den [Spuren [23]](GUI-overview) oder dem [Mixer [24]](GUI-overview) liegt. Dazu findest du im `Actions`-Dialog den praktischen Button `Find shortcut`. Dort gibst du dann den Shortcut ein und landest so in der damit verknüpften Action. Dort machst du im Prinzip das Gleiche wie vorher bei der Zuordnung: Du klickst auf `Add…` und gibst den Shortcut nochmal ein, also hier <kbd>Alt</kbd> + <kbd>Eingabe</kbd>. Achte bitte darauf, dass in der `Scope`-Dropdown-Liste `Normal` ausgewählt ist. Danach bestätigst du mit `OK`.

![Shortcuts Local](https://raw.githubusercontent.com/Ultraschall/ultraschall-manual/main/assets/images/Anpassungen-und-Shortcuts/lokale_shortcuts.gif)

Du erkennst, dass dein Shortcut richtig gesetzt ist, wenn in der Shortcut-Liste unten KEIN "(global)" mehr hinter der Shortcut-Bezeichnung steht.

## Ultraschall Settings

Über das Podcast-Menü oder den Tastatur-Shortcut <kbd>;</kbd> werden die Ultraschall-Settings angezeigt. Diese sind über Tabs in drei Bereiche gegliedert: <kbd>GENERAL</kbd>, <kbd>SOUNDCHECK</kbd> sowie <kbd>INTERFACES</kbd>.

### General Settings

![general-settings](https://raw.githubusercontent.com/Ultraschall/ultraschall-manual/main/assets/images/Anpassungen-und-Shortcuts/settings_general.png))

Folgende Einstellungen können vorgenommen werden:

* Show the start screen
  * Show Ultraschall start screen on launch
* Check for updates
  * Check for Ultraschall updates on launch. Only a message is displayed. No further data is transferred.
* Preroll time preview
  * Set the time in seconds by which the program jumps back when the <kbd>p</kbd> key is used to preview cuts.
* Preroll time recording
  * Set the time in seconds by which the program jumps back for a preroll recording.
* Preshow music mix
  * Play some music from the Ultraschall-Soundboard in your preshow to entertain the livestream. If you choose the preshow routing preset, you can mix none (0) some or all (1) of the music to your headphones mix.
* Soundboard ducking during recording
  * Activate ducking of the soundboard during recording. If anyone starts to talk to a microphone, the Soundboard track will be gently reduced in volume.
* Soundboard ducking during editing
  * Activate ducking of the soundboard during editing. If anyone starts to talk to a microphone, the Soundboard track will be gently reduced in volume.
* Marker ping sound during playback
  * Play a sound if a chapter- oder edit-marker is passed during playback
* Volume of Ping-Sound
  * Set volume of the ping sound
*  Followmode auto detection
  * Turns off Follow Mode when clicking into Arrange View. Disable this if you encounter problems with the Followmode.
* Graceful Soundcheck
  * Set all open soundcheck warnings to the _ignore_ state by closing the soundcheck window.
* Recording safemode
  * Warn about an unwanted stop of the recording after hitting <kbd>SPACE</kbd> or <kbd>RETURN</kbd>.
* Autocolor tracks - Sonic Rainboom
  * New tracks get a unique color. Local tracks start with blue, remote tracks (StudioLink) will be orange and the Soundboard grey.
* Autoarrange track height
  * Zoom or shrink tracks to fit the arrangeview|if new tracks or envelopes are added.    
* Large marker manager
  * Give way more space to the marker manager on the right.  

### Soundcheck Settings

![soundcheck-settings](https://raw.githubusercontent.com/Ultraschall/ultraschall-manual/main/assets/images/Anpassungen-und-Shortcuts/settings_soundcheck.png)

### Interfaces Settings für direct monitoring

![interfaces-settings](https://raw.githubusercontent.com/Ultraschall/ultraschall-manual/main/assets/images/Anpassungen-und-Shortcuts/settings_interfaces.png)

<!-- [ ] ToDo für V2: das Kapitel existiert noch nicht
## Kontrollgeräte verwenden (Midi, OSC, etc.)

:::info Info
Du kannst alle Shortcuts auch per Midi und OSC ansteuern. Hinweise dazu sind im Kapitel [Sonstiges](https://pad.gwdg.de/sLRAFF9eS0OwYFuobe_wZw#) zu finden.
:::
-->
