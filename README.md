# Fünfzehntes Projekt: Toggle Navigation Menü

Dieses Projekt zeigt eine einfache Navigation mit einem Toggle-Button, der das Menü ein- und ausblendet, wenn darauf geklickt wird. Das Projekt verwendet HTML, CSS und JavaScript, um eine mobile-friendly Navigation zu erstellen.

## Projektstruktur

- **HTML**: Definiert die Struktur der Navigation mit einer Liste von Links und einem Toggle-Button.
- **CSS**: Hier wird das Styling der Navigation sowie der Toggle-Button festgelegt.
- **JavaScript**: Ermöglicht das Ein- und Ausblenden der Navigation durch Hinzufügen und Entfernen der Klasse `active` beim Klick auf den Toggle-Button.

## Funktionsweise

1. **HTML**:
   - Es gibt ein `nav`-Element mit einer ungeordneten Liste (`ul`), die die Navigationseinträge enthält.
   - Ein `button` mit der Klasse `icon` und der ID `toggle` dient als Toggle-Button, um das Menü umzuschalten.
   
2. **CSS**:
   - Das Menü ist standardmäßig sichtbar (durch die Klasse `active`).
   - Es gibt eine `line`-Klasse für den Toggle-Button, um ein Burger-Menü zu erstellen.
   - CSS wird verwendet, um das Menü im Desktop-Modus und im mobilen Modus (beim Klicken des Buttons) ein- oder auszublenden.

3. **JavaScript**:
   - Ein Event-Listener wird auf den Toggle-Button (`toggle`) gesetzt, der beim Klick die Klasse `active` auf das `nav`-Element hinzufügt oder entfernt, was die Sichtbarkeit des Menüs steuert.

## Installation

git clone https://github.com/AkinKale1999/NavbarOnclickGetsSmaller.git
