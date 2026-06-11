# Eksamit-Mari-Grosberg

## Eksamitöö – Mari Grosberg
* Kood: EX-2026-4MDQ
* Ettevõte: Valge Laine OÜ
* Tegevusala: spordiklubi

## Ülesanne
Loo ettevõttele Valge Laine OÜ (spordiklubi) veebileht, mis sisaldab:

* esilehte
* uudiste lehte (uudiste loend)
* ühe uudise vaadet
* kontaktilehte
Uudised võiksid kajastada näiteks uusi treeninguid, võistlusi ja liikmete saavutusi.

### Millise CMS-i valisid ja miks (2–3 lauset):
* CMS mille valin on WordPress. Põhjuseks see, et sellega nii palju töötanud ja erinevaid asju testinud, et olen kindalm sellega.

### Kasutatud tööristada ja selgitus:
- DDEV 
- Docker 
- WordPress (CMS)

#### Selgitus: 
* setup on kiire (mõni käsk)
* ei pea midagi lokaalselt installima (PHP/MySQL)
* lihtne teistega jagada
* töötab igal arvutil samamoodi


### Tööplaani: millised sammud kavatsed teha ja mis järjekorras, koos umbkaudse ajahinnanguga:
Algus umbes 10 minutit:
1. Paigaldan ja seadistan DDEV keskkonna.
2. Loon Wp projekti.
3. Kontrollin, et site töötab.
4. Loon Admini.
5. Create block theme plugina.


Kõik töö teen WordPress Adminnis algselt ära, umbes 2-3 tundi:
1. Alustan Index templetist.
2. Siis tegin Headeri ja Footeri korda.
3. Lõin Front-Page templeti. Tegin seal kõik disain ära.
4. Siis Page template, mis oleks tagavara.
5. Home template, uudiste postituste jaoks.
6. Single template, ühe spetsiifilise uudise jaoks.
7. Page content template, mis on contact lehe oma.
8. Kui kõik adminiss valmis siis tuleb VS codes failid iga template jaoks.
9. Siis ´ddev exec wp post list --post_type=wp_template´ abil saan iga template koodi ja copy-ida nad filedesse.
10. theme.json korda teha.
11. Lõpiks commitida.


## Kokkuvõtte:

Iseenesest läks wordpressis töö kõigite tempalte tegemine hästi. Setup on juba nagu käes ja käib kiiresti. 

Raske oli ikkagi see theme.json fail. Kuna ma tegin põhimõtteliselt kõik disain(valisin värvid, tüpograafia ja muud) WP adminnis valmis siis ma väga ei tahnud midagi katki teha theme.jsoniga.

Sujus oli template lisamine my-theme alla. See on nüüd suhteliselt lihtne nüüd.