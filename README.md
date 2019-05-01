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
3. i `Main()` på program.cs laves en rutine som prompt'er brugeren for
 Navn
 Alder
4. Disse værdier bruges til at lave en ny instans af en person
5. Udskriv personen på konsollen
```c#
Console.WriteLine(_person);
```
6. Husk af overskrive ToString på person klasse for at dette virker

### Hændelse
7. Opret en hændelse i `person.cs` som skal signalerer, at personen er for gammel
```c#
public event EventHandler ForGammel;
```
8. Udløs hændelsen hvis man forsøger at tildele en værdi i alder som er over 125 år.
