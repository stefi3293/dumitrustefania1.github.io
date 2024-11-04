 # Diagrame de tip _Flowchart_

```mermeid
flowchart LR

A[/ANUL I/] -.->|tranzitie usoara| B[\Anul II\]
A -.->|Tranzitie grea| C(anul IIII)
```
**De retinut**
- Diagramele _flowcharte_ au _noduri_ si _conectori_
- Nodurile au:
-  **Forma** (dara de parantezele flodite la descriere _nodului_)
-  ID (sirul folodit in afara descrierii nodului )
-  Descriere (textul ce apare in caseta nodului si care este implementat in interiorul diferitelor tipuri de paranteze -ce decid forma casetei modulului)
-  Conectorii au:
-  Diferite tipuri de sageti sau chair pot activa fara sageti
-  Diferite tipuri de linii:
-  `-->` linie continua (SAGEATA DREAPTA)
- `--` LINIE CONTINUA FARA SAGETI
- `<-->` linia continua cu sageti stanga dreapta
- `==>` linie continua ingrosata

  ```mermaid
  flowchart LR
  A --> B & C & D --> E

  ```
  timeline
  title "My Timeline"
  section "Sectiunea 1"
  2023-2024
     : am luat la facultate
     : am luat contact cu mediul academic
   2024-2025
     : am terminat anul I
     : am facut grafice
  2025-2026
     : am facut practica la fotogrmmetrie
  2026-2027
      :am terminat facultatea 
