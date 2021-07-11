# 🚀 Formúlario animado com JS puro e CSS Animation 🚀

## 📝 O que foi feito

- [x] O formulário aparece suavimente quando a página abre.
- [x] Os campos aparecem da esquerda para direita e entram em momentos distintos.
- [x] Ao clicar em "login", o formulário sai da tela indo para baixo.
- [x] O formulário foi removido do html, não mostra a barra de rolagem 
quando o formúlario sai da tela.
- [x] Foi adicionado um efeito diferentes do timing para a saída do formulário.
- [x] O formulário diz não-não (vibra) caso haja campos vazios.
- [x] Foram criados quadrados animados (que ficam girando), que saem de baixo da 
tela e vão para cima (fora do campo de visão). Os quadrados tem tamanhos diferentes,
saem em momentos diferentes, tem timing diferentes e a animação contínua.

## Animation

8 propriedades:

- animation-name: animationname;
- animation-duration: 2s;
- animation-delay: 3s;
- animation-fill-mode: none;
- animation-play-state: running;
- animation-timing-function: ease;
- animation-direction: reverse;
- animation-iteration-count: infinite;

@keyframes animationname {
    0% {

    }

  100%{

    }
  
}
podemos ter múltiplas animações no mesmo elemento

.animate {

    animation: slide-top 2s, bounce 1s, fade 0.2s;
  
}
