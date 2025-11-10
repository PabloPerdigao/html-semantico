# HTML Semântico - Dominando a semântica das tags

O projeto **Portifólio** tem como objetivo demonstrar o conhecimento prático e teórico sobre as tags semânticas do HTML. 

Onde cada tag utilizada é explicada (no arquivo index.html com comentários e aqui no  README.md) o seu propósito da tag, por que foi escolhida para aquele trecho e como isso ajuda na acessibilidade/SEO/manutenção do código.

## 🚀 Visualização do Projeto

Você pode acessar a versão final do projeto (publicada com GitHub Pages) no link abaixo:

**[Clique aqui para acessar o portifólio](https://pabloperdigao.github.io/html-semantico/)**

![Prévia do Portfólio](./assets/img/preview-portifolio.png/)

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** A estrutura da página foi construída seguindo as melhores práticas de semântica.
* **CSS3:** Para estilização, utilizando Flexbox, Variáveis CSS e fontes customizadas (`@font-face`).
* **Google Fonts:** Para a tipografia do projeto.

---

 ## 📚 Estrutura HTML Semântca

Esta tabela contém as principais escolhas estruturais e o porquê de cada tag:

| Tag | Função | Justificativa de Uso |
| :--- | :--- | :--- |
| `<header>` | Cabeçalho da página. | Agrupa os elementos de topo, como o logotipo (`<img>`) e a navegação principal (`<nav>`) |
| `<nav>` | Seção de navegação. | Contém a lista `<ul>` de links principais do site (Início, Sobre, Contato) |
| `<main>` | Conteúdo principal | Envolve *todo* o conteúdo único da página, separando-o do `<header>` e `<footer>` |
| `<section>`| Seção temática | Usado 3x para agrupar logicamente os blocos de "Sobre", "Projetos" e "Contato" |
| `<article>` | Conteúdo independente. | Usado para cada projeto ("Finance Pro", "Star UP"), pois são itens que fariam sentido sozinhos em um feed |
| `<aside>` | Conteúdo agrupado | Contém "Habilidades & Tecnologias", um conteúdo relacionado aos projetos |
| `<footer>` | Rodapé da página | Contém informações secundárias, como copyright, redes sociais e informações de contato (`<address>`) |


### Tags de Conteúdo Específico

| Tag | Propósito (Função) | Justificativa de Uso (Contexto) |
| :--- | :--- | :--- |
| `<h1>`-`<h4>`| Títulos | Usados em ordem sequencial (H1: Nome, H2: Seções, H3: Títulos de Projetos). |
| `<figure>` | Mídia com legenda | Agrupa a foto de perfil (`<img>`) e seu `<figcaption>`, criando uma ligação semântica entre eles. |
| `<figcaption>`| Legenda do `<figure>` | Usado para fornecer a legenda "Foto de perfil" para a imagem (`<img>`) dentro do `<figure>` |
| `<table>` | Tabela de dados. | Usada para listar os "Detalhes dos Projetos" de forma estruturada, com `<thead>`, `<tbody>` e `<tfoot>` |
| `<details>` | Widget interativo. | Usado no `<aside>` para criar um menu "sanfona" (accordion) que esconde/mostra as listas de habilidades. |
| `<summary>` | Título do `<details>` | Usado como o título clicável (ex: "Habilidades", "Techs") para o widget `<details>` |
| `<form>` | Formulário interativo | Usado na seção "Contato" para coletar dados do usuário. |
| `<fieldset>`| Agrupamento de campos. | Agrupa visual e semanticamente os campos do formulário de contato, com um `<legend>` descritivo |
| `<address>` | Informação de contato. | Fornece dados de contato do autor (email, telefone, localização) dentro do rodapé |

### Tags Inline

| Tag | Propósito (Função) | Justificativa de Uso (Contexto) |
| :--- | :--- | :--- |
| `<strong>` | Negrito | Usado para destacar o nome "Pablo Perdigão" no parágrafo de introdução |
| `<em>` | Itálico | Usado para enfatizar o cargo "desenvolvedor front-end júnior" |
| `<mark>` | Texto destacado | Usado como um "marca-texto" para destacar as tecnologias (HTML, CSS, etc.) no parágrafo de introdução. |
| `<time>` | Data ou hora | Usado para marcar semanticamente as datas dos projetos, com o atributo `datetime` para leitura de máquina. |
| `<abbr>` | Abreviação | Usado em "Jr" com o `title="Júnior"` para explicar a abreviação. |
| `<br>` | Quebra de linha. | Usado no parágrafo de introdução para forçar uma quebra de linha por razões estéticas |

---

## ♿ Acessibilidade & SEO

A semântica não é apenas organização; é o pilar para tornar a web acessível e otimizada.

* **Atributos `alt`:** Todas as tags `<img>` (logo, foto de perfil, ícones) possuem um atributo `alt` que descreve a imagem para leitores de tela.
* **Hierarquia de Títulos:** O uso correto de `<h1>` a `<h4>` permite que usuários de leitores de tela "pulem" para a seção de interesse.
* **Atributo `lang`:** Essencial para que o leitor de tela use a pronúncia correta de acordo com o idioma.
* **Tags de Formulário:** O uso de `<label for="id">` associado ao `input`, melhorando a acessibilidade para quem navega pelo teclado.

###  Atributos ARIA

Como bônus, utilizei os `aria-label` nos links de redes sociais no rodapé. Como eles contêm apenas um ícone (`<img>`), o `aria-label` fornece uma descrição (ex: "Link para o LinkedIn") para leitores de tela.

---

### 👨‍💻 Pablo Perdigão

 - **LinkedIn:** [linkedin.com/in/pabloperdigao](https://www.linkedin.com/in/pabloperdigao/)
- **GitHub:** [github.com/pabloperdigao](https://github.com/pabloperdigao)



