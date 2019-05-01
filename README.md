# Events

1. Lav en ny Console App (.NET Framework)
2. Indsæt en klasse som skal representerer en person
```c#
public class person
{
  public string Navn { get; set; }
  public int Alder { get; set; }
}
```
3. Indsæt en `foreach` som gennemløber værdierne og udskriver dem med en `Console.WriteLine`
4. Kør koden og se svar
5. Indsæt en `Array.Sort(tal);` før `foreach`
6. Kør igen og konstater, at værdierne nu er sorteret.

7. Opret en ny klasse 
```c#
public class Person
{
   public string Navn { get; set; }
   public int alder { get; set; }
}
```
8. Lav nu et array af denne klasse og instansier 3 personer i listen
9. Udskriv listen med en `foreach` sætning
10. Kan man sorterer listen med en `Array.Sort` før `foreach`
11. Hvorfor ikke?
12. Implementer `IComparable` interface på klassen person.
13. Kan man nu sorterer?
