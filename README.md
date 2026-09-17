<div align="center">

# Messier — Protótipo Desktop

Aplicação acadêmica para gestão e acesso a jogos educacionais por escolas.

![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Windows Forms](https://img.shields.io/badge/Windows_Forms-0078D4?style=for-the-badge&logo=windows&logoColor=white)

</div>

## Sobre o projeto

Este repositório contém um protótipo desenvolvido em **C# com Windows Forms** para o Projeto Interdisciplinar do curso de **Análise e Desenvolvimento de Sistemas da FECAP**.

A proposta da plataforma Messier é permitir que escolas acessem um catálogo de jogos educacionais de acordo com o pacote contratado, além de oferecer uma área administrativa para consultar jogos, pacotes e relatórios de utilização.

> O projeto representa uma etapa acadêmica de prototipação. Alguns dados e comportamentos ainda são simulados e não devem ser utilizados em produção.

## Funcionalidades demonstradas

- autenticação com diferentes perfis de acesso;
- catálogo de jogos educacionais;
- menu administrativo;
- visualização de jogos e pacotes;
- área de ajuda;
- relatório demonstrativo de utilização por escola;
- navegação entre telas do sistema.

## Tecnologias

- C#;
- .NET 8;
- Windows Forms;
- Visual Studio;
- Git e GitHub.

## Estrutura principal

```text
PrototipoMessier/
├── CatalogoJogosForms
├── HelpForms
├── JogosForms
├── LoginForms
├── MenuForms
├── PacoteForms
├── RelEscolaForms
└── Program.cs
```

## Como executar

### Requisitos

- Windows;
- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0);
- Visual Studio 2022 com a carga de trabalho **Desenvolvimento para desktop com .NET**.

### Passos

```bash
git clone https://github.com/GuiRyuki/PrototipoMessier.git
cd PrototipoMessier
```

Abra o arquivo `PrototipoMessier.slnx` no Visual Studio, restaure as dependências e execute o projeto.

## Aprendizados

O desenvolvimento deste protótipo envolveu conceitos iniciais de:

- criação de interfaces desktop;
- programação orientada a eventos;
- organização de formulários;
- navegação entre telas;
- validação de dados;
- trabalho colaborativo em um projeto acadêmico.

## Próximos passos

- integrar um banco de dados;
- substituir os dados simulados por registros persistentes;
- implementar validação de pacote e IP autorizado;
- registrar acessos aos jogos;
- aprimorar os relatórios;
- adicionar testes e tratamento de erros.

## Autor

Desenvolvido por [Guilherme Ryuki Kawahira](https://github.com/GuiRyuki) como parte dos estudos em Análise e Desenvolvimento de Sistemas na FECAP.
