# Ķīmijas laboratorijas uzskaites sistēmas API

## 1. Pievienot serverim statiskas datnes pēc parauga

Sagatavošanās soļi:

- izveido mapi `templates` html datnēm (obligāti šādu nosaukumu, ja negrib nodarboties ar Flask pārkonfigurēšanu!)
- mapē `static` izveido mapes `static/css` un `static/js` css un js datnēm
- pievieno jaunu Flask funkcionalitāti: `from Flask import render_template`
- no sava projekta vai repozitorija *<https://github.com/armandspucs/klus2>* nokopē `index.html` un citas html datnes, un ievieto tās jaunajā mapē `templates`
- no sava projekta vai repozitorija nokopē css un js datnes un ievieto attiecīgajās `static` mapēs.

Servera programmēšana:

- nomaina route `/` funkciju, lai tā atgrieztu `index.html` template.
- izveido route `/publiski`, kas atgriež `pub_data.html` template.
- novēro, ka nestrādā css. html datnēs `index.html` un `pub_data.html` salabo linkus uz statiskajām datnēm (css, js, images), priekšā pieliekot `/static/`.
- salabo linkus starp index un publiski lapām

## 2. Patstāvīgs darbs

- izveido route `/pieslegties`, kas atgriež `login.html` template, salabo linkus uz css un js un linkus no citiem template.
