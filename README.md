<div align="center">

# TAP Air Portugal — Frontend Clone

**Web Technologies Course — ISEC 2025/2026**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?logo=sass&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![No Frameworks](https://img.shields.io/badge/Frameworks-None-lightgrey)

A pixel-accurate static recreation of the [TAP Air Portugal](https://www.flytap.com) homepage, built entirely from scratch with vanilla HTML, SCSS, and JavaScript — no libraries, no frameworks.

<br>

<!-- Add a screenshot of your project here for visual impact -->
<!-- ![Preview](img/screenshot-desktop.png) -->

</div>

---

<details open>
<summary><strong>🇬🇧 English</strong></summary>

## About

This project is a full static frontend recreation of the official TAP Air Portugal website, developed for the **Web Technologies** course in the Computer Engineering degree at **ISEC — Instituto Superior de Engenharia de Coimbra**. The goal was to faithfully reproduce the visual design, layout structure, and interactive behavior of the TAP homepage using only core web technologies.

## Features

**Navigation & Layout** — Fully responsive mega-dropdown navigation with multi-level menus, hamburger menu for mobile viewports, and a sticky header that adapts its styling on scroll.

**Hero Carousel** — Multi-slide image carousel with dot indicators and smooth transitions, cycling through promotional banners.

**Booking Interface** — Tabbed booking panel with four sections (flight search, trip management, check-in, and flight status), including form inputs, date selectors, and custom checkboxes.

**Flight Status Modal** — Interactive modal overlay that displays flight details (departure time, status) with animated open/close behavior.

**Destination Cards** — Grid of flight offer cards with destination images, pricing, and hover effects. Supports filtering by region and a "show more" toggle.

**Responsive Design** — Full breakpoint coverage from mobile (~375px) to desktop (1920px+), with layout reflows, hidden/visible elements, and a dedicated mobile navigation.

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 semantic elements |
| Styling | SCSS compiled to CSS3 (Flexbox, Grid, media queries, CSS transitions) |
| Interactivity | Vanilla JavaScript (DOM manipulation, event handling) |
| Icons | SVG sprite sheet with `<use>` references |
| Fonts | Google Fonts (Lato, Montserrat) |

No external libraries or frameworks were used — this was a strict requirement of the assignment.

## Project Structure

```
tap-airline-frontend-clone/
├── index.html          # Single-page markup (~1500 lines)
├── style.scss          # SCSS source with variables, nesting, and mixins
├── style.css           # Compiled CSS output
├── script.js           # Carousel, menus, modal, and tab logic
└── img/                # Destination photos, icons (SVG sprite), logos
```

</details>

---

<details>
<summary><strong>🇵🇹 Português</strong></summary>

## Sobre

Este projeto é uma recriação estática completa do frontend do website oficial da TAP Air Portugal, desenvolvido no âmbito da unidade curricular de **Tecnologias Web** do curso de Engenharia Informática no **ISEC — Instituto Superior de Engenharia de Coimbra**. O objetivo foi reproduzir fielmente o design visual, a estrutura de layout e o comportamento interativo da página inicial da TAP, utilizando apenas tecnologias web base.

## Funcionalidades

**Navegação e Layout** — Navegação responsiva com mega-dropdowns multi-nível, menu hamburger para dispositivos móveis e header fixo que adapta o estilo ao scroll.

**Carrossel Hero** — Carrossel de imagens com indicadores de pontos e transições suaves, alternando entre banners promocionais.

**Interface de Reservas** — Painel de reservas com tabs para quatro secções (pesquisa de voos, gestão de viagens, check-in e estado do voo), incluindo inputs de formulário, seletores de data e checkboxes personalizadas.

**Modal de Estado do Voo** — Modal interativo que apresenta detalhes de voo (hora de partida, estado) com animação de abertura e fecho.

**Cards de Destinos** — Grelha de ofertas de voo com imagens de destinos, preços e efeitos hover. Suporta filtragem por região e toggle de "mostrar mais".

**Design Responsivo** — Cobertura completa de breakpoints desde mobile (~375px) até desktop (1920px+), com reflows de layout e navegação mobile dedicada.

## Stack Tecnológica

| Camada | Tecnologia |
|---|---|
| Markup | Elementos semânticos HTML5 |
| Estilização | SCSS compilado para CSS3 (Flexbox, Grid, media queries, transições CSS) |
| Interatividade | JavaScript vanilla (manipulação DOM, gestão de eventos) |
| Ícones | Sprite sheet SVG com referências `<use>` |
| Fontes | Google Fonts (Lato, Montserrat) |

Não foram utilizadas bibliotecas ou frameworks externas — requisito estrito do enunciado.

## Estrutura do Projeto

```
tap-airline-frontend-clone/
├── index.html          # Markup single-page (~1500 linhas)
├── style.scss          # Source SCSS com variáveis, nesting e mixins
├── style.css           # CSS compilado
├── script.js           # Lógica do carrossel, menus, modal e tabs
└── img/                # Fotos de destinos, ícones (SVG sprite), logos
```

Desenvolvido para a cadeira de Tecnologias Web (2025/2026) no DEIS — Instituto Superior de Engenharia de Coimbra.

</details>