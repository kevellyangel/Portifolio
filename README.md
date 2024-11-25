Meu Portfólio Pessoal
Bem-vindo ao meu portfólio! Este repositório contém o código fonte do meu portfólio pessoal, desenvolvido para destacar minhas habilidades, experiências e projetos na área de Jogos Digitais e Análise e Desenvolvimento de Sistemas. O portfólio é projetado para ser uma apresentação pessoal simples e visualmente agradável, acessível e responsiva.

Tecnologias Usadas
React - Biblioteca JavaScript para construção da interface do usuário.
CSS - Utilizado para estilização do layout e componentes.
GitHub Pages (ou outro serviço de hospedagem) - Para hospedar o site online.
JavaScript - Para a funcionalidade dinâmica e interação.
HTML - Estrutura básica do conteúdo.


Funcionalidades
Página Inicial: Uma introdução a quem sou, minhas habilidades e experiência.
Lista de Projetos: Exibição de cards com meus principais projetos de programação, com links para os repositórios no GitHub.
Informações de Contato: Formas de entrar em contato comigo por email e redes sociais.
Responsividade: O layout se ajusta bem para diferentes tamanhos de tela, incluindo dispositivos móveis.

Como Rodar o Projeto Localmente
Para rodar este projeto localmente na sua máquina, siga os passos abaixo:

1.download
por alguns motivos tive que colocar o arquivo rar não se preocupe é totalmente seguro.
faça o download do rar e extrai para onde deseja que fique a pasta.

2. Abra com VS code
depois disso abra com vs code,pode ser pelo cmd ou indo pela propria pasta.

3. Instale as dependências
Possivelmente os pacotes ja estão instalados mas se der erro,tente instalar esses pacotes:
npm i

Ou se estiver usando yarn, use:
yarn install

5. Execute o projeto localmente
Para iniciar o servidor de desenvolvimento e ver a aplicação localmente, use o comando:

npm run dev
O projeto será exibido no seu navegador em [http://localhost:5173].

Estrutura do Projeto
/src
  /assets               # Imagens utilizadas no projeto (ex: Pokedex.jpg, TodoList.jpg)
  /components           # Componentes React reutilizáveis
    Footer.jsx          # Componente de rodapé
    Navbar.jsx          # Componente de barra de navegação
    ProjectCard.jsx     # Componente de cartão de projeto
  /pages                # Páginas da aplicação
    ContactPage.jsx     # Página de contato
    ErrorPage.jsx       # Página de erro
    HomePage.jsx        # Página inicial
    PortfolioPage.jsx   # Página do portfólio
  App.js                # Componente principal do aplicativo
  App.css               # Estilos globais para o aplicativo
  index.js              # Arquivo de entrada do React
  index.css             # Estilos globais
/public
  index.html            # Arquivo HTML principal
.gitignore              # Arquivo para excluir arquivos indesejados do Git
.eslint.config.js       # Configuração do ESLint
package.json            # Gerenciamento de dependências e scripts
package-lock.json       # Bloqueio das versões das dependências
README.md


Como Contribuir
Faça um fork deste repositório.
Crie uma nova branch para suas modificações!
