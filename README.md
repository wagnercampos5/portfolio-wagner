# 🌐 Portfólio Web — Wagner Campos

[![Deploy with GitHub Pages](https://img.shields.io/badge/Deploy-GitHub_Pages-0b6e4f?style=for-the-badge&logo=githubpages&logoColor=white)](https://wagnercampos5.github.io/portfolio-wagner/)
[![Status](https://img.shields.io/badge/Status-Online-2ea44f?style=for-the-badge)](#)
[![Stack](https://img.shields.io/badge/Stack-HTML5_%26_CSS3_Puro-0b6e4f?style=for-the-badge&logo=html5&logoColor=white)](#)

> Página única (Single-Page) desenvolvida sob medida para consolidação de marca pessoal, apresentação de competências em desenvolvimento Full Stack, Mobile e Inteligência Artificial, e captação de clientes para projetos sob demanda.

🔗 **Acesse o portfólio no ar:** [wagnercampos5.github.io/portfolio-wagner](https://wagnercampos5.github.io/portfolio-wagner/)

---

## 🎯 Objetivo & Proposta de Valor

Diferente de portfólios genéricos com excesso de bibliotecas e dependências pesadas, esta aplicação foi desenhada com foco em **performance pura, carregamento instantâneo e alta taxa de conversão**. 

A estrutura comunica autoridade técnica e visão de negócio, destacando como o desenvolvimento de software resolve dores comerciais para pequenas e médias empresas através de páginas de vendas, catálogos digitais e integrações com automação e IA.

---

## 🎨 Identidade Visual & Design System

A interface gráfica foi concebida com um esquema cromático moderno em tons de menta e verde floresta, transmitindo inovação, clareza e solidez técnica:

* **Paleta de Cores:**
  * Fundo Primário (`--bg-principal`): `#C7FFDA` (Menta suave)
  * Cartões & Elementos (`--bg-secundario`): `#FFFFFF` (Branco puro para contraste e legibilidade)
  * Destaques & Ações (`--destaque`): `#0b6e4f` (Verde esmeralda escuro)
  * Estado Hover (`--destaque-hover`): `#08523b`
  * Textos Principais (`--texto-principal`): `#0f291e` (Alto contraste para acessibilidade)
  * Bordas & Divisores (`--borda`): `#a3e7be`
* **Tipografia:** Sistema de fontes nativas (`system-ui`, `-apple-system`, `BlinkMacSystemFont`), eliminando requisições externas de web fonts e acelerando a renderização do layout.
* **Microinterações:**
  * Efeito de elevação vertical (`translateY(-10px)`) nos cartões de competências e projetos com foco visual na borda ativa.
  * Transições suaves de cor e preenchimento nos botões primários e secundários.
  * Barra de navegação com fixação contínua (`position: sticky`) com suporte a rolagem suave (`scroll-behavior: smooth`).

---

## ⚙️ Destaques de Engenharia Front-end

* **Zero Dependências (100% Vanilla):** Ausência total de frameworks CSS ou scripts de terceiros, garantindo pontuações máximas em métricas de Core Web Vitals (LCP, FID e CLS).
* **HTML5 Estritamente Semântico:** Uso correto de tags estruturais (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) para máxima indexação orgânica (SEO) e compatibilidade com tecnologias assistivas (`a11y`).
* **Sistemas Modernos de Layout:**
  * **CSS Grid** com `repeat(auto-fit, minmax(...))` para redistribuição fluida dos cards sem necessidade de dezenas de breakpoints manuais.
  * **Flexbox** para alinhamento simétrico da barra de navegação, cabeçalho de apresentação (*hero section*) e grupos de botões.
* **Design Responsivo & Mobile-First:** Adaptação completa de menus, espaçamentos, tipografia e botões para dispositivos móveis abaixo de `768px`.

---

## 🧭 Arquitetura de Conteúdo

1. **Header & Navegação:** Identidade visual `<WagnerCampos />` e atalhos rápidos entre as seções.
2. **Hero Section:** Boas-vindas, proposta de posicionamento e botões de chamada primária para ação (CTAs).
3. **Sobre Mim:** Apresentação executiva da postura profissional, foco em arquitetura limpa e entrega de valor de negócio.
4. **Habilidades & Tecnologias:** Matriz técnica categorizada em três pilares fundamentais:
   * *Front-end* (Semântica, UI moderna, acessibilidade e padrões CSS)
   * *Back-end & Dados* (Node.js, APIs REST e bancos relacionais/não-relacionais)
   * *Ferramentas, Cloud & IA* (Git, OCI Cloud, agentes autônomos e automações)
5. **Vitrine de Projetos:** Cartões independentes contendo escopo do projeto, tecnologias aplicadas e links duplos (código-fonte no GitHub e demonstração ativa):
   * *Raza13 Tattoo Studio* (Landing page de conversão)
   * *MarombaFIT* (Vitrine digital e e-commerce display)
   * *Hub de Links Pessoal* (Agregador de canais estilo Linktree ultra-otimizado)
6. **Contato & Conversão:** Canais diretos para fechamento de contratos e networking profissional.

---

## 📂 Estrutura do Repositório

```text
├── index.html        # Estrutura semântica, meta tags, marcação das seções e conteúdo textual
├── style.css         # Variáveis CSS, reset global, sistema de grids, media queries e efeitos
└── README.md         # Documentação e especificações técnicas do portfólio
```

---

## 📬 Contato & Conexão

* **Wagner Campos** — Desenvolvedor Full Stack, Mobile & IA
* **E-mail:** [wagnercmps20@gmail.com](mailto:wagnercmps20@gmail.com)
* **LinkedIn:** [linkedin.com/in/wagnercampos5](https://linkedin.com/in/wagnercampos5)

---

Desenvolvido por **Wagner Campos**. Focado em performance, código semântico e soluções digitais de alto impacto.