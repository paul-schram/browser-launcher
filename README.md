## Browser Startseite

### Features

Sofort einsatzbereit: Keine Installation oder Downloads nötig – einfach die URL aufrufen.

Drag & Drop: Sortiere deine Shortcuts intuitiv per Maus. Die Reihenfolge wird automatisch gespeichert.

Anpassbare Shortcuts: Bearbeite Namen, URLs und Icons direkt in der App. Das Protokoll (https://) wird automatisch ergänzt.

Icon-Datenbank: Wähle aus einer kuratierten Liste beliebter Icons (FontAwesome).

Smart Search: Integrierte Google-Suche mit visuellem Feedback (Enter-Badge) und Hotkey-Support (/).

Privatsphäre: Alle Einstellungen werden ausschließlich via Local Storage in deinem eigenen Browser gespeichert.

### Nutzung

Du kannst die Seite auf zwei Arten nutzen: Entweder über GitHub Pages oder indem du sie selbst hostest. Für den Einstieg empfehle ich die GitHub-Pages Seite:

👉 https://paul-schram.github.io/browser-launcher/

### 1. Als "Neuer Tab" Seite einrichten (Wichtig)

Moderne Browser erlauben es aus Sicherheitsgründen meist nicht, die "Neuer Tab"-Seite direkt über die Einstellungen zu ändern. Daher ist die Nutzung einer kleinen Erweiterung erforderlich:

Installiere eine Erweiterung wie "Custom New Tab URL" (für Chrome/Edge)

Trage in den Optionen der Erweiterung die URL ein: https://paul-schram.github.io/browser-launcher/

Bestätige beim ersten Öffnen eines neuen Tabs, dass du die Änderung beibehalten möchtest.

### 2. Als Startseite festlegen

Kopiere die URL und trage sie in deinem Browser als Startseite ein, damit sie sich beim Browserstart automatisch öffnet:

Chrome: Einstellungen > Erscheinungsbild > Schaltfläche "Startseite" anzeigen > Deine URL eingeben.

Firefox: Einstellungen > Startseite > Neue Fenster und Tabs > Benutzerdefinierte URLs.

Edge: Einstellungen > Start, Startseite und neue Registerkarten.

Hinweis: Da die Daten im Local Storage deines Browsers gespeichert werden, bleiben deine Shortcuts erhalten, solange du deine Browserdaten für diese Domain nicht löschst.

### Technologien

HTML5 / CSS3 (Custom Properties & Animations)

Tailwind CSS (via CDN)

FontAwesome Icons (via CDN)

Vanilla JavaScript (ES6+)