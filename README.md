# Template Admin
Template Front-end para Painéis de administração e dashboards.
## Recursos utilizados
HTML, CSS e JS com framework BOOTSTRAP 5, documentação e exemplos de componentes em https://getbootstrap.com/docs/5.0/getting-started/introduction/

## Arquivos e estrutura
- Pasta assets  - contém arquivos de uso geral de todo o site como o CSS, JS e imagens de logotipo e backgrounds.  As imagens de conteúdo que forem carregadas por banco de dados podem usar qualquer caminho
- estrutura.html  - toda página deverá ter essa estrutura, o comentário indica onde os conteúdos serão inseridos
- login.html  - Página com a estrutura padrão e o componente específico de login
- dashboard.html - Página de exemplo utilizando a estrutura padrão, a navbar e outros componentes.
- navbar.html - Página de exemplo mostrando apenas o componente navbar.

## Classes CSS

Além das classes do Bootstrap 5, as classes abaixo são utilizadas por várias páginas e componentes:

- .bg   - Background de fundo com imagem das páginas (substituir imagem pela sua preferência)
- .tela-cheia   - aplicado em elementos que deverão ocupar toda a tela

Classes de animações:  .fadeInDown, .fadeIn, .fadeIn.primeiro, .fadeIn.segundo, .fadeIn.terceiro, .fadeIn.quarto
O início do arquivo assets/styles.css contém um índice para as partes do CSS como tags, cores, tipografia etc
