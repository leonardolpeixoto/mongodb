# MongoDB

## Primeiros passos

+ Subir o container com o MongoDB
+ Copiar o arquivo **megasena.csv** para dentro do container
+ Importar o csv copiado para dentro do Mongo.

## Inserindo Dados
```js
concurso = {
    "Concurso" : 99999,
    "Data Sorteio" : "11/11/2019",
    "1ª Dezena" : 1,
    "2ª Dezena" : 2,
    "3ª Dezena" : 3,
    "4ª Dezena" : 4,
    "5ª Dezena" : 5,
    "6ª Dezena" : 6,
    "Arrecadacao_Total" : 0,
    "Ganhadores_Sena" : 0,
    "Rateio_Sena" : 0,
    "Ganhadores_Quina" : 1,
    "Rateio_Quina" : "88000",
    "Ganhadores_Quadra" : 55,
    "Rateio_Quadra" : "76200",
    "Acumulado" : "NAO",
    "Valor_Acumulado" : 0,
    "Estimativa_Prêmio" : 0,
    "Acumulado_Mega_da_Virada" : 0
}
```