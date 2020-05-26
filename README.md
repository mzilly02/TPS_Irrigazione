# TPS_Irrigazione
Sistema Irrigazione con 5 aree programmabili e gestione attivazione tramite sensori di umidità industriali e sistema RTC DS1307 (Timer I2C).

Il progetto si basa su un arduino Uno R3 incluso in un PCB custom (dimensioni nel file .brd), il tutto montato in un case stampato in 3d su una barra DIN (barra 35mm per montaggio PLC).

L’intero sistema è inserito in una scatola di distribuzione impermeabile per permettere all’utente di installare il sistema di controllo all’esterno.

Il sistema è alimentato tramite un alimentatore per PLC a 12V / 2,5A MAX con doppia uscita 12V (Arduino e elettrovalvole).

Controllo del sistema tramite 4 tasti: SET, SW, SU e GIU'.

visualizzazione dati usando i display 7 segmenti in connessione I2C.

I sensori di umidità industriali sono attivati quando è presente una programmazione, per permettere un risparmio d'acqua all'utente.

L'attivazione dell'irrigazione è attuata tramite 5 elettrovalvole a 12v di tipo NC, controllate da 5 rele a stato solido.
