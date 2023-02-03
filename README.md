<h1 align="center">
  <img alt="Alurabooks" src="https://raw.githubusercontent.com/nayarawatanuki/html-css-responsibility__alurabook/main/img/readme/cover.png#vitrinedev"/>
</h1>

### Índice

* [:pencil: Descrição do Projeto](#pencil-descrição-do-projeto)
* [:white_circle: Status do Projeto](#white_circle-status-do-projeto)
* [:hammer: Funcionalidades e Demonstração da Aplicação](#hammer-funcionalidades-e-demonstração-da-aplicação)
* [:open_file_folder: Acesso ao Projeto](#open_file_folder-acesso-ao-projeto)
* [:rocket: Abrir e rodar o projeto](#rocket-abrir-e-rodar-o-projeto)
* [:keyboard: Tecnologias utilizadas](#keyboard-tecnologias-utilizadas)
* [:woman_technologist: Desenvolvedor(a) do Projeto](#woman_technologist-desenvolvedora-do-projeto)

</br>

## :pencil: Descrição do Projeto
O projeto **[Alurabooks](https://nayarawatanuki.github.io/html-css-responsibility__alurabook/)**, é uma proposta de página web para uma loja de livros. 
Esse projeto contém o objetivo de aprender a fazer uma página totalmente responsiva, suportando todas as resoluções e dispositivos.

</br>Desenvolvido para o curso de **HTML E CSS: RESPONSIVIDADE COM MOBILE-FIRST** da plataforma [Alura](https://www.alura.com.br/).

</br>

## :white_circle: Status do Projeto
> Projeto concluído :white_check_mark:

</br>

## :hammer: Funcionalidades e Demonstração da Aplicação
A construção/estrutura da página foi pensada e estruturada primeiramente na resolução mobile. Com decorrer do projeto, foi adaptado para telas maiores. 
Pois o objetivo é conseguir visualizar e utilizar a página em qualquer resolução ou dispositivo.
</br>Segue a estruturação básica do projeto e as principais configurações utilizadas:
</br></br>
**HTML:**
- Estrutura básica padrão do HTML5;
- Body: 
  - `<header>Menu e links</header>`
  - `<section class="banner">`
  - `<section class="carousel">` para o carrossel, utilizamos a API [Swiper](https://swiperjs.com/)
  - `<section class="card">`
  - `<section class="topics">`
  - `<section class="contact">`
  - `<section class="footer">`

</br>

**Estilização CSS:**</br>
Foi aprendido e utilizado: 
- Importar arquivos para o arquivo principal da página, através do `@import;`. Afim de evitar muitas linhas de tag `<link>` nos arquivos `html`;
- Uso de variáveis (dessa vez foi preciso usar cores em `gradient`);
- Manipular o comportamento do `Menu`, realizando uma interação com o clique do usuário apenas com HTML e CSS para abrir o menu hambúrguer. 
Para isso, foi utilizado em HTML: um elemento input do tipo checkbox `<input type="checkbox">` (que constrói uma caixa quadrada que são marcadas através do clique) 
com auxílio do elemento `<label>`. E utlizado em CSS: o atributo de condição `~`, no caso: `.container__button:checked ~ .menu-list`. 
E também foi feito o uso dos atributos de posicionamento `position`;
- Essencial o uso do `@media screen and (min-width: XXXpx)`, utilizamos para resoluções de 1024px (iPad) e 1728px (desktop). 
Esse rescurso possibilitou adequar cada um dos elementos da página para as devidas resoluções. Com isso foi muito utilizado a configuração de `display: none` e `display: block`.
E com a repetição do recurso em muitos momentos, foi aprendido a atribuir a configuração apenas 1x para todas as classes necessárias de cada resolução.

</br>

Isso tudo foi realizado com as seguintes aulas: 
- Figma: 
  - Captar informações como as cores dos elementos no Figma;
  - Baixar imagens no Figma;

- Aplicando a metodologia mobile-first;
- Criando Header, Flexbox e @import
- Desenvolver um menu hambúrguer interativo com HTML e CSS;
- Criar sections;
- Editar input e seu placeholder;
- Integrando o Carrossel com SwiperJS;
- Criar listas;

</br>

- Criar variáveis CSS;
- Associar arquivos CSS através do @import;
- Transformar elementos em flex-containers e flex-items com FlexBox;
- Position relative e absolute;
- Importar e usar fontes do google fonts;
- Reforçar o aprendizado de flexbox;
- Reutilizar elementos e estilos;
- Media Queries;
- Aplicar estilos com media queries diferentes;
- Aplicar elementos na tela de acordo com o tamanho do dispositivo;
- Aplicar diferentes estilos para diferentes tamanhos de tela;
- Retirar elementos da tela;
- Usar estilos diferentes no mesmo elemento com pseudo-classes.

</br>

## :open_file_folder: Acesso ao projeto
Você pode acessar o [código fonte do projeto](https://github.com/nayarawatanuki/html-css-responsibility__alurabook) ou 
[baixá-lo](https://github.com/nayarawatanuki/html-css-responsibility__alurabook/archive/refs/heads/main.zip).

Caso obte por baixá-lo: 
Após baixar o projeto, você pode abrir com o VS Code. Para isso, abra o explorer (primeiro icone no menu) clique em:
- Abir pasta ou Open folder
- Procure o local onde o projeto está localizado e o selecione (Caso o projeto seja baixado em zip, é necessário extraí-lo antes de procurá-lo)
- Por fim, clique em Selecionar pasta ou Select Folder

</br>

## :rocket: Abrir e rodar o projeto
Caso tenha interesse em visualizar o que foi realizado: [AluraBooks](https://nayarawatanuki.github.io/html-css-responsibility__alurabook/) 

Ou, caso prefira baixá-lo clicando [aqui](https://github.com/nayarawatanuki/html-css-responsibility__alurabook/archive/refs/heads/main.zip).

> Após baixar o projeto, abra a pasta do projeto (Caso o projeto seja baixado em zip, é necessário extraí-lo antes de abrir), então clique no:
> - Aqruivo **``index.html``**
> - O projeto abrirá em seu navegador padrão (aconselho configurar para o Chrome, se possível)

</br>

## :keyboard: Tecnologias utilizadas
![HTML + CSS](https://raw.githubusercontent.com/nayarawatanuki/html-css-responsiveness__alurabook/main/img/readme/html-css.PNG)</br>

</br>

## :woman_technologist: Desenvolvedor(a) do Projeto
:star: [Nayara Watanuki](https://github.com/nayarawatanuki)
