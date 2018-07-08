# NBNO.py
NB.no nedlaster


For å kjøre denne koden trengs Python 2.7 og pillow.
For å sjekke om du har python 2.7, kjør **python --version** fra kommandolinjen.

Python 2.7 kan lastes ned fra https://www.python.org/download/releases/2.7/ Pillow legges til ved å kjøre **pip install pillow** eller **easy_install pillow** etter python er installert (Husk å få med at Python skal oppdatere Path).

For å kjøre scriptet er kommandoen rimelig enkel, det eneste påkrevde argumentet er ID, som finnes ved å trykke Referere for så å kopiere tallrekken etter digibok_ i lenken som dukker opp.
For aviser må både tekst og tall etter digavis_ kopieres med.
```
bruk: nbno.py [-h] [--id <bokID>] [--avis] [--cover] [--pdf] [--f2pdf]
               [--url] [--error] [--start <int>] [--stop <int>]
               [--level <int>] [--maxlevel <int>] [--maxcol <int>]
               [--maxrow <int>]

påkrevd argument:
  --id <bokID>    IDen på boken som skal lastes ned

valgfrie argumenter:
  -h, --help      show this help message and exit
  --avis          Settes om det er en avis som lastes
  --cover         Settes for å laste covers
  --pdf             Settes for å lage pdf av bildene som lastes
  --f2pdf           Settes for å lage pdf av bilder i mappe
  --url           Settes for å printe URL på hver del
  --error         Settes for å printe HTTP feilkoder
  --start <int>   Sidetall å starte på
  --stop <int>    Sidetall å stoppe på
  --level <int>   Sett Level
  --maxlevel <int>  Sett MaxLevel
  --maxcol <int>  Sette max Col
  --maxrow <int>  Sette max Row
```
