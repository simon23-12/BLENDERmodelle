# LMG 3D Modellierung

Übersichtsseite der interaktiven 3D-Unterrichtsmodelle von LMG TECH – in Blender modelliert, im Browser mit Three.js erkundbar.

**Online:** https://simon23-12.github.io/BLENDERmodelle/

| Fach | Modell | Repo |
| --- | --- | --- |
| Physik | Der Viertaktmotor | [BLENDERviertaktmotor](https://github.com/simon23-12/BLENDERviertaktmotor) |
| Chemie | Kochsalz löst sich | [BLENDERnaclsolution](https://github.com/simon23-12/BLENDERnaclsolution) |
| Chemie | Der Akku von innen | [BLENDERakku](https://github.com/simon23-12/BLENDERakku) |
| Biologie | Kinesin läuft | [BLENDERkinesinmicrotubula](https://github.com/simon23-12/BLENDERkinesinmicrotubula) |
| Erdkunde | Platten in Bewegung | [BLENDERtektonik](https://github.com/simon23-12/BLENDERtektonik) |
| Geschichte | Gutenberg druckt | [BLENDERgpress](https://github.com/simon23-12/BLENDERgpress) |
| Mathematik | Vektoren im Raum | [BLENDERmath](https://github.com/simon23-12/BLENDERmath) |

Statische Seite in `web/` (eine HTML-Datei, kein Build); jeder Push auf `main` veröffentlicht sie über GitHub Pages. Die Vorschaubilder in `web/img/` sind Blender-Renderings der jeweiligen Szenen. Ein neues Modell kommt als Eintrag in die Liste `PROJECTS` in `web/index.html` dazu.

Lokal: `node serve.mjs` → http://127.0.0.1:5173
