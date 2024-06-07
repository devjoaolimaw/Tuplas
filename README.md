# Tuplas

Este código em C# demonstra o uso de tuplas para armazenar uma coleção heterogênea de dados, no caso, um ID (inteiro), um nome (string), um sobrenome (string) e uma altura (decimal).

```csharp
(int, string, string, decimal) tupla = (1, "Joao", "Lima", 1.80M);
```

Neste trecho, uma tupla é definida e inicializada com valores. Os tipos dos elementos da tupla são especificados entre parênteses, e os valores são atribuídos entre parênteses também.

```csharp
Console.WriteLine($"Id: {tupla.Item1}");
Console.WriteLine($"Nome: {tupla.Item2}");
Console.WriteLine($"Sobrenome: {tupla.Item3}");
Console.WriteLine($"Altura: {tupla.Item4}");
```

Estes comandos imprimem os valores dos elementos da tupla. `Item1`, `Item2`, `Item3` e `Item4` são propriedades predefinidas para acessar os elementos da tupla.

Os comentários abaixo mostram outras formas de criar e acessar tuplas em C#. O código está comentado para indicar que essas linhas estão desativadas e não serão executadas. As duas formas alternativas apresentadas são:

1. Utilizando a classe `ValueTuple`:
```csharp
ValueTuple<int, string, string, decimal> outroExemploTupla = (1, "Joao", "Lima", 1.80M);
```

2. Utilizando o método `Tuple.Create`:
```csharp
var outroExemploTuplaCreate = Tuple.Create(1, "Joao", "Lima", 1.80M);
```

Ambas as formas criam uma tupla semelhante à primeira, mas com algumas diferenças na forma como são declaradas e acessadas.
