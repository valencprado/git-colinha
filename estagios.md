# Estágios dos Arquivos no Git: o ciclo dos arquivos

![Estágios](https://miro.medium.com/v2/resize:fit:720/format:webp/1*tl3B9CRamhIw54usIfXubw.png)

Entrando em uma parte mais conceitual, porém bastante importante de ser compreendida, temos os estados dos arquivos dentro de um repositório. Seguindo o diagrama acima, os arquivos "se sentem" de várias formas.

## Não rastreado (untracked)

Ao criar um arquivo novo em um repositório, ele começa como **não-rastreado**. O Git sabe que ele existe, mas não o monitora. para começar a manutenção, é necessário adicionar usando o `git add`. Assim, ele entra em outro estágio: o **staged**. 

Outra forma de um arquivo ficar nessa situação é quando ele já estava no repositório e foi excluído. O Git considera exclusões dessa forma, e você tem que adicionar como se fosse um arquivo novo. 

## Sem modificações (unmodified)

Depois que o commit é enviado ou se o arquivo já está sendo monitorado, mas não sofreu alterações, ele é considerado dessa forma. Ou seja, ele está pronto para futuras alterações.

## Modificado (modified)

Agora sim! Após alterar um arquivo, colocar uma feature nova ou algo do tipo, ele precisa novamente ser adicionado para ser commitado.

## Staged (esperando para entrar em cena!)

Imagine que seu repositório é uma peça de teatro e os arquivos são seus atores. Antes de eles entrarem em cena, é preciso que se arrumem, passem por maquiagem etc. Essa "coxia" é o staged: ele está pronto para entrar, ou seja, preparado para ser commitado. Sendo assim, após commitar, você pode empurrar essas alterações para brilharem no palco! E então, os arquivos estão sem modificações para serem enviados e prontos para mais códigos acontecerm. 

Fonte da imagem: [Medium](https://medium.com/opendev-blog/the-three-stages-of-git-16565bfa67e5)

*Feito por [Valentina Corradini Prado](https://github.com/valencprado).*
