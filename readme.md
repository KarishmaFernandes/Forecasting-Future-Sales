# Assignment

Erstelle eine Data Science Pipeline, die folgende Komponenten beinhaltet:
- Daten Laden
- Daten aufbereiten (Achte auf Datenfehler)
- Modell trainieren
- Vorhersage

Die Daten werden dir zur Verfügung gestellt. Das Modell sollte die zukünftigen Verkäufe eines Artikels für die nächsten x-Tage vorhersagen (Kein Fokus auf Genauigkeit).

Achte auf:
- Fundierte EDA (Explorative Datenanalyse)
- Wiederverwendbarkeit
- Dokumentation
- Erweiterbarkeit
- Error-Handling

Die Aufgabe ist absichtlich sehr offen gestaltet, damit du deiner Kreativität freien Lauf lassen kannst 🙂. Du kannst dich auch gerne auf Teilaspekte der Aufgabenstellung konzentrieren!

Stell uns deine Arbeit vor (Datenanalyse/Data Insights, Vorhersagen, Herausforderungen) als wären wir der/die Kund*in deines Produkts, wir freuen uns darauf!



# Data Dictionary

orderDate: Date of sale
WGR1: Product Group 
WGR2: Product Group
WGR3: Product Group
WGR4: Product Group
articleNumber: Unique identifier of article
quantity: Amount of sold items
temp: Weather details
dwpt: Weather details
rhum: Weather details
prcp: Weather details
snow: Weather details
wdir: Weather details
wspd: Weather details
wpgt: Weather details
pres: Weather details
tsun: Weather details
coco: Weather details
promotion_article: If there is an article promotion 
promotion_wgr: If there is a product group promotion
promotion_global: If there is a global promotion
public_holiday: If there is a public holiday
school_holiday: If there is a school holiday
sunday: If it is sunday

Weather details are explained here: https://dev.meteostat.net/formats.html#time-format 
Product Groups are coarser than articles, for example: WGR1: Electronics, WGR2: Smartphones, WGR3: Apple, WGR4: iPhone -> Article: iPhone 12
