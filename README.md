## 💻 Visualização do Projeto

![Preview do Tech News](/assets/projeto_portal_de_noticias.png)

#  Tech News - Portal de Notícias Contemporâneo

Um portal de notícias responsivo e moderno, desenvolvido para consolidar conceitos avançados de **CSS Grid**, **Layouts Bi-dimensionais** e **Arquitetura de Software** no Front-end.

---

##  Tecnologias e Técnicas Aplicadas

O projeto foi construído utilizando **HTML5** e **CSS3**, explorando as capacidades mais recentes dos navegadores:

### 1. CSS Grid Layout (Nível Avançado)
* **Layout por Nomeação:** Uso de `grid-template-areas` para definir a malha estrutural (Main, Aside, Featured, Weekly), facilitando a manutenção do código.
* **Malha Dinâmica:** Implementação de `grid-auto-flow: column` e `grid-template-columns` para controle preciso de densidade em diferentes seções.
* **Utility-First:** Criação de um sistema de classes utilitárias (`grid-cols-2`, `gap-16`, `gap-32`) para acelerar o desenvolvimento e manter a consistência.

### 2. Arquitetura de CSS e Design System
* **Modularização:** Organização do CSS por componentes (`section.css`, `header.css`, `global.css`) utilizando `@import` para uma arquitetura limpa.
* **Custom Properties (Variáveis):** Gerenciamento centralizado de cores, fontes e tokens de tipografia (H1, H2, H3, Spans) via `:root`.
* **Nesting:** Uso de aninhamento nativo do CSS para melhorar a legibilidade e hierarquia dos seletores.

### 3. Seletores Modernos e UI Avançada
* **Seletor `:has()`:** Implementação de lógica condicional no CSS para ajustar o padding de elementos pais com base no conteúdo interno.
* **Pseudo-elementos:** Criação de overlays de gradiente dinâmico com `::before` para garantir a legibilidade do texto sobre as imagens.
* **Mídia Adaptável:** Uso de `aspect-ratio` e `object-fit: cover` para garantir que as imagens se adaptem a qualquer tamanho de container sem distorção.

---
