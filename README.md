# Smartwatch „Notfalldaten“
### Dion Toska · Yannis Sharma

---

## Überblick

Diese Oberfläche ist ein **interaktiver Smartwatch-Prototyp** für den Notfall- und Gesundheitsbereich.  
Sie ist darauf ausgelegt, dass **Rettungskräfte oder medizinisches Personal sofort die wichtigsten Informationen erfassen** können und bei Bedarf in Detailansichten wechseln.

---

## Grundprinzip

- Die Uhr besteht aus **mehreren Screens (Ansichten)**
- **Immer nur ein Screen ist sichtbar**
- Navigation erfolgt über Buttons oder klickbare Bereiche
- Technisch wird das über eine einfache Screen-Umschaltfunktion realisiert

---

## Screen 1 – Notfalldaten (Startscreen)

Der zentrale Überblick im Notfall.

### Inhalte
- **Patientendaten**
  - Name
  - Alter
  - Blutdruck
- **Profilbild** (Platzhalter)

### SOS-Button
- Rot, oben rechts
- Aktuell rein visuell
- Gedacht für spätere Erweiterungen wie:
  - Notruf
  - Alarmierung
  - Standortübermittlung

---

### Vorerkrankungen (linke Box)
- Eigene, unabhängige Box
- Zeigt medizinisch relevante Risiken
- Keine Interaktion
- Gedacht für schnelles Erfassen im Notfall

---

### Schritte (rechte Box)
- Ebenfalls eine **eigenständige Box**
- Steht bewusst **unabhängig von den Vorerkrankungen**
- Zeigt aktuelle Schrittzahl

**Interaktion:**
- Antippen öffnet die Schrittzähler-Detailansicht (Screen 4)

---

### EKG-Vorschau
- Kleine animierte EKG-Darstellung
- Gibt einen schnellen visuellen Eindruck der Herzaktivität

**Interaktion:**
- Antippen öffnet das Live-EKG (Screen 2)

---

### Medikamentenliste-Button
- Öffnet die Medikamentenübersicht (Screen 3)

---

## Screen 2 – Live EKG

Detaillierte Herzaktivitätsansicht.

### Inhalte
- Größere, animierte EKG-Darstellung
- Hinweistext:
  > „Finger auf Crown halten“

### Navigation
- **Zurück**
  - Wechsel zurück zu den Notfalldaten (Screen 1)

---

## Screen 3 – Medikamentenliste

Übersicht über Medikamente und Einnahmezeiten.

### Darstellung
- Bereits eingenommene Medikamente sind visuell abgeschwächt
- Noch ausstehende Medikamente sind aktiv dargestellt

### Floating Action Button
- Platzhalter für „Medikament hinzufügen“
- Aktuell ohne Funktion
- Zeigt geplante Erweiterbarkeit

### Navigation
- **Zurück**
  - Wechsel zurück zu Screen 1

---

## Screen 4 – Schrittzähler (Detailansicht)

Detailansicht der täglichen Aktivität.

### Inhalte
- Große Anzeige der heutigen Schrittzahl
- Fortschrittsbalken im Verhältnis zum Tagesziel (10.000 Schritte)
- Kleine Aktivitäts-Historie mit Uhrzeit und Schritten

### Navigation
- **Zurück**
  - Wechsel zurück zu den Notfalldaten (Screen 1)

---

hrittzähler Detail
