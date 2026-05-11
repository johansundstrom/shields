# Shields
Mina noteringar om användandet av Shields på Github

## Upptäckten av Shields för Github gjorde mig glad. Här för jag vidare mina upptäkter genom mina minneanteckningar.

* Shields ger möjlighet att markera repository med en *badge*
* Shields kan väljas att vara dynamiska, t.ex. visa senaste commit
* Färg och form kan påverkas

## Exempel

### Statisk badge

![Static Badge](https://img.shields.io/badge/Status-Finshed-brightgreen)

```![Static Badge](https://img.shields.io/badge/Status-Finshed-brightgreen)```

### Dynamisk badge

![GitHub commit activity](https://img.shields.io/github/commit-activity/w/Badges/Squint)

```![GitHub commit activity](https://img.shields.io/github/commit-activity/w/Badges/Squint)```

## Detaljer

På ```[shields.io](https://shields.io/badges)``` hittas detaljer om utformning

För att konstruera en statisk *badge* med för- och efternamn är följande REQUIRED:

| Path Parameters | |
|---|---|
| badgeContent string | REQUIRED |
| Label, (optional) message, and color | Separated by dashes |
| Example | Johan-Sundström-FFFF00 |

![Static Badge](https://img.shields.io/badge/Johan-Sundstr%C3%B6m-ffff00)

* Till höger på sidan finns en badge-generator. 
* Välj fliken *Markdown* och välj *Execute*. 
* Kopiera och klistra in i ```README.md```
