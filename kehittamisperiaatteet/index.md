---
layout: "default"
description: ""
id: "kehittamisperiaatteet"
status: "Ehdotus"
---
# Kaavamääräyslajit - kehittämisperiaatteet
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/alueJotaKoskeeKehittamisperiaate>

1. 
{:toc}

## Yhdyskuntarakenteen laajenemissuunta
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/yhdyskuntarakenteenLaajenemissuunta>

{% include common/clause_start.html type="req" id="sp-yk/vaat-yhdyskuntarakenteen-laajenemissuunta-arvot" %}
```arvo```-attribuutin mahdolliset arvot ovat seuraavat:
* Yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} joka kertoo yhdyskuntarakenteen laajenemissuunnan asteina (```deg```). Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta.
* Nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} jotka viittaavat koodiston [KaavamääraysLaji](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/) alakoodeihin, ja joiden avulla voidaan kuvata laajenevan yhdyskuntarakenteen käyttötarkoitukset.

Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-yk/vaat-yhdyskuntarakenteen-laajenemissuunta-geometria" %}
{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavakohde" title="Kaavakohteen" %}, johon liittyy Yhdyskuntarakenteen laajenemissuunta -lajin kaavamääräys, ```geometria```-attribuutin arvon tulee olla pistemäinen, ja sen tulee sijaita paikassa, josta yhdyskuntarakenne laajenee ```arvo```-attribuutin osoittamaan suuntaan.  
{% include common/clause_end.html %}

## Yhdyskuntarakenteen mahdollinen laajenemisalue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/yhdyskuntarakenteenMahdollinenLaajenemisAlue>

{% include common/clause_start.html type="req" id="sp-yk/vaat-yhdyskuntarakenteen-laajenemisalue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} jotka viittaavat koodiston KaavamääraysLaji koodin [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/01) alakoodeihin, ja joiden avulla voidaan kuvata laajenevan yhdyskuntarakenteen käyttötarkoitukset. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-yk/vaat-yhdyskuntarakenteen-laajenemisalue-geometria" %}
{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavakohde" title="Kaavakohteen" %} johon liittyy Yhdyskuntarakenteen mahdollinen laajenemisalue -lajin kaavamääräys, ```geometria```-attribuutin arvon tulee olla aluemainen.
{% include common/clause_end.html %}

## Eheytettävä tai tiivistettävä alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/eheytettavaTaiTiivistettavaAlue>

{% include common/clause_start.html type="req" id="sp-yk/vaat-eheytettava-tai-tiivistettava-alue" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.  Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-yk/vaat-eheytettava-tai-tiivistettava-alue" %}
{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavakohde" title="Kaavakohteen" %} johon liittyy Eheytettävä tai tiivistettävä alue -lajin kaavamääräys, ```geometria```-attribuutin arvon tulee olla aluemainen.
{% include common/clause_end.html %}

<!--
## Kävely-ympäristön kehittämistarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0412>

{% include common/clause_start.html type="req" id="sp-yk/vaat-kavely-ympariston-kehittamistarve-maar" %}
Ilmaisee, että kaavakohde kuvaa kävely-ympäristön kehittämistarpeen.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-yk/vaat-kavely-ympariston-kehittamistarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}
-->
<!--
## Meluntorjuntatarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0414>

{% include common/clause_start.html type="req" id="sp-yk/vaat-meluntorjuntatarve-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolla esiintyy siinä määrin melua, että siitä voi aiheutua merkittävää haittaa. Meluntorjunta tulee huomioida alueen käyttöä ja rakentamista suunniteltaessa.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-yk/vaat-meluntorjuntatarve-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), jolla kuvataan melun tyyppiä ja haitallisuutta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}-->