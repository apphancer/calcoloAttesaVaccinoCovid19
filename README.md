# Calcolore Attesa Vaccino Anti COVID-19

Questo calcolatore stima in quale punto ci si trovi nella coda per ricevere un vaccino contro il COVID-19 in Italia. 💉

## Fonte dati
- Fasi e gruppi di priorità https://www.epicentro.iss.it/vaccini/covid-19-piano-vaccinazione e http://www.salute.gov.it/imgs/C_17_pubblicazioni_3014_allegato.pdf
- Percentuale di accettazione del vaccino in Italia del 70.79% https://www.nature.com/articles/s41591-020-1124-9.pdf
- Dati sulla somministrazione delle dosi https://github.com/italia/covid19-opendata-vaccini
- Dati sulla popolazione http://dati.istat.it/
- Il personale RSA si basa su una stima su base regionale usando dati forniti da https://www.epicentro.iss.it/vaccini/covid-19-piano-vaccinazione
- I dati sui servizi essenziali si basano su una stima su base regionale usando dati forniti da https://www.fpcgil.it/2021/02/04/vaccino-ai-lavoratori-dei-servizi-essenziali-nessuno-sia-escluso/


## Issues
- I calcoli non tengono in conto dell'anticipazione delle vaccinazioni con alcuni marchi (es. AstraZeneca)
- I calcoli sono basati su quattro fasi (1 gruppo per fase) sulla base di informazioni iniziali sul piano di vaccinazione
- I dati sugli operatori sanitari con un totale di 755K non corrispondono ai dati del piano https://www.epicentro.iss.it/vaccini/covid-19-piano-vaccinazione


## Miglioramenti
- I calcoli possono essere cambiati calcolando sotto-categorie  (1 gruppo nella fase 1 e 6 gruppi nella fase 2)
- Calculation does not take into consideration non-working days