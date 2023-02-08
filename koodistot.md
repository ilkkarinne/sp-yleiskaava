---
layout: "default"
description: ""
id: "koodistot"
status: "Ehdotus"
---
# Koodistot

## Vuorovaikutustapahtuman laji
{% include common/clause_start.html type="req" id="sp-yk/vaat-vuorovaikutustapahtuman-laji" %}
Luokan {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#abstraktivuorovaikutustapahtumanlaji" title="AbstraktiVuorovaikutustapahtumanLaji" %} sijaan tulee käyttää tarkentavaa luokkaa {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavanvuorovaikutustapahtumanlaji" title="KaavanVuorovaikutustapahtumanLaji" %}.
{% include common/clause_end.html %}

## Käsittelytapahtuman laji
{% include common/clause_start.html type="req" id="sp-yk/vaat-kasittelytapahtuman-laji" %}
Luokan {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#abstraktikasittelytapahtumanlaji" title="AbstraktiKasittelytapahtumanLaji" %} sijaan tulee käyttää tarkentavaa luokkaa {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavankasittelytapahtumanlaji" title="KaavanKasittelytapahtumanLaji" %}.
{% include common/clause_end.html %}

## Kaavakohdelaji
{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#abstraktikaavakohdelaji" title="AbstraktiKaavakohdelaji" %}-koodisto on varattu tulevaisuuden käyttöön. Tässä tietomalliin versiossa ei määritellä yleiskaavakohtaista koodistoa kaavakohdelajeille.

{% include common/clause_start.html type="req" id="sp-yk/vaat-kaavakohdelaji" %}
{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavakohde" title="Kaavakohde" %}-luokan ```laji```-attribuuttia ei saa käyttää informaation välittämiseen. Mikäli sille on annettu ei-tyhjä arvo, se tulee jättää huomiotta.  
{% include common/clause_end.html %}

## Kaavoitusteema
{% include common/clause_start.html type="req" id="sp-yk/vaat-kaavoitusteema" %}
Luokan {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#abstraktikaavoitusteema" title="AbstraktiKaavoitusteema" %} sijaan tulee käyttää tarkentavaa luokkaa {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavoitusteemayleiskaava" title="KaavoitusteemaYleiskaava" %}.
{% include common/clause_end.html %}

## Kaavamääräys
{% include common/clause_start.html type="req" id="sp-yk/vaat-kaavamaarays" %}
Luokan {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#abstraktikaavamaarayslaji" title="AbstraktiKaavamaaraysLaji" %} sijaan tulee käyttää tarkentavaa luokkaa {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavamaarayslaji" title="KaavamaaraysLaji" %}.
{% include common/clause_end.html %}

## Kaavamääräyksen lisätieto
{% include common/clause_start.html type="req" id="sp-yk/vaat-kaavamaarayksen-lisatieto" %}
Luokan {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#abstraktilisatieto" title="AbstraktiLisatieto" %} sijaan tulee käyttää tarkentavaa luokkaa {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatietoyleiskaava" title="LisatiedonLajiYleiskaava" %}.
{% include common/clause_end.html %}