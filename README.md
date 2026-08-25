#  Project Monolith: Spatial Ruins

> Um puzzle game 3D isometrico para navegador, inspirado no clássico *Bloxorz*, desenvolvido com **HTML5/CSS3**.

![Game Banner / Screenshot](https://raw.githubusercontent.com/seu-usuario/project-monolith/main/assets/banner.jpg)

[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://seu-usuario.github.io/project-monolith/)
---

##  Sobre o Projeto

**Project Monolith: Spatial Ruins** traz a clássica jogabilidade de alinhamento espacial do *Bloxorz* para a web moderna. O jogador controla a **Arka**, um monólito cristalino ancestral que precisa navegar por plataformas flutuantes, acionar mecanismos e atravessar portais dimensionais para reativar os *Anéis Ley*.

O projeto foi construído do zero focando em **alto desempenho**, **controles suaves via matriz de pivô**, **iluminação física (PBR)** e uma **interface responsiva**, sem dependência de engines pesadas, ideal para execução direta no navegador.

 **[Clique aqui para jogar a versão demo online](https://seu-usuario.github.io/project-monolith/)**

---

##  Funcionalidades Principais

-  **Física de Rotação por Pivô:** Rotação suave baseada em matriz tridimensional ($1 \times 1 \times 2$), calculando os eixos de rotação de cada aresta em tempo real com GSAP.
-  **Mapa de Fases (Overworld Map):** Sistema de seleção de níveis no estilo *Sackboy / Mario 3D World*, divididos em 3 setores temáticos.
-  **Sistema de Estrelas & Highscore:** Classificação por desempenho (1 a 3 estrelas) comparando os movimentos realizados com a marca ideal do nível.
-  **Sistema de Undo (Desfazer) & Restart:** Estrutura de dados em Pilha (*Stack*) para desfazer jogadas instantaneamente sem quebrar o estado do jogo.
-  **Persistência de Dados Local:** Salvamento automático de progresso, estrelas, configurações de áudio e skins desbloqueadas via `LocalStorage`.
-  **Estilização & Temas Visualmente Stylized:** Iluminação física com sombras suaves, partículas de brilho (*glow/bloom*) e suporte a skins customizadas para o bloco.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem Principal:** JavaScript (ES6+)
- **Renderizador 3D:** [Three.js](https://threejs.org/) (WebGL2)
- **Animações & Interpoladores:** [GSAP (GreenSock)](https://greensock.com/gsap/)
- **Gerenciamento de Áudio:** [Howler.js](https://howlerjs.com/)
- **Interface & HUD:** HTML5, CSS3 (Flexbox/Grid, Glassmorphism)
- **Hospedagem & CI/CD:** GitHub Pages / GitHub Actions
