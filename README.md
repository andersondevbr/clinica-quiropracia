# Pedro Nogueira · Quiropraxia e Terapia Manual

Site institucional de página única para Pedro Nogueira, quiropraxia e terapia manual em Camocim, CE, com agendamento pelo WhatsApp.

**Demo:** _em breve_

## Screenshots

| Desktop (escuro) | Desktop (claro) |
| --- | --- |
| ![Página inicial no tema escuro, desktop](.github/screenshots/desktop-escuro.png) | ![Página inicial no tema claro, desktop](.github/screenshots/desktop-claro.png) |

| Mobile (escuro) | Mobile (claro) |
| --- | --- |
| <img src=".github/screenshots/mobile-escuro.png" alt="Página inicial no tema escuro, mobile" width="300"> | <img src=".github/screenshots/mobile-claro.png" alt="Página inicial no tema claro, mobile" width="300"> |

## Stack

HTML, CSS e JavaScript puros: um único `index.html`, sem framework e sem etapa de build.

## Funcionalidades

- **Tema claro/escuro sem flash:** segue a preferência do sistema, lembra a escolha e aplica o tema antes da primeira pintura.
- **Acessibilidade:** link para pular ao conteúdo, navegação por teclado, foco visível, `aria` nos controles e respeito a `prefers-reduced-motion`.
- **Reveal com IntersectionObserver:** os blocos entram suavemente ao rolar, com fallback para que nada fique escondido.
- **Agendamento pelo WhatsApp:** botões com mensagem pronta para consultório ou atendimento a domicílio.
- **Responsivo:** layout pensado do celular ao desktop, com imagens WebP em vários tamanhos (`srcset`).
- **SEO e compartilhamento:** metatags Open Graph/Twitter, favicon e dados estruturados (JSON-LD).

## Como rodar localmente

Abra o `index.html` no navegador. Para servir como em produção:

```bash
npx serve .
```

Para publicar, envie `index.html` e a pasta `assets/` para qualquer hospedagem estática. Depois de publicar, troque o `og:image` por uma URL absoluta e adicione `og:url`/`canonical` (há um comentário no `<head>` indicando onde).

## Créditos

Desenvolvido por Anderson.
