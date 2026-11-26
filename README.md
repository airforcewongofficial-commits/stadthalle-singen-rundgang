# 360°-Rundgang Stadthalle Singen (Entwurf)

Virtueller Rundgang durch die Stadthalle Singen, gestaltet im Design des Imagevideos (Magenta/Schwarz, Montserrat).
Aufnahmen und Umsetzung: Air.Force.Wong UG, Frankfurt am Main.

**Stand 26.11.2026:** Raumwerte wie in den finalen Bannern des Imagevideos (Kapazitäten laut Stadthalle, Bestuhlungspläne 12.11.2026; mit „ca.“ gekennzeichnete Flächen aus dem Gebäudemodell errechnet).

## Standorte
Außenansicht · Foyer Eingang · Foyer Thüga Saal · Thüga Saal (Saalmitte, mit Reihenbestuhlung, vor der Bühne) · Rang vorne · Rang oben · Empore · Tagungsraum 1–3 · Seminarraum 1+2

## In eine Website einbauen

```html
<iframe src="https://<benutzer>.github.io/stadthalle-singen-rundgang/"
        title="360°-Rundgang Stadthalle Singen"
        style="width:100%;aspect-ratio:16/9;min-height:480px;border:0"
        allow="fullscreen; accelerometer; gyroscope"
        allowfullscreen loading="lazy"></iframe>
```

## Technik
- Reine statische Seite (HTML/CSS/JS), keine Datenbank, kein Build-Schritt
- Panorama-Viewer: [Pannellum](https://pannellum.org) 2.5.6 (MIT-Lizenz), lokal eingebunden
- Schrift Montserrat (SIL Open Font License), lokal eingebunden – keine Verbindung zu Google-Servern
- Panoramen in zwei Größen: `img/pano/` (8000 × 4000) und `img/pano-sm/` (4096 × 2048); die Seite wählt je nach Gerät automatisch
- Raumtexte und Werte stehen im Skript von `index.html` im Block `ROOMS`
