# Formação Frontend Alura: Acessibilidade Web

# Acessibilidade web parte 1: tornando seu front-end inclusivo
### Iniciado em 06/02/2022
### Finalizado em 15/02/2022

### Aula 01
- [x] Que pessoas cegas ou com baixa visão podem contar com o auxílio de um software que lê o conteúdo exibido na tela, estes recebem o nome de leitores de tela.
- [x] Vimos, configuramos e aprendemos atalhos do NVDA, leitor de tela escolhido para testar o projeto Apeperia, a fim de deixar seu uso em testes menos maçante para quem não está acostumado com a ferramenta. E também habilitamos seu "exibidor de tela" para não dependermos de ouvir sua leitura.
- [x] Tomar cuidado com a marcação de conteúdo quando estamos utilizando elementos HTML5. Vale mais por uma div do que usar um aside ou details erroneamente.
- [x] O melhor caminho para deixar nosso projeto inclusivo não é apenas seguir regras e guidelines, mas testá-las por conta para começarmos a compreender os caminhos e dificuldades que muitas pessoas podem ter ao usar nosso produto e/ou serviço. Empatia.

### Aula 02
- [x] Alt nas imagens que possuem função de conteúdo;
- [x] Escrever o alt de maneira descritiva, evitando redundâncias;
- [x] Configurar o idioma principal do documento com o atributo lang;
- [x] Colocar o elemento title em SVGs que forem inline (código direto no HTML).

### Aula 03
- [x] Css pode impactar no leitor de tela
- [x] Como ocultar inputs nativos para priorizar inputs personalizados, sem usar display: none ou visibility: hidden, pois ambas propriedades fazem com que o leitor ignore o input personalizado
- [x] Elementos como list style são lidos pelo leitor de tela

### Aula 04
- [x] como utilizar o atributo role para mudar a semantica do html 
- [x] Uso do wai aria, no caso o labelled-by com o id de uma figure para indicar que aquele elemento é "empacotado" e definido pelo conteúdo indicado

### Aula 05
- [x] Como trabalhar com formulários acessíveis, usando label for para ligar a label ao seu input
- [x] Como desabilitar campos e ainda deixa-los acessíveis ao leitor de tela, utilizando os atributos readonly e disabled juntos
- [x] Inserindo videos via html e legendas utilizando as tags semanticas video para o video e track para as legendas

## Anotações gerais 

### Comandos do NVDA
- Tecla = navega para frente | Shift+Tecla = navega para trás
- Tecla K faz navegação proximos links
- Tecla H faz navegação entre headers/cabeçalhos
- Tecla G faz navegação entre imagens
- Tecla L faz navegação entre listas
- Caps lock+ctrl+seta cima ou baixo para aumentar ou diminuir volume do leitor

### Dicas
- É possivel usar o atributo lang="en" por exemplo para frases em outras linguas, no caso, inglês
- Não precisa usar os atributos alt e title ao mesmo tempo
- O css pode sim influenciar no leitor de tela, como um list-style por exemplo
- IMPORTANTE! Para inputs personalizados(tipo checkbox) o display none irá fazer com q o leitor de tela ignore o elemento, portanto use a gambiarra de um left: -9999px, position: absolute, opacity:0 
- Podemos usar um link âncora href="#id-seção" para que o leitor de tela pule direto para determinado contéudo quando clicado

# Acessibilidade web parte 2: Componentes acessíveis com um pouco de JavaScript
### Iniciado em 16/02/2022

### Aula 01
- [x] Como esconder visualmente elementos na página, porém ainda deixa-los acessiveis pelo leitor de tela usando o css (no caso a classe escondeVisualmente)
- [x] Em list style, podemos deixar as bolinhas (disc) visiveis na tela e no leitor de tela, pois usuários cegos já estão acostumados 
- [x] Questionamento se há ou não a necessidade de colocar textos em imagens meramente ilustrativas, deixando o alt vazio ou inserindo um texto alternativo se realmente você quer dar destaque aquela imagem 