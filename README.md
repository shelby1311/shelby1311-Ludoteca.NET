Ludoteca .NET

Projeto acadêmico: sistema de gerenciamento de empréstimos de jogos de tabuleiro para um clube universitário.
Aplicação em console desenvolvida em C# sobre o ecossistema .NET 9, com persistência dos dados em JSON.

Visão geral

O sistema Ludoteca .NET foi concebido para gerenciar o cadastro de jogos e membros, controlar empréstimos e devoluções, e gerar relatórios de uso da ludoteca. É uma aplicação de linha de comando (console) voltada a fins acadêmicos, estruturada conforme princípios de separação de responsabilidades.

Funcionalidades principais

Cadastro de jogos e de membros do clube.

Listagem de jogos com status (Disponível / Emprestado).

Fluxo de empréstimo e devolução de jogos.

Geração de relatórios e estatísticas de utilização.

Persistência dos dados em arquivo biblioteca.json para garantir recuperação entre execuções.

Arquitetura do projeto

O código foi organizado em camadas claras para facilitar manutenção e teste:

Modelos (Models) — entidades de domínio (jogo, membro, empréstimo, etc.).

Serviços (Services) — lógica de negócio (regras de empréstimo, validações, geração de relatórios).

Interface do Usuário (Console) — interação com o usuário via terminal.

Tecnologias

C# 13

.NET 9

System.Text.Json para serialização e persistência dos dados

Pré-requisitos

SDK do .NET 9 instalado. (Ex.: baixar em https://dotnet.microsoft.com)

Como executar (local)

Clone o repositório:

git clone URL_DO_SEU_REPOSITORIO_AQUI


Acesse a pasta do projeto (onde está o .csproj):

cd Ludoteca.NET/src/Ludoteca


Restaure dependências (recomendado):

dotnet restore


Execute a aplicação:

dotnet run


Observação: os dados são salvos/atualizados no arquivo biblioteca.json presente no diretório do projeto. Se o arquivo não existir, ele será criado automaticamente pela aplicação.

Estrutura de diretórios (exemplo)
Ludoteca.NET/
├─ src/
│  ├─ Ludoteca/         # projeto principal (console)
│  │  ├─ Models/
│  │  ├─ Services/
│  │  └─ Program.cs
│  └─ ...
└─ biblioteca.json

Autores
Nome	Matrícula
Gustavo Ramos	06009333
Nathan Salles	06009233
Cristiano Cordeiro	06010709
Andrey Campos	06009553

Observações finais

Este repositório tem objetivo acadêmico e demonstrativo. Para uso em produção, recomenda-se adicionar testes automatizados, tratamento de concorrência no acesso ao arquivo de dados, e migrar a persistência para um banco de dados adequado conforme requisitos de escalabilidade e integridade.
