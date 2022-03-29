# flexbox_css
Repositório ref curso Flexbox com CSS da Dio.

# Objetivo da aula

 - Conhecer a estrutura básica
 - Entender a diferença entre Flex Container e Flex Item
 - Conhecer inicialmente algumas propriedades.


#Suporte
Foi projetado como um layout unidimensional e como um método que pode oferecer distribuição de espaço entre itens em um interface e recursos de alinhamento.

# Flex container

É a tag que envolve os itens, será nela que iremos a aplicar a propriedade "display flex". Transforma todos os seus itens filhos em flex itens.

### Propriedade relacionada
 - display
 - flex-direction
 - flex-wrap
 - flex-flow 
 - justify-content
 - align-items
 - align-content

# Flex Item
São os elementos filhos diretos do Flex Container. E também podem se tornar Flex Container.

![Flex-Itens](https://arquivo.devmedia.com.br/artigos/Fernando_gaspar/flex/alinhamento.png)

 - **Tamanho principal:** É a dimensão do elemento na direção do eixo principal (largura, caso horizontal e altura caso vertical);
 - **Tamanho transversal:** É a dimensão do elemento na direção do eixo transversal (largura, caso horizontal e altura caso vertical);
 - **Início principal e final principal:** Representam o início e o fim do eixo principal;
  - **Início transversal e final transversal:** Representam o início e o fim do eixo transversal.


### Propriedades relacionadas
 - flex-grow
 - flex-basis
 - flex-shrink
 - flex
 - order
 - align-self

# Display Flex
Torna a tag um elemento do tipo flex container, e assim automaticamente todos os seus filhos diretos desta tag, tarnam-se em flex items.

# Flex-direction
É a propriedade que estabelece o eixo principal do container, definindo assim a direção que os flez items são colocados no flex container.

### Os eixos
- row(padrão): a direção do texto, esquerda para direita.
- row-reverse: sentido oposto à direção do texto
- column: ordenação de cima para baixo, em unica coluna.
- column-reverse: ordenação inversa, de baixo para cima.


# Flex-Wrap
 É a propriedade que define de os itens devem ou não quebrar a linha.
 Por padrão eles não quebram linhas, isso faz com que os flex itens sejam compactados além do limite do conteúdo.


#### nowrap
é o padrão, não permite a quebra de linha
#### wrap
permite a quebra de linha assim que um dos flex não puder mais ser compactado.
#### wrap-reverse
permite a quebra de linha assim que um dos flex itens não puder mais ser compactado, porém na direção contrária da linha.




