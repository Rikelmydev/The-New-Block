#  The Block 
<img width="1365" height="589" alt="image" src="https://github.com/user-attachments/assets/5bf7ab6c-a421-456f-9281-2ee75d95ad1a" />


<p align="center">
  <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-00ccff?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Three.js-r128-black?style=for-the-badge&logo=three.js" alt="Three.js">
  <img src="https://img.shields.io/badge/GSAP-3.12.5-88CE02?style=for-the-badge&logo=greensock" alt="GSAP">
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Web_Audio_API-Sintetizado-purple?style=for-the-badge" alt="Web Audio API">
</p>

<p align="center">
  <b>The Block</b> é um jogo de puzzle 3D estratégico em estética <i>Cyberpunk / Sci-Fi Neon</i>, diretamente inspirado no clássico cult <b>Bloxorz</b>. Conduza o bloco retangular através de plataformas desafiadoras suspensas no espaço e faça-o encaixar perfeitamente de pé no portal de saída.
</p>

---

##  Sobre o Jogo

O objetivo do jogador é rolar um bloco retangular de dimensões **1x2x1** por um grid de blocos flutuantes, evitando cair no abismo cósmico e lidando com terrenos frágeis. Cada movimento altera a orientação do bloco entre vertical e horizontal (eixos X e Z).

Para vencer cada fase, o bloco deve terminar perfeitamente **em pé** sobre o orifício/portal luminoso de chegada.

---

##  Funcionalidades Principais

-  **12 Níveis Desafiadores**: Fases projetadas com progressão gradual de dificuldade e desafios espaciais instigantes.
-  **Física de Rotação 3D Precisa**: Sistema de pivô calculado dinamicamente em Three.js para tombamento realista do bloco.
-  **Sistema de Desempenho e Estrelas**: Avaliação de 1 a 3 estrelas baseada na quantidade de movimentos realizados vs. movimentos ideais.
-  **Função de Desfazer (Undo)**: Possibilidade de reverter jogadas passo a passo sem perder o progresso.
-  **Salvamento Automático**: Persistência de fases desbloqueadas, melhor pontuação e estrelas salvas localmente via `LocalStorage`.


---

##  Controles

| Controle | Teclado | Touch / Mobile | Ação |
| :--- | :--- | :--- | :--- |
| **Mover Bloco** | <kbd>W</kbd> <kbd>A</kbd> <kbd>S</kbd> <kbd>D</kbd> ou <kbd>↑</kbd> <kbd>←</kbd> <kbd>↓</kbd> <kbd>→</kbd> | **Deslizar o dedo (Swipe)** | Rola o bloco na direção correspondente |
| **Desfazer Jogada** | <kbd>Z</kbd> | Botão **↩ Desfazer** | Reverte o último movimento |
| **Reiniciar Fase** | <kbd>R</kbd> | Botão **⟳ Reiniciar** | Reinicia a posição e contador da fase |
| **Menu de Fases** | — | Botão **☰ Menu** | Retorna à seleção de fases e menu inicial |


---

##  Tecnologias Utilizadas

- **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML)** & **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS)**: Estrutura semântica, fontes (*Rajdhani*), efeitos de vidro (*glassmorphism*) e animações de glitch.
- **[JavaScript (ES6+)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)**: Arquitetura modular orientada a objetos.
- **[Three.js (r128)](https://threejs.org/)**: Renderização 3D WebGL, iluminação dinâmica, sombras, geometrias e sistema de partículas.
- **[GSAP 3.12.5](https://greensock.com/gsap/)**: Interpolações e animações suaves de rotação do bloco, transições e janelas modais.
- **[Web Audio API](https://developer.mozilla.org/pt-BR/docs/Web/API/Web_Audio_API)**: Sintetizador de ondas sonoras (*sine*, *square*, *sawtooth*, *triangle*) para áudio imersivo sem latência.

---

##  Como Executar o Projeto

Como o jogo foi desenvolvido de forma auto-contida e moderna em Web standards, não é necessária instalação de dependências ou compilação:

### Opção 1: Execução Direta
Basta dar um duplo clique no arquivo [`index.html`](index.html) para abri-lo em qualquer navegador moderno (Chrome, Edge, Firefox, Safari, Opera).

### Opção 2: Servidor Local (Recomendado para desenvolvimento)
Com o Node.js ou Python instalado, você pode rodar:

```bash
# Usando npx (Node.js)
npx serve .

# Ou usando Python 3
python -m http.server 8000
```
Em seguida, acesse no navegador: `http://localhost:8000` (ou a porta indicada).

---

##  Estrutura do Código

```text
The-New-Block/
│
├── index.html          # Arquivo principal contendo HTML, CSS e JavaScript do jogo
├── .gitattributes      # Configurações de atributos do Git
└── README.md           # Documentação completa do projeto
```

---

## 👨‍💻 Créditos

- **Desenvolvimento e Design**: [ricks](https://github.com/Rikelmydev)
- **Inspiração**: Clássico jogo de puzzle *Bloxorz* (originalmente criado por Damien Clarke / DX Interactive).
