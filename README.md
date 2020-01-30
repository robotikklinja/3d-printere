# 3D-Printere
### [Midlertidig køsystem!](https://docs.google.com/document/d/1-oxqKc14jag_Qz2laUNbbtoBmCuNLyVew2syaTiFzV8/edit?usp=sharing)

Vi har to printere, de heter **Prusa I3 MK3S**.

Slicers som vi kan bruke er [PrusaSlicer](https://cdn.prusa3d.com/downloads/drivers/prusa3d_win_2_2_8.exe#_ga=2.168176611.334666038.1575547204-1800476386.1574322674) eller [Ultimaker Cura](https://ultimaker.com/software/ultimaker-cura). 

Nozzle er på **0,4mm**, så husk på å konfigurere dette når du laster ned sliceren.


## Bruk av 3D-printer (Guides)

- [Hvordan lage en G-code fil?](https://github.com/robotikklinja/3d-printere/blob/master/Guide/Hvordan%20lage%20en%20G-code%20fil.md)
- [Hvordan starte printerne?](https://github.com/robotikklinja/3d-printere/blob/master/Guide/Starte%20printeren.md)
- [Hvordan ta av en print?](https://github.com/robotikklinja/3d-printere/blob/master/Guide/Ta%20av%20en%20print.md)
- [Vanlige feil på printer](https://github.com/robotikklinja/3d-printere/blob/master/Guide/Vanlige%20feil.md)
- [Bruk av Køsystemet](./QUEUE.md) Foreløpig ikke aktiv.

## Status

### Dokumenter til senere bruk
- [Kabinettbyggings-guide](https://blog.prusaprinters.org/cheap-simple-3d-printer-enclosure/)

### Status for internett kobling

**09/01/2020**

- Raspberry Pi har problemer pga power supply. Løsning: bestill powersupply som tilhører modellen.
- Venter på bestillinger

**15/01/2020**

- Ny router er satt opp
- Venter på bestillinger

## OctoPi

Det var satt opp en OctoPi instance, men Raspberry Pi-en har møtt noen hardware problemer. Man kan fortsatt printe via SD-kort.

## Videre Planer

- [x] Sette opp 3D-printer queue system
- [x] Lage brukermanual til printerne (Gjort, men burde arbeides mer med)
- [ ] Deploye 3D-printer queue system
- [ ] Bytte ut med 2x Raspberry Pi 4
- [ ] Sette opp overvåking av printeren (kamera)
- [ ] Styre alle printere over nettet
- [ ] Sette opp kabinetter
