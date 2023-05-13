# README e .gitignore: dois arquivos importantes e conhecidos


[Voltar](./README.md)

Se você entrar em alguns repositórios famosos, como o do [React](https://github.com/facebook/react) ou outros [exemplo pessoal](https://github.com/valencprado/nlw-setup), deve ter reparado que existe uma explicação visual deste repositório em forma de texto. Interessante, né? Mas como esse arquivo é feito? Além disso, há outro arquivo importante, exibido logo quando um novo repositório é criado: o **.gitignore**. Esse arquivo falará brevemente sobre esses e ainda mais!


## LEIA-ME! O README

O README é um arquivo em **Markdown** (extensão .md), uma linguagem de marcação (que é a mesma em que esses arquivos são escritos). Deixo aqui um [guia](https://www.markdownguide.org/) com mais detalhes mas, basicamente, segue abaixo uma pequena legenda.

```markdown
# texto 1 (maior prioridade)
## texto 2
### texto 3 
#### texto 4 
##### texto 5 
###### texto 6 (menor prioridade)

**negrito**
__itálico__

> citação

`código inline`
código em bloco (``` código aqui ```)

--- linha divisória

1. lista
2. com
3. ordem

- lista
- sem
- ordem

[link](url)

![texto alternativo de imagem](url da imagem)
```

Esse arquivo tem como objetivo explicar mais sobre o projeto, seus objetivos, tecnologias utilizadas, entre outros. É um convite ao leitor a conhecer melhor o que foi desenvolvido e é uma excelente prática criar um e escrever sumarizadamente do que se trata o código guardado naquele repositório.

Há algumas boas práticas envolvendo a escrita de um README, como colocar título e descrição, um índice para facilitar a navegação no arquivo, o status (se está em desenvolvimento ou não), pré-requisitos para rodar, tecnologias usadas, o desenvolvedor e a licença, que é outro arquivo que pode ser inserido, sendo comumente utilizada a MIT License.

Recomendo esse artigo da [Rocketseat](https://blog.rocketseat.com.br/como-fazer-um-bom-readme/) que traz outros itens opcionais e exemplos.

## Ignorando arquivos: .gitignore

Esse arquivo (que não possui nome, apenas a extensão .gitignore) possui a finalidade de não deixar determinadas pastas e arquivos serem enviadas ao GitHub. Mas por quê? Algumas ferramentas servem apenas para o desenvolvimento e podem tornar o projeto pesado para quem puxá-lo. 

O próprio GitHub oferece templates baseados em padrões comuns de projeto. Porém, você pode criar o seu próprio ignorador.

Para escrever os arquivos que serão ignorados, você pode ignorar:

- Pastas (exemplo: /node_modules)
- Extensões de arquivos
- O próprio nome do arquivo

Ainda é possível utilizar asteriscos e pontuações para facilitar. Por exemplo: 

- *.log (todos os arquivos com essa extensão)
- **/logs (pasta com esse nome em qualquer lugar do repositório)
- !important.log (esse arquivo não será ignorado, é uma exceção)

Há vários outras formas, por isso sugiro este [artigo](https://www.atlassian.com/br/git/tutorials/saving-changes/gitignore). 


## Conclusão

Há dois arquivos comumente utilizados em repositórios: o **README**, responsável por explicar o projeto, e o **.gitignore**, que ignora arquivos desnecessários. Agora, sinta-se à vontade para testá-los em suas aplicações códigos. Há mais tipos de arquivos para configuração, mas esses ficam para um próximo artigo. 

*Feito por [Valentina Corradini Prado](https://github.com/valencprado).*



