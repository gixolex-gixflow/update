# GixFlow Update Repository

Dieses Repository ist der kostenlose Remote-Update-Speicher für GixFlow Core.

## Wichtig

Keine Ordner verwenden. Diese Dateien liegen direkt im Hauptpfad des GitHub-Repositories:

- `gixflow-updates.json`
- `gixflow-update-001-update-center.zip`
- `README.md`

## GitHub-Einstellungen

Repository-Name:

```text
update
```

Sichtbarkeit:

```text
Public
```

## Feed-Link für GixFlow

Nach dem Upload ersetzt du `DEIN-GITHUB-NAME` durch deinen echten GitHub-Namen.

```text
https://raw.githubusercontent.com/DEIN-GITHUB-NAME/update/main/gixflow-updates.json
```

Diesen Link trägst du im GixFlow Update Center ein.

## ZIP-Link im JSON

Die Update-ZIP liegt direkt im gleichen Repository-Pfad wie die JSON:

```text
https://raw.githubusercontent.com/DEIN-GITHUB-NAME/update/main/gixflow-update-001-update-center.zip
```

## Ablauf bei jedem neuen Update

1. Neue Update-ZIP mit ChatGPT erstellen.
2. ZIP direkt in den Hauptpfad dieses Repositories hochladen.
3. `gixflow-updates.json` bearbeiten.
4. Neue Version, neue Reihenfolge, ZIP-URL und SHA256 eintragen.
5. Im GixFlow Update Center `Feed prüfen` klicken.

## Sicherheit

Keine Passwörter, keine Datenbank-Zugangsdaten, keine Kundeninfos und keine Tokens in dieses öffentliche Repository laden.
