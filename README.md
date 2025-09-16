🎲 Projeto Ludoteca .NET
Este é um projeto acadêmico desenvolvido para a disciplina de [Nome da Disciplina], com o objetivo de criar um sistema de gerenciamento de empréstimos de jogos de tabuleiro para um clube universitário. A aplicação é executada via console e foi construída utilizando C# e o ecossistema .NET 9.

📖 Sobre o Projeto
O sistema "Ludoteca .NET" permite realizar as seguintes operações:

Cadastrar novos jogos e membros do clube.

Listar todos os jogos disponíveis e seus status (Disponível ou Emprestado).

Gerenciar o fluxo de empréstimo e devolução de jogos.

Gerar relatórios com estatísticas de uso da ludoteca.

Persistir todos os dados em um arquivo biblioteca.json, garantindo que as informações não sejam perdidas ao fechar o programa.

O projeto foi estruturado seguindo os princípios de Separação de Responsabilidades, dividindo o código em camadas de Modelos (dados), Serviços (lógica de negócio) e Interface do Usuário (console).

💻 Tecnologias Utilizadas
C# 13

.NET 9

System.Text.Json para serialização e persistência de dados.

👨‍💻 Autores
Nome	Matrícula
Gustavo Ramos	06009333
Nathan Salles	06009233
Cristiano Cordeiro	06010709
Andrey Campos	06009553

Exportar para as Planilhas
🚀 Como Executar o Projeto
Para executar este projeto em sua máquina local, siga os passos abaixo.

Pré-requisitos
É necessário ter o SDK do .NET 9 instalado. Você pode baixá-lo em dotnet.microsoft.com.

Passo a Passo
Clone o repositório para sua máquina:

Bash

git clone URL_DO_SEU_REPOSITORIO_AQUI
Navegue até a pasta do projeto onde o arquivo .csproj está localizado:

Bash

cd Ludoteca.NET/src/Ludoteca
Restaure as dependências do projeto (uma boa prática):

Bash

dotnet restore
Execute a aplicação:

Bash

dotnet run
