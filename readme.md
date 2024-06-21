Teste técnico - Engenharia de Dados

### Instruções
1.  Clone este repositório.
2.  Resolva as questões propostas.
    1. As questões devem ser respondidas em arquivos separados.
    2. Você deve utilizar PySpark para resolver as questões.
    3. Os arquivos gerados devem ser salvos no diretório `outputs` dentro da pasta relativa ao número da questão.
3. Envie o link do seu repositório para o e-mail: selecao@operdata.com.br até às 12h do dia 24/06/2024


### Questão 1

_Disclaimer: Salve o resultado de cada análise em um formato de arquivo de sua preferência._ 

**Descrição:** 
Dado o arquivo `base_copa2018.csv`, crie um notebook que responda às seguintes questões.

1. Precisamos saber algumas informações:
    1. Qual é a média de altura de cada seleção? Qual é a seleção mais alta e a mais baixa?
    2. Qual é a média de peso de cada seleção? Qual é a seleção mais pesada e a mais leve?
    3. Qual é a media de idade de clube?
    4. Qual clube tem o jogador com IMC (Índice de massa corporal) mais alto da competição?
    5. Qual clube tem o jogador com IMC (Índice de massa corporal) mais baixo da competição?
    6. Qual é o jogador mais velho da competição?
    7. Qual é o jogador mais novo da competição?
    8. Qual é o clube com mais jogadores na competição?
    9. Monte um time com os jogadores mais altos da competição, respeitando a quantidade de jogadores por posição (1 goleiro, 4 defensores, 4 meio-campistas e 2 atacantes).
    10. Monte um time com os jogadores mais pesados da competição, respeitando a quantidade de jogadores por posição (1 goleiro, 4 defensores, 4 meio-campistas e 2 atacantes).


### Questão 2

_Disclaimer: Essa questão pode ter um nível de complexidade elevado em relação à anterior, portanto, recomenda-se que tente resolvê-la só quando as outras estiverem concluídas._ 

**Descrição:** 

Dado o arquivo `base_desafio.json`, faça uma limpeza e transformação dos dados, de forma que seja possível identificar em formato de tabela os dados de cada um dos itens do array "items".

Após isso, aplique uma transformação no nome das colunas para que elas sigam o padrão snake_case. As colunas que começam com números devem ter o número e possível pontuação, convertidos para "etapa". Por exemplo, a coluna "1. item" deve ser transformada para "etapa_item". As colunas de etapas devem ser convertidas para o tipo booleano.

Por fim, separe os dados em dataframes que você achar que fazem sentido e salve-os em um formato de arquivo otimizado.