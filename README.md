<hr>
<h2>Css Flexbox</h2>
<h3>Galeria de fotos</h3>

<img src="/images/Photo-Gallery.png">
<hr>

<h4>Passo 1</h4>
<p>- Comece com seu clichê HTML padrão. Adicione uma declaração DOCTYPE, um elemento html, um elemento head e um elemento body.
Adicione o atributo lang à tag de abertura <html> com en definido como o valor.</p>

<h4>Passo 2</h4>
<p>- No elemento head, adicione uma meta tag com o nome definido como viewport e o conteúdo definido como width=device-width, initial-scale=1.
Adicione também uma meta tag com o conjunto de caracteres definido como UTF-8.</p>

<h4>Passo 3</h4>
<p>- No elemento head, adicione um elemento title com o texto definido como Galeria de fotos e um elemento link para adicionar seu arquivo styles.css à página.</p>

<h4>Passo 4</h4>
<p>- Adicione um elemento de cabeçalho dentro do elemento de corpo e atribua uma classe de cabeçalho a ele.
Dentro do cabeçalho, crie um h1 com a galeria de fotos css flexbox como texto.</p>

<h4>Passo 5</h4>
<p>- Abaixo do elemento .header, crie um novo elemento div e atribua a ele uma classe de galeria. Este div atuará como um contêiner para as imagens da galeria.Dentro desse elemento .gallery, crie nove elementos img.</p>

<h4>Passo 6</h4>
<p>- Em seguida, dê a cada img um atributo src de acordo com sua ordem no documento. A primeira img deve ter um src de https://cdn.freecodecamp.org/curriculum/css-photo-gallery/1.jpg. O resto deve ser o mesmo, exceto substituir o 1 pelo número que a img está no documento.</p>

<h4>Passo 7</h4>
<p>- Normalize seu modelo de caixa criando um seletor * e definindo a propriedade box-sizing como border-box como o valor.</p>

<h4>Passo 8</h4>
<p>- Suas imagens são muito grandes. Crie um seletor de img .gallery para direcioná-los. Dê a todos uma largura de 100% e uma largura máxima de 350px para que encolham conforme necessário, mas não fiquem muito grandes. Defina também a propriedade height como 300px para manter suas imagens em um tamanho uniforme.</p>

<h4>Passo 9</h4>
<p>- Remova a margem do elemento do corpo, defina a família da fonte como sem serifa e dê a ela uma cor de fundo de #f5f6f7 como valor.</p>

<h4>Passo 10</h4>
<p>- Alinhe o texto do cabeçalho no centro. Torne o texto em letras maiúsculas usando a propriedade text-transform com letras maiúsculas como o valor. Dê um preenchimento de 32px em todos os lados. Defina o plano de fundo como #0a0a23 e o texto como #fff como valores de cor. Adicione uma borda inferior com sólido de 4px #fdb347 como valor.</p>

<h4>Passo 11</h4>
<p>- Flexbox é um layout CSS unidimensional que pode controlar a maneira como os itens são espaçados e alinhados dentro de um contêiner. Para usá-lo, dê a um elemento uma propriedade de exibição de flex. Isso tornará o elemento um contêiner flexível. Quaisquer filhos diretos de um flex container são chamados de flex items. Crie um seletor .gallery e torne-o um contêiner flexível.</p>

<h4>Passo 12</h4>
<p>- Flexbox é um layout CSS unidimensional que pode controlar a maneira como os itens são espaçados e alinhados dentro de um contêiner.
Flexbox tem um eixo principal e transversal. O eixo principal é definido pela propriedade flex-direction, que possui quatro valores possíveis:

linha (padrão): eixo horizontal com itens flexíveis da esquerda para a direita
row-reverse: eixo horizontal com itens flexíveis da direita para a esquerda
coluna: eixo vertical com itens flexíveis de cima para baixo
column-reverse: eixo vertical com itens flexíveis de baixo para cima
Nota: Os eixos e direções serão diferentes dependendo da direção do texto. Os valores mostrados são para uma direção de texto da esquerda para a direita.

Experimente os diferentes valores para ver como eles afetam o layout. Quando terminar, defina uma direção flexível explícita de linha no elemento .gallery.</p>

<h4>Passo 13</h4>
<p>- A propriedade flex-wrap determina como seus itens flexíveis se comportam quando o contêiner flexível é muito pequeno. Defini-lo como encapsulamento permitirá que os itens sejam encapsulados na próxima linha ou coluna. nowrap (padrão) impedirá que seus itens sejam embrulhados e os encolha, se necessário.
Faça com que seus itens flexíveis passem para a próxima linha quando ficarem sem espaço.</p>

<h4>Passo 14</h4>
<p>- A propriedade justify-content determina como os itens dentro de um flex container são posicionados ao longo do eixo principal, afetando sua posição e o espaço ao redor deles. Dê ao seu seletor .gallery uma propriedade de conteúdo justificado com centro como o valor.</p>

<h4>Passo 15</h4>
<p>- A propriedade align-items posiciona o conteúdo flexível ao longo do eixo transversal. Nesse caso, com sua direção flexível definida como linha, seu eixo transversal seria vertical. Para centralizar verticalmente suas imagens, dê ao seu seletor .gallery uma propriedade align-items com center como o valor.</p>

<h4>Passo 16</h4>
<p>- Dê ao seu seletor .gallery uma propriedade de preenchimento definida como 20px 10px para criar algum espaço ao redor do contêiner.
Em seguida, dê a ele uma largura máxima de 1400px e adicione uma margem de 0 auto para centralizá-lo.</p>

<h4>Passo 17</h4>
<p>- Observe como algumas de suas imagens ficaram distorcidas. Isso ocorre porque as imagens têm diferentes proporções. Em vez de definir cada proporção individualmente, você pode usar a propriedade de ajuste de objeto para determinar como as imagens devem se comportar. Dê ao seu seletor img .gallery a propriedade object-fit e defina-a como cover. Isso fará com que a imagem preencha o contêiner img enquanto mantém a proporção, resultando em corte para caber.</p>

<h4>Passo 18</h4>
<p>- Suas imagens precisam de algum espaço entre elas. A propriedade abreviada CSS gap define as lacunas, também conhecidas como calhas, entre linhas e colunas. A propriedade gap e suas subpropriedades row-gap e column-gap fornecem essa funcionalidade para layout flexível, de grade e de várias colunas. Você aplica a propriedade ao elemento container. Dê ao seu contêiner flexível .gallery uma propriedade gap com 16px como o valor.</p>


<h4>Passo 19</h4>
<p>- Suavize um pouco suas imagens dando ao seletor .gallery img uma propriedade border-radius com 10px definido como o valor.</p>


<h4>Passo 20</h4>
<p>- O pseudo-elemento ::after cria um elemento que é o último filho do elemento selecionado. Você pode usá-lo para adicionar um elemento vazio após a última imagem. Se você der a mesma largura que as imagens, ela empurrará a última imagem para a esquerda quando a galeria estiver em um layout de duas colunas. No momento, está no centro porque você configurou justify-content: center no flex container.

Exemplo:

.container::após {
   contente: "";
   largura: 860px;
}
Crie um novo seletor usando um pseudo-elemento ::after no elemento .gallery. Adicione uma propriedade de conteúdo definida como uma string vazia "" e 350px definido para a propriedade de largura.</p>


<h4>Passo 21</h4>
<p>- O atributo alt image deve descrever o conteúdo da imagem. Os leitores de tela anunciam o texto alternativo no lugar das imagens. Caso a imagem não possa ser carregada, este texto é apresentado no lugar da imagem. Para concluir o projeto, adicione um atributo alt a todas as nove imagens de gatos para descrevê-las. Use um valor de pelo menos cinco caracteres para cada.</p>