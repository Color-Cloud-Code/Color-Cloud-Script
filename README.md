# Color Cloud Script (CCS)

Willkommen beim offiziellen Spickzettel für **Color Cloud Script**. Hier findest du alle Befehle auf einen Blick!

---

## 1. Grundlagen
| Befehl | Beschreibung | Beispiel |
| :--- | :--- | :--- |
| **Schreibe** | Gibt Text oder Zahlen im Terminal aus. | `Schreibe "Hallo Welt"` |
| **Variable** | Speichert einen Wert in einem Namen. | `Variable punkte = 10` |
| **Frage** | Wartet auf eine Benutzereingabe. | `Frage "Wie heißt du?"` |
| **Warte** | Pausiert das Programm für X Sekunden. | `Warte 2 Sekunden` |

## 2. Logik & Bedingungen
### Wenn-Abfrage
Prüft, ob eine Bedingung wahr ist.
```ccs
Wenn punkte > 5:
    Schreibe "Du hast gewonnen!"
Ende
```

### Schleifen
Wiederholt Code mehrmals.
```ccs
Wiederhole 5 mal:
    Schreibe "Ich lerne CCS!"
Ende
```

## 3. Fortgeschrittene Funktionen
### Funktionen
Speichere Code-Blöcke für später.
```ccs
Funktion Begruessung ((
    Schreibe "Willkommen in der Cloud!"
))

Aufruf Begruessung
```

### Zufall
Erzeugt eine Zufallszahl zwischen Min und Max.
```ccs
Variable wuerfel = Zufall(1, 6)
```

## 4. Events (Triggers)
Reagiere auf Knöpfe oder Ereignisse.
```ccs
Aktivierung wenn Variable von Aktivierungsschalter Startknopf 1 betätigt wird ((
    Schreibe "Knopf wurde gedrückt!"
))
```

---
**Viel Spaß beim Coden!** 🚀☁️
