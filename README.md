# PANDAS knižnica programovacieho jazyka Python3
*Let's Playing With Datas*


  V krátkosti sa pokúsim demonštrovať základné možnosti knižnice PANDAS na dátach, ktoré obsahujú onformácie z krajov, okresov, obcí a ulíc SR. Uvedené dáta boli získané z adresy : [Poštové Smerovacie Čísla] (http://www.posta.sk/sluzby/postove-smerovacie-cisla).
  
  Pri potrebe vyhľadávanie GPS súradníc pre jednotlivé ulice na SR, som narazil na problém, nakoľko som nenašiel nikde dôveryhodný zdroj (okrem spomínanej web adresy Slovenskej pošty) kde by boli pokope zoznam krajov, okresov, obcí, ulíc, PSČ a predovšetkým **GPS** súradnice.
  
  Na uvedenej adrese je možné získať "zip" balík, ktorý obsahuje tri excel súbory:
  OBCE.xlsx
  ULICE.xlsx
  POBoxy.xlsx
  
  > Pre moje potreby som použil súbory OBCE.xlsx a ULICE.xlsx. PANDAS dokáže samozrejme pracovať buď stýmto formátom (avšak je potrebné mať nainštalovaný modul xlrd a následne je ptrebné ho aj naimportovať...), alebo ak excelovský tvar prevedete do CSV formátu tak priamo aj sním. 
  
  V príklade budú uvedené oba prístupy.
  
  Cieľom je získať výslednú dátovú štruktúru (Pandas DataFrame), ktorý by obsahoval všetko v jednom:
  KRAJ, OKRES, OBEC, ULICA, GPS (LATITUDE,LONGITUDE)

  Následne pochopiteľne túto datovú štruktúru uložíme do excel/CSV formátu podľa potreby... <br>
  Takže začíname tu : [1. Kapitola : Od excelu k Pandas Data Frame] (./obce_and_ulice.ipynb)
  
  
                                                                                  Ing. Tibor Kurina, Ph.D.

  
  
  
  
  
