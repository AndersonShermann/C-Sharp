# Projetos e Estudos C#

## Projeto 01 
### [API](https://github.com/AndersonShermann/C-Sharp/tree/main/MinhaAPI) e [Minimal API](https://github.com/AndersonShermann/C-Sharp/tree/main/MinhaMinimalAPI) com C# e Visual Studio

Este projeto é possuem duas API's, uma minimal e outra com controller, construídas usando C# no Visual Studio. O objetivo é demonstrar a implementação de métodos HTTP GET e manipulação de rotas.

[API](https://github.com/AndersonShermann/C-Sharp/tree/main/MinhaAPI)
[MinimalAPI](https://github.com/AndersonShermann/C-Sharp/tree/main/MinhaMinimalAPI)

#### Recursos

- Implementação do método HTTP GET
- Manipulação de rotas

#### Requisitos

- Visual Studio (ou qualquer ambiente de desenvolvimento C#)
- .NET Framework

#### Começando

1. Clone este repositório em sua máquina local.
2. Abra o arquivo de solução (`SimpleAPI.sln`) no Visual Studio.
3. Compile a solução.
4. Execute o projeto.
5. Acesse os endpoints da API usando o cliente HTTP de sua preferência.

#### Uso

A API fornece os seguintes endpoints:

- `/api/data` - Recupera dados da API.

## Exemplos

Para recuperar dados da API, você pode usar uma ferramenta como cURL ou Postman:

```bash
curl http://localhost:porta/api/data
