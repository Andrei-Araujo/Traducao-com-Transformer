# Tradução com Transformer
Geração de rede neural tradutora a partir de modelo de Transformer, tendo como exemplo rede do tipo BERT.


## Execução

Para executar:

```
1. Baixar o arquivo notebook (extensão .ipynb)
2. Fazer upload desse arquivo para um diretório no Google Drive
3. Abrir o arquivo .ipynb com a ferramenta Google Colab
4. Executar as células de código
```
#### Observações:
- Recomendável executrar com ambiente de execução remoto (para execução mais rápida)
- Para executar todas as células de comando de uma única vez, pressionar ```Ctrl + F9```

## Possíveis alterações no modelamento da rede

#### Banco de Dados
Para a criação da rede, utilizou-se banco de dados previamente tokenizado. Assim, ao se utilizar outro banco de dados, deve-se incluir também código para manipulação de tokens (tanto tokenizer quanto detokenizer). Nesse caso, soluções aplicadas a redes BERT são válidas.

#### Hiperparâmetros
Além disso, utilizaram-se hiperparâmetros com valores não-ideais, com o intuito de agilizar a geração da rede de tradução. A fim de se obterem melhores resultados, esses valores devem ser alterados connforme literatura sobre modelo de Transformers sugere.



