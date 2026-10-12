# app.ffhorizon.studio

Pagine delle app di FF Horizon Studio (supporto, privacy, eliminazione dell'account), pubblicate
con GitHub Pages sul sottodominio `app.ffhorizon.studio`. Il dominio principale `ffhorizon.studio`
resta libero per il sito vero dello studio: le pagine delle app non devono mai cambiare indirizzo,
perché sono registrate negli store.

Pagine statiche in HTML e CSS: nessun cookie, nessuna statistica, nessun servizio esterno
(il carattere Atkinson Hyperlegible Next è incluso in `assets/fonts`, licenza SIL OFL).

## Pagine

| Indirizzo | Contenuto |
|---|---|
| `/` | Elenco delle app di FF Horizon Studio |
| `/il-mio-rione/` | Presentazione e supporto di Il Mio Rione (URL di supporto per gli store) |
| `/il-mio-rione/privacy/` | Informativa sulla privacy (URL della privacy policy per gli store) |
| `/il-mio-rione/elimina-account/` | Come chiedere l'eliminazione dell'account (richiesto da Google Play) |

## DNS (Hostinger)

Un solo record: `CNAME` con nome `app` che punta a `fforesta-dev.github.io`.
Gli altri record del dominio (posta compresa) non riguardano questo sito.

## Regole

- Repository **pubblico**: solo il sito. Il codice dell'app sta nel repository privato `il-mio-rione`.
- **Non cambiare gli indirizzi delle pagine**: sono registrati in App Store Connect e Play Console.
- Il nome della Chiesa va sempre scritto per intero: «La Chiesa di Gesù Cristo dei Santi degli
  Ultimi Giorni», con «La» maiuscola anche dopo una preposizione («de La Chiesa…»).
- Quando cambia la privacy policy, aggiornare la data «Ultimo aggiornamento» in cima alla pagina.
