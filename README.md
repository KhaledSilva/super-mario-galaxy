# Super Mario Galaxy: O Filme

Página promocional conceitual, em português, inspirada em *Super Mario Galaxy: O Filme*. O projeto apresenta uma experiência de página única com estética espacial, animações de rolagem, personagens, trailers incorporados e uma contagem regressiva para a data de estreia informada na própria página.

> **Projeto conceitual para fins educacionais.** Não é um site oficial da Nintendo. A página inclui um aviso sobre marcas registradas no rodapé.


## Funcionalidades

- **Hero cinematográfico:** apresentação visual com vídeos decorativos e animações de rolagem.
- **Navegação:** acesso às principais seções da página.
- **Personagens:** apresentação do elenco com efeitos de partículas.
- **Carrossel de trailers:** quatro vídeos do YouTube, com controles por botões e teclado.
- **Contagem regressiva:** contador até 25 de dezembro de 2026.
- **Responsividade:** layout adaptado a diferentes tamanhos de tela.
- **Acessibilidade:** suporte à preferência por movimento reduzido.

## Tecnologias

- **HTML5:** estrutura e conteúdo da página.
- **CSS3:** estilização, responsividade e animações.
- **JavaScript (ES6+):** interatividade e funcionalidades.
- **Canvas 2D:** renderização de efeitos visuais.
- **GSAP e ScrollTrigger:** animações e efeitos de rolagem.
- **particles.js:** efeitos de partículas.
- **Google Fonts (Outfit):** tipografia.
- **YouTube:** incorporação dos trailers.

O GSAP, ScrollTrigger e particles.js são carregados por CDN no `index.html`. As fontes bibliotecas e os vídeos do YouTube também dependem de serviços externos carregados pela internet.

## Estrutura do projeto

```text
├── assets/
│   ├── images/       # Imagens e elementos visuais
│   └── videos/       # Vídeos utilizados na página
├── css/
│   └── styles.css    # Estilos e responsividade
├── js/
│   ├── script.js     # Funcionalidades principais
│   └── scroll-animations.js
├── docs/             # Documentação e especificações
├── prints/           # Capturas de tela e referências visuais
├── index.html        # Página principal
└── DESIGN.md         # Diretrizes visuais do projeto
```

## Como executar

1. Clone o repositório:

```bash
git clone https://github.com/KhaledSilva/super-mario-galaxy.git
```

2. Acesse a pasta do projeto:

```bash
cd super-mario-galaxy
```

3. Abra o arquivo `index.html` diretamente no navegador.

Não é necessário instalar dependências ou configurar um processo de build.

## Acessar o projeto

Você também pode acessar a versão publicada diretamente pelo link:

[Super Mario Galaxy: O Filme](https://khaledsilva.github.io/super-mario-galaxy/)

## Navegação

No carrossel de trailers, utilize as setas da interface ou as teclas **←** e **→** para navegar. As teclas **Home** e **End** permitem acessar o primeiro e o último trailer.
