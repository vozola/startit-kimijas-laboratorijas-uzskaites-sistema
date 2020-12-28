# Ķīmijas laboratorijas uzskaites sistēmas API

## 1. Pievienot serverim jaunu funcionalitāti pēc parauga

No sākuma `serveris.py` datnē pieslēdz papildus funkcionalitāti no bibliotēkam (Flask jsonify) un citām datnēm (dati.py):

- `import data` - lai pieklūtu paraugdatiem
- `from Flask import jsonify` - lai pārvērstu dažādus datu tipus par JSON formātu

Uzdevumi:

- izveidot route `/api/v1/vielas`, kas atgriež visus piemēra datus, kas atrodami datnē `dati.py` mainīgajā `vielas`. Ievērot, ka jāatgriež ir *string* datu tips!
- izveidot route `/api/v1/viela/<vielasID>`, kas atgriež datus par vielu ar ID &lt;vielasID&gt;, kas atrodami datnē `dati.py` mainīgajā `vielas`. Ievērot, ka jāatgriež ir *string* datu tips!

## 2. Patstāvīgs darbs

- izveidot route `/api/v1/inventars`, kas atgriež visus piemēra datus, kas atrodami datnē `dati.py` mainīgajā `inventars`.
- izveidot route `/api/v1/inventars/<inventarssD>`, kas atgriež datus par vielu ar ID &lt;inventarsID&gt;, kas atrodami datnē `dati.py` mainīgajā `inventars`.
