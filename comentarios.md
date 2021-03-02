## Recursos

* Minify CSS:é um compressor que retira todos os espaçamentos, identação, minificando o código;

* Usar o "px" em font-size não aumenta a fonte do navegador quando damos zoom na página, dificultando que pessoas com baixa visão tenham acessibilidade (muito importante!) em suas leituras; daí usar "em" ou "rem";

* site "uigradients.com" para encontrar gradientes de cores;

## Comentários Sobre Tags

```css 

* {
    list-style: none; /* sem os marcadores de lista*/
    text-decoration: none; /* sem sublinhados nos links*/
}

header {

height: 100vh; 
/* vh: view height, altura da página ou visualização */
overflow: hidden; 
/* desabilita a possilidade do cabeçalho passar o tamanho da janela */
}

.hamburguer {
    z-index: 100; /* plano cartesiano z que permite que o elemento fique à frente do background */
}

.img-wrapper img {
/* seletor css para img dentro do img-wrapper; a imagem está envelopada, não é um elemento direto da página */
object-fit: 
/* especifica como o elemento, no caso a imagem, será colocado dentro da página; ele pode cubrir ou ser reduzido na div, fazendo com que a proporção não seja perdida caso a aumentássemos para visualização */

}

.banner {
    position: absolute;
/* pra funcionar precisa estar dentro de um elemento com position relative, como o banner está dentro do header, este será o p.r.; assim eu consigo colocar o banner em qualquer posição dentro do header */
    left: ; /* distância do elemento em relação à borda esquerda */
    text-shadow: ; /*distância à direita, baixo, blur (embaçada), cor */
    line-height: ; /*espaçamento*/
    font-weight: ; /* intensidade, peso da fonte */
    padding: ; /* se eu coloco um valor, é aplicado nos quatro cantos; se eu coloco dois valores, o primeiro valor será top-bottom e o segundo left-right; se eu coloco quatro valores, irá em sentido horário (top, right, bottom, left) */

}

.banner button:hover {
    /* quando o cursor é passado sobre o botão, ele pode mudar de cor, ficar mais opaco, etc */
}

@keyframes nome {
    0% {
        /* posição, aqui significa início */
    }
}


## Minhas Impressões

# Na primeira vez que usei o terminal para subir o arquivo no github, acabei comitando o arquivo do live-server e que não conseguiria excluí-lo. Entendi que o gitignore oculta esses arquivos para o público e é interessante que eles não sejam excluídos, pois assim podemos tanto como acompanhar a história do projeto, como tirá-los de seu estado de ignorado;

# Sempre verificar os arquivos e linhas antes de enviá-los;

# Quando enviar pelo terminal, olhar na integração e verificar se o shell do editor é o mesmo do gitdesktop;

# Os @keyframes nome {} precisam ser ligados aos elementos em que serão usados; separar essa propriedade de outras tags, nos dá liberdade para ativa-lá ou desativá-la sem que os elementos precisem, necessariamente, ser alterados;

# O devtools é fantástico pois nos permite alterar para visualização qualquer página, além de podermos copiar, para nosso código-fonte, qualquer modificação realizada; 

# Aviso (warning: LF will be replaced by CRLF in testes.html The file will have its original line endings in your working directory);

# Elemento "aside" deve ser usado nas barras laterais;

# Colocar "required" em contatos é importante, isso faz com a mensagem seja respondida no email enviado pelo usuário; importante que se for sugestão, críticas o campo email e nome seja facultativo


