# Fit Generator

Eine Webseite, auf der man sich Outfits an einer 3D-Figur zusammenstellt.

`fit-generator.html` läuft als Claude-Artifact auf claude.ai, daher braucht es keinen API-Key.

## Stand

- **Schritt 1 (fertig):** 3D-Figur (männlich/weiblich, Größe, Statur, Hautton) mit Kleidungsvorlagen zum An- und Ausziehen: T-Shirt, Longsleeve, Pullover, Hoodie, Hemd, Jacke, Mantel, Jeans, Chino, Jogginghose, Shorts, Rock, Sneaker, Boots, Loafer. Farben und Muster sind frei wählbar.
- **Schritt 2:** Kleidung per Foto hinzufügen. Claude erkennt Art, Farbe und Stil, das Foto wird als Textur angezogen.
- **Schritt 3:** Outfit-Vorschläge nach Anlass und Stilrichtung.

Technik: Three.js 0.160 (über jsDelivr), sonst reines HTML/JS.
