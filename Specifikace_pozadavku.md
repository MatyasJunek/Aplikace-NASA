# Aplikace NASA
## Verze 1.0
### Matyáš Junek
#### 16. 11. 2021
* Úvod
  * Účel
    * Program slouží jako pomůcka pro **lehké a přehledné prohlížení a vyhledávání objektů v blízkosti Země**. Slouží jako náhrada za prohlížení těchto informací v oknech prohlížeče, které zbytečně zpomalují počítač.
  * Konvence dokumentu
    * Každý termín v dokumentu bude vyznačen kurzívou, důležité části budou zvýrazněny.
  * Pro koho je dokument určený
    * Dokument je určený pro uživatele, kteří chtějí podrobnou zprávu o programu. Může sloužit také jako návod, nebo jako základ pro vývojáře, kteří by chtěli program vylepšit.
  * Odkazy na ostatní dokumenty
    * [SRS](https://github.com/MatyasJunek/Aplikace-NASA/blob/main/README.md)
* Scénáře
  * Všechny reálné způsoby použití
    * Program můžeme využít pro **sledování objektů v blízkosti Země**. Mohou jej využít **studenti** atronomie, **zaujatí jedinci**, nebo i běžní, zvědaví lidé snažící se přijít na to, kdy do Země udeří *asteroid*.
  * Detaily, motivace, „živé“ příklady
    * Program bude používat volně dostupná data od *NASA*. Bude přetvářet *JSON* poskytnutý na oficiálních webových stránách *NASA API*. Data se budou při dostupném datovém připojení aktualizovat. Pokud nebude žádné připojení dostupné, zobrazí se poslední data a program bude ukazovat čas poslední aktualizace. 
  * Vymezení rozsahu
    * V programu budou pouze informace poskytnuté v jednom NASA API*, tedy pouze asteroidy v blízkosti Země.
  * Na co se nebude klást důraz
    * Důraz se nebude klást zejména na optimalizaci programu. Dále nebude zapotřebí zbytečná komplexnost a složitost - program by měl zůstat co nejvíce strohý.
* Celková hrubá architektura
  * Pracocní tok
    * Program by měl být jednoduchý a lehce použitelný. Při používání by se měl uživatel cítil lépe, než při používání oken prohlížeče.
  * Detaily
    * 
  * Všechny možné toky programu a jejich projevy
    * 
* Otevřené otázky
  * Části, na kterých se zatím nedosáhlo shody
    * 
