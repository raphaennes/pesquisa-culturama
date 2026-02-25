# Pesquisa Culturama 📝

Este projeto é uma aplicação web de página única (Single Page) que utiliza **HTML5** e **CSS3** para criar um formulário de pesquisa semântico, acessível e visualmente moderno.

## 🚀 Integração HTML & CSS

O projeto foi construído focando na separação de responsabilidades:
- **HTML5:** Define a estrutura e o significado dos dados (inputs de texto, seletores, botões de rádio e áreas de texto).
- **CSS3:** Responsável por todo o layout, desde o reset de margens (`box-sizing`) até a responsividade e identidade visual.

## 🛠️ Detalhes Técnicos

### Estrutura (HTML)
- Uso de `main` para centralizar o conteúdo principal.
- Agrupamento lógico de campos usando `fieldset` e `legend`.
- Diversidade de tipos de entrada: `text`, `select`, `textarea`, `checkbox`, `radio` e `color`.

### Estilização (CSS)
- **Tipografia:** Integração com Google Fonts (*Fjalla One* e *Work Sans*).
- **Layout:** Centralização automática com `margin: 0 auto` e largura máxima de `700px`.
- **Componentes:** - Botões personalizados com estados de `:hover`.
  - Campos de formulário com bordas arredondadas e espaçamento interno (`padding`).
  - Reset global para garantir consistência entre diferentes navegadores.

## 📂 Arquivos do Repositório

| Arquivo | Descrição |
| :--- | :--- |
| `index.html` | Estrutura semântica do formulário de pesquisa. |
| `style.css` | Folha de estilo com as regras de design e responsividade. |

## 🎨 Design e Cores

- **Fundo do Body:** `#f9f9f9` (Cinza claro para conforto visual)
- **Botão Sucesso:** `#4CAF50` (Verde para o `submit`)
- **Botão Perigo:** `#f44336` (Vermelho para o `reset`)

## 🔧 Como Testar Localmente

1. Clone o repositório:
   ```bash
   git clone [https://github.com/raphaennes/pesquisa-culturama.git](https://github.com/raphaennes/pesquisa-culturama.git)
