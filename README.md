# Events

1. Lav en ny Console App (.NET Framework)
2. Opret en klasse som skal representerer en person i sin egen fil `person.cs`
```c#
public class person
{
  public string Navn { get; set; }
  public int Alder { get; set; }
}
```
3. i `Main()` på program.cs laves en rutine som propter brugeren for
 Navn
 Alder
4. Disse værdier bruges til at lave en ny instans af en person
5. Udskriv personen i en konsollen
```c#
Console.WriteLine(_person);
```
6. Husk af overskrive ToString på person klasse for at dette virker
