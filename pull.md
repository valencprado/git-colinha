# Pegando alterações: Pull e Pull Request

Já aprendemos que devemos empurrar (push) as nossas alterações para o repositório remoto. Mas e quando estamos trabalhando em equipe e um colega fez alterações? Pode ser que teremos erros ao tentar fazer um commit. O motivo é simples: para adicionar novas alterações, precisamos que nosso repositório local esteja igual ao remoto e, se alguém enviou alterações novas, os repositórios estarão diferentes. Para resolver essa questão, temos um comando: o `pull`.

## Pull

O pull é o contrário de push: ao invés de empurrar nossos commits, estamos **puxando** alterações que não temos no repositório local. Podemos fazer um pull quando:

- sempre que for começar a codar em um projeto em grupo
- você fez alterações no repositório via GitHub (exemplo: adicionar um README)
- um colega seu avisar que fez alterações novas

Você não precisa fazer pull várias vezes caso esteja trabalhando sozinho e não tenha mexido no repositório remoto. É um comando mais utilizado em repositórios compartilhados, então será mais comum utilizá-lo em trabalhos para a faculdade/escola ou no próprio trabalho.

O comando é assim:
> `git pull [<options>] [<repository>] `
Sendo que as opções nem sempre são utilizadas, o principal é o repositório remoto ou a origem remota (exemplo: git pull origin), mas se possuir apenas um repositório remoto, utilizar apenas `git pull` já funciona perfeitamente. Mais detalhes sobre podem ser encontrados [aqui](https://git-scm.com/docs/git-pull) na documentação.

## Pull Request: um pull elaborado

"Mas então, se o pull já puxa as alterações novas, o que esse tal de Pull Request faz?" Digamos que ele é um pull um pouco mais "elaborado". Uma das diferenças dele para o pull é que ele ocorre no GitHub, enquanto o outro é pelo Git Bash ou por outra ferramenta mais visual do Git.

Em suma, o pull request funciona também como uma ferramenta de comparação. Podemos comparar branches (a mais comum), tags e até forks (explicados [aqui](./fork.md)). A ideia é ver as alterações feitas e uma outra pessoa avaliar essas novidades, aceitando ou não o pull. Se for aceito, o pull request pode ser **mergeado** (algo que falaremos no próximo artigo) e as alterações estarão na branch principal. 

 Por meio dessa tecnologia, é possível contribuir com projetos open-source (e projetos em que você não possui a permissão de empurrar alterações diretamente na main) ou simplesmente organizar a entrada de novos códigos no projeto. É possível revisá-lo, verificar se ele está escrito da melhor forma possível e também sugerir possíveis alterações. Essa prática também pode gerar discussões e insights positivos para o projeto. É algo que se tornou praticamente "obrigatório"

Provavelmente, você não vai utilizar essa ferramenta se trabalhar sozinho. Porém, pode ser extremamente útil nos mesmos contextos do pull. Porém, dessa vez, é importante que você crie uma branch separada para gerar novas alterações por uma questão de organização. Não há comandos para realizar pull requests, mas deixo esse [vídeo](https://youtu.be/Du04jBWrv4A?si=mSGKixD0oS9ryb-q) caso tenham ficado dúvidas. Sempre há vários conteúdos sobre em toda parte!

## Conclusão

Agora, podemos sempre estar a par das alterações do repositório remoto! Basta fazer um `git pull` (a depender do projeto) e pronto, você poderá trabalhar na versão mais atualizada do seu projeto, sem dores de cabeça na hora de fazer o push. Também vimos um pouco sobre o Pull Request, uma maneira de colaborar de forma mais organizada com a possibilidade de suas alterações serem revisadas e uma "gourmetização" do pull. 

*Feito por [Valentina Corradini Prado](https://github.com/valencprado).*