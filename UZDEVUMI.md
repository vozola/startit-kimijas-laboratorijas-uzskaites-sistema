# Projekta sākums

## 1. Izveidot "fork" no šī GitHub repozitorija

- projekta GitHub lapas labajā augšējā stūrī nospiest pogu "Fork"
- pagaidīt līdz projekts ir nokopēts uz jūsu personīgo kontu
- turpmākā darbā izmantot savu repozitorija *forku*

## 2. Izvēlēties izstrādes un darbināšanas vidi

Nolemt kādā veidā vēlaties veikt izstrādi un projekta darbināšanu:

### 2A. Lokāli

- pārbaudīt vai ir uzinstalēta visa nepieciešamā programmatūra
  - git
  - Visual Studio Code, cits koda redaktors vai IDE
  - Python 3
  - Python bibliotēkas no requirements.txt
- veikt "clone" no **sava** GitHub projekta
- atvērt projekta mapi koda redaktorā/IDE
- strādāt pie projekta, saglabāt datnes
- palaist serveri, izmantojot koda redakrota/IDE "run" funkcionalitāti uz datnes "serveris.py" vai no komandrindas (Git Bash) izpildot `python serveris.py`
- pārbaudīt darbību atverot norādīto adresi pārlūkprogrammā

### 2B. repl.it vidē

- atvērt lapu [repl.it](repl.it)
- nospiest pogu "New Repl"
- izvēlēties iespēju "Import from GitHub"
- ielīmēt **sava** repozitorija URL
- nospiest pogu "Import from GitHub"
- pārbaudīt iespējas:
  - kodu labot pārlūkprogrammā
  - serveri iedarbināt ar zaļo pogu "Run" lapas augšpusē - vidū
  - savu aplikāciju atvērt jaunā pārlūkprogrammas cilnī ar pogu "Open in new tab"

## 3. Pievienot serverim jaunu founcionalitāti

- izveidot route "/sveiki", kas atgriež tekstu "Nav vairs nekāds rīts!"
- izveidot route "/cik/2/2", kas aprēķina un atgriež summu 2+2. Ievērot, ka jāatgriež ir *string* datu tips!
- izveidot route "/sveiki/<vards>", kas izmanto mainīgo `vards`, lai atgrieztu personalizētu sveicienu, piemēram, ja `vards` ir *Māris*, tad atgriež tekstu "Sveiki, Māris!"
- izveidot route "/cik/<sk1>/<sk2>, kas izmanto mainīgos sk1 un sk2, lai aprēķinātu un atgrieztu to summu. Ievērot, ka mainīgais tiek iegūts kā *string* datu tips, bet aprēķiniem nepieciešams *int* vai *float*, savukārt jāatgriež ir *string* datu tips!
