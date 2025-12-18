# 📱 Smartwatch „Notfalldaten“ – Kurzdokumentation

Diese Oberfläche ist ein **interaktiver Smartwatch-Prototyp** für den Notfall- und Gesundheitsbereich.  
Sie ist so aufgebaut, dass **Rettungskräfte oder medizinisches Personal sofort die wichtigsten Informationen sehen**, aber auch Detailansichten aufrufen können.

---

## 🧭 Grundprinzip

- Die Uhr besteht aus **mehreren Screens (Ansichten)**  
- **Immer nur ein Screen ist sichtbar**
- Die Navigation erfolgt über Buttons und klickbare Bereiche
- Technisch wird das über eine einfache Screen-Umschaltfunktion gelöst

---

## 🏠 Screen 1 – *Notfalldaten* (Startscreen)

Das ist der **zentrale Überblick**.

### Inhalte
- **Patientendaten**
  - Name
  - Alter
  - Blutdruck
- **Profilbild** (Platzhalter)

### SOS-Button
- Rot, oben rechts
- Aktuell rein visuell
- Gedacht für:
  - Notruf
  - Alarm
  - Standortübermittlung (später erweiterbar)

---

### 🩺 Vorerkrankungen (linke Box)
- Eigene, unabhängige Box
- Zeigt relevante medizinische Risiken
- Keine Interaktion
- Gedacht für schnelles Erfassen im Notfall

---

### 👟 Schritte (rechte Box)
- Ebenfalls **eine eigene Box**
- Hat **nichts mit den Vorerkrankungen zu tun**
- Zeigt aktuelle Schrittzahl

**Interaktion:**
- Antippen öffnet die **Schrittzähler-Detailansicht (Screen 4)**

---

### ❤️ EKG-Vorschau
- Kleine animierte EKG-Darstellung
- Gibt schnellen visuellen Eindruck

**Interaktion:**
- Antippen öffnet das **Live-EKG (Screen 2)**

---

### 💊 Medikamentenliste-Button
- Öffnet die **Medikamentenübersicht (Screen 3)**

---

## 📈 Screen 2 – *Live EKG*

Detaillierte Herzaktivitätsansicht.

### Inhalte
- Größeres, animiertes EKG
- Hinweistext:
  > „Finger auf Crown halten“

### Navigation
- **‹ Zurück**
  - Bringt dich zurück zu den Notfalldaten (Screen 1)

---

## 💊 Screen 3 – *Medikamentenliste*

Übersicht über Medikamente und Einnahmezeiten.

### Darstellung
- ✔ Bereits eingenommen → ausgegraut
- ⏳ Noch offen → aktiv sichtbar

### Floating Action Button (+)
- Platzhalter für „Medikament hinzufügen“
- Aktuell ohne Funktion
- Zeigt geplante Erweiterbarkeit

### Navigation
- **‹ Zurück**
  - Zurück zu Screen 1

---

## 👟 Screen 4 – *Schrittzähler (Detailansicht)*

Detailansicht der körperlichen Aktivität.

### Inhalte
- Große Schrittzahl („heute“)
- Fortschrittsbalken zum Tagesziel (10.000 Schritte)
- Kleine Aktivitäts-Historie (Zeit + Schritte)

### Navigation
- **‹ Zurück**
  - Zurück zu den Notfalldaten (Screen 1)

---

## ⚙️ Technisches Verhalten (einfach erklärt)

### Screen-Wechsel
Alle Screens sind im DOM vorhanden, aber:
- nur der aktive Screen hat die Klasse `active`
- ein Klick ruft `go(n)` auf

```js
go(1) → Notfalldaten  
go(2) → Live EKG  
go(3) → Medikamentenliste  
go(4) → Schrittzähler Detail
