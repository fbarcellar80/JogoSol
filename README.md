# JogoSol — Sol Errante

Protótipo de jogo web (um único arquivo: `index.html`). Abra no navegador.

Um sol incandescente vaga pelo espaço. Clique sobre ele, **arraste** na direção desejada e solte
para aplicar um empurrão. Como o sol tem muita inércia, um empurrão só desvia um pouco a rota.

## Elementos
- **Obstáculos**: rochas espaciais, planetas do sistema solar e lixo espacial (satélites, estágios de foguete, destroços). O sol quica neles.
- **Naves**: fogem do sol; atingi-las dá **+1,5 de massa**.
- **Estrelas**: cada choque rouba **1,2 de massa**.
- **Buracos negros**: puxam o sol com gravidade e drenam massa enquanto ele estiver no disco de acreção.
- **Artilharia interestelar**: aparece a cada 3 minutos e dispara contra o sol (cada tiro tira 0,7 de massa).
  Precisa ser atingida pelo sol **4 vezes** para ser destruída, e dá +5 de massa.

Se a massa cair abaixo de 1, o sol se apaga e o jogo termina.

## Controles laterais
Aleatoriedade, quantidade de obstáculos, naves, estrelas/buracos negros, massa do sol, velocidade de cruzeiro
e qualidade do sol (WebGL ou 2D). O botão "Chamar artilharia" invoca o chefe na hora, para testes.
Abrir com `?render=2d` força o sol em Canvas 2D.
