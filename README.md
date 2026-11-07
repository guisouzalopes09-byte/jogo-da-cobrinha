🐍 Snake Game --- Classic Arcade
Um jogo da cobrinha desenvolvido com HTML5, CSS3 e JavaScript puro,
inspirado nos clássicos jogos de arcade. O projeto apresenta uma
interface moderna, controles para computador e dispositivos móveis,
sistema de pontuação e armazenamento do recorde no navegador.
🎮 Sobre o projeto
O objetivo é controlar a cobrinha pelo tabuleiro, coletar os alimentos e
aumentar a pontuação sem colidir com as paredes ou com o próprio corpo.
A cada alimento coletado, a cobrinha cresce e o jogador recebe 10
pontos. O jogo termina quando ocorre uma colisão. Também é possível
vencer ao preencher todo o tabuleiro.
✨ Funcionalidades
🕹️ Movimentação da cobrinha em quatro direções.
🍎 Alimentos gerados aleatoriamente em posições livres do tabuleiro.
📈 Sistema de pontuação: 10 pontos por alimento coletado.
🏆 Recorde salvo no `localStorage` do navegador.
⏸️ Opção para pausar e continuar a partida.
🔄 Opção para reiniciar o jogo.
💥 Detecção de colisões com as paredes e com o próprio corpo.
🎉 Condição de vitória quando todo o tabuleiro é ocupado.
📱 Controles adaptados para dispositivos móveis, incluindo botões
direcionais e gestos na tela.
📐 Interface responsiva para diferentes tamanhos de tela.
🛠️ Tecnologias utilizadas
---
Tecnologia                          Utilização
---
HTML5                           Estrutura e organização dos
elementos da página.
CSS3                            Estilização, layout responsivo,
cores, efeitos visuais e animações
de interação.
JavaScript (Vanilla)            Lógica do jogo, movimentação,
pontuação, colisões, controles e
gerenciamento dos estados.
Canvas API                      Desenho do tabuleiro, da cobrinha e
dos alimentos.
LocalStorage                    Armazenamento local do recorde
entre sessões.
> O projeto não utiliza frameworks ou bibliotecas externas.
🧩 Como jogar
No computador
⬆️ Setas do teclado ou W, A, S, D: movimentar a cobrinha.
Espaço: pausar ou continuar a partida.
Enter: iniciar ou reiniciar quando o jogo estiver pronto ou
finalizado.
No celular
Toque nos botões direcionais exibidos na tela.
Ou deslize o dedo sobre o tabuleiro para mudar a direção.
Objetivo
Colete os alimentos para ganhar pontos e aumentar o tamanho da cobrinha.
Evite atingir as paredes ou o próprio corpo!
🚀 Como executar o projeto
Não é necessário instalar dependências ou configurar um servidor.
Faça o download ou clone este repositório.
Abra a pasta do projeto.
Abra o arquivo `index.html` em um navegador atualizado.
Clique em COMEÇAR JOGO e divirta-se!
📁 Estrutura do projeto
``` text
snake-game/
└── index.html    # Estrutura, estilos e lógica do jogo
```
Todo o projeto está concentrado em um único arquivo HTML, que contém o
CSS e o JavaScript.
🎨 Interface
O jogo utiliza uma identidade visual inspirada em arcades, com:
🌑 Fundo escuro para destacar os elementos.
💚 Verde neon para a cobrinha, a pontuação e os destaques.
🔴 Vermelho para representar os alimentos e ações de perigo.
📊 Painel com pontuação atual e recorde.
✨ Efeitos de brilho e cartões com visual moderno.
🧠 Conceitos praticados
Este projeto permite praticar conceitos importantes de desenvolvimento
front-end, como:
Manipulação do DOM.
Eventos de teclado, clique e toque.
Desenho e atualização de elementos com Canvas.
Arrays, objetos e funções em JavaScript.
Controle de estado e temporização com `setInterval`.
Armazenamento de dados com `localStorage`.
Layout responsivo com media queries.
📌 Observações
O recorde é armazenado no navegador por meio do `localStorage`.
Portanto, ele fica associado ao navegador e ao dispositivo
utilizados.
Caso o navegador não permita o uso do `localStorage`, o jogo
continua funcionando, mas o recorde não será persistido.
O projeto foi desenvolvido sem dependências externas.
---
⭐ Se você gostou do projeto, considere deixar uma estrela no
repositório!
Desenvolvido para praticar HTML, CSS e JavaScript. 💻
