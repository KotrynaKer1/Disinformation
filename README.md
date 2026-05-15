
Kompleksinė teksto analizė dezinformacijai aptikti
Magistro baigiamasis darbas — dezinformacijos aptikimo įrankis lietuvių kalba, integruojantis semantinę, emocinę ir stilistinę teksto analizę.

Apie įrankį
Įrankis klasifikuoja lietuviškus naujienų straipsnius į dvi klases: dezinformacija ir tiesa. Naudojami trys analizės komponentai:

- **Semantinė analizė** — MiniLM daugiakalbiai sakinių įterpiniai (384 dimensijos)
- **Emocinė analizė** — DistilBERT sentimento modelis, išvestiniai rodikliai ir lietuviški emociniai žodynai (23 dimensijos)
- **Stilistinė analizė** — skaitiniai stiliaus teksto požymiai (36 dimensijos)

Klasifikavimui naudojamas XGBoost algoritmas.

## Rezultatai

- Tikslumas testavimo aibėje: **87%**
- Kryžminės patikros tikslumas: **81%**

