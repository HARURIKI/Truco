let pontos1 = 0;
let pontos2 = 0;

function adicionarPontos(dupla, pontos) {
  if (pontos1 >= 12 || pontos2 >= 12) return;

  if (dupla === 1) {
    pontos1 += pontos;
    if (pontos1 > 12) pontos1 = 12;
    document.getElementById("pontuacao1").textContent = pontos1;
  } else {
    pontos2 += pontos;
    if (pontos2 > 12) pontos2 = 12;
    document.getElementById("pontuacao2").textContent = pontos2;
  }

  verificarVencedor();
}

function verificarVencedor() {
  const vencedorDiv = document.getElementById("vencedor");
  if (pontos1 >= 12) {
    vencedorDiv.textContent = "🎉 Dupla 1 venceu!";
  } else if (pontos2 >= 12) {
    vencedorDiv.textContent = "🎉 Dupla 2 venceu!";
  }
}
