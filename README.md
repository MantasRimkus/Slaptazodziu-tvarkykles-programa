Slaptažodžių tvarkyklė

Aprašymas
Ši programa yra žiniatinklio slaptažodžių tvarkyklė, leidžianti saugiai saugoti, ieškoti, atnaujinti ir ištrinti slaptažodžių įrašus. Programa naudoja AES šifravimą jautriems duomenims apsaugoti ir leidžia eksportuoti bei importuoti užšifruotus duomenis tekstinio failo formatu.

Funkcionalumas
Programa leidžia vartotojui prisijungti naudojant pagrindinį slaptažodį, kuris naudojamas AES rakto generavimui. Vartotojas gali pridėti naujus slaptažodžių įrašus, įvesdamas pavadinimą, slaptažodį, URL arba programos pavadinimą bei papildomas pastabas. Taip pat galima ieškoti įrašų pagal pavadinimą, atnaujinti esamus įrašus, ištrinti juos, rodyti slaptažodį tik pareikalavus, kopijuoti slaptažodį į iškarpinę ir generuoti atsitiktinius slaptažodžius.

Naudotos technologijos
HTML
CSS
JavaScript
Web Crypto API
AES-GCM
PBKDF2
LocalStorage

Veikimo principas
Vartotojas įveda pagrindinį slaptažodį. Iš šio slaptažodžio naudojant PBKDF2 ir SHA-256 sugeneruojamas AES šifravimo raktas. Slaptažodžių įrašai yra šifruojami naudojant AES-GCM algoritmą ir saugomi naršyklės LocalStorage. Duomenys gali būti eksportuojami į .txt failą ir vėliau importuojami atgal į programą.

Slaptažodžiai nėra rodomi iš karto. Jie parodomi tik vartotojui paspaudus mygtuką „Rodyti slaptažodį“. Tai apsaugo jautrius duomenis nuo nereikalingo atskleidimo.

Kaip paleisti
Atsisiųskite projektą arba atidarykite GitHub repozitoriją. Atidarykite index.html failą naršyklėje. Įveskite pagrindinį slaptažodį ir pradėkite naudotis programa.

Jeigu projektas paleistas per GitHub Pages, atidarykite sugeneruotą svetainės nuorodą.

Papildomos funkcijos
Programa turi atsitiktinio slaptažodžio generatorių, saugų slaptažodžio peržiūrėjimą ir slaptažodžio kopijavimą į iškarpinę.

Pastaba
Kadangi programa veikia naršyklėje, ji neturi tiesioginės prieigos prie kompiuterio failų sistemos kaip darbalaukio programa. Todėl duomenų failų valdymas realizuotas per užšifruotų duomenų eksportavimą į .txt failą ir importavimą iš .txt failo.

Autorius
Mantas Rimkus
