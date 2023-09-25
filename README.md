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
Console.WriteLine($"Hello, {name} !");
```

For loopid
```
for(int i=0; i <  5; i++){}
Deklareerime muutuja ning tingimuse
```
```
i = 0
for(i=0; i <  5; i++){}
Saab ka ilma muutuja deklareerimiseta
```
Random rand = new Random();
To generate a random number
```
