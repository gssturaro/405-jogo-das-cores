# Jogo das Cores
---
## - Linguagens Utilizadas no Jogo
 - `HTML`
 - `CSS`
 - `JAVA SCRIPT`
---
### - Ferramentas Utilizadas nas Linguagens
---
 - Utilizamos em `CSS`

 - `Display Flex.`
 - `Propriedades simples de edição.`

 - Utilizamos em `Java Script`

 - `For`
 - `Math`
 - `Function`
---
**-Ex: Função de Resetar Jogo**
~~~
function resetarJogo(){
    for(let quadrado of quadradinhos){
        quadrado.style.backgroundColor = "unset";
    }
    resposta.innerHTML = "Jogo resetado !";
}

botao.ondblclick = resetarJogo;
~~~
---
### Jogue o Jogo!
[Clique Aqui para Jogar](https://gabrielssturaro.github.io/405-jogo-das-cores/.)