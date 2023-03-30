Type system:
Alle variabler bliver instantieret med den riktige datatype.

Null handling: 
vi bruger try catch ved hvores file readers.

String interpolation:
vi bruger string interpolation ved hvores league ToString()

Pattern Matching:
vi søger efter abriviations når vi søger efter cluberne, ved match returnerar vi den givne club object.

Classes, structs and enums: 
League, Club er en klass, vi bruger en struct som heder match, og enum til at specificere league type.

Properties:
getter og setters i vores klasser.

Named & optional parameters: 
i club metoden StreakSet() bruger vi optional parameter som sikkrer klassen når den bliver instantieret.

Exception:
File not found exception i file reader.

Attributes and DataValidation:
Vi bruger attributes i hvores klasser og når vi indlæser CSV filer caster vi til den riktige datatype.

Arrays / Collections:
Data håndtering med Arrays og Lists. En liga indeholder en en Liste af clubber og en runde indeholder en liste af kampe. I LongestTeamName bruges en array for at iterare igennem navne og finde det længste navn for dynamisk tabel.

Ranges:
GetRange() bliver brugt for at dele op superligaen i Upper og Lower League.

Operator overloads:
Vi kunde ha brugt dem istedet for Optional parameters for class constructers.

Ref/in/out:
Out kunder blive brugt i PrelimnaryFinish istedet for at opbevare variablerne i en liste som bliver returneret.