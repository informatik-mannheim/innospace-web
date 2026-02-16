---
layout: collection
title: Liveable
section_id: portfolio
year: 2025
program: PIY


image:
  - /images/@projects/liveable2.png
  - /images/@projects/liveable3.png
  - /images/@projects/liveable4.jpg
 
---

### **MoldGuard** 
MoldGuard ist ein zweiteiliges Frühwarnsystem, das Schimmel verhindern soll, bevor er
sichtbar wird. Die Idee ist, nicht erst auf Schimmel zu reagieren, sondern früh zu erkennen,
wann Kondensation an einer kalten Wand wahrscheinlich wird. Dafür misst ein Sensorgerät
kontinuierlich Temperatur und relative Luftfeuchte (rLF) an zwei Stellen: an der Wand und
in der Raumluft. Aus den Messwerten wird der Taupunkt (TP) berechnet und daraus ein
Status abgeleitet. Die Ausgabe läuft über eine HomeStation mit Raspberry Pi (RPi), Display
und LED-Streifen. Auf dem Display werden Live-Werte, Status und eine konkrete
Handlungsempfehlung angezeigt, zusätzlich zeigt der LED-Streifen den Status visuell an.
Das System arbeitet mit vier Statusstufen (Alles ok, Vorwarnung, Kritisch, Schimmelgefahr
hoch) plus einem Offline-Status.
Die Messdaten kommen vom ESP32 per Message Queuing Telemetry Transport (MQTT)
und werden über einen MQTT-Server an die HomeStation weitergeleitet.
