## 📄 README.md do Projeto Web

Olá! Este `README.md` serve como documentação para o seu projeto web, que foi desenvolvido com foco em design responsivo, acessibilidade e na aplicação de técnicas modernas de CSS.

---

### 🌟 Visão Geral do Projeto

Este projeto é uma **página web de notícias/conteúdo** com foco em **design limpo** e **experiência do usuário (UX)**. O desenvolvimento foi focado em garantir a completa **responsividade** do _layout_, adaptando-se perfeitamente a dispositivos móveis, _tablets_ e _desktops_.

#### Tecnologias Utilizadas

- **HTML5:** Estrutura semântica do conteúdo.
- **CSS3:** Estilização completa do _layout_, utilizando **variáveis CSS (`:root`)** e técnicas avançadas (como `flexbox`, `grid` e `media queries`).

---

### 🚀 Funcionalidades Principais (Sprint 3)

A Sprint 3 foi focada na finalização visual, interativa e técnica do projeto, introduzindo elementos de design avançados e validação de código.

#### 1. Melhorias Visuais e Interativas (CSS Avançado)

| Funcionalidade                  | Implementação no CSS                                                                                              | Benefício                                                   |
| :------------------------------ | :---------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------- |
| **Efeitos de Elevação (Hover)** | Uso de **`box-shadow`** e **`transform: translateY()`** nos cards (`.noticia-recente` e `.social-card`) e botões. | _Feedback_ visual claro ao usuário.                         |
| **Transições Suaves**           | Aplicação da propriedade **`transition: all 0.3s ease;`** em todos os estados de _hover_ e _focus_.               | Experiência de usuário fluida e profissional.               |
| **Gradiente**                   | Inclusão de um **`linear-gradient`** no cabeçalho (`header`).                                                     | Visual moderno e diferenciado.                              |
| **Animação de Carregamento**    | Aplicação da animação **`@keyframes fadeIn`** no conteúdo principal (`main`).                                     | Transição de entrada suave e elegante ao carregar a página. |
| **Acessibilidade (Focus)**      | Uso da pseudo-classe **`:focus`** com `box-shadow` nos campos de formulário.                                      | Melhora a acessibilidade e a navegação por teclado.         |
| **Tipografia em Destaque**      | Uso de **`:first-of-type`** para destacar o primeiro parágrafo de artigos.                                        | Guia o leitor e melhora a hierarquia visual.                |

#### 2. Responsividade e Navegação

- **Menu Dropdown (Desktop):** Implementação de uma estrutura de **submenu _dropdown_** com _hover_ (utilizando as classes `.has-dropdown` e `.dropdown-menu`).
- **Layout Mobile Refinado:**
  - Ajustes nos tamanhos de fonte e _padding_ do menu de navegação (`nav ul li a`) para garantir maior usabilidade e área de clique em telas menores.
  - Garantia de que elementos de formulário, como o campo de anexo (`input[type="file"]`), ocupem a largura total (`width: 100%`) para evitar truncamento de texto.
- **Tabela Responsiva:** Uso de **`overflow-x: auto`** no container de tabelas (`.tabela-responsiva`) para evitar a quebra do _layout_ em telas estreitas.

#### 3. Otimização e Padrões Técnicos

- **Código Validado:** O código HTML e CSS deve ser verificado e **validado** usando as ferramentas do W3C.
- **Otimização de Imagens:** Todas as imagens devem ser comprimidas e dimensionadas corretamente para garantir um carregamento rápido da página.
- **Uso de SVGs:** Implementação de **ícones SVG** para gráficos escaláveis.
- **Documentação:** Inclusão de comentários e tags semânticas para facilitar a manutenção e a leitura do código.

---

### 💻 Como Rodar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/Airam-D/Portal-de-Not-cias-Interativo
    ```
2.  **Abra os arquivos:**
    Navegue até o diretório do projeto e simplesmente abra o arquivo `index.html` (ou o arquivo principal) em seu navegador web.
3.  **Teste a Responsividade:**
    Use as ferramentas de desenvolvedor do navegador (F12) e o "Device Mode" (Modo Dispositivo) para simular diferentes tamanhos de tela e verificar a adaptabilidade do _layout_.

---

### 🎨 Estrutura de Estilos (Variáveis CSS)

O projeto utiliza **Variáveis CSS** no bloco `:root` para gerenciar o esquema de cores de forma eficiente:

| Variável CSS     | Valor     | Uso Principal                            |
| :--------------- | :-------- | :--------------------------------------- |
| `--verde-escuro` | `#004d40` | Cor primária de fundo, títulos e botões. |
| `--verde-claro`  | `#86ff64` | Cor de destaque, _hover_ e acentuação.   |
| `--preto-texto`  | `#1a1a1a` | Cor principal do texto.                  |
| `--branco-fundo` | `#ffffff` | Cor de fundo geral e elementos internos. |

---

### 🤝 Contato

Para dúvidas, sugestões de melhoria ou reportar _bugs_, entre em contacto através do formulário na página de Contato ou abra uma _Issue_ neste repositório.
