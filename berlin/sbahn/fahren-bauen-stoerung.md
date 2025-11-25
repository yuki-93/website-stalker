Alle Fahrplanänderungen (Bauen, Störungen) | S-Bahn Berlin GmbH /\*\<![CDATA[\*/ /\*\_scriptCode\*/ /\* decrypt helper function \*/ function decryptCharcode(n,start,end,offset) { n = n + offset; if (offset \> 0 && n \> end) { n = start + (n - end - 1); } else if (offset \< 0 && n \< start) { n = end - (start - n - 1); } return String.fromCharCode(n); } /\* decrypt string \*/ function decryptString(enc,offset) { var dec = ""; var len = enc.length; for(var i=0; i \< len; i++) { var n = enc.charCodeAt(i); if (n \>= 0x2B && n \<= 0x3A) { dec += decryptCharcode(n,0x2B,0x3A,offset); /\* 0-9 . , - + / : \*/ } else if (n \>= 0x40 && n \<= 0x5A) { dec += decryptCharcode(n,0x40,0x5A,offset); /\* A-Z @ \*/ } else if (n \>= 0x61 && n \<= 0x7A) { dec += decryptCharcode(n,0x61,0x7A,offset); /\* a-z \*/ } else { dec += enc.charAt(i); } } return dec; } /\* decrypt spam-protected emails \*/ function linkTo\_UnCryptMailto(s) { location.href = decryptString(s,-2); } /\*]]\>\*/  var removeInitalCSS = window.dynamicScriptLoad || (function(document, window) { 'use strict'; var obj; obj = { init: function() { let initialStyle = document.querySelector('#inital-css-style'); window.requestAnimationFrame(function() { window.requestAnimationFrame(function() { initialStyle.remove(); }) }) } }; return obj; })(document, window);  body { opacity: 0; } \<link rel="stylesheet" type="text/css" href="/typo3conf/ext/sbb\_sitepackage/Resources/Public/Frontend/css/main.css?1764075170" media="all"\>\<style id="inital-css-style"\> body { opacity: 1; } \</style\> window.project = { spriteTimestamp: '?1764075170', config: { system: { code: 'lab', baseUrl: 'https://sbahn.berlin/' }, ext: { news: true, events: false, slider: true } }, locallang: { more: 'more' } }  var \_mtm = window.\_mtm = window.\_mtm || []; \_mtm.push({'mtm.startTime': (new Date().getTime()), 'event': 'mtm.Start'}); (function() { var d=document, g=d.createElement('script'), s=d.getElementsByTagName('script')[0]; g.async=true; g.src='https://numbers.sbahn.berlin/js/container\_EvcjsdYJ.js'; s.parentNode.insertBefore(g,s); })(); [Zum Hauptinhalt](https://sbahn.berlin/fahren/bauen-stoerung/#start-content)[Zur Suche](https://sbahn.berlin/suche/)[Zur Suche](https://sbahn.berlin/fahren/bauen-stoerung/#searchfield)[Zur Hauptnavigation](https://sbahn.berlin/fahren/bauen-stoerung/#start-menu-main)[Zur Fußzeile](https://sbahn.berlin/fahren/bauen-stoerung/#start-footer)

[Zur Startseite - S-Bahn Berlin](https://sbahn.berlin/)[Unternehmen](https://sbahn.berlin/das-unternehmen/)[Kontakt & Hilfe](https://sbahn.berlin/kontakt/)Meine S-Bahn

Meine S-Bahn

* [Meine Übersicht](https://sbahn.berlin/meine-s-bahn/)
* [Meine Daten ändern](https://sbahn.berlin/meine-s-bahn/?pageId=914&return_url=%2Fmeine-s-bahn%2Fmein-profil-bearbeiten%2F&cHash=0b19aace2051c857d46d737d2737fefa)
*
* [Logout](https://sbahn.berlin/meine-s-bahn/?logintype=logout&cHash=ee3063d942156a05265a0b89b54ca623)

[de](https://sbahn.berlin/fahren/bauen-stoerung/)[en](https://sbahn.berlin/en/plan-a-journey/timetable-changes/)[](https://sbahn.berlin/suche/)[](https://www.bahn.de/)

 { "@context": "https://schema.org", "@type": "ItemList", "itemListElement": [{"@type":"SiteNavigationElement","position":1,"name":"Fahren","description":"Der Bereich Fahren gibt Ihnen den \\u00dcberblick zu allen Linien und m\\u00f6glichen Fahrplan\\u00e4nderungen. Seien Sie immer top informiert!","url":"https://sbahn.berlin/fahren/"},{"@type":"SiteNavigationElement","position":2,"name":"Liniennetz","description":"Digitales Liniennetz mit Linienverl\\u00e4ufen, Bahnhofsinformationen, Abfahrtszeiten, St\\u00f6rungs-/Bauinformationen und Ausflugstipps. ","url":"https://sbahn.berlin/liniennetz/"},{"@type":"SiteNavigationElement","position":3,"name":"Tickets","description":"Pendler, Studenten, spontane Abenteurer, Touristen \\u2013 bei der S-Bahn Berlin gib es f\\u00fcr jeden das passende Ticket.","url":"https://sbahn.berlin/tickets/"},{"@type":"SiteNavigationElement","position":4,"name":"Ausfl\\u00fcge","description":"Berlin bietet viele Freizeitaktivit\\u00e4ten. Eine vielf\\u00e4ltige Inspiration bietet diese Seite der S-Bahn Berlin. Von Ausflugstouren, \\u00fcber Rabatte f\\u00fcr Fahrg\\u00e4ste und Gewinnspiele, gibt es hier viel Neues zu entdecken. ","url":"https://sbahn.berlin/was-hast-du-vor/"},{"@type":"SiteNavigationElement","position":5,"name":"S-Bahn-Welt","description":"Hier k\\u00f6nnen Sie die S-Bahn Berlin erleben und besser kennenlernen. ","url":"https://sbahn.berlin/s-bahn-welt/"},{"@type":"SiteNavigationElement","position":6,"name":"Touristen","description":"Wichtige Informationen zu den Verkehrsmitteln und dem Tarif in Berlin und Brandenburg.","url":"https://sbahn.berlin/fahren/infos-fuer-berlin-besucher/"}] }

* [Fahren](https://sbahn.berlin/fahren/)
* [Liniennetz](https://sbahn.berlin/liniennetz/)
* [Tickets](https://sbahn.berlin/tickets/)
* [Ausflüge](https://sbahn.berlin/was-hast-du-vor/)
* [S-Bahn-Welt](https://sbahn.berlin/s-bahn-welt/)
* [Touristen](https://sbahn.berlin/fahren/infos-fuer-berlin-besucher/)

Suche
----------

 Suchbegriff eingeben

Suche starten

Öffne Seitennavigation

* [Startseite](https://sbahn.berlin/)
* [Fahren](https://sbahn.berlin/fahren/)
  * [Fahrplanauskunft](https://sbahn.berlin/fahren/fahrplanauskunft/)
    * [Linienfahrpläne](https://sbahn.berlin/fahren/fahrplanauskunft/linienfahrplaene/)

  * [Linienübersicht](https://sbahn.berlin/fahren/)
  * [Bauen & Störung](https://sbahn.berlin/fahren/bauen-stoerung/)
    * [Gründe für Störungen](https://sbahn.berlin/fahren/bauen-stoerung/gruende-fuer-stoerungen/)
    * [Wieso wird gebaut?](https://sbahn.berlin/fahren/bauen-stoerung/wieso-wird-gebaut/)
    * [Verspätungsbescheinigung](https://sbahn.berlin/fahren/bauen-stoerung/verspaetungsbescheinigung/)
    * [Baumaßnahme](https://sbahn.berlin/fahren/bauen-stoerung/bauen/)
    * [Auswirkung](https://sbahn.berlin/fahren/bauen-stoerung/auswirkung/)

  * [Bahnhofsübersicht](https://sbahn.berlin/fahren/bahnhofsuebersicht/)
    * [Ausstattung von Bahnhöfen](https://sbahn.berlin/fahren/bahnhofsuebersicht/ausstattung-von-bahnhoefen/)
    * [Hausordnung](https://sbahn.berlin/fahren/bahnhofsuebersicht/hausordnung/)

  * [Liniennetze](https://sbahn.berlin/fahren/liniennetze/)
  * [Touristen](https://sbahn.berlin/fahren/infos-fuer-berlin-besucher/)
    * [Berlins Flughafen Berlin Brandenburg (BER)](https://sbahn.berlin/fahren/infos-fuer-berlin-besucher/berlins-flughafen-berlin-brandenburg-ber/)
    * [Zentraler Busbahnhof (ZOB)](https://sbahn.berlin/fahren/infos-fuer-berlin-besucher/zentraler-busbahnhof-zob/)
    * [Hauptbahnhof Berlin](https://sbahn.berlin/fahren/infos-fuer-berlin-besucher/hauptbahnhof-berlin/)

  * [Hilfe für unterwegs](https://sbahn.berlin/fahren/hilfe-fuer-unterwegs/)
    * [Barrierefrei unterwegs](https://sbahn.berlin/fahren/bahnhofsuebersicht/barrierefrei-unterwegs/)
    * [Notruf & Hotlines](https://sbahn.berlin/fahren/hilfe-fuer-unterwegs/notruf-hotlines/)
    * [Übergriffiges Verhalten - was tun?](https://sbahn.berlin/fahren/hilfe-fuer-unterwegs/uebergriffiges-verhalten-hilfe/)
    * [Automatenstörung](https://sbahn.berlin/tickets/verkauf-kontakt/ticketautomat/)
    * [Fahrscheinkontrolle](https://sbahn.berlin/tickets/vbb-tarif-erklaert/fahrscheinkontrolle/)
    * [Fundservice](https://sbahn.berlin/fahren/hilfe-fuer-unterwegs/fundservice/)
    * [Verhalten bei Betriebsstörungen](https://sbahn.berlin/fahren/hilfe-fuer-unterwegs/verhalten-bei-betriebsstoerungen/)
    * [Informationsmöglichkeiten](https://sbahn.berlin/fahren/hilfe-fuer-unterwegs/informationsmoeglichkeiten/)
    * [WC-Suche](https://sbahn.berlin/fahren/hilfe-fuer-unterwegs/wc-suche/)

* [Liniennetz](https://sbahn.berlin/liniennetz/)
* [Tickets](https://sbahn.berlin/tickets/)
  * [VBB-Tarif erklärt](https://sbahn.berlin/tickets/vbb-tarif-erklaert/)
    * [Tarifbereiche](https://sbahn.berlin/tickets/vbb-tarif-erklaert/tarifbereiche/)
    * [Fahrscheinkontrolle](https://sbahn.berlin/tickets/vbb-tarif-erklaert/fahrscheinkontrolle/)
    * [Beförderungsbedingungen](https://sbahn.berlin/tickets/vbb-tarif-erklaert/befoerderungsbedingungen/)
    * [Fahrgastrechte](https://sbahn.berlin/tickets/vbb-tarif-erklaert/fahrgastrechte/)
    * [Tarifbroschüren](https://sbahn.berlin/tickets/vbb-tarif-erklaert/tarifbroschueren/)
    * [Mitnahmeregelungen](https://sbahn.berlin/tickets/vbb-tarif-erklaert/mitnahmeregelungen/)

  * [Alle Tickets](https://sbahn.berlin/tickets/alle-tickets/)
    * [Alle Tickets - Preise](https://sbahn.berlin/tickets/alle-tickets/alle-tickets-preise/)
    * [Einzelfahrausweise/ Tageskarten](https://sbahn.berlin/tickets/alle-tickets/einzelfahrausweise-tageskarten/)
    * [Wochen-/ Monats-/ Abo-/ Jahrestickets](https://sbahn.berlin/tickets/alle-tickets/wochen-monats-abo-jahrestickets/)
    * [Schüler/ Azubis / Studenten](https://sbahn.berlin/tickets/alle-tickets/schueler-azubis-studenten/)
    * [Gruppentickets](https://sbahn.berlin/tickets/alle-tickets/gruppentickets/)
    * [Fahrradmitnahme](https://sbahn.berlin/tickets/alle-tickets/fahrradmitnahme/)
    * [Touristentickets](https://sbahn.berlin/tickets/alle-tickets/touristentickets/)
    * [Regionalverkehr](https://sbahn.berlin/tickets/alle-tickets/regionalverkehr/)

  * [Handyticket](https://sbahn.berlin/tickets/handyticket/)
  * [Verkauf / Kontakt](https://sbahn.berlin/tickets/verkauf-kontakt/)
    * [Verkaufsstellen](https://sbahn.berlin/tickets/verkauf-kontakt/verkaufsstellen/)
    * [Ticketautomat](https://sbahn.berlin/tickets/verkauf-kontakt/ticketautomat/)
    * [Online-Shop](https://shop.sbahn.berlin/Cms/CmsPage/Page/Startseite)

  * [VBB-Ticket im Abo](https://sbahn.berlin/tickets/vbb-ticket-im-abo/)
    * [Startkarte](https://sbahn.berlin/tickets/vbb-ticket-im-abo/startkarte/)
    * [VBB-fahrCard](https://sbahn.berlin/tickets/vbb-ticket-im-abo/vbb-fahrcard/)
    * [Abo bestellen & verwalten](https://www.abo-antrag.de/)

  * [Infos für Berlin Besucher](https://sbahn.berlin/fahren/infos-fuer-berlin-besucher/)

* [Ausflüge](https://sbahn.berlin/was-hast-du-vor/)
  * [Gewinnspiele](https://sbahn.berlin/was-hast-du-vor/gewinnspiele/)
    * [Weihnachtskalender](https://sbahn.berlin/was-hast-du-vor/gewinnspiele/weihnachtskalender/)

  * [Angesagt](https://sbahn.berlin/was-hast-du-vor/neues-entdecken/)
  * [Ausflugstouren](https://sbahn.berlin/was-hast-du-vor/ausflugstouren/)

* [S-Bahn-Welt](https://sbahn.berlin/s-bahn-welt/)
  * [Die S-Bahn-Züge](https://sbahn.berlin/das-unternehmen/fahrzeugpark/)
  * [Geschichte der Berliner S-Bahn](https://sbahn.berlin/das-unternehmen/unternehmensprofil/die-historie-der-berliner-s-bahn/)
  * [Fanartikel](https://sbahn.berlin/s-bahn-welt/fanartikel/)
    * [Videocall-Hintergründe](https://sbahn.berlin/s-bahn-welt/fanartikel/videocall-hintergruende/)
    * [Malvorlagen](https://sbahn.berlin/s-bahn-welt/fanartikel/malvorlagen/)

  * [Kundenbeirat der S-Bahn Berlin](https://sbahn.berlin/s-bahn-welt/unser-beirat-fuer-kundinnen/)
    * [Bewerbung Kundenbeirat](https://sbahn.berlin/s-bahn-welt/unser-beirat-fuer-kundinnen/bewerbung-beirat-fuer-kundinnen/)

  * [Liebe in rot-gelb](https://sbahn.berlin/s-bahn-welt/liebe-in-rot-gelb/)
    * [Zugtaufen](https://sbahn.berlin/s-bahn-welt/liebe-in-rot-gelb/zugtaufen/)
    * [Wohltätigkeitsaktionen](https://sbahn.berlin/das-unternehmen/unternehmensprofil/engagement-fuer-berlin/wohltaetigkeitsaktionen/)
    * [Verbände und Vereine](https://sbahn.berlin/das-unternehmen/unternehmensprofil/engagement-fuer-berlin/vereine-und-hilfsorganisationen/)
    * [S-Bahner:innen und ihre Hobbys](https://sbahn.berlin/s-bahn-welt/liebe-in-rot-gelb/s-bahner-und-ihre-hobbys/)

* [Touristen](https://sbahn.berlin/fahren/infos-fuer-berlin-besucher/)
  * [Berlins Flughafen Berlin Brandenburg (BER)](https://sbahn.berlin/fahren/infos-fuer-berlin-besucher/berlins-flughafen-berlin-brandenburg-ber/)
  * [Zentraler Busbahnhof (ZOB)](https://sbahn.berlin/fahren/infos-fuer-berlin-besucher/zentraler-busbahnhof-zob/)
  * [Hauptbahnhof Berlin](https://sbahn.berlin/fahren/infos-fuer-berlin-besucher/hauptbahnhof-berlin/)

* [Unternehmen](https://sbahn.berlin/das-unternehmen/)
  * [Unternehmensprofil](https://sbahn.berlin/das-unternehmen/unternehmensprofil/)
    * [Nur für alle](https://sbahn.berlin/das-unternehmen/unternehmensprofil/nur-fuer-alle/)
    * [Auf einen Blick - Zahlen und Fakten](https://sbahn.berlin/das-unternehmen/unternehmensprofil/auf-einen-blick-zahlen-und-fakten/)
    * [Geschäftsführung](https://sbahn.berlin/das-unternehmen/unternehmensprofil/geschaeftsfuehrung/)
    * [Die Historie der Berliner S-Bahn](https://sbahn.berlin/das-unternehmen/unternehmensprofil/die-historie-der-berliner-s-bahn/)
    * [Umweltschutz](https://sbahn.berlin/das-unternehmen/unternehmensprofil/umweltschutz/)
    * [Engagement für Berlin](https://sbahn.berlin/das-unternehmen/unternehmensprofil/engagement-fuer-berlin/)
    * [Unsere Partner im ÖPNV](https://sbahn.berlin/das-unternehmen/unternehmensprofil/unsere-partner-im-oepnv/)

  * [Verkehrswende Ding](https://sbahn.berlin/das-unternehmen/verkehrswende-ding/)
  * [Als Arbeitgeberin](https://sbahn.berlin/das-unternehmen/als-arbeitgeberin/)
    * [Instandhaltungsberufe](https://sbahn.berlin/das-unternehmen/als-arbeitgeberin/instandhaltungsberufe/)
    * [Lokführer:innen gesucht](https://sbahn.berlin/das-unternehmen/als-arbeitgeberin/lokfuehrerinnen-gesucht/)
    * [Frauen bei der S-Bahn](https://sbahn.berlin/das-unternehmen/als-arbeitgeberin/frauen-bei-der-s-bahn/)
    * [Qualifiziertes Ausbildungsangebot](https://sbahn.berlin/das-unternehmen/als-arbeitgeberin/qualifiziertes-ausbildungsangebot/)

  * [Fahrzeugpark](https://sbahn.berlin/das-unternehmen/fahrzeugpark/)
    * [Die neue S-Bahn](https://sbahn.berlin/das-unternehmen/fahrzeugpark/die-neue-s-bahn/)
    * [IdeenzugCity](https://sbahn.berlin/das-unternehmen/fahrzeugpark/ideenzugcity/)
    * [Baureihe 481](https://sbahn.berlin/das-unternehmen/fahrzeugpark/baureihe-481/)
    * [Baureihe 480](https://sbahn.berlin/das-unternehmen/fahrzeugpark/baureihe-480/)
    * [Baureihe 485](https://sbahn.berlin/das-unternehmen/fahrzeugpark/baureihe-485/)
    * [Historische Züge](https://sbahn.berlin/das-unternehmen/fahrzeugpark/historische-zuege/)
    * [Instandhaltungswerke](https://sbahn.berlin/das-unternehmen/fahrzeugpark/instandhaltungswerke/)

  * [Informations- & Verkehrstechnik](https://sbahn.berlin/das-unternehmen/informations-verkehrstechnik/)
    * [Wie voll ist meine S-Bahn?](https://sbahn.berlin/das-unternehmen/informations-verkehrstechnik/auslastung/)

  * [Sicherheit & Sauberkeit](https://sbahn.berlin/das-unternehmen/sicherheit-sauberkeit/)
    * [Sicherheit](https://sbahn.berlin/das-unternehmen/sicherheit-sauberkeit/sicherheit/)
    * [Sauberkeit](https://sbahn.berlin/das-unternehmen/sicherheit-sauberkeit/sauberkeit/)

  * [Presse](https://sbahn.berlin/das-unternehmen/presse/)
    * [Pressemitteilungen, Pressearchiv](https://sbahn.berlin/das-unternehmen/presse/pressemitteilungen-pressearchiv/)
    * [Pressebilder](https://sbahn.berlin/das-unternehmen/presse/pressebilder/)
    * [Foto- und Drehgenehmigungen](https://sbahn.berlin/das-unternehmen/presse/foto-und-drehgenehmigungen/)

  * [Werbeflächen in den Zügen](https://sbahn.berlin/das-unternehmen/werbeflaechen-in-den-zuegen/)
    * [Deckenflächenplakat](https://sbahn.berlin/das-unternehmen/werbeflaechen-in-den-zuegen/deckenflaechenplakat/)
    * [Train-Poster](https://sbahn.berlin/das-unternehmen/werbeflaechen-in-den-zuegen/train-poster/)

[Fahrplanauskunft](https://sbahn.berlin/fahren/fahrplanauskunft/)[Bauen & Störungen](https://sbahn.berlin/fahren/bauen-stoerung/)

Service

* [Kontakt & Hilfe](https://sbahn.berlin/kontakt/)
* [Aufzugs- & Fahrtreppenstörung](https://sbahn.berlin/fahren/bahnhofsuebersicht/barrierefrei-unterwegs/aufzugs-fahrtreppenstoerung/)
* [Verkaufsstellen](https://sbahn.berlin/tickets/verkauf-kontakt/verkaufsstellen/)
* [Meine S-Bahn](https://sbahn.berlin/meine-s-bahn/)
* [WC-Suche](https://sbahn.berlin/fahren/hilfe-fuer-unterwegs/wc-suche/)

Hotline

Sie erreichen uns täglich rund um die Uhr+49 30 29743333:

[\+49 30 29743333](tel:+493029743333)[S-Bahn Service überWhat's App](whatsapp://send/?phone=+493029712971&text=hallo)

* [Impressum](https://sbahn.berlin/impressum/)
* [Datenschutz](https://sbahn.berlin/datenschutz/)
* [Barrierefreiheit](https://sbahn.berlin/barrierefreiheit/)
* [Nur für alle](https://sbahn.berlin/das-unternehmen/unternehmensprofil/nur-fuer-alle/)
* [Cookie-Einstellungen](https://sbahn.berlin/fahren/bauen-stoerung/#)
* [Abo kündigen](https://www.abo-antrag.de/de/kuendigen/)

* [Startseite](https://sbahn.berlin/)
* [Fahren](https://sbahn.berlin/fahren/)
* Bauen & Störung

 Störungen und Bauarbeiten:
==========

 Bauinfos, Störungen und Fahrplanänderungen
----------

<img src="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%224%22%20height%3D%221%22%20viewBox%3D%220%200%204%201%22%3E%3Crect%20width%3D%224%22%20height%3D%221%22%20fill%3D%22%23f6f6f7%22%2F%3E%3C%2Fsvg%3E" data-src="/fileadmin/_processed_/1/1/csm_Nordring_Sperrung_Santiago_Engelhardt_L1002073_punkt3_09-21_2ef30b17ef.jpg" class="o-lazyload" alt="Infrastruktur der Berliner S-Bahn - Investitionen in Zukunft" title="Infrastruktur der Berliner S-Bahn - Investitionen in Zukunft" width="4" height="1">©Santiago Engelhardt

<img aria-hidden="true" class="o-lazyload" src="https://sbahn.berlin/fileadmin/user_upload/Verteilerbilder/pattern_lift.svg" width="20" height="9" alt="" title="pattern_lift.svg">

Aufzug- & Fahrtreppenstörungen
----------

Information zu gestörten Aufzügen und Fahrtreppen pro Bahnhof

[Mehr lesen über Aufzug- & Fahrtreppenstörungen](https://sbahn.berlin/fahren/bahnhofsuebersicht/barrierefrei-unterwegs/aufzugs-fahrtreppenstoerung/)

<img aria-hidden="true" class="o-lazyload" src="https://sbahn.berlin/fileadmin/user_upload/Verteilerbilder/pattern_construction.svg" width="20" height="9" alt="" title="pattern_construction.svg">

Wieso wird gebaut?
----------

Noch mehr Sicherheit, Pünktlichkeit und Komfort - daran wird gearbeitet!

[Mehr lesen über Wieso wird gebaut?](https://sbahn.berlin/fahren/bauen-stoerung/wieso-wird-gebaut/)

<img aria-hidden="true" class="o-lazyload" src="https://sbahn.berlin/fileadmin/user_upload/Verteilerbilder/pattern_app.svg" width="20" height="9" alt="" title="pattern_app.svg">

Gründe für Störungen
----------

Hier erfahren Sie warum es wo Störungen gibt.

[Mehr lesen über Gründe für Störungen](https://sbahn.berlin/fahren/bauen-stoerung/gruende-fuer-stoerungen/)

###  Hotline  ###

 Sie erreichen uns täglich rund um die Uhr

[\+49 30 29743333](tel:+493029743333)

### [Hilfe / FAQ](https://sbahn.berlin/kontakt/) ###

 Die wichtigsten Antworten und Hilfestellungen für unterwegs

### [Verkaufsstellen](https://sbahn.berlin/tickets/verkauf-kontakt/verkaufsstellen/) ###

 Ticketverkauf und persönliche Beratung

### [Newsletter](https://sbahn.berlin/ihr-passender-newsletter/) ###

 Immer top informiert – mit unserem Newsletter

* [Impressum](https://sbahn.berlin/impressum/)
* [Datenschutz](https://sbahn.berlin/datenschutz/)
* [Barrierefreiheit](https://sbahn.berlin/barrierefreiheit/)
* [Nur für alle](https://sbahn.berlin/das-unternehmen/unternehmensprofil/nur-fuer-alle/)
* [Cookie-Einstellungen](https://sbahn.berlin/fahren/bauen-stoerung/#)

####  Login  ####

 Login

 E-Mail-Adresse

 Passwort

[Passwort vergessen?](https://sbahn.berlin/meine-s-bahn/?tx_hairu_auth%5Baction%5D=showPasswordResetForm&tx_hairu_auth%5BreturnUrl%5D=%2Ffahren%2Fbauen-stoerung%2F&tx_hairu_auth%5Bstart%5D=1&cHash=ba6c86ba8db73508977a5710b8571c2e)

 Anmelden

### Registrierung bei "Meine S-Bahn" ###

Registrieren Sie sich für personalisierte Newsletter, Gewinnspiele und Informationen zu Ihren Routen.

[Jetzt registrieren](https://sbahn.berlin/registrierung/)

---

### Weitere Onlinedienste: ###

* [Zum Online-Shop](https://shop.sbahn.berlin/Cms/CmsPage/Page/Startseite)
* [Zur Abo-Bestellung/Verwaltung](https://www.abo-antrag.de/)
* [Zum EBE-Portal (Bußgeld bei Fahrt ohne Ticket)](https://www.sbahn-ebe.de/uebersicht/)

Nach oben scrollen
