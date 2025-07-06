# 🌐 Projeto: perfil.html

Este projeto consiste em uma página de perfil pessoal utilizando **HTML semântico** e **CSS responsivo**.

---

## 📁 Estrutura HTML

Utilize as seguintes tags para organizar o conteúdo em `perfil.html`:

### ✅ Tags obrigatórias

- `<header>` — Cabeçalho com:
  - Seu **nome**
  - **Foto**
  - (Opcional) **Slogan**
- `<nav>` — Menu de navegação com **âncoras internas** para as seções da página.
- `<main>` — Contêiner do conteúdo principal.
- `<section>` — Blocos temáticos, como:
  - Sobre mim
  - Habilidades
  - Projetos
  - Contato
- `<article>` — Para publicações, textos ou **depoimentos**, se houver.
- `<aside>` — Informações **complementares**:
  - Redes sociais
  - Links externos
- `<footer>` — Rodapé com:
  - Direitos autorais
  - Créditos

---

## 🎨 Estilo com CSS

### 🎯 Seletores

- **Por elemento:**  
  `h1`, `p`, `section` { ... }

- **Por classe:**  
  `.minha-classe { ... }`

- **Por ID:**  
  `#meu-id { ... }`

---

### 🧩 Layout

- Use **Flexbox** e/ou **CSS Grid** para criar colunas e grades.
- Inclua um **reset CSS** ou **normalize.css** para garantir consistência entre navegadores.

---

### ⚙️ Recursos avançados

- **Variáveis CSS**  
  Exemplo:
  ```css
  :root {
    --cor-primaria: #0077cc;
  }
