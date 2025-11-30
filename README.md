# node.corecraftgenesis.ch

# CoreCraft Genesis Node (audit-sealed)

Eine transparente, audit-sealed Referenzseite für die CoreCraft Genesis Node. Ziel: öffentlich nachvollziehbare Artefakte, klare Abgrenzung, und ein kulturell wie technisch belastbarer Vertrauensanker.

## Inhalte
- Einführung und historischer Bezug (Bitcoin Genesis Block)
- Technische Eckdaten (Chain-ID 200624, Genesis 0x00, Validator-Adresse, DNSSeed)
- Injektion/Einspeisung audit-sealed Artefakte
- Download-Links zu Artefakten und Manifesten
- Abgrenzung zu Mars-networks „ares-1“
- Timeline von Bitcoin Genesis zu CoreCraft Genesis

---

## Struktur

root/ 
    index.html styles.css 
    
assets/ artefacts/ ip-logs/ 
                          # Zeitgestempelte IP-Logs snapshots/        
                          # Versionierte Chain-Snapshots hardware.txt       
                          # Hardwarebeschreibung cids.txt          
                          # Optionale IPFS-CIDs manifests/ genesis.json      
                          # Audit-sealed Manifest images/ timeline.png     
                          # Optionale Timeline-Grafik docs/ index.html       
                          # Erweiterte Dokumentation (optional) impressum.html      
                          # Kontakt / rechtliche Angaben
---

## Veröffentlichung
- GitHub Pages aktivieren (Settings → Pages → Deploy from branch).
- `index.html` dient als Einstiegsseite.
- Alle Dateien in UTF-8 ohne BOM speichern.

## Audit-Hinweise
- Commits taggen (z. B. `v1.0.0-audit`).
- Commit-Hash und Datei-Hashes in `assets/artefacts/cids.txt` dokumentieren.
- Optional: Manifest (genesis.json) auf IPFS pinnen, CID veröffentlichen.
- Standortwechsel stets in Artefakten und Impressum nachführen.

## Lizenz
- Füge eine klare Lizenz hinzu (z. B. MIT), um Replikation und externe Prüfung zu ermöglichen.
