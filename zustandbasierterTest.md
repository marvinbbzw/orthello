# Zustandsbasierter Testfall 1 – NEGATIVTEST (unerlaubter Spielzug)
## Vorbedingung:
Das Board ist im Standard-Startzustand. Das Feld [0,0] ist leer, aber kein gültiger Zug, da es keine gegnerischen Steine einkesselt.
## Ereignis:
Spieler macht Zug auf Feld [0,0]
## Sollreaktion:
Es soll eine Fehlermeldung ausgegeben werden.
## Nachbedingung:
Das Brett bleibt unverändert.
 
 
# Zustandsbasierter Testfall 2 – POSITIVTEST (erlaubter Spielzug)
## Vorbedingung:
Das Spiel befindet sich im Anfangszustand. Gemäss Valid-Moves ist Zug auf [2,3] ein gülltiger Zug.
## Ereignis:
Spieler macht Zug auf Feld [2,3]
## Sollreaktion:
Die Methode akzeptiert den Zug und wirft keine Fehler.Alle weissen Steine sollten nun korrekt auf schwarz umgedreht woren sein.
## Nachbedingung:
Das Brett wurde neu angeordnet, gespeichert mit korrekten "Kehrungen".