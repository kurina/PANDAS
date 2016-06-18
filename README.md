# PANDAS knižnica programovacieho jazyka Python3

  V krátkosti sa pokúsim demonštrovať základné možnosti knižnice PANDAS na dátach, ktoré obsahujú onformácie z krajov, okresov, obcí a ulíc SR. Uvedené dáta boli získané z adresy : [Poštové smerovacie čísla] (http://www.posta.sk/sluzby/postove-smerovacie-cisla).
  
  Pri potrebe vyhľadávanie GPS súradníc pre jednotlivé ulice na SR, som narazil na problém, nakoľko som nenašiel nikde dôveryhodný zdroj (okrem spomínanej web adresy Slovenskej pošty) kde by boli pokope zoznam krajov, okresov, obcí, ulíc, PSČ a predovšetkým GPS súradnice.
  
<div style='font-size:0.6em;'>
<sup>1st edition, published September 23rd 2015<br>
Paperback: 454 pages<br>
Publisher: Packt Publishing<br>  
Language: English<br>
ISBN-10: 1783555130<br>  
ISBN-13: 978-1783555130<br>
Kindle ASIN: B00YSILNL0<br>
</div>
  
  Na uvedenej adrese je možné získať "zip" balík, ktorý obsahuje tri excel súbory:
  OBCE.xlsx
  ULICE.xlsx
  POBoxy.xlsx
  
  Pre moje potreby som použil súbory OBCE.xlsx a ULICE.xlsx. PANDAS dokáže samozrejme pracovať buď stýmto formátom (avšak je potrebné mať nainštalovaný modul xlrd a následne je ptrebné ho aj naimportovať...), alebo ak excelovský tvar prevedete do CSV formátu tak priamo aj sním. 
  
  V príklade budú uvedené oba prístupy.
  
  cieľom je získať výslednú dátovú štruktúru (Pandas DataFrame), ktorý by obsahoval všetko v jednom:
  KRAJ, OKRES, OBEC, ULICA, GPS (LATITUDE,LONGITUDE)

  Následne pochopiteľne túto datovú štruktúru uložíme do excel/CSV formátu podľa potreby...
  
                                                                                  Ing. Tibor Kurina, Ph.D.

  
  
  
  
  
