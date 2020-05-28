# Markdown
### Aprendendo a trabalhar com Markdown

Esse site tem intuito de mostrar as maneiras que o Markdown pode ser utilizado para formatar seu arquivo README. Além de algumas utilizações dentro do GitHUB.

- #### Afinal, o que é o MARKDOWN?

Markdown é uma linguagem de marcação que, basicamente, faz alterações nos textos utilizando símbolos como asterisco (*), underline (_), til (~) e etc. Estilizando o texto de maneira similar ao glorioso HTML. Inclusive, é possível mesclar as duas linguagens de marcação tranquilamente.

- #### E esse tal de README, o que é?

Ele é, basicamente, um arquivo de texto que pode ser escrito a partir de tags HTML ou Markdown. O README traz informações sobre seu projeto de forma geral, ou seja, é a documentação que indica por qual motivo você criou aquele projeto, o que ele faz, quais ferramentas utilizou, o que é preciso para que utilizem e por aí vai. Como se esse  arquivo fosse o "cartão de visitas" do seu projeto.


## Os símbolos que utilizamos para estilização são:

- ##### HEADER - TÍTULOS

Para criar títulos utilizamos o símbolo "hashtag"(#). Para cada "hashtag"(#) adicionada definimos um nível para o título, que pode atingir o máximo de 6 "hashtags"(#), similar ao "h1" ao "h6" que temos no HTML. A ideia também é a mesma, organizar corretamente o conteúdo do site.

##### Exemplo:

# Título1
## Título2
### Título3
#### Título4
##### Título5
###### Título6

<img src="img/Header_M.PNG" alt="Marcação para títulos" title="Marcação para títulos"></br>
        <img src="img/Header_R.PNG" alt="Resultado de título em Markdown" title="Resultado de título em Markdown">

- ##### NEGRITO

Para estilizarmos o texto com **NEGRITO** utilizamos 2 asteriscos (*) ou 2 underlines (_), no início e no fim do texto. Assim, o que estiver entre os asteriscos (*) ou underlines(_) ficará em **NEGRITO**

##### Exemplo:

<img src="img/Bolder_M.PNG" alt="Marcação para negrito" title="Marcação para negrito"><br>
        <img src="img/Bolder_R.PNG" alt="Resultado de negrito em Markdown" title="Resultado de negrito em Markdown">

__Texto em Negrito__  
**Texto em Negrito**

- ##### ITÁLICO

Para estilizarmos o texto com <em>ITÁLICO</em> utilizamos 1 asterisco (*) ou 1 underline (_), no
            início e no fim do texto. Assim, o que estiver entre o asterisco (*) ou underline (_) ficará em <em>
                ITÁLICO</em>.</p>
        <h5>Exemplo:</h5>
        <img src="img/Italic_M.PNG" alt="Marcação para itálico" title="Marcação para itálico"><br>
        <img src="img/Italic_R.PNG" alt="Resultado de itálico em Markdown" title="Resultado de itálico em Markdown">


<h3>MISTURANDO AS COISAS</h3>
        <p>É possível utilizar a combinação de 2 underlines (_) e 1 asterisco (*) ou a combinação de 2
            asteriscos (*) e 1 underline (_) para estilizar o texto com <b><em>NEGRITO</em></b> e
            <b><em>ITÁLICO</em></b>.</p>
        <h5>Exemplo:</h5>
        <img src="img/Bold_Ita_M.PNG" alt="Marcação para negrito e itálico" title="Marcação para negrito itálico"><br>
        <img src="img/Bold_Ita_R.PNG" alt="Resultado de negrito e itálico em Markdown"
            title="Resultado de negrito e itálico em Markdown">

        <h3>RISCADO</h3>
        <p>Para estilizarmos o texto com <del>RISCADO</del> utilizamos 2 tils (~), no início e no fim do texto. Assim, o
            que estiver entre o til (~) ficará <del>RISCADO</del>.</p>
        <h5>Exemplo:</h5>
        <img src="img/Riscado_M.PNG" alt="Marcação para riscado" title="Marcação para riscado"><br>
        <img src="img/Riscado_R.PNG" alt="Resultado de riscado em Markdown" title="Resultado de riscado em Markdown">

        <h3>CITAÇÃO</h3>
        <p>Para adicionarmos uma citação utilizamos o símbolo de "maior" (>) no início da linha. Assim, o
            que estiver após o símbolo (>) será considerado uma citação.</p>
        <h5>Exemplo:</h5>
        <img src="img/Citação_M.PNG" alt="Marcação para citação" title="Marcação para citação"><br>
        <img src="img/Citação_R.PNG" alt="Resultado de citação em Markdown" title="Resultado de citação em Markdown">

        <h3>LINHAS HORIZONTAIS</h3>
        <p>Para adicionarmos Linhas Horizontais utilizamos asterisco (*), underline (_) ou hífen (-). O Markdown
            identifica uma linha horizontal a partir do terceiro caractere, com ou sem espaços.</p>
        <h5>Exemplo:</h5>
        <img src="img/LinhaHor_M.PNG" alt="Marcação para linha horizontal" title="Marcação para linha horizontal"><br>
        <img src="img/LinhaHor_R.PNG" alt="Resultado de linha horizontal em Markdown"
            title="Resultado de linha horizontal em Markdown">

        <h3>LISTA NÃO ORDENADA</h3>
        <p>Para criarmos listas não ordenadas utilizamos asterisco (*), adição (+) ou hífen (-) antes do item da lista.
            Para adicionarmos subitens a lista basta utilizar o TAB antes de cada símbolo.</p>
        <h5>Exemplo:</h5>
        <img src="img/UL_M.PNG" alt="Marcação para lista não ordenada" title="Marcação para lista não ordenada"><br>
        <img src="img/UL_R.PNG" alt="Resultado de lista não ordenada em Markdown"
            title="Resultado de lista não ordenada em Markdown">

        <h3>LISTA ORDENADA</h3>
        <p>Para criar uma lista ordenada basta adicionar um número e um ponto (.) qualquer antes do texto. O primeiro
            número que for adicionado a lista indicará onde ela começa, os números seguintes, estando em linhas
            consecutivas, vão continuar a sequência "automaticamente". Para adicionarmos subitens a lista basta utilizar
            o TAB antes de cada número.</p>
        <h5>Exemplo:</h5>
        <img src="img/OL_M.PNG" alt="Marcação para lista ordenada" title="Marcação para lista ordenada"><br>
        <img src="img/OL_R.PNG" alt="Resultado de lista ordenada em Markdown"
            title="Resultado de lista ordenada em Markdown">

        <h3>LINKS</h3>
        <p>Para adicionarmos um link utilizamos colchetes [] e parênteses (), onde o colchetes [] recebe a descrição do
            link e o parênteses recebe o endereço do link. Utilizando aspas duplas ("") é possível adicionar um texto
            alternativo, assim como no HTML. O texto deve ser inserido após o endereço do link. Podemos também criar um
            link utilizando 2 conjuntos de colchetes [], onde o primeiro recebe a descrição do link e o segundo recebe
            uma variável contendo o endereço do site. Essa variável precisa ser declarada previamente.</p>

        <h5>Exemplo:</h5>

        <img src="img/Link_M.PNG" alt="Marcação para link" title="Marcação para link"><br>
        <img src="img/Link_R.PNG" alt="Resultado de link em Markdown" title="Resultado de link em Markdown">

        <h3>IMAGENS</h3>
        <p>Para adicionar imagens utilizamos de sinal de exclamação (!), colchetes [] e parênteses. Entretanto, podemos
            fazer isso de 4 maneiras diferentes:</p>
        <ol>
            <li>
                <p>Simples!</p>
                <img src="img/Simples_M.PNG" alt="Marcação para imagens" title="Marcação para imagens"><br>
            </li>
            <li>
                <p>Declarando variável para imagem!</p>
                <img src="img/VarImg_M.PNG" alt="Marcação para imagens com variável"
                    title="Marcação para imagens com variável"><br>
            </li>
            <li>
                <p>Imagem com link!</p>
                <img src="img/LinkImg_M.PNG" alt="Marcação para imagens com link"
                    title="Marcação para imagens com link"><br>
            </li>
            <li>
                <p>Declarando variável para imagem e link!</p>
                <img src="img/ImgLinkVar_M.PNG" alt="Marcação para imagens com variável para link e imagem"
                    title="Marcação para imagens com variável para link e imagem"><br>
            </li>
        </ol>

        <h3>TABELA</h3>
        <p>Para criamos tabelas utilizamos o símbolo pipe ( | ). Com ele separaremos as colunas da tabela. As linhas são
            criadas após de maneira "automatica" conforme pressionamos ENTER e inserimos um novo conjunto de pipe ( | ).
            Para definirmos o alinhamento de cada coluna utilizamos a seguinte configuração:</p>
        <ul>
            <li>Para alinhamento a ESQUERDA utilizamos dois pontos (:) seguidos de hífen (-) <b>|:-|</b></li>
            <li>Para alinhamento a DIREITA utilizamos hífen (-) seguido de dois pontos (:) <b>|-:|</b></li>
            <li>Para alinhamento a CENTRALIZADO utilizamos dois pontos (:), hífen (-) e dois pontos (:) novamente
                <b>|:-:|</b></li>
        </ul>
        <h5>Exemplo:</h5>
        <img src="img/Tabela_M.PNG" alt="Marcação para tabela" title="Marcação para tabela"><br>
        <img src="img/Tabela_R.PNG" alt="Resultado de tabela em Markdown" title="Resultado de tabela em Markdown">

        <h3>BLOCO DE CÓDIGO</h3>
        <p>Para inserirmos um bloco de código utilizamos a crase (`). Ela transforma o texto inserido em bloco de
            código. Basta utilizar uma no início e no fim da linha de código. Caso precise de utilizar em mais linha, ou
            seja, em um bloco selecione o bloco e use o tecla TAB ou faça uso de 3 crases (```) no início e no fim do
            bloco, sem espaço entre elas. Lembre que não podemos misturar duas ou mais linguagens em um mesmo bloco de
            código. Para isso devemos criar dois blocos de códigos separados. Podemos também estilizar o bloco de código
            utilizando a Syntax Highlighting, adicionando o nome da linguagem apresentada no bloco logo após a 3ª crase.
        </p>
        <h5>Exemplo:</h5>
        <img src="img/Bloco_M.PNG" alt="Marcação para bloco de código" title="Marcação para bloco de código"><br>
        <img src="img/Bloco_R.PNG" alt="Resultado de bloco de código em Markdown"
            title="Resultado de bloco de código em Markdown">

        <h3>FUGINDO DA ESTILIZAÇÃO</h3>
        <p>Vimos que os símbolos são utilizados para tratar da estilização do texto, mas como faremos se quisermos mostrar
            exatamente o símbolo sem seu efeito de formatação? Nesse caso, temos que fazer uso da barra invertida (\) antes do símbolo. Com isso, seu efeito de formatação é "cancelado".</p>
        <h5>Exemplo:</h5>
        <img src="img/SemSimb_M.PNG" alt="Texto sem estilização" title="Texto sem estilização"></br>
        <img src="img/SemSimb_R.PNG" alt="Texto sem estilização" title="Texto sem estilização">

        <h3>E MAIS...</h3>

        <p>Lá no <a href="githhttps://github.com/" title="Site GitHUB">GITHUB</a>, exato, lá mesmo. Podemos criar checkboxes que utilizamos para montar listas de tarefas além de
            referências de <em>issues</em> e/ou <em>pull requests</em> utilizando apenas uma "hastag" (#) e o nome da
            issues / pull request. É possível mencionar usuários nos comentários utilizando o arroba (@). Dá pra utilizar
            até <em>emojis</em>. Também é possível utilizar todos as outras estilizações mostradas
            aqui.</p>
        <h5>Exemplo:</h5>
        <img src="img/ListC_M.PNG" alt="Marcação no GitHUB" title="Marcação no GitHUB"><br>
        <img src="img/ListC_R.PNG" alt="Resultado no GitHUB" title="Resultado no GitHUB">
        <h3>Mas como vou decorar os códigos dos emojis?!?</h3>
        <p>Não se preocupe, aqui segue um site com lista de diversos emojis para utilizar: <a
                href="https://www.webfx.com/tools/emoji-cheat-sheet/" alt="Site com código de emojis"
                title="Site com códigos para emojis">EMOJIS</a></p>

        <p>Bem, espero que esse conteúdo lhe ajude de alguma forma! Se puder, compartilhe com mais pessoas. Repasse o conhecimento! Forte abraço e LET's CODE!</p>
    </main>
    <!--MAIN_FIM-->

    <!--FOOTER_FIM-->
    <footer id="rodape">
        <a href="#top" alt="Para o topo" title="Para o topo"><img src="img/UP.png"></a>
        Ícones feitos por <a
            href="https://www.flaticon.com/br/icone-gratis/seta-para-cima_2923177?term=seta%20para%20cima&page=1&position=53"
            title="Vitaly Gorbachev">Vitaly Gorbachev</a> from <a href="https://www.flaticon.com/br/" title="Flaticon">
            www.flaticon.com</a>
        Criado por Diego Augusto Pedro
        Atualizado em 29/05/2020
    </footer>
    <!--FOOTER_FIM-->
</body>

</html>

















Apenas um underline (_) ou um asterisco (*) transformam a palavra MARKDOWN em itálico.

Dois tils (~) transforma a palavra MARKDOWN em riscado.

O sinal de maior (>) cria um bloco de citação.

É possível utilizando a combinação de dois underlines (_) e um asterisco (*) ou a combinação de dois asteriscos (*) e um underline (_).

Os caracteres utilizados para criar linhas horizontais são asteriscos (*), underline (_) e traços (-). 

O Markdown identifica uma linha horizontal a partir do terceiro caractere.

Você pode espaçar desde que tenha pelo menos 03 caracteres.

Correto, adicionando um TAB ou dois espaços na frente do tem, o Markdown identifica como subitem.

Lista ordenada
Basta adicionar os números antes dos items para transformá-los em uma lista ordenada.

O resultado será uma lista com 03 items, numerados de 1 à 3, pois o Markdown ignora a continuação da lista.

link
O correto é utilizar colchetes para o texto que será exibido no link e parênteses para o endereço do link.

O texto alternativo deve ser inserido após o endereço do link dentro de aspas duplas.

Podemos utilizar variáveis utilizando colchetes.

Imagens
Precisamos adicionar o sinal de exclamação (!) no início.

Da mesma forma que os links, podemos utilizar colchetes para utilizar variáveis.
imagem com link
Devemos envolver a imagem dentro de colchetes e adicionar o endereço do link dentro de parênteses,mas fora dos colchetes.

Tabelas
O pipe separa as colunas.

Alinhamento do texto na tabela
Para alinhar ao centro, devemos utilizar | :-: |.

Bloco de códigos
Crase transforma o texto em bloco de código.
É necessário adicionar 03 crases no início e no fim do bloco.
Não podemos misturar duas ou mais linguagens em um mesmo bloco de código. Para isso devemos criar dois blocos de códigos separados.

Dentro do GITHUB Exato, ele permite a criação de checkboxes, referências de issues e pull requests e até emojis.

Praticando Markdown - Baseado no curso de Roberto Achar - Markdown pela Udemy
