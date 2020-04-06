# HTML5

É uma linguagem de marcação que tem as seguintes responsabilidades:

- Conteúdo (texto, imagem, vídeo);
- Semântico (utilizar as tags de forma correta);
- Estrutura

* `<h1>`- heading 1 - 6
Usado para definir títulos

- `<a>`- Link (a - anchor)
Usado para definir a navegação do usuário: faz o texto virar um link. Usa-se junto com o atributo `href`(não esquecer q o atributo deve estar na tag de abertura)
```
< a href="http://collabcode.training">CollabCode.Training</a>
```

- `<head>`- Parte da "configuração"(não ficará visível para o usuário)

- `<body>`- Corpo - O que ficará visível para o usuário

- `<header>`- cabeçário



# CSS

É uma linguagem de estilo.  Responsabilidades:

- Visual;

`reset`serve para tirar os diferentes comportamentos de cada browser, para padronizar o modo de visualização em qualquer browser
```
<link rel="stylesheet" href="reset.css">
```
(código copiado de Erik Meyer e salvo como reset.css) - lembrar de colar o reset antes, para que ele não sobreponha qualquer alteração que seja feita depois

- FLOAT 
    - É criado um novo contexto (o pai ignora o filho);
    - O elemento vai para a camada da frente (eixo z);
    - O elemento que está flutuando NUNCA esconde um conteúdo;
    - O tamanho do elemento passa a ser o tamanho do conteúdo

```
youtube.com/c/collabcode - pare de chutar e aprenda as propriedades
```

`paddings`- respiro interno
`margin`- respiro externo

`paddings`- top right bottom left
Configuração da ordem dos paddings (separados apenas por espaço)

`position: absolute` - propriedade parecida com o float, usada para criar um novo contexto para o elemento
    Esta propriedade nos possibilita movimentar o elemento na tela, usando os seguintes comandos:

`top:50%`- move o elemento a 50% do topo (porém, o elemento fica posicionado na metade do browser em relaçao ao topo)
`transform:translateY()`- deixa o elemento verticalmente alinhado pelo meio
`right:50%`- move o elemento a 50% da direita (porém, o elemento fica posicionaado na metade do browser em relação à esquerda do browser)
`transform:translateX()`- deixaaa o elemento horizontalmente alinhado pelo meio





