# Protótipo de Rebranding de Website

## 📄 Sobre o Projeto

Este repositório contém o protótipo front-end para o projeto de rebranding de um site. O objetivo é modernizar a identidade visual da empresa, criando uma interface mais elegante, profissional e amigável, que reflita sua posição no mercado global.

Este protótipo foi construído com **HTML5, CSS3 e JavaScript puro** e servirá como base visual e guia de estilo para o desenvolvimento da aplicação final em **React.js**.

## ✨ Funcionalidades do Protótipo

- **Design Moderno e Responsivo:** O layout se adapta a diferentes tamanhos de tela, de desktops a dispositivos móveis.
- **Sistema de Cores Definido:** Uma paleta de cores coesa e acessível foi criada para fortalecer a nova identidade da marca.
- **Componentes Reais:** Simula seções importantes do site como hero, sobre nós, listagem de produtos e formulário de contato.
- **Seletor de Idioma Funcional:** Inclui um seletor (Português/Inglês) para demonstrar a capacidade de internacionalização do site, crucial para o negócio da empresa.

---

## 🎨 Paleta de Cores (Guia de Estilo)

A paleta de cores foi cuidadosamente escolhida para transmitir confiança, inovação e clareza. A padronização está documentada diretamente no arquivo `style.css` usando as variáveis CSS abaixo para fácil manutenção.

### Variáveis CSS

O seguinte bloco de código está definido no seletor `:root` do arquivo `style.css` e deve ser usado para garantir a consistência em todo o projeto.

```css
:root {
    --color-primary: #0A3E85;
    --color-accent: #FF6B00;
    --color-text: #333333;
    --color-text-light: #555555;
    --color-background: #F0F2F5;
    --color-surface: #FFFFFF;
    --color-border: #DDDDDD;
    --font-primary: 'Roboto', sans-serif;
    --font-headings: 'Poppins', sans-serif;
}
```

### Guia de Uso

| Categoria                | Cor                                                               | Hex Code    | Uso Principal                                                              |
| ------------------------ | ----------------------------------------------------------------- | ----------- | -------------------------------------------------------------------------- |
| **Primária (Primary)** | <img src="https://via.placeholder.com/15/0A3E85/0A3E85.png"> Azul Principal | `#0A3E85`   | Links, ícones, títulos principais e elementos de interação da marca.       |
| **Destaque (Accent)** | <img src="https://via.placeholder.com/15/FF6B00/FF6B00.png"> Laranja Vibrante | `#FF6B00`   | Botões de ação (CTAs), alertas e elementos que exigem atenção imediata.    |
| **Texto (Text)** | <img src="https://via.placeholder.com/15/333333/333333.png"> Cinza Escuro    | `#333333`   | Corpo de texto e parágrafos, garantindo alta legibilidade.                 |
| **Fundo (Background)** | <img src="https://via.placeholder.com/15/F0F2F5/F0F2F5.png"> Cinza Suave     | `#F0F2F5`   | Fundo principal da página (`body`), criando contraste suave com as seções. |
| **Superfície (Surface)** | <img src="https://via.placeholder.com/15/FFFFFF/FFFFFF.png"> Branco           | `#FFFFFF`   | Fundos de cards, headers e outras superfícies de conteúdo.                 |

---

## 🚀 Como Visualizar

Para visualizar este protótipo, você não precisa de nenhuma ferramenta de build ou servidor local. Basta seguir os passos:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/agr3w/amostra_de_cores_template.git
    ```

2.  **Navegue até a pasta do projeto:**
    ```bash
    cd amostra_de_cores_template
    ```

3.  **Abra o arquivo `index.html`:**
    -   Abra o arquivo `index.html` diretamente no seu navegador de preferência (Google Chrome, Firefox, etc.).

E pronto! Você poderá navegar pela página e interagir com o seletor de idiomas.

## ➡️ Próximos Passos (Versão em React.js)

Este protótipo serve como um "contrato visual". O próximo passo é migrar esta estrutura para uma aplicação React, onde iremos:

-   **Componentizar a UI:** Quebrar a página em componentes reutilizáveis (Header, Card, Button, etc.).
-   **Gerenciar Estado:** Utilizar o state do React para funcionalidades como o seletor de idioma (com uma biblioteca como `i18next`).
-   **Criar Rotas:** Usar `react-router-dom` para navegação entre páginas (ex: página de detalhes do produto).
-   **Estilização em Componentes:** Adotar uma estratégia de estilização como Styled Components ou CSS Modules.

---
