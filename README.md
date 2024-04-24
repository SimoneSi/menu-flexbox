# Menu com flexbox
Projeto de menu semântico e responsivo utilizando as propriedades de flexbox e unidade de medida em rem 🚀

## Tecnologia utilizadas
- HTML
- CSS

##  Um erro interessante 
Como foi trabalhado nesse projeto a unidade de mediada em rem acabei por declarar a nova medida padrão no body da página o que casou a não correspondencia dos tamanhos esperados para os estilos das tags. Contudo, o erro foi reparado com o seletor html recebendo a propriedade padrão do font-size.

````
body{
    font-size:62,5%
}
