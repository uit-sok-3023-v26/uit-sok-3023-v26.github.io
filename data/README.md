# Data
Her legger jeg ut flere datasett vi kommer til å bruke i forelesning, seminar og til oppgaveregning.

Vi vil også legge ut noen datasett dere kan bruke i oppgaven deres.

**Her følger noen eksempler på datasett dere kan bruke:**
* *Fraud.csv* - som er et datasett om svindel og bank-data brukt i forelesning. Her har vi gjort mye i forelesningene, men ingen nevrale nettverk ting på det.
* *California Housing Prices Data (5 new features!)*, som kan brukes til å predikere priser i California området - lenke til datasettet finnes [her](https://www.kaggle.com/datasets/fedesoriano/california-housing-prices-data-extra-features).
* *User behavior datasett*, et datasett som ser på mobilbruken til folk. Lenke til datasettet finnes [her](https://www.kaggle.com/datasets/valakhorasani/mobile-device-usage-and-user-behavior-dataset).
* *Loan Approval Classification Dataset*, datasett som kan brukes til binær klassifikasjon for å se om et lån blir akseptert eller ikke. Lenke til datasettet finnes [her](https://www.kaggle.com/datasets/taweilo/loan-approval-classification-data).
* *Student performance*, et datasett om studenters prestasjoner. Lenke til datasettet finnes [her](https://www.kaggle.com/datasets/muhammadroshaanriaz/students-performance-dataset-cleaned).
* *Bildeklassifisering*, et datasett om hunder og katter. Ikke særlig økonomisk data, men krevende kode-vinkling. Lenke til datasettet finnes [her](https://www.kaggle.com/datasets/samuelcortinhas/cats-and-dogs-image-classification).
* *Bildeklassifisering*, et datasett om grønnsaker. Klassifiseringsoppgave med flere klasser. Lenke til datasettet finnes [her](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset).
* *Bildeklassifisering*, et datasett som inneholder eksempler på **ekte** bilder av ansikt, og **falsk** genererte bilder. Lenke til datasettet finnes [her](https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces).
* *Helsedata*, et datasett som handler om helseforsikring, og personlige attributter og pris av forsikring. Lenke til datasettet [her](https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance).
  
## Kaggle
Mange av datasettene over bruker *Kaggle.com* - alt dere trenger å gjøre er å lage en bruker der (f.eks. med Gmail) for å laste ned datasett.

## Andre steder dere kan finne data til semesteroppgaven
Det viktigste med dataene dere velger å bruke til semesteroppgaven er at det er *nok* data, og at det har en viss tilknytning til samfunnsøkonomien. Det trenger med andre ikke **bare** være finansielle data, men kan handle om bærekraftighet, forurensning, befolkning og så videre. Andre temaer kan også være aktuelle, men i så fall interessant fra et maskinlæringsperspektiv.

| Kilde                                      | Hva                                         | Link |
|--------------------------------------------|---------------------------------------------|------|
|Kaggle                                      |Nesten hva som helst:-)                         |[kaggle.com](https://www.kaggle.com/)|
| SSB                                        | Statistisk sentralbyrå – Norsk statistikk  | [ssb.no](https://www.ssb.no) |
| Yahoo Finance                              | Finansielle data, aksjekurser, råvarer etc. | [finance.yahoo.com](https://finance.yahoo.com) |
| Titlon (UiT)                               | Data fra Oslo Børs                         | [Titlon UiT](https://titlon.uit.no/) |
| World Bank – World Development Indicators | Globale økonomiske indikatorer (GDP, inflasjon etc.)| [World Bank](https://databank.worldbank.org/source/world-development-indicators) |
|World Bank - Andre type data|Statistikk innen utdannelse, kjønn, helse, populasjon|[World Bank](https://databank.worldbank.org/)|
|ML Repo|Massevis av ulike ML datasett|[UC Irvine Machine Learning Repository](https://archive.ics.uci.edu)|

## Boka *Introduction to Statistical Learning* har en rekke datasett dere kan bruke
| Datasett | Beskrivelse |
| :--- | :--- |
| `Auto` | Drivstofforbruk, hestekrefter og annen informasjon om biler. |
| `Bikeshare` | Timebasert bruk av et sykkeldelingsprogram i Washington, DC. |
| `Boston` | Boligverdier og annen informasjon om bydeler (census tracts) i Boston. |
| `BrainCancer` | Overlevelsestid for pasienter diagnostisert med hjernekreft. |
| `Caravan` | Informasjon om individer som er tilbudt forsikring for campingvogn. |
| `Carseats` | Informasjon om salg av barneseter i 400 butikker. |
| `College` | Demografiske data, skolepenger og mer for amerikanske høyskoler (Colleges). |
| `Credit` | Informasjon om kredittkortgjeld for 400 kunder. |
| `Default` | Data om kunder som misligholder kredittkortgjeld (Default). |
| `Fund` | Avkastning for 2 000 hedgefond-forvaltere over 50 måneder. |
| `Hitters` | Statistikk og lønningsdata for baseballspillere. |
| `Khan` | Målinger av genuttrykk for fire krefttyper. |
| `NCI60` | Målinger av genuttrykk for 64 kreftcelle-linjer. |
| `NYSE` | Avkastning, volatilitet og volum for New York Stock Exchange. |
| `OJ` | Salgsinformasjon for appelsinjuicene Citrus Hill og Minute Maid. |
| `Portfolio` | Historiske verdier av finansielle eiendeler (brukes til porteføljeallokering). |
| `Publication` | Tid til publisering for 244 kliniske studier. |
| `Smarket` | Daglige prosentvise avkastninger for S&P 500 over en 5-års periode. |
| `USArrests` | Kriminalitetsstatistikk per 100 000 innbyggere i 50 amerikanske stater. |
| `Wage` | Inntektsdata for menn i den sentral-atlantiske regionen i USA. |
| `Weekly` | 1 089 ukentlige aksjemarkedsavkastninger over en periode på 21 år. |

Dere henter dataen på følgende vis:
```python
!pip install ISLP

from ISLP import load_data
# Eksempel
wage = load_data('Wage')
wage
```

