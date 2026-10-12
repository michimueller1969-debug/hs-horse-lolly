# HS-Horse Lolly® – Produktseite

Statische Landingpage für das HS-Horse Lolly® von Turnierbedarf Schäfer, Nentershausen.
Stil angelehnt an www.turnierbedarf-schaefer.de (Rosettenrot, Wortmarken-Braun, Chrom-Grau), modernisiert.

## Aufbau

```
index.html   Seite inkl. CSS (keine Build-Tools nötig)
img/         Logo, Produktfotos, Konstruktionsbilder, Video
fonts/       Playfair Display + Inter, lokal eingebunden (kein Google-Fonts-Abruf, DSGVO)
```

## Lokal ansehen

In VS Code die Erweiterung **Live Server** installieren (wird beim Öffnen vorgeschlagen),
dann `index.html` → Rechtsklick → „Open with Live Server“.

## Veröffentlichen

Den Ordnerinhalt (ohne `.git`, `.vscode`) per FTP/SFTP ins Webverzeichnis laden.
Alternativ GitHub Pages: Repo pushen → Settings → Pages → Branch `main`, Ordner `/`.

## Offen

- [ ] Preis und Bestellmöglichkeit (Abschnitt `#bestellen`)
- [ ] Impressum-/AGB-Links im Footer auf die genauen Unterseiten setzen
- [ ] „Gut zu wissen“-Hinweis (LPO) mit Herrn Schäfer abstimmen
- [ ] Pop-up auf der alten Seite mit Link zur neuen Adresse
- [ ] Logo als Vektordatei (SVG), falls vorhanden

## Farben

| Token | Wert | Verwendung |
|---|---|---|
| brand-red | `#ac0f0a` | Buttons, Akzente (Rosette) |
| brand-brown | `#644e43` | Serifen-Akzente (Wortmarke) |
| steel-dark | `#313131` | Kopf-/Fußband, dunkle Sektion |
| ink | `#2b2523` | Text |
| surface-alt | `#f4f2f1` | abgesetzte Bereiche |
