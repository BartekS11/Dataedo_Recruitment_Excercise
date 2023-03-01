Zapozna� si� z dokumentacj�, wymaganiami zadania
- W pliku Program.cs z�a nazwa pliku podana w 15 linijce, zamiast "data.csv" jest "dataa.csv",
- W Program.cs dyrektywy using s� w z�ym miejscu, powinny by� przed definicj� namespace, powinny by� r�wnie� usuni�te dyrektywy using
poniewa� nie s� one u�ywane,
- W pliku DataReader.cs dyrektywy using s� w z�ym miejscu, powinny si� znajdowa� przed deklaracj� namespace, powinny by� r�wnie� usuni�te dyrektywy using
kt�re nie s� one u�ywane
- W pliku DataReader.cs po przeprowadzeniu operacji splitowania poszczeg�lnej linii, przemy�le� pomin�� pierwsz� linie, b�d�c� najpewniej headerem pliku csv (sprawdzi� w wymaganiach)
- W sekcjii "clear and correct imported data" rozwa�y� skipni�cie headera csv w range-based for loopie
- Podobnie rozwa�y� skipni�cie headera w przypadku printowania bazy danych (sekcja "print all database's tables" jak i sekcja "print all table's columns") 
- W klasie ImportedObject rozwa�y� zasygnalizowanie zas�oni�cia atrybutu "Name" (np. z u�yciem keyworda "new") w celu unikni�cia dwuznaczno�ci
- W klasie ImportedObject rozwa�y� zmian� typu pola NumberOfChildren z double na int (sprawdzi� czy zgodne z wymaganiami)