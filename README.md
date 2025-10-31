# Tela de Carregamento – Estilo Slack

Uma réplica minimalista e elegante da **tela de carregamento do Slack**, feita com HTML puro e CSS. Perfeita para protótipos, landing pages ou como inspiração para interfaces de carregamento em aplicações web.

> ✨ Leve, sem JavaScript, 100% responsiva e fácil de personalizar.

---

## 🌟 Demonstração ao vivo

Veja o projeto funcionando aqui:  
👉 [**Demo no GitHub Pages**](https://maike-simoncini.github.io/Tela-de-Carregamento/)

---

## 📦 Estrutura do Projeto

```
Tela-de-Carregamento/
├── index.html
├── style.css
└── README.md
```

---

## 🎨 Personalização

Você pode adaptar facilmente o design:

| Elemento             | Como personalizar |
|----------------------|-------------------|
| Cor do spinner       | Altere `border-left-color` e `border-top-color` em `.loading__anim` |
| Cor do texto         | Modifique `color` em `.loading` e `.loading__author` |
| Tamanho do spinner   | Ajuste `width` e `height` em `.loading__anim` |
| Velocidade da animação | Mude a duração em `animation: rotate 600ms infinite linear;` |
| Mensagem de texto    | Edite o conteúdo dentro da tag `<section class="loading">` |

Exemplo: para usar tons de verde:

```css
.loading__anim {
  border-left-color: #4CAF50;
  border-top-color: #4CAF50;
}
```

---

## 🧩 Tecnologias usadas

- **HTML5**
- **CSS3** (Flexbox, animações com `@keyframes`)

> 💡 Nenhum framework, biblioteca ou JavaScript necessário.
