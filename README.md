# BoostLab Minecraft (Web Edition)

Dies ist die optimierte Web-Version deines Minecraft-Klons. Du kannst sie ganz einfach direkt im Internet hosten, sodass jeder auf deinem Discord-Server ohne Download mitspielen kann!

## Features (Aktualisiert)
- **Echtes Abbauen und Platzieren**: Zielen (Fadenkreuz) und Links-/Rechtsklick funktionieren!
- **Hotbar & Blöcke**: Drücke 1-9 um zwischen Erde, Gras, Stein, Holz, Sand etc. zu wechseln.
- **Terrain Generation**: Eine komplette Landschaft wird mathematisch (Simplex Noise) beim Start generiert.
- **Web-Optimiert**: Keine komplizierte Tauri/Rust-Kompilierung mehr nötig.

## Wie du das Spiel online bringst (Für deine Freunde)
Die absolut einfachste Methode ist **Vercel** (Kostenlos):
1. Gehe auf [Vercel.com](https://vercel.com) und erstelle dir einen kostenlosen Account (am besten mit GitHub).
2. Lade diesen gesamten entpackten Ordner in ein neues Repository auf deinem [GitHub-Account](https://github.com/) hoch.
3. Klicke in Vercel auf "Add New -> Project" und wähle dein hochgeladenes GitHub-Projekt aus.
4. Vercel erkennt automatisch, dass es ein React/Vite-Projekt ist. Klicke einfach auf **Deploy**.
5. Nach 2 Minuten bekommst du einen Link. Den Link postest du in deinen Discord – fertig!

## Lokales Testen (Auf deinem PC)
Wenn du es erst selbst testen willst, bevor du es online stellst:
1. Node.js installieren.
2. Terminal in diesem Ordner öffnen.
3. `npm install` eingeben.
4. `npm run dev` eingeben.
5. Den Link `http://localhost:3000` im Browser öffnen.
