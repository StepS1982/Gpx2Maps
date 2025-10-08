# GPX2MAPS – Web-APP
**👉 Prova subito:** https://gpx2maps.pages.dev/

Web app gratuita per:
- **Fondere/ottimizzare** link di Google Maps (fino a 25 punti navigabili)
- **Maps → GPX** (RTE e TRK con WPT) via OSRM
- **GPX → Maps** (genera link /maps/dir da WPT/RTE/TRK)
- **Sanitizzare GPX** (arrotonda, dedupe adiacenti, LF/UTF-8, rimuove i WPT)
- **Meteo + info percorso** (7 giorni × 4 fasce, TXT/CSV)

Niente account, niente database: tutto gira **client-side** nel browser.

![Anteprima](https://gpx2maps.pages.dev/gpx2maps_og.jpg)

## Perché
Google Maps ha limiti stretti sui punti della rotta: GPX2MAPS aiuta a unirli/ottimizzarli e a passare facilmente tra Maps e GPX senza tool pesanti. Inoltre ti permette di estrarre il meteo di tutte le località del percorso e di queste, ricavare i tempi e le distanze per fare una più precisa pianificazione. 

## Funzionalità in dettaglio
- **Fusione link**: dedupe adiacente, ottimizzazione a 25 o split automatico in più link.
- **Maps → GPX**: genera due file (RTE e TRK) + WPT; nomi e encoding puliti.
- **GPX → Maps**: crea uno o più link navigabili dai punti del tuo GPX.
- **Sanitizza**: rounding a 6 decimali, rimozione duplicati adiacenti, output LF/UTF-8.
- **Meteo**: tabella 7×4 con condizioni e min/max per ogni località. File generati: HTML/TXT/CSV. Gli ultimi due formati servono per i tempi e le distanze totali e parziali tra le varie località dell'itinerario. Meteo estraibile sia da link Google Maps che anche da GPX. E' possibile avere il meteo anche solo scrivendo le località una sotto l'altra.

## Come si usa
1. Apri https://gpx2maps.pages.dev/
2. Scegli il tab in base a quello che ti serve (Fusione, Maps→GPX, ecc.)
3. Segui le istruzioni scritte

## Privacy
- Nessun login.
- Nessun database.
- I file vengono elaborati **in locale** nel browser.

## Supporto
Se l’app ti è utile, puoi:
- [Offrirmi un caffè su PayPal](https://www.paypal.com/donate?business=stefano.vitro%40gmail.com&no_recurring=0&item_name=Supporto+sviluppo+GPX2MAPS&currency_code=EUR)
- Dare un’occhiata alle [Offerte/Coupon Amazon](https://amzn.to/41o2XjA)

## Roadmap
- Miglioramenti UI/UX
- Altri profili (es. bike/hike) per il routing
- Suggerisci la tua idea nelle Issues!
