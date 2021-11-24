# Atividades - Programação WEB


## **5 DE AGOSTO/10 DE AGOSTO**

ATIVIDADE 01
- Atualmente estou utilizando o navegado Opera GX, os principais motivos para utilizar ele seriam duas funções que eu considero muito interessantes, que seriam a limitação de quantidade de memoria RAM que o navegador pode utilizar (importante para quando eu estiver executando alguma aplicação mais pesada e usando o navegador ao mesmo tempo) e um limitador de quantidade de banda de internet que o navegador pode fazer uso (interessante para quando eu estiver fazendo algum download e vendo vídeos pesados no youtube, por exemplo). Duas características que me deixam um pouco decepcionado seriam o serviço de VPN fornecido pelo próprio navegador, que não é muito interessante, e algumas personalizações extras que não estão presentes, para deixar a aparência do navegador mais agradável aos meus olhos.
- A história da criação da web começa anos atrás, mais precisamente, teve início em 1980, com o inglês Tim Berners desenvolveu o que foi chamado de QNQUIRE, projeto que teve o objetivo de fazer o reconhecimento e armazenamento de associações de informações. Após diversos anos conturbados na vida de Tim, em 1990, ele criou o Protocolo de Transferência de Hipertexto, o HTTP, e o HTML, como também o primeiro browser, chamado WorlWideWeb. A partir daí, diversas evoluções foram acontecendo, até chegarmos na Web que conhecemos hoje.
- A guerra dos navegadores web foi um período muito interessante da história, ela foi ter seu início quando a empresa responsável pelo browser Netscape viu sua liderança em browsers ter sido ultrapassada pela Microsoft com o famosíssimo Internet Explorer. Foi um período intenso, visto que processos judiciais aconteceram, e as duas empresas estavam em uma incessante briga pelo maior número de usuários. Outros navegadores surgiram de todo esse conflito, os que melhor se destacam seriam o Opera e o navegador da Mozila
- A lista é extensa, mas dentre os principais navegadores que respeitam as 4 liberdades de softwares livres podem ser citados o Opera, o Firefox e o Konqueror


ATIVIDADE 02
- A utilização das tags ```<b>``` e ```</b>``` transformaram o texto para modo negrito.
- Inspecionando o código fonte foi informado o código HTML da página.
- Deve ser utilizada a tag ```<html>``` e ```</html>```.


ATIVIDADE 03
- 1º ```<html></html>``` = Abrindo e fechando a tag HTML na mesma linha. O correto seria abrir e somente fechar no final do código.
- 2º ```<h1>```Essa é uma marcação para ```<b>```títulos```</h1>``` = tag ```<b>``` não foi fechada, o correto seria fechá-la depois da palavra “títulos”.
- 3º ```<p>```Essa é a marcação para um parágrafo com ```<b>```negrito e ```<i>```itálico```</i></b></p>```. = tags estão sendo fechadas todas no final, o correto seria fechar elas após o termo correspondente que se quer transformar.
- 4º A tag ```<head>``` não foi fechada. Toda tag, quando aberta, deve ser fechada.

ATIVIDADE 04
- As mudanças realizadas foram na cor do texto, na fonte utilizada e no tamanha do texto. Isso auxilia na criação de páginas HTML por conta da infinidade de possibilidades de customização da página, com diversas fontes, cores e tamanhos.
  
ATIVIDADE 05
```
<html>
<body>
<h1>Artur Santana Mendanha</h1>
<h2> Dados pessoais</h2>
<p>Nasci em 13/05/2002</p>
<p>Estou cursando ciências da computção</p>
</body>
</html>
```

## **2 DE SETEMBRO**

ATIVIDADE 01
- 1º ```<html></html>``` = Abrindo e fechando a tag HTML na mesma linha. O correto seria abrir e somente fechar no final do código
- 2º ```<h1>```Essa é uma marcação para ```<b>```títulos```</h1>``` = tag ```<b>``` não foi fechada, o correto seria fechá-la depois da palavra “títulos”
- 3º ```<p>```Essa é a marcação para um parágrafo com ```<b>```negrito e ```<i>```itálico```</i></b></p>```. = tags estão sendo fechadas todas no final, o correto seria fechar elas após o termo correspondente que se quer transformar
- 4º A tag <head> não foi fechada. Toda tag, quando aberta, deve ser fechada.
  
ATIVIDADE 02
- As mudanças realizadas foram na cor do texto, na fonte utilizada e no tamanha do texto. Isso auxilia na criação de páginas HTML por conta da infinidade de possibilidades de customização da página, com diversas fontes, cores e tamanhos. ```
  
## **9 DE SETEMBRO**
  
ATIVIDADE 01

```
<html>
<head>
	<style type="text/css">
    	body {
            background-image: url("https://i.imgur.com/0hB1iqW.png");
            background-repeat: no-repeat;
            background-position: top-right
        }
    	h1 {
        	background-color: blue;
        }
        h2 {
        	background-color: blue;
        }
    	p {
        	background-color: blue;
        }
    </style>
    
<body>
<h1> Artur Santana Mendanha </h1>
<h2> Dados pessoais </h2>
<p> Nasci em 13/05/2002< /p>
<p> Estou cursando Ciência da Computação </p>
</body>
</html> 
  
```
  
ATIVIDADE 02
```
<html>
<head>
	<style type="text/css">
    	body {
            background-image: url("https://i.imgur.com/0hB1iqW.png");
            background-repeat: no-repeat;
            background-position: top-right
        }
    	h1 {
        	background-color: blue;
        }
        h2 {
        	background-color: blue;
        }
    	p {
        	background-color: blue;
        }
        a:link {
        	color: green;
            text-decoration: underline;
            font-family: Arial;
        }
        a:link {
        	color: pink;
            text-decoration: underline;
            font-family: Courier;
        }
        a:active {
        	color: yellow;
            text-decoration: underline;
            font-family: Verdana;  
        }
        
    </style>
    
<body>
<h1> Artur Santana Mendanha </h1>
<h2> Dados pessoais </h2>
<p> Nasci em 13/05/2002< /p>
<p> Estou cursando Ciência da Computação </p>
<a href="file:///C:/Users/santana/Desktop/meusite.html/">
        Meu link personalizado
    </a>
</body>

</html>
```
  
ATIVIDADE 01
As três propriedades que podem ser utilizadas seriam o nome da cor, o seu valor em hexadecimal, ou o seu valor dentro do sistema RGB.
  
```
<html>
<head>
	<style type="text/css">
    	body {
            background-image: url("https://i.imgur.com/0hB1iqW.png");
            background-repeat: no-repeat;
            background-position: top-right
        }
    	h1 {
        	background-color: blue;
        }
        h2 {
        	background-color: blue;
        }
    	p {
        	background-color: blue;
        }
        a:link {
        	color: green;
            text-decoration: underline;
            font-family: Arial;
        }
        a:link {
        	color: #FFCBDB;
            text-decoration: underline;
            font-family: Courier;
        }
        a:active {
        	color: #FFFF00;
            text-decoration: underline;
            font-family: Verdana;  
        }
        
    </style>
    
<body>
<h1> Artur Santana Mendanha </h1>
<h2> Dados pessoais </h2>
<p> Nasci em 13/05/2002< /p>
<p> Estou cursando Ciência da Computação </p>
<a href="file:///C:/Users/santana/Desktop/meusite.html/">
        Meu link personalizado
    </a>
</body>

</html>
```
  
ATIVIDADE 02
- O círculo é denominado como uma paleta de cores que apresenta doze cores em sua composição. Dentre essas cores, três são primárias, três são cores secundarias, e as seis restantes são cores terciarias. A paleta tem por definição um conjunto de diversas cores, separadas de maneira harmônica entre elas
- Uma boa paleta de cores é de extrema importância, pois o usuário, ao acessar o site, deve ter uma visão mais confortável possível da interface gráfica, sem causar nenhum desconforto aos seus olhos
- Escolhi cores mais frias, perto da cor azul, pois, na minha visão, e considerando a paleta de cores, são cores que transmitem um maior sentimento de “acolhimento”, o usuário não se sente desconfortável
- Não me agradam: 
	Google Classroom: O site mistura muitas cores, na seleção de turmas, cada turma possui uma cor diferente, muitas vezes não harmônica, deixa a visualização confusa.
	Aliexpress: A paleta do site é muito diversificada, as vezes, diversificada até demais, cada item na tela acaba recebendo uma cor diferente do seguinte, juntando com a quantidade de itens apresentados na mesma tela, cria uma sensação de confusão no usuário
- Me agradam:
	Espaço aluno: A paleta de cores do site me agradou bastante, a mistura do roxo com o amarelo é, na minha opinião, bastante atraente. São duas cores que se intercalam bem e criam uma boa e confortável visão ao usuário
	Google: o buscador apresenta uma paleta bastante sóbria e simples, até minimalista. Porém isso é o que me interessou ainda mais no site, ele propõe uma visão confortável e simples, direto ao ponto.
- A paleta mais harmoniosa foi a azul claro, como relatado anteriormente. 

## **14 DE SETEMBRO**

ATIVIDADE 01
- 1º	O resultado é diferente pois o parágrafo 3 usa a classe “absolute” e se encontre embaixo de uma classe “relative”. Assim o parágrafo anterior o sobrepõe
- 2º	
```
HTMLResult Skip Results Iframe
EDIT ON
<html>
<head>
<style>
p.solid {border-style: solid;}
</style>
<title>Exemplo de posicionamento</title>
<style type="text/css">
p {
padding: 20px 20px20px20px;
background-color:#cc9;
}
p.fixed {
position:fixed;
right:10px;
width:250px;
}
p.static {
position:static;
width:250px;
}
p.absolute{
position:absolute;
right:30px;
width:60%;
z-index:1;
}
p.relative{
position:relative;
width:60%;
}
</style>
</head>
<body>
<img src="https://tm.ibxk.com.br/2021/09/17/17083943806023.jpg?ims=1120x420" alt="some text" width=100 height=30>
<h1>Exemplos de posicionamento de elementos</h1>
<p class="static, solid">Parágrafo 1 – Este parágrafo está estilizado com "position:fixed" e  "right:10px". Isso faz com que ele seja posicionado a 10px da direita e não role na página. </p>
<p class="static, solid">Parágrafo 2 – Este parágrafo está estilizado com "position:static". Essa propriedade não precisa ser escrita porque todos os elementos são estáticos por default. Ele está aparecendo ao lado do parágrafo fixed porque fixed permite a sobreposição de elementos e ignora o fluxo descrito no (X)HTML.</p>
<p class="static, solid">Parágrafo 3 – Este parágrafo está estilizado com "position:absolute;" e "right:20px;". Esse método faz com que o parágrafo posterior sobreponha-o. </p>
<p class="static, solid">Parágrafo 4 – Este parágrafo está estilizado com "position:relative;". Esse método não ignora o fluxo dos elementos, mas permite a sobreposição. Assim, como o parágrafo anterior usa o método de posição absolute, este aparece por cima do parágrafo 
3.</p>
</body>
</html>
```


		





