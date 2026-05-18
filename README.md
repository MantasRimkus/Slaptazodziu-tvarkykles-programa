# Slaptažodžių tvarkyklė

## Aprašymas
Ši programa yra žiniatinklio slaptažodžių tvarkyklė, leidžianti saugiai saugoti, ieškoti, atnaujinti ir ištrinti slaptažodžių įrašus. Programa naudoja AES šifravimą jautriems duomenims apsaugoti ir leidžia eksportuoti bei importuoti užšifruotus duomenis tekstinio failo formatu.

## Funkcionalumas
- Prisijungimas naudojant pagrindinį slaptažodį
- AES šifravimas slaptažodžių apsaugai
- Naujo slaptažodžio įrašo pridėjimas
- Slaptažodžio paieška pagal pavadinimą
- Slaptažodžio atnaujinimas
- Slaptažodžio ištrynimas
- Saugus slaptažodžio peržiūrėjimas
- Slaptažodžio kopijavimas į iškarpinę
- Atsitiktinio slaptažodžio generatorius
- Užšifruotų duomenų eksportavimas į `.txt`
- Užšifruotų duomenų importavimas iš `.txt`

## Naudotos technologijos
- HTML
- CSS
- JavaScript
- Web Crypto API
- AES-GCM
- PBKDF2
- LocalStorage

## Veikimo principas
Vartotojas įveda pagrindinį slaptažodį. Iš šio slaptažodžio naudojant PBKDF2 ir SHA-256 sugeneruojamas AES šifravimo raktas.

Visi slaptažodžių įrašai yra šifruojami naudojant AES-GCM algoritmą prieš išsaugojimą. Duomenys saugomi naršyklės LocalStorage užšifruotu formatu.

Vartotojas gali:
- pridėti naujus įrašus
- ieškoti pagal pavadinimą
- atnaujinti įrašus
- ištrinti įrašus
- parodyti slaptažodį tik pareikalavus
- kopijuoti slaptažodį
- generuoti stiprų slaptažodį

Duomenys gali būti eksportuojami į `.txt` failą ir vėliau importuojami atgal į sistemą.

## Kaip paleisti
### Lokaliai
1. Atsisiųskite projektą
2. Atidarykite `index.html` failą naršyklėje

### Per GitHub Pages
1. Atidarykite GitHub Pages sugeneruotą nuorodą
2. Įveskite pagrindinį slaptažodį
3. Naudokitės sistema

## Pastaba
Kadangi programa veikia naršyklėje, failų sistemos valdymas realizuojamas per eksportavimo ir importavimo funkcionalumą.

## Autorius
Mantas Rimkus
