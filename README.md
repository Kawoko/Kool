# All about C# Coding
### Konsool ja selle kasutamine

Kasutatud, et kirjutada informatsiooni Konsooli.
``` 
Console.WriteLine("Enter your name: ");
```

Kasutatud, et oodata kasutajalt sisendit, kasutatakse korraga, et ka tavaliselt salvestada sisend muutujasse.
```
Console.ReadLine();
```

```
string name = Console.ReadLine();
```
-

Oletame, et saime kasutajalt sisendiks nime ning soovime selle välja kirjutada konsooli.
```
Console.WriteLine("Enter your name: ");
string name = Console.ReadLine();
Console.WriteLine("Hello " + name + "!");
```
