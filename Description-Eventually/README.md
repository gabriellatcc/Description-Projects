## Índice 🧭

- [Descrição](#descrição)
- [Documentação](#documentação)
- [Código Fonte](#atalho-para-o-código-fonte-do-projeto)
- [Como Executar o Projeto](#como-executar-o-projeto)
  - [Pré-requisitos](#pré-requisitos)
  - [Passo a Passo](#passo-a-passo)
- [Telas e Funcionalidades](#telas-e-funcionalidades-do-aplicativo)
- [Curiosidades de Desenvolvimento](#curiosidades-de-desenvolvimento-)

## Descrição

O projeto tem como objetivo principal ser uma plataforma centralizada para a criação, gerenciamento e descoberta de eventos. A plataforma é dirigida tanto para organizadores que desejam divulgar suas iniciativas, sejam elas corporativas, culturais, sociais ou educacionais, quanto para o público geral em busca de atividades e experiências que correspondam aos seus interesses. As principais funcionalidades do sistema incluem autenticação de usuários, um módulo completo para a criação de eventos (com detalhes como formato, capacidade, localização, data e tags temáticas), e um sistema de perfil de usuário com gerenciamento de preferências. A escolha do nome "Eventually" foi pensada a partir de um jogo de palavras com o termo em inglês: ele contém "Event" (evento), o foco do sistema, e o advérbio "eventually" (eventualmente) sugere que, com o tempo, o usuário encontrará o evento perfeito ou que a iniciativa planejada de fato acontecerá. A proposta é criar um ecossistema que sirva como ponte entre quem cria uma oportunidade (o organizador) e quem busca uma experiência (o participante), promovendo a interação social, o aprendizado e o lazer de forma organizada e acessível.

## Documentação: [Clique para ler](https://github.com/user-attachments/files/21191931/documentacaoFinalAcelera.docx)

## Atalho para o código fonte do projeto: [Clique para ver](https://github.com/gabriellatcc/Eventually)

## Como Executar o Projeto

Este projeto é simples e não requer nenhuma configuração de banco de dados ou dependências complexas. Siga os passos abaixo para executá-lo em sua máquina.

### Pré-requisitos

Antes de começar, garanta que você tenha instalado:

- **[Git](https://git-scm.com/)**
- Uma **IDE** de sua preferência (Ex: [VS Code](https://code.visualstudio.com/), [IntelliJ IDEA](https://www.jetbrains.com/idea/), [Eclipse](https://www.eclipse.org/))
- **[JDK](https://www.oracle.com/br/java/technologies/downloads/)** (23)

### Passo a Passo

1.  **Clone o Repositório**
    Abra o seu terminal (Git Bash, PowerShell, etc.), navegue até a pasta onde deseja salvar o projeto e execute o comando abaixo:

    ```bash
    git clone https://github.com/gabriellatcc/Eventually
    ```

    Isso criará uma nova pasta com todos os arquivos do projeto.

2.  **Abra o Projeto na IDE**
    Inicie sua IDE e utilize a opção para abrir um projeto existente. Geralmente o caminho é **File > Open** (ou **Arquivo > Abrir**) e então selecione a pasta que você acabou de clonar.

3.  **Execute o Código**
    Localize o arquivo principal que contém o método `main` (ponto de entrada do programa). Clique com o botão direito sobre ele e selecione a opção **Run** (ou **Executar**).

Pronto! O programa será compilado e iniciado.

## Telas e Funcionalidades do Aplicativo

### Tela de Login

![Tela de login do aplicativo](resources/TelaLogin.png)

### Tela Inicial

![Tela inicial com o dashboard principal de eventos](resources/TelaInicial.png)

### Funcionalidades da Tela Inicial

**Criar um Novo Evento**
![Janela para criação de um novo evento](resources/JanelaCriarEvento.png)

**Editar Filtros de Visualização**
![Janela para editar os filtros de eventos exibidos](resources/JanelaEditarFiltros.png)

**Visualizar Detalhes de um Evento**
_O sistema apresenta diferentes visualizações dependendo do seu status no evento._
![Visualização de um evento no qual o usuário não está inscrito](resources/VisualizacaoEventoNInscrito.png)
![Visualização de um evento logo após se inscrever](resources/VisualizacaoEventoPreInscrito.png)
![Visualização de um evento no qual o usuário já está inscrito](resources/VisualizacaoEventoInscrito.png)

**Visualizar Evento Próprio (Admin)**
_Permite ver comentários, lista de participantes e gerenciar o evento._
![Visualização do painel de gerenciamento de um evento próprio](resources/VisualizacaoEventoProprio.png)

**Compartilhar um Evento**
![Janela para compartilhar um evento em redes sociais](resources/JanelaCompartilharEvento.png)
![Exemplo de post gerado para o Twitter](resources/CompartilhamentoTwitter.jpg)

**Excluir um Evento**
![Janela de confirmação para exclusão de um evento](resources/JanelaExclusaoEvento.png)

### Tela "Meus Eventos"

_Para visualizar os eventos criados, inscritos e os já realizados._
![Tela de Meus Eventos](resources/TelaMeusEventos.png)

### Tela de Programação

_Permite ver os eventos criados e inscritos dos próximos 7 dias._
![Tela de Programação](resources/TelaProgramacao.png)

### Tela de Configurações

_Para edição de informações da conta do usuário._
![Tela de Configurações](resources/TelaConfiguracoes.png)

### Funcionalidades de Configuração

**Editar Preferências de Conteúdo**
![Janela para edição das preferências de conteúdo do usuário](resources/JanelaEdicaoPreferencias.png)

**Alterar Foto de Perfil**
![Janela para alterar a foto do usuário](resources/JanelaAlterarFoto.png)

**Alterar Dados Pessoais**
![Janela para alteração de dados da conta do usuário](resources/JanelaAlteracaoValorConta.png)

**Encerrar Sessão (Logout)**
![Janela de confirmação para encerrar a sessão](resources/JanelaEncerrarSessao.png)

### Tela de Registro

![Tela para registro de um novo usuário](resources/TelaRegistro.png)

# Curiosidades de Desenvolvimento 💡

Para garantir a qualidade e a organização do código, algumas práticas foram adotadas durante o desenvolvimento:

- **Histórico de Commits Organizado:** Todas as mensagens de commit seguem um padrão com prefixos (ex: `feat`, `fix`, `docs`) para facilitar a leitura e o entendimento do histórico de alterações.
- **Estrutura Orientada a Objetos (POO):** A arquitetura do projeto foi modelada com base nos princípios da Programação Orientada a Objetos, com as classes organizadas para ter responsabilidades claras e bem definidas.
- **Código Centralizado em Classes:** Toda a lógica e declaração de dados do projeto estão encapsuladas dentro de classes Java, evitando código disperso e fortalecendo a coesão.
