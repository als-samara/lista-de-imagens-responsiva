# Responsividade em Lista de Imagens

Este projeto demonstra a criação de uma lista de imagens responsiva e a centralização de elementos usando HTML e CSS. O objetivo foi desenvolver uma exibição de imagens adaptável a diferentes tamanhos de tela e centralizar os elementos na página.

## Como Funciona

### Estrutura do Projeto

- `index.html`: Arquivo HTML que contém a estrutura da página.
- `reset.css`: Arquivo CSS que reseta os estilos padrões aplicados pelo navegador.
- `styles.css`: Arquivo CSS que define o estilo da página da lista de imagens.
- `responsive.css`: Arquivo CSS que define a responsividade da lista de imagens.

### Responsividade

O arquivo `response.CSS` contém consultas de mídia (`@media`) para diferentes tamanhos de tela, garantindo que a lista de imagens se ajuste adequadamente. Aqui estão algumas configurações chave:

```css
@media(max-width: 1440px){
    .image-list{
        max-width: 900px;
        margin: 30px 0;
        gap: 0;
    }
}
```
Para telas menores ou até 1440px, a largura máxima da lista de imagens é ajustada para 900px, com margens e espaçamento específicos.

### Centralização de Elementos
A classe `.main-content` do arquivo `style.css` é responsável por centralizar o conteúdo na página usando flexbox:

```css
.main-content{
    display: flex;
    min-height: 100vh;
    justify-content: center;
    align-items: center;
}
```
Os elementos são alinhados vertical e horizontalmente usando as propriedades `justify-content` e `align-items`.

### Estilo das Imagens e Legendas
A lista de imagens é exibida em um layout flexível, usando `flex-wrap` e `gap` para garantir um espaçamento uniforme entre as imagens.
O tamanho das imagens é definido em `width: 335px` e `height: 430px`, mas ajusta-se conforme a largura da tela devido a `max-width: 100%`.
As legendas das imagens têm estilos específicos de fonte, cor e tamanho para melhor legibilidade.

### Como Utilizar
Faça o download ou clone este repositório.
Abra o arquivo `index.html` em um navegador web para visualizar a lista de imagens responsiva e centralizada.

### Recursos Adicionais
`public sans` é a fonte utilizada para o texto. Certifique-se de ter acesso a esta fonte ou substitua-a por outra de sua preferência.
Sinta-se à vontade para explorar e modificar o código conforme necessário para testar diferentes funcionalidades ou estilos. 
Para usar o projeto, faça um fork do repositório u envie uma sugestão por meio de um pull request.

### Contatos
[![Me envie um e-mail](https://img.shields.io/badge/Email-samaraalmeida379@gmail.com-red)](mailto:samaraalmeida379@gmail.com)<br>
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Me_envie_uma_mensagem!-blue)](https://www.linkedin.com/in/samara-almeida-als/)

### Deploy
Veja o deploy do Projeto [aqui](https://als-samara.github.io/lista-de-imagens-responsiva/).




