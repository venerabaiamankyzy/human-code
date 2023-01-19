## HUMAN CODE

Scegliere cosa guardare su Netflix
Che barba, che noia, che noia, che barba!
Perché ci si mette sempre un’ora a scegliere cosa guardare la sera? Certo è difficile mettere d’accordo i gusti di tutti, poi dipende anche in base al tempo (o al sonno) che abbiamo. Delle volte si pensa di vedere quel bel film che ci hanno consigliato, mentre altre volte si viene risucchiati da quella serie tv che ci tiene incollati allo schermo. Che senso di vuoto quando poi finisce!

## SCEGLIERE COSA GUARDARE SU NETFLIX

##### FILM PIU' VOTATO TRA 5 PERSONE

- APRI Lista_Film_Consigliati
- SFOGLIA Lista_Film_Consigliati
- RACCOGLI Votazioni(Film)
  **FINCHE'** Film < 3 voti VAI AL PROSSIMO
  DEFINISCI Lista_Film_Consigliati(_Film_Piu_Votato_)

### GUARDA NETFLIX

- Prendere il telecomando
- Accendere la TV
- Visualizzare l'elenco di APP
  - **SE** l'app _Netflix_ non è presente
    SCARICA _Netflix_
- ACCEDI a _Netflix_

- **SE** il _mio_tempo_ > 1.5h **E** _sonno_ non è vero
  APRI _Lista_Film_Consigliati_
  RIPRODUCI _Film_Consigliati(Film_Piu_Votato)_
  **ALTRIMENTI** Apri lista serie TV **O** documentari

  - **SE** è presente un _Documentario_Interessante_
    RIPRODUCI _Documentario_Interessante_
    **ALTRIMENTI**
  - **SE** è presente una _Serie_NonTerminata_
    RIPRODUCI _Serie_NonTerminata_
    **ALTRIMENTI**
    RIPRODUCI _Serie_Nuova_

- **FINCHE'** mio_tempo NON E' = 0 **E** _sonno_ NON è vero
  continua RIPRODUCI
- Prendi il telecomando
- Spegni TV
- Vai a dormire
