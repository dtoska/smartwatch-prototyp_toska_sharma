# Smartwatch „Notfalldaten“
### Dion Toska · Yannis Sharma

## Überblick  
Diese Anwendung ist ein interaktiver Smartwatch-Prototyp für den Notfall- und Gesundheitsbereich. Ziel ist es, dass Rettungskräfte oder medizinisches Personal innerhalb weniger Sekunden die wichtigsten Informationen erfassen können und bei Bedarf direkt in Detailansichten wechseln.

## Grundidee  
Die Oberfläche besteht aus mehreren Screens, von denen immer nur einer gleichzeitig sichtbar ist. Die Navigation erfolgt über Buttons oder klickbare Bereiche innerhalb der Uhr. Technisch wird dies über eine einfache Umschaltfunktion realisiert, die den jeweils aktiven Screen einblendet.

## Screen 1 – Notfalldaten  
Der Startscreen dient als zentraler Überblick im Notfall. Er zeigt die wichtigsten Patientendaten wie Name, Alter und Blutdruck sowie ein Profilbild als Platzhalter. Oben rechts befindet sich ein roter SOS-Button, der aktuell nur visuell vorhanden ist, aber für zukünftige Funktionen wie Notruf oder Alarmierung vorgesehen ist.

Im unteren Bereich befinden sich zwei voneinander unabhängige Boxen auf schwarzem Hintergrund. In der linken Box werden relevante Vorerkrankungen angezeigt, die schnell erfasst werden sollen und keine Interaktion besitzen. In der rechten Box wird die aktuelle Schrittzahl dargestellt. Diese Box ist interaktiv und führt bei Antippen zur detaillierten Schrittansicht.

Zusätzlich enthält der Screen eine kleine animierte EKG-Vorschau, die einen schnellen Eindruck der Herzaktivität vermittelt. Durch Antippen gelangt man in die Live-EKG-Ansicht. Über einen weiteren Button kann außerdem die Medikamentenliste geöffnet werden.

## Screen 2 – Live EKG  
Dieser Screen zeigt eine vergrößerte, animierte EKG-Darstellung. Ein kurzer Hinweistext fordert dazu auf, den Finger auf der Crown zu halten, um eine Messung zu simulieren. Über einen Zurück-Button gelangt man wieder zur Notfalldaten-Übersicht.

## Screen 3 – Medikamentenliste  
In der Medikamentenliste werden alle relevanten Medikamente mit ihren Einnahmezeiten angezeigt. Bereits eingenommene Medikamente sind visuell abgeschwächt, während noch ausstehende klar hervorgehoben werden. Ein schwebender Plus-Button deutet die Möglichkeit an, neue Medikamente hinzuzufügen, ist aktuell jedoch nur als Platzhalter gedacht. Auch hier führt ein Zurück-Button wieder zum Startscreen.

## Screen 4 – Schrittzähler  
Die Schrittzähler-Detailansicht zeigt die aktuelle Tages-Schrittzahl in großer Darstellung sowie einen Fortschrittsbalken im Verhältnis zum Tagesziel von 10.000 Schritten. Ergänzend wird ein kleiner Verlauf mit Zeitangaben angezeigt. Über den Zurück-Button gelangt man wieder zu den Notfalldaten.

## Ziel des Prototyps  
Der Fokus liegt auf einer klaren, ruhigen Darstellung mit schneller Orientierung im Notfall. Unterschiedliche Informationsbereiche sind bewusst getrennt, um Überforderung zu vermeiden. Der Prototyp bildet eine realistische Smartwatch-User-Experience ab und dient als solide Grundlage für funktionale Erweiterungen.
