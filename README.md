# Home Assistant Blueprints: Wetterwarnung

Diese ZIP-Datei enthält zwei Blueprints zur Verarbeitung von Wetterwarnungen in Home Assistant.

## 📁 Inhalte

- `blueprints/script/wetterwarnung.yaml`: Skript-Blueprint zum Erstellen von Benachrichtigungen
- `blueprints/automation/wetterwarnung_auto.yaml`: Automation-Blueprint zur automatischen Steuerung
- `README.md`: Diese Anleitung

## 🛠️ Verwendung

1. Lege in deinem Home Assistant je ein Skript und eine Automation auf Basis dieser Blueprints an.
2. Wähle beim Erstellen die passenden Eingaben:
   - Den Sensor, der die Wetterwarnungen liefert (z. B. DWD)
   - Dein mobiles Gerät für Push-Benachrichtigungen
3. Aktiviere die Automation. Sie reagiert automatisch auf neue oder beendete Warnungen.

## Hinweis

Die Blueprints sind allgemein gehalten und enthalten keinen Stadtnamen. Du kannst sie für beliebige Regionen verwenden.
