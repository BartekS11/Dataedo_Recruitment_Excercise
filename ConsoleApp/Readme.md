Zapoznaæ siê z dokumentacj¹, wymaganiami zadania
- W pliku Program.cs z³a nazwa pliku podana w 15 linijce, zamiast "data.csv" jest "dataa.csv",
- W Program.cs dyrektywy using s¹ w z³ym miejscu, powinny byæ przed definicj¹ namespace, powinny byæ równie¿ usuniête dyrektywy using
poniewa¿ nie s¹ one u¿ywane,
- W pliku DataReader.cs dyrektywy using s¹ w z³ym miejscu, powinny siê znajdowaæ przed deklaracj¹ namespace, powinny byæ równie¿ usuniête dyrektywy using
które nie s¹ one u¿ywane
- W pliku DataReader.cs po przeprowadzeniu operacji splitowania poszczególnej linii, przemyœleæ pomin¹æ pierwsz¹ linie, bêd¹c¹ najpewniej headerem pliku csv (sprawdziæ w wymaganiach)
- W sekcjii "clear and correct imported data" rozwa¿yæ skipniêcie headera csv w range-based for loopie
- Podobnie rozwa¿yæ skipniêcie headera w przypadku printowania bazy danych (sekcja "print all database's tables" jak i sekcja "print all table's columns") 
- W klasie ImportedObject rozwa¿yæ zasygnalizowanie zas³oniêcia atrybutu "Name" (np. z u¿yciem keyworda "new") w celu unikniêcia dwuznacznoœci
- W klasie ImportedObject rozwa¿yæ zmianê typu pola NumberOfChildren z double na int (sprawdziæ czy zgodne z wymaganiami)