# Analisando histórico: o poder do git log

Se você já está utilizando o Git, mesmo que de forma tímida, é provável que já tenha se perguntado: "como posso ver o que já fiz?". Para isso, existe o **git log**, que exibe todos os commits realizados.

```
git log
```

Porém, este comando pode se tornar extremamente poderoso utilizando os **parâmetros** que ele disponibiliza.

## Informações em uma linha

Para resumir as informações do commit de forma que ocupe apenas uma linha, é necessário utilizar o parâmetro --oneline.

```
git log --oneline
```

## E mais informações?

Nesse caso, utiliza-se o **-p**. Até mesmo as linhas de código são exibidas!

```
git log -p
```

## Vendo o fluxo 

Para ver os commits numa espécie de grafo/gráfico, pensando até mesmo nas branches do repositório (tudo bem caso você não saiba ainda o que é, veremos isso em breve). 

```
git log --graph
```

## Identificando por autor ou por época

Quer ver os commits de alguém específico ou de determinado momento? Esses são os comandos que você pode utilizar.

```
git log --author="user_name"
```

```
git log --since=1.week.ago --until=1.day.ago
```


## Mais embelezações? 💅

Para uma infinidade de variações e especificações, existe o parâmetro --pretty, que recebe valores. Seriam formatações mais específicas. [aqui](https://devhints.io/git-log-format) possui mais detalhes do uso. 

```
git log --pretty=":%H"
```

## Conclusão

Quem diria que haveria tantas possibilidades para mostrar o histórico de commits? É claro que algumas acabam ficando mais conhecidas por sua facilidade e constante necessidade, mas todos os comandos podem ser úteis um dia. Por isso, deixo como recomendação esse [link](https://devhints.io/git-log) com mais comandos e detalhes sobre o _git log_.

*Feito por [Valentina Corradini Prado](https://github.com/valencprado).*
