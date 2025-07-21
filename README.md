# Home Assistant Blueprints: Wetterwarnung

Diese ZIP-Datei enthält zwei Blueprints zur Verarbeitung von Wetterwarnungen in Home Assistant.

## 📁 Inhalte

- `blueprints/script/wetterwarnung.yaml`: Skript-Blueprint zum Erstellen von Benachrichtigungen
- `blueprints/automation/wetterwarnung_auto.yaml`: Automation-Blueprint zur automatischen Steuerung
- `README.md`: Diese Anleitung

## 📥 Import in Home Assistant

Du kannst diesen Blueprint direkt über My Home Assistant importieren:

#Automation
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FNoack1978%2FDWD-Benachrichtigungen-%2Fblob%2Fmain%2Fwetterwarnung.yaml)

#Skript
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FNoack1978%2FDWD-Benachrichtigungen-%2Fblob%2Fmain%2Fwetterwarnung_auto.yaml)

## 🛠️ Verwendung

1. Lege in deinem Home Assistant je ein Skript und eine Automation auf Basis dieser Blueprints an.
2. Wähle beim Erstellen die passenden Eingaben:
   - Den Sensor, der die Wetterwarnungen liefert (z. B. DWD)
   - Dein mobiles Gerät für Push-Benachrichtigungen
3. Aktiviere die Automation. Sie reagiert automatisch auf neue oder beendete Warnungen.

## Hinweis

Die Blueprints sind allgemein gehalten und enthalten keinen Stadtnamen. Du kannst sie für beliebige Regionen verwenden.
