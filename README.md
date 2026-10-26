# LH Pet – Aplicação Web MVC (.NET)

Atividade de Codificação Back-end (SENAI): aplicação ASP.NET Core MVC para a clínica veterinária LH Pet, sem banco de dados por enquanto.

## Estrutura
- `LHPet/Models/Cliente.cs` e `Fornecedor.cs` – models
- `LHPet/Controllers/HomeController.cs` – cria 5 clientes e 5 fornecedores, monta as listas e envia para a view via `ViewBag`
- `LHPet/Views/Home/Index.cshtml` – template Bootstrap que exibe as listas

## Como executar
```
cd LHPet
dotnet run
```
Abra no navegador o link exibido no terminal (ex.: https://localhost:7072 ou http://localhost:5103).

Requer o SDK do .NET 8 (testado). Para .NET 6, troque `net8.0` por `net6.0` no arquivo `LHPet/LHPet.csproj`.

Aluno(a): _escreva seu nome aqui_
