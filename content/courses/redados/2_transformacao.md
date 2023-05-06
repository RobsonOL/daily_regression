---
date: "2023-05-05"
title: Transformação de Dados
type: book
weight: 40
---

Nesse módulo você vai aprender a:

- Importar dados com as funções `read_csv()` e `read_excel()`

- Filtrar observações com a função `filter()`

- Utilizar o operador pipe `|>`

- Selecionar variáveis com a função `select()`

- Ordenar o banco de dados com a função `arrange()`

- Criar novas variáveis com `mutate()`

- Agrupar dados por grupos com `group_by()`

- Sumarizar informações com `summarise()`


{{< icon name="book" pack="fas" >}} <a href="https://robsonol.github.io/workshop_r_ciencias_sociais/lecture/lecture2222">Slides - Transformações de Dados</a>

{{< icon name="pen" pack="fas" >}} <a href="https://robsonol.github.io/workshop_r_ciencias_sociais/lecture/lecture1#/title-slide">Atividade 2 - Transformação de Dados</a>

<!--more-->

{{< icon name="clock" pack="fas" >}} 2 a 3 horas

### Vídeo: Importando Dados (20:00)

{{< youtube lkuFWd8xxD0 >}}

### Vídeo: Filtrando observações com Filter

{{< youtube f8MCpkWG6oY >}}
 
## Quiz


{{< spoiler text="Qual função é utilizada para instalar novos pacotes?" >}}

`install.packages()`

{{< /spoiler >}}


{{< spoiler text="Qual função posso utilizar para importar arquivos RDS?" >}}

`read_rds()`

{{< /spoiler >}}

{{< spoiler text="Como posso filtrar o banco de dados `mtcars` para carros com mpg maior que 20?" >}}

`mtcars |> filter(mpg > 20)`
{{< /spoiler >}}

