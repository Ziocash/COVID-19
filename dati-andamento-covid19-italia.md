<img src="http://opendatadpc.maps.arcgis.com/sharing/rest/content/items/5c8ef7516b5b4bb19f61037b4cd69015/data" alt="COVID-19" data-canonical-src="http://opendatadpc.maps.arcgis.com/sharing/rest/content/items/5c8ef7516b5b4bb19f61037b4cd69015/data" width="400" />

# Dati andamento COVID-19 Italia

## Aggiornamento dei dati

- Dati andamento COVID-19 Italia: ogni giorno alle 18:00

## Formato dei dati

### Dati per Regione

**Directory:**  dati-regioni<br>
**Struttura file giornaliero:** dpc-covid19-ita-regioni-yyyymmdd.csv (dpc-covid19-ita-regioni-20200224.csv)<br>
**File complessivo:** dpc-covid19-ita-regioni.csv<br>
**File ultimi dati (latest):** dpc-covid19-ita-regioni-latest.csv

| Nome campo                  | Descrizione                       | Description                            | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|----------------------------------------|-------------------------------|---------------------|
| **data**                        | Data dell'informazione            | Date of notification                   | YYYY-MM-DDTHH:MM:SS (ISO 8601) Ora italiana | 2020-03-05T12:15:45 |
| **stato**                       | Stato di riferimento              | Country of reference                   | XYZ (ISO 3166-1 alpha-3)      | ITA                 |
| **codice_regione**              | Codice della Regione (ISTAT 2019) | Code of the Region (ISTAT 2019)        | Numero                        | 13                  |
| **denominazione_regione**       | Denominazione della Regione       | Name of the Region                     | Testo                         | Abruzzo             |
| **lat**                         | Latitudine                        | Latitude                               | WGS84                         | 42.6589177          |
| **long**                        | Longitudine                       | Longitude                              | WGS84                         | 13.70439971         |
| **ricoverati_con_sintomi**      | Ricoverati con sintomi            | Hospitalised patients with symptoms    | Numero                        | 3                   |
| **terapia_intensiva**           | Ricoverati in terapia intensiva   | Intensive Care                         | Numero                        | 3                   |
| **totale_ospedalizzati**        | Totale ospedalizzati              | Total hospitalised patients            | Numero                        | 3                   |
| **isolamento_domiciliare**      | Persone in isolamento domiciliare | Home confinement                       | Numero                        | 3                   |
| **totale_positivi** | Totale attualmente positivi (ospedalizzati + isolamento domiciliare)      | Total amount of current positive cases (Hospitalised patients + Home confinement)  | Numero                        | 3                   |
| **variazione_totale_positivi**  | Variazione del totale positivi (totale_positivi giorno corrente - totale_positivi giorno precedente)       | News amount of current positive cases (totale_positivi current day - totale_positivi previous day)  | Numero                        | 3                   |
| **nuovi_positivi**  | Nuovi attualmente positivi (totale_casi giorno corrente - totale_casi giorno precedente)       | News amount of current positive cases (totale_casi current day - totale_casi previous day)  | Numero                        | 3                   |
| **dimessi_guariti**             | Persone dimesse guarite           | Recovered                              | Numero                        | 3                   |
| **deceduti**                    | Persone decedute                  | Death                                  | Numero                        | 3                   |
| **casi_da_sospetto_diagnostico**                    | Casi positivi al tampone emersi da attività clinica **Non più popolato**                  | Positive cases emerged from clinical activity **No longer populated**                                 | Numero                        | 3                   |
| **casi_da_screening**                    | Casi positivi emersi da indagini e test, pianificati a livello nazionale o regionale **Non più popolato**                  | Positive cases emerging from surveys and tests, planned at national or regional level  **No longer populated**                                | Numero                        | 3                   |
| **totale_casi**                 | Totale casi positivi              | Total amount of positive cases         | Numero                        | 3                   |
| **tamponi**                     | Totale tamponi (processati con test molecolari)                   | Tests performed   (processed with molecular tests)                     | Numero                        | 3                   |
| **casi_testati**                     | Totale dei soggetti sottoposti al test                    | Total number of people tested                        | Numero                        | 3                   |
| **note**                     | Note                   | Notes                       | Testo                        | Lorem ipsum...                   |
| **ingressi_terapia_intensiva**                     | Ingressi giornalieri in terapia intensiva | Daily admissions to intensive care                        | Numero                        | 3                  |
| **note_test**                     | Note sui test effettuati                  | Notes on the tests carried out                       | Testo                        | Lorem ipsum...                   |
| **note_casi**                     | Note sui casi testati                  | Notes on the cases tested                       | Testo                        | Lorem ipsum...                   |


*Le Province autonome di Trento e Bolzano sono indicate in "denominazione regione" e con il codice 04 del Trentino Alto Adige.*<br>
*Viene messo a disposizione un file JSON complessivo di tutte le date nella cartella "dati-json": dpc-covid19-ita-regioni.json* e rispettivo file ultimi dati (latest) dpc-covid19-ita-regioni-latest.json

### Dati per Provincia

**Directory:**  dati-province<br>
**Struttura file giornaliero:** dpc-covid19-ita-province-yyyymmdd.csv (dpc-covid19-ita-province-20200224.csv)<br>
**File complessivo:** dpc-covid19-ita-province.csv<br>
**File ultimi dati (latest):** dpc-covid19-ita-province-latest.csv

| Nome campo              | Descrizione                         | Description                     | Formato            | Esempio              |
|-------------------------|-------------------------------------|---------------------------------|--------------------|----------------------|
| **data**                    | Data dell'informazione              | Date of notification            | YYYY-MM-DD HH:MM:SS (ISO 8601) Ora italiana           | 2020-03-05 12:15:45 |                   |
| **stato**                   | Stato di riferimento                | Country of reference            | ISO 3166-1 alpha-3 | ITA                  |
| **codice_regione**          | Codice della Regione (ISTAT 2019)   | Code of the Region (ISTAT 2019) | Numero             | 13                   |
| **denominazione_regione**   | Denominazione della Regione         | Name of the Region              | Testo              | Abruzzo              |
| **codice_provincia**        | Codice della Provincia (ISTAT 2019) | Code of the Province            | Numero             | 067                  |
| **denominazione_provincia** | Denominazione della provincia       | Name of the Province            | Testo              | Teramo               |
| **sigla_provincia**         | Sigla della Provincia               | Province abbreviation           | Testo              | TE                   |
| **lat**                     | Latitudine                          | Latitude                        | WGS84              | 42.6589177           |
| **long**                    | Longitudine                         | Longitude                       | WGS84              | 13.70439971          |
| **totale_casi**             | Totale casi positivi                | Total amount of positive cases  | Numero             | 3                    |
| **note**                     | Note in lingua italiana                   | Notes in italian language                       | Testo                        | Lorem ipsum...                   |

*Le Province autonome di Trento e Bolzano sono indicate in "denominazione regione" e con il codice 04 del Trentino Alto Adige.*<br>
*Ogni Regione ha due "Province" denominate "Fuori Regione / Provincia Autonoma", con il codice provincia da 879 a 899, utile ad indicare dati relativi a soggetti fuori Regione o Provincia Autonoma e "In fase di definizione/aggiornamento", con il codice provincia da 979 a 999, utile ad indicare i dati ancora non assegnati alle Province.*<br>
*Viene messo a disposizione un file JSON complessivo di tutte le date nella cartella "dati-json": dpc-covid19-ita-province.json* e rispettivo file ultimi dati (latest) dpc-covid19-ita-province-latest.json

### Andamento nazionale

**Directory:**  dati-andamento-nazionale<br>
**Struttura file giornaliero:** dpc-covid19-ita-andamento-nazionale-yyyymmdd.csv (dpc-covid19-ita-andamento-nazionale-20200224.csv)<br>
**File complessivo:** dpc-covid19-ita-andamento-nazionale.csv<br>
**File ultimi dati (latest):** dpc-covid19-ita-regioni-latest.csv


| Nome campo                  | Descrizione                       | Description                            | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|----------------------------------------|-------------------------------|---------------------|
| **data**                        | Data dell'informazione            | Date of notification                   | YYYY-MM-DD HH:MM:SS (ISO 8601) Ora italiana | 2020-03-05 12:15:45 |
| **stato**                       | Stato di riferimento              | Country of reference                   | XYZ (ISO 3166-1 alpha-3)      | ITA                 |
| **ricoverati_con_sintomi**      | Ricoverati con sintomi            | Hospitalised patients with symptoms    | Numero                        | 3                   |
| **terapia_intensiva**           | Ricoverati in terapia intensiva   | Intensive Care                         | Numero                        | 3                   |
| **totale_ospedalizzati**        | Totale ospedalizzati              | Total hospitalised patients            | Numero                        | 3                   |
| **isolamento_domiciliare**      | Persone in isolamento domiciliare | Home confinement                       | Numero                        | 3                   |
| **totale_positivi** | Totale attualmente positivi (ospedalizzati + isolamento domiciliare)      | Total amount of current positive cases (Hospitalised patients + Home confinement)  | Numero                        | 3                   |
| **variazione_totale_positivi**  | Variazione del totale positivi (totale_positivi giorno corrente - totale_positivi giorno precedente)       | News amount of current positive cases (totale_positivi current day - totale_positivi previous day)  | Numero                        | 3                   |
| **nuovi_positivi**  | Nuovi attualmente positivi (totale_casi giorno corrente - totale_casi giorno precedente)       | News amount of current positive cases (totale_casi current day - totale_casi previous day)  | Numero                        | 3                   |
| **dimessi_guariti**             | Persone dimesse guarite           | Recovered                              | Numero                        | 3                   |
| **deceduti**                    | Persone decedute                  | Death                                  | Numero                        | 3                   |
| **casi_da_sospetto_diagnostico**                    | Casi positivi al tampone emersi da attività **Non più popolato** clinica                  | Positive cases emerged from clinical activity **No longer populated**                                 | Numero                        | 3                   |
| **casi_da_screening**                    | Casi positivi emersi da indagini e test, pianificati a livello nazionale o regionale **Non più popolato**                  | Positive cases emerging from surveys and tests, planned at national or regional level  **No longer populated**                                | Numero                        | 3                   |
| **totale_casi**                 | Totale casi positivi              | Total amount of positive cases         | Numero                        | 3                   |
| **tamponi**                     | Totale tamponi (processati con test molecolari)                    | Tests performed                        | Numero                        | 3                   |
| **casi_testati**                     | Totale dei soggetti sottoposti al test                    | Total number of people tested (processed with molecular tests)                      | Numero                        | 3                   |
| **note**                     | Note                   | Notes                       | Testo                        | Lorem ipsum...                   |
| **ingressi_terapia_intensiva**                     | Ingressi giornalieri in terapia intensiva | Daily admissions to intensive care                        | Numero                        | 3                  |
| **note_test**                     | Note sui test effettuati                  | Notes on the tests carried out                       | Testo                        | Lorem ipsum...                   |
| **note_casi**                     | Note sui casi testati                  | Notes on the cases tested                       | Testo                        | Lorem ipsum...                   |


*Viene messo a disposizione un file JSON complessivo di tutte le date nella cartella "dati-json": dpc-covid19-ita-andamento-nazionale.json* e rispettivo file ultimi dati (latest) dpc-covid19-ita-andamento-nazionale-latest.json

### Note

**Directory:**  note<br>
**Struttura file:** dpc-covid19-ita-note<br>

| Nome campo                  | Descrizione                       | Description                            | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|----------------------------------------|-------------------------------|---------------------|
| **data**                        | Data dell'informazione            | Date of notification                   | YYYY-MM-DD HH:MM:SS (ISO 8601) Ora italiana | 2020-03-05 12:15:45 |
| **note** | Note       | Notes            | Testo              | Lorem ipsum               |
<br><br><br>


### Licenza
**Licenza:** [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.it) - [Visualizza licenza](https://github.com/pcm-dpc/COVID-19/blob/master/LICENSE)<br>
Scheda metadati RNDT: [dati](https://geodati.gov.it/geoportale/visualizzazione-metadati/scheda-metadati/?uuid=PCM%3ACOVID-19%3A05032020%3A093000) - [aree](https://geodati.gov.it/geoportale/visualizzazione-metadati/scheda-metadati/?uuid=PCM%3A000086%3A20200306%3A110700)<br>
Temi del dataset: [Salute umana e sicurezza](http://inspire.ec.europa.eu/theme/hh) - [Human health and safety (Inspire)](http://inspire.ec.europa.eu/theme/hh)<br>
Categoria ISO 19115: Salute<br>
Dati forniti dal Ministero della Salute<br>
Elaborazione e gestione dati a cura del Dipartimento della Protezione Civile
