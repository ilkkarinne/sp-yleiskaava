---
layout: "default"
description: ""
id: "ymparistoarvojen-vaaliminen"
status: "Ehdotus"
---
# Kaavamääräyslajit - ympäristöarvojen vaaliminen
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/07>

1. 
{:toc}

## Kulttuurihistoriallisesti arvokas alue tai kohde
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0701>

{% include clause_start.html type="req" id="prof-yk/vaat-kulttuurihist-merkittava-alue" %}
Kaikkien yleiskaavojen tietoaineistojen sisältämien [Kaavamaarays](../../looginenmalli/dokumentaatio/#kaavamaarays)-luokan instanssien, joiden ```laji```-attribuutin arvo on jokin [Kultturihistoriallisesti arvokas alue tai kohde](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0701)-koodin alakoodi, osalta tulee noudattaa seuraavia rajoituksia:
* ```arvo```-attribuutin arvona saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
* ```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi [Lisatieto](../../looginenmalli/dokumentaatio/#lisatieto), joka ```laji``` on yksi seuraavista:   
   * [Kulttuurihistoriallinen merkittävyys](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/05), jonka arvoina on yksi tai useampi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), jotka viittaavat johonkin [Kulttuurihistoriallinen merkittävyys](http://uri.suomi.fi/codelist/rakrek/kulthistmer) koodiston koodeista,
   * [Kulttuurihistoriallinen arvotyyppi](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/06), jonka arvoina on yksi tai useampi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), jotka viittaavat johonkin [Kulttuurihistoriallinen arvotyyppi](http://uri.suomi.fi/codelist/rakrek/Kulthistatyyp) koodiston koodeista,
   * [Kulttuurihistoriallinen tyyppi](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/07), jonka arvoina on yksi tai useampi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), jotka viittaavat johonkin [Kulttuurihistoriallinen tyyppi](http://uri.suomi.fi/codelist/rakrek/kulthistyyp) koodiston koodeista, tai
   * [Kulttuurihistoriallisen merkittävyyden kriteerit](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/08), jonka arvoina on yksi tai useampi[KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), joka viittaa johonkin [Kulttuurihistoriallisen merkittävyyden kriteerit](http://uri.suomi.fi/codelist/rakrek/KultKritee) koodiston koodeista.
Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include question.html content="Kulttuurihistoriallisen merkittävyyden kriteerit on monikossa, kun muut koodien otsikot ovat yksikössä, pitäisikö myös se vaihtaa yksikköön? Samat nimet ovat käytössä viitatuissa rakrek-koodistoissa." %}

{% include question.html content="Tämä pääluokka toimii nyt kaatoluokkana, koska sitä ei ole rajattu vain ryhmittelyotsikoksi. Onko tämä tarkoitus?" %}

### Suojeltava alue tai alueen osa
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/070101>

{% include clause_start.html type="req" id="prof-yk/vaat-suojeltava-alue" %}
Ilmaisee, että kaavakohde kuvaa suojeltavan alueen tai alueen osan.
{% include clause_end.html %}

### Suojeltava rakennus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/070102>

{% include clause_start.html type="req" id="prof-yk/vaat-suojeltava-rakennus-maar" %}
Ilmaisee, että kaavakohde kuvaa suojeltavan [rakennuksen](http://uri.suomi.fi/terminology/rakymp/c6).
{% include clause_end.html %}

### Suojeltava rakennelma
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/070103>

{% include clause_start.html type="req" id="prof-yk/vaat-suojeltava-rakennelma-maar" %}
Ilmaisee, että kaavakohde kuvaa suojeltavan [rakennelman](http://uri.suomi.fi/terminology/mrl/concept-125).
{% include clause_end.html %}

### Kiinteä suojeltava kohde
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/070104>

{% include clause_start.html type="req" id="prof-yk/vaat-kiintea-suojeltava-kohde-maar" %}
Ilmaisee, että kaavakohde kuvaa kiinteän suojeltavan kohteen.
{% include clause_end.html %}

### Kiinteä muinaisjäännös
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/070105>

{% include clause_start.html type="req" id="prof-yk/vaat-kiintea-muinaisjaannos-maar" %}
Ilmaisee, että kaavakohde kuvaa kiinteän muinaisjäännöksen.
{% include clause_end.html %}

## Luontoarvoiltaan arvokas alue tai kohde
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0702>

{% include clause_start.html type="req" id="prof-yk/vaat-kulttuurihist-merkittava-alue" %}
Kaikkien yleiskaavojen tietoaineistojen sisältämien [Kaavamaarays](../../looginenmalli/dokumentaatio/#kaavamaarays)-luokan instanssien, joiden ```laji```-attribuutin arvo on jokin [Luontoarvoiltaan arvokas alue tai kohde](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0702)-koodin alakoodi, osalta tulee noudattaa seuraavia rajoituksia:
* ```arvo```-attribuutin arvona saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
* ```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi [Lisatieto](../../looginenmalli/dokumentaatio/#lisatieto), joka ```laji``` on yksi seuraavista:   
   * [Ympäristöarvon peruste](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/09), jolla on yksi arvona yksi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo), joka kuvaa ympäristöarvon perusteen sanallisesti, tai
   * [Ympäristö- tai luontoarvon merkittävyys](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/10), on yksi arvona yksi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo), joka kuvaa ympäristö- tai luontoarvon merkittävyyden sanallisesti.

Muun tyyppiset lisätietojen arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include note.html content="Mikäli ympäristöarvojen perusteet ja merkittävyydet kuvataan tulevaisuudessa omina koodistoinaan, tulee lisätietojen sallittuja arvoja muuttaa viittaamaan niihin" %}

{% include question.html content="Tämä pääluokka toimii nyt kaatoluokkana, koska sitä ei ole rajattu vain ryhmittelyotsikoksi. Onko tämä tarkoitus?" %}

### Suojeltu puu
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/070201>

{% include clause_start.html type="req" id="prof-yk/vaat-suojeltu-puu-maar" %}
Ilmaisee, että kaavakohde kuvaa suojellun puun.
{% include clause_end.html %}

{% include question.html content="Onko koodi tarkoituksella nimenomaan suojeltu, eikä suojeltava?" %}

### Säilytettävä puu
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_yK/code/070202>

{% include clause_start.html type="req" id="prof-yk/vaat-sailytettava-puu-maar" %}
Ilmaisee, että kaavakohde kuvaa säilytettävän puun.
{% include clause_end.html %}

### Suojeltava vesistö tai vesialue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/070203>

{% include clause_start.html type="req" id="prof-yk/vaat-suojeltava-vesisto-maar" %}
Ilmaisee, että kaavakohde kuvaa suojeltavan vesistön tai vesialueen.
{% include clause_end.html %}

### Luonnon monimuotoisuuden kannalta tärkeä alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/070204>

{% include clause_start.html type="req" id="prof-yk/vaat-luonnon-monimuotoisuus-maar" %}
Ilmaisee, että kaavakohde kuvaa luonnon monimuotoisuuden kannalta tärkeän alueen.
{% include clause_end.html %}

### Ekologinen yhteys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/070205>

{% include clause_start.html type="req" id="prof-yk/vaat-ekologinen-yhteys-maar" %}
Ilmaisee, että kaavakohde kuvaa ekologisen yhteyden.
{% include clause_end.html %}

## Alue, jolla ympäristö säilytetään
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0703>

{% include clause_start.html type="req" id="prof-yk/vaat-sailytettava-ymparisto-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolla ympäristö säilytetään.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-sailytettava-ymparisto-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-sailytettava-ymparisto-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Alue, jolla on erityistä ulkoilun ohjaamistarvetta
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0704>

{% include clause_start.html type="req" id="prof-yk/vaat-ulkoilun-ohjaamistarve-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolla on sen luontoarvojen vuoksi erityistä ulkoilun ohjaamistarvetta.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-ulkoilun-ohjaamistarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-ulkoilun-ohjaamistarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}
