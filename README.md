# TPS_Irrigazione
Sistema Irrigazione con 5 aree programmabili e gestione attivazione tramite sensori di umidità industriali e sistema RTC DS1307 (Timer I2C).
Il progetto si basa su un arduino Uno R3 montato su un PCB custom (dimensioni nel file .brd).

Controllo del sistema tramite 4 tasti: SET, SW, SU e GIU'.
visualizzazione dati usando i display 7 segmenti in connessione I2C (Adafruit 4 digit LED backpack).
I sensori di umidità industriali sono usati quando è presente una programmazione, per permettere un risparmio d'acqua all'utente.
