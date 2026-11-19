# schnitt-modelle

Modelle für die Schnitt-Skills (`reel-schnitt`, `langvideo-schnitt`, `story-producer`): Spracherkennung, Stimmabdruck, Gesichtserkennung, Entrauschen, Freistellung. Alle Dateien sind **unverändert** aus den Originalquellen übernommen, damit die Einrichtung nur github.com braucht.

Dateien über 90 MB sind geteilt (`model.bin.teil00` …). `kern/einrichten.py` aus dem Werkzeug der Skills holt dieses Repo selbst, setzt die Teile zusammen und prüft jede Datei gegen ihre SHA-256-Prüfsumme (`PRUEFSUMMEN.txt`, dort steht auch die Originalquelle je Datei).

Von Hand:
```bash
git clone --depth 1 https://github.com/ponytruppedresden-source/schnitt-modelle ~/content-werkzeug-modelle
python3 -I ~/content-werkzeug/kern/einrichten.py      # -> EINRICHTUNG OK
```

Herkunft und Lizenzen: `LIZENZEN.md`. Dieses Repo enthält keinen eigenen Code und keine eigenen Inhalte.
