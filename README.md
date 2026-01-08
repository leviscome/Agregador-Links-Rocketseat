# DevLinks

Pequeno linktree estático com tema claro/escuro, criado com HTML, CSS e JavaScript.

## Preview
- Página principal: `index.html`
- Alternar tema: botão no topo

## Recursos
- Tema claro/escuro (CSS custom properties)
- Links para redes sociais com ícones Ionicons
- Layout responsivo para mobile (360px design)

## Tecnologias
- HTML, CSS (Custom Properties), JavaScript
- Fonte: Inter (Google Fonts)
- Ícones: Ionicons

## Como usar
1. Clone o repositório:
  git clone <repo-url>
2. Abra `index.html` no navegador ou sirva com um servidor local:
  npx http-server .
3. Edite os links em `index.html` e as imagens em `assets/`.

## Estrutura
- index.html — marcação principal
- style.css — estilo e variáveis de tema
- script.js — alterna a classe `.light` no elemento root
- assets/ — imagens (avatar, background, ícones)

## Personalização rápida
- Avatar: `assets/avatar.png`
- Backgrounds: `assets/bg-mobile.jpg`, `assets/bg-mobile-light.jpg`
- Ícones switch: `assets/moon-stars.svg`, `assets/sun.svg`
- Alterar nome/links: editar `#profile p` e as tags `<a>` em `index.html`
- Ajustar cores: modificar variáveis em `:root` e `.light` no `style.css`

## Nota sobre o toggle
script.js:
function toggleMode() {
  document.documentElement.classList.toggle("light")
}

## Licença
MIT — sinta-se à vontade para usar e adaptar.
