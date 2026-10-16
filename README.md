# Subway Super Hopper Game

Jogo casual de corrida infinita em 3D, feito com Three.js. Desvie dos obstáculos trocando de faixa e pule para tentar sobreviver por mais tempo e aumentar a pontuação.

## Como jogar

- Use as setas **←** e **→** para trocar entre as três faixas.
- Use **↑** para pular.
- Clique em **PRESS START** para começar. Depois de uma colisão, clique em **TRY AGAIN** para reiniciar.
- **Enter** ou **Espaço** também iniciam a partida quando ela ainda não está em andamento.

## Recursos

- Cenário 3D com obstáculos gerados durante a partida.
- Cinco temas visuais possíveis: Candy, Neon, Sunset, Mint e Midnight.
- Personagem com aparência parcialmente aleatória a cada partida.
- Pontuação e aumento gradual da velocidade.
- Tela de início, tela de fim de jogo e adaptação do renderizador ao redimensionamento da janela.

## Executar localmente

O projeto não requer processo de build. Como usa módulos JavaScript, abra-o por um servidor HTTP local, não diretamente pelo endereço `file://`.

```bash
python3 -m http.server 8000
```

Depois, acesse <http://localhost:8000> no navegador. O navegador precisa oferecer suporte a WebGL e ter acesso à internet para carregar o Three.js e a fonte usados pelo projeto.

## Tecnologias e dependências

- HTML, CSS e JavaScript com módulos ES.
- [Three.js 0.160.0](https://unpkg.com/three@0.160.0/build/three.module.js), carregado do unpkg.
- Fonte [VT323](https://fonts.google.com/specimen/VT323), carregada do Google Fonts.

## Arquivos

- `index.html` — estrutura da página, interface e importmap do Three.js.
- `style.css` — estilos da interface.
- `script.js` — renderização 3D, controles e lógica do jogo.
