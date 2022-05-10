# b7web_teste_estagiario_dev_web
- Qual a função do no HTML?
  **R: O HTML é uma linguagem de marcação, cujo objetivo é criar a estrutura de uma pagina web, títulos, textos, imagens etc.**
  
- Quando uma página é criada, ela automaticamente se adapta a todos os tipos de tela? Por que?**R: Não, o conteudo dos elementos ficam relativo ao tamanho da tela atual ou fixos, para resolver isso é necessario configurar a viewport atraves da tag meta e adicionar responsividade com CSS**

- O código HTML e CSS é renderizado no servidor e repassado para o navegador em forma de imagem?
 **R: Não**
 
- Qual a função das tags H (h1, h2, h3, etc) no HTML?
  **R: A tag h se trata de elementos de título de forma hierárquica onde h1 é o maior titulo tanto de estilo como semanticamente e o h6 é o menor deles**
  
- O que é SEO e como funciona?
 **R: SEO são o cunjunto de tecnicas que são aplicados na pagina para melhorar o alcance de busca da mesma, exemplo utilizar tags html5, definir descrição, keywords entre varias outros detalhes**
 
- O uso de media query é obrigatório em todas as páginas?
**R: Não necessariamente as vezes somente utilizando medidas em porcentagem, e flex-box poupa o uso de media query**

- Qual a diferença entre CSS Inline e CSS em um arquivo?
**R: CSS inline é aplicado diretamente na tag html é pratico para usar algumas vezes ou até mesmo em projetos pequenos. Já quando se trata de um arquivo separado
é quando CSS vai ser utilizado para estruturar uma ou mais paginas sendo linkado na pagina html atraves da tag link**

- Como criar animações no CSS? Dê um exemplo.
**R: Animações CSS são criados a partir do keyframes onde é definido estilos para cada fração de tempo do total que é definido, por exemplo uma animação de fade in de 0.8 segundos é necessario criar apenas dois estados a origem e destino onde a origem a opacidade é 0 e destino 1 igual é mostrado no código abaixo**

```CSS
.fade-in {
    animation: fade-in 0.8s;
    animation-fill-mode: forwards;
}

@keyframes fade-in {
    from {
        opacity: 0;
    }
    to {
        opacity: 1;
    }
}
```
- Qual a diferença entre class e ID no CSS?
**R: IDs são utilizados para definir valores unicos, e class para mais de um valor, então se o estilo for aplicado em varios elementos utiliza-se class e para um unico elemento ID**

- Quais os diferentes tipos de seletores CSS?
**R: O CSS disponibiliza uma serie de seletores alem da class, id e tag, alguns exemplos são pseudo classes (hover, link, visited, active), pseudo elements(::placeholder, ::after, ::before), por atributos, ordenação, pai, filho entre varios outros**
