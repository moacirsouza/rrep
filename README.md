# R.R.E.P.: Regras para Registros de Evolução de Projetos 

Ultimamente eu comecei a gerar um formato para registar as evoluções dos cursos
e/ou projetos que andei criando e acredito ter chegado a um ponto "ótimo".

Então, para evitar ficar repetindo o mesmo conjunto de informações em cada novo
repositório que seguir esta linha, decidi centralizar as regras neste projeto e
fazer referência a ele de agora em diante.

## Regras

O histórico é mantido em uma tabela como esta:

| Tópico | Subtópico | Data |
|--------|:---------:|------|
| página xx | - | dd/mm/aaaa | 

E as entradas seguem as seguintes regras:

1. **Tópico**: Registra as Seções principais de conteúdo para as quais eu devo
seguir na **PRÓXIMA ITERAÇÃO**. No caso deste projeto, refere-se ao título de
cada uma das páginas do tutorial, grafados exatamente como o autor os criou.
Cada Tópico também é uma URL que aponta para o conteúdo em questão. Exemplo(s):
   1. Se durante os estudos do dia `01/01/1901` a `página 01` for completamente
   finalizada, a tabela mostratá o seguinte:

   | Tópico | Subtópico | Data |
   |--------|:---------:|------|
   | página 02 | - | 01/01/1901 | 

2. **Subtópico**: Faz um registro similar ao Tópico, mas só mostrará uma URL
quando o assunto de uma página não for completamente exaurido. Para todos os
outros casos, ou seja, quando ainda houver Subtópico(s) para finalizar, será
usado um hífen (-). Exemplo(s):
   1. Se a `página 03` tiver os Subtópicos `sub 01`, `sub 02` e
   `sub 03` e a interação atual finalizar o `sub 01` no dia `01/01/1910`, a
   tabela mostrará o seguinte:

   | Tópico | Subtópico | Data |
   |--------|:---------:|------|
   | página 03 | sub 02 | 01/01/1910 | 

   2. Se a `página 05` tiver três Subtópicos e todos eles forem
   concluídos durante a iteração do dia `10/10/1970`,  a tabela mostrará
   o seguinte:

   | Tópico | Subtópico | Data |
   |--------|:---------:|------|
   | página 06 | - | 10/10/1970 |

3. **Data**: Registra o dia em que estudei o Tópico e/ou Subtópico **ANTERIOR**
ao que está marcado na tabela. Apesar de parecer confuso, esta organização me
permite acessar imediatamente o próximo assunto, ao mesmo tempo que evita que
eu fique tentando "adivinhar" ou fixar a próxima data em que poderei retomar os
estudos. A data deve ser **SEMPRE** registrada usando o formato `dd/mm/aaaa`,
onde:
   1. `dd`: Representa o dia do mês, começando em `01` e podendo ir até `31`
   2. `mm`: Representa o mês do ano, começando em `01` (Janeiro) e indo até
   `12` (Dezembro)
   3. `aaaa`: Representa o ano
   4. **IMPORTANTE**: Os dias do mês e os meses do ano **SEMPRE** devem ser
   representados com dois dígitos, como a seguir: `01`, `23`, `30`, `31` _etc._
   Da mesma forma, o ano **SEMPRE** deve ser representado com quatro dígitos,
   como a seguir: `1920`, `1450`, `2099`
