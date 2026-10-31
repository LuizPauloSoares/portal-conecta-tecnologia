# Portal Conecta Tecnologia

[🇧🇷 Português](README.md) | [🇺🇸 English](README.en.md)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen?style=for-the-badge)
![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-blue?style=for-the-badge)

Atividade didática de **refatoração de uma página HTML 4.01 para HTML5 semântico**, com CSS moderno em arquivo separado. O projeto mantém o conteúdo e o visual do portal original, trocando tabelas de layout, tags `<font>` e atributos obsoletos por tags semânticas, Grid e CSS.

## 📑 Índice

- [O que o código faz](#-o-que-o-código-faz)
- [Como funciona](#-como-funciona)
- [Tecnologias utilizadas](#-tecnologias-utilizadas)
- [Estrutura de arquivos](#-estrutura-de-arquivos)
- [Pré-requisitos](#-pré-requisitos)
- [Como clonar o projeto](#-como-clonar-o-projeto)
- [Instalação e configuração](#-instalação-e-configuração)
- [Exemplos de uso](#-exemplos-de-uso)
- [O que mudou: HTML 4.01 → HTML5](#-o-que-mudou-html-401--html5)
- [Status do projeto](#-status-do-projeto)
- [Roadmap](#-roadmap)
- [Licença](#-licença)
- [Autor e créditos](#-autor-e-créditos)
- [Contato](#-contato)

## 💡 O que o código faz

O **Portal Conecta Tecnologia** é uma página institucional fictícia sobre programação, inovação e formação profissional. Ela contém:

- Cabeçalho e menu de navegação com botões
- Seção de boas-vindas
- Últimas notícias
- Lista de cursos disponíveis
- Agenda de atividades (tabela)
- Formulário de contato (demonstrativo, não envia dados)
- Barra lateral com destaques, links úteis e enquete (demonstrativa)
- Rodapé com link "Voltar ao topo"

## ⚙️ Como funciona

- O `index.html` define a **estrutura e o significado** do conteúdo, usando tags semânticas.
- O `estilo.css` cuida de **toda a aparência**: cores, fontes, espaçamentos e layout.
- O layout de duas colunas (conteúdo principal + barra lateral) usa **CSS Grid** aplicado ao `body`.
- Em telas de até 768px, uma **media query** deixa tudo em uma coluna só.
- O formulário e a enquete são apenas demonstrativos e não enviam dados para nenhum servidor.

## 🛠️ Tecnologias utilizadas

- **HTML5** (tags semânticas: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`)
- **CSS3** (Grid, Flexbox, media queries, transições)

## 📁 Estrutura de arquivos

```
portal-conecta-tecnologia/
├── index.html        # Versão refatorada em HTML5
├── refatora.html     # Versão original em HTML 4.01 (para comparação)
├── estilo.css        # Estilos da versão HTML5
├── README.md         # Este arquivo (português)
└── README.en.md      # Versão em inglês
```

## 📋 Pré-requisitos

- Um navegador atual (Chrome, Firefox, Edge ou Safari)
- Opcional: [Git](https://git-scm.com/) para clonar o repositório
- Opcional: um editor de código, como o [VS Code](https://code.visualstudio.com/)

Não há dependências nem instalação de pacotes.

## 📥 Como clonar o projeto

```bash
git clone https://github.com/LuizPauloSoares/portal-conecta-tecnologia.git
cd portal-conecta-tecnologia
```

## 🚀 Instalação e configuração

1. Clone o repositório (comando acima) ou baixe o ZIP pelo botão **Code** do GitHub.
2. Mantenha `index.html` e `estilo.css` **na mesma pasta**.
3. Abra o `index.html` com um duplo clique ou arraste o arquivo para o navegador.
4. Para ver a versão original, abra o `refatora.html` e compare as duas.

## 🖼️ Exemplos de uso

> Adicione aqui as capturas de tela do projeto (por exemplo, em uma pasta `docs/`).

```
![Versão HTML5](docs/screenshot-html5.png)
![Versão HTML 4.01](docs/screenshot-html4.png)
```

- Clique nos botões do menu para navegar entre as seções.
- Reduza a janela do navegador abaixo de 768px para ver o layout responsivo.
- Passe o mouse sobre os botões do menu e do formulário para ver as transições.

## 🔄 O que mudou: HTML 4.01 → HTML5

| HTML 4.01 (`refatora.html`) | HTML5 (`index.html` + `estilo.css`) |
|---|---|
| `<!DOCTYPE HTML PUBLIC ...>` longo | `<!DOCTYPE html>` |
| `<meta http-equiv="Content-Type">` | `<meta charset="UTF-8">` |
| Sem idioma definido | `<html lang="pt-BR">` |
| Layout feito com `<table>` | `<header>`, `<nav>`, `<main>`, `<aside>`, `<footer>` + CSS Grid |
| Tags `<font>` | Classes de CSS |
| Atributos `bgcolor`, `text`, `link`, `align` | Propriedades de CSS |
| `<a name="topo">` | `id="topo"` |
| Blocos separados por `<hr>` | `<section>` e `<article>` |
| Texto solto nos campos do formulário | `<label for>` + `id` |
| E-mail com `type="text"` | `type="email"` |
| `<b>` e `<i>` | `<strong>` e `<em>` |
| `<input type="button">` | `<button type="button">` |
| Links externos sem `rel` | `rel="noopener noreferrer"` |
| Sem responsividade | `<meta viewport>` + media query |

## 📌 Status do projeto

✅ **Concluído** como atividade didática. Melhorias futuras estão no roadmap.

## 🗺️ Roadmap

- [ ] Usar variáveis CSS (`:root`) para as cores
- [ ] Adicionar `scroll-behavior: smooth` na navegação
- [ ] Criar classe própria para os títulos das notícias
- [ ] Usar `<fieldset>` e `<legend>` na enquete
- [ ] Adicionar menu hambúrguer para celular
- [ ] Validar o HTML e o CSS no [W3C Validator](https://validator.w3.org/)
- [ ] Publicar no GitHub Pages

## 📄 Licença

Distribuído sob a licença **MIT**. Veja o arquivo `LICENSE` para mais detalhes.

## 👤 Autor e créditos

**Luiz Paulo Soares dos Santos**

Atividade didática de modernização de HTML 4.01 para HTML5.

## 📬 Contato

- 📧 E-mail: [luizdayspring@gmail.com](mailto:luizdayspring@gmail.com)
- 📸 Instagram: [@lu1z_st](https://www.instagram.com/lu1z_st/)
- 💼 LinkedIn: [luiz-paulo-soares](https://www.linkedin.com/in/luiz-paulo-soares/)
- 🐙 GitHub: [LuizPauloSoares](https://github.com/LuizPauloSoares)
