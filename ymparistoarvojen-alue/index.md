---
layout: "default"
description: ""
id: "ymparistoarvojen-alue"
status: "Ehdotus"
---
# Kaavamääräyslajit - ympäristöarvojen alue
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/ymparistoarvojenAlue>

1. 
{:toc}

## Kulttuurihistoriallisesti arvokas alue tai kohde
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0701>

{% include common/clause_start.html type="req" id="prof-yk/vaat-kulttuurihist-merkittava-alue" %}
Kaikkien yleiskaavojen tietoaineistojen sisältämien {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavamaarays" title="Kaavamaarays" %}-luokan instanssien, joiden ```laji```-attribuutin arvo on jokin [Kultturihistoriallisesti arvokas alue tai kohde](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0701)-koodin alakoodi, osalta tulee noudattaa seuraavia rajoituksia:
* ```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
* ```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatieto" title="Lisatieto" %} joka ```laji``` on yksi seuraavista:   
   * [Kulttuurihistoriallinen merkittävyys](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/05), jonka arvoina on yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} jotka viittaavat johonkin [Kulttuurihistoriallinen merkittävyys](http://uri.suomi.fi/codelist/rakrek/kulthistmer) koodiston koodeista,
   * [Kulttuurihistoriallinen arvotyyppi](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/06), jonka arvoina on yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} jotka viittaavat johonkin [Kulttuurihistoriallinen arvotyyppi](http://uri.suomi.fi/codelist/rakrek/Kulthistatyyp) koodiston koodeista,
   * [Kulttuurihistoriallinen tyyppi](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/07), jonka arvoina on yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} jotka viittaavat johonkin [Kulttuurihistoriallinen tyyppi](http://uri.suomi.fi/codelist/rakrek/kulthistyyp) koodiston koodeista, tai
   * [Kulttuurihistoriallisen merkittävyyden kriteerit](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/08), jonka arvoina on yksi tai useampi{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} joka viittaa johonkin [Kulttuurihistoriallisen merkittävyyden kriteerit](http://uri.suomi.fi/codelist/rakrek/KultKritee) koodiston koodeista.
Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/question.html content="Kulttuurihistoriallisen merkittävyyden kriteerit on monikossa, kun muut koodien otsikot ovat yksikössä, pitäisikö myös se vaihtaa yksikköön? Samat nimet ovat käytössä viitatuissa rakrek-koodistoissa." %}

{% include common/question.html content="Tämä pääluokka toimii nyt kaatoluokkana, koska sitä ei ole rajattu vain ryhmittelyotsikoksi. Onko tämä tarkoitus?" %}

## Luontoarvoiltaan arvokas alue tai kohde
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0702>

{% include common/clause_start.html type="req" id="prof-yk/vaat-kulttuurihist-merkittava-alue" %}
Kaikkien yleiskaavojen tietoaineistojen sisältämien {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavamaarays" title="Kaavamaarays" %}-luokan instanssien, joiden ```laji```-attribuutin arvo on jokin [Luontoarvoiltaan arvokas alue tai kohde](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0702)-koodin alakoodi, osalta tulee noudattaa seuraavia rajoituksia:
* ```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
* ```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatieto" title="Lisatieto" %} joka ```laji``` on yksi seuraavista:   
   * [Ympäristöarvon peruste](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/09), jolla on yksi arvona yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} joka kuvaa ympäristöarvon perusteen sanallisesti, tai
   * [Ympäristö- tai luontoarvon merkittävyys](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/10), on yksi arvona yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} joka kuvaa ympäristö- tai luontoarvon merkittävyyden sanallisesti.

Muun tyyppiset lisätietojen arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/note.html content="Mikäli ympäristöarvojen perusteet ja merkittävyydet kuvataan tulevaisuudessa omina koodistoinaan, tulee lisätietojen sallittuja arvoja muuttaa viittaamaan niihin" %}

{% include common/question.html content="Tämä pääluokka toimii nyt kaatoluokkana, koska sitä ei ole rajattu vain ryhmittelyotsikoksi. Onko tämä tarkoitus?" %}

## Alue, jolla ympäristö säilytetään
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0703>

{% include common/clause_start.html type="req" id="prof-yk/vaat-sailytettava-ymparisto-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolla ympäristö säilytetään.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-sailytettava-ymparisto-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-sailytettava-ymparisto-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Alue, jolla on erityistä ulkoilun ohjaamistarvetta
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0704>

{% include common/clause_start.html type="req" id="prof-yk/vaat-ulkoilun-ohjaamistarve-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolla on sen luontoarvojen vuoksi erityistä ulkoilun ohjaamistarvetta.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-ulkoilun-ohjaamistarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-ulkoilun-ohjaamistarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}