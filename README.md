# 🍽️ Página de Receitas - Projeto Prático com Bootstrap 5

Este repositório apresenta uma **página web de receitas culinárias**, desenvolvida com o objetivo de praticar e aplicar conceitos fundamentais do **Bootstrap 5**. A aplicação agrupa diferentes receitas em **cards** interativos com suporte a **modais** e **accordions** para exibição detalhada de ingredientes e modo de preparo.
[Confira!](https://danilodoes.github.io/receitas-bootstrap/)

---

## 📌 Objetivo

Este projeto tem como finalidade exercitar o uso prático do **framework Bootstrap 5**, implementando uma interface **modular, responsiva e interativa** para visualização de receitas. Através da combinação de diversos componentes do framework, o projeto simula uma galeria culinária, com foco em **usabilidade e estética**.

---

## 🧑‍🍳 Funcionalidades Implementadas

- ✅ Listagem de receitas organizadas em **cards responsivos**
- ✅ Detalhamento completo das receitas usando **modais interativos**
- ✅ Uso de **accordions** para seções de "Ingredientes" e "Modo de Preparo"
- ✅ Estrutura fluida com **flexbox**
- ✅ Estilização adicional com **classes utilitárias do Bootstrap** e **CSS personalizado**

---

## 🗂️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **Bootstrap 5.3.6** (via CDN)
- **Font Awesome 6.7.2** (ícones, se necessário)
- **JavaScript (via Bootstrap Bundle)**

---

## 📐 Componentes e Conceitos do Bootstrap Utilizados

### 🎴 Cards
Cada receita é exibida dentro de um componente `card` (`.card`, `.card-body`, `.card-title`, `.card-text`), com uma imagem, título, subtítulo e botão de ação. São utilizados também os modificadores visuais como `shadow` e `my-2`.

### 🧱 Containers
A estrutura geral é organizada com a classe `container` e `customContainer` (personalizada via CSS), permitindo alinhamento e responsividade com margens e preenchimentos consistentes.

### 📦 Flexbox
O agrupamento dos cards é realizado com `d-flex`, `flex-wrap`, `gap-2` e `justify-content-around`, criando uma disposição fluida e adaptável para múltiplos tamanhos de tela.

### 🧩 Accordions
Utilizados dentro dos modais, os `accordion` permitem mostrar/ocultar dinamicamente os **ingredientes** e o **modo de preparo** de cada receita. Eles estão implementados com `accordion-button`, `accordion-collapse`, `collapse`, entre outros.

### 💬 Modal
Ao clicar em "Saiba mais", um `modal` específico da receita é acionado. O componente `modal` do Bootstrap é utilizado com `fade`, `modal-dialog-scrollable` e `modal-dialog-centered`, trazendo acessibilidade e foco na experiência do usuário.

### 🎨 Utilitários Bootstrap
Foram usados utilitários para espaçamento (`my-2`, `mb-2`), alinhamento (`d-flex`, `justify-content-end`), tipografia (`text-secondary`, `card-title`, etc.) e responsividade.

---

## 🖼️ Estrutura Visual

Cada card representa uma receita, contendo:

- 📸 Imagem do prato
- 🧑 Nome do chef/responsável
- 📝 Descrição breve
- 🔘 Botão para abrir modal com detalhes

Ao abrir um modal, o usuário visualiza:

- Ingredientes (accordion)
- Modo de preparo (accordion)
- Botões de ação: "Amei a receita!" e "Fechar"

---

## 🧠 Aprendizados

Durante a construção do projeto, foram fixados conceitos importantes, tais como:

- Compreensão do sistema de **componentes reutilizáveis** do Bootstrap  
- Utilização do **sistema de flexbox**  
- Implementação de **UI interativa sem JavaScript manual**  
- Organização de layouts responsivos com **mínimo esforço**  
- Melhores práticas de estruturação **HTML semântica**

---

## 🤝 Contribuições

Sugestões e melhorias são sempre bem-vindas! Fique à vontade para abrir uma issue ou enviar um pull request.

---

## 📫 Contato
<img width="30px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linkedin/linkedin-original.svg" /> [Acesse aqui](https://linkedin.com/in/danilodoes)
    
---
