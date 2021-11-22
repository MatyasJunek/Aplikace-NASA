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
    * Program by měl být jednoduchý a lehce použitelný. Při používání by se měl uživatel cítil lépe, než při používání oken prohlížeče. Stejně tak by se měl cítit příjemněji, než čtení ve formátu JSON.
  * Detaily
    * Uživatel nemůže přímo do programu zasáhnout, protože se všechna data berou přímo z databáze NASA a uživatel nemůže nic přidat ani odebrat. Jediné chyby tak mohou být způsobeny chybou ve spojení, nebo nepřesností v kódu.
  * Všechny možné toky programu a jejich projevy
    * Hlavní okno programu ukazuje seznam asteroidů v blízkosti Země a jejich učité vlastnosti. Rozkliknutím jednotlivého asteroidu se zobrazí podrobnější informace. Informace se budou pravidelně aktualizovat a při výpadku spojení se zobrazí poslední aktualizované informace.
* Otevřené otázky
  * Části, na kterých se zatím nedosáhlo shody
    * Implementace astronomických zajímavostí, které by mohly program obohatit a zveselit.
