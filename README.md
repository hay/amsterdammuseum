Amsterdam Museum API
====================

General info
------------

* Tools and datasets/XML dumps for the [Amsterdam Museum API](http://www.amsterdammuseum.nl/open-data)
* "amsterdam-museum-complete.xml.zip" contains a complete dump of the collection from the Amsterdam Museum, downloaded at 10 november 2012, in XML OAI-PMH format.
* Made by [https://github.com/valhallasw](Merlijn van Deen). Thanks!

Stats on license status
-----------------------

Some stats in the dataset:

       6514 Public domain
      64734 Public Domain
          6 Public domainPublic domain
         84 Public DomainPublic Domain

Around 20.000 of the records don't have any copyright info, and are not PD.

Aquisition methods:
-------------------
         89
        456 aangetroffen
       9836 aankoop
          8 aankoopaankoop
          3 aankooponbekend
          1 aankoopoverdracht
          1 aankoopschenking
          1 afgegeven bij AHM
        439 bodemvondst
       8539 bruikleen
         11 bruikleenbruikleen
         10 door onteigening
          1 inbeslagneming
      13982 legaat
         38 legaat (?)
         16 legaatlegaat
         38 legaat (?) / onbekend
          1 legaatoud stadsbezit
         26 naasting
         76 nog invoeren
      10260 onbekend
          2 onbekendaankoop
          1 onbekendlegaat
          6 onbekendonbekend
          8 onbekend / opgenomen in collectie
          1 onbekendschenking
         12 onbekend / schenking
          2 onteigening
         15 opdracht
        250 opdracht museum
         39 opgenomen in collectie
         32 oud bezit
       1088 oud stadsbezit
         25 overboeking
       2261 overdracht
          4 overdrachtoverdracht
          4 overname
        145 ruil
      32139 schenking
          8 schenking / bruikleen
         34 schenkingschenking
          1 verhaal

Categories
----------
          1 beeldencollectiebeeldencollectie
          1 fotocollectiefotocollectie
          1 keramiekcollectieglascollectie
          1 keramiekcollectiekunstnijverheidcollectie
          1 prentencollectiekunstnijverheidcollectie
          1 textielcollectiekeramiekcollectie
          1 textielcollectiekunstnijverheidcollectie
          2 glascollectieglascollectie
          2 schilderijencollectieschilderijencollectie
          4 edele metalencollectieedele metalencollectie
          4 kunstnijverheid
          4 meubelcollectiemeubelcollectie
          5 keramiekcollectiekeramiekcollectie
          6 miniatuurzilver
          6 penningen- en muntencollectiepenningen- en muntencollectie
          6 tekeningencollectietekeningencollectie
          9 kunstnijverheidcollectiekunstnijverheidcollectie
         10 boekencollectieboekencollectie
         14 textielcollectietextielcollectie
         21 prentencollectieprentencollectie
         90
        500 archeologiecollectie
        607 maten en gewichtencollectie
        662 documentencollectie
        693 beeldencollectie
       1411 glascollectie
       1478 schilderijencollectie
       1627 onedele metalen collectie
       1782 fotocollectie
       3195 meubelcollectie
       3722 edele metalencollectie
       4950 tekeningencollectie
       5949 keramiekcollectie
       6906 penningen- en muntencollectie
       9928 kunstnijverheidcollectie
      11014 boekencollectie
      12566 textielcollectie
      21894 prentencollectie

Done using this query:

    xmlstarlet sel -t -v '//object_category' *.xml | sort | uniq -c | sort -n
