# Preamplificator Audio cu Amplificare Controlată de Tensiune

## Universitatea „Politehnica” din București
### Facultatea de Electronică, Telecomunicații și Tehnologia Informației
#### Anul universitar 2024-2025

### Proiect 1 - Proiectarea și realizarea unui preamplificator audio cu amplificare controlată de tensiune

Coordonatori științifici:
- Prof. dr. ing. Dragoș Dobrescu
- Prof. dr. ing. Vasile Mădălin Moise

Grupa 432B

---

![1.](Layout/pcb.jpg?raw=true "Title")



## Introducere

În domeniul electronicii audio, obținerea unei preamplificări fidele și stabile este esențială pentru a asigura o experiență de audiție de înaltă calitate. Preamplificatorul reprezintă prima verigă din lanțul de procesare a semnalelor, responsabil de amplificarea acestora de la nivele foarte mici (ex. microfon, pick-up) la un nivel suficient de ridicat, astfel încât semnalul să poată fi procesat sau transmis către un amplificator de putere.

Obiectivul acestui proiect este realizarea unui preamplificator audio cu amplificare controlată de tensiune, capabil să ofere un control dinamic al câștigului, variind între 1 și 30, în funcție de tensiunea de control aplicată (0–3V). Acesta va opera la o tensiune de alimentare de 13V și va asigura o performanță audio de calitate.

---

## Date inițiale de proiectare

### Descrierea temei

Proiectul constă în proiectarea și realizarea unui preamplificator audio cu amplificare controlată de tensiune. Principalele cerințe sunt:
- **Tensiune de alimentare**: 13V unipolară sau ±13V bipolară
- **Semnal de intrare**: 0–30mV la 3kHz
- **Controlul amplificării**: Tensiune de control între 0–3V
- **Ieșire**: Preamplificatorul va conduce o sarcină de 800 Ω

### Schema bloc a montajului electric

Schema bloc a circuitului include etaje precum:
- Etajul **Emitor Comun (EC)**: Amplificare de tensiune substanțială
- Etajul **Bază Comună (BC)**: Stabilitate și câștig suplimentar
- Etajul **Colector Comun (CC)**: Adaptarea de impedanță și amplificare de curent


### Mod de realizare

1. **Unelte și materiale necesare**:
    - Pasta de lipit
    - Stație de reflow
    - Pensetă antistatică
    - Flux suplimentar
2. **Procedura de lipire (Reflow)**:
    - Pregătirea PCB-ului
    - Aplicarea pastei de lipit
    - Plasarea componentelor SMD
    - Profilul termic de reflow

---

## Manual de utilizare

Preamplificatorul audio este ușor de utilizat urmând pașii de mai jos:
1. **Conectarea alimentării**:
    - Conectează borna negativă la GND și borna pozitivă la VCC.
2. **Semnalul de intrare**:
    - Conectează semnalul audio la borna IN.
3. **Controlul amplificării**:
    - Ajustează tensiunea de control (0-3V) pentru a modifica câștigul.
4. **Ieșirea audio**:
    - Conectează ieșirea la echipamentele audio externe.

---

## Concluzii

Acest proiect reprezintă realizarea unui preamplificator audio eficient cu amplificare controlată de tensiune, util atât în aplicații profesionale cât și hobby. Performanțele obținute în urma testărilor și simulărilor au confirmat funcționalitatea și fiabilitatea circuitului.

---

## Bibliografie

- Manuale tehnice privind amplificatoarele audio
- Ghiduri pentru realizarea PCB-urilor și a tehnologiei SMT

