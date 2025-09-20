# Guia de Estudos de Programação - HTML & CSS

Este projeto é um **guia de estudos fictício** sobre programação, criado usando HTML e CSS. Ele apresenta conteúdos de Back-End, Front-End e ferramentas de design como Figma, oferecendo uma experiência visual organizada e responsiva.

---

## 🛠 Estrutura do Projeto

- **index.html**  
  Contém a estrutura da página, incluindo:
  - Navbar com título, descrição e links de navegação.
  - Container principal com artigos (`article`) para cada guia.
  - Barra lateral (`aside`) com busca, outros guias e tags.
  - Seção de contato e rodapé (`footer`).

- **css/style.css**  
  Define o estilo do guia:
  - Background com imagem gradiente.  
  - Layout flexível (`Flexbox`) para o container principal e sidebar.  
  - Estilização de títulos, textos, links e imagens.  
  - Bordas arredondadas e cores contrastantes para destaque.  
  - Responsividade para telas pequenas usando `@media queries`.

- **img/**  
  Pasta contendo imagens ilustrativas para cada guia.

---

## 🎨 Design e Layout

- **Navbar**: título do guia, descrição e links de navegação (`Home`, `Guias`, `Contato`).  
- **Container principal**:
  - **Posts (articles)**: cada artigo contém uma imagem, título, descrição, autor e link "Ler mais".  
- **Sidebar**:
  - **Busca**: campo de pesquisa com botão.  
  - **Outros guias**: lista de links de estudo adicionais.  
  - **Tags**: links com categorias de estudo destacadas em azul.  
- **Rodapé**: informações gerais e copyright.

- **Estilo visual**:
  - Tipografia com fonte **Georgia**.  
  - Texto branco sobre fundo escuro com imagem gradiente.  
  - Layout organizado com Flexbox, garantindo espaçamento e alinhamento.  
  - Uso de bordas arredondadas e cores de destaque (#54b0ee) em links, tags e botões.

---

## 📱 Responsividade

- Para telas menores que 450px:
  - Container principal e sidebar se reorganizam em múltiplas linhas (`flex-wrap: wrap`).  
  - A página mantém legibilidade e organização mesmo em dispositivos móveis.

---

## ⚙️ Funcionalidades

- Navegação clara entre artigos e seções do site.  
- Barra lateral com busca e links úteis.  
- Tags interativas para filtrar ou destacar categorias de estudo.  
- Layout responsivo que se adapta a diferentes tamanhos de tela.  

---

## 💡 Possíveis melhorias

- Adicionar **JavaScript** para funcionalidade de busca e filtragem de guias.  
- Implementar **links reais** para conteúdos completos.  
- Incluir animações ou hover effects em cards e links.  
- Adicionar páginas internas para cada guia detalhado.

---

## 🔗 Referências

- [Flexbox - MDN](https://developer.mozilla.org/pt-BR/docs/Learn/CSS/CSS_layout/Flexbox)  
- [Imagens gratuitas - Freepik](https://www.freepik.com/)  
- Boas práticas de **UI/UX** para guias de estudo online.
