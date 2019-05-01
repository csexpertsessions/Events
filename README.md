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
3. i `Main()` på program.cs laves en rutine som prompt'er brugeren for Navn og Alder
4. Disse værdier bruges til at lave en ny instans af en person
5. Udskriv personen på konsolen
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
9. I `Main()` efter personen er instansieret, så tilknyt en metode til hændelsen
10. Metoden skal udskrive teksten 'En person kan ikke være over 125 år' i konsolen.

### Hændelse med parameter
11. Vi ønsker nu at hændelsen `ForGammel` skal kunne overfører en værdi som indeholder den ny alder til konsumenten
11. Lav en ny klasse som skal representere EventArgs for hændelsen ForGammel
```c#
public class ForGammelEventArgs: EventArgs
{
  public int Alder { get; set; }
}
```

